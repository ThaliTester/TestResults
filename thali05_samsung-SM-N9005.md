#### Test 539786639813e59_thali05_samsung-SM-N9005 Logs


```
--------- beginning of main,
E/SMD     (  290): DCD ON
D/AndroidRuntime( 7171): 
D/AndroidRuntime( 7171): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7171): CheckJNI is OFF
D/AndroidRuntime( 7171): readGMSProperty: start
D/AndroidRuntime( 7171): readGMSProperty: already setted!!
D/AndroidRuntime( 7171): readGMSProperty: end
D/AndroidRuntime( 7171): addProductProperty: start
E/AffinityControl( 7171): AffinityControl: registerfunction enter
D/AndroidRuntime( 7171): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  898): inState():  stateMachine is null !!
I/PersonaManagerService(  898): PersonaId don't exist
I/ActivityManager(  898): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  898): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
I/ActivityManager(  898): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  898): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager(  898): mDVFSHelper.acquire()
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  898): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7186 uid=10297 gids={50297, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 7186): MountEmulatedStorage()
E/Zygote  ( 7186): v2
I/libpersona( 7186): KNOX_SDCARD checking this for 10297
I/libpersona( 7186): KNOX_SDCARD not a persona
D/PointerIcon(  898): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  898): setMouseCustomIcon IconType is same.101
D/PointerIcon(  898): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  898): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7171): Shutting down VM
I/SELinux ( 7186): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7186): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7186): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7186): TimaSignature is unavailable
D/ActivityThread( 7186): Added TimaKeyStore provider
D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SurfaceFlinger(  254): id=11 Removed YUIInstallC (5/8)
I/SurfaceFlinger(  254): id=11 Removed YUIInstallC (-2/8)
D/ResourcesManager( 7186): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
V/ActivityThread( 3400): updateVisibility : ActivityRecord{18008ede token=android.os.BinderProxy@35c009e7 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
,I/WebViewFactory( 7186): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
D/ResourcesManager( 7186): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader( 7186): Loading: webviewchromium
I/LibraryLoader( 7186): Time to load native libraries: 5 ms (timestamps 3287-3292)
I/LibraryLoader( 7186): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7186): Binding Chromium to main looper Looper (main, tid 1) {33cfae5a}
I/LibraryLoader( 7186): Expected native library version number "",actual native library version number ""
I/chromium( 7186): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7186): Initializing chromium process, renderers=0
W/art     ( 7186): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7186): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7186): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46780 len=2953
I/chromium( 7186): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229536 len:643667
I/Adreno-EGL( 7186): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 7186): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7186): Build Date: 11/19/14 Wed
I/Adreno-EGL( 7186): Local Branch: mybranch5813579
I/Adreno-EGL( 7186): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 7186): Local Patches: NONE
I/Adreno-EGL( 7186): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
W/chromium( 7186): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7186): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/ActivityManager(  898): Activity pause timeout for ActivityRecord{2e9884c1 u0 com.test.thalitest/.MainActivity t4}
W/art     ( 7186): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7186): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7186): CordovaWebView is running on device made by: samsung
W/art     ( 7186): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7186): Attempt to remove local handle scope entry from IRT, ignoring
D/Activity( 7186): performCreate Call secproduct feature valuefalse
D/Activity( 7186): performCreate Call debug elastic valuetrue
D/OpenGLRenderer( 7186): Render dirty regions requested: true
D/Atlas   ( 7186): Validating map...
D/ActivityManager(  898): post active user change for 0
D/KnoxTimeoutHandler(  898): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  898): handleActiveUserChange for user 0
V/ActivityThread( 7186): updateVisibility : ActivityRecord{2b64fa7b token=android.os.BinderProxy@3a778275 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
I/SurfaceFlinger(  254): id=14 createSurf (1x1),1 flag=404, NainActivit
D/StatusBarManagerService(  898): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  898): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon(  898): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  898): setMouseCustomIcon IconType is same.101
D/PointerIcon(  898): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  898): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer( 7186): Initialized EGL, version 1.4
I/OpenGLRenderer( 7186): HWUI protection enabled for context ,  &this =0xb3c5cce0 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 7186): Enabling debug mode 0
D/InputMethodManagerService(  898): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ActivityManager(  898): mDVFSHelper.release()
I/Timeline(  898): Timeline: Activity_windows_visible id: ActivityRecord{2e9884c1 u0 com.test.thalitest/.MainActivity t4} time:153882
W/IInputConnectionWrapper( 7186): showStatusIcon on inactive InputConnection
I/Timeline( 7186): Timeline: Activity_idle id: android.os.BinderProxy@3a778275 time:153905
I/chromium( 7186): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7186): 
D/JsMessageQueue( 7186): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 7186): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1359350784
,D/JX-Cordova( 7186): jxcore cordova android initializing
,E/SMD     (  290): DCD ON
,W/jxcore-log( 7186): Initializing JXcore engine
W/jxcore-log( 7186): JXcore engine is ready
,W/jxcore-log( 7186): Starting JXcore engine
,E/auditd  ( 1844): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  898): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  898): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,D/SecurityLogAgent( 6968):  SeDenialReceiver : Intent Received : android.intent.action.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 6968):  SeDenialReceiver : File path = null
,W/jxcore-log( 7186): Platform android
W/jxcore-log( 7186): 
,W/jxcore-log( 7186): Process ARCH arm
W/jxcore-log( 7186): 
,I/jxcore-log( 7186): JXcore Cordova bridge is ready!
I/jxcore-log( 7186): 
,W/jxcore-log( 7186): JXcore engine is started
,I/jxcore-log( 7186): Toggling radios to true
I/jxcore-log( 7186): 
,D/BluetoothAdapter( 7186): enable()
,D/BluetoothAdapter( 7186): enable(): BT is already enabled..!
,I/WifiManager( 7186): packageName : com.test.thalitest
,D/SecContentProvider(  898): uri = 18 selection = isWifiEnabled
D/SecContentProvider2(  898): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  898): mCursor = null
,D/WifiService(  898): setWifiEnabled: true pid=7186, uid=10297
W/ActivityManager(  898): Permission Denial: getCurrentUser() from pid=7186, uid=10297 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  898): Failed getting userId using ActivityManagerNative
W/WifiService(  898): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7186, uid=10297 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  898): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23057)
W/WifiService(  898): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2181)
W/WifiService(  898): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2169)
W/WifiService(  898): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  898): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider(  898): name = wifi_on
,I/WifiService(  898): disconnect: pid=7186, uid=10297
,I/wpa_supplicant( 1268): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7186): Radios toggled
I/jxcore-log( 7186): 
,I/wpa_supplicant( 1268): CTRL-EVENT-DISCONNECTED bssid=C0.AA.4A reason=3 locally_generated=1
,I/wpa_supplicant( 1268): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1268): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.4A SSID=4E473730303567
I/wpa_supplicant( 1268): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine(  898): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1268): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1268): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1268): Disconnected - do not scan
I/wpa_supplicant( 1268): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiConfigStore(  898): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  898): do suspend true
,D/WifiP2pService(  898): InactiveState{ what=143375 }
,D/WifiP2pService(  898): P2pEnabledState{ what=143375 }
,D/CommandListener(  282): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 1183): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1183): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
,V/NativeCrypto( 1949): Read error: ssl=0x9ba8be00: I/O error during system call, Connection timed out
,E/WifiConfigStore(  898): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/ConnectivityService(  898): updateNetworkInfo()
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
D/ConnectivityService(  898): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/WifiTrafficPoller(  898): evaluateTrafficStatsPolling
E/ConnectivityService(  898): updateNetworkInfo()
,D/ConnectivityService(  898): ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
D/ConnectivityService(  898): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,D/StatusBar.NetworkController( 1183): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/NetUtils(  898): android_net_utils_resetConnections in env=0x9d7b7390 clazz=0x9bde098c iface=wlan0 mask=0x3
,D/STATUSBAR-WifiQuickSettingButton( 1183): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1183): applyOpen
,D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
,V/NativeCrypto( 1949): SSL shutdown failed: ssl=0x9ba8be00: I/O error during system call, Broken pipe
,D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
,E/WifiStateMachine(  898): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1268): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1268): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1268): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1268): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1268): First Scan Start
,E/native  (  898): do suspend true
,D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10015
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  898): ValidatedState{ when=0 what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  898): DefaultState{ when=0 what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  898): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  898): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  898): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,I/System.out(  898): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid (  898): Tagging socket 385 with tag ffffffff00000000{4294967295,0} uid 10015, pid: 898, getuid(): 1000
,D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  898): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.samsung.myplace.WIFINotificationHandler: pid=7269 uid=10038 gids={50038, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,E/Zygote  ( 7269): MountEmulatedStorage()
,I/System.out(  898): (HTTPLog)-Static: isSBSettingEnabled false
,E/Zygote  ( 7269): v2
I/libpersona( 7269): KNOX_SDCARD checking this for 10038
I/libpersona( 7269): KNOX_SDCARD not a persona
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  898): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  898): Validated
,I/SELinux ( 7269): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7269): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7269): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/wpa_supplicant( 1268): Scan requested (ret=0) - scan timeout 30 seconds
,D/WifiP2pService(  898): InactiveState{ what=143375 }
,D/WifiP2pService(  898): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1183): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1183): onWifiSignalChanged enabled=true enabledDesc:null
,D/CommandListener(  282): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 1183): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1183): onWifiSignalChanged enabled=true enabledDesc:null
,I/WifiTrafficPoller(  898): evaluateTrafficStatsPolling
,D/TimaKeyStoreProvider( 7269): TimaSignature is unavailable
,D/ActivityThread( 7269): Added TimaKeyStore provider
,D/WifiNetworkAgent(  898): NetworkAgent: NetworkAgent channel lost
,D/SecContentProvider2(  898): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  898): mCursor = null
,D/SecContentProvider2(  898): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  898): mCursor = null
,D/ResourcesManager( 7269): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
W/ResourcesManager( 7269): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ConnectivityService(  898): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  898): calling update connectivity
D/ConnectivityService(  898):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  898):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  898): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  898):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1183): CM callback handler got msg 524292
D/ConnectivityService(  898): sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/EntConnectivity(  898): Not allowed due to - mEnabled false
,V/Nat464Xlat(  898): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  898): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  898): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/CSLegacyTypeTracker(  898): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  898): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService(  898): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  898): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 2297): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  898): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  898): Disconnected - quitting
D/TelephonyNetworkFactory( 1421): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  898): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  898): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  898): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  898): getSBEnabled() enabled =false
D/SmartBondingService(  898): getSBEnabled() enabled =false
D/SmartBondingService(  898): getSBEnabled() enabled =false
D/Tethering(  898): MasterInitialState.processMessage what=3
V/NetworkStats(  898): updateIfacesLocked()
D/NtpTrustedTime(  898): currentTimeMillis() cache hit
E/ConnectivityService(  898): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
V/NetworkStats(  898): performPollLocked(flags=0x1)
D/NetworkStatsFactory(  898): UpdateStatsForKnox
D/ConnectivityService(  898): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1183): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1183): updateDataNetType()
D/StatusBar.NetworkController( 1183): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1183): updateLTEICONDataNetType:0
,V/NetworkStats(  898): performPollLocked() took 6ms
D/NtpTrustedTime(  898): currentTimeMillis() cache hit
,D/SmartBondingService(  898): getNetworkEnabled : wifi : true mobile : true
,D/NtpTrustedTime(  898): currentTimeMillis() cache hit
,D/NtpTrustedTime(  898): currentTimeMillis() cache hit
D/NtpTrustedTime(  898): currentTimeMillis() cache hit
D/NtpTrustedTime(  898): currentTimeMillis() cache hit
V/NetworkStats(  898): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  898): currentTimeMillis() cache hit
D/NtpTrustedTime(  898): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1183): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1183): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1183): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1183): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1183): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
,D/FileWriteThread_Telephony( 1421): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1421): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1421): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1421): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1421): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1421): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1421): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1421): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1421): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1421): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1421): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1421): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1421): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1421): FileWriteThread : threadType = 3
,I/VlingoApplication( 7269): VlingoApplication appVersion ='11.2.2.0.37649', ro.csc.sales_code=XEO
,E/BluetoothHeadset( 7269): BTStateChangeCB is registed
,E/BluetoothHeadset( 7269): BluetoothHeadset service is binded
,I/ActivityManager(  898): Killing 6306:com.android.defcontainer/u0a7 (adj 15): bgCount ##41
,I/Hs20UtilService( 1325): Starting #6
,I/Hs20UtilService( 1325): Message received 5007
,D/NearbySettings( 1325): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1325): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1325): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1325): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1325): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1325): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1325): MountReceiver.mPrefHandler - 7002
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6753): NETWORK_STATE_CHANGED_ACTION
,D/SettingsProvider(  898): name = driving_mode_on
D/SettingsProvider(  898): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  898): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  898): selectionArgs: false
D/SettingsProvider(  898): selectionArgs: 10038
D/SecContentProvider(  898): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  898): ret = -1
,D/BluetoothManager( 7269): [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.media.ACTION_SCO_AUDIO_STATE_UPDATED
,I/Hs20UtilService( 1325): Starting #7
,D/NearbySettings( 1325): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1325): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1325): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1325): DMSUtil.isNetworkConnected - P2P: IDLE
D/ConnectivityService(  898): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1325): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1325): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1325): MountReceiver.mPrefHandler - 7002
,I/Hs20UtilService( 1325): Message received 5007
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6753): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  898): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  898): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GpsLocationProvider(  898): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ApplicationPolicy(  898): updateDataUsageMap
D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  898): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  898): getSBEnabled() enabled =false
D/SmartBondingService(  898): getSBEnabled() enabled =false
D/SmartBondingService(  898): getSBEnabled() enabled =false
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  898): getNetworkEnabled : wifi : true mobile : true
,I/DBG_DM  ( 3400): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/NetworkMonitor( 5706): type=WIFI subType= reason=null isConnected=false
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/PCWCLIENTTRACE_PushUtil( 6465): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6465): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6465): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6465): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6465): noConnectivity : true
,I/DBG_DM  ( 3400): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  898): stay LED for fully charged
,I/ActivityManager(  898): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7328 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 7328): MountEmulatedStorage()
E/Zygote  ( 7328): v2
,I/libpersona( 7328): KNOX_SDCARD checking this for 10004
I/libpersona( 7328): KNOX_SDCARD not a persona
,I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/SELinux ( 7328): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/SELinux ( 7328): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SELinux ( 7328): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SSRM:n  (  898): SIOP:: AP = 340, PST = 335, CUR = 450
,D/TimaKeyStoreProvider( 7328): TimaSignature is unavailable
,D/ActivityThread( 7328): Added TimaKeyStore provider
,D/ResourcesManager( 7328): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager(  898): Killing 6448:com.samsung.groupcast/u0a20 (adj 15): bgCount ##41
,E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7350): MountEmulatedStorage()
E/Zygote  ( 7350): v2
I/libpersona( 7350): KNOX_SDCARD checking this for 1000
I/libpersona( 7350): KNOX_SDCARD not a persona
,I/ActivityManager(  898): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7350 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7350): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7350): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7350): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7350): TimaSignature is unavailable
,D/ActivityThread( 7350): Added TimaKeyStore provider
,D/ResourcesManager( 7350): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT( 7350): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7350): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT( 7350): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7350): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7350): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT( 7350): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/FOTA_Client( 6829): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 6829): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 6829): [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.511: ( 6846): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.511: ( 6846): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450361512558
,I/KLMS-2.4.511: ( 6846): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.511: ( 6846): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.511: ( 6846): StateImplV2(): networkChangeListener().END
,E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7376): MountEmulatedStorage()
,E/Zygote  ( 7376): v2
I/libpersona( 7376): KNOX_SDCARD checking this for 10036
I/libpersona( 7376): KNOX_SDCARD not a persona
,I/ActivityManager(  898): Start proc com.samsung.android.app.pinboard:tagService for broadcast com.samsung.android.app.pinboard/.service.TagReadyReceiver: pid=7376 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  898): Killing 5936:sstream.app/u0a25 (adj 15): bgCount ##41
,I/SELinux ( 7376): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7376): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7376): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/wpa_supplicant( 1268): nl80211: Received scan results (7 BSSes)
,I/wpa_supplicant( 1268): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1268): Trying to associate with C0.AA.4A (SSID='4E473730303567' freq=5220 MHz)
I/wpa_supplicant( 1268): wlan0: State: SCANNING -> ASSOCIATING
,I/wpa_supplicant( 1268): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E473730303567
,D/SecContentProvider2(  898): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  898): mCursor = null
,D/TimaKeyStoreProvider( 7376): TimaSignature is unavailable
,D/ActivityThread( 7376): Added TimaKeyStore provider
,D/ResourcesManager( 7376): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
W/ResourcesManager( 7376): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7376): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/wpa_supplicant( 1268): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1268): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E473730303567
I/wpa_supplicant( 1268): Associated with C0.AA.4A
D/SecContentProvider2(  898): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  898): mCursor = null
E/Minikin ( 7376): addFont failed to create font /system/fonts/SamsungSans-light.ttf
I/wpa_supplicant( 1268): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1268): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.4A SSID=4E473730303567
D/SecContentProvider2(  898): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  898): mCursor = null
I/wpa_supplicant( 1268): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1268): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1268): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.4A SSID=4E473730303567
I/wpa_supplicant( 1268): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1268): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1268): CTRL-EVENT-CONNECTED - Connection to C0.AA.4A completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1268): Blacklist: Clear (temp) 
I/wpa_supplicant( 1268): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.4A SSID=4E473730303567
D/WifiNative-HAL(  898): callSECApiVoid - ID [50]
D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1183): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1183): onWifiSignalChanged enabled=true enabledDesc:null
I/ActivityManager(  898): Killing 5984:com.samsung.android.app.galaxyfinder/u0a39 (adj 15): bgCount ##41
D/ConnectivityService(  898): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  898): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  898): Got NetworkAgent Messenger
D/ConnectivityService(  898): hsengiv:checkWhatTypeOfNetwork and the value is false
D/ConnectivityService(  898): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  898): updateNetworkInfo()
D/ConnectivityService(  898): NetworkAgent connected
I/SO_AGENT( 6861): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  898): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/SPPClientService( 4922): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
E/WifiConfigStore(  898): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
I/SA      ( 6551): [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
I/SA      ( 6551): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 6551): [OR] == ACTION_CONNECTIVITY_CHANGE ==
D/CommandListener(  282): Setting iface cfg
E/WifiStateMachine(  898): Start Dhcp Watchdog 2
I/SA      ( 6551): [SLFUCHKMGR] constructor called
D/SecContentProvider2(  898): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  898): mCursor = null
E/SPPClientService( 4922): [[SystemStateMonitorService]] No Active Internet
I/SA      ( 6551): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6551): [OR] == isSIMCardReady false ==
I/SA      ( 6551): [SCU] == networkStateCheck == false
I/SA      ( 6551): [OR] onReceive END
D/ConnectivityService(  898): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/SMD     (  290): DCD ON
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7399): MountEmulatedStorage()
E/Zygote  ( 7399): v2
I/libpersona( 7399): KNOX_SDCARD checking this for 10074
I/libpersona( 7399): KNOX_SDCARD not a persona
I/ActivityManager(  898): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=7399 uid=10074 gids={50074, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/SELinux ( 7399): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7399): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7399): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/native  (  898): do suspend false
D/TimaKeyStoreProvider( 7399): TimaSignature is unavailable
D/ActivityThread( 7399): Added TimaKeyStore provider
D/SecContentProvider2(  898): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  898): mCursor = null
D/WifiP2pService(  898): InactiveState{ what=143375 }
D/WifiP2pService(  898): P2pEnabledState{ what=143375 }
D/ResourcesManager( 7399): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
I/sCloudBackupApp( 7399): sCloudBackupApp Version Info : 3.13.7.KK_APP
I/SCloudBackupReceiver( 7399): Other Intent
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7415): MountEmulatedStorage()
E/Zygote  ( 7415): v2
I/libpersona( 7415): KNOX_SDCARD checking this for 1000
I/libpersona( 7415): KNOX_SDCARD not a persona
I/ServiceManager(  327): Waiting for service AtCmdFwd...
I/ActivityManager(  898): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7415 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  898): Killing 6522:com.samsung.android.sdk.samsunglink/u0a48 (adj 15): bgCount ##41
I/SELinux ( 7415): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7415): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7415): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7415): TimaSignature is unavailable
D/ActivityThread( 7415): Added TimaKeyStore provider
E/dhcpcd  ( 7433): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/dhcpcd  ( 7433): version 5.5.6 starting
E/dhcpcd  ( 7433): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
D/ResourcesManager( 7415): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
W/ResourcesManager( 7415): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/KnoxUsageLogPro( 7415): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 7415): premStatus:2
I/KnoxUsageLogPro( 7415): isEulaShown : false
I/KnoxUsageLogPro( 7415): KnoxUsageReceiver onReceive : not Processible, just return
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7440): MountEmulatedStorage()
E/Zygote  ( 7440): v2
I/libpersona( 7440): KNOX_SDCARD checking this for 10104
I/libpersona( 7440): KNOX_SDCARD not a persona
I/dhcpcd  ( 7433): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7433): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7433): if(wlan0) info get Success. (MAC : C0.AA.4A)
I/dhcpcd  ( 7433): bssid match
I/dhcpcd  ( 7433): wlan0: rebinding lease of 192.168.1.128
I/ActivityManager(  898): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7440 uid=10104 gids={50104, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  898): Killing 5770:com.sec.android.gallery3d/u0a53 (adj 13): bgCount ##41
I/SELinux ( 7440): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7440): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7440): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7440): TimaSignature is unavailable
D/ActivityThread( 7440): Added TimaKeyStore provider
D/ResourcesManager( 7440): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7456): MountEmulatedStorage()
,E/Zygote  ( 7456): v2
I/libpersona( 7456): KNOX_SDCARD checking this for 10146
I/libpersona( 7456): KNOX_SDCARD not a persona
,I/SELinux ( 7456): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7456): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7456): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  898): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7456 uid=10146 gids={50146, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  898): Killing 6596:com.sec.android.provider.badge/u0a92 (adj 13): bgCount ##41
,I/art     (  320): Explicit concurrent mark sweep GC freed 8739(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 312us total 13.237ms
,I/jxcore-log( 7186): Got Device Bluetooth address: E0:DB:10:1F:C9:5E
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): my name is : samsung-SM-N9005_PT2526
I/jxcore-log( 7186): 
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 269us total 9.945ms
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 274us total 9.646ms
D/TimaKeyStoreProvider( 7456): TimaSignature is unavailable
,D/ActivityThread( 7456): Added TimaKeyStore provider
,D/ResourcesManager( 7456): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/jxcore-log( 7186): attempting to connect to test coordinator
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): check test folder
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): found test : ./testFindPeers.js
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): found test : ./testReConnect.js
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): found test : ./testSendData.js
I/jxcore-log( 7186): 
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7456): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7456): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/jxcore-log( 7186): Test app app.js loaded
I/jxcore-log( 7186): 
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7456): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7456): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/jxcore-log( 7186): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7186): 
,I/Choreographer( 7186): Skipped 147 frames!  The application may be doing too much work on its main thread.
,I/chromium( 7186): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/chromium( 7186): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/WebViewFactory( 7456): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,D/ResourcesManager( 7456): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7456): Loading: webviewchromium
,I/LibraryLoader( 7456): Time to load native libraries: 4 ms (timestamps 9258-9262)
,I/LibraryLoader( 7456): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7456): Binding Chromium to main looper Looper (main, tid 1) {1f469ab0}
,I/LibraryLoader( 7456): Expected native library version number "",actual native library version number ""
,I/chromium( 7456): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7456): Initializing chromium process, renderers=0
,W/art     ( 7456): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7456): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7456): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46780 len=2953
,I/chromium( 7456): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229536 len:643667
,W/AudioManagerAndroid( 7456): Requires BLUETOOTH permission
,I/Adreno-EGL( 7456): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 7456): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7456): Build Date: 11/19/14 Wed
I/Adreno-EGL( 7456): Local Branch: mybranch5813579
I/Adreno-EGL( 7456): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 7456): Local Patches: NONE
I/Adreno-EGL( 7456): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,I/NSApplication( 7456): Starting up...
,I/ActivityManager(  898): Killing 6615:com.sec.android.app.soundalive/u0a64 (adj 15): bgCount ##41
,E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7514): MountEmulatedStorage()
E/Zygote  ( 7514): v2
I/libpersona( 7514): KNOX_SDCARD checking this for 10158
I/libpersona( 7514): KNOX_SDCARD not a persona
,I/ActivityManager(  898): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7514 uid=10158 gids={50158, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 7514): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7514): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7514): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7514): TimaSignature is unavailable
,D/ActivityThread( 7514): Added TimaKeyStore provider
,D/ResourcesManager( 7514): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 7514): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7514): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7514): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 7514): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7514): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7514): PeriphStartReceiver.onReceive - no need to start
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7529): MountEmulatedStorage()
I/ActivityManager(  898): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7529 uid=10186 gids={50186, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
E/Zygote  ( 7529): v2
I/ActivityManager(  898): Killing 5559:com.samsung.android.app.assistantmenu/1000 (adj 13): bgCount ##41
I/libpersona( 7529): KNOX_SDCARD checking this for 10186
I/libpersona( 7529): KNOX_SDCARD not a persona
,I/SELinux ( 7529): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7529): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7529): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7529): TimaSignature is unavailable
,D/ActivityThread( 7529): Added TimaKeyStore provider
,D/ResourcesManager( 7529): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7529): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7529): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7529): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 7529): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7529): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService(  898): exchangeData() failure , invalid userId
,D/RCPManagerService(  898): exchangeData() failure , invalid userId
,D/RCPManagerService(  898): exchangeData() failure , invalid userId
,E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService(  898): exchangeData() failure , invalid userId
,I/ActivityManager(  898): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7552 uid=10092 gids={50092, 9997} abi=armeabi-v7a
E/Zygote  ( 7552): MountEmulatedStorage()
I/libpersona( 7552): KNOX_SDCARD checking this for 10092
E/Zygote  ( 7552): v2
I/libpersona( 7552): KNOX_SDCARD not a persona
,I/dhcpcd  ( 7433): wlan0: acknowledged 192.168.1.128 from 192.168.1.1
,I/SELinux ( 7552): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7552): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7552): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/RCPManagerService(  898): exchangeData() failure , invalid userId
,D/RCPManagerService(  898): exchangeData() failure , invalid userId
,I/dhcpcd  ( 7433): wlan0: leased 192.168.1.128 for 86400 seconds
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6968): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6968): KnoxConfiguration : Current State Mapping Found 
D/ConnectivityService(  898): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,D/SecurityLogAgent( 6968): StateMachine : Current State = 1
,D/TimaKeyStoreProvider( 7552): TimaSignature is unavailable
,D/ActivityThread( 7552): Added TimaKeyStore provider
,D/SecurityLogAgent( 6968): StateMachine : Changed Current State = 1
,I/ActivityManager(  898): Killing 6655:com.wsomacp/u0a29 (adj 13): bgCount ##41
,I/ActivityManager(  898): Killing 6634:com.google.android.apps.docs/u0a112 (adj 13): bgCount ##41
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  898): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7583): MountEmulatedStorage()
E/Zygote  ( 7583): v2
,I/libpersona( 7583): KNOX_SDCARD checking this for 10200
I/libpersona( 7583): KNOX_SDCARD not a persona
,I/ActivityManager(  898): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7583 uid=10200 gids={50200, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7583): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7583): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7583): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7583): TimaSignature is unavailable
,D/ActivityThread( 7583): Added TimaKeyStore provider
,I/art     (  898): Explicit concurrent mark sweep GC freed 65026(3MB) AllocSpace objects, 24(432KB) LOS objects, 17% free, 37MB/45MB, paused 1.807ms total 114.956ms
,D/ResourcesManager( 7552): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/ResourcesManager( 7583): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,D/BadgeProvider( 7552): onCreate
D/BadgeProvider( 7552): DatabaseHelper
,I/ActivityManager(  898): Killing 6686:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##41
,D/BadgeProvider( 7552): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/iu.Environment( 2297): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2297): num queued entries: 0
,I/iu.UploadsManager( 2297): num updated entries: 0
I/iu.SyncManager( 2297): NEXT; no task
,D/BadgeProvider( 7552): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7552): sendNotify, [notify] : null
D/BadgeProvider( 7552): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7552): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7552): update, [UpdateCount] : 1
,D/Launcher.Model( 1441): reloadBadges entered.
,I/Hs20UtilService( 1325): Starting #8
,I/Hs20UtilService( 1325): Message received 5007
,D/NearbySettings( 1325): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1325): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1325): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1325): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1325): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1325): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1325): MountReceiver.mPrefHandler - 7002
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6753): NETWORK_STATE_CHANGED_ACTION
,W/ActivityManager(  898): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,E/native  (  898): do suspend true
,D/WifiP2pService(  898): InactiveState{ what=143375 }
D/WifiP2pService(  898): P2pEnabledState{ what=143375 }
,D/ConnectivityService(  898): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,E/WifiStateMachine(  898): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG7005g"WPA_PSK
E/WifiStateMachine(  898): VerifyingLinkState enter
D/StatusBar.NetworkController( 1183): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1183): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiNative-HAL(  898): callSECApiInt - ID [210]
,E/ConnectivityService(  898): updateNetworkInfo()
,D/ConnectivityService(  898): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService(  898): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine(  898): updateDnsLinkProperty: enter
D/WifiWatchdogStateMachine.DnsPinger(  898): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/StatusBar.NetworkController( 1183): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1183): onWifiSignalChanged enabled=true enabledDesc:null
D/WifiWatchdogStateMachine.DnsResolver(  898): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker(  898): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  898): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,E/WifiStateMachine(  898): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,I/WifiTrafficPoller(  898): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1183): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1183): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine(  898): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller(  898): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  898): mBoosterFLAG : 0
I/WifiTrafficPoller(  898): current booster mode : FullMode
D/WifiNative-HAL(  898): callSECApiVoid - ID [212]
,D/StatusBar.NetworkController( 1183): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1183): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
,D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1183): applyOpen
,D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1183): applyOpen
,I/Hs20UtilService( 1325): Starting #9
,I/Hs20UtilService( 1325): Message received 5007
,D/NearbySettings( 1325): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1325): MountReceiver.onReceive - Keep current state
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService(  898): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService(  898): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/SignOutReceiver( 6753): NETWORK_STATE_CHANGED_ACTION
,E/ConnectivityService(  898): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  898): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  898): updateSourceRoutes : add src route for:192.168.1.128
V/        (  282): QcRouteController
,I/Hs20UtilService( 1325): Starting #10
,V/        (  282): QcRouteController
I/Hs20UtilService( 1325): Message received 5007
,D/NearbySettings( 1325): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1325): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1325): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1325): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1325): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1325): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1325): MountReceiver.mPrefHandler - 7002
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6753): NETWORK_STATE_CHANGED_ACTION
,V/        (  282): QcRouteController
,I/Hs20UtilService( 1325): Starting #11
,D/NearbySettings( 1325): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/Hs20UtilService( 1325): Message received 5007
I/NearbySettings( 1325): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine(  898): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,V/        (  282): QcRouteController
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6753): NETWORK_STATE_CHANGED_ACTION
,V/        (  282): QcRouteController
,I/SurfaceFlinger(  254): id=15 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService(  898): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=898
,V/        (  282): QcRouteController
,V/        (  282): QcRouteController
,V/        (  282): QcRouteController
,D/ConnectivityService(  898): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService(  898): LTETest block dns file not exists
,V/Nat464Xlat(  898): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  898): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  898): calling update connectivity
E/ConnectivityService(  898): updateNetworkInfo()
D/ConnectivityService(  898): ignoring duplicate network state non-change. WIFI, state = CONNECTING
E/ConnectivityService(  898): updateNetworkInfo()
D/ConnectivityService(  898): ignoring duplicate network state non-change. WIFI, state = CONNECTING
D/EntConnectivity(  898): Not allowed due to - mEnabled false
D/ConnectivityService(  898): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  898): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  898): calling update connectivity
D/ConnectivityService(  898): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  898):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  898): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  898):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  898): Connected
D/ConnectivityService(  898):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  898): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  898):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  898): Checking http://clients3.google.com/generate_204 on "NG7005g"
,I/System.out(  898): (HTTPLog)-Static: isSBSettingEnabled false
D/ConnectivityService(  898): currentScore = 0, newScore = 60
D/ConnectivityService(  898):    accepting network in place of null
D/ConnectivityService(  898): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1421): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/CSLegacyTypeTracker(  898): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  898): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  898): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  898): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  898): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/Tethering(  898): MasterInitialState.processMessage what=3
D/SmartBondingService(  898): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  898): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  898): getSBEnabled() enabled =false
D/SmartBondingService(  898): getSBEnabled() enabled =false
D/SmartBondingService(  898): getSBEnabled() enabled =false
D/NtpTrustedTime(  898): currentTimeMillis() cache hit
V/NetworkStats(  898): updateIfacesLocked()
V/NetworkStats(  898): performPollLocked(flags=0x1)
D/SmartBondingService(  898): getNetworkEnabled : wifi : true mobile : true
D/NetworkStatsFactory(  898): UpdateStatsForKnox
D/ConnectivityService(  898): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1183): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1183): updateDataNetType()
D/NtpTrustedTime(  898): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1183): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1183): updateLTEICONDataNetType:0
V/NetworkStats(  898): performPollLocked() took 4ms
D/NtpTrustedTime(  898): currentTimeMillis() cache hit
D/NtpTrustedTime(  898): currentTimeMillis() cache hit
V/NetworkStats(  898): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  898): currentTimeMillis() cache hit
D/NtpTrustedTime(  898): currentTimeMillis() cache hit
D/EntConnectivity(  898): Not allowed due to - mEnabled false
D/ConnectivityService(  898): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  898): calling update connectivity
D/ConnectivityService(  898):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  898):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NtpTrustedTime(  898): currentTimeMillis() cache hit
D/NtpTrustedTime(  898): currentTimeMillis() cache hit
D/ConnectivityService(  898): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  898):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1183): CM callback handler got msg 524290
D/ConnectivityService(  898): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 2297): CM callback handler got msg 524290
D/StatusBar.NetworkController( 1183): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
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
I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/jxcore-log( 7186): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7186): 
,I/System.out(  898): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  898): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 17 Dec 2015 14:11:55 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450361515038], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450361515026]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  898): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  898): Validated
,D/ConnectivityService(  898): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  898): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  898):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  898):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  898):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  898): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  898): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  898): calling update connectivity
D/ConnectivityService(  898):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  898):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  898): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  898):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  898): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1183): CM callback handler got msg 524290
D/ConnectivityService(  898): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 2297): CM callback handler got msg 524290
D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1183): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1183): updateDataNetType()
D/StatusBar.NetworkController( 1183): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1183): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1183): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1183): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1183): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1183): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1183): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
,D/ConnectivityService(  898): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  898): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  898): SmartBondingReceiver: wifi is connected
,D/SmartBondingService(  898): SmartBondingReceiver: wifi ap is not changed
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  898): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  898): getSBEnabled() enabled =false
,D/SmartBondingService(  898): getSBEnabled() enabled =false
D/SmartBondingService(  898): getSBEnabled() enabled =false
,D/SmartBondingService(  898): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1940): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1940): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GpsLocationProvider(  898): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 3400): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/NetworkMonitor( 5706): type=WIFI subType= reason=null isConnected=true
,I/PCWCLIENTTRACE_PushUtil( 6465): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6465): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6465): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6465): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 3400): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DIAGMON_AGENT( 7350): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7350): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/SecContentProvider2(  898): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  898): mCursor = null
,I/FOTA_Client( 6829): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 6829): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 6829): [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.511: ( 6846): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.511: ( 6846): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450361515765
,I/KLMS-2.4.511: ( 6846): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.511: ( 6846): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.511: ( 6846): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.511: ( 6846): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.511: ( 6846): StateImplV2(): networkChangeListener().END
,E/SMD     (  290): DCD ON
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SO_AGENT( 6861): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 4922): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 6551): [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
,I/SA      ( 6551): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 6551): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6551): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6551): [OR] == isSIMCardReady false ==
D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 6551): [SCU] == networkStateCheck == true
,I/SA      ( 6551): [DM] getCountryCodeFromCSC : PL
I/SA      ( 6551): isChinaCountryCode : false
I/SA      ( 6551): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6551): [OR] == networkStateCheck true ==
,I/SA      ( 6551): [OR] GetMyCountryZoneTask
,I/SA      ( 6551): [OR] onReceive END
,I/SA      ( 6551): [SRS] prepareGetMyCountryZone
,D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6551): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6551): [SSP] query invoked
,I/SCloudBackupReceiver( 7399): Other Intent
,I/SA      ( 6551): [TPMU] GetMccFromDB : null
,I/SA      ( 6551): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6551): [TPM] isNoProxy(default) : true
,I/KnoxUsageLogPro( 7415): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 7415): premStatus:2
,I/KnoxUsageLogPro( 7415): isEulaShown : false
I/KnoxUsageLogPro( 7415): KnoxUsageReceiver onReceive : not Processible, just return
,D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,E/File    ( 6551): fail readDirectory() errno=2
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 7514): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7514): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 7514): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  898): exchangeData() failure , invalid userId
,D/RCPManagerService(  898): exchangeData() failure , invalid userId
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6968): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6968): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6968): StateMachine : Current State = 1
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 6968): StateMachine : Changed Current State = 1
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/iu.Environment( 2297): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/iu.UploadsManager( 2297): num queued entries: 0
,I/iu.UploadsManager( 2297): num updated entries: 0
,I/iu.SyncManager( 2297): NEXT; no task
,D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 5273): notifyNetworkActivated
,D/hcjo    ( 5273): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5273): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5273): exit::IDLE
D/InitializeManagerStateMachine( 5273): entry::NETWORK_CHECK
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 5273): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5273): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5273): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5273): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5273): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5273): entry::SUCCESS
D/hcjo    ( 5273): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5273): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 5273): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 5273): exit::SUCCESS
D/InitializeManagerStateMachine( 5273): entry::IDLE
,D/ConnectivityService(  898): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
,D/ConnectivityService(  898): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService(  898): identical MTU - not setting
D/ConnectivityService(  898): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  898): updateSourceRoutes : add src route for:fe80::ea50:8bff:fede:28a3
,D/SmartBondingService(  898): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
V/        (  282): QcRouteController
D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  898): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  898): getSBEnabled() enabled =false
D/SmartBondingService(  898): getSBEnabled() enabled =false
D/SmartBondingService(  898): getSBEnabled() enabled =false
,V/        (  282): QcRouteController
,W/NetworkManagementService(  898): route cmd failed: 
W/NetworkManagementService(  898): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '74 route replace src v6 wlan0 fe80::ea50:8bff:fede:28a3 2 ::' failed with '400 74 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  898): '
W/NetworkManagementService(  898): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService(  898): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService(  898): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService(  898): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService(  898): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  898): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5625)
W/NetworkManagementService(  898): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5437)
W/NetworkManagementService(  898): 	at com.android.server.ConnectivityService.access$2300(ConnectivityService.java:229)
W/NetworkManagementService(  898): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2382)
W/NetworkManagementService(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  898): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
V/Nat464Xlat(  898): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  898): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  898): calling update connectivity
,D/ConnectivityService(  898):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  898):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  898): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  898):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1183): CM callback handler got msg 524295
,D/ConnectivityService(  898): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 2297): CM callback handler got msg 524295
D/ConnectivityService(  898): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  898): calling update connectivity
D/ConnectivityService(  898):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  898):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  898): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  898):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1183): CM callback handler got msg 524295
,D/ConnectivityService(  898): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 2297): CM callback handler got msg 524295
,D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PowerManagerService(  898): [PWL] Off : 75s ago
,I/SA      ( 6551): [RC New] Execute method=[GET] start
,I/SA      ( 6551): [RC New] Security=[true]
,I/System.out( 6551): Thread-1065(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6551): Thread-1065(ApacheHTTPLog):isShipBuild true
,I/System.out( 6551): Thread-1065(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/PackageManager(  898): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/dhcpcd  ( 7433): wlan0: sending IPv6 Router Solicitation
,I/SA      ( 6551): [RC New] [v2liruge] api execute + 908
,I/SA      ( 6551): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6551): AsyncTask #1 calls detatch()
,I/SA      ( 6551): [TPMU] getNetworkMcc : 
,I/SA      ( 6551): [SCU] saveMccToPreferece Start
,I/SA      ( 6551): [SCU] RegionMCC : 260
,I/SA      ( 6551): [SSP] query invoked
,I/SA      ( 6551): [TPMU] GetMccFromDB : null
,I/SA      ( 6551): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6551): [SCU] saveMccToPreferece End
,I/SA      ( 6551): [RC New] executeRequest [v2liruge] end. 1026
,I/SA      ( 6551): [RC New] Execute end
,I/SA      ( 6551): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 6551): [OR] GetMyCountryZoneTask Success
,I/jxcore-log( 7186): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7186): 
,I/ClearcutLoggerApiImpl( 1949): disconnect managed GoogleApiClient
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 4
,E/WifiStateMachine(  898): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/SurfaceFlinger(  254): id=15 Removed Uoast (8/9)
,I/SurfaceFlinger(  254): id=15 Removed Uoast (-2/9)
,D/PowerManagerService(  898): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 898) eventTime = 163957
,D/PowerManagerService(  898): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=898 (0x0)
,D/PowerManagerService(  898): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=898, ws=WorkSource{10067}) (elapsedTime=3520)
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7186): setDiscoveryMode: Failed to set discovery mode to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7186): setDiscoveryMode: Mode set to WIFI
,I/jxcore-log( 7186): BLE supported!!
I/jxcore-log( 7186): 
,I/GAV4    ( 7456): Thread[GAThread,5,main]: No campaign data found.
,E/SMD     (  290): DCD ON
,D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  898): waitForAlarm result :8
,E/Watchdog(  898): !@Sync 5
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6465): mConnectivityHandler : connected
,D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 6465): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE( 6465): ================================================
,I/CSTORAGE( 6465):  CSTORAGE_SKM_LIB v1.0.6
I/CSTORAGE( 6465): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 6465): [GetString-S]
,E/art     ( 6465): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6465): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 6465): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 6465): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6465): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6465): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6465): [ensureRegistration] - No Samsung account
,I/dhcpcd  ( 7433): wlan0: sending IPv6 Router Solicitation
,E/SMD     (  290): DCD ON
,I/jxcore-log( 7186): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7186): 
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/SSRM:n  (  898): SIOP:: AP = 330, PST = 329, CUR = 450
,E/SMD     (  290): DCD ON,
,I/dhcpcd  ( 7433): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 7433): wlan0: no IPv6 Routers available
,D/PreloadUpdateManagerStateMachine( 5273): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5273): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5273): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5273): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5273): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5273): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5273): entry::IDLE
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7186): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7186): 
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,I/jxcore-log( 7186): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7186): 
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): stay LED for fully charged
D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/SSRM:n  (  898): SIOP:: AP = 310, PST = 324, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,I/jxcore-log( 7186): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7186): 
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/jxcore-log( 7186): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7186): 
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  898): stay LED for fully charged
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/SSRM:n  (  898): SIOP:: AP = 310, PST = 319, CUR = 450
,E/SMD     (  290): DCD ON
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  290): DCD ON
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  898): [PWL] Off : 105s ago
,I/jxcore-log( 7186): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7186): 
,E/SMD     (  290): DCD ON
,E/Watchdog(  898): !@Sync 6
,E/SMD     (  290): DCD ON
,I/jxcore-log( 7186): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7186): 
,D/SSRM:n  (  898): SIOP:: AP = 300, PST = 316, CUR = 450
,V/AlarmManager(  898): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1183): handleTimeUpdate
,D/KeyguardEffectViewController( 1183): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1183): *** don't update sliding image ***
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  290): DCD ON
,I/jxcore-log( 7186): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7186): 
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,I/jxcore-log( 7186): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7186): 
,D/SSRM:n  (  898): SIOP:: AP = 300, PST = 314, CUR = 450
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD ON
,I/jxcore-log( 7186): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7186): 
,I/Atfwd_Sendcmd(  327): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  327): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  290): DCD ON
,I/jxcore-log( 7186): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7186): 
,D/SSRM:n  (  898): SIOP:: AP = 300, PST = 312, CUR = 450
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true,
,D/BatteryService(  898): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,E/SMD     (  290): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,E/SMD     (  290): DCD ON
,I/jxcore-log( 7186): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7186): 
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,V/AlarmManager(  898): waitForAlarm result :8
,E/Watchdog(  898): !@Sync 7
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/PowerManagerService(  898): [PWL] Off : 140s ago
,E/SMD     (  290): DCD ON
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/jxcore-log( 7186): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7186): 
,D/SSRM:n  (  898): SIOP:: AP = 300, PST = 311, CUR = 450
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  290): DCD ON
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7186): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7186): 
,E/SMD     (  290): DCD ON
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/jxcore-log( 7186): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7186): 
,D/SSRM:n  (  898): SIOP:: AP = 300, PST = 310, CUR = 450
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryService(  898): stay LED for fully charged
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,I/jxcore-log( 7186): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7186): 
,E/SMD     (  290): DCD ON
,I/jxcore-log( 7186): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7186): 
,D/SSRM:n  (  898): SIOP:: AP = 300, PST = 309, CUR = 450
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryService(  898): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/jxcore-log( 7186): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7186): 
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  290): DCD ON
,E/Watchdog(  898): !@Sync 8
,E/SMD     (  290): DCD ON
,I/jxcore-log( 7186): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7186): 
,D/SSRM:n  (  898): SIOP:: AP = 300, PST = 305, CUR = 450
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  898): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,E/SMD     (  290): DCD ON
,I/jxcore-log( 7186): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7186): 
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,I/PowerManagerService(  898): [PWL] Off : 180s ago
,I/jxcore-log( 7186): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7186): 
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 301, CUR = 450
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD ON
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/jxcore-log( 7186): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7186): 
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  290): DCD ON
,I/jxcore-log( 7186): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7186): 
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 299, CUR = 450
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryService(  898): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,E/SMD     (  290): DCD ON
,I/jxcore-log( 7186): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7186): 
,E/SMD     (  290): DCD ON
,E/Watchdog(  898): !@Sync 9
,E/SMD     (  290): DCD ON
,I/jxcore-log( 7186): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7186): 
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 297, CUR = 450
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD ON
,I/jxcore-log( 7186): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7186): 
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/jxcore-log( 7186): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7186): 
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 296, CUR = 450
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 5
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,I/jxcore-log( 7186): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7186): 
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,I/jxcore-log( 7186): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7186): 
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 295, CUR = 450
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  898): [PWL] Off : 225s ago
,D/TimaService(  898): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  898): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  898): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  898): initializing...
,I/TLC_TIMA_PKM_initialize(  898): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  898): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  898): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  898): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  898): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  898): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  898): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  898): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  898): App is not loaded in QSEE
,D/QSEECOMAPI: (  898): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  898): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  898): Trustlet response is completed
,I/jxcore-log( 7186): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7186): 
,E/SMD     (  290): DCD ON
,E/Watchdog(  898): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel(  898): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  898): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  898): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  898): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  290): DCD ON
,I/jxcore-log( 7186): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7186): 
,D/SSRM:n  (  898): SIOP:: AP = 300, PST = 295, CUR = 450
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,I/Atfwd_Sendcmd(  327): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  327): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/jxcore-log( 7186): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7186): 
,E/SMD     (  290): DCD ON
,I/jxcore-log( 7186): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7186): 
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 294, CUR = 450
,E/SMD     (  290): DCD ON
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD ON
,V/AlarmManager(  898): waitForAlarm result :4
,E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/Zygote  ( 7721): MountEmulatedStorage()
,E/Zygote  ( 7721): v2
I/libpersona( 7721): KNOX_SDCARD checking this for 10096
I/libpersona( 7721): KNOX_SDCARD not a persona
,I/ActivityManager(  898): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=7721 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7721): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7721): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7721): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1183): handleTimeUpdate
,D/KeyguardEffectViewController( 1183): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1183): *** don't update sliding image ***
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/TimaKeyStoreProvider( 7721): TimaSignature is unavailable
,D/ActivityThread( 7721): Added TimaKeyStore provider
,I/jxcore-log( 7186): DBG, CoordinatorConnector connect called
I/jxcore-log( 7186): 
I/jxcore-log( 7186): Coordinator is now connected to the server!
I/jxcore-log( 7186): 
,D/ResourcesManager( 7721): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,I/chromium( 7186): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,I/ActivityManager(  898): Killing 6714:com.samsung.android.app.watchmanagerstub/u0a126 (adj 13): bgCount ##41
,E/SMD     (  290): DCD ON
,I/ActivityManager(  898): Killing 6729:com.samsung.helphub/1000 (adj 13): bgCount ##41
,E/SMD     (  290): DCD ON
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 293, CUR = 450
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 1
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  898): stay LED for fully charged
,E/SMD     (  290): DCD ON
,V/AlarmManager(  898): waitForAlarm result :8
,E/Watchdog(  898): !@Sync 11
,E/SMD     (  290): DCD ON
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 292, CUR = 450
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 2
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  898): stay LED for fully charged
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 291, CUR = 450
,E/SMD     (  290): DCD ON
,I/PowerManagerService(  898): [PWL] Off : 275s ago
,E/SMD     (  290): DCD ON
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  898): stay LED for fully charged
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 291, CUR = 450
,E/SMD     (  290): DCD ON
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,E/Watchdog(  898): !@Sync 12
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 291, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 4
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 291, CUR = 450
,E/SMD     (  290): DCD ON
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  898): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 291, CUR = 450
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,E/Watchdog(  898): !@Sync 13
,E/SMD     (  290): DCD ON
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 291, CUR = 450
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 5
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  898): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,E/SMD     (  290): DCD ON
,I/PowerManagerService(  898): [PWL] Off : 330s ago
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryService(  898): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  290): DCD ON
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  898): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,E/SMD     (  290): DCD ON
,E/Watchdog(  898): !@Sync 14
,E/SMD     (  290): DCD ON
,I/Atfwd_Sendcmd(  327): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  327): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryService(  898): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,E/SMD     (  290): DCD ON
,I/jxcore-log( 7186): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): DBG, CoordinatorConnector command called
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":20000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":14,"addressList":[{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"F8:CF:C5:D9:E5:61","tryCount":0},{"address":"34:FC:EF:11:AE:67","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"90:E7:C4:F6:69:77","tryCount":0},{"address":"B0:C5:59:3F:75:69","tryCount":0},{"address":"7C:F9:0E:51:18:22","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0}]}
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): Start now : testSendData.js
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 14
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): check server
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): serverPort is 34740
I/jxcore-log( 7186): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7186): setDiscoveryMode: Failed to set discovery mode to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7186): setDiscoveryMode: Mode set to WIFI
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7186): setDiscoveryMode: Failed to set discovery mode to BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7186): setDiscoveryMode: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7186): start: Peer ID: E0:DB:10:1F:C9:5E, peer name: samsung-SM-N9005_PT2526
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7186): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7186): initialize: My bluetooth address is E0:DB:10:1F:C9:5E
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7186): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2526","ra":"E0:DB:10:1F:C9:5E"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7186): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7186): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7186): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 7186): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 7186): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[115]}
,D/BluetoothSocket( 7186): bindListen(), new LocalSocket 
D/BluetoothSocket( 7186): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 7186): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@34b6fced
D/BluetoothSocket( 7186): channel: 6
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7186): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7186): start: OK
,I/io.jxcore.node.ConnectionHelper( 7186): start: Using peer discovery mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7186): start: Peer ID: E0:DB:10:1F:C9:5E, peer name: samsung-SM-N9005_PT2526
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7186): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2526","ra":"E0:DB:10:1F:C9:5E"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7186): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7186): start: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2526","ra":"E0:DB:10:1F:C9:5E"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7186): start: Identity string: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2526","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7186): Waiting for incoming connections...
,D/WifiP2pService(  898): InactiveState{ what=139292 }
,D/WifiP2pService(  898): P2pEnabledState{ what=139292 }
,D/WifiP2pService(  898): P2pEnabledState add service
,D/WifiP2pService(  898): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7186): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7186): start: Starting P2P device discovery...
,D/WifiP2pService(  898): InactiveState{ what=139265 }
,D/WifiP2pService(  898): P2pEnabledState{ what=139265 }
D/WifiService(  898): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine(  898): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL(  898): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1268): USE_NETWORK : USE_NETWORK OFF
,D/WifiP2pService(  898): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7186): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7186): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7186): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7186): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 7186): start: OK
,I/jxcore-log( 7186): StartBroadcasting started ok,
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): do fake peer & start
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): Connect to fake peer: 08:EC:A9:50:75:41
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:43.671Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:43.672Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 7186): 
I/jxcore-log( 7186): 2015-12-17T14:16:43.672Z SendDataConnector.js: do connect now
I/jxcore-log( 7186): 
,I/io.jxcore.node.ConnectionHelper( 7186): connect: Trying to connect to peer with ID 08:EC:A9:50:75:41
,D/io.jxcore.node.ConnectionHelper( 7186): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
W/io.jxcore.node.ConnectionHelper( 7186): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7186): connect: [08:EC:A9:50:75:41 08:EC:A9:50:75:41]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7186): connect: Trying to start connecting to null in address 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7186): setInsecureRfcommSocketPort: Using port -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7186): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7186): onConnecting: null 08:EC:A9:50:75:41
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7186): connect: Started connecting to null in address 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 7186): connect: Connection process successfully started (peer ID: 08:EC:A9:50:75:41)
,I/jxcore-log( 7186): 2015-12-17T14:16:43.682Z SendDataTCPServer.js: TCP/IP server is bound to port: 34740
I/jxcore-log( 7186): 
,I/io.jxcore.node.ConnectionHelper( 7186): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7186): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7186): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7186): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7186): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7186): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 7186): onDiscoveryManagerStateChanged: RUNNING
,I/chromium( 7186): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7186): Trying to connect to peer with address 08:EC:A9:50:75:41 (thread ID: 1198)
,D/BluetoothUtils( 7186): isSocketAllowedBySecurityPolicy start : device null
,W/BluetoothAdapter( 7186): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2938): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/IOP_DB_BT( 2938): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:75:41
D/IOP_DB_BT( 2938): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 2938): db_query_add_key: key KEY_LMP_VER, value 7:2003
D/IOP_DB_BT( 2938): db_query_add_key: key KEY_DIR_ALL, value 1
,D/IOP_DB_BT( 2938): db_query_execute: result 1
,D/bt_vendor( 2938): op for 7
,D/BluetoothSocket( 7186): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[116]}
,D/bt_upio ( 2938): proc btwrite assertion
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  290): DCD ON
,D/IOP_DB_BT( 2938): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:51:18:22
,D/IOP_DB_BT( 2938): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 2938): db_query_add_key: key KEY_LMP_VER, value 7:2003
D/IOP_DB_BT( 2938): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2938): db_query_execute: result 1
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/IOP_DB_BT( 2938): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,D/IOP_DB_BT( 2938): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 2938): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 2938): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2938): db_query_execute: result 1
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/IOP_DB_BT( 2938): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:51:18:22
,D/bt_vendor( 2938): op for 7
D/IOP_DB_BT( 2938): db_query_add_key: key KEY_LMP_MFCT, value 29
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/IOP_DB_BT( 2938): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 2938): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2938): db_query_execute: result 1
,W/bt-btif ( 2938): info:x10
D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
D/        ( 2938): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2938): aclStateChangeCallback: Device is NULL
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.NAME_CHANGED
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_upio ( 2938): ..proc_btwrite_timeout..
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_upio ( 2938): proc btwrite assertion
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/IOP_DB_BT( 2938): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
D/IOP_DB_BT( 2938): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 2938): db_query_add_key: key KEY_LMP_VER, value 7:8975
,D/IOP_DB_BT( 2938): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 2938): db_query_execute: result 1
,W/bt-btif ( 2938): info:x10
D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/        ( 2938): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,E/BluetoothRemoteDevices( 2938): aclStateChangeCallback: Device is NULL
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.NAME_CHANGED
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,E/bt-btm  ( 2938): tBTM_SEC_DEV:0xa1ce571c rs_disc_pending=1
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,W/bt-btif ( 2938): bta_dm_check_av:0
,W/bt-btif ( 2938): btif_dm_cback : unhandled event (14)
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothBondStateMachine( 2938): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 1
,D/SecContentProvider(  898): uri = 4 selection = bluetoothLogForRemote
,E/bt-btif ( 2938): check_cod: remote_cod = 0x5a020c
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/BluetoothTile( 1183):  onBluetoothPairedDevicesChanged:
,I/BluetoothBondStateMachine( 2938): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 10 NewState: 11
,D/BtConfig.SecureMode( 2938): isSecureModeOn:false
I/BluetoothBondStateMachine( 2938): Entering PendingCommandState State
,D/BluetoothTile( 1183):  handleUpdatestate:false name:null
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.CLASS_CHANGED
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothNotiBroadcastReceiver( 1325): onReceive
,E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7778): MountEmulatedStorage()
,E/Zygote  ( 7778): v2
,I/libpersona( 7778): KNOX_SDCARD checking this for 10126
I/libpersona( 7778): KNOX_SDCARD not a persona
,I/ActivityManager(  898): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/.GMHFPReceiver: pid=7778 uid=10126 gids={50126, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 7778): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
E/SMD     (  290): DCD ON
,I/SELinux ( 7778): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7778): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7778): TimaSignature is unavailable
,D/ActivityThread( 7778): Added TimaKeyStore provider
,D/ResourcesManager( 7778): creating new AssetManager and set to /system/app/GearManagerStub/GearManagerStub.apk
,E/BluetoothHeadset( 7778): BTStateChangeCB is registed
,E/BluetoothHeadset( 7778): BluetoothHeadset service is binded
D/GMFPReceiver( 7778): android.bluetooth.device.action.BOND_STATE_CHANGED
,D/GMFPReceiver( 7778): jangil::setProperties()
,D/GMFPReceiver( 7778): jangil::printBTStatus()
,D/SettingsProvider(  898): name = Wearable0001
D/SettingsProvider(  898): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  898): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  898): selectionArgs: false
D/SettingsProvider(  898): selectionArgs: 10126
D/SecContentProvider(  898): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  898): ret = -1
,W/BackupManagerService(  898): dataChanged but no participant pkg='com.android.providers.settings' uid=10126
,D/GMFPReceiver( 7778): ::::::::Wearable0001::false
,D/SettingsProvider(  898): name = Wearable0002
,D/SettingsProvider(  898): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider(  898): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  898): selectionArgs: false
,D/SettingsProvider(  898): selectionArgs: 10126
,D/SecContentProvider(  898): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  898): ret = -1
,W/BackupManagerService(  898): dataChanged but no participant pkg='com.android.providers.settings' uid=10126
,D/GMFPReceiver( 7778): ::::::::Wearable0002::false
,I/ActivityManager(  898): Killing 6780:com.samsung.android.snote:provider/u0a168 (adj 13): bgCount ##41
,D/GMFPReceiver( 7778): onServiceConnected() : 1
,D/GMFPReceiver( 7778): mBluetoothHeadset = true
,E/bt-btm  ( 2938): tBTM_SEC_DEV:0xa1ce571c rs_disc_pending=0
W/bt-btif ( 2938): bta_dm_check_av:0
W/bt-btif ( 2938): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 1268): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService(  898): InactiveState{ what=147477 }
,D/WifiP2pService(  898): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  898): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  898): InactiveState{ what=139283 }
D/WifiP2pService(  898): P2pEnabledState{ what=139283 }
D/WifiP2pService(  898): DefaultState{ what=139283 }
D/WifiP2pService(  898): InactiveState{ what=139283 }
,D/WifiP2pService(  898): P2pEnabledState{ what=139283 }
D/WifiP2pService(  898): DefaultState{ what=139283 }
,D/WifiDisplayController(  898): Received list of peers.
,D/WifiDisplayController(  898):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7186): onP2pDeviceListChanged: 1 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7186): onP2pDeviceListChanged: Peer 1: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService(  898): InactiveState{ what=139301 }
,D/btif_config_util( 2938): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/WifiP2pService(  898): P2pEnabledState{ what=139301 }
,D/WifiP2pService(  898): P2pEnabledState add service request
,D/WifiP2pManager( 7186): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7186): Service request added successfully
,I/BluetoothBondStateMachine( 2938): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 0
,D/BluetoothAdapterProperties( 2938): Failed to remove device: 7C:F9:0E:51:18:22
,D/SecContentProvider(  898): uri = 4 selection = bluetoothLogForRemote
,I/BluetoothBondStateMachine( 2938): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 11 NewState: 10
,D/BtConfig.SecureMode( 2938): isSecureModeOn:false
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothTile( 1183):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 1183):  handleUpdatestate:false name:null
,D/BluetoothNotiBroadcastReceiver( 1325): onReceive
,E/BluetoothHeadset( 7778): BTStateChangeCB is registed
D/HidService( 2938): getHidService(): returning com.android.bluetooth.hid.HidService@3788451a
,D/SettingsProvider(  898): name = bluetooth_input_device_priority_7C:F9:0E:51:18:22
,D/SettingsProvider(  898): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  898): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  898): selectionArgs: false
,D/SettingsProvider(  898): selectionArgs: 1002
D/SecContentProvider(  898): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  898): ret = -1
D/HidService( 2938): Saved priority 7C:F9:0E:51:18:22 = -1
,D/SettingsProvider(  898): name = bluetooth_a2dp_sink_priority_7C:F9:0E:51:18:22
D/SettingsProvider(  898): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider(  898): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  898): selectionArgs: false
D/SettingsProvider(  898): selectionArgs: 1002
D/SecContentProvider(  898): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  898): ret = -1
E/BluetoothHeadset( 7778): BluetoothHeadset service is binded
D/GMFPReceiver( 7778): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 7778): jangil::setProperties()
,D/SettingsProvider(  898): name = bluetooth_headset_priority_7C:F9:0E:51:18:22
D/SettingsProvider(  898): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  898): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  898): selectionArgs: false
D/SettingsProvider(  898): selectionArgs: 1002
D/SecContentProvider(  898): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  898): ret = -1
,I/BluetoothBondStateMachine( 2938): StableState(): Entering Off State
,D/GMFPReceiver( 7778): jangil::printBTStatus()
,D/SettingsProvider(  898): name = Wearable0001
,D/SettingsProvider(  898): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  898): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  898): selectionArgs: false
D/SettingsProvider(  898): selectionArgs: 10126
D/SecContentProvider(  898): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  898): ret = -1
D/GMFPReceiver( 7778): ::::::::Wearable0001::false
D/SettingsProvider(  898): name = Wearable0002
,D/SettingsProvider(  898): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  898): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  898): selectionArgs: false
D/SettingsProvider(  898): selectionArgs: 10126
,D/SecContentProvider(  898): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  898): ret = -1
D/GMFPReceiver( 7778): ::::::::Wearable0002::false
,D/GMFPReceiver( 7778): onServiceConnected() : 1
,D/GMFPReceiver( 7778): mBluetoothHeadset = true
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
D/bt_vendor( 2938): op for 7,
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,W/bt-btif ( 2938): new conn_srvc id:26, app_id:255
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,W/bt-btif ( 2938): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 2938): bta_dm_pm_ssr:2, lat:1200
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/BluetoothSocket( 7186): socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@21937ae9
,E/BluetoothRemoteDevices( 2938): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7186): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7186): Incoming connection initialized (thread ID: 1199)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7186): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7186): Entering thread (ID: 1199)
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7186): onBytesRead: Read 83 bytes successfully (thread ID: 1199)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7186): Got valid identity from [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4673]
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7186): onBytesWritten: 82 bytes successfully written (thread ID: 1199)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7186): removeThreadFromList: Removing thread with ID 1199
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7186): Handshake thread disposed (thread ID: 1199)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7186): onIncomingConnectionConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4673]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7186): Exiting thread (ID: 1199)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7186): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4673]
,I/io.jxcore.node.ConnectionHelper( 7186): onConnected: Incoming connection to peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4673]
,D/io.jxcore.node.ConnectionHelper( 7186): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
,D/io.jxcore.node.ConnectionHelper( 7186): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4673] is available
,I/io.jxcore.node.ConnectionHelper( 7186): onConnected: Incoming socket thread, for peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4673], created successfully
,D/io.jxcore.node.ConnectionHelper( 7186): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 7186): Entering thread (ID: 1200)
,I/io.jxcore.node.IncomingSocketThread( 7186): Local host address: localhost/127.0.0.1, port: 34740
,I/jxcore-log( 7186): 2015-12-17T14:16:47.872Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 7186): 
,D/io.jxcore.node.IncomingSocketThread( 7186): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 7186): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 7186): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 7186): startStreamCopyingThreads: OK
,D/io.jxcore.node.IncomingSocketThread( 7186): Exiting thread (ID: 1200)
,D/io.jxcore.node.StreamCopyingThread( 7186): Entering thread (ID: 1202, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 7186): Entering thread (ID: 1201, name: Sender)
,E/bt-btm  ( 2938): tBTM_SEC_DEV:0xa1ce571c rs_disc_pending=1
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,W/bt-btif ( 2938): bta_dm_check_av:0
,W/bt-btif ( 2938): btif_dm_cback : unhandled event (14)
,D/bt_upio ( 2938): ..proc_btwrite_timeout..
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_upio ( 2938): proc btwrite assertion
,D/WifiP2pService(  898): InactiveState{ what=139310 }
,D/WifiP2pService(  898): P2pEnabledState{ what=139310 }
,D/WifiP2pService(  898): P2pEnabledState discover services
,D/WifiService(  898): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine(  898): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL(  898): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1268): USE_NETWORK : USE_NETWORK OFF
,I/wpa_supplicant( 1268): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7186): Service discovery started successfully
,I/wpa_supplicant( 1268): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): stay LED for fully charged
D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,I/jxcore-log( 7186): 2015-12-17T14:16:48.973Z SendDataTCPServer.js: TCP/IP server has received 2024 bytes of data
I/jxcore-log( 7186): 
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,I/jxcore-log( 7186): 2015-12-17T14:16:49.255Z SendDataTCPServer.js: TCP/IP server has received 4048 bytes of data
I/jxcore-log( 7186): 
,E/SMD     (  290): DCD ON
,D/bt_upio ( 2938): ..proc_btwrite_timeout..
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothBondStateMachine( 2938): bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 1
,D/SecContentProvider(  898): uri = 4 selection = bluetoothLogForRemote
,E/bt-btif ( 2938): check_cod: remote_cod = 0x5a020c
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_upio ( 2938): proc btwrite assertion
,D/BluetoothTile( 1183):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 1183):  handleUpdatestate:false name:null
,I/BluetoothBondStateMachine( 2938): Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 10 NewState: 11
D/BtConfig.SecureMode( 2938): isSecureModeOn:false
,I/BluetoothBondStateMachine( 2938): Entering PendingCommandState State
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.CLASS_CHANGED
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothNotiBroadcastReceiver( 1325): onReceive
,W/bt-sdp  ( 2938): SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,E/bt-btif ( 2938): DISCOVERY_COMP_EVT slot id:5, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2938): invalid rfc slot id: 5
D/BluetoothSocket( 7186): close() in, this: android.bluetooth.BluetoothSocket@3474836e, channel: -1, state: INIT
,D/BluetoothSocket( 7186): close() this: android.bluetooth.BluetoothSocket@3474836e, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2abbaa0f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@36522a9cmSocket: android.net.LocalSocket@3a9fdca5 impl:android.net.LocalSocketImpl@37e9687a fd:FileDescriptor[116]
D/BluetoothSocket( 7186): Closing mSocket: android.net.LocalSocket@3a9fdca5 impl:android.net.LocalSocketImpl@37e9687a fd:FileDescriptor[116]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7186): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 1198)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7186): Maximum number of allowed retries (0) reached, giving up... (thread ID: 1198)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7186): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7186): Exiting thread (thread ID: 1198)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7186): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [08:EC:A9:50:75:41 08:EC:A9:50:75:41]
,I/jxcore-log( 7186): 2015-12-17T14:16:50.131Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [08:EC:A9:50:75:41 08:EC:A9:50:75:41] failed
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:50.131Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [08:EC:A9:50:75:41 08:EC:A9:50:75:41] failed
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:50.132Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 7186): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7186): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7186): shutdown (thread ID: 1198)
,D/BluetoothSocket( 7186): close() in, this: android.bluetooth.BluetoothSocket@3474836e, channel: -1, state: CLOSED
,E/BluetoothHeadset( 7778): BTStateChangeCB is registed
,E/BluetoothHeadset( 7778): BluetoothHeadset service is binded
,D/GMFPReceiver( 7778): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 7778): jangil::setProperties()
,D/GMFPReceiver( 7778): jangil::printBTStatus()
,D/SettingsProvider(  898): name = Wearable0001
,D/SettingsProvider(  898): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  898): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  898): selectionArgs: false
,D/SettingsProvider(  898): selectionArgs: 10126
D/SecContentProvider(  898): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  898): ret = -1
,D/GMFPReceiver( 7778): ::::::::Wearable0001::false
,D/SettingsProvider(  898): name = Wearable0002
D/SettingsProvider(  898): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  898): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider(  898): selectionArgs: false
D/SettingsProvider(  898): selectionArgs: 10126
D/SecContentProvider(  898): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  898): ret = -1
D/GMFPReceiver( 7778): ::::::::Wearable0002::false
,D/GMFPReceiver( 7778): onServiceConnected() : 1
,D/GMFPReceiver( 7778): mBluetoothHeadset = true
,D/btif_config_util( 2938): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 2938): bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 0
,D/BluetoothAdapterProperties( 2938): Failed to remove device: F8:CF:C5:D9:E5:61
,D/SecContentProvider(  898): uri = 4 selection = bluetoothLogForRemote
,D/BluetoothTile( 1183):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 1183):  handleUpdatestate:false name:null
,I/BluetoothBondStateMachine( 2938): Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 11 NewState: 10
,D/BtConfig.SecureMode( 2938): isSecureModeOn:false
,D/HidService( 2938): getHidService(): returning com.android.bluetooth.hid.HidService@3788451a
,D/SettingsProvider(  898): name = bluetooth_input_device_priority_F8:CF:C5:D9:E5:61
,D/SettingsProvider(  898): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  898): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  898): selectionArgs: false
D/SettingsProvider(  898): selectionArgs: 1002
,D/SecContentProvider(  898): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  898): ret = -1
,D/HidService( 2938): Saved priority F8:CF:C5:D9:E5:61 = -1
,D/SettingsProvider(  898): name = bluetooth_a2dp_sink_priority_F8:CF:C5:D9:E5:61
,D/SettingsProvider(  898): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  898): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  898): selectionArgs: false
D/SettingsProvider(  898): selectionArgs: 1002
,D/SecContentProvider(  898): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  898): ret = -1
,D/SettingsProvider(  898): name = bluetooth_headset_priority_F8:CF:C5:D9:E5:61
,D/SettingsProvider(  898): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  898): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  898): selectionArgs: false
D/SettingsProvider(  898): selectionArgs: 1002
,D/SecContentProvider(  898): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  898): ret = -1
I/BluetoothBondStateMachine( 2938): StableState(): Entering Off State
,I/jxcore-log( 7186): 2015-12-17T14:16:50.256Z SendDataTCPServer.js: TCP/IP server has received 6072 bytes of data
I/jxcore-log( 7186): 
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,I/jxcore-log( 7186): 2015-12-17T14:16:50.260Z SendDataTCPServer.js: TCP/IP server has received 8096 bytes of data
I/jxcore-log( 7186): 
,D/BluetoothNotiBroadcastReceiver( 1325): onReceive
,I/jxcore-log( 7186): 2015-12-17T14:16:50.266Z SendDataTCPServer.js: TCP/IP server has received 10120 bytes of data
I/jxcore-log( 7186): 
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,E/BluetoothHeadset( 7778): BTStateChangeCB is registed
,E/BluetoothHeadset( 7778): BluetoothHeadset service is binded
,D/GMFPReceiver( 7778): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 7778): jangil::setProperties()
,D/GMFPReceiver( 7778): jangil::printBTStatus()
,D/SettingsProvider(  898): name = Wearable0001
,D/SettingsProvider(  898): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  898): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  898): selectionArgs: false
D/SettingsProvider(  898): selectionArgs: 10126
,D/SecContentProvider(  898): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  898): ret = -1
,D/GMFPReceiver( 7778): ::::::::Wearable0001::false
,D/SettingsProvider(  898): name = Wearable0002
,D/SettingsProvider(  898): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider(  898): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  898): selectionArgs: false
D/SettingsProvider(  898): selectionArgs: 10126
,D/SecContentProvider(  898): uri = 17 selection = isSettingsChangesAllowed
I/jxcore-log( 7186): 2015-12-17T14:16:50.285Z SendDataTCPServer.js: TCP/IP server has received 12144 bytes of data
I/jxcore-log( 7186): 
D/SettingsProvider(  898): ret = -1
,D/GMFPReceiver( 7778): ::::::::Wearable0002::false
,D/GMFPReceiver( 7778): onServiceConnected() : 1
,D/GMFPReceiver( 7778): mBluetoothHeadset = true
,I/jxcore-log( 7186): 2015-12-17T14:16:50.319Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:50.327Z SendDataTCPServer.js: TCP/IP server has received 18408 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:50.343Z SendDataTCPServer.js: TCP/IP server has received 20432 bytes of data
I/jxcore-log( 7186): 
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,E/bt-btm  ( 2938): tBTM_SEC_DEV:0xa1ce571c rs_disc_pending=0
,W/bt-btif ( 2938): bta_dm_check_av:0
,W/bt-btif ( 2938): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 7186): 2015-12-17T14:16:50.432Z SendDataTCPServer.js: TCP/IP server has received 22456 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:50.458Z SendDataTCPServer.js: TCP/IP server has received 24480 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:50.466Z SendDataTCPServer.js: TCP/IP server has received 26504 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:50.480Z SendDataTCPServer.js: TCP/IP server has received 28528 bytes of data
I/jxcore-log( 7186): 
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,I/jxcore-log( 7186): 2015-12-17T14:16:51.060Z SendDataTCPServer.js: TCP/IP server has received 30552 bytes of data
I/jxcore-log( 7186): 
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,I/jxcore-log( 7186): 2015-12-17T14:16:51.149Z SendDataTCPServer.js: TCP/IP server has received 32576 bytes of data
I/jxcore-log( 7186): 
,W/bt-btif ( 2938): new conn_srvc id:26, app_id:255
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,W/bt-btif ( 2938): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 2938): bta_dm_pm_ssr:2, lat:1200
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/BluetoothSocket( 7186): socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@3492d82b
,E/BluetoothRemoteDevices( 2938): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7186): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7186): Incoming connection initialized (thread ID: 1204)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7186): Waiting for incoming connections...
,I/jxcore-log( 7186): 2015-12-17T14:16:51.197Z SendDataTCPServer.js: TCP/IP server has received 34792 bytes of data
I/jxcore-log( 7186): 
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7186): Entering thread (ID: 1204)
,I/jxcore-log( 7186): 2015-12-17T14:16:51.212Z SendDataTCPServer.js: TCP/IP server has received 36816 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:51.258Z SendDataTCPServer.js: TCP/IP server has received 38840 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:51.289Z SendDataTCPServer.js: TCP/IP server has received 40864 bytes of data
I/jxcore-log( 7186): 
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,I/jxcore-log( 7186): 2015-12-17T14:16:51.336Z SendDataTCPServer.js: TCP/IP server has received 42888 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:51.465Z SendDataTCPServer.js: TCP/IP server has received 44912 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:51.476Z SendDataTCPServer.js: TCP/IP server has received 46936 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:51.505Z SendDataTCPServer.js: TCP/IP server has received 49152 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:51.536Z SendDataTCPServer.js: TCP/IP server has received 51176 bytes of data
I/jxcore-log( 7186): 
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,I/jxcore-log( 7186): 2015-12-17T14:16:51.593Z SendDataTCPServer.js: TCP/IP server has received 53200 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:51.667Z SendDataTCPServer.js: TCP/IP server has received 55224 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:51.676Z SendDataTCPServer.js: TCP/IP server has received 57248 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:51.686Z SendDataTCPServer.js: TCP/IP server has received 59272 bytes of data,
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:51.761Z SendDataTCPServer.js: TCP/IP server has received 61296 bytes of data
I/jxcore-log( 7186): 
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,I/jxcore-log( 7186): 2015-12-17T14:16:51.779Z SendDataTCPServer.js: TCP/IP server has received 63320 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:51.841Z SendDataTCPServer.js: TCP/IP server has received 65344 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:51.850Z SendDataTCPServer.js: TCP/IP server has received 65536 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:51.881Z SendDataTCPServer.js: TCP/IP server has received 67560 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:51.888Z SendDataTCPServer.js: TCP/IP server has received 69584 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:51.921Z SendDataTCPServer.js: TCP/IP server has received 71608 bytes of data
I/jxcore-log( 7186): 
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,I/jxcore-log( 7186): 2015-12-17T14:16:51.949Z SendDataTCPServer.js: TCP/IP server has received 75656 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:52.036Z SendDataTCPServer.js: TCP/IP server has received 77680 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:52.061Z SendDataTCPServer.js: TCP/IP server has received 81728 bytes of data
I/jxcore-log( 7186): 
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_upio ( 2938): ..proc_btwrite_timeout..
,I/jxcore-log( 7186): 2015-12-17T14:16:52.105Z SendDataTCPServer.js: TCP/IP server has received 81920 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:52.139Z SendDataTCPServer.js: TCP/IP server has received 85968 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:52.167Z SendDataTCPServer.js: TCP/IP server has received 87992 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:52.175Z SendDataTCPServer.js: TCP/IP server has received 90016 bytes of data
I/jxcore-log( 7186): 
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_upio ( 2938): proc btwrite assertion
,E/bt-btm  ( 2938): tBTM_SEC_DEV:0xa1ce571c rs_disc_pending=1
,W/bt-btif ( 2938): bta_dm_check_av:0
,W/bt-btif ( 2938): btif_dm_cback : unhandled event (14)
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already,
,I/jxcore-log( 7186): 2015-12-17T14:16:52.252Z SendDataTCPServer.js: TCP/IP server has received 92040 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:52.289Z SendDataTCPServer.js: TCP/IP server has received 94064 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:52.441Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 7186): 
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,W/bt-btif ( 2938): invalid rfc slot id: 4
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,W/io.jxcore.node.StreamCopyingThread( 7186): Either failed to read from the output stream or write to the input stream (thread ID: 1202, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 7186): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,W/io.jxcore.node.ConnectionHelper( 7186): onDisconnected: Incoming connection, peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4673] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 7186): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1200
,D/io.jxcore.node.IncomingSocketThread( 7186): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 7186): doStop: Thread ID: 1202
,D/io.jxcore.node.IncomingSocketThread( 7186): close: Stopping sending thread...
,I/io.jxcore.node.StreamCopyingThread( 7186): doStop: Thread ID: 1201
,D/io.jxcore.node.IncomingSocketThread( 7186): closeLocalSocketAndStreams: Closing...
,D/io.jxcore.node.IncomingSocketThread( 7186): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 7186): Either failed to read from the output stream or write to the input stream (thread ID: 1201, thread name: Sender): Socket closed
,E/io.jxcore.node.IncomingSocketThread( 7186): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper( 7186): onDisconnected: Incoming connection, peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4673] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 7186): closeLocalSocketAndStreams: Closing the local output stream...
,D/io.jxcore.node.IncomingSocketThread( 7186): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.IncomingSocketThread( 7186): closeBluetoothSocketAndStreams
,D/BluetoothSocket( 7186): close() in, this: android.bluetooth.BluetoothSocket@3ca55488, channel: 6, state: CONNECTED
,D/BluetoothSocket( 7186): close() this: android.bluetooth.BluetoothSocket@3ca55488, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1b569e21, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@36959246mSocket: android.net.LocalSocket@3864cc07 impl:android.net.LocalSocketImpl@d7f3134 fd:FileDescriptor[114]
,D/BluetoothSocket( 7186): Closing mSocket: android.net.LocalSocket@3864cc07 impl:android.net.LocalSocketImpl@d7f3134 fd:FileDescriptor[114]
,D/BluetoothSocket( 7186): close() in, this: android.bluetooth.BluetoothSocket@3ca55488, channel: 6, state: CLOSED
,D/BluetoothSocket( 7186): close() in, this: android.bluetooth.BluetoothSocket@3ca55488, channel: 6, state: CLOSED
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/io.jxcore.node.ConnectionHelper( 7186): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 7186): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 7186): Exiting thread (ID: 1201, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 7186): Exiting thread (ID: 1202, name: Receiver)
,I/jxcore-log( 7186): 2015-12-17T14:16:52.580Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 7186): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7186): onBytesRead: Read 82 bytes successfully (thread ID: 1204)
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7186): Got valid identity from [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT6358]
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,E/bt-btm  ( 2938): tBTM_SEC_DEV:0xa1ce555c rs_disc_pending=0
,W/bt-btif ( 2938): bta_dm_check_av:0
,W/bt-btif ( 2938): btif_dm_cback : unhandled event (14)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7186): onBytesWritten: 82 bytes successfully written (thread ID: 1204)
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7186): removeThreadFromList: Removing thread with ID 1204
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7186): Handshake thread disposed (thread ID: 1204)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7186): onIncomingConnectionConnected: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT6358]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7186): Exiting thread (ID: 1204)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7186): onConnected: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT6358]
,I/io.jxcore.node.ConnectionHelper( 7186): onConnected: Incoming connection to peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT6358]
,D/io.jxcore.node.ConnectionHelper( 7186): hasConnection: No connection with peer with ID F8:CF:C5:D9:E5:61
,D/io.jxcore.node.ConnectionHelper( 7186): notifyPeerAvailability: Peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT6358] is available
,I/io.jxcore.node.ConnectionHelper( 7186): onConnected: Incoming socket thread, for peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT6358], created successfully
,D/io.jxcore.node.ConnectionHelper( 7186): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 7186): Entering thread (ID: 1205)
,I/io.jxcore.node.IncomingSocketThread( 7186): Local host address: localhost/127.0.0.1, port: 34740
,I/jxcore-log( 7186): 2015-12-17T14:16:52.869Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 7186): 
,D/io.jxcore.node.IncomingSocketThread( 7186): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 7186): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 7186): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 7186): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 7186): Exiting thread (ID: 1205)
E/SMD     (  290): DCD ON
,D/io.jxcore.node.StreamCopyingThread( 7186): Entering thread (ID: 1207, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 7186): Entering thread (ID: 1206, name: Sender)
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,W/bt-rfcomm( 2938): rfc_find_lcid_mcb LCID reused LCID:0x43 current:0x0
,W/bt-rfcomm( 2938): RFCOMM_DisconnectInd LCID:0x43
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,I/jxcore-log( 7186): 2015-12-17T14:16:53.851Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 7186): 
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 290, CUR = 450
,I/jxcore-log( 7186): 2015-12-17T14:16:54.040Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:54.046Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 7186): 
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/jxcore-log( 7186): 2015-12-17T14:16:54.159Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 7186): 
,D/bt_upio ( 2938): ..proc_btwrite_timeout..
,I/jxcore-log( 7186): 2015-12-17T14:16:54.198Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:54.248Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 7186): 
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_upio ( 2938): proc btwrite assertion
,I/jxcore-log( 7186): 2015-12-17T14:16:54.271Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:54.404Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:54.438Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:54.458Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:54.508Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 7186): 
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,I/jxcore-log( 7186): 2015-12-17T14:16:54.629Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:54.669Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:54.702Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:54.706Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 7186): 
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,I/jxcore-log( 7186): 2015-12-17T14:16:54.755Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 7186): 
,I/wpa_supplicant( 1268): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService(  898): InactiveState{ what=147477 }
,D/WifiP2pService(  898): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  898): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  898): InactiveState{ what=139283 }
,D/WifiP2pService(  898): P2pEnabledState{ what=139283 }
D/WifiP2pService(  898): DefaultState{ what=139283 }
,D/WifiDisplayController(  898): Received list of peers.
D/WifiDisplayController(  898):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  898):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  898): InactiveState{ what=139283 }
D/WifiP2pService(  898): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  898): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7186): onP2pDeviceListChanged: 2 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7186): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7186): onP2pDeviceListChanged: Peer 2: Android_8ae2 52:55:27:f0:fd:0b
,I/jxcore-log( 7186): 2015-12-17T14:16:54.820Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:54.869Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:54.872Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:54.919Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:54.966Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 7186): 
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,I/jxcore-log( 7186): 2015-12-17T14:16:55.001Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 7186): 
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/jxcore-log( 7186): 2015-12-17T14:16:55.075Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:55.133Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:55.143Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:55.348Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:55.397Z SendDataTCPServer.js: TCP/IP server has received 49152 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:55.435Z SendDataTCPServer.js: TCP/IP server has received 51132 bytes of data
I/jxcore-log( 7186): 
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,I/jxcore-log( 7186): 2015-12-17T14:16:55.448Z SendDataTCPServer.js: TCP/IP server has received 53112 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:55.543Z SendDataTCPServer.js: TCP/IP server has received 55092 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:55.578Z SendDataTCPServer.js: TCP/IP server has received 57072 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:55.587Z SendDataTCPServer.js: TCP/IP server has received 59052 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:55.637Z SendDataTCPServer.js: TCP/IP server has received 65536 bytes of data
I/jxcore-log( 7186): 
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,I/jxcore-log( 7186): 2015-12-17T14:16:55.679Z SendDataTCPServer.js: TCP/IP server has received 67516 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:55.684Z SendDataTCPServer.js: TCP/IP server has received 69496 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:55.736Z SendDataTCPServer.js: TCP/IP server has received 75436 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:55.741Z SendDataTCPServer.js: TCP/IP server has received 77416 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:55.783Z SendDataTCPServer.js: TCP/IP server has received 79396 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:55.793Z SendDataTCPServer.js: TCP/IP server has received 81920 bytes of data
I/jxcore-log( 7186): 
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,I/jxcore-log( 7186): 2015-12-17T14:16:55.830Z SendDataTCPServer.js: TCP/IP server has received 85880 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:55.874Z SendDataTCPServer.js: TCP/IP server has received 87860 bytes of data
I/jxcore-log( 7186): 
,E/SMD     (  290): DCD ON
,I/jxcore-log( 7186): 2015-12-17T14:16:55.900Z SendDataTCPServer.js: TCP/IP server has received 89840 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:55.929Z SendDataTCPServer.js: TCP/IP server has received 91820 bytes of data
I/jxcore-log( 7186): 
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,I/jxcore-log( 7186): 2015-12-17T14:16:55.964Z SendDataTCPServer.js: TCP/IP server has received 93800 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:56.002Z SendDataTCPServer.js: TCP/IP server has received 97760 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:56.013Z SendDataTCPServer.js: TCP/IP server has received 99740 bytes of data
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:16:56.036Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 7186): 
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,W/bt-btif ( 2938): invalid rfc slot id: 6
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,W/io.jxcore.node.StreamCopyingThread( 7186): Either failed to read from the output stream or write to the input stream (thread ID: 1207, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 7186): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,W/io.jxcore.node.ConnectionHelper( 7186): onDisconnected: Incoming connection, peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT6358] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 7186): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1205
,D/io.jxcore.node.IncomingSocketThread( 7186): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 7186): doStop: Thread ID: 1207
D/io.jxcore.node.IncomingSocketThread( 7186): close: Stopping sending thread...
,I/io.jxcore.node.StreamCopyingThread( 7186): doStop: Thread ID: 1206
D/io.jxcore.node.IncomingSocketThread( 7186): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 7186): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 7186): Either failed to read from the output stream or write to the input stream (thread ID: 1206, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 7186): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 7186): onDisconnected: Incoming connection, peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT6358] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 7186): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 7186): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 7186): closeBluetoothSocketAndStreams
,D/BluetoothSocket( 7186): close() in, this: android.bluetooth.BluetoothSocket@25dfb5d, channel: 6, state: CONNECTED
D/BluetoothSocket( 7186): close() this: android.bluetooth.BluetoothSocket@25dfb5d, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2b888cd2, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@207821a3mSocket: android.net.LocalSocket@14782ca0 impl:android.net.LocalSocketImpl@3883f059 fd:FileDescriptor[116]
D/BluetoothSocket( 7186): Closing mSocket: android.net.LocalSocket@14782ca0 impl:android.net.LocalSocketImpl@3883f059 fd:FileDescriptor[116]
,D/BluetoothSocket( 7186): close() in, this: android.bluetooth.BluetoothSocket@25dfb5d, channel: 6, state: CLOSED
,D/BluetoothSocket( 7186): close() in, this: android.bluetooth.BluetoothSocket@25dfb5d, channel: 6, state: CLOSED
D/io.jxcore.node.ConnectionHelper( 7186): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.ConnectionHelper( 7186): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7186): Exiting thread (ID: 1206, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 7186): Exiting thread (ID: 1207, name: Receiver)
,I/jxcore-log( 7186): 2015-12-17T14:16:56.159Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 7186): 
,D/bt_upio ( 2938): ..proc_btwrite_timeout..
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_upio ( 2938): proc btwrite assertion
,W/bt-rfcomm( 2938): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
,W/bt-rfcomm( 2938): RFCOMM_DisconnectInd LCID:0x44
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,E/bt-btm  ( 2938): tBTM_SEC_DEV:0xa1ce555c rs_disc_pending=1
,E/bt-btm  ( 2938): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 2938): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 2938): bta_dm_check_av:0
,W/bt-btif ( 2938): btif_dm_cback : unhandled event (14)
,D/KeyguardViewMediator( 1183): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothManager( 7269): [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothManager( 7269): [SVoiceBT, LatencyCheck] BT onHeadsetStateChanged(): isConnected= false
,E/BluetoothEventManager( 1325): ACTION_ACL_DISCONNECTED
,D/BluetoothAdapterService( 2938): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a28d88b
,D/BtConfig.SecureMode( 2938): isSecureModeOn:false
,D/SecContentProvider(  898): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,D/KeyguardViewMediator( 1183): isGear1: device is not B1!
,I/BluetoothPbapService( 2938): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,D/BluetoothManager( 7269): ====[SVoiceBT, LatencyCheck] closeBtProxy===
,D/BluetoothManager( 7269): ==[SVoiceBT, LatencyCheck] BT stopSCO()==
,D/BluetoothManager( 7269): [SVoiceBT, LatencyCheck] BT Ignoring stopSCO() bluetooth Audio off
,E/BluetoothHeadset( 7269): BTStateChangeCB is unregisted
,I/BTConnectionReceiver( 1571): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1571): Bluetooth Device Name: Thali Test (Galaxy A5)
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 1
,D/bt_upio ( 2938): ..proc_btwrite_timeout..
,D/bt_vendor( 2938): op for 7
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryService(  898): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): proc btwrite assertion
,E/bt-btm  ( 2938): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 2938): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 1183): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/io.jxcore.node.ConnectionHelper( 7186): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:75:41
,E/io.jxcore.node.ConnectionHelper( 7186): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 7186): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 7186): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:75:41), either no such connection or failed to close the connection
,I/jxcore-log( 7186): 2015-12-17T14:17:00.171Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): 2015-12-17T14:17:00.171Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 7186): 
I/jxcore-log( 7186): 2015-12-17T14:17:00.172Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 7186): 
,D/BluetoothAdapterService( 2938): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a28d88b
,D/BtConfig.SecureMode( 2938): isSecureModeOn:false
,D/SecContentProvider(  898): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,I/BluetoothPbapService( 2938): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,D/KeyguardViewMediator( 1183): isGear1: device is not B1!
,I/jxcore-log( 7186): 2015-12-17T14:17:00.196Z SendDataConnector.js: do connect now
I/jxcore-log( 7186): 
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.ACL_DISCONNECTED
I/io.jxcore.node.ConnectionHelper( 7186): connect: Trying to connect to peer with ID 08:EC:A9:50:75:41
,D/io.jxcore.node.ConnectionHelper( 7186): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
W/io.jxcore.node.ConnectionHelper( 7186): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7186): connect: [08:EC:A9:50:75:41 08:EC:A9:50:75:41]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7186): connect: Trying to start connecting to null in address 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7186): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7186): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7186): onConnecting: null 08:EC:A9:50:75:41
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7186): connect: Started connecting to null in address 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 7186): connect: Connection process successfully started (peer ID: 08:EC:A9:50:75:41)
,E/Watchdog(  898): !@Sync 15
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7186): Trying to connect to peer with address 08:EC:A9:50:75:41 (thread ID: 1208)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 7186): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 7186): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2938): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/IOP_DB_BT( 2938): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:75:41
D/IOP_DB_BT( 2938): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 2938): db_query_add_key: key KEY_LMP_VER, value 7:2003
D/IOP_DB_BT( 2938): db_query_add_key: key KEY_DIR_ALL, value 1
D/IOP_DB_BT( 2938): db_query_execute: result 1
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/BluetoothSocket( 7186): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[116]}
,E/BluetoothEventManager( 1325): ACTION_ACL_DISCONNECTED
D/BluetoothManager( 7269): [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.device.action.ACL_DISCONNECTED
D/BluetoothManager( 7269): [SVoiceBT, LatencyCheck] BT onHeadsetStateChanged(): isConnected= false
,W/System.err( 7269): java.lang.NullPointerException: Attempt to invoke virtual method 'java.util.List android.bluetooth.BluetoothHeadset.getConnectedDevices()' on a null object reference
,W/System.err( 7269): 	at com.vlingo.core.internal.bluetooth.BluetoothManager.getBluetoothHeadsetConnctedDevices(BluetoothManager.java:941)
W/System.err( 7269): 	at com.vlingo.core.internal.bluetooth.BluetoothManager.onHeadsetStateChanged(BluetoothManager.java:462)
W/System.err( 7269): 	at com.vlingo.core.internal.bluetooth.BluetoothManager$BTStateBroadcastReceiver.onReceive(BluetoothManager.java:1245)
W/System.err( 7269): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:923)
W/System.err( 7269): 	at android.os.Handler.handleCallback(Handler.java:739)
,W/System.err( 7269): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7269): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7269): 	at android.app.ActivityThread.main(ActivityThread.java:5940)
W/System.err( 7269): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7269): 	at java.lang.reflect.Method.invoke(Method.java:372)
,W/System.err( 7269): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1389)
W/System.err( 7269): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1184)
D/BluetoothManager( 7269): ====[SVoiceBT, LatencyCheck] closeBtProxy===
,I/BTConnectionReceiver( 1571): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1571): Bluetooth Device Name: Nexus 6
,I/wpa_supplicant( 1268): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService(  898): InactiveState{ what=147477 }
,D/WifiP2pService(  898): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  898): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  898): InactiveState{ what=139283 }
,D/WifiP2pService(  898): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  898): DefaultState{ what=139283 }
,D/WifiDisplayController(  898): Received list of peers.
,D/WifiDisplayController(  898):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  898):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  898):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  898): InactiveState{ what=139283 }
,D/WifiP2pService(  898): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  898): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7186): onP2pDeviceListChanged: 3 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7186): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7186): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7186): onP2pDeviceListChanged: Peer 3: Android_8ae2 52:55:27:f0:fd:0b
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7186): restart: Restarting...
,D/WifiP2pService(  898): InactiveState{ what=139307 }
,D/WifiP2pService(  898): P2pEnabledState{ what=139307 }
,D/WifiP2pService(  898): P2pEnabledState clear service request
,F/libc    ( 1268): Fatal signal 11 (SIGSEGV), code 1, fault addr 0xc in tid 1268 (wpa_supplicant)
,D/bt_vendor( 2938): op for 7
,D/WifiP2pService(  898): InactiveState{ what=139301 }
,D/WifiP2pService(  898): P2pEnabledState{ what=139301 }
D/WifiP2pService(  898): P2pEnabledState add service request
,D/WifiP2pManager( 7186): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7186): Service request added successfully
,W/NativeCrashListener(  898): Couldn't find ProcessRecord for pid 1268
,I/DEBUG   (  284): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
,E/DEBUG   (  284): AM write failure (32 / Broken pipe)
I/DEBUG   (  284): Build fingerprint: 'samsung/hltexx/hlte:5.0/LRX21V/N9005XXUGBOB6:user/release-keys'
I/DEBUG   (  284): Revision: '8'
I/DEBUG   (  284): ABI: 'arm'
,I/DEBUG   (  284): pid: 1268, tid: 1268, name: wpa_supplicant  >>> /system/bin/wpa_supplicant <<<
,I/DEBUG   (  284): signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0xc
,I/DEBUG   (  284):     r0 cf2407e1  r1 00000000  r2 00000009  r3 00000000
,I/DEBUG   (  284):     r4 b66c5800  r5 b66b1780  r6 b6689042  r7 00000000
I/DEBUG   (  284):     r8 00000985  r9 b6689048  sl be96ef00  fp b665b428
I/DEBUG   (  284):     ip b6fd39b8  sp be96ecf0  lr b6efac41  pc b6efac5e  cpsr 600f0030
,I/DEBUG   (  284): 
I/DEBUG   (  284): backtrace:
,I/DEBUG   (  284):     #00 pc 00031c5e  /system/bin/wpa_supplicant
I/DEBUG   (  284):     #01 pc 00029e8b  /system/bin/wpa_supplicant
I/DEBUG   (  284):     #02 pc 000901db  /system/bin/wpa_supplicant
I/DEBUG   (  284):     #03 pc 00098d2f  /system/bin/wpa_supplicant
,I/DEBUG   (  284):     #04 pc 000a6a57  /system/bin/wpa_supplicant
I/DEBUG   (  284):     #05 pc 000a83af  /system/bin/wpa_supplicant
I/DEBUG   (  284):     #06 pc 000a930d  /system/bin/wpa_supplicant
,I/DEBUG   (  284):     #07 pc 00005bf5  /system/lib/libnl.so
I/DEBUG   (  284):     #08 pc 000062cb  /system/lib/libnl.so (nl_recvmsgs+622)
I/DEBUG   (  284):     #09 pc 0009e2e5  /system/bin/wpa_supplicant
,I/DEBUG   (  284):     #10 pc 000141e1  /system/bin/wpa_supplicant
I/DEBUG   (  284):     #11 pc 00014849  /system/bin/wpa_supplicant
,E/SMD     (  290): DCD ON
I/DEBUG   (  284):     #12 pc 00092a3b  /system/bin/wpa_supplicant
I/DEBUG   (  284):     #13 pc 0000cd7b  /system/bin/wpa_supplicant
I/DEBUG   (  284):     #14 pc 0000fb79  /system/lib/libc.so (__libc_init+44)
,I/DEBUG   (  284):     #15 pc 0000ce60  /system/bin/wpa_supplicant
,I/DEBUG   (  284): 
I/DEBUG   (  284): Tombstone written to: /data/tombstones/tombstone_08
,E/SharedPreferencesImpl(  898): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,I/BootReceiver(  898): Copying /data/tombstones/tombstone_08 to DropBox (SYSTEM_TOMBSTONE)
E/        (  284): !@dumpstate -k -t -z -d -o /data/log/dumpstate_app_native -m 1268
,I/dumpstate( 7856): begin
,D/CrashAnrDetector(  898): Build: samsung/hltexx/hlte:5.0/LRX21V/N9005XXUGBOB6:user/release-keys
D/CrashAnrDetector(  898): Hardware: MSM8974
D/CrashAnrDetector(  898): Revision: 8
D/CrashAnrDetector(  898): Bootloader: N9005XXUGBOB6
D/CrashAnrDetector(  898): Radio: unknown
D/CrashAnrDetector(  898): Kernel: Linux version 3.4.0-3643614 (dpi@SWDD5914) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Wed Feb 25 21:52:47 KST 2015
D/CrashAnrDetector(  898): 
D/CrashAnrDetector(  898): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector(  898): Build fingerprint: 'samsung/hltexx/hlte:5.0/LRX21V/N9005XXUGBOB6:user/release-keys'
D/CrashAnrDetector(  898): Revision: '8'
D/CrashAnrDetector(  898): ABI: 'arm'
D/CrashAnrDetector(  898): pid: 1268, tid: 1268, name: wpa_supplicant  >>> /system/bin/wpa_supplicant <<<
D/CrashAnrDetector(  898): signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0xc
D/CrashAnrDetector(  898):     r0 cf2407e1  r1 00000000  r2 00000009  r3 00000000
D/CrashAnrDetector(  898):     r4 b66c5800  r5 b66b1780  r6 b6689042  r7 00000000
D/CrashAnrDetector(  898):     r8 00000985  r9 b6689048  sl be96ef00  fp b665b428
D/CrashAnrDetector(  898):     ip b6fd39b8  sp be96ecf0  lr b6efac41  pc b6efac5e  cpsr 600f0030
D/CrashAnrDetector(  898):     d0  0000000000000000  d1  0000000000000000
D/CrashAnrDetector(  898):     d2  2079726575512079  d3  626c6c6163205854
D/CrashAnrDetector(  898):     d4  00650006000000e0  d5  00050004000000f0
D/CrashAnrDetector(  898):     d6  0007000400060004  d7  0000000500080084
D/CrashAnrDetector(  898):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector(  898):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector(  898):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector(  898):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector(  898):     d16 363a37663a39333a  d17 2064353a39633a66
D/CrashAnrDetector(  898):     d18 6b6361626c6c6163  d19 3d65746174732820
D/CrashAnrDetector(  898):     d20 323d716572662035  d21 3d74736420373334
D/CrashAnrDetector(  898):     d22 37663a39333a3261  d23 353a39633a66363a
D/CrashAnrDetector(  898):     d24 0000000000000000  d25 0000000000000000
D/CrashAnrDetector(  898):     d26 0000000000000000  d27 0000000000000000
D/CrashAnrDetector(  898):     d28 0000000000000000  d29 0000000000000000
D/CrashAnrDetector(  898):     d30 0000000000000000  d31 0000000000000000
D/CrashAnrDetector(  898):     scr 60000000
D/CrashAnrDetector(  898): 
D/CrashAnrDetector(  898): backtrace:
D/CrashAnrDetector(  898):     #00 pc 00031c5e  /system/bin/wpa_supplicant
D/CrashAnrDetector(  898):     #01 pc 00029e8b  /system/bin/wpa_supplicant
D/CrashAnrDetector(  898):     #02 pc 000901db  /system/bin/wpa_supplicant
D/CrashAnrDetector(  898):     #03 pc 00098d2f  /system/bin/wpa_supplicant
D/CrashAnrDetector(  898):     #04 pc 000a6a57  /system/bin/wpa_supplicant
D/CrashAnrDetector(  898):     #05 pc 000a83af  /system/bin/wpa_supplicant
D/CrashAnrDetector(  898):     #06 pc 000a930d  /system/bin/wpa_supplicant
D/CrashAnrDetector(  898):     #07 pc 00005bf5  /system/lib/libnl.so
D/CrashAnrDetector(  898):     #08 pc 000062cb  /system/lib/libnl.so (nl_recvmsgs+622)
D/CrashAnrDetector(  898):     #09 pc 0009e2e5  /system/bin/wpa_supplicant
D/CrashAnrDetector(  898):     #10 pc 000141e1  /system/bin/wpa_supplicant
D/CrashAnrDetector(  898):     #11 pc 00014849  /system/bin/wpa_supplicant
D/CrashAnrDetector(  898):     #12 pc 00092a3b  /system/bin/wpa_supplicant
D/CrashAnrDetector(  898):     #13 pc 0000cd7b  /system/bin/wpa_supplicant
D/CrashAnrDetector(  898):     #14 pc 0000fb79  /system/lib/libc.so (__libc_init+44)
D/CrashAnrDetector(  898):     #15 pc 0000ce60  /system/bin/wpa_supplicant
D/CrashAnrDetector(  898): 
D/CrashAnrDetector(  898): stack:
D/CrashAnrDetector(  898):          be96ec70  00000000  
D/CrashAnrDetector(  898):          be96ec74  00000000  
D/CrashAnrDetector(  898):          be96ec78  00000000  
D/CrashAnrDetector(  898):    ,      be96ec7c  ffffffff  
D/CrashAnrDetector(  898):          be96ec80  00004000  
D/CrashAnrDetector(  898):          be96ec84  b665a155  [anon:libc_malloc]
D/CrashAnrDetector(  898):          be96ec88  00000000  
D/CrashAnrDetector(  898):          be96ec8c  00000000  
D/CrashAnrDetector(  898):          be96ec90  ffff0208  [vectors]
D/CrashAnrDetector(  898):          be96ec94  cf2407e1  
D/CrashAnrDetector(  898):          be96ec98  b6eaffec  
D/CrashAnrDetector(  898):          be96ec9c  b6688c00  [anon:libc_malloc]
D/CrashAnrDetector(  898):          be96eca0  b661b2a0  [anon:libc_malloc]
D/CrashAnrDetector(  898):          be96eca4  00000035  
D/CrashAnrDetector(  898):          be96eca8  b665a120  [anon:libc_malloc]
D/CrashAnrDetector(  898):          be96ecac  00000002  
D/CrashAnrDetector(  898):          be96ecb0  00000036  
D/CrashAnrDetector(  898):          be96ecb4  b6ea7e04  
D/CrashAnrDetector(  898):          be96ecb8  00000000  
D/CrashAnrDetector(  898):          be96ecbc  b6f54ab1  /system/bin/wpa_supplicant
D/CrashAnrDetector(  898):          be96ecc0  00000002  
D/CrashAnrDetector(  898):          be96ecc4  b665a120  [anon:libc_malloc]
D/CrashAnrDetector(  898):          be96ecc8  00f54a4d  
D/CrashAnrDetector(  898):          be96eccc  cf2407e1  
D/CrashAnrDetector(  898):          be96ecd0  b6688c00  [anon:libc_malloc]
D/CrashAnrDetector(  898):          be96ecd4  b66c5800  [anon:libc_malloc]
D/CrashAnrDetector(  898):          be96ecd8  00000001  
D/CrashAnrDetector(  898):          be96ecdc  b6689042  [anon:libc_malloc]
D/CrashAnrDetector(  898):          be96ece0  b6efac41  /system/bin/wpa_supplicant
D/CrashAnrDetector(  898):          be96ece4  b6f8f293  /system/bin/wpa_supplicant
D/CrashAnrDetector(  898):          be96ece8  00000001  
D/CrashAnrDetector(  898):          be96ecec  00000005  
D/CrashAnrDetector(  898):     #00  be96ecf0  000000a2  
D/CrashAnrDetector(  898):          be96ecf4  00000039  
D/CrashAnrDetector(  898):          be96ecf8  000000f7  
D/CrashAnrDetector(  898):          be96ecfc  0000006f  
D/CrashAnrDetector(  898):          be96ed00  000000c9  
D/CrashAnrDetector(  898):          be96ed04  0000005d  
D/CrashAnrDetector(  898):          be96ed08  000000ea  
D/CrashAnrDetector(  898):          be96ed0c  00000050  
D/CrashAnrDetector(  898):          be96ed10  0000008b  
D/CrashAnrDetector(  898):          be96ed14  000000de  
D/CrashAnrDetector(  898):          be96ed18  00000028  
D/CrashAnrDetector(  898):          be96ed1c  000000a3  
D/CrashAnrDetector(  898):          be96ed20  000000a2  
D/CrashAnrDetector(  898):          be96ed24  00000039  
D/CrashAnrDetector(  898):          be96ed28  000000f7  
D/CrashAnrDetector(  898):          be96ed2c  0000006f  
D/CrashAnrDetector(  898):       
D/CrashAnrDetector(  898): processName:/system/bin/wpa_supplicant
D/CrashAnrDetector(  898): broadcastEvent : null SYSTEM_TOMBSTONE
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1700 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,D/bt_upio ( 2938): ..proc_btwrite_timeout..
,D/WifiP2pService(  898): InactiveState{ what=139310 },
,D/WifiP2pService(  898): P2pEnabledState{ what=139310 },
,D/WifiP2pService(  898): P2pEnabledState discover services
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/SSRM:n  (  898): SIOP:: AP = 300, PST = 291, CUR = 450
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/TimaService(  898): TIMA: timaDumpLog
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 2
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): stay LED for fully charged
D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,E/SMD     (  290): DCD ON
,I/PowerManagerService(  898): [PWL] Off : 390s ago
,I/PowerManagerService(  898): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  898): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  898): [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=2938, ws=null) (elapsedTime=27900)
,D/WifiHW  (  898): 'P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001020a436f72646f7661703270c00c000c01' command timed out.
,W/WifiHW  (  898): connection closed - 2
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7186): Failed to start the service discovery, got error code: 3
,E/WifiStateMachine(  898): Connection lost, restart supplicant
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 300, PST = 292, CUR = 450
,I/dumpstate( 7856): waiting for zip started,
,I/dumpstate( 7856): waiting for zip end
,I/dumpstate( 7856): done
,I/        ( 8009): debuggerd: Feb 25 2015 21:59:08
,E/WifiStateMachine(  898): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,D/WifiNative-HAL(  898): callSECApiBoolean - ID [21]
,D/SmartBondingService(  898): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1183): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1183): onWifiSignalChanged enabled=false enabledDesc:null
,D/STATUSBAR-WifiQuickSettingButton( 1183): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-WifiQuickSettingButton( 1183): Wifi onReceive(1)
D/STATUSBAR-QSTileView( 1183): onStateChanged: Wi-Fi
,D/HotspotTile( 1183): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/SmartBondingService(  898): getNetworkEnabled : wifi : false mobile : true
,D/HotspotTile( 1183): onReceive : 1, 0
,E/WifiConfigStore(  898): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  898): failed to set BSSID: any
,E/native  (  898): do suspend true
,D/WifiP2pService(  898): InactiveState{ what=143375 }
D/WifiP2pService(  898): P2pEnabledState{ what=143375 }
,D/WifiCredService( 1325): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/CommandListener(  282): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 1183): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1183): onWifiSignalChanged enabled=false enabledDesc:null
,I/jxcore-log( 7186): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 7186): 
,I/jxcore-log( 7186): The Coordinator has disconnected!
I/jxcore-log( 7186): 
,W/Settings( 1949): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/SignOutReceiver( 6753): WIFI_STATE_CHANGED_ACTION
,V/NativeCrypto( 1949): Read error: ssl=0x9ba8be00: I/O error during system call, Connection timed out
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 6968): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6968): KnoxConfiguration : Current State Mapping Found 
V/NativeCrypto( 1949): SSL shutdown failed: ssl=0x9ba8be00: I/O error during system call, Broken pipe
D/SecurityLogAgent( 6968): StateMachine : Current State = 1
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6968): StateMachine : Changed Current State = 1
,E/ConnectivityService(  898): updateNetworkInfo()
D/ConnectivityService(  898): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  898): updateNetworkInfo()
D/ConnectivityService(  898): ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
D/NetUtils(  898): android_net_utils_resetConnections in env=0x9d7b7390 clazz=0x9bde098c iface=wlan0 mask=0x3
D/ConnectivityService(  898): NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 3
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7186): Connection timeout
,E/WifiConfigStore(  898): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/WifiConfigStore(  898): failed to set BSSID: any
E/WifiStateMachine(  898): WifiStateMachine: Leaving Connected state
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7186): onConnectionTimeout: [08:EC:A9:50:75:41 08:EC:A9:50:75:41]
,I/jxcore-log( 7186): 2015-12-17T14:17:15.204Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [08:EC:A9:50:75:41 08:EC:A9:50:75:41] timed out
I/jxcore-log( 7186): 
I/jxcore-log( 7186): 2015-12-17T14:17:15.204Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [08:EC:A9:50:75:41 08:EC:A9:50:75:41] timed out
I/jxcore-log( 7186): 
D/WifiNetworkAgent(  898): NetworkAgent: NetworkAgent channel lost
I/jxcore-log( 7186): 2015-12-17T14:17:15.204Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 7186): 
D/SecContentProvider2(  898): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  898): mCursor = null
,D/WifiP2pService(  898): InactiveState{ what=131204 }
D/WifiP2pService(  898): P2pEnabledState{ what=131204 }
,I/WifiTrafficPoller(  898): evaluateTrafficStatsPolling
,D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  898): reportBadNetwork(NetworkAgentInfo [WIFI () - 503]) by 10015
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  898): ValidatedState{ when=0 what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  898): DefaultState{ when=-1ms what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  898): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  898): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  898): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WifiScanningService(  898): SCAN_AVAILABLE : 1
D/RttService(  898): SCAN_AVAILABLE : 1
D/StatusBar.NetworkController( 1183): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1183): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/WifiScanningService(  898): DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  898): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,D/RttService(  898): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/StatusBar.NetworkController( 1183): applyOpen
,I/System.out(  898): (HTTPLog)-Static: isSBSettingEnabled false
,D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  898): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  898): Validated
,D/WifiP2pService(  898): sending p2p connection changed broadcast: FAILED
,D/WifiP2pService(  898): discovery change broadcast false
,D/WifiDisplayController(  898): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiDisplayController(  898): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WifiDisplayAdapter(  898): onP2pDisconnected
D/IpRemoteDisplayController(  898): disconnectWfdBridgeServer
D/IpRemoteDisplayController(  898): WfdBridgeServer is already null
,D/WifiP2pService(  898): sending p2p connection changed broadcast: DISCONNECTED
E/WifiStateMachine(  898): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/WifiDisplayController(  898): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,D/WifiDisplayController(  898): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  898): disconnect
D/WifiDisplayController(  898): updateConnection
D/WifiDisplayController(  898): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7186): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7186): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7186): setState: RESTARTING
,D/WifiDisplayAdapter(  898): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7186): onWifiStateChanged: State changed to 1
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7186): onWifiStateChanged: Wi-Fi disabled, pausing Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7186): stop: Stopping services
,D/AllShareCastTile( 1183): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
D/WifiDisplayAdapter(  898): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/AllShareCastTile( 1183): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7186): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7186): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7186): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7186): stopWifiPeerDiscovery: Stopped
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7186): setState: WAITING_FOR_SERVICES_TO_BE_ENABLED
I/io.jxcore.node.ConnectionHelper( 7186): onDiscoveryManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
,D/WifiP2pService(  898): P2pDisablingState
,D/WifiDisplayController(  898): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter(  898): onP2pDisconnected
D/WifiP2pService(  898): P2pDisablingState{ what=147458 }
D/IpRemoteDisplayController(  898): disconnectWfdBridgeServer
,D/WifiP2pService(  898): p2p socket connection lost
D/IpRemoteDisplayController(  898): WfdBridgeServer is already null
D/WifiP2pService(  898): P2pDisabledState
D/WifiP2pService(  898): P2pDisabledState{ what=139283 }
D/WifiP2pService(  898): DefaultState{ what=139283 }
,D/WifiDisplayController(  898): Received list of peers.
D/WifiP2pService(  898): P2pDisabledState{ what=139283 }
D/WifiP2pService(  898): DefaultState{ what=139283 }
I/Hs20UtilService( 1325): Starting #12
,D/WifiP2pService(  898): P2pDisabledState{ what=139268 }
D/WifiP2pService(  898): DefaultState{ what=139268 }
I/Hs20UtilService( 1325): Message received 5007
D/WifiP2pService(  898): P2pDisabledState{ what=139298 }
D/WifiP2pService(  898): DefaultState{ what=139298 }
,D/NearbySettings( 1325): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1325): DMSUtil.isNetworkConnected - flag-null, state-null
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7186): onP2pDeviceListChanged: 0 device(s) discovered
,D/AndroidRuntime( 7186): Shutting down VM
D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7186): Uncaught exception: Attempt to invoke virtual method 'boolean org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser.isStarted()' on a null object reference
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7186): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser.isStarted()' on a null object reference
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7186): 	at org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer.onP2pDeviceListChanged(WifiPeerDiscoverer.java:164)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7186): 	at org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer$MyPeerListListener.onPeersAvailable(WifiP2pDeviceDiscoverer.java:285)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7186): 	at android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler.handleMessage(WifiP2pManager.java:1009)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7186): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7186): 	at android.os.Looper.loop(Looper.java:145)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7186): 	at android.app.ActivityThread.main(ActivityThread.java:5940)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7186): 	at java.lang.reflect.Method.invoke(Native Method)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7186): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7186): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1389)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7186): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1184)
I/NearbySettings( 1325): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1325): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1325): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1325): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1325): MountReceiver.mPrefHandler - 7002
,D/WifiP2pService(  898): P2pDisabledState{ what=139268 }
,D/WifiP2pService(  898): DefaultState{ what=139268 }
,D/WifiP2pService(  898): P2pDisabledState{ what=139307 }
,D/WifiP2pService(  898): DefaultState{ what=139307 }
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6753): NETWORK_STATE_CHANGED_ACTION
,I/GoogleURLConnFactory( 1949): Using platform SSLCertificateSocketFactory
,D/NearbySettings( 1325): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 1325): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1325): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1325): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1325): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1325): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1325): MountReceiver.mPrefHandler - 7002
,E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8040): MountEmulatedStorage()
E/Zygote  ( 8040): v2
I/libpersona( 8040): KNOX_SDCARD checking this for 10088
I/libpersona( 8040): KNOX_SDCARD not a persona
,D/EntConnectivity(  898): Not allowed due to - mEnabled false
D/ConnectivityService(  898): notifyType LOST for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  898): calling update connectivity
D/ConnectivityService(  898):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  898):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  898): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  898):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  898): sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1183): CM callback handler got msg 524292
V/Nat464Xlat(  898): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  898): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  898): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  898): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  898): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  898): Disconnected - quitting
D/CSLegacyTypeTracker(  898): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  898): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=false
D/ConnectivityService(  898): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityManager.CallbackHandler( 2297): CM callback handler got msg 524292
,D/TelephonyNetworkFactory( 1421): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/ActivityManager(  898): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=8040 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/SmartBondingService(  898): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  898): MasterInitialState.processMessage what=3
V/NetworkStats(  898): updateIfacesLocked()
D/NtpTrustedTime(  898): currentTimeMillis() cache hit
V/NetworkStats(  898): performPollLocked(flags=0x1)
,D/ConnectivityService(  898): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
D/NetworkStatsFactory(  898): UpdateStatsForKnox
D/ConnectivityService(  898): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  898): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
E/ConnectivityService(  898): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
E/ConnectivityService(  898): updateNetworkInfo()
D/ConnectivityService(  898): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  898): updateNetworkInfo()
D/ConnectivityService(  898): ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,D/SmartBondingService(  898): getSBEnabled() enabled =false
D/SmartBondingService(  898): getSBEnabled() enabled =false
D/SmartBondingService(  898): getSBEnabled() enabled =false
,V/NetworkStats(  898): performPollLocked() took 4ms
D/NtpTrustedTime(  898): currentTimeMillis() cache hit
,I/SELinux ( 8040): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/SmartBondingService(  898): getNetworkEnabled : wifi : false mobile : true
D/StatusBar.NetworkController( 1183): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1183): updateDataNetType()
D/StatusBar.NetworkController( 1183): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1183): updateLTEICONDataNetType:0
,I/SELinux ( 8040): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 8040): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/NtpTrustedTime(  898): currentTimeMillis() cache hit
,D/NtpTrustedTime(  898): currentTimeMillis() cache hit
V/NetworkStats(  898): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  898): currentTimeMillis() cache hit
D/NtpTrustedTime(  898): currentTimeMillis() cache hit
D/NtpTrustedTime(  898): currentTimeMillis() cache hit
D/NtpTrustedTime(  898): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1183): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1183): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1183): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1183): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1183): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
,I/PhenotypeConfigurator( 1949): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,D/TimaKeyStoreProvider( 8040): TimaSignature is unavailable
,D/ActivityThread( 8040): Added TimaKeyStore provider
,D/FileWriteThread_Telephony( 1421): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1421): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1421): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1421): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1421): FileWriteThread : threadType = 3
,D/ResourcesManager( 8040): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
D/FileWriteThread_Telephony( 1421): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1421): FileWriteThread : threadType = 3
,E/WifiStateMachine(  898): skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,D/FileWriteThread_Telephony( 1421): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1421): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1421): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1421): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1421): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1421): FileWriteThread : threadType = 3
D/FileShare-Server( 8040): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/FileWriteThread_Telephony( 1421): FileWriteThread : threadType = 3
,E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8069): MountEmulatedStorage()
E/Zygote  ( 8069): v2
I/libpersona( 8069): KNOX_SDCARD checking this for 10192
I/libpersona( 8069): KNOX_SDCARD not a persona
,I/ActivityManager(  898): Start proc com.samsung.shareshot for broadcast com.samsung.shareshot/.WifiDirectBroadcastReceiver: pid=8069 uid=10192 gids={50192, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 8069): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 8069): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 8069): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/System.out( 1949): (HTTPLog)-Static: isSBSettingEnabled false
,V/NativeCrypto( 1949): SSL shutdown failed: ssl=0xad356800: I/O error during system call, Connection timed out
,W/PhenotypeConfigurator( 1949): IOException while sending for: 
D/TimaKeyStoreProvider( 8069): TimaSignature is unavailable
,D/ActivityThread( 8069): Added TimaKeyStore provider
,D/ResourcesManager( 8069): creating new AssetManager and set to /system/app/ShareShotService/ShareShotService.apk
,D/WifiDirectBR( 8069): WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/WifiDirectBR( 8069): WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
,W/ContextImpl( 8069): Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,D/WifiDirectBR( 8069): stopServiceTest : false
,D/WifiDirectBR( 8069): WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,I/ActivityManager(  898): Killing 6798:com.sec.kidsplat.installer/u0a189 (adj 13): bgCount ##41
,D/ConnectivityService(  898): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  898): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider(  898): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  898): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  898): getSBEnabled() enabled =false
D/SmartBondingService(  898): getSBEnabled() enabled =false
D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  898): getSBEnabled() enabled =false
,I/ApplicationPolicy(  898): updateDataUsageMap
,D/SmartBondingService(  898): getNetworkEnabled : wifi : false mobile : true
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3400): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5706): type=WIFI subType= reason=null isConnected=false
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3400): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,I/PCWCLIENTTRACE_PushUtil( 6465): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6465): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6465): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6465): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
I/PCWCLIENTTRACE_SYSTEMReceiver( 6465): noConnectivity : true
,I/DIAGMON_AGENT( 7350): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7350): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/FOTA_Client( 6829): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 6829): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 6829): [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.511: ( 6846): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.511: ( 6846): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450361836116
,I/KLMS-2.4.511: ( 6846): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.511: ( 6846): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.511: ( 6846): StateImplV2(): networkChangeListener().END
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SO_AGENT( 6861): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 4922): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 6551): [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
,I/SA      ( 6551): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 6551): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6551): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6551): [OR] == isSIMCardReady false ==
,E/SPPClientService( 4922): [[SystemStateMonitorService]] No Active Internet
,I/SA      ( 6551): [SCU] == networkStateCheck == false
I/SA      ( 6551): [OR] onReceive END
,I/SCloudBackupReceiver( 7399): Other Intent
,I/KnoxUsageLogPro( 7415): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7415): premStatus:2
,I/KnoxUsageLogPro( 7415): isEulaShown : false
I/KnoxUsageLogPro( 7415): KnoxUsageReceiver onReceive : not Processible, just return
,D/QuickConnect( 7514): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7514): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7514): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService(  898): exchangeData() failure , invalid userId
,D/RCPManagerService(  898): exchangeData() failure , invalid userId
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6968): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6968): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6968): StateMachine : Current State = 1
D/SecurityLogAgent( 6968): StateMachine : Changed Current State = 1
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/iu.Environment( 2297): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2297): num queued entries: 0
,I/iu.UploadsManager( 2297): num updated entries: 0
,I/iu.SyncManager( 2297): NEXT; no task
,W/bt-sdp  ( 2938): SDP - Rcvd conn cnf with error: 0xd  CID 0x45
,E/bt-btif ( 2938): DISCOVERY_COMP_EVT slot id:8, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2938): invalid rfc slot id: 8
,D/BluetoothSocket( 7186): close() in, this: android.bluetooth.BluetoothSocket@13ea41e, channel: 1, state: INIT
,D/BluetoothSocket( 7186): close() this: android.bluetooth.BluetoothSocket@13ea41e, channel: 1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2ae134ff, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1c4372ccmSocket: android.net.LocalSocket@2b7a3915 impl:android.net.LocalSocketImpl@3bace42a fd:FileDescriptor[116]
D/BluetoothSocket( 7186): Closing mSocket: android.net.LocalSocket@2b7a3915 impl:android.net.LocalSocketImpl@3bace42a fd:FileDescriptor[116]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7186): shutdown (thread ID: 1208)
,D/BluetoothSocket( 7186): close() in, this: android.bluetooth.BluetoothSocket@13ea41e, channel: 1, state: CLOSED
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7186): Exiting thread (thread ID: 1208)
,E/SMD     (  290): DCD ON
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
D/BatteryService(  898): stay LED for fully charged
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/bootchecker(  323): bootchecker wake up!!
,E/SMD     (  290): DCD ON
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/WifiHW  (  898): ##################### set firmware type 0 #####################
,I/WifiHW  (  282): wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
I/WifiHW  (  282): module is semco
E/WifiHW  (  282): ==========[WIFI] SEMCO MODULE ===========
I/WifiHW  (  282): wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
E/WifiHW  (  282): TEMP_FAILURE_RETRY complete
D/SoftapController(  282): Softap fwReload - Ok
,D/CommandListener(  282): Setting iface cfg
D/CommandListener(  282): Trying to bring down wlan0
,I/ActivityManager(  898): Killing 4347:com.sec.android.app.shealth/u0a40 (adj 13): bgCount ##41
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/NetdConnector(  898): NDC Command {82 interface setcfg wlan0 0.0.0.0 0 down multicast running broadcast} took too long (1158ms)
,D/CommandListener(  282): Clearing all IP addresses on wlan0
,D/Tethering(  898): InitialState.processMessage what=4
,E/Tethering(  898): No numeric data
,V/NetworkStats(  898): performPollLocked(flags=0x1)
,D/HotspotTile( 1183): onReceive : android.net.conn.TETHER_STATE_CHANGED
,D/NtpTrustedTime(  898): currentTimeMillis() cache hit
D/HotspotTile( 1183): updateTetherState():false, false
,D/Tethering(  898): sendTetherStateChangedBroadcast 0, 0, 0
,D/NetworkStatsFactory(  898): UpdateStatsForKnox
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/NetworkStats(  898): performPollLocked() took 9ms
,E/Tethering(  898): No numeric data
,D/HotspotTile( 1183): onReceive : android.net.conn.TETHER_STATE_CHANGED
,D/HotspotTile( 1183): updateTetherState():false, false
D/Tethering(  898): sendTetherStateChangedBroadcast 1, 0, 0
,D/NtpTrustedTime(  898): currentTimeMillis() cache hit
,D/NtpTrustedTime(  898): currentTimeMillis() cache hit
,D/NtpTrustedTime(  898): currentTimeMillis() cache hit
,E/WifiHW  (  898): supplicant_name : p2p_supplicant
,D/SmartBondingService(  898): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,D/StatusBar.NetworkController( 1183): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1183): onWifiSignalChanged enabled=false enabledDesc:null
,D/STATUSBAR-WifiQuickSettingButton( 1183): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-WifiQuickSettingButton( 1183): Wifi onReceive(2)
,D/HotspotTile( 1183): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-QSTileView( 1183): onStateChanged: Wi-Fi
,D/SmartBondingService(  898): getNetworkEnabled : wifi : false mobile : true
,D/HotspotTile( 1183): onReceive : 2, 0
,V/NetworkStats(  898): performPollLocked(flags=0x1)
,D/NtpTrustedTime(  898): currentTimeMillis() cache hit
,D/WifiMonitor(  898): startMonitoring(wlan0) with mConnected = false
,D/NetworkStatsFactory(  898): UpdateStatsForKnox
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/NetworkStats(  898): performPollLocked() took 13ms
,D/NtpTrustedTime(  898): currentTimeMillis() cache hit
,D/NtpTrustedTime(  898): currentTimeMillis() cache hit
,D/NtpTrustedTime(  898): currentTimeMillis() cache hit
,D/WifiCredService( 1325): Action received :android.net.wifi.WIFI_STATE_CHANGED
,I/wpa_supplicant( 8104): [wpa_supplicant_init]: use SECRIL
,I/wpa_supplicant( 8104): Successfully initialized wpa_supplicant
,I/SecureStorage( 8104): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,I/SecureStorage( 8104): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/SecureStorage(  441): [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 8104
I/SecureStorage(  441): [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
I/SecureStorage( 8104): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 8104): ssSupport state is = 1
,I/wpa_supplicant( 8104): >>>>> GET KEY, IV <<<<<
,I/SecureStorage( 8104): [INFO]: SPID(0x00000000)Processing data
E/SignOutReceiver( 6753): WIFI_STATE_CHANGED_ACTION
,I/SecureStorage(  441): [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 8104
I/SecureStorage(  441): [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 6968): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6968): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6968): StateMachine : Current State = 1
D/SecurityLogAgent( 6968): StateMachine : Changed Current State = 1
,I/SecureStorage(  441): [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/SecureStorage( 8104): [INFO]: SPID(0x00000000)Processing data has been completed
,I/SecureStorage( 8104): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,I/SecureStorage( 8104): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SecureStorage(  441): [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 8104
I/SecureStorage(  441): [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
I/SecureStorage( 8104): [INFO]: SPID(0x00000000)SS Daemon is running
,I/wpa_supplicant( 8104): ssSupport state is = 1
I/wpa_supplicant( 8104): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 8104): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,E/wpa_supplicant( 8104): SIM READ ERROR
I/wpa_supplicant( 8104): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 8104): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 8104): SIM READ ERROR
I/wpa_supplicant( 8104): Blacklist: Clear (all) 
,I/wpa_supplicant( 8104): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 8104): getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
I/wpa_supplicant( 8104): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,E/wpa_supplicant( 8104): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,I/wpa_supplicant( 8104): rfkill: Cannot open RFKILL control device
,I/wpa_supplicant( 8104): wlan0: Setting scan request: 0 sec 100000 usec
,I/wpa_supplicant( 8104): wlan0: State: DISCONNECTED -> DISCONNECTED
,I/SecureStorage( 8104): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 8104): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/SecureStorage(  441): [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 8104
I/SecureStorage(  441): [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
I/SecureStorage( 8104): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 8104): ssSupport state is = 1
,I/SecureStorage( 8104): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 8104): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/SecureStorage(  441): [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 8104
I/SecureStorage(  441): [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
I/SecureStorage( 8104): [INFO]: SPID(0x00000000)SS Daemon is running
,I/wpa_supplicant( 8104): ssSupport state is = 1
I/wpa_supplicant( 8104): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,E/wpa_supplicant( 8104): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 8104): SIM READ ERROR
I/wpa_supplicant( 8104): rfkill: Cannot open RFKILL control device
,E/SMD     (  290): DCD ON
,I/wpa_supplicant( 8104): p2p0: State: DISCONNECTED -> INACTIVE
,I/wpa_supplicant( 8104): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 8104): p2p0: State: INACTIVE -> DISCONNECTED
,I/wpa_supplicant( 8104): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,D/WifiNative-HAL(  898): callSECApiBoolean - ID [21]
,I/wpa_supplicant( 8104): HOTSPOT20_ENABLE called
,I/wpa_supplicant( 8104): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 8104): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 8104): SIM READ ERROR
I/wpa_supplicant( 8104): Blacklist: Clear (all) 
,I/wpa_supplicant( 8104): Skip scan - bUseNetwork false
,D/WifiNative-HAL(  898): callSECApiInt - ID [210]
,D/SmartBondingService(  898): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,D/StatusBar.NetworkController( 1183): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/SmartBondingService(  898): getNetworkEnabled : wifi : true mobile : true
,D/STATUSBAR-WifiQuickSettingButton( 1183): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1183): applyOpen
,D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1183): applyOpen
D/STATUSBAR-WifiQuickSettingButton( 1183): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-WifiQuickSettingButton( 1183): Wifi onReceive(3)
,D/HotspotTile( 1183): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-QSTileView( 1183): onStateChanged: Wi-Fi
D/WifiConfigStore(  898): Loading config and enabling all networks 
,D/HotspotTile( 1183): onReceive : 3, 0
,D/WifiCredService( 1325): Action received :android.net.wifi.WIFI_STATE_CHANGED
,E/WifiConfigStore(  898): Not a HS20
,E/WifiConfigStore(  898): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,E/SignOutReceiver( 6753): WIFI_STATE_CHANGED_ACTION
,D/WifiNative-HAL(  898): callSECApiInt - ID [65]
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6968): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6968): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6968): StateMachine : Current State = 1
D/SecurityLogAgent( 6968): StateMachine : Changed Current State = 1
,I/WifiStateMachine(  898): SkipScanAssoc WiFi enabled for P2P function. In this case, Skip scan and assoc for p2p connection
,D/WifiNative-HAL(  898): callSECApiBoolean - ID [13]
I/wpa_supplicant( 8104): USE_NETWORK : USE_NETWORK OFF
,D/WifiNative-HAL(  898): Setting external_sim to 1
,D/WifiStateMachine(  898): Setting OUI to DA-A1-19
,I/WifiNative-HAL(  898): startHal
E/wifi    (  898): getStaticLongField sWifiHalHandle 0x9c5be86c
D/wifi    (  898): halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x8020f6
I/WifiNative-HAL(  898): Could not start hal
,E/native  (  898): do suspend true
,E/WifiStateMachine(  898): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,D/WifiScanningService(  898): SCAN_AVAILABLE : 3
D/RttService(  898): SCAN_AVAILABLE : 3
D/WifiScanningService(  898): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  898): startHal
E/wifi    (  898): getStaticLongField sWifiHalHandle 0x950b199c
D/wifi    (  898): halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x4020e2
I/WifiNative-HAL(  898): Could not start hal
E/WifiScanningService(  898): could not start HAL
,D/WifiP2pService(  898): P2pDisabledState{ what=131203 }
D/RttService(  898): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  898): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,D/WifiNative-HAL(  898): callSECStringApiVoid - ID [215]
E/WifiNative-HAL(  898): invaild command id : 215
D/CommandListener(  282): Setting iface cfg
D/CommandListener(  282): Trying to bring up p2p0
,D/WifiMonitor(  898): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService(  898): P2pEnablingState
,D/WifiP2pService(  898): P2pEnablingState{ what=147457 }
D/WifiP2pService(  898): P2p socket connection successful
,D/WifiP2pService(  898): P2pEnabledState
,D/WifiP2pService(  898): sending p2p connection changed broadcast: DISCONNECTED
,E/WifiStateMachine(  898): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,D/WifiDisplayController(  898): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDirectBR( 8069): WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
D/WifiDisplayController(  898): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  898): disconnect
,D/WifiDisplayController(  898): updateConnection
D/WifiDisplayController(  898): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter(  898): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayController(  898): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WifiDisplayAdapter(  898): onP2pDisconnected
D/IpRemoteDisplayController(  898): disconnectWfdBridgeServer
,D/IpRemoteDisplayController(  898): WfdBridgeServer is already null
,E/ConnectivityService(  898): updateNetworkInfo()
,D/ConnectivityService(  898): ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,I/wpa_supplicant( 8104): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,D/AllShareCastTile( 1183): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,D/WifiDisplayAdapter(  898): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/AllShareCastTile( 1183): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,D/NearbySettings( 1325): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 1325): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1325): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1325): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/wpa_supplicant( 8104): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
I/NearbySettings( 1325): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1325): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1325): MountReceiver.mPrefHandler - 7002
,I/wpa_supplicant( 8104): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 8104): Skip scan - bUseNetwork false
,D/WifiNative-HAL(  898): p2pGetDeviceAddress
,D/FileShare-Server( 8040): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/WifiNative-HAL(  898): p2pGetDeviceAddress returning ea:50:8b:de:28:a3
,D/SecContentProvider2(  898): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  898): mCursor = null
,D/WifiDirectBR( 8069): WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/WifiDirectBR( 8069): WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
,W/ContextImpl( 8069): Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,D/WifiP2pService(  898): DeviceAddress: ea:28:a3
,D/WifiDisplayController(  898): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Note3-1
D/WifiDisplayController(  898):  deviceAddress: ea:50:8b:de:28:a3
D/WifiDisplayController(  898):  primary type: 10-0050F204-5
D/WifiDisplayController(  898):  secondary type: null
D/WifiDisplayController(  898):  wps: 0
D/WifiDisplayController(  898):  grpcapab: 0
D/WifiDisplayController(  898):  devcapab: 0
D/WifiDisplayController(  898):  status: 3
D/WifiDisplayController(  898):  wfdInfo: null
D/WifiDisplayController(  898):  groupownerAddress: null
D/WifiDisplayController(  898):  GOdeviceName: null
D/WifiDisplayController(  898):  interfaceAddress: 
D/WifiDisplayController(  898):  SConnectInfo : null
D/WifiDirectBR( 8069): stopServiceTest : false
,D/WifiP2pService(  898): sending p2p persistent groups changed broadcast
,D/WifiP2pService(  898): InactiveState
D/WifiP2pService(  898): InactiveState{ what=143376 }
,D/WifiP2pService(  898): P2pEnabledState{ what=143376 }
,I/wpa_supplicant( 8104): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,D/WifiP2pService(  898): InactiveState{ what=143376 }
W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 3
,D/WifiP2pService(  898): P2pEnabledState{ what=143376 }
,D/SSRM:n  (  898): SIOP:: AP = 300, PST = 293, CUR = 450
,E/SMD     (  290): DCD ON
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,E/Watchdog(  898): !@Sync 16
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 293, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 293, CUR = 450
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  898): Plugged
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryService(  898): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 293, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,V/AlarmManager(  898): waitForAlarm result :8
,E/Watchdog(  898): !@Sync 17
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/IOP_DB_BT( 2938): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
,D/IOP_DB_BT( 2938): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 2938): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 2938): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2938): db_query_execute: result 1
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): proc btwrite assertion
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/IOP_DB_BT( 2938): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
D/IOP_DB_BT( 2938): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 2938): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 2938): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 2938): db_query_execute: result 1
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
W/bt-btif ( 2938): info:x10
,D/        ( 2938): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 2938): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.NAME_CHANGED
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,I/BluetoothBondStateMachine( 2938): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 1
,D/SecContentProvider(  898): uri = 4 selection = bluetoothLogForRemote
,E/bt-btif ( 2938): check_cod: remote_cod = 0x5a020c
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
I/BluetoothBondStateMachine( 2938): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 10 NewState: 11
D/BtConfig.SecureMode( 2938): isSecureModeOn:false
,I/BluetoothBondStateMachine( 2938): Entering PendingCommandState State
,D/BluetoothTile( 1183):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 1183):  handleUpdatestate:false name:null
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.NAME_CHANGED
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.CLASS_CHANGED
V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothNotiBroadcastReceiver( 1325): onReceive
,E/BluetoothHeadset( 7778): BTStateChangeCB is registed
,E/BluetoothHeadset( 7778): BluetoothHeadset service is binded
,D/GMFPReceiver( 7778): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 7778): jangil::setProperties()
,D/GMFPReceiver( 7778): jangil::printBTStatus()
,D/SettingsProvider(  898): name = Wearable0001
D/SettingsProvider(  898): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  898): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  898): selectionArgs: false
,D/SettingsProvider(  898): selectionArgs: 10126
D/SecContentProvider(  898): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  898): ret = -1
D/GMFPReceiver( 7778): ::::::::Wearable0001::false
,D/SettingsProvider(  898): name = Wearable0002
D/SettingsProvider(  898): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  898): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  898): selectionArgs: false
D/SettingsProvider(  898): selectionArgs: 10126
,D/SecContentProvider(  898): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  898): ret = -1
D/GMFPReceiver( 7778): ::::::::Wearable0002::false
,D/GMFPReceiver( 7778): onServiceConnected() : 1
,D/GMFPReceiver( 7778): mBluetoothHeadset = true
,D/btif_config_util( 2938): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 2938): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 0
,D/BluetoothAdapterProperties( 2938): Failed to remove device: 34:FC:EF:11:AE:67
,D/SecContentProvider(  898): uri = 4 selection = bluetoothLogForRemote
,D/BluetoothTile( 1183):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 1183):  handleUpdatestate:false name:null
,I/BluetoothBondStateMachine( 2938): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 11 NewState: 10
,D/BtConfig.SecureMode( 2938): isSecureModeOn:false
D/HidService( 2938): getHidService(): returning com.android.bluetooth.hid.HidService@3788451a
,D/SettingsProvider(  898): name = bluetooth_input_device_priority_34:FC:EF:11:AE:67
,D/SettingsProvider(  898): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  898): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  898): selectionArgs: false
D/SettingsProvider(  898): selectionArgs: 1002
D/SecContentProvider(  898): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  898): ret = -1
,D/HidService( 2938): Saved priority 34:FC:EF:11:AE:67 = -1
V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/SettingsProvider(  898): name = bluetooth_a2dp_sink_priority_34:FC:EF:11:AE:67
D/SettingsProvider(  898): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  898): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  898): selectionArgs: false
D/SettingsProvider(  898): selectionArgs: 1002
D/SecContentProvider(  898): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  898): ret = -1
D/SettingsProvider(  898): name = bluetooth_headset_priority_34:FC:EF:11:AE:67
D/SettingsProvider(  898): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider(  898): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  898): selectionArgs: false
D/SettingsProvider(  898): selectionArgs: 1002
D/BluetoothNotiBroadcastReceiver( 1325): onReceive
D/SecContentProvider(  898): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  898): ret = -1
,I/BluetoothBondStateMachine( 2938): StableState(): Entering Off State
,E/BluetoothHeadset( 7778): BTStateChangeCB is registed
,E/BluetoothHeadset( 7778): BluetoothHeadset service is binded
,D/GMFPReceiver( 7778): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 7778): jangil::setProperties()
,D/GMFPReceiver( 7778): jangil::printBTStatus()
,D/SettingsProvider(  898): name = Wearable0001
D/SettingsProvider(  898): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  898): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  898): selectionArgs: false
D/SettingsProvider(  898): selectionArgs: 10126
D/SecContentProvider(  898): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  898): ret = -1
D/GMFPReceiver( 7778): ::::::::Wearable0001::false
D/SettingsProvider(  898): name = Wearable0002
D/SettingsProvider(  898): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  898): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  898): selectionArgs: false
D/SettingsProvider(  898): selectionArgs: 10126
D/SecContentProvider(  898): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  898): ret = -1
D/GMFPReceiver( 7778): ::::::::Wearable0002::false
,D/GMFPReceiver( 7778): onServiceConnected() : 1
,D/GMFPReceiver( 7778): mBluetoothHeadset = true
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,W/bt-btif ( 2938): new conn_srvc id:26, app_id:255
W/bt-btif ( 2938): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2938): bta_dm_pm_ssr:2, lat:1200
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/BluetoothSocket( 7186): socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@389e221b
,E/BluetoothRemoteDevices( 2938): setRfcommConnected true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7186): Incoming connection accepted
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,F/libc    ( 7186): Fatal signal 11 (SIGSEGV), code 2, fault addr 0x95b09fd0 in tid 7776 (Thread-1197)
,I/DEBUG   ( 8009): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
,I/DEBUG   ( 8009): Build fingerprint: 'samsung/hltexx/hlte:5.0/LRX21V/N9005XXUGBOB6:user/release-keys'
I/DEBUG   ( 8009): Revision: '8'
I/DEBUG   ( 8009): ABI: 'arm'
,I/DEBUG   ( 8009): pid: 7186, tid: 7776, name: Thread-1197  >>> com.test.thalitest <<<
I/DEBUG   ( 8009): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0x95b09fd0
,I/DEBUG   ( 8009):     r0 700f9400  r1 724860b8  r2 12d9f9b0  r3 12e818a0
,I/DEBUG   ( 8009):     r4 000000c2  r5 700f9400  r6 724860b8  r7 12e818a0
I/DEBUG   ( 8009):     r8 72486060  r9 966b9c00  sl 12d9f9b0  fp 95c0b888
I/DEBUG   ( 8009):     ip 95b09fd0  sp 95b0bfd0  lr 74e782d9  pc 74e7825c  cpsr a00f0030
I/DEBUG   ( 8009): 
I/DEBUG   ( 8009): backtrace:
,I/DEBUG   ( 8009):     #00 pc 0009225c  /system/framework/arm/boot.oat
I/DEBUG   ( 8009):     #01 pc 000922d7  /system/framework/arm/boot.oat
,E/SMD     (  290): DCD ON
,D/bt_upio ( 2938): ..proc_btwrite_timeout..
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/DEBUG   ( 8009): 
I/DEBUG   ( 8009): Tombstone written to: /data/tombstones/tombstone_09
E/        ( 8009): !@dumpstate -k -t -z -d -o /data/log/dumpstate_app_native -m 7186
,I/BootReceiver(  898): Copying /data/tombstones/tombstone_09 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl(  898): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
D/bt_vendor( 2938): op for 7
,W/ActivityManager(  898):   Force finishing activity com.test.thalitest/.MainActivity
,I/ActivityManager(  898): Killing 6571:com.android.mms/u0a55 (adj 13): bgCount ##41
,I/dumpstate( 8167): begin
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/CrashAnrDetector(  898): Build: samsung/hltexx/hlte:5.0/LRX21V/N9005XXUGBOB6:user/release-keys
D/CrashAnrDetector(  898): Hardware: MSM8974
D/CrashAnrDetector(  898): Revision: 8
D/CrashAnrDetector(  898): Bootloader: N9005XXUGBOB6
D/CrashAnrDetector(  898): Radio: unknown
D/CrashAnrDetector(  898): Kernel: Linux version 3.4.0-3643614 (dpi@SWDD5914) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Wed Feb 25 21:52:47 KST 2015
D/CrashAnrDetector(  898): 
D/CrashAnrDetector(  898): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector(  898): Build fingerprint: 'samsung/hltexx/hlte:5.0/LRX21V/N9005XXUGBOB6:user/release-keys'
D/CrashAnrDetector(  898): Revision: '8'
D/CrashAnrDetector(  898): ABI: 'arm'
D/CrashAnrDetector(  898): pid: 7186, tid: 7776, name: Thread-1197  >>> com.test.thalitest <<<
D/CrashAnrDetector(  898): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0x95b09fd0
D/CrashAnrDetector(  898):     r0 700f9400  r1 724860b8  r2 12d9f9b0  r3 12e818a0
D/CrashAnrDetector(  898):     r4 000000c2  r5 700f9400  r6 724860b8  r7 12e818a0
D/CrashAnrDetector(  898):     r8 72486060  r9 966b9c00  sl 12d9f9b0  fp 95c0b888
D/CrashAnrDetector(  898):     ip 95b09fd0  sp 95b0bfd0  lr 74e782d9  pc 74e7825c  cpsr a00f0030
D/CrashAnrDetector(  898):     d0  0000000000000000  d1  0000000000000000
D/CrashAnrDetector(  898):     d2  0000000000000000  d3  0000000000000000
D/CrashAnrDetector(  898):     d4  0040404040404040  d5  0004000400040004
D/CrashAnrDetector(  898):     d6  0000000000000000  d7  0003000400040004
D/CrashAnrDetector(  898):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector(  898):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector(  898):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector(  898):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector(  898):     d16 0000000000000000  d17 7320656d69746e75
D/CrashAnrDetector(  898):     d18 0069007200750064  d19 007200200067006e
D/CrashAnrDetector(  898):     d20 0101010101010101  d21 0101010101010101
D/CrashAnrDetector(  898):     d22 8080808080808080  d23 8080808080808080
D/CrashAnrDetector(  898):     d24 4000404040404040  d25 0040404040404040
D/CrashAnrDetector(  898):     d26 0f0f0f0f0f0f0f0f  d27 0f0f0f0f0f0f0f0f
D/CrashAnrDetector(  898):     d28 0101010101010101  d29 0101010101010101
D/CrashAnrDetector(  898):     d30 0000000000000000  d31 0000000000000000
D/CrashAnrDetector(  898):     scr 20000013
D/CrashAnrDetector(  898): 
D/CrashAnrDetector(  898): backtrace:
D/CrashAnrDetector(  898):     #00 pc 0009225c  /system/framework/arm/boot.oat
D/CrashAnrDetector(  898):     #01 pc 000922d7  /system/framework/arm/boot.oat
D/CrashAnrDetector(  898): 
D/CrashAnrDetector(  898): stack:
D/CrashAnrDetector(  898):          95b0bf50  00000000  
D/CrashAnrDetector(  898):          95b0bf54  00000000  
D/CrashAnrDetector(  898):          95b0bf58  00000000  
D/CrashAnrDetector(  898):          95b0bf5c  00000000  
D/CrashAnrDetector(  898):          95b0bf60  00000000  
D/CrashAnrDetector(  898):          95b0bf64  00000000  
D/CrashAnrDetector(  898):          95b0bf68  00000000  
D/CrashAnrDetector(  898):          95b0bf6c  00000000  
D/CrashAnrDetector(  898):          95b0bf70  00000000  
D/CrashAnrDetector(  898):          95b0bf74  00000000  
D/CrashAnrDetector(  898):          95b0bf78  00000000  
D/CrashAnrDetector(  898):          95b0bf7c  00000000  
D/CrashAnrDetector(  898):          95b0bf80  00000000  
D/CrashAnrDetector(  898):          95b0bf84  00000000  
D/CrashAnrDetector(  898):          95b0bf88  00000000  
D/CrashAnrDetector(  898):          95b0bf8c  00000000  
D/CrashAnrDetector(  898):          95b0bf90  00000000  
D/CrashAnrDetector(  898):          95b0bf94  00000000  
D/CrashAnrDetector(  898):          95b0bf98  00000000  
D/CrashAnrDetector(  898):          95b0bf9c  00000000  
D/CrashAnrDetector(  898):          95b0bfa0  00000000  
D/CrashAnrDetector(  898):          95b0bfa4  00000000  
D/Cr,ashAnrDetector(  898):          95b0bfa8  00000000  
D/CrashAnrDetector(  898):          95b0bfac  00000000  
D/CrashAnrDetector(  898):          95b0bfb0  700e6af8  /system/framework/arm/boot.art
D/CrashAnrDetector(  898):          95b0bfb4  00000000  
D/CrashAnrDetector(  898):          95b0bfb8  00000000  
D/CrashAnrDetector(  898):          95b0bfbc  00000000  
D/CrashAnrDetector(  898):          95b0bfc0  00000000  
D/CrashAnrDetector(  898):          95b0bfc4  700f9400  /system/framework/arm/boot.art
D/CrashAnrDetector(  898):          95b0bfc8  e3a070ad  
D/CrashAnrDetector(  898):          95b0bfcc  ef9000ad  
D/CrashAnrDetector(  898):     #00  95b0bfd0  700f9400  /system/framework/arm/boot.art
D/CrashAnrDetector(  898):          ........  ........
D/CrashAnrDetector(  898):     #01  95b0bfd0  700f9400  /system/framework/arm/boot.art
D/CrashAnrDetector(  898):          95b0bfd4  00000000  
D/CrashAnrDetector(  898):          95b0bfd8  00000000  
D/CrashAnrDetector(  898):          95b0bfdc  00000000  
D/CrashAnrDetector(  898):          95b0bfe0  00000000  
D/CrashAnrDetector(  898):          95b0bfe4  00000000  
D/CrashAnrDetector(  898):          95b0bfe8  700f9400  /system/framework/arm/boot.art
D/CrashAnrDetector(  898):          95b0bfec  72486060  /system/framework/arm/boot.art
D/CrashAnrDetector(  898):          95b0bff0  12e818a0  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector(  898):          95b0bff4  724860b8  /system/framework/arm/boot.art
D/CrashAnrDetector(  898):          95b0bff8  12d9f9b0  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector(  898):          95b0bffc  74e7828d  /system/framework/arm/boot.oat
D/CrashAnrDetector(  898):          95b0c000  700f9400  /system/framework/arm/boot.art
D/CrashAnrDetector(  898):          95b0c004  00000000  
D/CrashAnrDetector(  898):          95b0c008  00000000  
D/CrashAnrDetector(  898):          95b0c00c  00000000  
D/CrashAnrDetector(  898):          95b0c010  700e6af8  /system/framework/arm/boot.art
D/CrashAnrDetector(  898):          95b0c014  00000000  
D/CrashAnrDetector(  898):          95b0c018  700f9400  /system/framework/arm/boot.art
D/CrashAnrDetector(  898):          95b0c01c  724860b8  /system/framework/arm/boot.art
D/CrashAnrDetector(  898):          95b0c020  12e818a0  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector(  898):          95b0c024  72486060  /system/framework/arm/boot.art
D/CrashAnrDetector(  898):          95b0c028  12d9f9b0  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector(  898):          95b0c02c  74e782d9  /system/framework/arm/boot.oat
D/CrashAnrDetector(  898):          95b0c030  700f9400  /system/framework/
D/CrashAnrDetector(  898): processName:com.test.thalitest
W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1700 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
D/CrashAnrDetector(  898): broadcastEvent : com.test.thalitest SYSTEM_TOMBSTONE
,D/CountryDetector(  898): No listener is left
,W/ActivityManager(  898): mDVFSHelper.acquire()
,I/DBG_DM  ( 3400): [com.wssyncmldm.ui.XUIInstallConfirmActivity(477/onResume)] 
,I/DBG_DM  ( 3400): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 20
,I/DBG_DM  ( 3400): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,I/DBG_DM  ( 3400): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3400): [com.wssyncmldm.ui.XUIInstallConfirmActivity(487/onResume)] Postpone Count : 20
,I/DBG_DM  ( 3400): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,I/DBG_DM  ( 3400): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 3400): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/SecContentProvider2(  898): uri = 14 selection = getSealedState
D/SecContentProvider2(  898): mCursor = null
,D/ApplicationPolicy(  898): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy(  898): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/StatusBar( 1183): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/DBG_DM  ( 3400): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 20
,D/PersonaManager( 1183): isKioskContainerExistOnDevice
D/PersonaManager( 1183): isKioskContainerExistOnDevice
D/PanelView( 1183): There is/are notification(s) 
D/PanelView( 1183): There is/are notification(s) 
,I/DBG_DM  ( 3400): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,I/DBG_DM  ( 3400): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3400): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 3400): [IIlllIlIIlIllIlllIll(376/llIIllllIIlllIIIIlll)] 
,I/DBG_DM  ( 3400): [IIlllIlIIlIllIlllIll(397/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
,D/ActivityManager(  898): post active user change for 0
,D/KnoxTimeoutHandler(  898): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  898): handleActiveUserChange for user 0
,I/DBG_DM  ( 3400): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
,I/SurfaceFlinger(  254): id=16 createSurf (1080x1920),2 flag=404, YUIInstallC
,V/ActivityThread( 3400): updateVisibility : ActivityRecord{18008ede token=android.os.BinderProxy@35c009e7 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,I/Timeline( 3400): Timeline: Activity_idle id: android.os.BinderProxy@35c009e7 time:529011
,W/ActivityManager(  898): mDVFSHelper.release()
I/Timeline(  898): Timeline: Activity_windows_visible id: ActivityRecord{2170d161 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t2} time:529027
,D/ConnectivityService(  898): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/SSRM:n  (  898): SIOP:: AP = 310, PST = 295, CUR = 450
,D/IOP_DB_BT( 2938): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value b0:c5:59:3f:75:69
,D/IOP_DB_BT( 2938): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2938): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 2938): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2938): db_query_execute: result 1
D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): proc btwrite assertion
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/IOP_DB_BT( 2938): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value b0:c5:59:3f:75:69
,D/IOP_DB_BT( 2938): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2938): db_query_add_key: key KEY_LMP_VER, value 7:24844
D/IOP_DB_BT( 2938): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2938): db_query_execute: result 1
,W/bt-btif ( 2938): info:x10
D/        ( 2938): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,E/BluetoothRemoteDevices( 2938): aclStateChangeCallback: Device is NULL
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.NAME_CHANGED
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,E/SMD     (  290): DCD ON
,E/bt-btm  ( 2938): tBTM_SEC_DEV:0xa1ce58dc rs_disc_pending=1
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
W/bt-btif ( 2938): bta_dm_check_av:0
W/bt-btif ( 2938): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2938): tBTM_SEC_DEV:0xa1ce5a9c rs_disc_pending=0
W/bt-btif ( 2938): bta_dm_check_av:0
W/bt-btif ( 2938): btif_dm_cback : unhandled event (14)
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,I/BluetoothBondStateMachine( 2938): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 1
,D/SecContentProvider(  898): uri = 4 selection = bluetoothLogForRemote
,E/bt-btif ( 2938): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2938): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 10 NewState: 11
D/BtConfig.SecureMode( 2938): isSecureModeOn:false
I/BluetoothBondStateMachine( 2938): Entering PendingCommandState State
D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.NAME_CHANGED
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.CLASS_CHANGED
,D/BluetoothTile( 1183):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 1183):  handleUpdatestate:false name:null
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothNotiBroadcastReceiver( 1325): onReceive
,E/BluetoothHeadset( 7778): BTStateChangeCB is registed
,E/BluetoothHeadset( 7778): BluetoothHeadset service is binded
,D/GMFPReceiver( 7778): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 7778): jangil::setProperties()
,D/GMFPReceiver( 7778): jangil::printBTStatus()
,D/SettingsProvider(  898): name = Wearable0001
D/SettingsProvider(  898): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider(  898): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  898): selectionArgs: false
D/SettingsProvider(  898): selectionArgs: 10126
D/SecContentProvider(  898): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  898): ret = -1
D/GMFPReceiver( 7778): ::::::::Wearable0001::false
,D/SettingsProvider(  898): name = Wearable0002
D/SettingsProvider(  898): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  898): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  898): selectionArgs: false
D/SettingsProvider(  898): selectionArgs: 10126
,D/SecContentProvider(  898): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  898): ret = -1
D/GMFPReceiver( 7778): ::::::::Wearable0002::false
,D/GMFPReceiver( 7778): onServiceConnected() : 1
,D/GMFPReceiver( 7778): mBluetoothHeadset = true
,D/btif_config_util( 2938): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 2938): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 0
D/BluetoothAdapterProperties( 2938): Failed to remove device: B0:C5:59:3F:75:69
,D/SecContentProvider(  898): uri = 4 selection = bluetoothLogForRemote
,I/BluetoothBondStateMachine( 2938): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 11 NewState: 10
D/BtConfig.SecureMode( 2938): isSecureModeOn:false
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.BOND_STATE_CHANGED
D/HidService( 2938): getHidService(): returning com.android.bluetooth.hid.HidService@3788451a
,D/SettingsProvider(  898): name = bluetooth_input_device_priority_B0:C5:59:3F:75:69
D/SettingsProvider(  898): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  898): projectionArgs: isSettingsChangesAllowed
D/BluetoothTile( 1183):  onBluetoothPairedDevicesChanged:
D/SettingsProvider(  898): selectionArgs: false
D/SettingsProvider(  898): selectionArgs: 1002
D/SecContentProvider(  898): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  898): ret = -1
D/HidService( 2938): Saved priority B0:C5:59:3F:75:69 = -1
D/BluetoothTile( 1183):  handleUpdatestate:false name:null
D/BluetoothNotiBroadcastReceiver( 1325): onReceive
D/SettingsProvider(  898): name = bluetooth_a2dp_sink_priority_B0:C5:59:3F:75:69
,D/SettingsProvider(  898): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  898): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  898): selectionArgs: false
D/SettingsProvider(  898): selectionArgs: 1002
,D/SecContentProvider(  898): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  898): ret = -1
,D/SettingsProvider(  898): name = bluetooth_headset_priority_B0:C5:59:3F:75:69
,D/SettingsProvider(  898): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  898): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  898): selectionArgs: false
D/SettingsProvider(  898): selectionArgs: 1002
D/SecContentProvider(  898): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  898): ret = -1
,E/BluetoothHeadset( 7778): BTStateChangeCB is registed
,I/BluetoothBondStateMachine( 2938): StableState(): Entering Off State
E/BluetoothHeadset( 7778): BluetoothHeadset service is binded
D/GMFPReceiver( 7778): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 7778): jangil::setProperties()
,D/GMFPReceiver( 7778): jangil::printBTStatus()
,D/SettingsProvider(  898): name = Wearable0001
D/SettingsProvider(  898): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  898): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider(  898): selectionArgs: false
D/SettingsProvider(  898): selectionArgs: 10126
D/SecContentProvider(  898): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  898): ret = -1
,D/GMFPReceiver( 7778): ::::::::Wearable0001::false
D/SettingsProvider(  898): name = Wearable0002
,D/SettingsProvider(  898): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  898): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  898): selectionArgs: false
D/SettingsProvider(  898): selectionArgs: 10126
D/SecContentProvider(  898): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  898): ret = -1
D/GMFPReceiver( 7778): ::::::::Wearable0002::false
,D/GMFPReceiver( 7778): onServiceConnected() : 1
,D/GMFPReceiver( 7778): mBluetoothHeadset = true
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7,
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7,
D/bt_upio ( 2938): BT_WAKE is asserted already
,W/bt-btif ( 2938): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2938): bta_dm_pm_ssr conn_srvc id:26, app_id:255
D/bt_vendor( 2938): op for 7,
W/bt-btif ( 2938): bta_dm_pm_ssr:2, lat:1200
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already,
,D/TaskPersister(  898): removeObsoleteFile: deleting file=2_task.xml
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/bt-btm  ( 2938): tBTM_SEC_DEV:0xa1ce5a9c rs_disc_pending=1
W/bt-btif ( 2938): bta_dm_check_av:0
D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
W/bt-btif ( 2938): btif_dm_cback : unhandled event (14)
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_upio ( 2938): ..proc_btwrite_timeout..
,D/IOP_DB_BT( 2938): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
D/IOP_DB_BT( 2938): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2938): db_query_add_key: key KEY_LMP_VER, value 7:24844
D/IOP_DB_BT( 2938): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 2938): db_query_execute: result 1
D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_upio ( 2938): proc btwrite assertion
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/IOP_DB_BT( 2938): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
,D/IOP_DB_BT( 2938): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2938): db_query_add_key: key KEY_LMP_VER, value 7:24844
D/IOP_DB_BT( 2938): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2938): db_query_execute: result 1
W/bt-btif ( 2938): info:x10
,D/        ( 2938): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 2938): aclStateChangeCallback: Device is NULL
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.NAME_CHANGED
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,E/bt-btm  ( 2938): tBTM_SEC_DEV:0xa1ce5c5c rs_disc_pending=0
,W/bt-btif ( 2938): bta_dm_check_av:0
,W/bt-btif ( 2938): btif_dm_cback : unhandled event (14)
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,E/SMD     (  290): DCD ON
,D/TimaService(  898): TIMA: timaDumpLog
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 5
,D/bt_upio ( 2938): ..proc_btwrite_timeout..
,E/bt-btm  ( 2938): tBTM_SEC_DEV:0xa1ce58dc rs_disc_pending=0
,W/bt-btif ( 2938): bta_dm_check_av:0
,W/bt-btif ( 2938): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 2938): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
,D/SecContentProvider(  898): uri = 4 selection = bluetoothLogForRemote
,E/bt-btif ( 2938): check_cod: remote_cod = 0x5a020c
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
D/bt_upio ( 2938): proc btwrite assertion
,I/BluetoothBondStateMachine( 2938): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
D/BtConfig.SecureMode( 2938): isSecureModeOn:false
,I/BluetoothBondStateMachine( 2938): Entering PendingCommandState State
,D/BluetoothTile( 1183):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 1183):  handleUpdatestate:false name:null
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.NAME_CHANGED
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.CLASS_CHANGED
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothNotiBroadcastReceiver( 1325): onReceive
,E/BluetoothHeadset( 7778): BTStateChangeCB is registed
,E/BluetoothHeadset( 7778): BluetoothHeadset service is binded
,D/GMFPReceiver( 7778): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 7778): jangil::setProperties()
,D/GMFPReceiver( 7778): jangil::printBTStatus()
,D/SettingsProvider(  898): name = Wearable0001
D/SettingsProvider(  898): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider(  898): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  898): selectionArgs: false
D/SettingsProvider(  898): selectionArgs: 10126
D/SecContentProvider(  898): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  898): ret = -1
,D/GMFPReceiver( 7778): ::::::::Wearable0001::false
D/SettingsProvider(  898): name = Wearable0002
D/SettingsProvider(  898): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  898): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider(  898): selectionArgs: false
D/SettingsProvider(  898): selectionArgs: 10126
D/SecContentProvider(  898): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  898): ret = -1
D/GMFPReceiver( 7778): ::::::::Wearable0002::false
,D/GMFPReceiver( 7778): onServiceConnected() : 1
,D/GMFPReceiver( 7778): mBluetoothHeadset = true
,D/btif_config_util( 2938): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 2938): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,D/BluetoothAdapterProperties( 2938): Failed to remove device: 7C:F9:0E:34:8A:A0
,D/SecContentProvider(  898): uri = 4 selection = bluetoothLogForRemote
,D/BluetoothTile( 1183):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 1183):  handleUpdatestate:false name:null
,I/BluetoothBondStateMachine( 2938): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,D/BtConfig.SecureMode( 2938): isSecureModeOn:false
,D/HidService( 2938): getHidService(): returning com.android.bluetooth.hid.HidService@3788451a
,D/SettingsProvider(  898): name = bluetooth_input_device_priority_7C:F9:0E:34:8A:A0
,D/SettingsProvider(  898): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  898): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  898): selectionArgs: false
D/SettingsProvider(  898): selectionArgs: 1002
D/SecContentProvider(  898): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  898): ret = -1
D/HidService( 2938): Saved priority 7C:F9:0E:34:8A:A0 = -1
,D/SettingsProvider(  898): name = bluetooth_a2dp_sink_priority_7C:F9:0E:34:8A:A0
D/SettingsProvider(  898): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  898): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  898): selectionArgs: false
D/SettingsProvider(  898): selectionArgs: 1002
,D/SecContentProvider(  898): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  898): ret = -1
,D/SettingsProvider(  898): name = bluetooth_headset_priority_7C:F9:0E:34:8A:A0
D/SettingsProvider(  898): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  898): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  898): selectionArgs: false
,D/SettingsProvider(  898): selectionArgs: 1002
D/SecContentProvider(  898): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  898): ret = -1
,I/BluetoothBondStateMachine( 2938): StableState(): Entering Off State
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothNotiBroadcastReceiver( 1325): onReceive
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,E/BluetoothHeadset( 7778): BTStateChangeCB is registed
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,E/BluetoothHeadset( 7778): BluetoothHeadset service is binded
,D/GMFPReceiver( 7778): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 7778): jangil::setProperties()
,D/GMFPReceiver( 7778): jangil::printBTStatus()
,D/SettingsProvider(  898): name = Wearable0001
D/SettingsProvider(  898): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
D/SettingsProvider(  898): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  898): selectionArgs: false
D/SettingsProvider(  898): selectionArgs: 10126
,D/SecContentProvider(  898): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  898): ret = -1
,D/GMFPReceiver( 7778): ::::::::Wearable0001::false
D/SettingsProvider(  898): name = Wearable0002
,D/SettingsProvider(  898): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  898): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  898): selectionArgs: false
D/SettingsProvider(  898): selectionArgs: 10126
D/SecContentProvider(  898): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  898): ret = -1
,D/GMFPReceiver( 7778): ::::::::Wearable0002::false
,D/GMFPReceiver( 7778): onServiceConnected() : 1
,D/GMFPReceiver( 7778): mBluetoothHeadset = true
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
W/bt-btif ( 2938): new conn_srvc id:26, app_id:255
W/bt-btif ( 2938): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2938): bta_dm_pm_ssr:2, lat:1200
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
E/bt-btm  ( 2938): tBTM_SEC_DEV:0xa1ce5c5c rs_disc_pending=1
W/bt-btif ( 2938): bta_dm_check_av:0
,W/bt-btif ( 2938): btif_dm_cback : unhandled event (14)
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,E/bt-btm  ( 2938): tBTM_SEC_DEV:0xa1ce58dc rs_disc_pending=1
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
W/bt-btif ( 2938): bta_dm_check_av:0
W/bt-btif ( 2938): btif_dm_cback : unhandled event (14)
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryService(  898): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,E/SMD     (  290): DCD ON
,D/bt_upio ( 2938): ..proc_btwrite_timeout..
,E/bt-btm  ( 2938): tBTM_SEC_DEV:0xa1ce58dc rs_disc_pending=0
,W/bt-btif ( 2938): bta_dm_check_av:0
W/bt-btif ( 2938): btif_dm_cback : unhandled event (14)
,D/bt_vendor( 2938): op for 7
,W/ActivityManager(  898): Activity destroy timeout for ActivityRecord{2e9884c1 u0 com.test.thalitest/.MainActivity t4 f}
,D/StatusBarManagerService(  898): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  898): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams,
,I/SurfaceFlinger(  254): id=14 Removed NainActivit (6/9)
,D/PointerIcon(  898): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon(  898): setMouseCustomIcon IconType is same.101
,D/PointerIcon(  898): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  898): setHoveringSpenCustomIcon IconType is same.1
,D/InputMethodManagerService(  898): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/dumpstate( 8167): waiting for zip started
,I/dumpstate( 8167): waiting for zip end
I/dumpstate( 8167): done
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): proc btwrite assertion
D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,I/ActivityManager(  898): Process com.test.thalitest (pid 7186)(adj 9) has died(338,1468)
,I/Zygote  (  320): Process 7186 exited due to signal (11)
,E/SMD     (  290): DCD ON
,W/bt-btif ( 2938): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,E/bt-btif ( 2938): bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/SSRM:n  (  898): SIOP:: AP = 300, PST = 296, CUR = 450
,W/bt-btif ( 2938): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
E/bt-btif ( 2938): bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,W/bt-btif ( 2938): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,E/bt-btif ( 2938): bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,E/bt-btm  ( 2938): tBTM_SEC_DEV:0xa1ce58dc rs_disc_pending=1
,W/bt-btif ( 2938): bta_dm_check_av:0
,W/bt-btif ( 2938): btif_dm_cback : unhandled event (14)
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/ConnectivityService(  898): Failed to find a new network - expiring NetTransition Wakelock
,D/bt_upio ( 2938): ..proc_btwrite_timeout..
,D/bt_vendor( 2938): op for 7
,I/PowerManagerService(  898): [PWL] Off : 455s ago
,I/PowerManagerService(  898): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  898): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  898): [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=2938, ws=null) (elapsedTime=16047)
,E/SMD     (  290): DCD ON
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): proc btwrite assertion
,E/bt-btm  ( 2938): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 2938): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 1183): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService( 2938): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a28d88b
,D/BtConfig.SecureMode( 2938): isSecureModeOn:false
,D/SecContentProvider(  898): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,I/BluetoothPbapService( 2938): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,D/KeyguardViewMediator( 1183): isGear1: device is not B1!
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothManager( 7269): [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.device.action.ACL_DISCONNECTED
E/BluetoothEventManager( 1325): ACTION_ACL_DISCONNECTED
,D/BluetoothManager( 7269): [SVoiceBT, LatencyCheck] BT onHeadsetStateChanged(): isConnected= false
,W/System.err( 7269): java.lang.NullPointerException: Attempt to invoke virtual method 'java.util.List android.bluetooth.BluetoothHeadset.getConnectedDevices()' on a null object reference
W/System.err( 7269): 	at com.vlingo.core.internal.bluetooth.BluetoothManager.getBluetoothHeadsetConnctedDevices(BluetoothManager.java:941)
W/System.err( 7269): 	at com.vlingo.core.internal.bluetooth.BluetoothManager.onHeadsetStateChanged(BluetoothManager.java:462)
,W/System.err( 7269): 	at com.vlingo.core.internal.bluetooth.BluetoothManager$BTStateBroadcastReceiver.onReceive(BluetoothManager.java:1245)
W/System.err( 7269): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:923)
W/System.err( 7269): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7269): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7269): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7269): 	at android.app.ActivityThread.main(ActivityThread.java:5940)
,W/System.err( 7269): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7269): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7269): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1389)
W/System.err( 7269): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1184)
D/BluetoothManager( 7269): ====[SVoiceBT, LatencyCheck] closeBtProxy===
,I/BTConnectionReceiver( 1571): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1571): Bluetooth Device Name: S5-1
,E/bt-btm  ( 2938): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 2938): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 1183): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService( 2938): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a28d88b
,D/BtConfig.SecureMode( 2938): isSecureModeOn:false
,D/SecContentProvider(  898): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,I/BluetoothPbapService( 2938): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,D/KeyguardViewMediator( 1183): isGear1: device is not B1!
,D/BluetoothManager( 7269): [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothManager( 7269): [SVoiceBT, LatencyCheck] BT onHeadsetStateChanged(): isConnected= false
E/BluetoothEventManager( 1325): ACTION_ACL_DISCONNECTED
,W/System.err( 7269): java.lang.NullPointerException: Attempt to invoke virtual method 'java.util.List android.bluetooth.BluetoothHeadset.getConnectedDevices()' on a null object reference
W/System.err( 7269): 	at com.vlingo.core.internal.bluetooth.BluetoothManager.getBluetoothHeadsetConnctedDevices(BluetoothManager.java:941)
,W/System.err( 7269): 	at com.vlingo.core.internal.bluetooth.BluetoothManager.onHeadsetStateChanged(BluetoothManager.java:462)
W/System.err( 7269): 	at com.vlingo.core.internal.bluetooth.BluetoothManager$BTStateBroadcastReceiver.onReceive(BluetoothManager.java:1245)
W/System.err( 7269): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:923)
W/System.err( 7269): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7269): 	at android.os.Handler.dispatchMessage(Handler.java:95)
,W/System.err( 7269): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7269): 	at android.app.ActivityThread.main(ActivityThread.java:5940)
W/System.err( 7269): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7269): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7269): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1389)
,W/System.err( 7269): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1184)
D/BluetoothManager( 7269): ====[SVoiceBT, LatencyCheck] closeBtProxy===
,I/BTConnectionReceiver( 1571): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1571): Bluetooth Device Name: Nexus 5
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,E/bt-btm  ( 2938): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 2938): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 1183): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService( 2938): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a28d88b
,D/BtConfig.SecureMode( 2938): isSecureModeOn:false
,D/SecContentProvider(  898): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,I/BluetoothPbapService( 2938): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 1183): isGear1: device is not B1!
,D/BluetoothManager( 7269): [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothManager( 7269): [SVoiceBT, LatencyCheck] BT onHeadsetStateChanged(): isConnected= false
E/BluetoothEventManager( 1325): ACTION_ACL_DISCONNECTED
,W/System.err( 7269): java.lang.NullPointerException: Attempt to invoke virtual method 'java.util.List android.bluetooth.BluetoothHeadset.getConnectedDevices()' on a null object reference
W/System.err( 7269): 	at com.vlingo.core.internal.bluetooth.BluetoothManager.getBluetoothHeadsetConnctedDevices(BluetoothManager.java:941)
,W/System.err( 7269): 	at com.vlingo.core.internal.bluetooth.BluetoothManager.onHeadsetStateChanged(BluetoothManager.java:462)
W/System.err( 7269): 	at com.vlingo.core.internal.bluetooth.BluetoothManager$BTStateBroadcastReceiver.onReceive(BluetoothManager.java:1245)
W/System.err( 7269): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:923)
,W/System.err( 7269): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7269): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7269): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 7269): 	at android.app.ActivityThread.main(ActivityThread.java:5940)
W/System.err( 7269): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7269): 	at java.lang.reflect.Method.invoke(Method.java:372)
,W/System.err( 7269): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1389)
W/System.err( 7269): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1184)
D/BluetoothManager( 7269): ====[SVoiceBT, LatencyCheck] closeBtProxy===
,I/BTConnectionReceiver( 1571): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1571): Bluetooth Device Name: Thali Test (Galaxy S5)
,D/bt_upio ( 2938): ..proc_btwrite_timeout..
,E/SMD     (  290): DCD ON
,D/bt_vendor( 2938): op for 7
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 296, CUR = 450
,E/SMD     (  290): DCD ON
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD ON
,E/Watchdog(  898): !@Sync 18
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,E/SMD     (  290): DCD ON
,I/Atfwd_Sendcmd(  327): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  327): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 296, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 295, CUR = 450
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 294, CUR = 450
,E/SMD     (  290): DCD ON
,I/Atfwd_Daemon(  327): Stop the daemon....
,E/SMD     (  290): DCD ON
,E/Watchdog(  898): !@Sync 19
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 293, CUR = 450
,E/SMD     (  290): DCD ON
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 293, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 293, CUR = 450
,E/SMD     (  290): DCD ON
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  898): [PWL] Off : 525s ago
,D/TimaService(  898): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  898): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  898): TimaServiceHandler.handleMessage what =1
,E/SMD     (  290): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  898): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  898): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  898): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  898): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  898): !@Sync 20
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 293, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 291, CUR = 450
,W/ContextImpl(  898): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryService(  898): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/Watchdog(  898): !@Sync 21
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 289, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  898): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 288, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/Watchdog(  898): !@Sync 22
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 287, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,I/PowerManagerService(  898): [PWL] Off : 600s ago
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 286, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  898): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 285, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/Watchdog(  898): !@Sync 23
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): stay LED for fully charged
D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 284, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  898): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 283, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 282, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/Watchdog(  898): !@Sync 24
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/Watchdog(  898): !@Sync 25
,I/PowerManagerService(  898): [PWL] Off : 680s ago
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryService(  898): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/Watchdog(  898): !@Sync 26
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  898): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/Watchdog(  898): !@Sync 27
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryService(  898): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,I/PowerManagerService(  898): [PWL] Off : 765s ago
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/Watchdog(  898): !@Sync 28
,E/SMD     (  290): DCD ON
,D/IOP_DB_BT( 2938): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:85:54
D/IOP_DB_BT( 2938): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2938): db_query_add_key: key KEY_LMP_VER, value 6:16653
D/IOP_DB_BT( 2938): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 2938): db_query_execute: result 1
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): proc btwrite assertion
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
D/IOP_DB_BT( 2938): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:85:54
,D/IOP_DB_BT( 2938): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2938): db_query_add_key: key KEY_LMP_VER, value 6:16653
D/IOP_DB_BT( 2938): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2938): db_query_execute: result 1
D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,W/bt-btif ( 2938): info:x10
D/        ( 2938): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 2938): aclStateChangeCallback: Device is NULL
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.NAME_CHANGED
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_upio ( 2938): ..proc_btwrite_timeout..
,D/bt_vendor( 2938): op for 7
,E/SMD     (  290): DCD ON
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): proc btwrite assertion
,E/bt-btm  ( 2938): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 2938): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 1183): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothManager( 7269): [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothManager( 7269): [SVoiceBT, LatencyCheck] BT onHeadsetStateChanged(): isConnected= false
,W/System.err( 7269): java.lang.NullPointerException: Attempt to invoke virtual method 'java.util.List android.bluetooth.BluetoothHeadset.getConnectedDevices()' on a null object reference
,W/System.err( 7269): 	at com.vlingo.core.internal.bluetooth.BluetoothManager.getBluetoothHeadsetConnctedDevices(BluetoothManager.java:941)
W/System.err( 7269): 	at com.vlingo.core.internal.bluetooth.BluetoothManager.onHeadsetStateChanged(BluetoothManager.java:462)
,W/System.err( 7269): 	at com.vlingo.core.internal.bluetooth.BluetoothManager$BTStateBroadcastReceiver.onReceive(BluetoothManager.java:1245)
W/System.err( 7269): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:923)
W/System.err( 7269): 	at android.os.Handler.handleCallback(Handler.java:739)
,W/System.err( 7269): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7269): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7269): 	at android.app.ActivityThread.main(ActivityThread.java:5940)
,W/System.err( 7269): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7269): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7269): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1389)
,W/System.err( 7269): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1184)
,D/KeyguardViewMediator( 1183): isGear1: device is not B1!
,D/BluetoothAdapterService( 2938): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a28d88b
,D/BtConfig.SecureMode( 2938): isSecureModeOn:false
,D/SecContentProvider(  898): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,I/BluetoothPbapService( 2938): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,D/BluetoothManager( 7269): ====[SVoiceBT, LatencyCheck] closeBtProxy===
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 1325): ACTION_ACL_DISCONNECTED
,I/BTConnectionReceiver( 1571): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 1571): Bluetooth Device Name: G3s-1
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): ..proc_btwrite_timeout..
,D/btif_config_util( 2938): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/SMD     (  290): DCD ON
,D/IOP_DB_BT( 2938): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:85:54
,D/IOP_DB_BT( 2938): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 2938): db_query_add_key: key KEY_LMP_VER, value 6:16653
,D/IOP_DB_BT( 2938): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2938): db_query_execute: result 1
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): proc btwrite assertion
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/IOP_DB_BT( 2938): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:85:54
,D/IOP_DB_BT( 2938): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2938): db_query_add_key: key KEY_LMP_VER, value 6:16653
,D/IOP_DB_BT( 2938): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 2938): db_query_execute: result 1
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
W/bt-btif ( 2938): info:x10
,D/        ( 2938): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/KeyguardViewMediator( 1183): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 1183): isGear1: device is not B1!
,D/BluetoothManager( 7269): [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.device.action.ACL_CONNECTED
,D/BluetoothManager( 7269): [SVoiceBT, LatencyCheck] BT onHeadsetStateChanged(): isConnected= true
,D/BluetoothManager( 7269): ====[SVoiceBT, LatencyCheck] openBtProxy===
,E/BluetoothHeadset( 7269): BTStateChangeCB is registed
,E/BluetoothHeadset( 7269): BluetoothHeadset service is binded
,D/BluetoothNotiBroadcastReceiver( 1325): onReceive
,I/BTConnectionReceiver( 1571): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 1571): Bluetooth Device Name: G3s-1
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.NAME_CHANGED
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,E/SMD     (  290): DCD ON
,D/bt_upio ( 2938): ..proc_btwrite_timeout..
,D/bt_vendor( 2938): op for 7
,E/SMD     (  290): DCD ON
,E/bt-btm  ( 2938): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 2938): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 1183): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothManager( 7269): [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService( 2938): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a28d88b
,D/BtConfig.SecureMode( 2938): isSecureModeOn:false
,D/SecContentProvider(  898): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,I/BluetoothPbapService( 2938): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,D/KeyguardViewMediator( 1183): isGear1: device is not B1!
,D/BluetoothManager( 7269): [SVoiceBT, LatencyCheck] BT onHeadsetStateChanged(): isConnected= false
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 1325): ACTION_ACL_DISCONNECTED
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): stay LED for fully charged
D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BluetoothManager( 7269): ====[SVoiceBT, LatencyCheck] closeBtProxy===
,D/BluetoothManager( 7269): ==[SVoiceBT, LatencyCheck] BT stopSCO()==
,D/BluetoothManager( 7269): [SVoiceBT, LatencyCheck] BT Ignoring stopSCO() bluetooth Audio off
,E/BluetoothHeadset( 7269): BTStateChangeCB is unregisted
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,I/BTConnectionReceiver( 1571): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 1571): Bluetooth Device Name: G3s-1
,D/btif_config_util( 2938): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/IOP_DB_BT( 2938): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:85:54
D/IOP_DB_BT( 2938): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2938): db_query_add_key: key KEY_LMP_VER, value 6:16653
D/IOP_DB_BT( 2938): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 2938): db_query_execute: result 1
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): proc btwrite assertion
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/IOP_DB_BT( 2938): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:85:54
,D/IOP_DB_BT( 2938): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 2938): db_query_add_key: key KEY_LMP_VER, value 6:16653
D/IOP_DB_BT( 2938): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2938): db_query_execute: result 1
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
W/bt-btif ( 2938): info:x10
D/        ( 2938): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,D/KeyguardViewMediator( 1183): Received android.bluetooth.device.action.ACL_CONNECTED
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/BluetoothManager( 7269): [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.device.action.ACL_CONNECTED
,D/BluetoothManager( 7269): [SVoiceBT, LatencyCheck] BT onHeadsetStateChanged(): isConnected= true
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/KeyguardViewMediator( 1183): isGear1: device is not B1!
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.NAME_CHANGED
,D/BluetoothManager( 7269): ====[SVoiceBT, LatencyCheck] openBtProxy===
,E/BluetoothHeadset( 7269): BTStateChangeCB is registed
,E/BluetoothHeadset( 7269): BluetoothHeadset service is binded
,D/BluetoothNotiBroadcastReceiver( 1325): onReceive
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,I/BTConnectionReceiver( 1571): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 1571): Bluetooth Device Name: G3s-1
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,E/SMD     (  290): DCD ON
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): ..proc_btwrite_timeout..
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/btif_config_util( 2938): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2938): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 2938): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 1183): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService( 2938): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a28d88b
,D/BtConfig.SecureMode( 2938): isSecureModeOn:false
,D/SecContentProvider(  898): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,D/KeyguardViewMediator( 1183): isGear1: device is not B1!
,I/BluetoothPbapService( 2938): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,D/BluetoothManager( 7269): [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothManager( 7269): [SVoiceBT, LatencyCheck] BT onHeadsetStateChanged(): isConnected= false
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.ACL_DISCONNECTED
E/BluetoothEventManager( 1325): ACTION_ACL_DISCONNECTED
,D/BluetoothManager( 7269): ====[SVoiceBT, LatencyCheck] closeBtProxy===
,D/BluetoothManager( 7269): ==[SVoiceBT, LatencyCheck] BT stopSCO()==
,D/BluetoothManager( 7269): [SVoiceBT, LatencyCheck] BT Ignoring stopSCO() bluetooth Audio off
,E/BluetoothHeadset( 7269): BTStateChangeCB is unregisted
,I/BTConnectionReceiver( 1571): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 1571): Bluetooth Device Name: G3s-1
,E/SMD     (  290): DCD ON
,E/Watchdog(  898): !@Sync 29
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/IOP_DB_BT( 2938): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:85:54
D/IOP_DB_BT( 2938): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2938): db_query_add_key: key KEY_LMP_VER, value 6:16653
D/IOP_DB_BT( 2938): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 2938): db_query_execute: result 1
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): proc btwrite assertion
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/IOP_DB_BT( 2938): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:85:54
,D/IOP_DB_BT( 2938): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 2938): db_query_add_key: key KEY_LMP_VER, value 6:16653
,D/IOP_DB_BT( 2938): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2938): db_query_execute: result 1
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,W/bt-btif ( 2938): info:x10
D/        ( 2938): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/KeyguardViewMediator( 1183): Received android.bluetooth.device.action.ACL_CONNECTED
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/KeyguardViewMediator( 1183): isGear1: device is not B1!
,D/BluetoothManager( 7269): [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.device.action.ACL_CONNECTED
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.NAME_CHANGED
D/BluetoothManager( 7269): [SVoiceBT, LatencyCheck] BT onHeadsetStateChanged(): isConnected= true
,D/BluetoothManager( 7269): ====[SVoiceBT, LatencyCheck] openBtProxy===
,E/BluetoothHeadset( 7269): BTStateChangeCB is registed
,E/BluetoothHeadset( 7269): BluetoothHeadset service is binded
,D/BluetoothNotiBroadcastReceiver( 1325): onReceive
,I/BTConnectionReceiver( 1571): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 1571): Bluetooth Device Name: G3s-1
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,E/SMD     (  290): DCD ON
,D/bt_upio ( 2938): ..proc_btwrite_timeout..
,D/bt_vendor( 2938): op for 7
,E/bt-btm  ( 2938): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 2938): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 1183): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService( 2938): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a28d88b
,D/BtConfig.SecureMode( 2938): isSecureModeOn:false
,D/SecContentProvider(  898): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,I/BluetoothPbapService( 2938): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,D/KeyguardViewMediator( 1183): isGear1: device is not B1!
,D/BluetoothManager( 7269): [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothManager( 7269): [SVoiceBT, LatencyCheck] BT onHeadsetStateChanged(): isConnected= false
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.ACL_DISCONNECTED
E/BluetoothEventManager( 1325): ACTION_ACL_DISCONNECTED
,D/BluetoothManager( 7269): ====[SVoiceBT, LatencyCheck] closeBtProxy===
,D/BluetoothManager( 7269): ==[SVoiceBT, LatencyCheck] BT stopSCO()==
,D/BluetoothManager( 7269): [SVoiceBT, LatencyCheck] BT Ignoring stopSCO() bluetooth Audio off
,E/BluetoothHeadset( 7269): BTStateChangeCB is unregisted
,I/BTConnectionReceiver( 1571): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 1571): Bluetooth Device Name: G3s-1
,E/SMD     (  290): DCD ON
,D/btif_config_util( 2938): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/IOP_DB_BT( 2938): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:85:54
,D/IOP_DB_BT( 2938): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 2938): db_query_add_key: key KEY_LMP_VER, value 6:16653
,D/IOP_DB_BT( 2938): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2938): db_query_execute: result 1
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): proc btwrite assertion
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/IOP_DB_BT( 2938): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:85:54
,D/IOP_DB_BT( 2938): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 2938): db_query_add_key: key KEY_LMP_VER, value 6:16653
,D/IOP_DB_BT( 2938): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2938): db_query_execute: result 1
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
W/bt-btif ( 2938): info:x10
,D/        ( 2938): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,D/KeyguardViewMediator( 1183): Received android.bluetooth.device.action.ACL_CONNECTED
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/BluetoothManager( 7269): [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.device.action.ACL_CONNECTED
,D/BluetoothManager( 7269): [SVoiceBT, LatencyCheck] BT onHeadsetStateChanged(): isConnected= true
,D/KeyguardViewMediator( 1183): isGear1: device is not B1!
,D/BluetoothManager( 7269): ====[SVoiceBT, LatencyCheck] openBtProxy===
,E/BluetoothHeadset( 7269): BTStateChangeCB is registed
,E/BluetoothHeadset( 7269): BluetoothHeadset service is binded
,D/BluetoothNotiBroadcastReceiver( 1325): onReceive
,I/BTConnectionReceiver( 1571): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 1571): Bluetooth Device Name: G3s-1
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.NAME_CHANGED
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,D/bt_vendor( 2938): op for 7
,D/bt_upio ( 2938): BT_WAKE is asserted already
,E/SMD     (  290): DCD ON
,D/bt_upio ( 2938): ..proc_btwrite_timeout..
,D/bt_vendor( 2938): op for 7
,E/bt-btm  ( 2938): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 2938): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 1183): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService( 2938): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a28d88b
,D/BtConfig.SecureMode( 2938): isSecureModeOn:false
,D/SecContentProvider(  898): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,I/BluetoothPbapService( 2938): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,D/KeyguardViewMediator( 1183): isGear1: device is not B1!
,D/BluetoothManager( 7269): [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.ACL_DISCONNECTED
D/BluetoothManager( 7269): [SVoiceBT, LatencyCheck] BT onHeadsetStateChanged(): isConnected= false
E/BluetoothEventManager( 1325): ACTION_ACL_DISCONNECTED
,D/BluetoothManager( 7269): ====[SVoiceBT, LatencyCheck] closeBtProxy===
,D/BluetoothManager( 7269): ==[SVoiceBT, LatencyCheck] BT stopSCO()==
,D/BluetoothManager( 7269): [SVoiceBT, LatencyCheck] BT Ignoring stopSCO() bluetooth Audio off
,E/BluetoothHeadset( 7269): BTStateChangeCB is unregisted
,I/BTConnectionReceiver( 1571): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 1571): Bluetooth Device Name: G3s-1
,E/SMD     (  290): DCD ON
,D/btif_config_util( 2938): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/SMD     (  290): DCD ON
,D/TimaService(  898): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  898): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  898): TimaServiceHandler.handleMessage what =1
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  898): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  898): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  898): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  898): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  898): !@Sync 30
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryService(  898): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,I/PowerManagerService(  898): [PWL] Off : 855s ago
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/Watchdog(  898): !@Sync 31
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryService(  898): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/Watchdog(  898): !@Sync 32
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
D/BatteryService(  898): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryService(  898): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/Watchdog(  898): !@Sync 33
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  898): !@Sync 34
,I/PowerManagerService(  898): [PWL] Off : 950s ago
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  898): !@Sync 35
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  898): !@Sync 36
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/Watchdog(  898): !@Sync 37
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryService(  898): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,I/PowerManagerService(  898): [PWL] Off : 1050s ago
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/Watchdog(  898): !@Sync 38
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/Watchdog(  898): !@Sync 39
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/TimaService(  898): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  898): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  898): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService(  898): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  898): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  898): Updating Usage Statistics in DB @ 1450362568104
,I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
,W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
,W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
,W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
,W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
,W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
,W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  898): ::getAppControlDB: Exception to create DB
W/System.err(  898): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  898): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsage(  898): Done Updating Usage Statistics in DB @ 1450362568287
,E/SMD     (  290): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  898): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  898): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  898): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  898): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  898): !@Sync 40
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryService(  898): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,I/PowerManagerService(  898): [PWL] Off : 1155s ago
,E/SMD     (  290): DCD ON
,E/Watchdog(  898): !@Sync 41
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryService(  898): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/Watchdog(  898): !@Sync 42
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/Watchdog(  898): !@Sync 43
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  898): Plugged
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryService(  898): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,E/SMD     (  290): DCD ON
D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/Watchdog(  898): !@Sync 44
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  898): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,I/PowerManagerService(  898): [PWL] Off : 1265s ago
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): stay LED for fully charged
D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/Watchdog(  898): !@Sync 45
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  898): Plugged
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryService(  898): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/Watchdog(  898): !@Sync 46
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  898): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/Watchdog(  898): !@Sync 47
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/Watchdog(  898): !@Sync 48
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  898): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,I/PowerManagerService(  898): [PWL] Off : 1380s ago
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/Watchdog(  898): !@Sync 49
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryService(  898): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryService(  898): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,D/TimaService(  898): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  898): TimaServiceHandler.handleMessage what =1
,D/TimaService(  898): TIMA: checkEvent, operation: 50000 subject: 10000
,E/SMD     (  290): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  898): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  898): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  898): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  898): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  898): !@Sync 50
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  898): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/Watchdog(  898): !@Sync 51
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  898): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/Watchdog(  898): !@Sync 52
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  898): Plugged
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryService(  898): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,I/PowerManagerService(  898): [PWL] Off : 1500s ago
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/Watchdog(  898): !@Sync 53
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/Watchdog(  898): !@Sync 54
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/Watchdog(  898): !@Sync 55
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryService(  898): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  898): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/Watchdog(  898): !@Sync 56
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,I/PowerManagerService(  898): [PWL] Off : 1625s ago
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/Watchdog(  898): !@Sync 57
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/Watchdog(  898): !@Sync 58
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryService(  898): stay LED for fully charged
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/Watchdog(  898): !@Sync 59
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/NetworkStatsFactory(  898): UpdateStatsForKnox
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/TimaService(  898): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  898): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  898): TimaServiceHandler.handleMessage what =1
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryService(  898): stay LED for fully charged
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  898): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  898): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  898): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  898): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  898): !@Sync 60
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,I/PowerManagerService(  898): [PWL] Off : 1755s ago
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  898): !@Sync 61
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  898): !@Sync 62
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  898): !@Sync 63
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  898): stay LED for fully charged
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/Watchdog(  898): !@Sync 64
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  898): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  898): Plugged
I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/BatteryService(  898): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/Watchdog(  898): !@Sync 65
,D/BatteryService(  898): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  898): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  898): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  898): stay LED for fully charged
D/BatteryService(  898): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  898): Plugged
,I/MotionRecognitionService(  898): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 2938): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2938): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  898): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 8480): 
D/AndroidRuntime( 8480): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8480): CheckJNI is OFF
D/AndroidRuntime( 8480): readGMSProperty: start
D/AndroidRuntime( 8480): readGMSProperty: already setted!!
D/AndroidRuntime( 8480): readGMSProperty: end
D/AndroidRuntime( 8480): addProductProperty: start
E/AffinityControl( 8480): AffinityControl: registerfunction enter
D/AndroidRuntime( 8480): Calling main entry com.android.commands.pm.Pm
D/PackageManager(  898): START PACKAGE DELETE: observer{679314699}
D/PackageManager(  898): pkg{<packageName>}
D/PackageManager(  898): user{0}
D/PackageManager(  898): caller{2000}
D/PackageManager(  898): flags{3}
D/PersonaManagerService(  898): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  898): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  898): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  898): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  898): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  898): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  898): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  898): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  898): getApplicationUninstallationEnabled
D/ApplicationPolicy(  898): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  898): !@killApplicatoin: 10297, uninstall pkg
I/ActivityManager(  898): Force stopping com.test.thalitest appid=10297 user=-1: uninstall pkg
I/ActivityManager(  898): Killing 7552:com.sec.android.provider.badge/u0a92 (adj 13): empty for 1809s
I/ActivityManager(  898): Killing 6106:com.android.vending/u0a33 (adj 13): empty for 1875s
W/PackageSettings(  898): Skipping PackageSetting{17d92d07 com.example.hello/10292} due to missing metadata
I/ActivityManager(  898): Killing 6934:com.android.calendar/u0a172 (adj 13): empty for 1886s
I/ActivityManager(  898): Killing 7014:com.sec.android.widgetapp.SPlannerAppWidget/u0a171 (adj 13): empty for 1887s
I/ActivityManager(  898): Killing 6954:com.android.providers.calendar/u0a51 (adj 15): empty for 1888s
I/ActivityManager(  898): Killing 6987:com.qualcomm.timeservice/1000 (adj 15): empty for 1888s
I/ActivityManager(  898): Killing 6075:com.sec.android.app.controlpanel/u0a134 (adj 15): empty for 1888s
E/lowmemorykiller(  251): Error writing /proc/6075/oom_score_adj; errno=22
I/ActivityManager(  898): Killing 6912:com.sec.esdk.elm/u0a116 (adj 15): empty for 1888s
I/ActivityManager(  898): Killing 6894:com.sec.android.app.clockpackage/u0a106 (adj 15): empty for 1888s
I/ActivityManager(  898): Killing 6878:com.samsung.android.scloud.sync/u0a76 (adj 15): empty for 1889s
I/ProcessStatsService(  898): Prepared write state in 8ms
W/libprocessgroup(  898): failed to open /acct/uid_10092/pid_7552/cgroup.procs: No such file or directory
I/ActivityManager(  898): Force stopping com.test.thalitest appid=10297 user=0: pkg removed
W/libprocessgroup(  898): failed to open /acct/uid_10033/pid_6106/cgroup.procs: No such file or directory
W/libprocessgroup(  898): failed to open /acct/uid_10172/pid_6934/cgroup.procs: No such file or directory
W/libprocessgroup(  898): failed to open /acct/uid_10171/pid_7014/cgroup.procs: No such file or directory
W/libprocessgroup(  898): failed to open /acct/uid_10051/pid_6954/cgroup.procs: No such file or directory
W/libprocessgroup(  898): failed to open /acct/uid_1000/pid_6987/cgroup.procs: No such file or directory
W/libprocessgroup(  898): failed to open /acct/uid_10134/pid_6075/cgroup.procs: No such file or directory
W/libprocessgroup(  898): failed to open /acct/uid_10116/pid_6912/cgroup.procs: No such file or directory
W/libprocessgroup(  898): failed to open /acct/uid_10106/pid_6894/cgroup.procs: No such file or directory
W/libprocessgroup(  898): failed to open /acct/uid_10076/pid_6878/cgroup.procs: No such file or directory
D/ResourcesManager(  898): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
I/InputReader(  898): Reconfiguring input devices.  changes=0x00000010
E/SamsungIME( 1733): mOCRHelper is null
W/GeofencerStateMachine( 1949): Ignoring removeGeofence because network location is disabled.
I/art     ( 4250): Explicit concurrent mark sweep GC freed 33711(1888KB) AllocSpace objects, 9(144KB) LOS objects, 40% free, 15MB/26MB, paused 391us total 71.148ms
I/KLMS-2.4.511: ( 6846): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.4.511: ( 6846): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1450363324881
I/KLMS-2.4.511: ( 6846): MainReciver(): PACKAGE_REMOVED
I/KLMS-2.4.511: ( 6846): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
D/ResourcesManager( 1441): creating new AssetManager and set to /system/priv-app/StoryAlbumWidget/StoryAlbumWidget.apk
W/ResourcesManager( 1441): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1441): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
D/ResourcesManager( 1441): creating new AssetManager and set to /system/app/AccuweatherPhone2013_H_LMR/AccuweatherPhone2013_H_LMR.apk
W/ResourcesManager( 1441): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1441): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1441): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
D/ResourcesManager( 1441): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
W/ResourcesManager( 1441): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1441): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
I/art     ( 1571): Explicit concurrent mark sweep GC freed 56847(3MB) AllocSpace objects, 6(96KB) LOS objects, 24% free, 19MB/25MB, paused 625us total 193.776ms
I/art     ( 6753): Explicit concurrent mark sweep GC freed 13147(703KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 16MB/21MB, paused 355us total 192.377ms
I/art     ( 2297): Explicit concurrent mark sweep GC freed 3673(143KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 22MB/30MB, paused 990us total 192.294ms
I/art     (  898): Explicit concurrent mark sweep GC freed 42966(4MB) AllocSpace objects, 175(2MB) LOS objects, 17% free, 37MB/45MB, paused 1.713ms total 178.025ms
I/art     (  898): WaitForGcToComplete blocked for 50.196ms for cause Explicit
D/ResourcesManager(  898): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/RegisteredServicesCache( 1409): empty dynamic service
D/SecContentProvider2(  898): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  898): mCursor = null
D/ResourcesManager(  898): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ResourcesManager(  898): creating new AssetManager and set to /system/app/Videos/Videos.apk
E/Zygote  ( 8510): MountEmulatedStorage()
E/Zygote  ( 8510): v2
I/libpersona( 8510): KNOX_SDCARD checking this for 10116
I/libpersona( 8510): KNOX_SDCARD not a persona
D/RCPManagerService(  898): PackageReceiver onReceive()
I/ActivityManager(  898): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8510 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
I/HarmonyEASService(  898): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy(  898): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  898): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  898): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  898): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  898): uID is 10297
V/EnterpriseBillingPolicy(  898): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  898): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  898): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  898): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  898): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  898): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  898): getBillingProfileForVpnEngine - end - null
D/TaskPersister(  898): removeObsoleteFile: deleting file=4_task.xml
I/SELinux ( 8510): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 8510): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 8510): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/art     (  898): Explicit concurrent mark sweep GC freed 8085(429KB) AllocSpace objects, 1(16KB) LOS objects, 17% free, 37MB/45MB, paused 1.714ms total 215.172ms
D/TimaKeyStoreProvider( 8510): TimaSignature is unavailable
D/ActivityThread( 8510): Added TimaKeyStore provider
D/ResourcesManager( 8510): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/elm:14491( 8510): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14491( 8510): ELMEngine.ELMEngine( context ).
D/elm:14491( 8510): MDMBridge.setEnterpriseBridge()
D/elm:14491( 8510): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
D/elm:14491( 8510): ElmAgentService : onCreate()
D/elm:14491( 8510): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14491( 8510): MainReceiver.listeningToPackageRemoved()
D/elm:14491( 8510): MDMBridge.getInstance()
D/elm:14491( 8510): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14491( 8510): MDMBridge.getAllLicenseInfoFromSDK()
E/Zygote  ( 8528): MountEmulatedStorage()
E/Zygote  ( 8528): v2
I/libpersona( 8528): KNOX_SDCARD checking this for 10021
I/libpersona( 8528): KNOX_SDCARD not a persona
I/ActivityManager(  898): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8528 uid=10021 gids={50021, 9997} abi=armeabi-v7a
I/SELinux ( 8528): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/elm:14491( 8510): ElmAgentService : onDestroy().
I/SELinux ( 8528): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 8528): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/PackageManager(  898): delete codoeFile: 
I/AASAUninstall(  898):  com.test.thalitest not target!
D/PackageManager(  898): result of delete: 1{679314699}
E/SMD     (  290): DCD ON
D/AndroidRuntime( 8480): Shutting down VM
D/TimaKeyStoreProvider( 8528): TimaSignature is unavailable
D/ActivityThread( 8528): Added TimaKeyStore provider
D/ResourcesManager( 8528): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8528): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 8528): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8528): onReceive() : package name is not s health. Return !!!
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 8543): MountEmulatedStorage()
I/libpersona( 8543): KNOX_SDCARD checking this for 10025
E/Zygote  ( 8543): v2
I/libpersona( 8543): KNOX_SDCARD not a persona
I/ActivityManager(  898): Start proc sstream.app for broadcast sstream.app/.receiver.ApplicationCompatibleReceiver: pid=8543 uid=10025 gids={50025, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/SELinux ( 8543): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 8543): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 8543): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 8543): TimaSignature is unavailable
D/ActivityThread( 8543): Added TimaKeyStore provider
I/art     (  320): Explicit concurrent mark sweep GC freed 8708(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 344us total 13.236ms
D/ResourcesManager( 8543): creating new AssetManager and set to /system/priv-app/MagazineHome/MagazineHome.apk
I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 282us total 10.358ms
W/ResourcesManager( 8543): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 272us total 9.837ms
W/linker  ( 8543): libdmcAlwaysFD.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
D/MVFD_interface( 8543): <<<  caMVFace_FaceInit
E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/sstream.app/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8543): Failed to ensure directory: /storage/extSdCard/Android/data/sstream.app/cache
E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/sstream.app/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8543): Failed to ensure directory: /storage/extSdCard/Android/data/sstream.app/cache
D/HockeyApp( 8543): Current handler class = sstream.app.util.Log$1
E/SQLiteLog( 8543): (28) failed to open "/data/data/sstream.app/databases/sstream.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 8543): Failed to open database '/data/data/sstream.app/databases/sstream.db'.
E/SQLiteDatabase( 8543): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8543): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8543): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 8543): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 8543): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8543): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8543): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8543): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 8543): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 8543): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 8543): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 8543): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 8543): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 8543): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 8543): 	at sstream.app.provider.StoryProvider.delete(StoryProvider.java:90)
E/SQLiteDatabase( 8543): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:314)
E/SQLiteDatabase( 8543): 	at android.content.ContentResolver.delete(ContentResolver.java:1309)
E/SQLiteDatabase( 8543): 	at sstream.app.provider.DatabaseUtil.deleteConfigSettingForApp(DatabaseUtil.java:985)
E/SQLiteDatabase( 8543): 	at sstream.app.receiver.ApplicationCompatibleReceiver.onReceive(ApplicationCompatibleReceiver.java:216)
E/SQLiteDatabase( 8543): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2991)
E/SQLiteDatabase( 8543): 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
E/SQLiteDatabase( 8543): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
E/SQLiteDatabase( 8543): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8543): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 8543): 	at android.app.ActivityThread.main(ActivityThread.java:5940)
E/SQLiteDatabase( 8543): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 8543): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 8543): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1389)
E/SQLiteDatabase( 8543): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1184)
D/ResourcesManager( 8543): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/AndroidRuntime( 8543): Shutting down VM
I/PCWCLIENTTRACE_PushUtil( 6465): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6465): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6465): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6465): [onReceive] - android.intent.action.PACKAGE_REMOVED
W/ResourcesManager( 8543): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  898): checkUser: useridlist=null, currentuser=0
E/SQLiteLog( 8543): (28) failed to open "/data/data/sstream.app/databases/sstream.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 8543): Failed to open database '/data/data/sstream.app/databases/sstream.db'.
E/SQLiteDatabase( 8543): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8543): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8543): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 8543): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 8543): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8543): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8543): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8543): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 8543): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 8543): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 8543): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 8543): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 8543): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 8543): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 8543): 	at sstream.app.provider.StoryProvider.query(StoryProvider.java:386)
E/SQLiteDatabase( 8543): 	at android.content.ContentProvider.query(ContentProvider.java:980)
E/SQLiteDatabase( 8543): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/SQLiteDatabase( 8543): 	at android.content.ContentResolver.query(ContentResolver.java:484)
E/SQLiteDatabase( 8543): 	at android.content.ContentResolver.query(ContentResolver.java:428)
E/SQLiteDatabase( 8543): 	at sstream.app.provider.DatabaseUtil.queryConfigSetting(DatabaseUtil.java:685)
E/SQLiteDatabase( 8543): 	at sstream.app.receiver.ApplicationCompatibleReceiver.addCompatibleAppsToDB(ApplicationCompatibleReceiver.java:418)
E/SQLiteDatabase( 8543): 	at sstream.app.receiver.ApplicationCompatibleReceiver.getCompatibleApps(ApplicationCompatibleReceiver.java:155)
E/SQLiteDatabase( 8543): 	at sstream.app.StreamManager$1.run(StreamManager.java:177)
D/HockeyApp( 8543): Writing unhandled exception to: /data/data/sstream.app/files/00f1da59-9e9a-4448-b751-0c0fd0a46d45.stacktrace
D/HockeyApp( 8543): Writing unhandled exception to: /data/data/sstream.app/files/0c5ee0ab-fa41-49b4-a6f3-b2b3ce7bc525.stacktrace
E/HockeyApp( 8543): Error saving exception stacktrace!
E/HockeyApp( 8543): 
E/HockeyApp( 8543): java.io.FileNotFoundException: /data/data/sstream.app/files/00f1da59-9e9a-4448-b751-0c0fd0a46d45.stacktrace: open failed: EROFS (Read-only file system)
E/HockeyApp( 8543): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/HockeyApp( 8543): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/HockeyApp( 8543): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/HockeyApp( 8543): 	at java.io.FileWriter.<init>(FileWriter.java:80)
E/HockeyApp( 8543): 	at net.hockeyapp.android.internal.ExceptionHandler.saveException(ExceptionHandler.java:83)
E/HockeyApp( 8543): 	at net.hockeyapp.android.internal.ExceptionHandler.uncaughtException(ExceptionHandler.java:108)
E/HockeyApp( 8543): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
E/HockeyApp( 8543): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
E/HockeyApp( 8543): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/HockeyApp( 8543): 	at libcore.io.Posix.open(Native Method)
E/HockeyApp( 8543): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/HockeyApp( 8543): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/HockeyApp( 8543): 	... 7 more
E/HockeyApp( 8543): Error saving exception stacktrace!
E/HockeyApp( 8543): 
E/HockeyApp( 8543): java.io.FileNotFoundException: /data/data/sstream.app/files/0c5ee0ab-fa41-49b4-a6f3-b2b3ce7bc525.stacktrace: open failed: EROFS (Read-only file system)
E/HockeyApp( 8543): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/HockeyApp( 8543): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/HockeyApp( 8543): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/HockeyApp( 8543): 	at java.io.FileWriter.<init>(FileWriter.java:80)
E/HockeyApp( 8543): 	at net.hockeyapp.android.internal.ExceptionHandler.saveException(ExceptionHandler.java:83)
E/HockeyApp( 8543): 	at net.hockeyapp.android.internal.ExceptionHandler.uncaughtException(ExceptionHandler.java:108)
E/HockeyApp( 8543): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
E/HockeyApp( 8543): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
E/HockeyApp( 8543): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/HockeyApp( 8543): 	at libcore.io.Posix.open(Native Method)
E/HockeyApp( 8543): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/HockeyApp( 8543): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/HockeyApp( 8543): 	... 7 more
E/Zygote  ( 8579): MountEmulatedStorage()
E/Zygote  ( 8579): v2
I/libpersona( 8579): KNOX_SDCARD checking this for 10039
I/libpersona( 8579): KNOX_SDCARD not a persona
I/EventHub(  898): Removing device '/dev/input/event6' due to inotify event
I/ActivityManager(  898): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=8579 uid=10039 gids={50039, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/SELinux ( 8579): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0_0002
E/SELinux ( 8579): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 8579): TimaSignature is unavailable
D/ActivityThread( 8579): Added TimaKeyStore provider
I/EventHub(  898): Removing device '/dev/input/event7' due to inotify event
D/ResourcesManager( 8579): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
W/ContextImpl( 8579): Unable to create files subdir /data/data/com.samsung.android.app.galaxyfinder/cache
E/ActivityThread( 8579): Unable to setupGraphicsSupport due to missing cache directory
I/FeatureConfig( 8579): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
D/ResourcesManager( 8579): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
W/ResourcesManager( 8579): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8579): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/ResourcesManager( 8579): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
W/ResourcesManager( 8579): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 8579): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8579): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8579): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8579): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 8579): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/ResourcesManager( 8579): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
W/ResourcesManager( 8579): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 8579): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8579): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8579): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8579): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8579): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/EventHub(  898): Removing device '/dev/input/event8' due to inotify event
D/ResourcesManager( 8579): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/ResourcesManager( 8579): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/ResourcesManager( 8579): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
D/ResourcesManager( 8579): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
W/ResourcesManager( 8579): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8579): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8579): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ResourcesManager( 8579): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
W/ResourcesManager( 8579): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8579): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8579): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/ResourcesManager( 8579): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
W/ResourcesManager( 8579): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8579): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8579): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8579): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8579): Asset path '/system/framework/svi.jar' does not exist or contains no resources.
W/ResourcesManager( 8579): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 8579): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/ResourcesManager( 8579): creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
W/ResourcesManager( 8579): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8579): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
W/ResourcesManager( 8579): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 8579): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/ResourcesManager( 8579): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
W/ResourcesManager( 8579): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 8579): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8579): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8579): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8579): Asset path '/system/framework/videowall.jar' does not exist or contains no resources.
W/ResourcesManager( 8579): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
I/EventHub(  898): Removing device '/dev/input/event9' due to inotify event
D/ResourcesManager( 8579): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
W/ResourcesManager( 8579): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 8579): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8579): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/ResourcesManager( 8579): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
W/ResourcesManager( 8579): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/ResourcesManager( 8579): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
W/ResourcesManager( 8579): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 8579): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8579): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8579): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8579): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/ResourcesManager( 8579): creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
W/ResourcesManager( 8579): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 8579): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8579): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/ResourcesManager( 8579): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager( 8579): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
W/ResourcesManager( 8579): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
D/ResourcesManager( 8579): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk

```
