#### Test 50650278b86327b_thali05_samsung-SM-N9005 Logs


```
--------- beginning of main
E/SMD     (  287): DCD ON
,D/AndroidRuntime( 7251): 
D/AndroidRuntime( 7251): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7251): CheckJNI is OFF
D/AndroidRuntime( 7251): readGMSProperty: start
D/AndroidRuntime( 7251): readGMSProperty: already setted!!
D/AndroidRuntime( 7251): readGMSProperty: end
D/AndroidRuntime( 7251): addProductProperty: start
E/AffinityControl( 7251): AffinityControl: registerfunction enter
D/AndroidRuntime( 7251): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  735): inState():  stateMachine is null !!
I/PersonaManagerService(  735): PersonaId don't exist
I/ActivityManager(  735): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  735): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
I/ActivityManager(  735): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  735): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager(  735): mDVFSHelper.acquire()
D/FocusedStackFrame(  735): Set to : 0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  735): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7266 uid=10281 gids={50281, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7251): Shutting down VM
D/PointerIcon(  735): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  735): setMouseCustomIcon IconType is same.101
D/PointerIcon(  735): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  735): setHoveringSpenCustomIcon IconType is same.1
E/Zygote  ( 7266): MountEmulatedStorage()
E/Zygote  ( 7266): v2
I/libpersona( 7266): KNOX_SDCARD checking this for 10281
I/libpersona( 7266): KNOX_SDCARD not a persona
I/SELinux ( 7266): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7266): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7266): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7266): TimaSignature is unavailable
D/ActivityThread( 7266): Added TimaKeyStore provider
V/WindowOrientationListener(  735): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowManager(  735): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  735): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowOrientationListener(  735): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  735): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager(  735): Display changed displayId=0
D/SurfaceWidgetView( 1428): destroyHardwareResources():852467732
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1797): [237392/8] Surface widget visibility changed visibility = false on instance = 1
V/ActivityThread( 1428): updateVisibility : ActivityRecord{3b12b985 token=android.os.BinderProxy@34896b66 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1428): onTrimMemory. Level: 20
D/ConnectivityService(  735): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SurfaceFlinger(  254): id=14 Removed Mauncher (5/8)
I/SurfaceFlinger(  254): id=14 Removed Mauncher (-2/8)
,D/ResourcesManager( 7266): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,I/WebViewFactory( 7266): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,D/ResourcesManager( 7266): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7266): Loading: webviewchromium
,I/LibraryLoader( 7266): Time to load native libraries: 6 ms (timestamps 7014-7020)
,I/LibraryLoader( 7266): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7266): Binding Chromium to main looper Looper (main, tid 1) {2573984e}
,I/LibraryLoader( 7266): Expected native library version number "",actual native library version number ""
,I/chromium( 7266): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7266): Initializing chromium process, renderers=0
,W/art     ( 7266): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7266): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7266): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46780 len=2953
I/chromium( 7266): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229536 len:643667
,I/Adreno-EGL( 7266): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 7266): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7266): Build Date: 11/19/14 Wed
I/Adreno-EGL( 7266): Local Branch: mybranch5813579
I/Adreno-EGL( 7266): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 7266): Local Patches: NONE
I/Adreno-EGL( 7266): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,W/ActivityManager(  735): Activity pause timeout for ActivityRecord{253b0b43 u0 com.test.thalitest/.MainActivity t4}
,W/chromium( 7266): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7266): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 7266): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7266): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 7266): CordovaWebView is running on device made by: samsung
,W/art     ( 7266): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7266): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity( 7266): performCreate Call secproduct feature valuefalse
D/Activity( 7266): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer( 7266): Render dirty regions requested: true
,D/Atlas   ( 7266): Validating map...
,D/ActivityManager(  735): post active user change for 0
D/KnoxTimeoutHandler(  735): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  735): handleActiveUserChange for user 0
,V/ActivityThread( 7266): updateVisibility : ActivityRecord{3c98f05f token=android.os.BinderProxy@39d0a4b9 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/SurfaceFlinger(  254): id=16 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService(  735): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  735): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon(  735): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  735): setMouseCustomIcon IconType is same.101
D/PointerIcon(  735): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  735): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer( 7266): Initialized EGL, version 1.4
,I/OpenGLRenderer( 7266): HWUI protection enabled for context ,  &this =0xb3b56ab0 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 7266): Enabling debug mode 0
,D/InputMethodManagerService(  735): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager(  735): mDVFSHelper.release()
I/Timeline(  735): Timeline: Activity_windows_visible id: ActivityRecord{253b0b43 u0 com.test.thalitest/.MainActivity t4} time:157697
,W/IInputConnectionWrapper( 7266): showStatusIcon on inactive InputConnection
,I/Timeline( 7266): Timeline: Activity_idle id: android.os.BinderProxy@39d0a4b9 time:157706
,D/JsMessageQueue( 7266): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 7266): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7266): 
,D/jxcore_app_log( 7266): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1356772224
,D/JX-Cordova( 7266): jxcore cordova android initializing
,E/SMD     (  287): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,D/SSRM:n  (  735): SIOP:: AP = 330, PST = 343, CUR = 450
,W/jxcore-log( 7266): Initializing JXcore engine
W/jxcore-log( 7266): JXcore engine is ready
,W/jxcore-log( 7266): Starting JXcore engine
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/auditd  ( 1863): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  735): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
,D/SecurityLogAgent:SEDenialService(  735): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,E/Zygote  ( 7337): MountEmulatedStorage()
I/ActivityManager(  735): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7337 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/Zygote  ( 7337): v2
I/libpersona( 7337): KNOX_SDCARD checking this for 1000
I/libpersona( 7337): KNOX_SDCARD not a persona
,I/SELinux ( 7337): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7337): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7337): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7337): TimaSignature is unavailable
,D/ActivityThread( 7337): Added TimaKeyStore provider
,D/ResourcesManager( 7337): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,W/jxcore-log( 7266): Platform android
W/jxcore-log( 7266): 
W/jxcore-log( 7266): Process ARCH arm
W/jxcore-log( 7266): 
,D/SecurityLogAgent( 7337):  SeDenialReceiver : Intent Received : android.intent.action.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7337):  SeDenialReceiver : File path = null
,I/ActivityManager(  735): Killing 5910:com.sec.android.app.music:service/u0a49 (adj 15): bgCount ##41
,I/jxcore-log( 7266): JXcore Cordova bridge is ready!
I/jxcore-log( 7266): 
W/jxcore-log( 7266): JXcore engine is started
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
I/jxcore-log( 7266): Toggling radios to true
I/jxcore-log( 7266): 
D/BluetoothAdapter( 7266): enable()
D/BluetoothAdapter( 7266): enable(): BT is already enabled..!
I/WifiManager( 7266): packageName : com.test.thalitest
D/SecContentProvider(  735): uri = 18 selection = isWifiEnabled
D/SecContentProvider2(  735): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  735): mCursor = null
D/WifiService(  735): setWifiEnabled: true pid=7266, uid=10281
W/ActivityManager(  735): Permission Denial: getCurrentUser() from pid=7266, uid=10281 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  735): Failed getting userId using ActivityManagerNative
W/WifiService(  735): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7266, uid=10281 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  735): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23057)
W/WifiService(  735): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2181)
W/WifiService(  735): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2169)
W/WifiService(  735): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  735): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider(  735): name = wifi_on
I/WifiService(  735): disconnect: pid=7266, uid=10281
I/wpa_supplicant( 1278): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 7266): Radios toggled
I/jxcore-log( 7266): 
I/jxcore-log( 7266): Got Device Bluetooth address: E0:DB:10:1F:C9:5E
I/jxcore-log( 7266): 
I/jxcore-log( 7266): Perf Test app loaded loaded
I/jxcore-log( 7266): 
I/wpa_supplicant( 1278): CTRL-EVENT-DISCONNECTED bssid=C0.AA.4A reason=3 locally_generated=1
I/wpa_supplicant( 1278): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 1278): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.4A SSID=4E473730303567
I/wpa_supplicant( 1278): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine(  735): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1278): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1278): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1278): Disconnected - do not scan
I/wpa_supplicant( 1278): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
I/jxcore-log( 7266): check test folder
I/jxcore-log( 7266): 
I/jxcore-log( 7266): found test : ./testFindPeers.js
I/jxcore-log( 7266): 
E/native  (  735): do suspend true
D/WifiP2pService(  735): InactiveState{ what=143375 }
D/WifiP2pService(  735): P2pEnabledState{ what=143375 }
D/StatusBar.NetworkController( 1193): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1193): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
D/CommandListener(  282): Clearing all IP addresses on wlan0
I/jxcore-log( 7266): found test : ./testSendData.js
I/jxcore-log( 7266): 
V/NativeCrypto( 1938): Read error: ssl=0xaf81b600: I/O error during system call, Connection timed out
V/NativeCrypto( 1938): SSL shutdown failed: ssl=0xaf81b600: I/O error during system call, Broken pipe
D/ConnectivityService(  735): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/ConnectivityService(  735): updateNetworkInfo()
D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
D/NetUtils(  735): android_net_utils_resetConnections in env=0xaec72080 clazz=0x99cd798c iface=wlan0 mask=0x3
E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
I/WifiTrafficPoller(  735): evaluateTrafficStatsPolling
D/StatusBar.NetworkController( 1193): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1193): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1193): refreshSignalCluster - setNWBoosterIndicators(false)
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
D/ConnectivityService(  735): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1193): applyOpen
D/StatusBar.NetworkController( 1193): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1193): applyOpen
D/StatusBar.NetworkController( 1193): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1193): applyOpen
D/StatusBar.NetworkController( 1193): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1193): applyOpen
D/ConnectivityService(  735): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10015
D/ConnectivityService(  735): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  735): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  735): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): ValidatedState{ when=-4ms what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): DefaultState{ when=-4ms what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Checking http://clients3.google.com/generate_204 on <unknown ssid>
E/WifiStateMachine(  735): Start Disconnecting Watchdog 1
I/System.out(  735): (HTTPLog)-Static: isSBSettingEnabled false
I/wpa_supplicant( 1278): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1278): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1278): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1278): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1278): First Scan Start
I/qtaguid (  735): Tagging socket 391 with tag ffffffff00000000{4294967295,0} uid 10015, pid: 735, getuid(): 1000
E/Zygote  ( 7359): MountEmulatedStorage()
E/Zygote  ( 7359): v2
I/libpersona( 7359): KNOX_SDCARD checking this for 10038
I/libpersona( 7359): KNOX_SDCARD not a persona
E/native  (  735): do suspend true
I/System.out(  735): (HTTPLog)-Static: isSBSettingEnabled false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Validated
I/ActivityManager(  735): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.samsung.myplace.WIFINotificationHandler: pid=7359 uid=10038 gids={50038, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
I/SELinux ( 7359): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7359): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7359): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/wpa_supplicant( 1278): Scan requested (ret=0) - scan timeout 30 seconds
D/WifiP2pService(  735): InactiveState{ what=143375 }
D/WifiP2pService(  735): P2pEnabledState{ what=143375 }
D/CommandListener(  282): Clearing all IP addresses on wlan0
I/WifiTrafficPoller(  735): evaluateTrafficStatsPolling
D/StatusBar.NetworkController( 1193): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1193): onWifiSignalChanged enabled=true enabledDesc:null
D/WifiNetworkAgent(  735): NetworkAgent: NetworkAgent channel lost
D/StatusBar.NetworkController( 1193): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1193): onWifiSignalChanged enabled=true enabledDesc:null
I/ServiceManager(  339): Waiting for service AtCmdFwd...
D/SecContentProvider2(  735): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  735): mCursor = null
D/TimaKeyStoreProvider( 7359): TimaSignature is unavailable
D/ActivityThread( 7359): Added TimaKeyStore provider
D/SecContentProvider2(  735): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  735): mCursor = null
D/ResourcesManager( 7359): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
W/ResourcesManager( 7359): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/ConnectivityService(  735): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  735): calling update connectivity
D/ConnectivityService(  735):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  735):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  735): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  735):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1193): CM callback handler got msg 524292
D/ConnectivityService(  735): sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/Nat464Xlat(  735): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  735): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  735): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1418): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CSLegacyTypeTracker(  735): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  735): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/EntConnectivity(  735): Not allowed due to - mEnabled false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): ValidatedState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): DefaultState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Disconnected - quitting
D/ConnectivityService(  735): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  735): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  735): MasterInitialState.processMessage what=3
D/SmartBondingService(  735): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  735): getSBEnabled() enabled =false
D/SmartBondingService(  735): getSBEnabled() enabled =false
D/SmartBondingService(  735): getSBEnabled() enabled =false
V/NetworkStats(  735): updateIfacesLocked()
D/ConnectivityManager.CallbackHandler( 2270): CM callback handler got msg 524292
V/NetworkStats(  735): performPollLocked(flags=0x1)
D/NtpTrustedTime(  735): currentTimeMillis() cache hit
D/NetworkStatsFactory(  735): UpdateStatsForKnox
D/SmartBondingService(  735): getNetworkEnabled : wifi : true mobile : true
D/ConnectivityService(  735): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/NtpTrustedTime(  735): currentTimeMillis() cache hit
D/NtpTrustedTime(  735): currentTimeMillis() cache hit
D/ConnectivityService(  735): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/ConnectivityService(  735): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/StatusBar.NetworkController( 1193): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1193): updateDataNetType()
D/StatusBar.NetworkController( 1193): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1193): updateLTEICONDataNetType:0
E/ConnectivityService(  735): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/NtpTrustedTime(  735): currentTimeMillis() cache hit
V/NetworkStats(  735): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  735): currentTimeMillis() cache hit
V/NetworkStats(  735): performPollLocked() took 8ms
D/NtpTrustedTime(  735): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1193): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1193): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1193): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1193): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1193): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1193): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1193): applyOpen
D/StatusBar.NetworkController( 1193): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1193): applyOpen
D/StatusBar.NetworkController( 1193): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1193): applyOpen
D/StatusBar.NetworkController( 1193): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1193): applyOpen
D/NtpTrustedTime(  735): currentTimeMillis() cache hit
D/NtpTrustedTime(  735): currentTimeMillis() cache hit
I/chromium( 7266): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
V/AlarmManager(  735): waitForAlarm result :8
D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1193): handleTimeUpdate
D/KeyguardEffectViewController( 1193): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1193): *** don't update sliding image ***
W/NetworkUtils( 1645): OkHttp exception
D/FileWriteThread_Telephony( 1418): FileWriteThread : threadType = 3
W/EventLoggerService( 1645): Unable to send logs Error code: 262146
D/FileWriteThread_Telephony( 1418): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1418): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1418): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1418): FileWriteThread : threadType = 3
I/chromium( 7266): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
D/DateView( 1193): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/FileWriteThread_Telephony( 1418): FileWriteThread : threadType = 3
D/DateView( 1193): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/FileWriteThread_Telephony( 1418): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1418): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1418): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1418): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1418): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1418): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1418): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1418): FileWriteThread : threadType = 3
I/VlingoApplication( 7359): VlingoApplication appVersion ='11.2.2.0.37649', ro.csc.sales_code=XEO
,I/PhenotypeConfigurator( 1938): Scheduling Phenotype for one-off execution 6176 seconds from now (1449756720232)
,D/GetConfigurationSnapshotOperation( 1938): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,E/BluetoothHeadset( 7359): BTStateChangeCB is registed
,E/BluetoothHeadset( 7359): BluetoothHeadset service is binded
,I/ActivityManager(  735): Killing 5981:com.sec.android.app.myfiles/u0a56 (adj 15): bgCount ##41
,I/Hs20UtilService( 1310): Starting #6
,I/Hs20UtilService( 1310): Message received 5007
,D/NearbySettings( 1310): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1310): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  735): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1310): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1310): DMSUtil.isNetworkConnected - P2P: IDLE
D/ConnectivityService(  735): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1310): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1310): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1310): MountReceiver.mPrefHandler - 7002
,D/SettingsProvider(  735): name = driving_mode_on
D/SettingsProvider(  735): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  735): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  735): selectionArgs: false
D/SettingsProvider(  735): selectionArgs: 10038
D/SecContentProvider(  735): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  735): ret = -1
,D/BluetoothManager( 7359): [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.media.ACTION_SCO_AUDIO_STATE_UPDATED
,I/PhenotypeFlagCommitter( 1938): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1938): Using platform SSLCertificateSocketFactory
,D/ConnectivityService(  735): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6863): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 1310): Starting #7
,I/Hs20UtilService( 1310): Message received 5007
,D/NearbySettings( 1310): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1310): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  735): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1310): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  735): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1310): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1310): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1310): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1310): MountReceiver.mPrefHandler - 7002
,D/ConnectivityService(  735): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6863): NETWORK_STATE_CHANGED_ACTION
,D/LocationManagerService(  735): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  735): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  735): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ApplicationPolicy(  735): updateDataUsageMap
,D/GpsLocationProvider(  735): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  735): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  735): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  735): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  735): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/ConnectivityService(  735): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  735): getSBEnabled() enabled =false
D/SmartBondingService(  735): getSBEnabled() enabled =false
D/SmartBondingService(  735): getSBEnabled() enabled =false
,D/ConnectivityService(  735): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  735): getNetworkEnabled : wifi : true mobile : true
,I/PCWCLIENTTRACE_PushUtil( 6593): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6593): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6593): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6593): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6593): noConnectivity : true
,D/ConnectivityService(  735): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  735): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3602): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/NetworkMonitor( 5862): type=WIFI subType= reason=null isConnected=false
,D/ConnectivityService(  735): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3602): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7421): MountEmulatedStorage()
E/Zygote  ( 7421): v2
I/libpersona( 7421): KNOX_SDCARD checking this for 10004
I/libpersona( 7421): KNOX_SDCARD not a persona
,I/ActivityManager(  735): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7421 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7421): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7421): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7421): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  324): Explicit concurrent mark sweep GC freed 8729(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 313us total 14.922ms
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 270us total 10.424ms
,D/TimaKeyStoreProvider( 7421): TimaSignature is unavailable
,D/ActivityThread( 7421): Added TimaKeyStore provider
,I/System.out( 1938): (HTTPLog)-Static: isSBSettingEnabled false
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 271us total 10.815ms
,D/Uploader( 1938): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/LocationManagerService(  735): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ResourcesManager( 7421): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/System.out( 1938): (HTTPLog)-Static: isSBSettingEnabled false
,D/Uploader( 1938): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/LocationManagerService(  735): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1938): (HTTPLog)-Static: isSBSettingEnabled false
,D/Uploader( 1938): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,I/ActivityManager(  735): Killing 6454:com.google.android.gms:car/u0a15 (adj 15): bgCount ##41
,E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7440): MountEmulatedStorage()
E/Zygote  ( 7440): v2
I/libpersona( 7440): KNOX_SDCARD checking this for 1000
I/libpersona( 7440): KNOX_SDCARD not a persona
,I/SELinux ( 7440): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/ActivityManager(  735): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7440 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7440): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7440): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7440): TimaSignature is unavailable
,D/ActivityThread( 7440): Added TimaKeyStore provider
,D/ResourcesManager( 7440): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT( 7440): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7440): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT( 7440): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7440): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7440): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT( 7440): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7457): MountEmulatedStorage()
E/Zygote  ( 7457): v2
I/libpersona( 7457): KNOX_SDCARD checking this for 10014
I/libpersona( 7457): KNOX_SDCARD not a persona
,I/SELinux ( 7457): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7457): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7457): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  735): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7457 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 7457): TimaSignature is unavailable
,D/ActivityThread( 7457): Added TimaKeyStore provider
,D/ResourcesManager( 7457): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager(  735): Killing 6430:com.android.defcontainer/u0a7 (adj 15): bgCount ##41
,I/FOTA_Client( 7457): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7457): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7457): [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
,I/wpa_supplicant( 1278): nl80211: Received scan results (7 BSSes)
,I/wpa_supplicant( 1278): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1278): Trying to associate with C0.AA.4A (SSID='4E473730303567' freq=5220 MHz)
I/wpa_supplicant( 1278): wlan0: State: SCANNING -> ASSOCIATING
,I/wpa_supplicant( 1278): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E473730303567
,E/Zygote  ( 7472): MountEmulatedStorage()
,E/Zygote  ( 7472): v2
I/libpersona( 7472): KNOX_SDCARD checking this for 10023
,I/libpersona( 7472): KNOX_SDCARD not a persona
I/ActivityManager(  735): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7472 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  735): Killing 6557:com.google.android.partnersetup/u0a19 (adj 15): bgCount ##41
,D/SecContentProvider2(  735): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  735): mCursor = null
,I/wpa_supplicant( 1278): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1278): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E473730303567
,I/wpa_supplicant( 1278): Associated with C0.AA.4A
,D/SecContentProvider2(  735): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  735): mCursor = null
,I/SELinux ( 7472): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7472): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7472): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/wpa_supplicant( 1278): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1278): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.4A SSID=4E473730303567
,D/SecContentProvider2(  735): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  735): mCursor = null
,I/wpa_supplicant( 1278): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1278): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1278): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.4A SSID=4E473730303567
,I/wpa_supplicant( 1278): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1278): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1278): CTRL-EVENT-CONNECTED - Connection to C0.AA.4A completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 1278): Blacklist: Clear (temp) 
I/wpa_supplicant( 1278): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.4A SSID=4E473730303567
,D/WifiNative-HAL(  735): callSECApiVoid - ID [50]
,D/TimaKeyStoreProvider( 7472): TimaSignature is unavailable
,D/StatusBar.NetworkController( 1193): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1193): onWifiSignalChanged enabled=true enabledDesc:null
,D/ActivityThread( 7472): Added TimaKeyStore provider
,D/ConnectivityService(  735): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  735): Got NetworkAgent Messenger
D/ConnectivityService(  735): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  735): updateNetworkInfo()
D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  735): NetworkAgent connected
,D/ResourcesManager( 7472): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  282): Setting iface cfg
,E/WifiStateMachine(  735): Start Dhcp Watchdog 2
,D/SecContentProvider2(  735): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  735): mCursor = null
,I/KLMS-2.4.511: ( 7472): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/ConnectivityService(  735): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,I/KLMS-2.4.511: ( 7472): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449756721333
,I/KLMS-2.4.511: ( 7472): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  735): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  735): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.511: ( 7472): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.511: ( 7472): StateImplV2(): networkChangeListener().END
,E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7488): MountEmulatedStorage()
E/Zygote  ( 7488): v2
I/libpersona( 7488): KNOX_SDCARD checking this for 10036
I/libpersona( 7488): KNOX_SDCARD not a persona
,I/ActivityManager(  735): Start proc com.samsung.android.app.pinboard:tagService for broadcast com.samsung.android.app.pinboard/.service.TagReadyReceiver: pid=7488 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  735): Killing 6576:com.samsung.groupcast/u0a20 (adj 15): bgCount ##41
,I/SELinux ( 7488): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7488): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7488): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7488): TimaSignature is unavailable
,D/ActivityThread( 7488): Added TimaKeyStore provider
,E/native  (  735): do suspend false
,D/SecContentProvider2(  735): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  735): mCursor = null
D/WifiP2pService(  735): InactiveState{ what=143375 }
D/WifiP2pService(  735): P2pEnabledState{ what=143375 }
,D/ResourcesManager( 7488): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,W/ResourcesManager( 7488): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7488): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Minikin ( 7488): addFont failed to create font /system/fonts/SamsungSans-light.ttf
,D/ConnectivityService(  735): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  735): Killing 4619:com.sec.android.app.shealth/u0a40 (adj 15): bgCount ##41
,E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7503): MountEmulatedStorage()
,E/Zygote  ( 7503): v2
I/libpersona( 7503): KNOX_SDCARD checking this for 10042
I/libpersona( 7503): KNOX_SDCARD not a persona
,I/ActivityManager(  735): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7503 uid=10042 gids={50042, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7503): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7503): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7503): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7503): TimaSignature is unavailable
,D/ActivityThread( 7503): Added TimaKeyStore provider
,D/ResourcesManager( 7503): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT( 7503): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,D/ConnectivityService(  735): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  735): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5099): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 6676): [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
,I/SA      ( 6676): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 6676): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,E/SPPClientService( 5099): [[SystemStateMonitorService]] No Active Internet
,I/SA      ( 6676): [SLFUCHKMGR] constructor called
,I/SA      ( 6676): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6676): [OR] == isSIMCardReady false ==
,I/SA      ( 6676): [SCU] == networkStateCheck == false
I/SA      ( 6676): [OR] onReceive END
,I/ActivityManager(  735): Killing 6649:com.samsung.android.sdk.samsunglink/u0a48 (adj 15): bgCount ##41
,E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
,E/dhcpcd  ( 7521): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 7521): version 5.5.6 starting
,E/dhcpcd  ( 7521): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,E/Zygote  ( 7522): MountEmulatedStorage()
E/Zygote  ( 7522): v2
I/libpersona( 7522): KNOX_SDCARD checking this for 10074
I/libpersona( 7522): KNOX_SDCARD not a persona
,I/SELinux ( 7522): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/ActivityManager(  735): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=7522 uid=10074 gids={50074, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 7522): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7522): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7522): TimaSignature is unavailable
,D/ActivityThread( 7522): Added TimaKeyStore provider
,D/ResourcesManager( 7522): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/dhcpcd  ( 7521): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7521): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7521): if(wlan0) info get Success. (MAC : C0.AA.4A)
I/dhcpcd  ( 7521): bssid match
I/dhcpcd  ( 7521): wlan0: rebinding lease of 192.168.1.128
,I/sCloudBackupApp( 7522): sCloudBackupApp Version Info : 3.13.7.KK_APP
,I/SCloudBackupReceiver( 7522): Other Intent
,I/KnoxUsageLogPro( 7068): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7068): premStatus:2
,I/KnoxUsageLogPro( 7068): isEulaShown : false
,I/KnoxUsageLogPro( 7068): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7544): MountEmulatedStorage()
E/Zygote  ( 7544): v2
I/libpersona( 7544): KNOX_SDCARD checking this for 10104
I/libpersona( 7544): KNOX_SDCARD not a persona
,I/SELinux ( 7544): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7544): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7544): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  735): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7544 uid=10104 gids={50104, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  735): Killing 6720:com.sec.android.provider.badge/u0a92 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7544): TimaSignature is unavailable
D/ActivityThread( 7544): Added TimaKeyStore provider
,D/ResourcesManager( 7544): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
,W/Atfwd_Sendcmd(  339): AtCmdFwd service not published, waiting... retryCnt : 4
,I/dhcpcd  ( 7521): wlan0: acknowledged 192.168.1.128 from 192.168.1.1
,E/Zygote  ( 7560): MountEmulatedStorage()
E/Zygote  ( 7560): v2
I/libpersona( 7560): KNOX_SDCARD checking this for 10146
I/libpersona( 7560): KNOX_SDCARD not a persona
,I/dhcpcd  ( 7521): wlan0: leased 192.168.1.128 for 86400 seconds
,I/SELinux ( 7560): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,D/ConnectivityService(  735): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,I/ActivityManager(  735): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7560 uid=10146 gids={50146, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7560): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7560): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  735): Killing 6736:com.sec.android.app.soundalive/u0a64 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7560): TimaSignature is unavailable
,D/ActivityThread( 7560): Added TimaKeyStore provider
,D/ResourcesManager( 7560): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7560): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7560): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/ContextImpl( 7560): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7560): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory( 7560): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,D/ResourcesManager( 7560): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,E/native  (  735): do suspend true
,I/LibraryLoader( 7560): Loading: webviewchromium
,I/LibraryLoader( 7560): Time to load native libraries: 5 ms (timestamps 3929-3934)
,I/LibraryLoader( 7560): Expected native library version number "",actual native library version number ""
,D/WifiP2pService(  735): InactiveState{ what=143375 }
D/WifiP2pService(  735): P2pEnabledState{ what=143375 }
,V/WebViewChromiumFactoryProvider( 7560): Binding Chromium to main looper Looper (main, tid 1) {6fa7344}
,D/ConnectivityService(  735): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  735): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG7005g"WPA_PSK
D/StatusBar.NetworkController( 1193): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
E/WifiStateMachine(  735): VerifyingLinkState enter
D/STATUSBAR-WifiQuickSettingButton( 1193): onWifiSignalChanged enabled=true enabledDesc:null
,I/LibraryLoader( 7560): Expected native library version number "",actual native library version number ""
D/WifiNative-HAL(  735): callSECApiInt - ID [210]
,I/chromium( 7560): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
E/ConnectivityService(  735): updateNetworkInfo()
,D/ConnectivityService(  735): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService(  735): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine(  735): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  735): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver(  735): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker(  735): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  735): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 1193): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1193): onWifiSignalChanged enabled=true enabledDesc:null
,I/BrowserStartupController( 7560): Initializing chromium process, renderers=0
,W/art     ( 7560): Attempt to remove local handle scope entry from IRT, ignoring
,E/WifiStateMachine(  735): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,I/WifiTrafficPoller(  735): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1193): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1193): onWifiSignalChanged enabled=true enabledDesc:null
,I/WifiTrafficPoller(  735): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  735): mBoosterFLAG : 0
I/WifiTrafficPoller(  735): current booster mode : FullMode
D/WifiNative-HAL(  735): callSECApiVoid - ID [212]
,D/StatusBar.NetworkController( 1193): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1193): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
D/StatusBar.NetworkController( 1193): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1193): applyOpen
D/StatusBar.NetworkController( 1193): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1193): applyOpen
D/StatusBar.NetworkController( 1193): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1193): applyOpen
D/StatusBar.NetworkController( 1193): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1193): applyOpen
,E/WifiStateMachine(  735): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/ConnectivityService(  735): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService(  735): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService(  735): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,W/chromium( 7560): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
E/ConnectivityService(  735): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  735): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  735): updateSourceRoutes : add src route for:192.168.1.128
,V/        (  282): QcRouteController
,I/chromium( 7560): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46780 len=2953
,I/chromium( 7560): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229536 len:643667
,W/AudioManagerAndroid( 7560): Requires BLUETOOTH permission
,V/        (  282): QcRouteController
,I/Adreno-EGL( 7560): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 7560): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7560): Build Date: 11/19/14 Wed
I/Adreno-EGL( 7560): Local Branch: mybranch5813579
I/Adreno-EGL( 7560): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 7560): Local Patches: NONE
I/Adreno-EGL( 7560): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,V/        (  282): QcRouteController
,V/        (  282): QcRouteController
,V/        (  282): QcRouteController
,V/        (  282): QcRouteController
,V/        (  282): QcRouteController
,I/NSApplication( 7560): Starting up...
,V/        (  282): QcRouteController
,I/ActivityManager(  735): Killing 5696:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
,D/ConnectivityService(  735): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService(  735): LTETest block dns file not exists
,V/Nat464Xlat(  735): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  735): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  735): calling update connectivity
E/ConnectivityService(  735): updateNetworkInfo()
D/ConnectivityService(  735): ignoring duplicate network state non-change. WIFI, state = CONNECTING
E/ConnectivityService(  735): updateNetworkInfo()
D/ConnectivityService(  735): ignoring duplicate network state non-change. WIFI, state = CONNECTING
D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  735): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  735): calling update connectivity
D/ConnectivityService(  735): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  735):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  735):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/EntConnectivity(  735): Not allowed due to - mEnabled false
D/ConnectivityService(  735):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  735):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Checking http://clients3.google.com/generate_204 on "NG7005g"
,I/System.out(  735): (HTTPLog)-Static: isSBSettingEnabled false
D/ConnectivityService(  735): currentScore = 0, newScore = 60
D/ConnectivityService(  735):    accepting network in place of null
D/ConnectivityService(  735): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1418): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/CSLegacyTypeTracker(  735): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  735): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  735): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  735): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/SmartBondingService(  735): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  735): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  735): getSBEnabled() enabled =false
D/SmartBondingService(  735): getSBEnabled() enabled =false
D/Tethering(  735): MasterInitialState.processMessage what=3
D/SmartBondingService(  735): getSBEnabled() enabled =false
D/NtpTrustedTime(  735): currentTimeMillis() cache hit
V/NetworkStats(  735): updateIfacesLocked()
V/NetworkStats(  735): performPollLocked(flags=0x1)
D/ConnectivityService(  735): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  735): calling update connectivity
D/ConnectivityService(  735):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  735):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  735): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkStatsFactory(  735): UpdateStatsForKnox
D/ConnectivityService(  735):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  735): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  735): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/EntConnectivity(  735): Not allowed due to - mEnabled false
D/ConnectivityManager.CallbackHandler( 1193): CM callback handler got msg 524290
D/ConnectivityService(  735): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/NetworkStats(  735): performPollLocked() took 3ms
D/StatusBar.NetworkController( 1193): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1193): updateDataNetType()
D/StatusBar.NetworkController( 1193): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1193): updateLTEICONDataNetType:0
D/NtpTrustedTime(  735): currentTimeMillis() cache hit
D/SmartBondingService(  735): getNetworkEnabled : wifi : true mobile : true
D/ConnectivityManager.CallbackHandler( 2270): CM callback handler got msg 524290
D/NtpTrustedTime(  735): currentTimeMillis() cache hit
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
D/NtpTrustedTime(  735): currentTimeMillis() cache hit
D/NtpTrustedTime(  735): currentTimeMillis() cache hit
D/NtpTrustedTime(  735): currentTimeMillis() cache hit
V/NetworkStats(  735): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  735): currentTimeMillis() cache hit
D/NtpTrustedTime(  735): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1193): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1193): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1193): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1193): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1193): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
D/StatusBar.NetworkController( 1193): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1193): applyOpen
D/StatusBar.NetworkController( 1193): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1193): applyOpen
D/StatusBar.NetworkController( 1193): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1193): applyOpen
D/StatusBar.NetworkController( 1193): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1193): applyOpen
,E/Zygote  ( 7655): MountEmulatedStorage()
E/Zygote  ( 7655): v2
I/libpersona( 7655): KNOX_SDCARD checking this for 10158
I/libpersona( 7655): KNOX_SDCARD not a persona
I/SELinux ( 7655): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/ActivityManager(  735): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7655 uid=10158 gids={50158, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
I/SELinux ( 7655): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7655): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7655): TimaSignature is unavailable
,D/ActivityThread( 7655): Added TimaKeyStore provider
,I/System.out(  735): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/ResourcesManager( 7655): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 7655): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7655): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 7655): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 7655): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7655): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 10 Dec 2015 14:12:02 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449756722525], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449756722511]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Validated
,D/ConnectivityService(  735): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  735): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  735):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  735):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  735):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  735): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  735): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  735): calling update connectivity
D/ConnectivityService(  735):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  735):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  735): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  735):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1193): CM callback handler got msg 524290
D/ConnectivityService(  735): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 2270): CM callback handler got msg 524290
,D/ConnectivityService(  735): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1193): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1193): updateDataNetType()
D/StatusBar.NetworkController( 1193): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1193): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1193): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1193): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1193): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1193): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1193): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
,I/QuickConnect( 7655): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7670): MountEmulatedStorage()
E/Zygote  ( 7670): v2
I/libpersona( 7670): KNOX_SDCARD checking this for 10186
I/libpersona( 7670): KNOX_SDCARD not a persona
,I/ActivityManager(  735): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7670 uid=10186 gids={50186, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/SELinux ( 7670): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/ActivityManager(  735): Killing 6770:com.wsomacp/u0a29 (adj 15): bgCount ##41
,I/SELinux ( 7670): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7670): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7670): TimaSignature is unavailable
,D/ActivityThread( 7670): Added TimaKeyStore provider
,D/ResourcesManager( 7670): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7670): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7670): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7670): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 7670): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7670): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/SMD     (  287): DCD ON
,D/RCPManagerService(  735): exchangeData() failure , invalid userId
,D/RCPManagerService(  735): exchangeData() failure , invalid userId
,D/RCPManagerService(  735): exchangeData() failure , invalid userId
,E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService(  735): exchangeData() failure , invalid userId
,E/Zygote  ( 7693): MountEmulatedStorage()
E/Zygote  ( 7693): v2
I/libpersona( 7693): KNOX_SDCARD checking this for 10092
I/libpersona( 7693): KNOX_SDCARD not a persona
,I/SELinux ( 7693): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/ActivityManager(  735): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7693 uid=10092 gids={50092, 9997} abi=armeabi-v7a
I/SELinux ( 7693): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7693): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  735): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  735): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  735): exchangeData() failure , invalid userId
,D/RCPManagerService(  735): exchangeData() failure , invalid userId
,I/art     (  324): Explicit concurrent mark sweep GC freed 8733(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 342us total 13.359ms
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 278us total 10.311ms
,D/TimaKeyStoreProvider( 7693): TimaSignature is unavailable
,D/ActivityThread( 7693): Added TimaKeyStore provider
,I/ActivityManager(  735): Killing 6755:com.google.android.apps.docs/u0a112 (adj 15): bgCount ##41
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 265us total 9.757ms
,D/ConnectivityService(  735): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7337): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 7337): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7337): StateMachine : Current State = 1
,D/ConnectivityService(  735): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  735): Explicit concurrent mark sweep GC freed 73169(4MB) AllocSpace objects, 14(272KB) LOS objects, 16% free, 39MB/47MB, paused 1.455ms total 94.585ms
,D/ResourcesManager( 7693): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/SecurityLogAgent( 7337): StateMachine : Changed Current State = 1
D/BadgeProvider( 7693): onCreate
,D/BadgeProvider( 7693): DatabaseHelper
,I/ActivityManager(  735): Killing 6805:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
,D/ConnectivityService(  735): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  735): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,E/Zygote  ( 7710): MountEmulatedStorage()
,E/Zygote  ( 7710): v2
I/libpersona( 7710): KNOX_SDCARD checking this for 10200
I/libpersona( 7710): KNOX_SDCARD not a persona
,I/ActivityManager(  735): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7710 uid=10200 gids={50200, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7710): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7710): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7710): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  735): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  735): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  735): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  735): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  735): SmartBondingReceiver: wifi ap is not changed
D/ConnectivityService(  735): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  735): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  735): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  735): getSBEnabled() enabled =false
D/SmartBondingService(  735): getSBEnabled() enabled =false
D/SmartBondingService(  735): getSBEnabled() enabled =false
,D/GpsLocationProvider(  735): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  735): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ActivityManager(  735): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
D/ConnectivityService(  735): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  735): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  735): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  735): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  735): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  735): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  735): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  735): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NetworkMonitor( 5862): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  735): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  735): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3602): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 3602): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/ConnectivityService(  735): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  735): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  735): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  735): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1923): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,W/ContextImpl( 1923): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/SmartBondingService(  735): getNetworkEnabled : wifi : true mobile : true
D/ConnectivityService(  735): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  735): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BadgeProvider( 7693): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/TimaKeyStoreProvider( 7710): TimaSignature is unavailable
,D/ActivityThread( 7710): Added TimaKeyStore provider
,D/BadgeProvider( 7693): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/Launcher.Model( 1428): reloadBadges entered.
D/BadgeProvider( 7693): sendNotify, [notify] : null
D/BadgeProvider( 7693): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7693): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7693): update, [UpdateCount] : 1
,D/SecContentProvider2(  735): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  735): mCursor = null
,D/ResourcesManager( 7710): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,I/ActivityManager(  735): Killing 6829:com.samsung.android.app.watchmanagerstub/u0a126 (adj 15): bgCount ##41
,D/ConnectivityService(  735): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  735): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  735): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  735): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  735): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  735): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 5453): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5453): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5453): exit::IDLE
D/InitializeManagerStateMachine( 5453): entry::NETWORK_CHECK
,D/ConnectivityService(  735): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  735): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 5453): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5453): exit::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5453): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5453): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5453): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5453): entry::SUCCESS
D/hcjo    ( 5453): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5453): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5453): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  735): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 5453): exit::SUCCESS
D/InitializeManagerStateMachine( 5453): entry::IDLE
,I/Hs20UtilService( 1310): Starting #8
,I/Hs20UtilService( 1310): Message received 5007
,D/NearbySettings( 1310): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1310): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  735): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1310): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  735): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1310): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1310): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1310): MountReceiver.onReceive - Keep current state
,D/ConnectivityService(  735): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6863): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 1310): Starting #9
,I/Hs20UtilService( 1310): Message received 5007
,D/NearbySettings( 1310): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1310): MountReceiver.onReceive - Keep current state
,D/ConnectivityService(  735): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6863): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 1310): Starting #10
,I/Hs20UtilService( 1310): Message received 5007
,D/NearbySettings( 1310): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1310): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  735): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1310): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/ConnectivityService(  735): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1310): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1310): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1310): MountReceiver.onReceive - Keep current state
,D/ConnectivityService(  735): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6863): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 1310): Starting #11
,I/Hs20UtilService( 1310): Message received 5007
D/NearbySettings( 1310): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1310): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine(  735): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/ConnectivityService(  735): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6863): NETWORK_STATE_CHANGED_ACTION
,I/PCWCLIENTTRACE_PushUtil( 6593): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6593): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6593): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6593): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/SurfaceFlinger(  254): id=17 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService(  735): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=735
,I/DIAGMON_AGENT( 7440): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7440): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/FOTA_Client( 7457): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7457): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7457): [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.511: ( 7472): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.511: ( 7472): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449756723323
,I/KLMS-2.4.511: ( 7472): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  735): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  735): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.511: ( 7472): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.511: ( 7472): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.511: ( 7472): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.511: ( 7472): StateImplV2(): networkChangeListener().END
,D/ConnectivityService(  735): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SO_AGENT( 7503): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/ConnectivityService(  735): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  735): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5099): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 6676): [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
,I/SA      ( 6676): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 6676): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6676): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6676): [OR] == isSIMCardReady false ==
D/ConnectivityService(  735): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6676): [SCU] == networkStateCheck == true
,I/SA      ( 6676): [DM] getCountryCodeFromCSC : PL
I/SA      ( 6676): isChinaCountryCode : false
I/SA      ( 6676): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6676): [OR] == networkStateCheck true ==
,I/SA      ( 6676): [OR] GetMyCountryZoneTask
,I/SA      ( 6676): [OR] onReceive END
,D/ConnectivityService(  735): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
D/ConnectivityService(  735): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6676): [SRS] prepareGetMyCountryZone
,I/SA      ( 6676): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6676): [SSP] query invoked
,I/SCloudBackupReceiver( 7522): Other Intent
,I/SA      ( 6676): [TPMU] GetMccFromDB : null
,I/KnoxUsageLogPro( 7068): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 7068): premStatus:2
,I/KnoxUsageLogPro( 7068): isEulaShown : false
I/KnoxUsageLogPro( 7068): KnoxUsageReceiver onReceive : not Processible, just return
,I/SA      ( 6676): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6676): [TPM] isNoProxy(default) : true
,D/ConnectivityService(  735): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/File    ( 6676): fail readDirectory() errno=2
,D/ConnectivityService(  735): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  735): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 7655): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7655): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7655): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  735): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  735): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  735): exchangeData() failure , invalid userId
D/RCPManagerService(  735): exchangeData() failure , invalid userId
,D/ConnectivityService(  735): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7337): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7337): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7337): StateMachine : Current State = 1
D/ConnectivityService(  735): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 7337): StateMachine : Changed Current State = 1
,D/ConnectivityService(  735): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  735): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  735): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  735): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  735): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  735): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  735): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  735): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 5453): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5453): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5453): exit::IDLE
D/InitializeManagerStateMachine( 5453): entry::NETWORK_CHECK
,D/ConnectivityService(  735): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  735): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 5453): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5453): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5453): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5453): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5453): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5453): entry::SUCCESS
D/hcjo    ( 5453): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5453): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 5453): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/ConnectivityService(  735): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 5453): exit::SUCCESS
D/InitializeManagerStateMachine( 5453): entry::IDLE
,I/SA      ( 6676): [RC New] Execute method=[GET] start
,I/SA      ( 6676): [RC New] Security=[true]
,I/System.out( 6676): Thread-1110(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6676): Thread-1110(ApacheHTTPLog):isShipBuild true
,I/System.out( 6676): Thread-1110(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,E/Watchdog(  735): !@Sync 5
,D/ConnectivityService(  735): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
,D/ConnectivityService(  735): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService(  735): identical MTU - not setting
,D/ConnectivityService(  735): updateSourceRoutes : add source routing for type : 1
,D/ConnectivityService(  735): updateSourceRoutes : add src route for:fe80::ea50:8bff:fede:28a3
,V/        (  282): QcRouteController
D/SmartBondingService(  735): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  735): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  735): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  735): getSBEnabled() enabled =false
,D/SmartBondingService(  735): getSBEnabled() enabled =false
,D/SmartBondingService(  735): getSBEnabled() enabled =false
,V/        (  282): QcRouteController
,W/NetworkManagementService(  735): route cmd failed: 
W/NetworkManagementService(  735): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '74 route replace src v6 wlan0 fe80::ea50:8bff:fede:28a3 2 ::' failed with '400 74 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  735): '
W/NetworkManagementService(  735): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService(  735): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService(  735): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService(  735): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService(  735): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  735): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5625)
W/NetworkManagementService(  735): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5437)
W/NetworkManagementService(  735): 	at com.android.server.ConnectivityService.access$2300(ConnectivityService.java:229)
W/NetworkManagementService(  735): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2382)
W/NetworkManagementService(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  735): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
V/Nat464Xlat(  735): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  735): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  735): calling update connectivity
D/ConnectivityService(  735):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  735):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  735): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  735):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1193): CM callback handler got msg 524295
,D/ConnectivityService(  735): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  735): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  735): calling update connectivity
D/ConnectivityService(  735):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  735):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 2270): CM callback handler got msg 524295
D/ConnectivityService(  735): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  735):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1193): CM callback handler got msg 524295
D/ConnectivityService(  735): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 2270): CM callback handler got msg 524295
,I/jxcore-log( 7266): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 7266): 
,I/SA      ( 6676): [RC New] [v2liruge] api execute + 685
I/SA      ( 6676): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6676): AsyncTask #1 calls detatch()
,I/SA      ( 6676): [TPMU] getNetworkMcc : 
,W/ProcessCpuTracker(  735): Skipping unknown process pid 7254
,W/ProcessCpuTracker(  735): Skipping unknown process pid 7255
,W/ProcessCpuTracker(  735): Skipping unknown process pid 7272
,W/ProcessCpuTracker(  735): Skipping unknown process pid 7282
,W/ProcessCpuTracker(  735): Skipping unknown process pid 7354
,W/ProcessCpuTracker(  735): Skipping unknown process pid 7355
,W/ProcessCpuTracker(  735): Skipping unknown process pid 7357
,W/ProcessCpuTracker(  735): Skipping unknown process pid 7358
,W/ProcessCpuTracker(  735): Skipping unknown process pid 7748
,W/ProcessCpuTracker(  735): Skipping unknown process pid 7751
,I/SA      ( 6676): [SCU] saveMccToPreferece Start
,I/SA      ( 6676): [SCU] RegionMCC : 260
I/SA      ( 6676): [SSP] query invoked
,I/SA      ( 6676): [TPMU] GetMccFromDB : null
,I/SA      ( 6676): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6676): [SCU] saveMccToPreferece End
,I/SA      ( 6676): [RC New] executeRequest [v2liruge] end. 875
,I/SA      ( 6676): [RC New] Execute end
,I/SA      ( 6676): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 6676): [OR] GetMyCountryZoneTask Success
,D/PackageManager(  735): [MSG] WRITE_PACKAGE_RESTRICTIONS
,E/SMD     (  287): DCD ON
,E/WifiStateMachine(  735): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/dhcpcd  ( 7521): wlan0: sending IPv6 Router Solicitation
,D/ConnectivityService(  735): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SurfaceFlinger(  254): id=17 Removed Uoast (8/9)
,D/PowerManagerService(  735): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 735) eventTime = 168453
,D/PowerManagerService(  735): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=735 (0x0)
D/PowerManagerService(  735): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=735, ws=WorkSource{10067}) (elapsedTime=3513)
,I/PowerManagerService(  735): [PWL] Off : 30s ago
,I/GAV4    ( 7560): Thread[GAThread,5,main]: No campaign data found.
,V/AlarmManager(  735): waitForAlarm result :4
,D/SSRM:n  (  735): SIOP:: AP = 350, PST = 339, CUR = 450
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6593): mConnectivityHandler : connected
,D/ConnectivityService(  735): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 6593): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE( 6593): ================================================
,I/CSTORAGE( 6593):  CSTORAGE_SKM_LIB v1.0.6
I/CSTORAGE( 6593): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 6593): [GetString-S]
E/art     ( 6593): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6593): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6593): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 6593): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6593): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6593): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 6593): [ensureRegistration] - No Samsung account
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,I/dhcpcd  ( 7521): wlan0: sending IPv6 Router Solicitation
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,D/PreloadUpdateManagerStateMachine( 5453): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5453): exit::IDLE
D/PreloadUpdateManagerStateMachine( 5453): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5453): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5453): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5453): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5453): entry::IDLE
,D/PreloadUpdateManagerStateMachine( 5453): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5453): exit::IDLE
D/PreloadUpdateManagerStateMachine( 5453): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5453): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/PreloadUpdateManagerStateMachine( 5453): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5453): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5453): entry::IDLE
,I/dhcpcd  ( 7521): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 7521): wlan0: no IPv6 Routers available
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 320, PST = 332, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/BatteryService(  735): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,E/SMD     (  287): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/PowerManagerService(  735): [PWL] Off : 50s ago
,W/Atfwd_Sendcmd(  339): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:n  (  735): SIOP:: AP = 320, PST = 330, CUR = 450
,E/SMD     (  287): DCD ON
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,E/Watchdog(  735): !@Sync 6
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 310, PST = 328, CUR = 450
,V/AlarmManager(  735): waitForAlarm result :4
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON,
,D/SSRM:n  (  735): SIOP:: AP = 310, PST = 325, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): stay LED for fully charged
D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  735): [PWL] Off : 75s ago
,I/Atfwd_Sendcmd(  339): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  339): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 310, PST = 322, CUR = 450
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/BatteryService(  735): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,E/SMD     (  287): DCD ON
,V/AlarmManager(  735): waitForAlarm result :8
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/Watchdog(  735): !@Sync 7
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ClearcutLoggerApiImpl( 1938): disconnect managed GoogleApiClient
,W/Atfwd_Sendcmd(  339): AtCmdFwd service not published, waiting... retryCnt : 1
,D/SSRM:n  (  735): SIOP:: AP = 310, PST = 320, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  735): stay LED for fully charged
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
I/MotionRecognitionService(  735): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  339): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:n  (  735): SIOP:: AP = 300, PST = 318, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  735): stay LED for fully charged
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  735): Plugged
I/MotionRecognitionService(  735): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,I/PowerManagerService(  735): [PWL] Off : 105s ago
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,D/SSRM:n  (  735): SIOP:: AP = 300, PST = 316, CUR = 450
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  339): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  287): DCD ON
,E/Watchdog(  735): !@Sync 8
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 300, PST = 313, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  735): stay LED for fully charged
D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  735): Plugged
I/MotionRecognitionService(  735): setPowerConnected  = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 300, PST = 308, CUR = 450
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/BatteryService(  735): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  339): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,I/PowerManagerService(  735): [PWL] Off : 140s ago
,D/SSRM:n  (  735): SIOP:: AP = 300, PST = 306, CUR = 450
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/BatteryService(  735): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/Watchdog(  735): !@Sync 9
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 300, PST = 304, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  735): stay LED for fully charged
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  339): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 300, PST = 303, CUR = 450
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 300, PST = 302, CUR = 450
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/BatteryService(  735): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService(  735): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  735): TimaServiceHandler.handleMessage what =1
,D/TimaService(  735): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  735): initializing...
,I/TLC_TIMA_PKM_initialize(  735): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  735): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication(  735): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  735): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication(  735): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  735): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  735): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  735): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  735): App is not loaded in QSEE
,D/QSEECOMAPI: (  735): Loaded image: APP id = 4
,I/TZ: qc_tlc_communication(  735): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  735): Trustlet response is completed
,I/jxcore-log( 7266): Connected to the server!
I/jxcore-log( 7266): 
,I/chromium( 7266): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,E/SMD     (  287): DCD ON
,E/Watchdog(  735): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel(  735): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  735): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  735): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  735): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  287): DCD ON
,I/PowerManagerService(  735): [PWL] Off : 180s ago
,D/SSRM:n  (  735): SIOP:: AP = 300, PST = 301, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  735): stay LED for fully charged
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,I/Atfwd_Sendcmd(  339): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  339): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 300, PST = 300, CUR = 450
,E/SMD     (  287): DCD ON
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  735): waitForAlarm result :4
,E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): stay LED for fully charged
,I/ActivityManager(  735): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=7790 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1193): handleTimeUpdate
,E/Zygote  ( 7790): MountEmulatedStorage()
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,E/Zygote  ( 7790): v2
,I/libpersona( 7790): KNOX_SDCARD checking this for 10096
I/libpersona( 7790): KNOX_SDCARD not a persona
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,I/SELinux ( 7790): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7790): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,D/KeyguardEffectViewController( 1193): onReceive action : android.intent.action.TIME_TICK
E/SELinux ( 7790): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/KeyguardEffectViewController( 1193): *** don't update sliding image ***
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/TimaKeyStoreProvider( 7790): TimaSignature is unavailable
,D/ActivityThread( 7790): Added TimaKeyStore provider
,D/DateView( 1193): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1193): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ResourcesManager( 7790): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,I/ActivityManager(  735): Killing 6844:com.samsung.helphub/1000 (adj 15): bgCount ##41
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,D/SSRM:n  (  735): SIOP:: AP = 300, PST = 300, CUR = 450
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,V/AlarmManager(  735): waitForAlarm result :8
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  339): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  735): !@Sync 11
,E/SMD     (  287): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,D/SSRM:n  (  735): SIOP:: AP = 300, PST = 300, CUR = 450
,E/SMD     (  287): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,W/Atfwd_Sendcmd(  339): AtCmdFwd service not published, waiting... retryCnt : 2
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3140): Disconnected process message: 10
,I/MotionRecognitionService(  735): Plugged
I/MotionRecognitionService(  735): setPowerConnected  = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
D/BatteryService(  735): stay LED for fully charged
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 300, PST = 300, CUR = 450
,E/SMD     (  287): DCD ON
,I/PowerManagerService(  735): [PWL] Off : 225s ago
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0,
D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  735): stay LED for fully charged
D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,E/SMD     (  287): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,W/Atfwd_Sendcmd(  339): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:n  (  735): SIOP:: AP = 290, PST = 299, CUR = 450
,E/SMD     (  287): DCD ON
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  735): stay LED for fully charged
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,E/Watchdog(  735): !@Sync 12
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 290, PST = 298, CUR = 450
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0,
D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  735): stay LED for fully charged
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  339): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 290, PST = 297, CUR = 450
,E/SMD     (  287): DCD ON
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 290, PST = 296, CUR = 450
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  735): stay LED for fully charged
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  735): !@Sync 13
,E/SMD     (  287): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,D/SSRM:n  (  735): SIOP:: AP = 290, PST = 295, CUR = 450
,E/SMD     (  287): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,I/PowerManagerService(  735): [PWL] Off : 275s ago
,W/Atfwd_Sendcmd(  339): AtCmdFwd service not published, waiting... retryCnt : 5
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 290, PST = 294, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 290, PST = 293, CUR = 450
,E/SMD     (  287): DCD ON
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
I/MotionRecognitionService(  735): Plugged
I/MotionRecognitionService(  735): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  735): stay LED for fully charged
,E/Watchdog(  735): !@Sync 14
,E/SMD     (  287): DCD ON
,I/Atfwd_Sendcmd(  339): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  339): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:n  (  735): SIOP:: AP = 290, PST = 292, CUR = 450
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  735): stay LED for fully charged
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 290, PST = 291, CUR = 450
,E/SMD     (  287): DCD ON
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/BatteryService(  735): stay LED for fully charged
D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,D/SSRM:n  (  735): SIOP:: AP = 290, PST = 290, CUR = 450
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  339): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  735): !@Sync 15
,E/SMD     (  287): DCD ON
,I/PowerManagerService(  735): [PWL] Off : 330s ago
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 290, PST = 290, CUR = 450
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,W/Atfwd_Sendcmd(  339): AtCmdFwd service not published, waiting... retryCnt : 2
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  735): stay LED for fully charged
D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  287): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/bootchecker(  330): bootchecker wake up!!
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,W/Atfwd_Sendcmd(  339): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:n  (  735): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  287): DCD ON
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  735): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,E/Watchdog(  735): !@Sync 16
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  287): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  735): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  339): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  287): DCD ON
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  735): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  287): DCD ON
,V/AlarmManager(  735): waitForAlarm result :8
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  735): !@Sync 17
,E/SMD     (  287): DCD ON
,I/PowerManagerService(  735): [PWL] Off : 390s ago
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,D/SSRM:n  (  735): SIOP:: AP = 290, PST = 290, CUR = 450
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,W/Atfwd_Sendcmd(  339): AtCmdFwd service not published, waiting... retryCnt : 5
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
I/MotionRecognitionService(  735): Plugged
I/MotionRecognitionService(  735): setPowerConnected  = true
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  735): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  735): setPowerConnected  = true
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  735): stay LED for fully charged
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  287): DCD ON
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  735): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  735): !@Sync 18
,E/SMD     (  287): DCD ON
,I/Atfwd_Sendcmd(  339): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  339): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
I/MotionRecognitionService(  735): Plugged
I/MotionRecognitionService(  735): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  735): stay LED for fully charged
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  287): DCD ON
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  735): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  287): DCD ON
,I/Atfwd_Daemon(  339): Stop the daemon....
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  735): Plugged
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/BatteryService(  735): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  735): !@Sync 19
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 290, PST = 290, CUR = 450
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,I/PowerManagerService(  735): [PWL] Off : 455s ago
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/BatteryService(  735): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/BatteryService(  735): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  287): DCD ON
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService(  735): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  735): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  735): TimaServiceHandler.handleMessage what =1
,E/SMD     (  287): DCD ON
,E/Watchdog(  735): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel(  735): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  735): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  735): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  735): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  735): Plugged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/BatteryService(  735): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  287): DCD ON
,W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,I/ActivityManager(  735): Killing 6880:com.samsung.android.snote:provider/u0a168 (adj 15): bgCount ##41
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/Watchdog(  735): !@Sync 21
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,E/SMD     (  287): DCD ON
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  735): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  287): DCD ON
,I/PowerManagerService(  735): [PWL] Off : 525s ago
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/Watchdog(  735): !@Sync 22
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  735): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3140): Disconnected process message: 10
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  735): stay LED for fully charged
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  287): DCD ON
,E/Watchdog(  735): !@Sync 23
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  735): Plugged
I/MotionRecognitionService(  735): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  735): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/BatteryService(  735): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  287): DCD ON
,E/Watchdog(  735): !@Sync 24
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/BatteryService(  735): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,E/SMD     (  287): DCD ON
,I/PowerManagerService(  735): [PWL] Off : 600s ago
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/BatteryService(  735): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  287): DCD ON
,E/Watchdog(  735): !@Sync 25
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/BatteryService(  735): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/BatteryService(  735): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  287): DCD ON
,E/Watchdog(  735): !@Sync 26
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  735): Plugged
I/MotionRecognitionService(  735): setPowerConnected  = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
D/BatteryService(  735): stay LED for fully charged
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/BatteryService(  735): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,I/PowerManagerService(  735): [PWL] Off : 680s ago
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 289, CUR = 450
,E/SMD     (  287): DCD ON
,E/Watchdog(  735): !@Sync 27
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 288, CUR = 450
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 287, CUR = 450
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  735): Plugged
I/MotionRecognitionService(  735): setPowerConnected  = true
,D/BatteryService(  735): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 286, CUR = 450
,E/SMD     (  287): DCD ON
,E/Watchdog(  735): !@Sync 28
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
D/BatteryService(  735): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 285, CUR = 450
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 284, CUR = 450
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 283, CUR = 450
,E/SMD     (  287): DCD ON
,E/Watchdog(  735): !@Sync 29
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 282, CUR = 450
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 281, CUR = 450
,I/PowerManagerService(  735): [PWL] Off : 765s ago
,V/AlarmManager(  735): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1193): handleTimeUpdate
,D/KeyguardEffectViewController( 1193): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1193): *** don't update sliding image ***
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): stay LED for fully charged
,D/LightsService(  735): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  735): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager(  735): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/DateView( 1193): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/DateView( 1193): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/EventLogService( 2270): Aggregate from 1449755663015 (log), 1449755663015 (data)
,D/LightsService(  735): [SvcLED]  onSensorChanged::light value = 3
,E/LightSensor(  735): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  735): unregisterListener ::   
,D/LightsService(  735): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,D/TimaService(  735): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  735): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  735): TimaServiceHandler.handleMessage what =1
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,I/TLC_TIMA_PKM_measure_kernel(  735): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  735): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  735): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  735): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  735): !@Sync 30
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 290, PST = 281, CUR = 450,
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  735): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 281, CUR = 450
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  735): stay LED for fully charged
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3140): Disconnected process message: 10
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,V/AlarmManager(  735): waitForAlarm result :8
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  735): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,E/Watchdog(  735): !@Sync 31
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 281, CUR = 450
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  735): stay LED for fully charged
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  735): !@Sync 32
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 281, CUR = 450
,I/PowerManagerService(  735): [PWL] Off : 855s ago
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  735): stay LED for fully charged
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  735): Plugged
I/MotionRecognitionService(  735): setPowerConnected  = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  735): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,E/Watchdog(  735): !@Sync 33
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  735): stay LED for fully charged
D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  735): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  735): setPowerConnected  = true
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  735): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  735): !@Sync 34
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/BatteryService(  735): stay LED for fully charged
D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  735): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  735): !@Sync 35
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService(  735): [PWL] Off : 950s ago
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  735): !@Sync 36
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  735): stay LED for fully charged
D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  735): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,E/Watchdog(  735): !@Sync 37
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  735): Plugged
I/MotionRecognitionService(  735): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  735): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  735): stay LED for fully charged
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,E/Watchdog(  735): !@Sync 38
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/BatteryService(  735): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,E/Watchdog(  735): !@Sync 39
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  735): stay LED for fully charged
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,E/SMD     (  287): DCD ON
,I/PowerManagerService(  735): [PWL] Off : 1050s ago
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
I/MotionRecognitionService(  735): Plugged
I/MotionRecognitionService(  735): setPowerConnected  = true
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  735): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/TimaService(  735): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  735): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  735): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService(  735): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  735): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  735): Updating Usage Statistics in DB @ 1449757772326
,I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
,W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
,W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
,W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
,W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
,W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
,W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
,W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
,W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  735): ::getAppControlDB: Exception to create DB
W/System.err(  735): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  735): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  735): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  735): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage(  735): Done Updating Usage Statistics in DB @ 1449757772506
,E/SMD     (  287): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  735): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  735): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  735): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  735): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  735): !@Sync 40
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 290, PST = 281, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  735): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  735): stay LED for fully charged
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  287): DCD ON
,E/Watchdog(  735): !@Sync 41
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  735): stay LED for fully charged
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  735): stay LED for fully charged
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  287): DCD ON
,E/Watchdog(  735): !@Sync 42
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  735): stay LED for fully charged
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  735): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,I/PowerManagerService(  735): [PWL] Off : 1155s ago
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  287): DCD ON
,E/Watchdog(  735): !@Sync 43
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/BatteryService(  735): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): stay LED for fully charged
D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
I/MotionRecognitionService(  735): Plugged
I/MotionRecognitionService(  735): setPowerConnected  = true
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  735): !@Sync 44
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  735): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): stay LED for fully charged
D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
I/MotionRecognitionService(  735): Plugged
I/MotionRecognitionService(  735): setPowerConnected  = true
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  735): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  735): !@Sync 45
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): stay LED for fully charged
D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  735): Plugged
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
I/MotionRecognitionService(  735): setPowerConnected  = true
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  735): Plugged
I/MotionRecognitionService(  735): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  735): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  735): !@Sync 46
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/BatteryService(  735): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,E/SMD     (  287): DCD ON
,I/PowerManagerService(  735): [PWL] Off : 1265s ago
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  735): !@Sync 47
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): stay LED for fully charged
D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3140): Disconnected process message: 10
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
I/MotionRecognitionService(  735): Plugged
I/MotionRecognitionService(  735): setPowerConnected  = true
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  735): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  735): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  735): !@Sync 48
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/BatteryService(  735): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  735): Plugged
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/BatteryService(  735): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  735): Plugged
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/BatteryService(  735): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  735): !@Sync 49
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/BatteryService(  735): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/BatteryService(  735): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/BatteryService(  735): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/TimaService(  735): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  735): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  735): TimaServiceHandler.handleMessage what =1
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,I/TLC_TIMA_PKM_measure_kernel(  735): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  735): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  735): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  735): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  735): !@Sync 50
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): stay LED for fully charged
D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,I/PowerManagerService(  735): [PWL] Off : 1380s ago
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): stay LED for fully charged
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  735): Plugged
I/MotionRecognitionService(  735): setPowerConnected  = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/BatteryService(  735): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  735): !@Sync 51
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  735): stay LED for fully charged
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  735): Plugged
I/MotionRecognitionService(  735): setPowerConnected  = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  735): stay LED for fully charged
D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  735): Plugged
I/MotionRecognitionService(  735): setPowerConnected  = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  735): !@Sync 52
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  735): stay LED for fully charged
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  735): Plugged
I/MotionRecognitionService(  735): setPowerConnected  = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  735): !@Sync 53
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  735): stay LED for fully charged
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  735): Plugged
I/MotionRecognitionService(  735): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3140): Disconnected process message: 10
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): stay LED for fully charged
D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): stay LED for fully charged
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  735): Plugged
I/MotionRecognitionService(  735): setPowerConnected  = true
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/Watchdog(  735): !@Sync 54
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,I/PowerManagerService(  735): [PWL] Off : 1500s ago
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): stay LED for fully charged
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/Watchdog(  735): !@Sync 55
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  735): stay LED for fully charged
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/Watchdog(  735): !@Sync 56
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/BatteryService(  735): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/Watchdog(  735): !@Sync 57
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  735): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  735): stay LED for fully charged
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  735): Plugged
I/MotionRecognitionService(  735): setPowerConnected  = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/Watchdog(  735): !@Sync 58
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  735): stay LED for fully charged
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3140): Disconnected process message: 10
,E/SMD     (  287): DCD ON
,I/PowerManagerService(  735): [PWL] Off : 1625s ago
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  735): Plugged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  735): stay LED for fully charged
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/Watchdog(  735): !@Sync 59
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  735): stay LED for fully charged
D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/NetworkStatsFactory(  735): UpdateStatsForKnox
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  735): Plugged
I/MotionRecognitionService(  735): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  735): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,D/TimaService(  735): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  735): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  735): TimaServiceHandler.handleMessage what =1
,E/SMD     (  287): DCD ON
,V/AlarmManager(  735): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1193): handleTimeUpdate
,I/ProcessStatsService(  735): Prepared write state in 7ms
,D/KeyguardEffectViewController( 1193): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1193): *** don't update sliding image ***
D/LightsService(  735): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  735): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager(  735): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,I/ProcessStatsService(  735): Prepared write state in 19ms
,D/DateView( 1193): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/NetworkStats(  735): performPollLocked(flags=0x3)
,D/NtpTrustedTime(  735): currentTimeMillis() cache hit
,D/NetworkStatsFactory(  735): UpdateStatsForKnox
,D/ConnectivityService(  735): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1193): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/NetworkStats(  735): performPollLocked() took 18ms
,D/NtpTrustedTime(  735): currentTimeMillis() cache hit
,D/NtpTrustedTime(  735): currentTimeMillis() cache hit
D/NtpTrustedTime(  735): currentTimeMillis() cache hit
,I/TLC_TIMA_PKM_measure_kernel(  735): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel(  735): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  735): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  735): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  735): !@Sync 60
,D/LightsService(  735): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  735): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  735): unregisterListener ::   
D/LightsService(  735): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/ProcessStatsService(  735): Pruning old procstats: /data/system/procstats/state-2015-12-09-22-26-07.bin
,D/SSRM:n  (  735): SIOP:: AP = 290, PST = 281, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
I/MotionRecognitionService(  735): Plugged
I/MotionRecognitionService(  735): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  735): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3140): Disconnected process message: 10
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/BatteryService(  735): stay LED for fully charged
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager(  735): waitForAlarm result :8
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/Watchdog(  735): !@Sync 61
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  735): Plugged
I/MotionRecognitionService(  735): setPowerConnected  = true
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/BatteryService(  735): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/BatteryService(  735): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/BatteryService(  735): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/Watchdog(  735): !@Sync 62
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/BatteryService(  735): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,I/PowerManagerService(  735): [PWL] Off : 1755s ago
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/Watchdog(  735): !@Sync 63
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/BatteryService(  735): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3140): Disconnected process message: 10
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/BatteryService(  735): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/Watchdog(  735): !@Sync 64
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,D/BatteryService(  735): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  735): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  735): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  735): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1193): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1193): handleBatteryUpdate
,I/MotionRecognitionService(  735): Plugged
,I/MotionRecognitionService(  735): setPowerConnected  = true
,D/BatteryService(  735): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1193):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1193): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3140): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3140): Disconnected process message: 10
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/Watchdog(  735): !@Sync 65
,E/SMD     (  287): DCD ON
,D/SSRM:n  (  735): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  287): DCD ON
,D/BatteryService(  735): !@BatteryListener : batteryPropertiesChanged!
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 7954): 
D/AndroidRuntime( 7954): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7954): CheckJNI is OFF
D/AndroidRuntime( 7954): readGMSProperty: start
D/AndroidRuntime( 7954): readGMSProperty: already setted!!
D/AndroidRuntime( 7954): readGMSProperty: end
D/AndroidRuntime( 7954): addProductProperty: start
E/AffinityControl( 7954): AffinityControl: registerfunction enter
D/AndroidRuntime( 7954): Calling main entry com.android.commands.pm.Pm
D/PackageManager(  735): START PACKAGE DELETE: observer{871396375}
D/PackageManager(  735): pkg{<packageName>}
D/PackageManager(  735): user{0}
D/PackageManager(  735): caller{2000}
D/PackageManager(  735): flags{3}
D/PersonaManagerService(  735): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  735): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  735): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  735): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  735): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  735): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  735): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  735): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  735): getApplicationUninstallationEnabled
D/ApplicationPolicy(  735): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  735): !@killApplicatoin: 10281, uninstall pkg
I/ActivityManager(  735): Force stopping com.test.thalitest appid=10281 user=-1: uninstall pkg
I/ActivityManager(  735): Killing 7266:com.test.thalitest/u0a281 (adj 0): stop com.test.thalitest
W/PackageSettings(  735): Skipping PackageSetting{18b1162a com.example.hello/10268} due to missing metadata
I/WindowState(  735): WIN DEATH: Window{29006fa1 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  254): id=16 Removed NainActivit (5/8)
I/SurfaceFlinger(  254): id=16 Removed NainActivit (-2/8)
D/PointerIcon(  735): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  735): setMouseCustomIcon IconType is same.101
D/PointerIcon(  735): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  735): setHoveringSpenCustomIcon IconType is same.1
I/SurfaceFlinger(  254): id=16 Removed NainActivit (-2/8)
E/lowmemorykiller(  251): Error writing /proc/4412/oom_score_adj; errno=22
I/ActivityManager(  735): Killing 4412:com.sec.chaton/u0a102 (adj 11): empty for 1807s
I/ActivityManager(  735): Killing 7068:com.sec.knox.bridge/1000 (adj 11): empty for 1807s
I/ActivityManager(  735): Killing 7522:com.samsung.android.scloud.backup/u0a74 (adj 11): empty for 1807s
I/ActivityManager(  735): Killing 6676:com.osp.app.signin/u0a50 (adj 11): empty for 1807s
I/ActivityManager(  735): Killing 6629:com.policydm/1000 (adj 11): empty for 1807s
I/ActivityManager(  735): Killing 7503:com.sec.android.soagent/u0a42 (adj 11): empty for 1807s
I/ActivityManager(  735): Killing 7359:com.vlingo.midas/u0a38 (adj 11): empty for 1807s
I/ActivityManager(  735): Killing 7488:com.samsung.android.app.pinboard:tagService/u0a36 (adj 11): empty for 1807s
I/ActivityManager(  735): Killing 7472:com.samsung.klmsagent/u0a23 (adj 11): empty for 1807s
I/ActivityManager(  735): Killing 7457:com.sec.android.fotaclient/u0a14 (adj 11): empty for 1807s
I/ActivityManager(  735): Killing 7440:com.sec.android.diagmonagent/1000 (adj 11): empty for 1807s
I/ActivityManager(  735): Killing 7421:com.sec.android.cloudagent/u0a4 (adj 13): empty for 1807s
I/ActivityManager(  735): Killing 6593:com.sec.pcw.device/1000 (adj 13): empty for 1807s
I/ActivityManager(  735): Killing 6863:com.samsung.android.snote/u0a168 (adj 13): empty for 1807s
I/ActivityManager(  735): Killing 7693:com.sec.android.provider.badge/u0a92 (adj 13): empty for 1808s
I/ActivityManager(  735): Killing 1716:com.google.process.gapps/u0a15 (adj 13): empty for 1809s
I/ActivityManager(  735): Killing 7179:com.sec.android.widgetapp.activeapplicationwidget/u0a182 (adj 13): empty for 1834s
E/SMD     (  287): DCD ON
I/ActivityManager(  735): Killing 7163:com.sec.android.widgetapp.dualclockdigital/u0a115 (adj 13): empty for 1858s
I/ActivityManager(  735): Killing 7148:com.sec.android.widgetapp.digitalclock/u0a109 (adj 13): empty for 1858s
I/ActivityManager(  735): Killing 6696:com.android.mms/u0a55 (adj 13): empty for 1858s
I/ActivityManager(  735): Killing 5927:com.sec.android.gallery3d/u0a53 (adj 13): empty for 1858s
I/ActivityManager(  735): Killing 6148:com.android.vending/u0a33 (adj 15): empty for 1863s
I/ActivityManager(  735): Killing 7083:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty for 1863s
I/ActivityManager(  735): Killing 6108:com.sec.android.app.controlpanel/u0a134 (adj 15): empty for 1864s
I/ActivityManager(  735): Killing 7053:com.samsung.android.app.FileShareServer/u0a88 (adj 15): empty for 1864s
I/ActivityManager(  735): Killing 6066:com.samsung.android.app.galaxyfinder/u0a39 (adj 15): empty for 1864s
I/ActivityManager(  735): Killing 6029:sstream.app/u0a25 (adj 15): empty for 1864s
I/ActivityManager(  735): Killing 6969:com.sec.enterprise.knox.cloudmdm.smdms/u0a201 (adj 15): empty for 1875s
I/ActivityManager(  735): Killing 6897:com.sec.kidsplat.installer/u0a189 (adj 15): empty for 1890s
I/ActivityManager(  735):   Force finishing activity ActivityRecord{253b0b43 u0 com.test.thalitest/.MainActivity t4}
D/FocusedStackFrame(  735): Set to : 0
W/ActivityManager(  735): Spurious death for ProcessRecord{18aa004 7266:com.test.thalitest/u0a281}, curProc for 7266: null
W/libprocessgroup(  735): failed to open /acct/uid_10015/pid_1716/cgroup.procs: No such file or directory
W/libprocessgroup(  735): failed to open /acct/uid_10102/pid_4412/cgroup.procs: No such file or directory
W/libprocessgroup(  735): failed to open /acct/uid_1000/pid_7068/cgroup.procs: No such file or directory
W/libprocessgroup(  735): failed to open /acct/uid_10074/pid_7522/cgroup.procs: No such file or directory
W/libprocessgroup(  735): failed to open /acct/uid_10050/pid_6676/cgroup.procs: No such file or directory
W/libprocessgroup(  735): failed to open /acct/uid_1000/pid_6629/cgroup.procs: No such file or directory
W/libprocessgroup(  735): failed to open /acct/uid_10042/pid_7503/cgroup.procs: No such file or directory
W/libprocessgroup(  735): failed to open /acct/uid_10038/pid_7359/cgroup.procs: No such file or directory
W/libprocessgroup(  735): failed to open /acct/uid_10036/pid_7488/cgroup.procs: No such file or directory
W/libprocessgroup(  735): failed to open /acct/uid_10023/pid_7472/cgroup.procs: No such file or directory
W/libprocessgroup(  735): failed to open /acct/uid_10014/pid_7457/cgroup.procs: No such file or directory
W/libprocessgroup(  735): failed to open /acct/uid_1000/pid_7440/cgroup.procs: No such file or directory
W/libprocessgroup(  735): failed to open /acct/uid_10004/pid_7421/cgroup.procs: No such file or directory
W/libprocessgroup(  735): failed to open /acct/uid_1000/pid_6593/cgroup.procs: No such file or directory
W/libprocessgroup(  735): failed to open /acct/uid_10168/pid_6863/cgroup.procs: No such file or directory
W/libprocessgroup(  735): failed to open /acct/uid_10092/pid_7693/cgroup.procs: No such file or directory
W/libprocessgroup(  735): failed to open /acct/uid_10115/pid_7163/cgroup.procs: No such file or directory
D/CountryDetector(  735): No listener is left
W/libprocessgroup(  735): failed to open /acct/uid_10182/pid_7179/cgroup.procs: No such file or directory
W/libprocessgroup(  735): failed to open /acct/uid_10109/pid_7148/cgroup.procs: No such file or directory
W/libprocessgroup(  735): failed to open /acct/uid_10055/pid_6696/cgroup.procs: No such file or directory
W/libprocessgroup(  735): failed to open /acct/uid_10053/pid_5927/cgroup.procs: No such file or directory
W/libprocessgroup(  735): failed to open /acct/uid_10033/pid_6148/cgroup.procs: No such file or directory
W/libprocessgroup(  735): failed to open /acct/uid_1000/pid_7083/cgroup.procs: No such file or directory
W/libprocessgroup(  735): failed to open /acct/uid_10134/pid_6108/cgroup.procs: No such file or directory
W/libprocessgroup(  735): failed to open /acct/uid_10088/pid_7053/cgroup.procs: No such file or directory
W/libprocessgroup(  735): failed to open /acct/uid_10039/pid_6066/cgroup.procs: No such file or directory
W/libprocessgroup(  735): failed to open /acct/uid_10025/pid_6029/cgroup.procs: No such file or directory
W/libprocessgroup(  735): failed to open /acct/uid_10201/pid_6969/cgroup.procs: No such file or directory
W/libprocessgroup(  735): failed to open /acct/uid_10189/pid_6897/cgroup.procs: No such file or directory
D/ConnectivityService(  735): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ActivityManager(  735): Force stopping com.test.thalitest appid=10281 user=0: pkg removed
I/art     ( 1645): Explicit concurrent mark sweep GC freed 1918(85KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 18MB/31MB, paused 529us total 23.788ms
D/ResourcesManager(  735): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
I/InputReader(  735): Reconfiguring input devices.  changes=0x00000010
E/SamsungIME( 1684): mOCRHelper is null
W/GeofencerStateMachine( 1938): Ignoring removeGeofence because network location is disabled.
D/ResourcesManager( 1428): creating new AssetManager and set to /system/priv-app/StoryAlbumWidget/StoryAlbumWidget.apk
W/ResourcesManager( 1428): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1428): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
I/art     ( 4543): Explicit concurrent mark sweep GC freed 38758(2MB) AllocSpace objects, 9(144KB) LOS objects, 40% free, 15MB/26MB, paused 417us total 42.352ms
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 1428): creating new AssetManager and set to /system/app/AccuweatherPhone2013_H_LMR/AccuweatherPhone2013_H_LMR.apk
W/ResourcesManager( 1428): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1428): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1428): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
I/art     ( 2270): Explicit concurrent mark sweep GC freed 6375(327KB) AllocSpace objects, 2(32KB) LOS objects, 25% free, 22MB/30MB, paused 833us total 83.903ms
D/ResourcesManager( 1428): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
W/ResourcesManager( 1428): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1428): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
E/Zygote  ( 7992): MountEmulatedStorage()
E/Zygote  ( 7992): v2
I/libpersona( 7992): KNOX_SDCARD checking this for 10023
I/libpersona( 7992): KNOX_SDCARD not a persona
I/ActivityManager(  735): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7992 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 7992): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7992): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7992): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/art     (  735): Explicit concurrent mark sweep GC freed 18971(1666KB) AllocSpace objects, 12(192KB) LOS objects, 17% free, 38MB/46MB, paused 1.876ms total 144.884ms
I/art     (  735): WaitForGcToComplete blocked for 60.719ms for cause Explicit
D/ResourcesManager(  735): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/ResourcesManager(  735): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager(  735): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
D/TimaKeyStoreProvider( 7992): TimaSignature is unavailable
D/ActivityThread( 7992): Added TimaKeyStore provider
D/ResourcesManager(  735): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/SurfaceWidgetView( 1428): destroyHardwareResources():852467732
V/WindowOrientationListener(  735): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  735): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  735): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  735): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  735): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/Launcher( 1428): onRestart, Launcher: 538562955
D/Launcher( 1428): onStart, Launcher: 538562955
D/Launcher.HomeView( 1428): onStart
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1797): [237392/8] Surface widget visibility changed visibility = true on instance = 1
V/ActivityThread( 1428): updateVisibility : ActivityRecord{3b12b985 token=android.os.BinderProxy@34896b66 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/SurfaceWidget.Renderer( 1797): [237392/8] SurfaceWidget drawing first frame
D/accuweather( 1797): [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
D/ResourcesManager(  735): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
I/SurfaceFlinger(  254): id=18 createSurf (1080x1920),1 flag=4, Mauncher
D/ResourcesManager(  735): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/StatusBarManagerService(  735): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/ResourcesManager( 7992): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
D/StatusBarManagerService(  735): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/ResourcesManager(  735): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/PointerIcon(  735): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  735): setMouseCustomIcon IconType is same.101
D/PointerIcon(  735): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  735): setHoveringSpenCustomIcon IconType is same.1
D/ResourcesManager(  735): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
D/ResourcesManager(  735): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager(  735): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager(  735): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager(  735): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager(  735): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
I/KLMS-2.4.511: ( 7992): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/ResourcesManager(  735): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/SecContentProvider2(  735): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  735): mCursor = null
I/KLMS-2.4.511: ( 7992): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1449758533208
I/KLMS-2.4.511: ( 7992): MainReciver(): PACKAGE_REMOVED
I/KLMS-2.4.511: ( 7992): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
D/RegisteredServicesCache( 1411): empty dynamic service
D/ResourcesManager(  735): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
D/InputMethodManagerService(  735): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/ResourcesManager(  735): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
W/InputMethodManagerService(  735): Got RemoteException sending setActive(false) notification to pid 7266 uid 10281
D/ResourcesManager(  735): creating new AssetManager and set to /system/app/talkback/talkback.apk
D/ResourcesManager(  735): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
W/ContextImpl(  735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/ResourcesManager(  735): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager(  735): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  735): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  735): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  735): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager(  735): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager(  735): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  735): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  735): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
I/Timeline(  735): Timeline: Activity_windows_visible id: ActivityRecord{6bc6ef3 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:1974995
D/ResourcesManager(  735): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/ResourcesManager(  735): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ResourcesManager(  735): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/EnterpriseDeviceManagerService(  735): Package has changed for user 0
D/EnterpriseDeviceManagerService(  735): Admin package name: com.google.android.gms
D/ResourcesManager(  735): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
I/art     (  735): Explicit concurrent mark sweep GC freed 13435(763KB) AllocSpace objects, 0(0B) LOS objects, 17% free, 38MB/46MB, paused 2.626ms total 270.569ms
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  735): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
E/Zygote  ( 8013): MountEmulatedStorage()
E/Zygote  ( 8013): v2
I/libpersona( 8013): KNOX_SDCARD checking this for 10116
I/libpersona( 8013): KNOX_SDCARD not a persona
D/RCPManagerService(  735): PackageReceiver onReceive()
I/HarmonyEASService(  735): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/ActivityManager(  735): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8013 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
D/KnoxMUMContainerPolicy(  735): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  735): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/ActivityManager(  735): Killing 7544:com.android.chrome/u0a104 (adj 15): empty for 1809s
D/JobSchedulerService(  735): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  735): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  735): uID is 10281
V/EnterpriseBillingPolicy(  735): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  735): getProfileForApplication - enter
W/Resources(  735): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
V/EnterpriseBillingPolicyStorage(  735): getProfileForApplication - exit null
D/ResourcesManager(  735): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
V/EnterpriseBillingPolicy(  735): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  735): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  735): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  735): getBillingProfileForVpnEngine - end - null
W/Resources(  735): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  735): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  735): creating new AssetManager and set to /system/app/Music2/Music2.apk
I/SELinux ( 8013): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 8013): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 8013): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(  735): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
W/Resources(  735): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  735): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/TimaKeyStoreProvider( 8013): TimaSignature is unavailable
D/ActivityThread( 8013): Added TimaKeyStore provider
D/ResourcesManager(  735): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
W/Resources(  735): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  735): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
W/Resources(  735): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  735): creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
W/Resources(  735): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  735): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  735): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/Resources(  735): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  735): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  735): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  735): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  735): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
W/Resources(  735): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  735): creating new AssetManager and set to /system/app/Maps/Maps.apk
D/ResourcesManager(  735): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  735): creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
D/PackageManager(  735): delete codoeFile: 
I/AASAUninstall(  735):  com.test.thalitest not target!
D/PackageManager(  735): result of delete: 1{871396375}
D/AndroidRuntime( 7954): Shutting down VM
D/ResourcesManager(  735): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
W/Resources(  735): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  735): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  735): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
W/ResourcesManager(  735): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  735): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  735): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources(  735): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/libprocessgroup(  735): failed to open /acct/uid_10104/pid_7544/cgroup.procs: No such file or directory
D/ResourcesManager(  735): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
D/ResourcesManager(  735): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/TaskPersister(  735): removeObsoleteFile: deleting file=4_task.xml
D/ResourcesManager( 8013): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/ResourcesManager(  735): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
D/elm:14491( 8013): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14491( 8013): ELMEngine.ELMEngine( context ).
W/Resources(  735): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:14491( 8013): MDMBridge.setEnterpriseBridge()
W/Resources(  735): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  735): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
D/elm:14491( 8013): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  735): checkUser: useridlist=null, currentuser=0
W/Resources(  735): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  735): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/elm:14491( 8013): ElmAgentService : onCreate()
D/ResourcesManager(  735): creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
D/elm:14491( 8013): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14491( 8013): MainReceiver.listeningToPackageRemoved()
D/elm:14491( 8013): MDMBridge.getInstance()
D/elm:14491( 8013): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14491( 8013): MDMBridge.getAllLicenseInfoFromSDK()
W/Resources(  735): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  735): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
W/Resources(  735): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  735): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  735): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
W/Resources(  735): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  735): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  735): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
W/Resources(  735): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}

```
