#### Test 506502789b39735_thali05_samsung-SM-N9005 Logs


```
--------- beginning of main
E/SMD     (  293): DCD ON
,D/AndroidRuntime( 7081): 
D/AndroidRuntime( 7081): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7081): CheckJNI is OFF
D/AndroidRuntime( 7081): readGMSProperty: start
D/AndroidRuntime( 7081): readGMSProperty: already setted!!
D/AndroidRuntime( 7081): readGMSProperty: end
D/AndroidRuntime( 7081): addProductProperty: start
E/AffinityControl( 7081): AffinityControl: registerfunction enter
D/AndroidRuntime( 7081): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  879): inState():  stateMachine is null !!
I/PersonaManagerService(  879): PersonaId don't exist
I/ActivityManager(  879): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  879): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
I/ActivityManager(  879): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  879): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager(  879): mDVFSHelper.acquire()
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  879): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7096 uid=10294 gids={50294, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/PointerIcon(  879): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  879): setMouseCustomIcon IconType is same.101
D/PointerIcon(  879): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  879): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7081): Shutting down VM
E/Zygote  ( 7096): MountEmulatedStorage()
E/Zygote  ( 7096): v2
I/libpersona( 7096): KNOX_SDCARD checking this for 10294
I/libpersona( 7096): KNOX_SDCARD not a persona
I/SELinux ( 7096): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7096): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7096): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7096): TimaSignature is unavailable
D/ActivityThread( 7096): Added TimaKeyStore provider
D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SurfaceFlinger(  254): id=11 Removed YUIInstallC (5/8)
I/SurfaceFlinger(  254): id=11 Removed YUIInstallC (-2/8)
D/ResourcesManager( 7096): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
V/ActivityThread( 3407): updateVisibility : ActivityRecord{bb20794 token=android.os.BinderProxy@3e9c32a5 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
,I/WebViewFactory( 7096): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
D/ResourcesManager( 7096): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader( 7096): Loading: webviewchromium
I/LibraryLoader( 7096): Time to load native libraries: 6 ms (timestamps 246-252)
I/LibraryLoader( 7096): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7096): Binding Chromium to main looper Looper (main, tid 1) {7781bf0}
I/LibraryLoader( 7096): Expected native library version number "",actual native library version number ""
I/chromium( 7096): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7096): Initializing chromium process, renderers=0
W/art     ( 7096): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7096): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7096): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46780 len=2953
I/chromium( 7096): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229536 len:643667
I/Adreno-EGL( 7096): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 7096): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7096): Build Date: 11/19/14 Wed
I/Adreno-EGL( 7096): Local Branch: mybranch5813579
I/Adreno-EGL( 7096): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 7096): Local Patches: NONE
I/Adreno-EGL( 7096): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
W/chromium( 7096): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7096): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7096): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7096): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7096): CordovaWebView is running on device made by: samsung
W/art     ( 7096): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7096): Attempt to remove local handle scope entry from IRT, ignoring
D/Activity( 7096): performCreate Call secproduct feature valuefalse
D/Activity( 7096): performCreate Call debug elastic valuetrue
W/ActivityManager(  879): Activity pause timeout for ActivityRecord{7caafef u0 com.test.thalitest/.MainActivity t4}
D/OpenGLRenderer( 7096): Render dirty regions requested: true
D/Atlas   ( 7096): Validating map...
D/ActivityManager(  879): post active user change for 0
D/KnoxTimeoutHandler(  879): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  879): handleActiveUserChange for user 0
V/ActivityThread( 7096): updateVisibility : ActivityRecord{1cdb4ad9 token=android.os.BinderProxy@34305823 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
I/SurfaceFlinger(  254): id=14 createSurf (1x1),1 flag=404, NainActivit
D/StatusBarManagerService(  879): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  879): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon(  879): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  879): setMouseCustomIcon IconType is same.101
D/PointerIcon(  879): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  879): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer( 7096): Initialized EGL, version 1.4
I/OpenGLRenderer( 7096): HWUI protection enabled for context ,  &this =0xb3a5eab0 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 7096): Enabling debug mode 0
D/InputMethodManagerService(  879): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl(  879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/IInputConnectionWrapper( 7096): showStatusIcon on inactive InputConnection
I/Timeline( 7096): Timeline: Activity_idle id: android.os.BinderProxy@34305823 time:150638
W/ActivityManager(  879): mDVFSHelper.release()
I/Timeline(  879): Timeline: Activity_windows_visible id: ActivityRecord{7caafef u0 com.test.thalitest/.MainActivity t4} time:150643
W/ContextImpl(  879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/JsMessageQueue( 7096): Set native->JS mode to OnlineEventsBridgeMode
I/chromium( 7096): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7096): 
D/jxcore_app_log( 7096): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1356204416
D/JX-Cordova( 7096): jxcore cordova android initializing
,W/ContextImpl(  879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,W/jxcore-log( 7096): Initializing JXcore engine
,W/jxcore-log( 7096): JXcore engine is ready
,W/jxcore-log( 7096): Starting JXcore engine
,E/auditd  ( 1877): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  879): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  879): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,D/SecurityLogAgent( 6884):  SeDenialReceiver : Intent Received : android.intent.action.DENIAL_NOTIFICATION
D/SecurityLogAgent( 6884):  SeDenialReceiver : File path = null
,W/jxcore-log( 7096): Platform android
W/jxcore-log( 7096): 
,W/jxcore-log( 7096): Process ARCH arm
W/jxcore-log( 7096): 
,I/jxcore-log( 7096): JXcore Cordova bridge is ready!
I/jxcore-log( 7096): 
,W/jxcore-log( 7096): JXcore engine is started
,I/jxcore-log( 7096): Toggling radios to true
I/jxcore-log( 7096): 
,D/BluetoothAdapter( 7096): enable()
D/BluetoothAdapter( 7096): enable(): BT is already enabled..!
,I/WifiManager( 7096): packageName : com.test.thalitest
,D/SecContentProvider(  879): uri = 18 selection = isWifiEnabled
D/SecContentProvider2(  879): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  879): mCursor = null
,D/WifiService(  879): setWifiEnabled: true pid=7096, uid=10294
W/ActivityManager(  879): Permission Denial: getCurrentUser() from pid=7096, uid=10294 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  879): Failed getting userId using ActivityManagerNative
W/WifiService(  879): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7096, uid=10294 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  879): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23057)
W/WifiService(  879): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2181)
W/WifiService(  879): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2169)
W/WifiService(  879): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  879): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider(  879): name = wifi_on
,I/WifiService(  879): disconnect: pid=7096, uid=10294
,I/jxcore-log( 7096): Radios toggled
I/jxcore-log( 7096): 
,I/jxcore-log( 7096): Got Device Bluetooth address: E0:DB:10:1F:C9:5E
I/jxcore-log( 7096): 
,I/jxcore-log( 7096): Perf Test app loaded loaded
I/jxcore-log( 7096): 
,I/wpa_supplicant( 1276): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 7096): check test folder
I/jxcore-log( 7096): 
,I/jxcore-log( 7096): found test : ./testFindPeers.js
I/jxcore-log( 7096): 
,I/jxcore-log( 7096): found test : ./testSendData.js
I/jxcore-log( 7096): 
,I/wpa_supplicant( 1276): CTRL-EVENT-DISCONNECTED bssid=C0.AA.4A reason=3 locally_generated=1
,I/wpa_supplicant( 1276): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1276): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.4A SSID=4E473730303567
I/wpa_supplicant( 1276): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  879): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 1276): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1276): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1276): Disconnected - do not scan
I/wpa_supplicant( 1276): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiConfigStore(  879): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  879): do suspend true
,D/WifiP2pService(  879): InactiveState{ what=143375 }
,D/WifiP2pService(  879): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1187): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1187): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
,D/CommandListener(  287): Clearing all IP addresses on wlan0
,E/WifiConfigStore(  879): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/ConnectivityService(  879): updateNetworkInfo()
,I/WifiTrafficPoller(  879): evaluateTrafficStatsPolling
,D/ConnectivityService(  879): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  879): updateNetworkInfo()
D/ConnectivityService(  879): ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
D/ConnectivityService(  879): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
D/NetUtils(  879): android_net_utils_resetConnections in env=0xad5f75f0 clazz=0x9cbf798c iface=wlan0 mask=0x3
V/NativeCrypto( 1943): Read error: ssl=0x9b733e00: I/O error during system call, Connection timed out
,D/StatusBar.NetworkController( 1187): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1187): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1187): refreshSignalCluster - setNWBoosterIndicators(false)
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,D/StatusBar.NetworkController( 1187): applyOpen
,V/NativeCrypto( 1943): SSL shutdown failed: ssl=0x9b733e00: I/O error during system call, Broken pipe
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,D/StatusBar.NetworkController( 1187): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1187): applyOpen
D/StatusBar.NetworkController( 1187): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1187): applyOpen
D/StatusBar.NetworkController( 1187): refreshSignalCluster - setNWBoosterIndicators(false)
,E/WifiStateMachine(  879): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1276): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1276): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1276): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1276): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1276): First Scan Start
,E/native  (  879): do suspend true
,D/StatusBar.NetworkController( 1187): applyOpen
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10015
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): ValidatedState{ when=0 what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): DefaultState{ when=0 what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,I/System.out(  879): (HTTPLog)-Static: isSBSettingEnabled false
,E/Zygote  ( 7179): MountEmulatedStorage()
E/Zygote  ( 7179): v2
I/libpersona( 7179): KNOX_SDCARD checking this for 10038
I/libpersona( 7179): KNOX_SDCARD not a persona
,I/qtaguid (  879): Tagging socket 379 with tag ffffffff00000000{4294967295,0} uid 10015, pid: 879, getuid(): 1000
,I/System.out(  879): (HTTPLog)-Static: isSBSettingEnabled false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): Validated
,I/wpa_supplicant( 1276): Scan requested (ret=0) - scan timeout 30 seconds
,I/ActivityManager(  879): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.samsung.myplace.WIFINotificationHandler: pid=7179 uid=10038 gids={50038, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,D/WifiP2pService(  879): InactiveState{ what=143375 }
,D/WifiP2pService(  879): P2pEnabledState{ what=143375 }
D/CommandListener(  287): Clearing all IP addresses on wlan0
I/WifiTrafficPoller(  879): evaluateTrafficStatsPolling
I/chromium( 7096): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/WifiNetworkAgent(  879): NetworkAgent: NetworkAgent channel lost
,D/SecContentProvider2(  879): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  879): mCursor = null
,D/SecContentProvider2(  879): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  879): mCursor = null
,I/SELinux ( 7179): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SELinux ( 7179): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1187): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1187): onWifiSignalChanged enabled=true enabledDesc:null
,E/SELinux ( 7179): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/StatusBar.NetworkController( 1187): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1187): onWifiSignalChanged enabled=true enabledDesc:null
,D/TimaKeyStoreProvider( 7179): TimaSignature is unavailable
,D/ActivityThread( 7179): Added TimaKeyStore provider
,I/chromium( 7096): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/ResourcesManager( 7179): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,W/ResourcesManager( 7179): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ConnectivityService(  879): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService(  879): calling update connectivity
D/ConnectivityService(  879):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/EntConnectivity(  879): Not allowed due to - mEnabled false
D/ConnectivityService(  879):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  879): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  879):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1187): CM callback handler got msg 524292
D/ConnectivityService(  879): sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,V/Nat464Xlat(  879): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): Disconnected - quitting
D/ConnectivityService(  879): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  879): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1420): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CSLegacyTypeTracker(  879): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  879): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,D/ConnectivityService(  879): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityManager.CallbackHandler( 2198): CM callback handler got msg 524292
,D/ConnectivityService(  879): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,V/NetworkStats(  879): updateIfacesLocked()
,V/NetworkStats(  879): performPollLocked(flags=0x1)
D/NtpTrustedTime(  879): currentTimeMillis() cache hit
D/SmartBondingService(  879): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  879): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  879): getSBEnabled() enabled =false
D/SmartBondingService(  879): getSBEnabled() enabled =false
D/SmartBondingService(  879): getSBEnabled() enabled =false
E/ConnectivityService(  879): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/Tethering(  879): MasterInitialState.processMessage what=3
,D/NetworkStatsFactory(  879): UpdateStatsForKnox
D/ConnectivityService(  879): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1187): getUpdateDataNetType(): 0
D/SmartBondingService(  879): getNetworkEnabled : wifi : true mobile : true
D/StatusBar.NetworkController( 1187): updateDataNetType()
D/StatusBar.NetworkController( 1187): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1187): updateLTEICONDataNetType:0
,D/NtpTrustedTime(  879): currentTimeMillis() cache hit
,D/NtpTrustedTime(  879): currentTimeMillis() cache hit
D/NtpTrustedTime(  879): currentTimeMillis() cache hit
V/NetworkStats(  879): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  879): currentTimeMillis() cache hit
,V/NetworkStats(  879): performPollLocked() took 8ms
,D/NtpTrustedTime(  879): currentTimeMillis() cache hit
,D/NtpTrustedTime(  879): currentTimeMillis() cache hit
D/NtpTrustedTime(  879): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1187): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1187): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1187): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1187): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1187): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1187): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1187): applyOpen
D/StatusBar.NetworkController( 1187): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1187): applyOpen
D/StatusBar.NetworkController( 1187): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1187): applyOpen
D/StatusBar.NetworkController( 1187): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1187): applyOpen
,D/FileWriteThread_Telephony( 1420): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1420): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1420): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1420): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1420): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1420): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1420): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1420): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1420): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1420): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1420): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1420): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1420): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1420): FileWriteThread : threadType = 3
,I/VlingoApplication( 7179): VlingoApplication appVersion ='11.2.2.0.37649', ro.csc.sales_code=XEO
,E/BluetoothHeadset( 7179): BTStateChangeCB is registed
,E/BluetoothHeadset( 7179): BluetoothHeadset service is binded
,I/ActivityManager(  879): Killing 6321:com.google.android.partnersetup/u0a19 (adj 15): bgCount ##41
,I/Hs20UtilService( 1304): Starting #6
,I/Hs20UtilService( 1304): Message received 5007
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
,D/SettingsProvider(  879): name = driving_mode_on
D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SettingsProvider(  879): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  879): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  879): selectionArgs: false
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/SettingsProvider(  879): selectionArgs: 10038
D/SecContentProvider(  879): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  879): ret = -1
D/ConnectivityService(  879): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Set preference state off
D/BluetoothManager( 7179): [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.media.ACTION_SCO_AUDIO_STATE_UPDATED
,V/NearbySettings( 1304): MountReceiver.mPrefHandler - 7002
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6641): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 1304): Starting #7
,I/Hs20UtilService( 1304): Message received 5007
D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1304): MountReceiver.mPrefHandler - 7002
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6641): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  879): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  879): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  879): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
I/ApplicationPolicy(  879): updateDataUsageMap
D/SmartBondingService(  879): getSBEnabled() enabled =false
D/SmartBondingService(  879): getSBEnabled() enabled =false
D/SmartBondingService(  879): getSBEnabled() enabled =false
D/GpsLocationProvider(  879): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  879): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3407): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/NetworkMonitor( 5645): type=WIFI subType= reason=null isConnected=false
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PCWCLIENTTRACE_PushUtil( 6356): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6356): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6356): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6356): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6356): noConnectivity : true
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3407): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7231): MountEmulatedStorage()
E/Zygote  ( 7231): v2
I/libpersona( 7231): KNOX_SDCARD checking this for 10004
I/libpersona( 7231): KNOX_SDCARD not a persona
,I/ActivityManager(  879): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7231 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7231): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7231): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7231): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7231): TimaSignature is unavailable
,D/ActivityThread( 7231): Added TimaKeyStore provider
,D/ResourcesManager( 7231): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager(  879): Killing 6339:com.samsung.groupcast/u0a20 (adj 15): bgCount ##41
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,E/SMD     (  293): DCD ON
,I/ActivityManager(  879): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7249 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/Zygote  ( 7249): MountEmulatedStorage()
E/Zygote  ( 7249): v2
I/libpersona( 7249): KNOX_SDCARD checking this for 1000
I/libpersona( 7249): KNOX_SDCARD not a persona
,I/SELinux ( 7249): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7249): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7249): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7249): TimaSignature is unavailable
,D/ActivityThread( 7249): Added TimaKeyStore provider
,D/ResourcesManager( 7249): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT( 7249): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7249): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT( 7249): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/wpa_supplicant( 1276): nl80211: Received scan results (12 BSSes)
,I/DIAGMON_AGENT( 7249): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
I/wpa_supplicant( 1276): wlan0: Setting scan request: 8 sec 0 usec
,I/DIAGMON_AGENT( 7249): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT( 7249): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
I/wpa_supplicant( 1276): Trying to associate with C0.AA.4A (SSID='4E473730303567' freq=5220 MHz)
I/wpa_supplicant( 1276): wlan0: State: SCANNING -> ASSOCIATING
,I/wpa_supplicant( 1276): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E473730303567
,D/SecContentProvider2(  879): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  879): mCursor = null
,I/wpa_supplicant( 1276): wlan0: State: ASSOCIATING -> ASSOCIATED
,I/wpa_supplicant( 1276): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E473730303567
,I/wpa_supplicant( 1276): Associated with C0.AA.4A
,D/SecContentProvider2(  879): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  879): mCursor = null
,I/wpa_supplicant( 1276): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1276): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.4A SSID=4E473730303567
,D/SecContentProvider2(  879): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  879): mCursor = null
,I/wpa_supplicant( 1276): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1276): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1276): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.4A SSID=4E473730303567
,I/FOTA_Client( 6724): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/wpa_supplicant( 1276): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1276): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,I/wpa_supplicant( 1276): CTRL-EVENT-CONNECTED - Connection to C0.AA.4A completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 1276): Blacklist: Clear (temp) 
I/wpa_supplicant( 1276): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.4A SSID=4E473730303567
,I/FOTA_Client( 6724): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,D/WifiNative-HAL(  879): callSECApiVoid - ID [50]
,D/StatusBar.NetworkController( 1187): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1187): onWifiSignalChanged enabled=true enabledDesc:null
,D/ConnectivityService(  879): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  879): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  879): Got NetworkAgent Messenger
D/ConnectivityService(  879): hsengiv:checkWhatTypeOfNetwork and the value is false
D/ConnectivityService(  879): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  879): updateNetworkInfo()
D/ConnectivityService(  879): NetworkAgent connected
,I/FOTA_Client( 6724): [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/WifiConfigStore(  879): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,I/KLMS-2.4.511: ( 6753): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.511: ( 6753): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450229683272
,I/KLMS-2.4.511: ( 6753): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/CommandListener(  287): Setting iface cfg
,I/KLMS-2.4.511: ( 6753): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
E/WifiStateMachine(  879): Start Dhcp Watchdog 2
,I/KLMS-2.4.511: ( 6753): StateImplV2(): networkChangeListener().END
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,D/SecContentProvider2(  879): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  879): mCursor = null
,E/Zygote  ( 7273): MountEmulatedStorage()
E/Zygote  ( 7273): v2
I/libpersona( 7273): KNOX_SDCARD checking this for 10036
I/libpersona( 7273): KNOX_SDCARD not a persona
,I/ActivityManager(  879): Start proc com.samsung.android.app.pinboard:tagService for broadcast com.samsung.android.app.pinboard/.service.TagReadyReceiver: pid=7273 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 5880:sstream.app/u0a25 (adj 15): bgCount ##41
,I/SELinux ( 7273): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7273): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7273): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  879): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,D/TimaKeyStoreProvider( 7273): TimaSignature is unavailable
,D/ActivityThread( 7273): Added TimaKeyStore provider
,D/ResourcesManager( 7273): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,W/ResourcesManager( 7273): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7273): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/native  (  879): do suspend false
,D/SecContentProvider2(  879): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  879): mCursor = null
,D/WifiP2pService(  879): InactiveState{ what=143375 }
,D/WifiP2pService(  879): P2pEnabledState{ what=143375 }
,E/Minikin ( 7273): addFont failed to create font /system/fonts/SamsungSans-light.ttf
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  879): Killing 5928:com.samsung.android.app.galaxyfinder/u0a39 (adj 15): bgCount ##41
,I/SO_AGENT( 6772): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 4874): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 6451): [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
,I/SA      ( 6451): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 6451): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,E/SPPClientService( 4874): [[SystemStateMonitorService]] No Active Internet
,I/SA      ( 6451): [SLFUCHKMGR] constructor called
,I/SA      ( 6451): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6451): [OR] == isSIMCardReady false ==
,I/SA      ( 6451): [SCU] == networkStateCheck == false
I/SA      ( 6451): [OR] onReceive END
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  879): stay LED for fully charged
D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,E/Zygote  ( 7290): MountEmulatedStorage()
E/Zygote  ( 7290): v2
I/libpersona( 7290): KNOX_SDCARD checking this for 10074
I/libpersona( 7290): KNOX_SDCARD not a persona
,I/SELinux ( 7290): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/ActivityManager(  879): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=7290 uid=10074 gids={50074, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 7290): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7290): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/MotionRecognitionService(  879): Plugged
I/MotionRecognitionService(  879): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,E/dhcpcd  ( 7297): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,I/dhcpcd  ( 7297): version 5.5.6 starting
D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,E/dhcpcd  ( 7297): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,D/TimaKeyStoreProvider( 7290): TimaSignature is unavailable
,D/ActivityThread( 7290): Added TimaKeyStore provider
,D/ResourcesManager( 7290): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/dhcpcd  ( 7297): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7297): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7297): if(wlan0) info get Success. (MAC : C0.AA.4A)
I/dhcpcd  ( 7297): bssid match
I/dhcpcd  ( 7297): wlan0: rebinding lease of 192.168.1.128
,I/sCloudBackupApp( 7290): sCloudBackupApp Version Info : 3.13.7.KK_APP
,I/SCloudBackupReceiver( 7290): Other Intent
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7316): MountEmulatedStorage()
,E/Zygote  ( 7316): v2
,I/libpersona( 7316): KNOX_SDCARD checking this for 1000
I/libpersona( 7316): KNOX_SDCARD not a persona
,I/ActivityManager(  879): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7316 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 6413:com.samsung.android.sdk.samsunglink/u0a48 (adj 15): bgCount ##41
,I/SELinux ( 7316): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7316): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7316): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7316): TimaSignature is unavailable
,D/ActivityThread( 7316): Added TimaKeyStore provider
,D/ResourcesManager( 7316): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7316): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro( 7316): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7316): premStatus:2
,I/KnoxUsageLogPro( 7316): isEulaShown : false
I/KnoxUsageLogPro( 7316): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7331): MountEmulatedStorage()
,E/Zygote  ( 7331): v2
I/libpersona( 7331): KNOX_SDCARD checking this for 10104
I/libpersona( 7331): KNOX_SDCARD not a persona
,I/ActivityManager(  879): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7331 uid=10104 gids={50104, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 5709:com.sec.android.gallery3d/u0a53 (adj 13): bgCount ##41
,I/dhcpcd  ( 7297): wlan0: acknowledged 192.168.1.128 from 192.168.1.1
,I/SELinux ( 7331): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7331): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7331): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/dhcpcd  ( 7297): wlan0: leased 192.168.1.128 for 86400 seconds
,D/ConnectivityService(  879): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,D/TimaKeyStoreProvider( 7331): TimaSignature is unavailable
,D/ActivityThread( 7331): Added TimaKeyStore provider
,D/ResourcesManager( 7331): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/SSRM:n  (  879): SIOP:: AP = 340, PST = 334, CUR = 450
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7359): MountEmulatedStorage()
,E/Zygote  ( 7359): v2
I/libpersona( 7359): KNOX_SDCARD checking this for 10146
I/libpersona( 7359): KNOX_SDCARD not a persona
,I/ActivityManager(  879): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7359 uid=10146 gids={50146, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  879): Killing 6510:com.sec.android.provider.badge/u0a92 (adj 13): bgCount ##41
,I/SELinux ( 7359): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7359): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7359): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7359): TimaSignature is unavailable
,D/ActivityThread( 7359): Added TimaKeyStore provider
,D/ResourcesManager( 7359): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7359): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7359): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7359): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7359): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/native  (  879): do suspend true
,D/WifiP2pService(  879): InactiveState{ what=143375 }
D/WifiP2pService(  879): P2pEnabledState{ what=143375 }
,D/ConnectivityService(  879): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,D/StatusBar.NetworkController( 1187): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1187): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine(  879): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG7005g"WPA_PSK
,E/WifiStateMachine(  879): VerifyingLinkState enter
,D/WifiNative-HAL(  879): callSECApiInt - ID [210]
,E/ConnectivityService(  879): updateNetworkInfo()
,D/ConnectivityService(  879): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService(  879): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine(  879): updateDnsLinkProperty: enter
D/WifiWatchdogStateMachine.DnsPinger(  879): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver(  879): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker(  879): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  879): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 1187): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1187): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine(  879): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,I/WifiTrafficPoller(  879): evaluateTrafficStatsPolling
,E/WifiStateMachine(  879): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/StatusBar.NetworkController( 1187): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1187): onWifiSignalChanged enabled=true enabledDesc:null
,I/WifiTrafficPoller(  879): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  879): mBoosterFLAG : 0
,I/WifiTrafficPoller(  879): current booster mode : FullMode
,D/WifiNative-HAL(  879): callSECApiVoid - ID [212]
,D/ConnectivityService(  879): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService(  879): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/StatusBar.NetworkController( 1187): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1187): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
D/StatusBar.NetworkController( 1187): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1187): applyOpen
D/StatusBar.NetworkController( 1187): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1187): applyOpen
D/StatusBar.NetworkController( 1187): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1187): applyOpen
D/StatusBar.NetworkController( 1187): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1187): applyOpen
,D/ConnectivityService(  879): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService(  879): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  879): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  879): updateSourceRoutes : add src route for:192.168.1.128
,V/        (  287): QcRouteController
,V/        (  287): QcRouteController
,V/        (  287): QcRouteController
,V/        (  287): QcRouteController
,V/        (  287): QcRouteController
,V/        (  287): QcRouteController
,V/        (  287): QcRouteController
,V/        (  287): QcRouteController
,I/WebViewFactory( 7359): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,D/ResourcesManager( 7359): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,D/ConnectivityService(  879): Setting Dns servers for network 503 to [/192.168.1.1]
,D/ConnectivityService(  879): LTETest block dns file not exists
,I/LibraryLoader( 7359): Loading: webviewchromium
,V/Nat464Xlat(  879): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/ConnectivityService(  879): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  879): calling update connectivity
,D/ConnectivityService(  879): ignoring duplicate network state non-change. WIFI, state = CONNECTING
E/ConnectivityService(  879): updateNetworkInfo()
D/ConnectivityService(  879): ignoring duplicate network state non-change. WIFI, state = CONNECTING
E/ConnectivityService(  879): updateNetworkInfo()
D/ConnectivityService(  879): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/EntConnectivity(  879): Not allowed due to - mEnabled false
D/ConnectivityService(  879): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  879): calling update connectivity
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): Connected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): Checking http://clients3.google.com/generate_204 on "NG7005g",
,I/System.out(  879): (HTTPLog)-Static: isSBSettingEnabled false
,D/ConnectivityService(  879): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  879):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  879):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  879):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  879):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/LibraryLoader( 7359): Time to load native libraries: 18 ms (timestamps 7415-7433)
,I/LibraryLoader( 7359): Expected native library version number "",actual native library version number ""
,D/ConnectivityService(  879): currentScore = 0, newScore = 60
D/ConnectivityService(  879):    accepting network in place of null
D/ConnectivityService(  879): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1420): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker(  879): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  879): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
,D/ConnectivityService(  879): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService(  879): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService(  879): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  879): getSBEnabled() enabled =false
D/SmartBondingService(  879): getSBEnabled() enabled =false
,V/NetworkStats(  879): updateIfacesLocked()
V/NetworkStats(  879): performPollLocked(flags=0x1)
D/NtpTrustedTime(  879): currentTimeMillis() cache hit
D/SmartBondingService(  879): getSBEnabled() enabled =false
D/Tethering(  879): MasterInitialState.processMessage what=3
,D/ConnectivityService(  879): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/NtpTrustedTime(  879): currentTimeMillis() cache hit
,D/NtpTrustedTime(  879): currentTimeMillis() cache hit
D/NtpTrustedTime(  879): currentTimeMillis() cache hit
V/NetworkStats(  879): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  879): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1187): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1187): updateDataNetType()
D/StatusBar.NetworkController( 1187): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1187): updateLTEICONDataNetType:0
,D/SmartBondingService(  879): getNetworkEnabled : wifi : true mobile : true
D/NetworkStatsFactory(  879): UpdateStatsForKnox
,D/EntConnectivity(  879): Not allowed due to - mEnabled false
D/ConnectivityService(  879): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/WebViewChromiumFactoryProvider( 7359): Binding Chromium to main looper Looper (main, tid 1) {eca3176}
,V/NetworkStats(  879): performPollLocked() took 8ms
D/NtpTrustedTime(  879): currentTimeMillis() cache hit
,D/ConnectivityService(  879): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  879): calling update connectivity
D/ConnectivityService(  879):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  879):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  879): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/StatusBar.NetworkController( 1187): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1187): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1187): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/ConnectivityManager.CallbackHandler( 1187): CM callback handler got msg 524290
D/StatusBar.NetworkController( 1187): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1187): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
D/StatusBar.NetworkController( 1187): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1187): applyOpen
D/StatusBar.NetworkController( 1187): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1187): applyOpen
,D/ConnectivityService(  879):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/StatusBar.NetworkController( 1187): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1187): applyOpen
D/StatusBar.NetworkController( 1187): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1187): applyOpen
D/ConnectivityService(  879): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/LibraryLoader( 7359): Expected native library version number "",actual native library version number ""
,D/ConnectivityManager.CallbackHandler( 2198): CM callback handler got msg 524290
,I/chromium( 7359): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,D/NtpTrustedTime(  879): currentTimeMillis() cache hit
D/NtpTrustedTime(  879): currentTimeMillis() cache hit
,I/BrowserStartupController( 7359): Initializing chromium process, renderers=0
,W/art     ( 7359): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7359): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7359): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46780 len=2953
I/chromium( 7359): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229536 len:643667
,I/System.out(  879): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,W/AudioManagerAndroid( 7359): Requires BLUETOOTH permission
,I/Adreno-EGL( 7359): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 7359): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7359): Build Date: 11/19/14 Wed
I/Adreno-EGL( 7359): Local Branch: mybranch5813579
I/Adreno-EGL( 7359): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 7359): Local Patches: NONE
I/Adreno-EGL( 7359): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 16 Dec 2015 01:34:44 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450229685095], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450229685076]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): Validated
,D/ConnectivityService(  879): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  879): rematching NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  879):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  879):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  879):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  879): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  879): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  879): calling update connectivity
D/ConnectivityService(  879):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  879):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  879): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1187): CM callback handler got msg 524290
,D/ConnectivityService(  879):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  879): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 2198): CM callback handler got msg 524290
,D/ConnectivityService(  879): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1187): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1187): updateDataNetType()
D/StatusBar.NetworkController( 1187): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1187): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1187): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1187): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1187): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1187): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1187): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
,I/NSApplication( 7359): Starting up...
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  879): Killing 6496:com.sec.android.app.soundalive/u0a64 (adj 15): bgCount ##41
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7456): MountEmulatedStorage()
E/Zygote  ( 7456): v2
I/libpersona( 7456): KNOX_SDCARD checking this for 10158
I/libpersona( 7456): KNOX_SDCARD not a persona
,I/SELinux ( 7456): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7456): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7456): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  879): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7456 uid=10158 gids={50158, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 7456): TimaSignature is unavailable
,D/ActivityThread( 7456): Added TimaKeyStore provider
,I/art     (  341): Explicit concurrent mark sweep GC freed 8770(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 659us total 25.130ms
,I/art     (  341): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 495us total 16.435ms
,D/ResourcesManager( 7456): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 7456): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     (  341): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 390us total 13.666ms
W/ResourcesManager( 7456): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 7456): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 7456): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7456): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7456): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7471): MountEmulatedStorage()
E/Zygote  ( 7471): v2
I/libpersona( 7471): KNOX_SDCARD checking this for 10186
I/libpersona( 7471): KNOX_SDCARD not a persona
,D/ConnectivityService(  879): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/SELinux ( 7471): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7471): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7471): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  879): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7471 uid=10186 gids={50186, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 5492:com.samsung.android.app.assistantmenu/1000 (adj 13): bgCount ##41
,D/GpsLocationProvider(  879): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  879): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  879): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  879): SmartBondingReceiver: wifi ap is not changed
D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  879): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  879): getSBEnabled() enabled =false
D/SmartBondingService(  879): getSBEnabled() enabled =false
D/SmartBondingService(  879): getSBEnabled() enabled =false
D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  879): getNetworkEnabled : wifi : true mobile : true
D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1932): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,W/ContextImpl( 1932): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5645): type=WIFI subType= reason=null isConnected=true
,I/DBG_DM  ( 3407): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3407): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 7471): TimaSignature is unavailable
,D/ActivityThread( 7471): Added TimaKeyStore provider
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7471): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7471): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7471): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7471): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7471): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7471): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/SMD     (  293): DCD ON
,I/art     (  879): Explicit concurrent mark sweep GC freed 77442(4MB) AllocSpace objects, 24(432KB) LOS objects, 17% free, 37MB/45MB, paused 1.379ms total 101.082ms
D/SecContentProvider2(  879): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  879): mCursor = null
,D/RCPManagerService(  879): exchangeData() failure , invalid userId
,D/RCPManagerService(  879): exchangeData() failure , invalid userId
,D/RCPManagerService(  879): exchangeData() failure , invalid userId
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7501): MountEmulatedStorage()
,E/Zygote  ( 7501): v2
I/libpersona( 7501): KNOX_SDCARD checking this for 10092
I/libpersona( 7501): KNOX_SDCARD not a persona
,D/RCPManagerService(  879): exchangeData() failure , invalid userId
I/SELinux ( 7501): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7501): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7501): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  879): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7501 uid=10092 gids={50092, 9997} abi=armeabi-v7a
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  879): exchangeData() failure , invalid userId
,D/RCPManagerService(  879): exchangeData() failure , invalid userId
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6884): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6884): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6884): StateMachine : Current State = 1
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6884): StateMachine : Changed Current State = 1
,I/ActivityManager(  879): Killing 6556:com.wsomacp/u0a29 (adj 13): bgCount ##41
,D/TimaKeyStoreProvider( 7501): TimaSignature is unavailable
,D/ActivityThread( 7501): Added TimaKeyStore provider
D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7518): MountEmulatedStorage()
E/Zygote  ( 7518): v2
I/libpersona( 7518): KNOX_SDCARD checking this for 10200
I/libpersona( 7518): KNOX_SDCARD not a persona
,I/ActivityManager(  879): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7518 uid=10200 gids={50200, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7518): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7518): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7518): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  879): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/TimaKeyStoreProvider( 7518): TimaSignature is unavailable
,D/ActivityThread( 7518): Added TimaKeyStore provider
,I/ActivityManager(  879): Killing 6539:com.google.android.apps.docs/u0a112 (adj 13): bgCount ##41
,D/ResourcesManager( 7501): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/BadgeProvider( 7501): onCreate
,D/BadgeProvider( 7501): DatabaseHelper
,D/ResourcesManager( 7518): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,D/BadgeProvider( 7501): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ActivityManager(  879): Killing 6585:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##41
,D/Launcher.Model( 1438): reloadBadges entered.
,D/BadgeProvider( 7501): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7501): sendNotify, [notify] : null
D/BadgeProvider( 7501): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7501): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7501): update, [UpdateCount] : 1
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 5222): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5222): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 5222): exit::IDLE
D/InitializeManagerStateMachine( 5222): entry::NETWORK_CHECK
D/ConnectivityService(  879): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 5222): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5222): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5222): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5222): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5222): exit::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 5222): entry::SUCCESS
D/hcjo    ( 5222): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5222): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5222): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 5222): exit::SUCCESS
D/InitializeManagerStateMachine( 5222): entry::IDLE
,W/ActivityManager(  879): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/Hs20UtilService( 1304): Starting #8
,I/Hs20UtilService( 1304): Message received 5007
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6641): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 1304): Starting #9
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1304): Message received 5007
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6641): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 1304): Starting #10
,I/Hs20UtilService( 1304): Message received 5007
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6641): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 1304): Starting #11
,I/Hs20UtilService( 1304): Message received 5007
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine(  879): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6641): NETWORK_STATE_CHANGED_ACTION
,I/SurfaceFlinger(  254): id=15 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService(  879): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=879
,I/PCWCLIENTTRACE_PushUtil( 6356): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6356): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6356): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6356): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7249): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7249): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/FOTA_Client( 6724): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
I/FOTA_Client( 6724): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
I/FOTA_Client( 6724): [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
I/KLMS-2.4.511: ( 6753): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.4.511: ( 6753): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450229686610
I/KLMS-2.4.511: ( 6753): MainReciver(): NETWORK_STATE_CHANGED_ACTION
D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  879): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/KLMS-2.4.511: ( 6753): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
I/KLMS-2.4.511: ( 6753): StateImplV2(): networkChangeListener().START
I/KLMS-2.4.511: ( 6753): NetworkChangeOperations(): uploadRequestLog().START 
I/jxcore-log( 7096): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 7096): 
I/KLMS-2.4.511: ( 6753): StateImplV2(): networkChangeListener().END
D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SO_AGENT( 6772): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/SPPClientService( 4874): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
I/SA      ( 6451): [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
I/SA      ( 6451): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 6451): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 6451): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6451): [OR] == isSIMCardReady false ==
D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 6451): [SCU] == networkStateCheck == true
I/SA      ( 6451): [DM] getCountryCodeFromCSC : PL
I/SA      ( 6451): isChinaCountryCode : false
I/SA      ( 6451): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6451): [OR] == networkStateCheck true ==
I/SA      ( 6451): [OR] GetMyCountryZoneTask
I/SA      ( 6451): [OR] onReceive END
I/SA      ( 6451): [SRS] prepareGetMyCountryZone
D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 6451): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6451): [SSP] query invoked
I/SA      ( 6451): [TPMU] GetMccFromDB : null
I/SCloudBackupReceiver( 7290): Other Intent
I/SA      ( 6451): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6451): [TPM] isNoProxy(default) : true
I/KnoxUsageLogPro( 7316): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 7316): premStatus:2
I/KnoxUsageLogPro( 7316): isEulaShown : false
I/KnoxUsageLogPro( 7316): KnoxUsageReceiver onReceive : not Processible, just return
E/File    ( 6451): fail readDirectory() errno=2
D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/QuickConnect( 7456): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect( 7456): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 7456): PeriphStartReceiver.onReceive - no need to start
D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  879): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/RCPManagerService(  879): exchangeData() failure , invalid userId
D/RCPManagerService(  879): exchangeData() failure , invalid userId
D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 6884): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6884): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6884): StateMachine : Current State = 1
D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 6884): StateMachine : Changed Current State = 1
D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  879): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/hcjo    ( 5222): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 5222): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5222): exit::IDLE
D/InitializeManagerStateMachine( 5222): entry::NETWORK_CHECK
D/ConnectivityService(  879): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 5222): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5222): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5222): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5222): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5222): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5222): entry::SUCCESS
D/hcjo    ( 5222): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 5222): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 5222): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 5222): exit::SUCCESS
D/InitializeManagerStateMachine( 5222): entry::IDLE
I/ServiceManager(  352): Waiting for service AtCmdFwd...
,D/PackageManager(  879): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/SA      ( 6451): [RC New] Execute method=[GET] start
,I/SA      ( 6451): [RC New] Security=[true]
,I/System.out( 6451): Thread-1060(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6451): Thread-1060(ApacheHTTPLog):isShipBuild true
,I/System.out( 6451): Thread-1060(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,D/ConnectivityService(  879): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
,D/ConnectivityService(  879): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService(  879): identical MTU - not setting
,D/ConnectivityService(  879): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  879): updateSourceRoutes : add src route for:fe80::ea50:8bff:fede:28a3
,D/SmartBondingService(  879): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/        (  287): QcRouteController
,D/SmartBondingService(  879): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  879): getSBEnabled() enabled =false
D/SmartBondingService(  879): getSBEnabled() enabled =false
D/SmartBondingService(  879): getSBEnabled() enabled =false
,V/        (  287): QcRouteController
,W/NetworkManagementService(  879): route cmd failed: 
W/NetworkManagementService(  879): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '74 route replace src v6 wlan0 fe80::ea50:8bff:fede:28a3 2 ::' failed with '400 74 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  879): '
W/NetworkManagementService(  879): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService(  879): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService(  879): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService(  879): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService(  879): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  879): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5625)
W/NetworkManagementService(  879): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5437)
W/NetworkManagementService(  879): 	at com.android.server.ConnectivityService.access$2300(ConnectivityService.java:229)
W/NetworkManagementService(  879): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2382)
W/NetworkManagementService(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  879): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/Nat464Xlat(  879): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  879): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  879): calling update connectivity
,D/ConnectivityService(  879):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  879):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  879): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1187): CM callback handler got msg 524295
D/ConnectivityService(  879):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  879): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 2198): CM callback handler got msg 524295
D/ConnectivityService(  879): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  879): calling update connectivity
D/ConnectivityService(  879):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  879):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  879): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1187): CM callback handler got msg 524295
D/ConnectivityService(  879):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  879): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 2198): CM callback handler got msg 524295
,E/WifiStateMachine(  879): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/dhcpcd  ( 7297): wlan0: sending IPv6 Router Solicitation
,I/SA      ( 6451): [RC New] [v2liruge] api execute + 740
,I/SA      ( 6451): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6451): AsyncTask #1 calls detatch()
,I/SA      ( 6451): [TPMU] getNetworkMcc : 
,I/SA      ( 6451): [SCU] saveMccToPreferece Start
,I/SA      ( 6451): [SCU] RegionMCC : 260
I/SA      ( 6451): [SSP] query invoked
,I/SA      ( 6451): [TPMU] GetMccFromDB : null
,I/SA      ( 6451): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6451): [SCU] saveMccToPreferece End
,I/SA      ( 6451): [RC New] executeRequest [v2liruge] end. 820
,I/SA      ( 6451): [RC New] Execute end
,I/SA      ( 6451): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 6451): [OR] GetMyCountryZoneTask Success
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  879): [PWL] Off : 75s ago
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/GAV4    ( 7359): Thread[GAThread,5,main]: No campaign data found.
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SurfaceFlinger(  254): id=15 Removed Uoast (8/9)
,I/SurfaceFlinger(  254): id=15 Removed Uoast (-2/9)
,D/PowerManagerService(  879): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 879) eventTime = 162346
,D/PowerManagerService(  879): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=879 (0x0)
,D/PowerManagerService(  879): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=879, ws=WorkSource{10067}) (elapsedTime=3484)
,I/ClearcutLoggerApiImpl( 1943): disconnect managed GoogleApiClient
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  352): AtCmdFwd service not published, waiting... retryCnt : 4
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6356): mConnectivityHandler : connected
,D/ConnectivityService(  879): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 6356): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE( 6356): ================================================
,I/CSTORAGE( 6356):  CSTORAGE_SKM_LIB v1.0.6
I/CSTORAGE( 6356): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 6356): [GetString-S]
,E/art     ( 6356): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6356): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6356): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 6356): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6356): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6356): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 6356): [ensureRegistration] - No Samsung account
,E/SMD     (  293): DCD ON
,I/dhcpcd  ( 7297): wlan0: sending IPv6 Router Solicitation
,E/Watchdog(  879): !@Sync 5
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): stay LED for fully charged
D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/SSRM:n  (  879): SIOP:: AP = 320, PST = 327, CUR = 450
,E/SMD     (  293): DCD ON
,I/dhcpcd  ( 7297): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 7297): wlan0: no IPv6 Routers available
,D/PreloadUpdateManagerStateMachine( 5222): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5222): exit::IDLE
D/PreloadUpdateManagerStateMachine( 5222): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5222): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5222): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5222): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5222): entry::IDLE
,D/PreloadUpdateManagerStateMachine( 5222): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5222): exit::IDLE
D/PreloadUpdateManagerStateMachine( 5222): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5222): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5222): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5222): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5222): entry::IDLE
,E/SMD     (  293): DCD ON
,W/ContextImpl(  879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager(  879): waitForAlarm result :8
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,E/SMD     (  293): DCD ON
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryService(  879): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/SSRM:n  (  879): SIOP:: AP = 310, PST = 322, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,D/SSRM:n  (  879): SIOP:: AP = 300, PST = 316, CUR = 450
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,W/Atfwd_Sendcmd(  352): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  879): [PWL] Off : 105s ago
,W/ContextImpl(  879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,E/Watchdog(  879): !@Sync 6
,V/AlarmManager(  879): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1187): handleTimeUpdate
,D/KeyguardEffectViewController( 1187): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1187): *** don't update sliding image ***
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  879): stay LED for fully charged
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/DateView( 1187): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1187): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  (  879): SIOP:: AP = 310, PST = 314, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  879): SIOP:: AP = 300, PST = 312, CUR = 450
,E/SMD     (  293): DCD ON
,W/ContextImpl(  879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,I/Atfwd_Sendcmd(  352): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  352): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  879): SIOP:: AP = 300, PST = 310, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,E/Watchdog(  879): !@Sync 7
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): stay LED for fully charged
D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,I/PowerManagerService(  879): [PWL] Off : 140s ago
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,D/SSRM:n  (  879): SIOP:: AP = 300, PST = 309, CUR = 450
,E/SMD     (  293): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  352): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  293): DCD ON
,W/ContextImpl(  879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  879): waitForAlarm result :8
,E/SMD     (  293): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  879): Plugged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  879): setPowerConnected  = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
D/BatteryService(  879): stay LED for fully charged
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,D/SSRM:n  (  879): SIOP:: AP = 300, PST = 308, CUR = 450
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  352): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryService(  879): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/SSRM:n  (  879): SIOP:: AP = 300, PST = 308, CUR = 450
,E/SMD     (  293): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,W/ContextImpl(  879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  352): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  293): DCD ON
,E/Watchdog(  879): !@Sync 8
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/BatteryService(  879): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 290, PST = 303, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  879): [PWL] Off : 180s ago
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/BatteryService(  879): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/SSRM:n  (  879): SIOP:: AP = 290, PST = 300, CUR = 450
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,W/ContextImpl(  879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  352): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  879): Plugged
I/MotionRecognitionService(  879): setPowerConnected  = true
,D/BatteryService(  879): stay LED for fully charged
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  879): SIOP:: AP = 290, PST = 298, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  879): !@Sync 9
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/BatteryService(  879): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 290, PST = 297, CUR = 450
,E/SMD     (  293): DCD ON
,W/ContextImpl(  879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/BatteryService(  879): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  879): SIOP:: AP = 290, PST = 295, CUR = 450
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  352): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  879): Plugged
I/MotionRecognitionService(  879): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  879): stay LED for fully charged
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/SSRM:n  (  879): SIOP:: AP = 290, PST = 294, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  879): [PWL] Off : 225s ago
,W/ContextImpl(  879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService(  879): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  879): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  879): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  879): initializing...
,I/TLC_TIMA_PKM_initialize(  879): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  879): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  879): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  879): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication(  879): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication(  879): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  879): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: (  879): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  879): App is not loaded in QSEE
,D/QSEECOMAPI: (  879): Loaded image: APP id = 4
,I/TZ: qc_tlc_communication(  879): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  879): Trustlet response is completed
,E/SMD     (  293): DCD ON
,E/Watchdog(  879): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel(  879): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  879): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  879): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  879): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryService(  879): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 300, PST = 294, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,I/Atfwd_Sendcmd(  352): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  352): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 290, PST = 293, CUR = 450
,E/SMD     (  293): DCD ON
,W/ContextImpl(  879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,V/AlarmManager(  879): waitForAlarm result :4
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  879): stay LED for fully charged
,I/ActivityManager(  879): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=7592 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,E/Zygote  ( 7592): MountEmulatedStorage()
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1187): handleTimeUpdate
,E/Zygote  ( 7592): v2
I/libpersona( 7592): KNOX_SDCARD checking this for 10096
,I/libpersona( 7592): KNOX_SDCARD not a persona
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,I/SELinux ( 7592): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,D/KeyguardEffectViewController( 1187): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1187): *** don't update sliding image ***
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
I/SELinux ( 7592): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
E/SELinux ( 7592): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaKeyStoreProvider( 7592): TimaSignature is unavailable
,D/ActivityThread( 7592): Added TimaKeyStore provider
,D/DateView( 1187): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1187): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ResourcesManager( 7592): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,I/ActivityManager(  879): Killing 6605:com.samsung.android.app.watchmanagerstub/u0a126 (adj 13): bgCount ##41
,I/jxcore-log( 7096): Connected to the server!
I/jxcore-log( 7096): 
,I/chromium( 7096): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 290, PST = 292, CUR = 450
,E/SMD     (  293): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  879): Plugged
I/MotionRecognitionService(  879): setPowerConnected  = true
,D/BatteryService(  879): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,W/Atfwd_Sendcmd(  352): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  293): DCD ON
,E/Watchdog(  879): !@Sync 11
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 290, PST = 291, CUR = 450
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,W/ContextImpl(  879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,V/AlarmManager(  879): waitForAlarm result :8
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,W/Atfwd_Sendcmd(  352): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 290, PST = 291, CUR = 450
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  879): [PWL] Off : 275s ago
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,D/SSRM:n  (  879): SIOP:: AP = 290, PST = 291, CUR = 450
,E/SMD     (  293): DCD ON
,W/Atfwd_Sendcmd(  352): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  293): DCD ON
,W/ContextImpl(  879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/Watchdog(  879): !@Sync 12
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 290, PST = 291, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,D/SSRM:n  (  879): SIOP:: AP = 290, PST = 291, CUR = 450
,W/Atfwd_Sendcmd(  352): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  293): DCD ON
,W/ContextImpl(  879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  879): Plugged
I/MotionRecognitionService(  879): setPowerConnected  = true
,D/BatteryService(  879): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 290, PST = 291, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/Watchdog(  879): !@Sync 13
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 290, PST = 291, CUR = 450
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,W/ContextImpl(  879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
D/BatteryService(  879): stay LED for fully charged
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,W/Atfwd_Sendcmd(  352): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  879): [PWL] Off : 330s ago
,D/SSRM:n  (  879): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,W/ContextImpl(  879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/Watchdog(  879): !@Sync 14
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 290, PST = 290, CUR = 450
,I/Atfwd_Sendcmd(  352): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  352): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  293): DCD ON
,W/ContextImpl(  879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  293): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  352): AtCmdFwd service not published, waiting... retryCnt : 1
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): stay LED for fully charged
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,E/Watchdog(  879): !@Sync 15
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 290, PST = 290, CUR = 450
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,W/ContextImpl(  879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,W/Atfwd_Sendcmd(  352): AtCmdFwd service not published, waiting... retryCnt : 2
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  879): stay LED for fully charged
D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  879): Plugged
I/MotionRecognitionService(  879): setPowerConnected  = true
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  879): [PWL] Off : 390s ago
,D/SSRM:n  (  879): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/bootchecker(  345): bootchecker wake up!!
,E/SMD     (  293): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 290, PST = 290, CUR = 450
,W/Atfwd_Sendcmd(  352): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  293): DCD ON
,W/ContextImpl(  879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/Watchdog(  879): !@Sync 16
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,D/SSRM:n  (  879): SIOP:: AP = 290, PST = 290, CUR = 450
,W/Atfwd_Sendcmd(  352): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  293): DCD ON
,W/ContextImpl(  879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
E/SMD     (  293): DCD ON
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryService(  879): stay LED for fully charged
,E/Watchdog(  879): !@Sync 17
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 290, PST = 290, CUR = 450
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,W/ContextImpl(  879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,V/AlarmManager(  879): waitForAlarm result :8
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,W/Atfwd_Sendcmd(  352): AtCmdFwd service not published, waiting... retryCnt : 5
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 289, CUR = 450
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  879): [PWL] Off : 455s ago
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 288, CUR = 450
,E/SMD     (  293): DCD ON
,W/ContextImpl(  879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryService(  879): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  879): !@Sync 18
,E/SMD     (  293): DCD ON
,I/Atfwd_Sendcmd(  352): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  352): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 287, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 286, CUR = 450
,E/SMD     (  293): DCD ON
,W/ContextImpl(  879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 285, CUR = 450
,E/SMD     (  293): DCD ON
,I/Atfwd_Daemon(  352): Stop the daemon....
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/BatteryService(  879): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,E/Watchdog(  879): !@Sync 19
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 284, CUR = 450
,E/SMD     (  293): DCD ON
,W/ContextImpl(  879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/BatteryService(  879): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 283, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  879): Plugged
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/BatteryService(  879): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 282, CUR = 450
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  879): [PWL] Off : 525s ago
,W/ContextImpl(  879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService(  879): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  879): TimaServiceHandler.handleMessage what =1
,D/TimaService(  879): TIMA: checkEvent, operation: 50000 subject: 10000
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  879): stay LED for fully charged
D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,E/Watchdog(  879): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel(  879): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  879): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  879): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  879): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 290, PST = 282, CUR = 450,
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  879): stay LED for fully charged
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  293): DCD ON
,W/ContextImpl(  879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  879): Plugged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  879): setPowerConnected  = true
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  879): stay LED for fully charged
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ActivityManager(  879): Killing 6620:com.samsung.helphub/1000 (adj 13): bgCount ##41
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/BatteryService(  879): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,E/Watchdog(  879): !@Sync 21
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  879): Plugged
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/BatteryService(  879): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  879): !@Sync 22
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  879): [PWL] Off : 600s ago
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  879): Plugged
I/MotionRecognitionService(  879): setPowerConnected  = true
,D/BatteryService(  879): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/BatteryService(  879): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,E/Watchdog(  879): !@Sync 23
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  879): stay LED for fully charged
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,E/Watchdog(  879): !@Sync 24
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/BatteryService(  879): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  879): Plugged
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  879): setPowerConnected  = true
,E/Watchdog(  879): !@Sync 25
,D/BatteryService(  879): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  879): [PWL] Off : 680s ago
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  879): Plugged
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/BatteryService(  879): stay LED for fully charged
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  879): !@Sync 26
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/BatteryService(  879): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryService(  879): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/BatteryService(  879): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  879): !@Sync 27
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  879): Plugged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/BatteryService(  879): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  879): [PWL] Off : 765s ago
,E/SMD     (  293): DCD ON
,E/Watchdog(  879): !@Sync 28
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/BatteryService(  879): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  879): Plugged
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/BatteryService(  879): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2932): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  879): stay LED for fully charged
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  879): !@Sync 29
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/BatteryService(  879): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  879): Plugged
I/MotionRecognitionService(  879): setPowerConnected  = true
,D/BatteryService(  879): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  879): Plugged
I/MotionRecognitionService(  879): setPowerConnected  = true
,D/BatteryService(  879): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/TimaService(  879): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  879): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  879): TimaServiceHandler.handleMessage what =1
,E/SMD     (  293): DCD ON
,E/Watchdog(  879): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel(  879): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  879): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  879): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  879): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON,
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  879): Plugged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  879): stay LED for fully charged
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  879): Plugged
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/BatteryService(  879): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  879): [PWL] Off : 855s ago
,E/SMD     (  293): DCD ON
,E/Watchdog(  879): !@Sync 31
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  879): Plugged
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/BatteryService(  879): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryService(  879): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,I/MotionRecognitionService(  879): Plugged
I/MotionRecognitionService(  879): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  879): stay LED for fully charged
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  879): !@Sync 32
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/BatteryService(  879): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  879): Plugged
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/BatteryService(  879): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryService(  879): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  879): !@Sync 33
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/BatteryService(  879): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  879): Plugged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  879): setPowerConnected  = true
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  879): stay LED for fully charged
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  879): !@Sync 34
,I/PowerManagerService(  879): [PWL] Off : 950s ago
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  879): stay LED for fully charged
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  879): !@Sync 35
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0,
D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  879): stay LED for fully charged
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  879): Plugged
I/MotionRecognitionService(  879): setPowerConnected  = true
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  879): stay LED for fully charged
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  879): !@Sync 36
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  879): Plugged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  879): stay LED for fully charged
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  879): !@Sync 37
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0,
D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  879): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  879): [PWL] Off : 1050s ago
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  879): !@Sync 38
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  879): Plugged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  879): stay LED for fully charged
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  879): Plugged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  879): setPowerConnected  = true
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  879): stay LED for fully charged
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  879): stay LED for fully charged
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2932): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  879): !@Sync 39
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  879): stay LED for fully charged
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  879): Plugged
I/MotionRecognitionService(  879): setPowerConnected  = true
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  879): stay LED for fully charged
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,D/TimaService(  879): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  879): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  879): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService(  879): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  879): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  879): Updating Usage Statistics in DB @ 1450230741180
,I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
,W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  879): ::getAppControlDB: Exception to create DB
W/System.err(  879): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  879): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  879): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  879): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage(  879): Done Updating Usage Statistics in DB @ 1450230741381
,E/SMD     (  293): DCD ON
,E/Watchdog(  879): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel(  879): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  879): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  879): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  879): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  879): stay LED for fully charged
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  879): [PWL] Off : 1155s ago
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  879): !@Sync 41
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  879): stay LED for fully charged
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  879): Plugged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  879): setPowerConnected  = true
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  879): stay LED for fully charged
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  879): !@Sync 42
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  879): stay LED for fully charged
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  879): stay LED for fully charged
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  879): Plugged
I/MotionRecognitionService(  879): setPowerConnected  = true
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  879): stay LED for fully charged
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  879): !@Sync 43
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  879): Plugged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  879): setPowerConnected  = true
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  879): stay LED for fully charged
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  879): !@Sync 44
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  879): Plugged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  879): stay LED for fully charged
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2932): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  879): [PWL] Off : 1265s ago
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  879): Plugged
I/MotionRecognitionService(  879): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  879): stay LED for fully charged
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  879): !@Sync 45
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  879): Plugged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  879): setPowerConnected  = true
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  879): stay LED for fully charged
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  879): Plugged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  879): stay LED for fully charged
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2932): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  879): stay LED for fully charged
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  879): !@Sync 46
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  879): stay LED for fully charged
D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  879): stay LED for fully charged
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  879): !@Sync 47
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryService(  879): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  879): !@Sync 48
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/BatteryService(  879): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  879): [PWL] Off : 1380s ago
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
D/BatteryService(  879): stay LED for fully charged
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  879): !@Sync 49
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/TimaService(  879): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  879): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  879): TimaServiceHandler.handleMessage what =1
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  879): !@Sync 50
,I/TLC_TIMA_PKM_measure_kernel(  879): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  879): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  879): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  879): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  879): Plugged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  879): stay LED for fully charged
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  879): stay LED for fully charged
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  879): Plugged
I/MotionRecognitionService(  879): setPowerConnected  = true
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  879): stay LED for fully charged
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  879): !@Sync 51
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  879): stay LED for fully charged
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  879): Plugged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  879): setPowerConnected  = true
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  879): stay LED for fully charged
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0,
D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  879): Plugged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  879): setPowerConnected  = true
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  879): stay LED for fully charged
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  879): !@Sync 52
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,I/PowerManagerService(  879): [PWL] Off : 1500s ago
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  879): stay LED for fully charged
D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  879): stay LED for fully charged
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  879): !@Sync 53
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  879): Plugged
I/MotionRecognitionService(  879): setPowerConnected  = true
,D/BatteryService(  879): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/BatteryService(  879): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  879): !@Sync 54
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/BatteryService(  879): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/BatteryService(  879): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  879): stay LED for fully charged
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  879): !@Sync 55
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  879): Plugged
I/MotionRecognitionService(  879): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  879): stay LED for fully charged
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  879): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  879): Plugged
I/MotionRecognitionService(  879): setPowerConnected  = true
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2932): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  879): Plugged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  879): stay LED for fully charged
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  879): !@Sync 56
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  879): Plugged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
I/MotionRecognitionService(  879): setPowerConnected  = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  879): stay LED for fully charged
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService(  879): [PWL] Off : 1625s ago
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryService(  879): stay LED for fully charged
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  879): !@Sync 57
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  879): stay LED for fully charged
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  879): stay LED for fully charged
D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): stay LED for fully charged
D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  879): !@Sync 58
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  879): stay LED for fully charged
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  879): Plugged
I/MotionRecognitionService(  879): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  879): stay LED for fully charged
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  879): Plugged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  879): stay LED for fully charged
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  879): !@Sync 59
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  879): stay LED for fully charged
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  879): Plugged
I/MotionRecognitionService(  879): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/NetworkStatsFactory(  879): UpdateStatsForKnox
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
D/BatteryService(  879): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/TimaService(  879): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  879): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  879): TimaServiceHandler.handleMessage what =1
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,V/AlarmManager(  879): waitForAlarm result :4
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  879): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1187): handleTimeUpdate
,D/KeyguardEffectViewController( 1187): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1187): *** don't update sliding image ***
D/LightsService(  879): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  879): Light old sensor_state 0, new sensor_state : 512 en : 1
,I/ProcessStatsService(  879): Prepared write state in 16ms
,D/SensorManager(  879): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,I/ProcessStatsService(  879): Prepared write state in 19ms
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 2932): Disconnected process message: 10
V/NetworkStats(  879): performPollLocked(flags=0x3)
D/NtpTrustedTime(  879): currentTimeMillis() cache hit
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/NetworkStatsFactory(  879): UpdateStatsForKnox
,D/ConnectivityService(  879): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/MotionRecognitionService(  879): Plugged
I/MotionRecognitionService(  879): setPowerConnected  = true
,V/NetworkStats(  879): performPollLocked() took 12ms
,D/NtpTrustedTime(  879): currentTimeMillis() cache hit
,D/NtpTrustedTime(  879): currentTimeMillis() cache hit
D/NtpTrustedTime(  879): currentTimeMillis() cache hit
,D/DateView( 1187): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1187): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 2198): Aggregate from 1450229052422 (log), 1450229052422 (data)
,I/TLC_TIMA_PKM_measure_kernel(  879): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  879): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  879): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  879): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  879): !@Sync 60
,D/LightsService(  879): [SvcLED]  onSensorChanged::light value = 0
E/LightSensor(  879): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  879): unregisterListener ::   
D/LightsService(  879): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/ProcessStatsService(  879): Pruning old procstats: /data/system/procstats/state-2015-12-15-12-28-58.bin
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryService(  879): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  879): [PWL] Off : 1755s ago
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  879): Plugged
I/MotionRecognitionService(  879): setPowerConnected  = true
,D/BatteryService(  879): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  879): !@Sync 61
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,V/AlarmManager(  879): waitForAlarm result :8
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  879): Plugged
I/MotionRecognitionService(  879): setPowerConnected  = true
,D/BatteryService(  879): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/BatteryService(  879): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  879): !@Sync 62
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  879): Plugged
I/MotionRecognitionService(  879): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/BatteryService(  879): stay LED for fully charged
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/BatteryService(  879): stay LED for fully charged
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  879): !@Sync 63
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  879): stay LED for fully charged
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  879): stay LED for fully charged
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  879): Plugged
I/MotionRecognitionService(  879): setPowerConnected  = true
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  879): stay LED for fully charged
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  879): !@Sync 64
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  879): stay LED for fully charged
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  879): !@Sync 65
,D/SSRM:n  (  879): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  879): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  879): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  879): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  879): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  879): Plugged
,I/MotionRecognitionService(  879): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2932): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryService(  879): stay LED for fully charged
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 7745): 
D/AndroidRuntime( 7745): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7745): CheckJNI is OFF
D/AndroidRuntime( 7745): readGMSProperty: start
D/AndroidRuntime( 7745): readGMSProperty: already setted!!
D/AndroidRuntime( 7745): readGMSProperty: end
D/AndroidRuntime( 7745): addProductProperty: start
E/AffinityControl( 7745): AffinityControl: registerfunction enter
D/AndroidRuntime( 7745): Calling main entry com.android.commands.pm.Pm
D/PackageManager(  879): START PACKAGE DELETE: observer{109819108}
D/PackageManager(  879): pkg{<packageName>}
D/PackageManager(  879): user{0}
D/PackageManager(  879): caller{2000}
D/PackageManager(  879): flags{3}
D/PersonaManagerService(  879): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager(  879): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService(  879): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  879): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  879): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  879): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService(  879): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  879): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  879): getApplicationUninstallationEnabled
D/ApplicationPolicy(  879): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  879): !@killApplicatoin: 10294, uninstall pkg
I/ActivityManager(  879): Force stopping com.test.thalitest appid=10294 user=-1: uninstall pkg
I/ActivityManager(  879): Killing 7096:com.test.thalitest/u0a294 (adj 0): stop com.test.thalitest
W/PackageSettings(  879): Skipping PackageSetting{1dc9ead1 com.example.hello/10292} due to missing metadata
I/WindowState(  879): WIN DEATH: Window{10bed2ad u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  254): id=14 Removed NainActivit (5/8)
I/SurfaceFlinger(  254): id=14 Removed NainActivit (-2/8)
I/SurfaceFlinger(  254): id=14 Removed NainActivit (-2/8)
D/PointerIcon(  879): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  879): setMouseCustomIcon IconType is same.101
D/PointerIcon(  879): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  879): setHoveringSpenCustomIcon IconType is same.1
I/ActivityManager(  879): Killing 4258:com.sec.chaton/u0a102 (adj 11): empty for 1811s
I/ActivityManager(  879): Killing 7316:com.sec.knox.bridge/1000 (adj 11): empty for 1811s
I/ActivityManager(  879): Killing 7290:com.samsung.android.scloud.backup/u0a74 (adj 11): empty for 1811s
I/ActivityManager(  879): Killing 6451:com.osp.app.signin/u0a50 (adj 11): empty for 1811s
E/SMD     (  293): DCD ON
I/ActivityManager(  879): Killing 6393:com.policydm/1000 (adj 11): empty for 1811s
I/ActivityManager(  879): Killing 6772:com.sec.android.soagent/u0a42 (adj 11): empty for 1811s
I/ActivityManager(  879): Killing 7179:com.vlingo.midas/u0a38 (adj 11): empty for 1811s
I/ActivityManager(  879): Killing 7273:com.samsung.android.app.pinboard:tagService/u0a36 (adj 11): empty for 1811s
I/ActivityManager(  879): Killing 6753:com.samsung.klmsagent/u0a23 (adj 11): empty for 1811s
I/ActivityManager(  879): Killing 6724:com.sec.android.fotaclient/u0a14 (adj 11): empty for 1811s
I/ActivityManager(  879): Killing 7249:com.sec.android.diagmonagent/1000 (adj 11): empty for 1811s
I/ActivityManager(  879): Killing 7231:com.sec.android.cloudagent/u0a4 (adj 13): empty for 1811s
I/ActivityManager(  879): Killing 6356:com.sec.pcw.device/1000 (adj 13): empty for 1811s
I/ActivityManager(  879): Killing 6641:com.samsung.android.snote/u0a168 (adj 13): empty for 1811s
I/ActivityManager(  879): Killing 7501:com.sec.android.provider.badge/u0a92 (adj 13): empty for 1812s
I/ActivityManager(  879): Killing 1601:com.google.process.gapps/u0a15 (adj 13): empty for 1813s
I/ActivityManager(  879): Killing 6029:com.android.vending/u0a33 (adj 13): empty for 1877s
I/ActivityManager(  879): Killing 6868:com.android.providers.calendar/u0a51 (adj 13): empty for 1887s
I/ActivityManager(  879): Killing 6847:com.android.calendar/u0a172 (adj 13): empty for 1887s
I/ActivityManager(  879): Killing 6930:com.sec.android.widgetapp.SPlannerAppWidget/u0a171 (adj 13): empty for 1887s
I/ActivityManager(  879): Killing 6900:com.qualcomm.timeservice/1000 (adj 15): empty for 1889s
I/ActivityManager(  879): Killing 5993:com.sec.android.app.controlpanel/u0a134 (adj 15): empty for 1889s
I/ActivityManager(  879): Killing 6826:com.sec.esdk.elm/u0a116 (adj 15): empty for 1889s
I/ActivityManager(  879): Killing 6810:com.sec.android.app.clockpackage/u0a106 (adj 15): empty for 1889s
I/ActivityManager(  879): Killing 6792:com.samsung.android.scloud.sync/u0a76 (adj 15): empty for 1890s
I/ActivityManager(  879): Killing 6471:com.android.mms/u0a55 (adj 15): empty for 1890s
I/ActivityManager(  879): Killing 4374:com.sec.android.app.shealth/u0a40 (adj 15): empty for 1890s
I/ActivityManager(  879): Killing 6681:com.sec.kidsplat.installer/u0a189 (adj 15): empty for 1892s
I/ActivityManager(  879): Killing 6659:com.samsung.android.snote:provider/u0a168 (adj 15): empty for 1892s
I/ActivityManager(  879):   Force finishing activity ActivityRecord{7caafef u0 com.test.thalitest/.MainActivity t4}
W/ActivityManager(  879): mDVFSHelper.acquire()
W/libprocessgroup(  879): failed to open /acct/uid_10102/pid_4258/cgroup.procs: No such file or directory
D/ConnectivityService(  879): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/libprocessgroup(  879): failed to open /acct/uid_1000/pid_7316/cgroup.procs: No such file or directory
W/libprocessgroup(  879): failed to open /acct/uid_10074/pid_7290/cgroup.procs: No such file or directory
W/libprocessgroup(  879): failed to open /acct/uid_10050/pid_6451/cgroup.procs: No such file or directory
W/libprocessgroup(  879): failed to open /acct/uid_1000/pid_6393/cgroup.procs: No such file or directory
W/libprocessgroup(  879): failed to open /acct/uid_10042/pid_6772/cgroup.procs: No such file or directory
W/libprocessgroup(  879): failed to open /acct/uid_10038/pid_7179/cgroup.procs: No such file or directory
W/libprocessgroup(  879): failed to open /acct/uid_10036/pid_7273/cgroup.procs: No such file or directory
W/libprocessgroup(  879): failed to open /acct/uid_10023/pid_6753/cgroup.procs: No such file or directory
W/libprocessgroup(  879): failed to open /acct/uid_10014/pid_6724/cgroup.procs: No such file or directory
W/libprocessgroup(  879): failed to open /acct/uid_1000/pid_7249/cgroup.procs: No such file or directory
W/libprocessgroup(  879): failed to open /acct/uid_10004/pid_7231/cgroup.procs: No such file or directory
W/libprocessgroup(  879): failed to open /acct/uid_1000/pid_6356/cgroup.procs: No such file or directory
W/libprocessgroup(  879): failed to open /acct/uid_10168/pid_6641/cgroup.procs: No such file or directory
W/libprocessgroup(  879): failed to open /acct/uid_10092/pid_7501/cgroup.procs: No such file or directory
W/ActivityManager(  879): Spurious death for ProcessRecord{26f1ad4d 7096:com.test.thalitest/u0a294}, curProc for 7096: null
W/libprocessgroup(  879): failed to open /acct/uid_10015/pid_1601/cgroup.procs: No such file or directory
W/libprocessgroup(  879): failed to open /acct/uid_10033/pid_6029/cgroup.procs: No such file or directory
D/CountryDetector(  879): No listener is left
W/libprocessgroup(  879): failed to open /acct/uid_10051/pid_6868/cgroup.procs: No such file or directory
W/libprocessgroup(  879): failed to open /acct/uid_10171/pid_6930/cgroup.procs: No such file or directory
W/libprocessgroup(  879): failed to open /acct/uid_10134/pid_5993/cgroup.procs: No such file or directory
W/libprocessgroup(  879): failed to open /acct/uid_10116/pid_6826/cgroup.procs: No such file or directory
W/libprocessgroup(  879): failed to open /acct/uid_10106/pid_6810/cgroup.procs: No such file or directory
W/libprocessgroup(  879): failed to open /acct/uid_10076/pid_6792/cgroup.procs: No such file or directory
W/libprocessgroup(  879): failed to open /acct/uid_1000/pid_6900/cgroup.procs: No such file or directory
W/libprocessgroup(  879): failed to open /acct/uid_10172/pid_6847/cgroup.procs: No such file or directory
W/libprocessgroup(  879): failed to open /acct/uid_10055/pid_6471/cgroup.procs: No such file or directory
W/libprocessgroup(  879): failed to open /acct/uid_10040/pid_4374/cgroup.procs: No such file or directory
W/libprocessgroup(  879): failed to open /acct/uid_10189/pid_6681/cgroup.procs: No such file or directory
W/libprocessgroup(  879): failed to open /acct/uid_10168/pid_6659/cgroup.procs: No such file or directory
I/ActivityManager(  879): Force stopping com.test.thalitest appid=10294 user=0: pkg removed
I/DBG_DM  ( 3407): [com.wssyncmldm.ui.XUIInstallConfirmActivity(477/onResume)] 
D/ResourcesManager(  879): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
E/SamsungIME( 1728): mOCRHelper is null
W/GeofencerStateMachine( 1943): Ignoring removeGeofence because network location is disabled.
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
I/InputReader(  879): Reconfiguring input devices.  changes=0x00000010
D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
I/DBG_DM  ( 3407): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 18
D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
D/ResourcesManager(  879): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
E/Zygote  ( 7780): MountEmulatedStorage()
E/Zygote  ( 7780): v2
I/libpersona( 7780): KNOX_SDCARD checking this for 10023
I/libpersona( 7780): KNOX_SDCARD not a persona
I/ActivityManager(  879): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7780 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
D/ResourcesManager(  879): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
I/DBG_DM  ( 3407): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
I/art     ( 4276): Explicit concurrent mark sweep GC freed 35228(1951KB) AllocSpace objects, 9(144KB) LOS objects, 40% free, 15MB/26MB, paused 7.162ms total 62.130ms
I/DBG_DM  ( 3407): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 3407): [com.wssyncmldm.ui.XUIInstallConfirmActivity(487/onResume)] Postpone Count : 18
D/ResourcesManager(  879): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
I/DBG_DM  ( 3407): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
D/ResourcesManager(  879): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager(  879): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager(  879): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
I/SELinux ( 7780): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7780): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7780): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/art     ( 1484): Explicit concurrent mark sweep GC freed 34569(2MB) AllocSpace objects, 1(39KB) LOS objects, 24% free, 18MB/25MB, paused 421us total 86.276ms
D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
I/DBG_DM  ( 3407): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/ResourcesManager( 1438): creating new AssetManager and set to /system/priv-app/StoryAlbumWidget/StoryAlbumWidget.apk
W/ResourcesManager( 1438): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1438): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
D/ResourcesManager( 1438): creating new AssetManager and set to /system/app/AccuweatherPhone2013_H_LMR/AccuweatherPhone2013_H_LMR.apk
W/ResourcesManager( 1438): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1438): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1438): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
D/ResourcesManager( 1438): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
W/ResourcesManager( 1438): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1438): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
I/art     ( 2198): Explicit concurrent mark sweep GC freed 41366(2MB) AllocSpace objects, 9(144KB) LOS objects, 25% free, 22MB/30MB, paused 676us total 137.320ms
D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
I/DBG_DM  ( 3407): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/TimaKeyStoreProvider( 7780): TimaSignature is unavailable
D/ActivityThread( 7780): Added TimaKeyStore provider
D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/SecContentProvider2(  879): uri = 14 selection = getSealedState
D/SecContentProvider2(  879): mCursor = null
D/ApplicationPolicy(  879): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy(  879): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager(  879): creating new AssetManager and set to /system/app/Books/Books.apk
I/DBG_DM  ( 3407): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 18
D/ResourcesManager( 7780): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
I/DBG_DM  ( 3407): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
I/DBG_DM  ( 3407): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 3407): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false
I/DBG_DM  ( 3407): [IIlllIlIIlIllIlllIll(376/llIIllllIIlllIIIIlll)] 
I/DBG_DM  ( 3407): [IIlllIlIIlIllIlllIll(397/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
D/ActivityManager(  879): post active user change for 0
D/KnoxTimeoutHandler(  879): postActiveUserChange for user 0
I/DBG_DM  ( 3407): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
D/ResourcesManager(  879): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
I/SurfaceFlinger(  254): id=16 createSurf (1080x1920),2 flag=404, YUIInstallC
D/StatusBarManagerService(  879): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
W/SQLiteConnectionPool( 2198): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/StatusBarManagerService(  879): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
V/ActivityThread( 3407): updateVisibility : ActivityRecord{bb20794 token=android.os.BinderProxy@3e9c32a5 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
D/PointerIcon(  879): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  879): setMouseCustomIcon IconType is same.101
D/PointerIcon(  879): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  879): setHoveringSpenCustomIcon IconType is same.1
D/ResourcesManager(  879): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  879): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager(  879): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
I/KLMS-2.4.511: ( 7780): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/ResourcesManager(  879): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/SecContentProvider2(  879): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  879): mCursor = null
I/KLMS-2.4.511: ( 7780): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1450231499869
D/ResourcesManager(  879): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
I/KLMS-2.4.511: ( 7780): MainReciver(): PACKAGE_REMOVED
D/ResourcesManager(  879): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
I/KLMS-2.4.511: ( 7780): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
D/ResourcesManager(  879): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/InputMethodManagerService(  879): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/ResourcesManager(  879): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/RegisteredServicesCache( 1413): empty dynamic service
W/InputMethodManagerService(  879): Got RemoteException sending setActive(false) notification to pid 7096 uid 10294
W/ContextImpl(  879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/ResourcesManager(  879): creating new AssetManager and set to /system/app/Videos/Videos.apk
W/ActivityManager(  879): mDVFSHelper.release()
I/Timeline(  879): Timeline: Activity_windows_visible id: ActivityRecord{3f802b98 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t2} time:1972391
I/Timeline( 3407): Timeline: Activity_idle id: android.os.BinderProxy@3e9c32a5 time:1972392
D/RCPManagerService(  879): PackageReceiver onReceive()
I/HarmonyEASService(  879): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy(  879): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  879): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  879): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  879): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  879): uID is 10294
V/EnterpriseBillingPolicy(  879): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  879): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  879): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  879): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  879): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  879): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  879): getBillingProfileForVpnEngine - end - null
D/KnoxTimeoutHandler(  879): handleActiveUserChange for user 0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
D/StatusBar( 1187): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
D/PersonaManager( 1187): isKioskContainerExistOnDevice
D/PersonaManager( 1187): isKioskContainerExistOnDevice
D/PanelView( 1187): There is/are notification(s) 
D/PanelView( 1187): There is/are notification(s) 
E/Zygote  ( 7801): MountEmulatedStorage()
I/libpersona( 7801): KNOX_SDCARD checking this for 10116
E/Zygote  ( 7801): v2
I/libpersona( 7801): KNOX_SDCARD not a persona
I/ActivityManager(  879): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7801 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  879): Killing 7331:com.android.chrome/u0a104 (adj 15): empty for 1813s
I/SELinux ( 7801): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7801): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7801): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7801): TimaSignature is unavailable
D/ActivityThread( 7801): Added TimaKeyStore provider
I/art     (  879): Explicit concurrent mark sweep GC freed 24187(1860KB) AllocSpace objects, 9(144KB) LOS objects, 17% free, 37MB/45MB, paused 1.942ms total 354.322ms
D/PackageManager(  879): delete codoeFile: 
I/AASAUninstall(  879):  com.test.thalitest not target!
D/PackageManager(  879): result of delete: 1{109819108}
D/AndroidRuntime( 7745): Shutting down VM
D/TaskPersister(  879): removeObsoleteFile: deleting file=4_task.xml
D/TaskPersister(  879): removeObsoleteFile: deleting file=2_task.xml
W/libprocessgroup(  879): failed to open /acct/uid_10104/pid_7331/cgroup.procs: No such file or directory
D/ResourcesManager( 7801): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/elm:14491( 7801): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14491( 7801): ELMEngine.ELMEngine( context ).
D/elm:14491( 7801): MDMBridge.setEnterpriseBridge()
D/elm:14491( 7801): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  879): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  879): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
D/elm:14491( 7801): ElmAgentService : onCreate()
D/elm:14491( 7801): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14491( 7801): MainReceiver.listeningToPackageRemoved()
D/elm:14491( 7801): MDMBridge.getInstance()
D/elm:14491( 7801): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14491( 7801): MDMBridge.getAllLicenseInfoFromSDK()
E/Zygote  ( 7818): MountEmulatedStorage()
E/Zygote  ( 7818): v2
I/libpersona( 7818): KNOX_SDCARD checking this for 10021
I/libpersona( 7818): KNOX_SDCARD not a persona
D/ResourcesManager(  879): creating new AssetManager and set to /system/app/talkback/talkback.apk
I/ActivityManager(  879): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=7818 uid=10021 gids={50021, 9997} abi=armeabi-v7a
D/elm:14491( 7801): ElmAgentService : onDestroy().
I/SELinux ( 7818): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/ActivityManager(  879): Killing 7359:com.google.android.apps.magazines/u0a146 (adj 15): empty for 1813s
I/SELinux ( 7818): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
D/EnterpriseDeviceManagerService(  879): Package has changed for user 0
D/EnterpriseDeviceManagerService(  879): Admin package name: com.google.android.gms
E/SELinux ( 7818): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(  879): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
W/Resources(  879): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/TimaKeyStoreProvider( 7818): TimaSignature is unavailable
D/ActivityThread( 7818): Added TimaKeyStore provider
W/Resources(  879): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  879): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  879): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  879): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
W/Resources(  879): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  879): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/ResourcesManager(  879): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
W/Resources(  879): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
W/Resources(  879): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  879): creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
W/Resources(  879): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  879): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  879): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/Resources(  879): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  879): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  879): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  879): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  879): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
W/Resources(  879): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  879): creating new AssetManager and set to /system/app/Maps/Maps.apk
D/ResourcesManager(  879): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  879): creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
D/ResourcesManager(  879): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
W/Resources(  879): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}

```
