#### Test 50650278d6c551a_thali05_samsung-SM-N9005 Logs


```
--------- beginning of system
W/ContextImpl(  731): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,--------- beginning of main
E/SMD     (  288): DCD ON
D/AndroidRuntime( 7164): 
D/AndroidRuntime( 7164): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7164): CheckJNI is OFF
D/AndroidRuntime( 7164): readGMSProperty: start
D/AndroidRuntime( 7164): readGMSProperty: already setted!!
D/AndroidRuntime( 7164): readGMSProperty: end
D/AndroidRuntime( 7164): addProductProperty: start
E/AffinityControl( 7164): AffinityControl: registerfunction enter
D/AndroidRuntime( 7164): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  731): inState():  stateMachine is null !!
I/PersonaManagerService(  731): PersonaId don't exist
I/ActivityManager(  731): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  731): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  731): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  731): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager(  731): mDVFSHelper.acquire()
E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7180): MountEmulatedStorage()
E/Zygote  ( 7180): v2
I/libpersona( 7180): KNOX_SDCARD checking this for 10280
I/libpersona( 7180): KNOX_SDCARD not a persona
I/ActivityManager(  731): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7180 uid=10280 gids={50280, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7164): Shutting down VM
D/PointerIcon(  731): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  731): setMouseCustomIcon IconType is same.101
D/PointerIcon(  731): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  731): setHoveringSpenCustomIcon IconType is same.1
I/SELinux ( 7180): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7180): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7180): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7180): TimaSignature is unavailable
D/ActivityThread( 7180): Added TimaKeyStore provider
D/ConnectivityService(  731): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SurfaceFlinger(  254): id=11 Removed YUIInstallC (5/8)
I/SurfaceFlinger(  254): id=11 Removed YUIInstallC (-2/8)
D/ResourcesManager( 7180): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
V/ActivityThread( 3439): updateVisibility : ActivityRecord{1a9bdcd0 token=android.os.BinderProxy@26eab9b1 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
,I/WebViewFactory( 7180): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
D/ResourcesManager( 7180): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader( 7180): Loading: webviewchromium
I/LibraryLoader( 7180): Time to load native libraries: 5 ms (timestamps 3189-3194)
I/LibraryLoader( 7180): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7180): Binding Chromium to main looper Looper (main, tid 1) {3a0a9e9f}
I/LibraryLoader( 7180): Expected native library version number "",actual native library version number ""
I/chromium( 7180): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7180): Initializing chromium process, renderers=0
W/art     ( 7180): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7180): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7180): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46780 len=2953
I/chromium( 7180): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229536 len:643667
I/Adreno-EGL( 7180): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 7180): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7180): Build Date: 11/19/14 Wed
I/Adreno-EGL( 7180): Local Branch: mybranch5813579
I/Adreno-EGL( 7180): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 7180): Local Patches: NONE
I/Adreno-EGL( 7180): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
W/ActivityManager(  731): Activity pause timeout for ActivityRecord{3427c0ca u0 com.test.thalitest/.MainActivity t4}
W/chromium( 7180): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7180): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7180): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7180): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7180): CordovaWebView is running on device made by: samsung
W/art     ( 7180): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7180): Attempt to remove local handle scope entry from IRT, ignoring
D/Activity( 7180): performCreate Call secproduct feature valuefalse
D/Activity( 7180): performCreate Call debug elastic valuetrue
D/OpenGLRenderer( 7180): Render dirty regions requested: true
D/Atlas   ( 7180): Validating map...
D/ActivityManager(  731): post active user change for 0
D/KnoxTimeoutHandler(  731): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  731): handleActiveUserChange for user 0
V/ActivityThread( 7180): updateVisibility : ActivityRecord{1430681c token=android.os.BinderProxy@11a224ee {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
I/SurfaceFlinger(  254): id=15 createSurf (1x1),1 flag=404, NainActivit
D/StatusBarManagerService(  731): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  731): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon(  731): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  731): setMouseCustomIcon IconType is same.101
D/PointerIcon(  731): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  731): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer( 7180): Initialized EGL, version 1.4
I/OpenGLRenderer( 7180): HWUI protection enabled for context ,  &this =0xa1653060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 7180): Enabling debug mode 0
D/InputMethodManagerService(  731): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl(  731): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ContextImpl(  731): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ActivityManager(  731): mDVFSHelper.release()
I/Timeline(  731): Timeline: Activity_windows_visible id: ActivityRecord{3427c0ca u0 com.test.thalitest/.MainActivity t4} time:153854
W/IInputConnectionWrapper( 7180): showStatusIcon on inactive InputConnection
I/Timeline( 7180): Timeline: Activity_idle id: android.os.BinderProxy@11a224ee time:153861
I/chromium( 7180): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7180): 
D/JsMessageQueue( 7180): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 7180): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1358284288
D/JX-Cordova( 7180): jxcore cordova android initializing
,E/SMD     (  288): DCD ON
,W/jxcore-log( 7180): Initializing JXcore engine
W/jxcore-log( 7180): JXcore engine is ready
,W/jxcore-log( 7180): Starting JXcore engine
,E/auditd  ( 1852): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  731): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  731): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  731): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,D/SecurityLogAgent( 6862):  SeDenialReceiver : Intent Received : android.intent.action.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 6862):  SeDenialReceiver : File path = null
,W/jxcore-log( 7180): Platform android
W/jxcore-log( 7180): 
,W/jxcore-log( 7180): Process ARCH arm
W/jxcore-log( 7180): 
,I/jxcore-log( 7180): JXcore Cordova bridge is ready!
I/jxcore-log( 7180): 
,W/jxcore-log( 7180): JXcore engine is started
,I/jxcore-log( 7180): Toggling radios to true
I/jxcore-log( 7180): 
,D/BluetoothAdapter( 7180): enable()
,D/BluetoothAdapter( 7180): enable(): BT is already enabled..!
,I/WifiManager( 7180): packageName : com.test.thalitest
,D/SecContentProvider(  731): uri = 18 selection = isWifiEnabled
D/SecContentProvider2(  731): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  731): mCursor = null
,D/WifiService(  731): setWifiEnabled: true pid=7180, uid=10280
W/ActivityManager(  731): Permission Denial: getCurrentUser() from pid=7180, uid=10280 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  731): Failed getting userId using ActivityManagerNative
W/WifiService(  731): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7180, uid=10280 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  731): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23057)
W/WifiService(  731): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2181)
W/WifiService(  731): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2169)
W/WifiService(  731): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  731): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider(  731): name = wifi_on
,I/WifiService(  731): disconnect: pid=7180, uid=10280
,I/wpa_supplicant( 1271): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 7180): Radios toggled
I/jxcore-log( 7180): 
,I/wpa_supplicant( 1271): CTRL-EVENT-DISCONNECTED bssid=C0.AA.4A reason=3 locally_generated=1
,I/wpa_supplicant( 1271): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1271): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.4A SSID=4E473730303567
,I/wpa_supplicant( 1271): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  731): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 1271): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1271): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1271): Disconnected - do not scan
I/wpa_supplicant( 1271): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiConfigStore(  731): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
I/jxcore-log( 7180): Got Device Bluetooth address: E0:DB:10:1F:C9:5E
I/jxcore-log( 7180): 
,I/jxcore-log( 7180): Perf Test app loaded loaded
I/jxcore-log( 7180): 
,I/Choreographer( 7180): Skipped 62 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 7180): check test folder
I/jxcore-log( 7180): 
,I/jxcore-log( 7180): found test : ./testFindPeers.js
I/jxcore-log( 7180): 
,E/native  (  731): do suspend true
,D/WifiP2pService(  731): InactiveState{ what=143375 }
,D/WifiP2pService(  731): P2pEnabledState{ what=143375 }
,D/CommandListener(  282): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
,V/NativeCrypto( 1882): Read error: ssl=0x9b7eae00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1882): SSL shutdown failed: ssl=0x9b7eae00: I/O error during system call, Broken pipe
,E/WifiConfigStore(  731): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/ConnectivityService(  731): updateNetworkInfo()
,I/WifiTrafficPoller(  731): evaluateTrafficStatsPolling
,E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
D/ConnectivityService(  731): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,E/ConnectivityService(  731): updateNetworkInfo()
D/ConnectivityService(  731): ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
D/ConnectivityService(  731): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,D/NetUtils(  731): android_net_utils_resetConnections in env=0xa939d320 clazz=0x99b1c98c iface=wlan0 mask=0x3
,D/ConnectivityService(  731): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,D/ConnectivityService(  731): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10015
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  731): ValidatedState{ when=0 what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  731): DefaultState{ when=-1ms what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  731): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  731): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  731): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,D/ConnectivityService(  731): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out(  731): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid (  731): Tagging socket 387 with tag ffffffff00000000{4294967295,0} uid 10015, pid: 731, getuid(): 1000
,D/ConnectivityService(  731): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  731): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/WifiStateMachine(  731): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1271): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1271): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1271): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1271): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1271): First Scan Start
,I/System.out(  731): (HTTPLog)-Static: isSBSettingEnabled false
,E/native  (  731): do suspend true
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  731): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  731): Validated
,E/Zygote  ( 7250): MountEmulatedStorage()
,I/ActivityManager(  731): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.samsung.myplace.WIFINotificationHandler: pid=7250 uid=10038 gids={50038, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,E/Zygote  ( 7250): v2
,I/libpersona( 7250): KNOX_SDCARD checking this for 10038
I/libpersona( 7250): KNOX_SDCARD not a persona
,I/wpa_supplicant( 1271): Scan requested (ret=0) - scan timeout 30 seconds
,I/jxcore-log( 7180): found test : ./testSendData.js
I/jxcore-log( 7180): 
,I/SELinux ( 7250): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7250): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,D/WifiP2pService(  731): InactiveState{ what=143375 }
,D/WifiP2pService(  731): P2pEnabledState{ what=143375 }
,D/CommandListener(  282): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
E/SELinux ( 7250): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:null
,I/WifiTrafficPoller(  731): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiNetworkAgent(  731): NetworkAgent: NetworkAgent channel lost
,D/SecContentProvider2(  731): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  731): mCursor = null
,D/SecContentProvider2(  731): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  731): mCursor = null
,D/TimaKeyStoreProvider( 7250): TimaSignature is unavailable
,D/ActivityThread( 7250): Added TimaKeyStore provider
,D/ResourcesManager( 7250): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,W/ResourcesManager( 7250): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ConnectivityService(  731): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  731): calling update connectivity
D/ConnectivityService(  731):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  731):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  731): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  731): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  731): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  731):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  731): Disconnected - quitting
D/ConnectivityService(  731): sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/Nat464Xlat(  731): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  731): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  731): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CSLegacyTypeTracker(  731): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  731): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService(  731): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory( 1420): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/EntConnectivity(  731): Not allowed due to - mEnabled false
D/SmartBondingService(  731): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1181): CM callback handler got msg 524292
V/NetworkStats(  731): updateIfacesLocked()
D/NtpTrustedTime(  731): currentTimeMillis() cache hit
V/NetworkStats(  731): performPollLocked(flags=0x1)
,D/Tethering(  731): MasterInitialState.processMessage what=3
D/SmartBondingService(  731): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  731): getSBEnabled() enabled =false
D/SmartBondingService(  731): getSBEnabled() enabled =false
D/SmartBondingService(  731): getSBEnabled() enabled =false
D/NetworkStatsFactory(  731): UpdateStatsForKnox
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  731): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  731): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1181): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1181): updateDataNetType()
D/StatusBar.NetworkController( 1181): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1181): updateLTEICONDataNetType:0
,E/ConnectivityService(  731): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
V/NetworkStats(  731): performPollLocked() took 5ms
D/NtpTrustedTime(  731): currentTimeMillis() cache hit
,D/NtpTrustedTime(  731): currentTimeMillis() cache hit
,D/NtpTrustedTime(  731): currentTimeMillis() cache hit
D/NtpTrustedTime(  731): currentTimeMillis() cache hit
D/NtpTrustedTime(  731): currentTimeMillis() cache hit
D/NtpTrustedTime(  731): currentTimeMillis() cache hit
V/NetworkStats(  731): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime(  731): currentTimeMillis() cache hit
,D/SmartBondingService(  731): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityManager.CallbackHandler( 2237): CM callback handler got msg 524292
,D/StatusBar.NetworkController( 1181): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,I/chromium( 7180): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/chromium( 7180): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
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
,I/VlingoApplication( 7250): VlingoApplication appVersion ='11.2.2.0.37649', ro.csc.sales_code=XEO
,E/BluetoothHeadset( 7250): BTStateChangeCB is registed
,E/BluetoothHeadset( 7250): BluetoothHeadset service is binded
,I/ActivityManager(  731): Killing 4919:com.sec.spp.push/u0a43 (adj 15): bgCount ##41
,I/Hs20UtilService( 1321): Starting #6
,I/Hs20UtilService( 1321): Message received 5007
,D/NearbySettings( 1321): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1321): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1321): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  731): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1321): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1321): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1321): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1321): MountReceiver.mPrefHandler - 7002
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6667): NETWORK_STATE_CHANGED_ACTION
,D/SettingsProvider(  731): name = driving_mode_on
D/SettingsProvider(  731): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  731): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  731): selectionArgs: false
D/SettingsProvider(  731): selectionArgs: 10038
D/SecContentProvider(  731): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  731): ret = -1
,D/BluetoothManager( 7250): [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.media.ACTION_SCO_AUDIO_STATE_UPDATED
,I/Hs20UtilService( 1321): Starting #7
,I/Hs20UtilService( 1321): Message received 5007
D/NearbySettings( 1321): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1321): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1321): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  731): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1321): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1321): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1321): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1321): MountReceiver.mPrefHandler - 7002
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6667): NETWORK_STATE_CHANGED_ACTION
,E/SMD     (  288): DCD ON
,D/ConnectivityService(  731): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  731): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  731): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  731): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  731): getSBEnabled() enabled =false
I/ApplicationPolicy(  731): updateDataUsageMap
D/SmartBondingService(  731): getSBEnabled() enabled =false
D/SmartBondingService(  731): getSBEnabled() enabled =false
,D/SmartBondingService(  731): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5714): type=WIFI subType= reason=null isConnected=false
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/DBG_DM  ( 3439): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3439): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/Zygote  ( 7302): MountEmulatedStorage()
,E/Zygote  ( 7302): v2
I/libpersona( 7302): KNOX_SDCARD checking this for 1000
I/libpersona( 7302): KNOX_SDCARD not a persona
,I/PowerManagerService(  731): [PWL] Off : 50s ago
I/PowerManagerService(  731): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  731): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  731): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=731, ws=null) (elapsedTime=587)
,I/ActivityManager(  731): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7302 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 7302): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7302): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7302): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7302): TimaSignature is unavailable
,D/ActivityThread( 7302): Added TimaKeyStore provider
,D/ResourcesManager( 7302): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/PCWCLIENTTRACE_LOG( 7302): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 7302): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 7302): new DMDBOpenHelper instance
,D/SSRM:n  (  731): SIOP:: AP = 350, PST = 348, CUR = 450
,I/PCWCLIENTTRACE_PushUtil( 7302): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 7302): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7302): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7302): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7302): noConnectivity : true
,D/BatteryService(  731): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  731): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  731): stay LED for fully charged
D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
I/ActivityManager(  731): Killing 6462:com.samsung.android.sdk.samsunglink/u0a48 (adj 15): bgCount ##41
,E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7319): MountEmulatedStorage()
E/Zygote  ( 7319): v2
I/libpersona( 7319): KNOX_SDCARD checking this for 10004
I/libpersona( 7319): KNOX_SDCARD not a persona
,I/ActivityManager(  731): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7319 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MotionRecognitionService(  731): Plugged
,I/MotionRecognitionService(  731): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,I/SELinux ( 7319): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2912): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2912): Disconnected process message: 10
,I/SELinux ( 7319): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7319): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7319): TimaSignature is unavailable
,D/ActivityThread( 7319): Added TimaKeyStore provider
,D/ResourcesManager( 7319): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager(  731): Killing 6533:com.sec.android.provider.badge/u0a92 (adj 15): bgCount ##41
,E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7336): MountEmulatedStorage()
,E/Zygote  ( 7336): v2
,I/libpersona( 7336): KNOX_SDCARD checking this for 1000
,I/libpersona( 7336): KNOX_SDCARD not a persona
,I/ActivityManager(  731): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7336 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7336): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7336): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7336): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  316): Explicit concurrent mark sweep GC freed 8755(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 741us total 25.885ms
,I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 394us total 13.926ms
,I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 394us total 14.141ms
,D/TimaKeyStoreProvider( 7336): TimaSignature is unavailable
,D/ActivityThread( 7336): Added TimaKeyStore provider
,D/ResourcesManager( 7336): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT( 7336): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7336): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/wpa_supplicant( 1271): nl80211: Received scan results (8 BSSes)
,I/wpa_supplicant( 1271): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 1271): Trying to associate with C0.AA.4A (SSID='4E473730303567' freq=5220 MHz)
I/wpa_supplicant( 1271): wlan0: State: SCANNING -> ASSOCIATING
,I/wpa_supplicant( 1271): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E473730303567
,D/SecContentProvider2(  731): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  731): mCursor = null
,I/wpa_supplicant( 1271): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1271): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E473730303567
,I/wpa_supplicant( 1271): Associated with C0.AA.4A
,D/SecContentProvider2(  731): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  731): mCursor = null
,I/DIAGMON_AGENT( 7336): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/wpa_supplicant( 1271): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1271): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.4A SSID=4E473730303567
,D/SecContentProvider2(  731): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  731): mCursor = null
I/wpa_supplicant( 1271): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1271): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,I/wpa_supplicant( 1271): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.4A SSID=4E473730303567
,I/wpa_supplicant( 1271): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1271): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1271): CTRL-EVENT-CONNECTED - Connection to C0.AA.4A completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1271): Blacklist: Clear (temp) 
I/wpa_supplicant( 1271): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.4A SSID=4E473730303567
D/WifiNative-HAL(  731): callSECApiVoid - ID [50]
D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:null
D/ConnectivityService(  731): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  731): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  731): hsengiv:checkWhatTypeOfNetwork and the value is false
D/ConnectivityService(  731): Got NetworkAgent Messenger
E/ConnectivityService(  731): updateNetworkInfo()
D/ConnectivityService(  731): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  731): NetworkAgent connected
I/DIAGMON_AGENT( 7336): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
I/DIAGMON_AGENT( 7336): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT( 7336): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
E/WifiConfigStore(  731): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/CommandListener(  282): Setting iface cfg
E/WifiStateMachine(  731): Start Dhcp Watchdog 2
D/SecContentProvider2(  731): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  731): mCursor = null
,D/ConnectivityService(  731): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,I/FOTA_Client( 6737): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,E/native  (  731): do suspend false
,D/SecContentProvider2(  731): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  731): mCursor = null
D/WifiP2pService(  731): InactiveState{ what=143375 }
D/WifiP2pService(  731): P2pEnabledState{ what=143375 }
,I/FOTA_Client( 6737): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 6737): [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.511: ( 6753): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.511: ( 6753): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449754851775
I/KLMS-2.4.511: ( 6753): MainReciver(): NETWORK_STATE_CHANGED_ACTION
D/ConnectivityService(  731): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  731): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/KLMS-2.4.511: ( 6753): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
I/KLMS-2.4.511: ( 6753): StateImplV2(): networkChangeListener().END
,E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/Zygote  ( 7354): MountEmulatedStorage()
I/libpersona( 7354): KNOX_SDCARD checking this for 10036
E/Zygote  ( 7354): v2
I/libpersona( 7354): KNOX_SDCARD not a persona
,I/SELinux ( 7354): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7354): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7354): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  731): Start proc com.samsung.android.app.pinboard:tagService for broadcast com.samsung.android.app.pinboard/.service.TagReadyReceiver: pid=7354 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  731): Killing 6548:com.sec.android.app.soundalive/u0a64 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7354): TimaSignature is unavailable
,D/ActivityThread( 7354): Added TimaKeyStore provider
,D/ResourcesManager( 7354): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,W/ResourcesManager( 7354): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7354): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/dhcpcd  ( 7369): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 7369): version 5.5.6 starting
,E/dhcpcd  ( 7369): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,E/Minikin ( 7354): addFont failed to create font /system/fonts/SamsungSans-light.ttf
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  731): Killing 5542:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
,I/SO_AGENT( 6768): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
,I/dhcpcd  ( 7369): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7369): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7369): if(wlan0) info get Success. (MAC : C0.AA.4A)
I/dhcpcd  ( 7369): bssid match
I/dhcpcd  ( 7369): wlan0: rebinding lease of 192.168.1.128
,E/Zygote  ( 7376): MountEmulatedStorage()
,E/Zygote  ( 7376): v2
I/libpersona( 7376): KNOX_SDCARD checking this for 1000
I/libpersona( 7376): KNOX_SDCARD not a persona
,I/ActivityManager(  731): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=7376 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7376): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7376): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7376): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7376): TimaSignature is unavailable
,D/ActivityThread( 7376): Added TimaKeyStore provider
,D/ResourcesManager( 7376): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7396): MountEmulatedStorage()
,E/Zygote  ( 7396): v2
I/libpersona( 7396): KNOX_SDCARD checking this for 10043
,I/libpersona( 7396): KNOX_SDCARD not a persona
,I/ActivityManager(  731): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7396 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  731): Killing 6576:com.wsomacp/u0a29 (adj 15): bgCount ##41
,I/SELinux ( 7396): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7396): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7396): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7396): TimaSignature is unavailable
D/ActivityThread( 7396): Added TimaKeyStore provider
D/ConnectivityService(  731): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  731): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager( 7396): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
E/SPPClientService( 7396): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 7396): [PushClientApplication] Push log off : This is Ship build version
D/SPPClientService( 7396): PushLog.txt file is not deleted.
D/SPPClientService( 7396): PushLog.txt file is not deleted.
D/SPPClientService( 7396): ============PushLog. stop!
E/SPPClientService( 7396): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
I/SA      ( 6488): [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
I/SA      ( 6488): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 6488): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 6488): [SLFUCHKMGR] constructor called
I/SA      ( 6488): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
E/SPPClientService( 7396): [[SystemStateMonitorService]] No Active Internet
I/SA      ( 6488): [OR] == isSIMCardReady false ==
I/SA      ( 6488): [SCU] == networkStateCheck == false
I/SA      ( 6488): [OR] onReceive END
E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7415): MountEmulatedStorage()
E/Zygote  ( 7415): v2
I/libpersona( 7415): KNOX_SDCARD checking this for 10074
I/libpersona( 7415): KNOX_SDCARD not a persona
I/SELinux ( 7415): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/ActivityManager(  731): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=7415 uid=10074 gids={50074, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager(  731): Killing 6567:com.google.android.apps.docs/u0a112 (adj 15): bgCount ##41
I/SELinux ( 7415): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7415): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7415): TimaSignature is unavailable
D/ActivityThread( 7415): Added TimaKeyStore provider
D/ResourcesManager( 7415): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
I/ServiceManager(  323): Waiting for service AtCmdFwd...
I/sCloudBackupApp( 7415): sCloudBackupApp Version Info : 3.13.7.KK_APP
I/SCloudBackupReceiver( 7415): Other Intent
I/KnoxUsageLogPro( 7029): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 7029): premStatus:2
I/KnoxUsageLogPro( 7029): isEulaShown : false
I/KnoxUsageLogPro( 7029): KnoxUsageReceiver onReceive : not Processible, just return
E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7431): MountEmulatedStorage()
E/Zygote  ( 7431): v2
I/libpersona( 7431): KNOX_SDCARD checking this for 10104
I/libpersona( 7431): KNOX_SDCARD not a persona
I/ActivityManager(  731): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7431 uid=10104 gids={50104, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  731): Killing 6614:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
,I/SELinux ( 7431): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7431): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7431): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/dhcpcd  ( 7369): wlan0: acknowledged 192.168.1.128 from 192.168.1.1
,I/dhcpcd  ( 7369): wlan0: leased 192.168.1.128 for 86400 seconds
,D/ConnectivityService(  731): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,D/TimaKeyStoreProvider( 7431): TimaSignature is unavailable
,D/ActivityThread( 7431): Added TimaKeyStore provider
,D/ResourcesManager( 7431): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7460): MountEmulatedStorage()
E/Zygote  ( 7460): v2
I/libpersona( 7460): KNOX_SDCARD checking this for 10146
I/libpersona( 7460): KNOX_SDCARD not a persona
,I/SELinux ( 7460): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/ActivityManager(  731): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7460 uid=10146 gids={50146, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  731): Killing 6634:com.samsung.android.app.watchmanagerstub/u0a126 (adj 15): bgCount ##41
,I/SELinux ( 7460): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7460): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7460): TimaSignature is unavailable
,D/ActivityThread( 7460): Added TimaKeyStore provider
,D/ResourcesManager( 7460): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7460): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7460): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7460): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7460): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/native  (  731): do suspend true
,D/WifiP2pService(  731): InactiveState{ what=143375 }
,D/WifiP2pService(  731): P2pEnabledState{ what=143375 }
,D/ConnectivityService(  731): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
E/WifiStateMachine(  731): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG7005g"WPA_PSK
E/WifiStateMachine(  731): VerifyingLinkState enter
,D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiNative-HAL(  731): callSECApiInt - ID [210]
,E/ConnectivityService(  731): updateNetworkInfo()
,D/ConnectivityService(  731): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService(  731): Adding iface wlan0 to network 503
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/WifiWatchdogStateMachine(  731): updateDnsLinkProperty: enter
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:null
D/WifiWatchdogStateMachine.DnsPinger(  731): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.DnsResolver(  731): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker(  731): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  731): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,E/WifiStateMachine(  731): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,I/WifiTrafficPoller(  731): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/ConnectivityService(  731): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:null
D/ConnectivityService(  731): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService(  731): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService(  731): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  731): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  731): updateSourceRoutes : add src route for:192.168.1.128
,V/        (  282): QcRouteController
I/WifiTrafficPoller(  731): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
I/WifiTrafficPoller(  731): mBoosterFLAG : 0
I/WifiTrafficPoller(  731): current booster mode : FullMode
D/WifiNative-HAL(  731): callSECApiVoid - ID [212]
,D/StatusBar.NetworkController( 1181): applyOpen
,D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): applyOpen
,E/WifiStateMachine(  731): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,V/        (  282): QcRouteController
,E/SMD     (  288): DCD ON
,V/        (  282): QcRouteController
,V/        (  282): QcRouteController
,V/        (  282): QcRouteController
,V/        (  282): QcRouteController
,V/        (  282): QcRouteController
,V/        (  282): QcRouteController
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/ConnectivityService(  731): Setting Dns servers for network 503 to [/192.168.1.1]
,D/ConnectivityService(  731): LTETest block dns file not exists
,V/Nat464Xlat(  731): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/ConnectivityService(  731): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  731): calling update connectivity
,D/ConnectivityService(  731): ignoring duplicate network state non-change. WIFI, state = CONNECTING
D/EntConnectivity(  731): Not allowed due to - mEnabled false
,E/ConnectivityService(  731): updateNetworkInfo()
D/ConnectivityService(  731): ignoring duplicate network state non-change. WIFI, state = CONNECTING
,E/ConnectivityService(  731): updateNetworkInfo()
,D/ConnectivityService(  731): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService(  731): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  731): calling update connectivity
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  731): DefaultState{ when=-3ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  731): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  731): Connected
I/WebViewFactory( 7460): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  731): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  731): Checking http://clients3.google.com/generate_204 on "NG7005g"
,I/System.out(  731): (HTTPLog)-Static: isSBSettingEnabled false
,D/ConnectivityService(  731):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService(  731):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  731):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  731):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ResourcesManager( 7460): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,D/ConnectivityService(  731): currentScore = 0, newScore = 60
D/ConnectivityService(  731):    accepting network in place of null
D/ConnectivityService(  731): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1420): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker(  731): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  731): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  731): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  731): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  731): MasterInitialState.processMessage what=3
D/ConnectivityService(  731): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/SmartBondingService(  731): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  731): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  731): getSBEnabled() enabled =false
D/SmartBondingService(  731): getSBEnabled() enabled =false
D/ConnectivityService(  731): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  731): calling update connectivity
D/ConnectivityService(  731):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  731):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  731): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/EntConnectivity(  731): Not allowed due to - mEnabled false
,V/NetworkStats(  731): updateIfacesLocked()
D/NtpTrustedTime(  731): currentTimeMillis() cache hit
V/NetworkStats(  731): performPollLocked(flags=0x1)
D/SmartBondingService(  731): getSBEnabled() enabled =false
,D/ConnectivityManager.CallbackHandler( 1181): CM callback handler got msg 524290
D/NetworkStatsFactory(  731): UpdateStatsForKnox
D/ConnectivityService(  731):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  731): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  731): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  731): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NtpTrustedTime(  731): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1181): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1181): updateDataNetType()
D/StatusBar.NetworkController( 1181): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1181): updateLTEICONDataNetType:0
,D/SmartBondingService(  731): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityManager.CallbackHandler( 2237): CM callback handler got msg 524290
,V/NetworkStats(  731): performPollLocked() took 7ms
D/NtpTrustedTime(  731): currentTimeMillis() cache hit
,D/NtpTrustedTime(  731): currentTimeMillis() cache hit
D/NtpTrustedTime(  731): currentTimeMillis() cache hit
D/NtpTrustedTime(  731): currentTimeMillis() cache hit
D/NtpTrustedTime(  731): currentTimeMillis() cache hit
D/NtpTrustedTime(  731): currentTimeMillis() cache hit
V/NetworkStats(  731): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/StatusBar.NetworkController( 1181): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
D/StatusBar.NetworkController( 1181): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): applyOpen
,I/LibraryLoader( 7460): Loading: webviewchromium
,I/LibraryLoader( 7460): Time to load native libraries: 7 ms (timestamps 1559-1566)
,I/LibraryLoader( 7460): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7460): Binding Chromium to main looper Looper (main, tid 1) {3c0c7652}
,I/LibraryLoader( 7460): Expected native library version number "",actual native library version number ""
,I/chromium( 7460): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7460): Initializing chromium process, renderers=0
,W/art     ( 7460): Attempt to remove local handle scope entry from IRT, ignoring
,I/System.out(  731): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,W/chromium( 7460): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7460): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46780 len=2953
,I/chromium( 7460): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229536 len:643667
,W/AudioManagerAndroid( 7460): Requires BLUETOOTH permission
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  731): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 10 Dec 2015 13:40:54 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449754853996], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449754853975]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  731): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  731): Validated
D/ConnectivityService(  731): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  731): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  731):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  731):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  731):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  731): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  731): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  731): calling update connectivity
D/ConnectivityService(  731):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  731):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  731): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  731):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  731): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1181): CM callback handler got msg 524290
D/ConnectivityService(  731): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 2237): CM callback handler got msg 524290
,D/ConnectivityService(  731): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1181): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1181): updateDataNetType()
D/StatusBar.NetworkController( 1181): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1181): updateLTEICONDataNetType:0
D/StatusBar.NetworkController( 1181): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
,I/Adreno-EGL( 7460): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 7460): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7460): Build Date: 11/19/14 Wed
I/Adreno-EGL( 7460): Local Branch: mybranch5813579
I/Adreno-EGL( 7460): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 7460): Local Patches: NONE
I/Adreno-EGL( 7460): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,I/NSApplication( 7460): Starting up...
,D/ConnectivityService(  731): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  731): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  731): Killing 6649:com.samsung.helphub/1000 (adj 15): bgCount ##41
,D/ConnectivityService(  731): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  731): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7550): MountEmulatedStorage()
,E/Zygote  ( 7550): v2
I/libpersona( 7550): KNOX_SDCARD checking this for 10158
,I/libpersona( 7550): KNOX_SDCARD not a persona
,I/ActivityManager(  731): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7550 uid=10158 gids={50158, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 7550): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,D/ConnectivityService(  731): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/SELinux ( 7550): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7550): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  731): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  731): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  731): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  731): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  731): SmartBondingReceiver: wifi ap is not changed
D/ConnectivityService(  731): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  731): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  731): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  731): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  731): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  731): getSBEnabled() enabled =false
D/SmartBondingService(  731): getSBEnabled() enabled =false
D/SmartBondingService(  731): getSBEnabled() enabled =false
D/ConnectivityService(  731): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  731): getNetworkEnabled : wifi : true mobile : true
D/ConnectivityService(  731): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1870): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,W/ContextImpl( 1870): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/ConnectivityService(  731): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  731): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  731): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  731): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  731): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/TimaKeyStoreProvider( 7550): TimaSignature is unavailable
,I/NetworkMonitor( 5714): type=WIFI subType= reason=null isConnected=true
D/ActivityThread( 7550): Added TimaKeyStore provider
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GpsLocationProvider(  731): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3439): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3439): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  731): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  731): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7550): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 7550): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7550): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7550): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 7550): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7550): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/art     (  731): Explicit concurrent mark sweep GC freed 108721(6MB) AllocSpace objects, 25(448KB) LOS objects, 17% free, 37MB/45MB, paused 1.823ms total 147.881ms
,D/SecContentProvider2(  731): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  731): mCursor = null
,I/QuickConnect( 7550): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7570): MountEmulatedStorage()
E/Zygote  ( 7570): v2
I/libpersona( 7570): KNOX_SDCARD checking this for 10186
,I/libpersona( 7570): KNOX_SDCARD not a persona
,I/ActivityManager(  731): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7570 uid=10186 gids={50186, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  731): Killing 6684:com.samsung.android.snote:provider/u0a168 (adj 15): bgCount ##41
I/SELinux ( 7570): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7570): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7570): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7570): TimaSignature is unavailable
,D/ActivityThread( 7570): Added TimaKeyStore provider
,D/ResourcesManager( 7570): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7570): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7570): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7570): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7570): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7570): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/ConnectivityService(  731): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/RCPManagerService(  731): exchangeData() failure , invalid userId
,D/RCPManagerService(  731): exchangeData() failure , invalid userId
,D/RCPManagerService(  731): exchangeData() failure , invalid userId
,I/jxcore-log( 7180): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 7180): 
,E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService(  731): exchangeData() failure , invalid userId
,I/ActivityManager(  731): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7597 uid=10092 gids={50092, 9997} abi=armeabi-v7a
E/Zygote  ( 7597): MountEmulatedStorage()
I/libpersona( 7597): KNOX_SDCARD checking this for 10092
E/Zygote  ( 7597): v2
I/libpersona( 7597): KNOX_SDCARD not a persona
,I/SELinux ( 7597): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7597): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7597): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  731): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  731): exchangeData() failure , invalid userId
,W/ProcessCpuTracker(  731): Skipping unknown process pid 7566
,W/ProcessCpuTracker(  731): Skipping unknown process pid 7567
,W/ProcessCpuTracker(  731): Skipping unknown process pid 7569
D/RCPManagerService(  731): exchangeData() failure , invalid userId
,W/ProcessCpuTracker(  731): Skipping unknown process pid 7573
W/ProcessCpuTracker(  731): Skipping unknown process pid 7591
,D/TimaKeyStoreProvider( 7597): TimaSignature is unavailable
,D/ActivityThread( 7597): Added TimaKeyStore provider
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6862): KnoxConfiguration : Current State = 1
I/ActivityManager(  731): Killing 6702:com.sec.kidsplat.installer/u0a189 (adj 15): bgCount ##41
D/SecurityLogAgent( 6862): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6862): StateMachine : Current State = 1
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6862): StateMachine : Changed Current State = 1
,I/ActivityManager(  731): Killing 5278:com.sec.android.app.samsungapps/u0a45 (adj 15): bgCount ##41
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 7597): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/ConnectivityService(  731): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
,D/ConnectivityService(  731): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService(  731): identical MTU - not setting
D/ConnectivityService(  731): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  731): updateSourceRoutes : add src route for:fe80::ea50:8bff:fede:28a3
V/        (  282): QcRouteController
,D/BadgeProvider( 7597): onCreate
,D/BadgeProvider( 7597): DatabaseHelper
,V/        (  282): QcRouteController
E/Zygote  ( 7619): MountEmulatedStorage()
I/libpersona( 7619): KNOX_SDCARD checking this for 10200
E/Zygote  ( 7619): v2
I/libpersona( 7619): KNOX_SDCARD not a persona
,W/NetworkManagementService(  731): route cmd failed: 
W/NetworkManagementService(  731): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '74 route replace src v6 wlan0 fe80::ea50:8bff:fede:28a3 2 ::' failed with '400 74 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  731): '
W/NetworkManagementService(  731): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService(  731): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService(  731): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService(  731): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService(  731): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  731): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5625)
W/NetworkManagementService(  731): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5437)
W/NetworkManagementService(  731): 	at com.android.server.ConnectivityService.access$2300(ConnectivityService.java:229)
W/NetworkManagementService(  731): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2382)
W/NetworkManagementService(  731): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  731): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  731): 	at android.os.HandlerThread.run(HandlerThread.java:61)
V/Nat464Xlat(  731): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  731): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  731): calling update connectivity
D/ConnectivityService(  731):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  731):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  731): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  731):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  731): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  731): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  731): calling update connectivity
D/ConnectivityService(  731):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  731):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  731): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  731):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  731): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/ActivityManager(  731): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7619 uid=10200 gids={50200, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ConnectivityManager.CallbackHandler( 1181): CM callback handler got msg 524295
I/SELinux ( 7619): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/ConnectivityManager.CallbackHandler( 1181): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 2237): CM callback handler got msg 524295
I/SELinux ( 7619): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7619): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
D/ConnectivityManager.CallbackHandler( 2237): CM callback handler got msg 524295
,D/SmartBondingService(  731): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  731): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  731): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  731): getSBEnabled() enabled =false
D/SmartBondingService(  731): getSBEnabled() enabled =false
D/SmartBondingService(  731): getSBEnabled() enabled =false
,D/TimaKeyStoreProvider( 7619): TimaSignature is unavailable
,D/ActivityThread( 7619): Added TimaKeyStore provider
,D/ResourcesManager( 7619): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,D/BadgeProvider( 7597): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/ActivityManager(  731): Killing 4436:com.sec.android.app.shealth/u0a40 (adj 15): bgCount ##41
,D/BadgeProvider( 7597): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7597): sendNotify, [notify] : null
D/BadgeProvider( 7597): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7597): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7597): update, [UpdateCount] : 1
,D/Launcher.Model( 1444): reloadBadges entered.
,W/ActivityManager(  731): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ConnectivityService(  731): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  731): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  731): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  731): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  731): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7637): MountEmulatedStorage()
E/Zygote  ( 7637): v2
I/libpersona( 7637): KNOX_SDCARD checking this for 10045
I/libpersona( 7637): KNOX_SDCARD not a persona
,I/ActivityManager(  731): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7637 uid=10045 gids={50045, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 7637): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7637): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7637): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/art     (  316): Explicit concurrent mark sweep GC freed 8744(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 837us total 32.070ms
,I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 518us total 36.587ms
,I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 551us total 17.149ms
,D/TimaKeyStoreProvider( 7637): TimaSignature is unavailable
,D/ActivityThread( 7637): Added TimaKeyStore provider
,D/ResourcesManager( 7637): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-1/base.apk
,D/ConnectivityService(  731): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 7637): notifyNetworkActivated
,W/ContextImpl( 7637): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  731): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 4
,D/hcjo    ( 7637): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7637): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 7637): exit::IDLE
D/InitializeManagerStateMachine( 7637): entry::NETWORK_CHECK
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7637): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7637): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7637): entry::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 7637): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7637): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7637): entry::SUCCESS
D/hcjo    ( 7637): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 7637): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7637): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/ConnectivityService(  731): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7637): exit::SUCCESS
D/InitializeManagerStateMachine( 7637): entry::IDLE
,I/ActivityManager(  731): Killing 6508:com.android.mms/u0a55 (adj 15): bgCount ##41
,I/Hs20UtilService( 1321): Starting #8
I/Hs20UtilService( 1321): Message received 5007
,D/NearbySettings( 1321): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1321): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1321): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1321): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1321): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1321): MountReceiver.onReceive - Keep current state
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6667): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 1321): Starting #9
,D/NearbySettings( 1321): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/Hs20UtilService( 1321): Message received 5007
,I/NearbySettings( 1321): MountReceiver.onReceive - Keep current state
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6667): NETWORK_STATE_CHANGED_ACTION
,D/CountryDetector(  731): No listener is left
,I/Hs20UtilService( 1321): Starting #10
,I/Hs20UtilService( 1321): Message received 5007
,D/NearbySettings( 1321): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1321): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1321): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1321): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1321): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1321): MountReceiver.onReceive - Keep current state
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6667): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 1321): Starting #11
,I/Hs20UtilService( 1321): Message received 5007
,D/NearbySettings( 1321): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1321): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine(  731): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6667): NETWORK_STATE_CHANGED_ACTION
,I/PCWCLIENTTRACE_PushUtil( 7302): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7302): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7302): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7302): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/SurfaceFlinger(  254): id=16 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService(  731): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=731
,I/DIAGMON_AGENT( 7336): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT( 7336): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/FOTA_Client( 6737): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 6737): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 6737): [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.511: ( 6753): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.511: ( 6753): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449754856463
,I/KLMS-2.4.511: ( 6753): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/dhcpcd  ( 7369): wlan0: sending IPv6 Router Solicitation
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.511: ( 6753): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.511: ( 6753): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.511: ( 6753): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.511: ( 6753): StateImplV2(): networkChangeListener().END
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SO_AGENT( 6768): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 7396): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 6488): [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
,I/SA      ( 6488): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,I/SA      ( 6488): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6488): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6488): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  731): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 6488): [SCU] == networkStateCheck == true
,I/SA      ( 6488): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 6488): isChinaCountryCode : false
I/SA      ( 6488): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6488): [OR] == networkStateCheck true ==
,I/SA      ( 6488): [OR] GetMyCountryZoneTask
,I/SA      ( 6488): [OR] onReceive END
,I/SA      ( 6488): [SRS] prepareGetMyCountryZone
,D/ConnectivityService(  731): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SCloudBackupReceiver( 7415): Other Intent
,I/KnoxUsageLogPro( 7029): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7029): premStatus:2
,I/KnoxUsageLogPro( 7029): isEulaShown : false
,I/KnoxUsageLogPro( 7029): KnoxUsageReceiver onReceive : not Processible, just return
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  288): DCD ON
,I/SA      ( 6488): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6488): [SSP] query invoked
,D/ConnectivityService(  731): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6488): [TPMU] GetMccFromDB : null
,I/SA      ( 6488): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6488): [TPM] isNoProxy(default) : true
,D/ConnectivityService(  731): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  731): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 7550): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7550): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 7550): PeriphStartReceiver.onReceive - no need to start
,E/File    ( 6488): fail readDirectory() errno=2
,D/ConnectivityService(  731): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  731): exchangeData() failure , invalid userId
,D/RCPManagerService(  731): exchangeData() failure , invalid userId
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6862): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6862): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6862): StateMachine : Current State = 1
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 6862): StateMachine : Changed Current State = 1
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  731): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  731): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  731): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  731): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  731): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  731): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7637): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7637): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7637): exit::IDLE
D/InitializeManagerStateMachine( 7637): entry::NETWORK_CHECK
D/ConnectivityService(  731): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7637): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7637): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7637): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7637): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
,D/InitializeManagerStateMachine( 7637): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7637): entry::SUCCESS
D/hcjo    ( 7637): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 7637): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7637): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/ConnectivityService(  731): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7637): exit::SUCCESS
D/InitializeManagerStateMachine( 7637): entry::IDLE
,E/WifiStateMachine(  731): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/SA      ( 6488): [RC New] Execute method=[GET] start
,I/SA      ( 6488): [RC New] Security=[true]
,I/System.out( 6488): Thread-1065(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6488): Thread-1065(ApacheHTTPLog):isShipBuild true
,I/System.out( 6488): Thread-1065(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/SA      ( 6488): [RC New] [v2liruge] api execute + 755
,I/SA      ( 6488): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6488): AsyncTask #1 calls detatch()
,I/SA      ( 6488): [TPMU] getNetworkMcc : 
,I/SA      ( 6488): [SCU] saveMccToPreferece Start
,I/SA      ( 6488): [SCU] RegionMCC : 260
,I/SA      ( 6488): [SSP] query invoked
,I/SA      ( 6488): [TPMU] GetMccFromDB : null
,I/SA      ( 6488): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6488): [SCU] saveMccToPreferece End
,I/SA      ( 6488): [RC New] executeRequest [v2liruge] end. 852
,I/SA      ( 6488): [RC New] Execute end
,I/SA      ( 6488): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 6488): [OR] GetMyCountryZoneTask Success
,E/Watchdog(  731): !@Sync 5
,I/GAV4    ( 7460): Thread[GAThread,5,main]: No campaign data found.
,E/SMD     (  288): DCD ON
,D/ConnectivityService(  731): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SurfaceFlinger(  254): id=16 Removed Uoast (8/9)
,I/SurfaceFlinger(  254): id=16 Removed Uoast (-2/9)
,D/PowerManagerService(  731): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 731) eventTime = 167391
,D/PowerManagerService(  731): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=731 (0x0)
,D/PowerManagerService(  731): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=731, ws=WorkSource{10067}) (elapsedTime=3481)
,D/ConnectivityService(  731): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  731): waitForAlarm result :8
,I/dhcpcd  ( 7369): wlan0: sending IPv6 Router Solicitation
,D/SSRM:n  (  731): SIOP:: AP = 340, PST = 342, CUR = 450
,D/BatteryService(  731): !@BatteryListener : batteryPropertiesChanged!
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7302): mConnectivityHandler : connected
,D/ConnectivityService(  731): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 7302): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE( 7302): ================================================
,I/CSTORAGE( 7302):  CSTORAGE_SKM_LIB v1.0.6
I/CSTORAGE( 7302): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 7302): [GetString-S]
E/art     ( 7302): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 7302): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI( 7302): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 7302): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7302): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7302): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 7302): [ensureRegistration] - No Samsung account
,E/SMD     (  288): DCD ON,
,W/ContextImpl(  731): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/dhcpcd  ( 7369): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 7369): wlan0: no IPv6 Routers available
,E/SMD     (  288): DCD ON
,D/PreloadUpdateManagerStateMachine( 7637): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7637): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7637): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7637): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7637): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7637): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7637): entry::IDLE
,D/PreloadUpdateManagerStateMachine( 7637): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7637): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7637): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7637): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/PreloadUpdateManagerStateMachine( 7637): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7637): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7637): entry::IDLE
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  731): SIOP:: AP = 320, PST = 333, CUR = 450
,D/BatteryService(  731): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/PowerManagerService(  731): [PWL] Off : 75s ago
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:n  (  731): SIOP:: AP = 310, PST = 328, CUR = 450
,E/SMD     (  288): DCD ON
,W/ContextImpl(  731): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,E/Watchdog(  731): !@Sync 6
,E/SMD     (  288): DCD ON
,V/AlarmManager(  731): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,D/BatteryService(  731): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  731): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  731): stay LED for fully charged
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 2912): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2912): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  731): Plugged
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  731): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  (  731): SIOP:: AP = 310, PST = 325, CUR = 450
,I/ClearcutLoggerApiImpl( 1882): disconnect managed GoogleApiClient
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  731): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  731): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  731): stay LED for fully charged
D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  731): Plugged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,I/MotionRecognitionService(  731): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2912): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2912): Disconnected process message: 10
,D/SSRM:n  (  731): SIOP:: AP = 310, PST = 322, CUR = 450
,E/SMD     (  288): DCD ON
,W/ContextImpl(  731): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,I/Atfwd_Sendcmd(  323): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  323): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/PowerManagerService(  731): [PWL] Off : 105s ago
,E/SMD     (  288): DCD ON
,D/BatteryService(  731): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  731): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  731): Plugged
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,I/MotionRecognitionService(  731): setPowerConnected  = true
,D/BatteryService(  731): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2912): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2912): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  731): SIOP:: AP = 310, PST = 320, CUR = 450
,E/SMD     (  288): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/Watchdog(  731): !@Sync 7
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,V/AlarmManager(  731): waitForAlarm result :8
,D/BatteryService(  731): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 1
,D/SSRM:n  (  731): SIOP:: AP = 310, PST = 319, CUR = 450
,E/SMD     (  288): DCD ON
,W/ContextImpl(  731): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/BatteryService(  731): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  731): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,I/MotionRecognitionService(  731): Plugged
,I/MotionRecognitionService(  731): setPowerConnected  = true
,D/BatteryService(  731): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2912): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2912): Disconnected process message: 10
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:n  (  731): SIOP:: AP = 300, PST = 317, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  731): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  731): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  731): Plugged
,I/MotionRecognitionService(  731): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/BatteryService(  731): stay LED for fully charged
,E/SMD     (  288): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2912): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2912): Disconnected process message: 10
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/PowerManagerService(  731): [PWL] Off : 140s ago
,D/SSRM:n  (  731): SIOP:: AP = 300, PST = 316, CUR = 450
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,W/ContextImpl(  731): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  288): DCD ON
,E/Watchdog(  731): !@Sync 8
,E/SMD     (  288): DCD ON
,D/BatteryService(  731): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  731): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  731): Plugged
,I/MotionRecognitionService(  731): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/BatteryService(  731): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2912): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2912): Disconnected process message: 10
,D/SSRM:n  (  731): SIOP:: AP = 300, PST = 311, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  731): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  731): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  731): Plugged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
I/MotionRecognitionService(  731): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2912): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2912): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  731): stay LED for fully charged
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/SSRM:n  (  731): SIOP:: AP = 300, PST = 307, CUR = 450
,E/SMD     (  288): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,W/ContextImpl(  731): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  731): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  731): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450,
D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  731): Plugged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  731): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2912): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2912): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  731): stay LED for fully charged
,D/SSRM:n  (  731): SIOP:: AP = 300, PST = 305, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  731): !@Sync 9
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  731): [PWL] Off : 180s ago
,D/BatteryService(  731): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  731): SIOP:: AP = 300, PST = 304, CUR = 450
,E/SMD     (  288): DCD ON
,W/ContextImpl(  731): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 5
,D/BatteryService(  731): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  731): SIOP:: AP = 300, PST = 303, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  731): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  731): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  731): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  731): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  731): Plugged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,I/MotionRecognitionService(  731): setPowerConnected  = true
,D/BatteryService(  731): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1181):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2912): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2912): Disconnected process message: 10
,D/SSRM:n  (  731): SIOP:: AP = 300, PST = 302, CUR = 450
,E/SMD     (  288): DCD ON
,W/ContextImpl(  731): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService(  731): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  731): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  731): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  731): initializing...
,I/TLC_TIMA_PKM_initialize(  731): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  731): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  731): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication(  731): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication(  731): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication(  731): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  731): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: (  731): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  731): App is not loaded in QSEE
,D/QSEECOMAPI: (  731): Loaded image: APP id = 4
,I/TZ: qc_tlc_communication(  731): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  731): Trustlet response is completed
,E/SMD     (  288): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  731): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  731): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,E/Watchdog(  731): !@Sync 10
,D/TimaService(  731): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  731): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  288): DCD ON
,D/BatteryService(  731): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  731): SIOP:: AP = 300, PST = 301, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,I/Atfwd_Sendcmd(  323): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  323): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  731): SIOP:: AP = 300, PST = 300, CUR = 450
,W/ContextImpl(  731): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  731): [PWL] Off : 225s ago
,V/AlarmManager(  731): waitForAlarm result :4
,E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  731): checkUser: useridlist=null, currentuser=0
,D/BatteryService(  731): !@BatteryListener : batteryPropertiesChanged!
,I/ActivityManager(  731): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=7736 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,E/Zygote  ( 7736): MountEmulatedStorage()
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,E/Zygote  ( 7736): v2
I/libpersona( 7736): KNOX_SDCARD checking this for 10096
I/libpersona( 7736): KNOX_SDCARD not a persona
,I/SELinux ( 7736): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7736): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7736): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/TimaKeyStoreProvider( 7736): TimaSignature is unavailable
,D/ActivityThread( 7736): Added TimaKeyStore provider
,D/ResourcesManager( 7736): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,I/ActivityManager(  731): Killing 6784:com.samsung.android.scloud.sync/u0a76 (adj 15): bgCount ##41
,E/SMD     (  288): DCD ON
,I/ActivityManager(  731): Killing 6800:com.sec.android.app.clockpackage/u0a106 (adj 15): bgCount ##41
,E/SMD     (  288): DCD ON
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/SSRM:n  (  731): SIOP:: AP = 300, PST = 300, CUR = 450,
,I/ServiceManager(  323): Waiting for service AtCmdFwd...

```
