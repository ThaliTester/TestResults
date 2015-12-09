#### Test 50650278d0426ce_thali05_samsung-SM-N9005 Logs


```
--------- beginning of system
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
--------- beginning of main
E/SMD     (  291): DCD ON
,D/AndroidRuntime( 7512): 
D/AndroidRuntime( 7512): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7512): CheckJNI is OFF
D/AndroidRuntime( 7512): readGMSProperty: start
D/AndroidRuntime( 7512): readGMSProperty: already setted!!
D/AndroidRuntime( 7512): readGMSProperty: end
D/AndroidRuntime( 7512): addProductProperty: start
E/AffinityControl( 7512): AffinityControl: registerfunction enter
D/AndroidRuntime( 7512): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  901): inState():  stateMachine is null !!
I/PersonaManagerService(  901): PersonaId don't exist
I/ActivityManager(  901): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  901): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  901): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  901): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager(  901): mDVFSHelper.acquire()
D/FocusedStackFrame(  901): Set to : 0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  901): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7527 uid=10275 gids={50275, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 7527): MountEmulatedStorage()
E/Zygote  ( 7527): v2
I/libpersona( 7527): KNOX_SDCARD checking this for 10275
I/libpersona( 7527): KNOX_SDCARD not a persona
D/PointerIcon(  901): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  901): setMouseCustomIcon IconType is same.101
D/PointerIcon(  901): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  901): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7512): Shutting down VM
I/SELinux ( 7527): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7527): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7527): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7527): TimaSignature is unavailable
D/ActivityThread( 7527): Added TimaKeyStore provider
V/WindowOrientationListener(  901): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  901): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  901): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  901): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  901): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager(  901): Display changed displayId=0
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SurfaceWidgetView( 1447): destroyHardwareResources():284766507
D/ResourcesManager( 7527): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SurfaceFlinger(  257): id=14 Removed Mauncher (5/8)
I/SurfaceFlinger(  257): id=14 Removed Mauncher (-2/8)
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1994): [237392/8] Surface widget visibility changed visibility = false on instance = 1
V/ActivityThread( 1447): updateVisibility : ActivityRecord{23911769 token=android.os.BinderProxy@332fb3e5 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1447): onTrimMemory. Level: 20
,I/WebViewFactory( 7527): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
D/ResourcesManager( 7527): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader( 7527): Loading: webviewchromium
I/LibraryLoader( 7527): Time to load native libraries: 5 ms (timestamps 3983-3988)
I/LibraryLoader( 7527): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7527): Binding Chromium to main looper Looper (main, tid 1) {366ba917}
I/LibraryLoader( 7527): Expected native library version number "",actual native library version number ""
I/chromium( 7527): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7527): Initializing chromium process, renderers=0
W/art     ( 7527): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7527): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7527): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46780 len=2953
I/chromium( 7527): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229536 len:643667
I/Adreno-EGL( 7527): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 7527): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7527): Build Date: 11/19/14 Wed
I/Adreno-EGL( 7527): Local Branch: mybranch5813579
I/Adreno-EGL( 7527): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 7527): Local Patches: NONE
I/Adreno-EGL( 7527): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
W/chromium( 7527): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7527): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7527): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7527): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7527): CordovaWebView is running on device made by: samsung
W/art     ( 7527): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7527): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager(  901): Activity pause timeout for ActivityRecord{394b7b6a u0 com.test.thalitest/.MainActivity t4}
D/Activity( 7527): performCreate Call secproduct feature valuefalse
D/Activity( 7527): performCreate Call debug elastic valuetrue
D/OpenGLRenderer( 7527): Render dirty regions requested: true
D/Atlas   ( 7527): Validating map...
D/ActivityManager(  901): post active user change for 0
D/KnoxTimeoutHandler(  901): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  901): handleActiveUserChange for user 0
V/ActivityThread( 7527): updateVisibility : ActivityRecord{1d79e334 token=android.os.BinderProxy@3b07446 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
I/SurfaceFlinger(  257): id=16 createSurf (1x1),1 flag=404, NainActivit
D/StatusBarManagerService(  901): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  901): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon(  901): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  901): setMouseCustomIcon IconType is same.101
D/PointerIcon(  901): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  901): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer( 7527): Initialized EGL, version 1.4
I/OpenGLRenderer( 7527): HWUI protection enabled for context ,  &this =0xb3a5ab28 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 7527): Enabling debug mode 0
D/InputMethodManagerService(  901): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/Timeline(  901): Timeline: Activity_windows_visible id: ActivityRecord{394b7b6a u0 com.test.thalitest/.MainActivity t4} time:154485
W/ActivityManager(  901): mDVFSHelper.release()
W/IInputConnectionWrapper( 7527): showStatusIcon on inactive InputConnection
I/Timeline( 7527): Timeline: Activity_idle id: android.os.BinderProxy@3b07446 time:154493
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/JsMessageQueue( 7527): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 7527): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1358070016
,D/JX-Cordova( 7527): jxcore cordova android initializing
,D/SSRM:n  (  901): SIOP:: AP = 320, PST = 329, CUR = 450
,E/SMD     (  291): DCD ON
,W/jxcore-log( 7527): Initializing JXcore engine
,W/jxcore-log( 7527): JXcore engine is ready
,W/jxcore-log( 7527): Starting JXcore engine
,E/auditd  ( 1753): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  901): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  901): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,D/SecurityLogAgent( 7124):  SeDenialReceiver : Intent Received : android.intent.action.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7124):  SeDenialReceiver : File path = null
,W/jxcore-log( 7527): Platform android
W/jxcore-log( 7527): 
,W/jxcore-log( 7527): Process ARCH arm
W/jxcore-log( 7527): 
,I/jxcore-log( 7527): JXcore Cordova bridge is ready!
I/jxcore-log( 7527): 
,W/jxcore-log( 7527): JXcore engine is started
,I/jxcore-log( 7527): Toggling radios to true
I/jxcore-log( 7527): 
,D/BluetoothAdapter( 7527): enable()
,D/BluetoothAdapter( 7527): enable(): BT is already enabled..!
,I/WifiManager( 7527): packageName : com.test.thalitest
,D/SecContentProvider(  901): uri = 18 selection = isWifiEnabled
D/SecContentProvider2(  901): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  901): mCursor = null
,D/WifiService(  901): setWifiEnabled: true pid=7527, uid=10275
W/ActivityManager(  901): Permission Denial: getCurrentUser() from pid=7527, uid=10275 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  901): Failed getting userId using ActivityManagerNative
W/WifiService(  901): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7527, uid=10275 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  901): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23057)
W/WifiService(  901): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2181)
W/WifiService(  901): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2169)
W/WifiService(  901): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  901): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider(  901): name = wifi_on
,I/WifiService(  901): disconnect: pid=7527, uid=10275
,I/wpa_supplicant( 1301): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7527): Radios toggled
I/jxcore-log( 7527): 
,I/wpa_supplicant( 1301): CTRL-EVENT-DISCONNECTED bssid=C0.AA.4A reason=3 locally_generated=1
,I/wpa_supplicant( 1301): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 1301): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.4A SSID=4E473730303567
I/wpa_supplicant( 1301): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  901): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1301): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1301): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1301): Disconnected - do not scan
I/wpa_supplicant( 1301): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiConfigStore(  901): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  901): do suspend true
,D/WifiP2pService(  901): InactiveState{ what=143375 }
,D/WifiP2pService(  901): P2pEnabledState{ what=143375 }
,D/CommandListener(  285): Clearing all IP addresses on wlan0
D/StatusBar.NetworkController( 1192): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1192): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
,V/NativeCrypto( 1862): Read error: ssl=0x9b8f1e00: I/O error during system call, Connection timed out
V/NativeCrypto( 1862): SSL shutdown failed: ssl=0x9b8f1e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10015
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): ValidatedState{ when=-1ms what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): DefaultState{ when=-1ms what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/System.out(  901): (HTTPLog)-Static: isSBSettingEnabled false
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/WifiConfigStore(  901): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/ConnectivityService(  901): updateNetworkInfo()
,D/ConnectivityService(  901): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  901): updateNetworkInfo()
D/ConnectivityService(  901): ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
D/ConnectivityService(  901): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
D/NetUtils(  901): android_net_utils_resetConnections in env=0xa939d320 clazz=0x9addc98c iface=wlan0 mask=0x3
,I/WifiTrafficPoller(  901): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1192): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1192): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1192): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1192): applyOpen
,D/StatusBar.NetworkController( 1192): refreshSignalCluster - setNWBoosterIndicators(false)
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
D/StatusBar.NetworkController( 1192): applyOpen
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
D/StatusBar.NetworkController( 1192): refreshSignalCluster - setNWBoosterIndicators(false)
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,D/StatusBar.NetworkController( 1192): applyOpen
D/StatusBar.NetworkController( 1192): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1192): applyOpen
,I/qtaguid (  901): Tagging socket 381 with tag ffffffff00000000{4294967295,0} uid 10015, pid: 901, getuid(): 1000
,E/WifiStateMachine(  901): Start Disconnecting Watchdog 1
,I/ActivityManager(  901): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.samsung.myplace.WIFINotificationHandler: pid=7609 uid=10038 gids={50038, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/wpa_supplicant( 1301): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1301): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1301): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1301): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1301): First Scan Start
,E/Zygote  ( 7609): MountEmulatedStorage()
E/Zygote  ( 7609): v2
I/libpersona( 7609): KNOX_SDCARD checking this for 10038
I/libpersona( 7609): KNOX_SDCARD not a persona
,E/native  (  901): do suspend true
,I/System.out(  901): (HTTPLog)-Static: isSBSettingEnabled false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): Validated
,I/wpa_supplicant( 1301): Scan requested (ret=0) - scan timeout 30 seconds
,I/SELinux ( 7609): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7609): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7609): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/WifiP2pService(  901): InactiveState{ what=143375 }
,D/WifiP2pService(  901): P2pEnabledState{ what=143375 }
,V/AlarmManager(  901):  next == MAX_VALUE
,D/StatusBar.NetworkController( 1192): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1192): onWifiSignalChanged enabled=true enabledDesc:null
D/CommandListener(  285): Clearing all IP addresses on wlan0
,I/WifiTrafficPoller(  901): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1192): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1192): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiNetworkAgent(  901): NetworkAgent: NetworkAgent channel lost
,D/SecContentProvider2(  901): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  901): mCursor = null
,D/SecContentProvider2(  901): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  901): mCursor = null
,D/TimaKeyStoreProvider( 7609): TimaSignature is unavailable
,D/ActivityThread( 7609): Added TimaKeyStore provider
,D/ResourcesManager( 7609): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,W/ResourcesManager( 7609): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ConnectivityService(  901): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService(  901): calling update connectivity
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/EntConnectivity(  901): Not allowed due to - mEnabled false
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  901): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1192): CM callback handler got msg 524292
D/ConnectivityService(  901): sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,V/Nat464Xlat(  901): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): Disconnected - quitting
,D/ConnectivityService(  901): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  901): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1420): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CSLegacyTypeTracker(  901): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::ea50:8bff:fede:28a3/64,192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  901): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService(  901): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityManager.CallbackHandler( 2181): CM callback handler got msg 524292
D/ConnectivityService(  901): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  901): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/Tethering(  901): MasterInitialState.processMessage what=3
V/NetworkStats(  901): updateIfacesLocked()
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
V/NetworkStats(  901): performPollLocked(flags=0x1)
D/SmartBondingService(  901): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  901): getSBEnabled() enabled =false
D/NetworkStatsFactory(  901): UpdateStatsForKnox
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  901): getSBEnabled() enabled =false
D/StatusBar.NetworkController( 1192): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1192): updateDataNetType()
D/StatusBar.NetworkController( 1192): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1192): updateLTEICONDataNetType:0
D/SmartBondingService(  901): getSBEnabled() enabled =false
,E/ConnectivityService(  901): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::ea50:8bff:fede:28a3/64,192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,V/NetworkStats(  901): performPollLocked() took 5ms
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
,D/SmartBondingService(  901): getNetworkEnabled : wifi : true mobile : true
,D/NtpTrustedTime(  901): currentTimeMillis() cache hit
,D/NtpTrustedTime(  901): currentTimeMillis() cache hit
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
,V/NetworkStats(  901): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1192): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1192): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1192): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1192): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1192): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1192): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1192): applyOpen
,D/StatusBar.NetworkController( 1192): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1192): applyOpen
D/StatusBar.NetworkController( 1192): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1192): applyOpen
D/StatusBar.NetworkController( 1192): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1192): applyOpen
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
,I/VlingoApplication( 7609): VlingoApplication appVersion ='11.2.2.0.37649', ro.csc.sales_code=XEO
,I/PhenotypeConfigurator( 1862): Scheduling Phenotype for one-off execution 13759 seconds from now (1449681224301)
,D/GetConfigurationSnapshotOperation( 1862): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,E/BluetoothHeadset( 7609): BTStateChangeCB is registed
,E/BluetoothHeadset( 7609): BluetoothHeadset service is binded
,I/PhenotypeFlagCommitter( 1862): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1862): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  901): Killing 6716:com.sec.android.app.soundalive/u0a64 (adj 15): bgCount ##41
,I/Hs20UtilService( 1313): Starting #6
I/Hs20UtilService( 1313): Message received 5007
,D/NearbySettings( 1313): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1313): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1313): DMSUtil.isNetworkConnected - P2P: IDLE
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1313): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1313): MountReceiver.mPrefHandler - 7002
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SettingsProvider(  901): name = driving_mode_on
,D/SettingsProvider(  901): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  901): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  901): selectionArgs: false
D/SettingsProvider(  901): selectionArgs: 10038
D/SecContentProvider(  901): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  901): ret = -1
,D/BluetoothManager( 7609): [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.media.ACTION_SCO_AUDIO_STATE_UPDATED
,I/art     (  901): Explicit concurrent mark sweep GC freed 80576(4MB) AllocSpace objects, 32(1840KB) LOS objects, 17% free, 38MB/46MB, paused 1.317ms total 96.078ms
,E/SignOutReceiver( 6855): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 1313): Starting #7
,I/Hs20UtilService( 1313): Message received 5007
,D/NearbySettings( 1313): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1313): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1313): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1313): MountReceiver.mPrefHandler - 7002
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6855): NETWORK_STATE_CHANGED_ACTION
,D/LocationManagerService(  901): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  901): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  901): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  901): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  901): getSBEnabled() enabled =false
D/SmartBondingService(  901): getSBEnabled() enabled =false
D/SmartBondingService(  901): getSBEnabled() enabled =false
,I/ApplicationPolicy(  901): updateDataUsageMap
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GpsLocationProvider(  901): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  901): getNetworkEnabled : wifi : true mobile : true
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3457): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5849): type=WIFI subType= reason=null isConnected=false
,I/DBG_DM  ( 3457): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/Zygote  ( 7662): MountEmulatedStorage()
,E/Zygote  ( 7662): v2
I/libpersona( 7662): KNOX_SDCARD checking this for 1000
I/libpersona( 7662): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7662 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7662): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7662): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7662): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7662): TimaSignature is unavailable
,D/ActivityThread( 7662): Added TimaKeyStore provider
,D/ResourcesManager( 7662): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/PCWCLIENTTRACE_LOG( 7662): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 7662): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 7662): new DMDBOpenHelper instance
I/PCWCLIENTTRACE_PushUtil( 7662): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7662): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7662): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7662): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
I/System.out( 1862): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1862): (HTTPLog)-Static: isShipBuild true
I/System.out( 1862): (HTTPLog)-Thread-253-1036422306: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1862): (HTTPLog)-Static: isSBSettingEnabled false
I/PCWCLIENTTRACE_SYSTEMReceiver( 7662): noConnectivity : true
,I/ActivityManager(  901): Killing 5583:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
,D/Uploader( 1862): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/LocationManagerService(  901): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7680): MountEmulatedStorage()
E/Zygote  ( 7680): v2
I/libpersona( 7680): KNOX_SDCARD checking this for 10004
I/libpersona( 7680): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7680 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7680): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7680): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7680): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/SMD     (  291): DCD ON
,D/TimaKeyStoreProvider( 7680): TimaSignature is unavailable
,D/ActivityThread( 7680): Added TimaKeyStore provider
,I/System.out( 1862): (HTTPLog)-Static: isSBSettingEnabled false
,D/Uploader( 1862): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/ResourcesManager( 7680): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,D/LocationManagerService(  901): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1862): (HTTPLog)-Static: isSBSettingEnabled false
,D/Uploader( 1862): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,V/AlarmManager(  901):  next == MAX_VALUE
,I/ActivityManager(  901): Killing 6761:com.wsomacp/u0a29 (adj 15): bgCount ##41
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7697): MountEmulatedStorage()
E/Zygote  ( 7697): v2
I/libpersona( 7697): KNOX_SDCARD checking this for 1000
I/libpersona( 7697): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7697 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7697): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7697): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7697): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7697): TimaSignature is unavailable
,D/ActivityThread( 7697): Added TimaKeyStore provider
,D/ResourcesManager( 7697): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT( 7697): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7697): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,I/DIAGMON_AGENT( 7697): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7697): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7697): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT( 7697): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/FOTA_Client( 6966): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 6966): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/wpa_supplicant( 1301): nl80211: Received scan results (3 BSSes)
,I/wpa_supplicant( 1301): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 1301): Trying to associate with C0.AA.4A (SSID='4E473730303567' freq=5220 MHz)
I/wpa_supplicant( 1301): wlan0: State: SCANNING -> ASSOCIATING
,I/wpa_supplicant( 1301): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E473730303567
,I/FOTA_Client( 6966): [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,D/SecContentProvider2(  901): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  901): mCursor = null
,I/KLMS-2.4.511: ( 6985): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.511: ( 6985): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449681225372
,I/KLMS-2.4.511: ( 6985): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.511: ( 6985): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.511: ( 6985): StateImplV2(): networkChangeListener().END
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,I/wpa_supplicant( 1301): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1301): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E473730303567
,I/wpa_supplicant( 1301): Associated with C0.AA.4A
,D/SecContentProvider2(  901): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  901): mCursor = null
,E/Zygote  ( 7715): MountEmulatedStorage()
I/libpersona( 7715): KNOX_SDCARD checking this for 10036
E/Zygote  ( 7715): v2
I/libpersona( 7715): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.samsung.android.app.pinboard:tagService for broadcast com.samsung.android.app.pinboard/.service.TagReadyReceiver: pid=7715 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/wpa_supplicant( 1301): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1301): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.4A SSID=4E473730303567
,I/ActivityManager(  901): Killing 6745:com.google.android.apps.docs/u0a112 (adj 15): bgCount ##41
,I/wpa_supplicant( 1301): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1301): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1301): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.4A SSID=4E473730303567
,I/wpa_supplicant( 1301): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1301): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1301): CTRL-EVENT-CONNECTED - Connection to C0.AA.4A completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1301): Blacklist: Clear (temp) 
I/wpa_supplicant( 1301): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.4A SSID=4E473730303567
,D/WifiNative-HAL(  901): callSECApiVoid - ID [50]
,D/ConnectivityService(  901): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  901): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  901): Got NetworkAgent Messenger
D/ConnectivityService(  901): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  901): updateNetworkInfo()
D/ConnectivityService(  901): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  901): NetworkAgent connected
,I/SELinux ( 7715): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,D/StatusBar.NetworkController( 1192): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1192): onWifiSignalChanged enabled=true enabledDesc:null
,I/SELinux ( 7715): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7715): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/WifiConfigStore(  901): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  285): Setting iface cfg
E/WifiStateMachine(  901): Start Dhcp Watchdog 2
,D/SecContentProvider2(  901): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  901): mCursor = null
,D/SecContentProvider2(  901): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  901): mCursor = null
,D/TimaKeyStoreProvider( 7715): TimaSignature is unavailable
,D/ActivityThread( 7715): Added TimaKeyStore provider
,D/ConnectivityService(  901): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,D/ResourcesManager( 7715): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,W/ResourcesManager( 7715): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7715): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Minikin ( 7715): addFont failed to create font /system/fonts/SamsungSans-light.ttf
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  901): Killing 6791:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
,E/native  (  901): do suspend false
,I/SO_AGENT( 7006): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,D/SecContentProvider2(  901): uri = 20 selection = getPromptCredentialsEnabled
D/WifiP2pService(  901): InactiveState{ what=143375 }
D/WifiP2pService(  901): P2pEnabledState{ what=143375 }
,D/SecContentProvider2(  901): mCursor = null
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7731): MountEmulatedStorage()
E/Zygote  ( 7731): v2
I/libpersona( 7731): KNOX_SDCARD checking this for 1000
I/libpersona( 7731): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=7731 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7731): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7731): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7731): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7731): TimaSignature is unavailable
,D/ActivityThread( 7731): Added TimaKeyStore provider
,D/ResourcesManager( 7731): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7751): MountEmulatedStorage()
,E/Zygote  ( 7751): v2
I/libpersona( 7751): KNOX_SDCARD checking this for 10043
I/libpersona( 7751): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7751 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  901): Killing 6820:com.samsung.android.app.watchmanagerstub/u0a126 (adj 15): bgCount ##41
,E/dhcpcd  ( 7756): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 7756): version 5.5.6 starting
,E/dhcpcd  ( 7756): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/SELinux ( 7751): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7751): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7751): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 7751): TimaSignature is unavailable
,D/ActivityThread( 7751): Added TimaKeyStore provider
,I/dhcpcd  ( 7756): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7756): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7756): if(wlan0) info get Success. (MAC : C0.AA.4A)
,I/dhcpcd  ( 7756): bssid match
I/dhcpcd  ( 7756): wlan0: rebinding lease of 192.168.1.128
,D/ResourcesManager( 7751): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService( 7751): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 7751): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 7751): PushLog.txt file is not deleted.
D/SPPClientService( 7751): PushLog.txt file is not deleted.
D/SPPClientService( 7751): ============PushLog. stop!
,E/SPPClientService( 7751): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 6647): [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
,I/SA      ( 6647): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 6647): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6647): [SLFUCHKMGR] constructor called
,E/SPPClientService( 7751): [[SystemStateMonitorService]] No Active Internet
,I/SA      ( 6647): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6647): [OR] == isSIMCardReady false ==
,I/SA      ( 6647): [SCU] == networkStateCheck == false
I/SA      ( 6647): [OR] onReceive END
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7777): MountEmulatedStorage()
I/libpersona( 7777): KNOX_SDCARD checking this for 10074
E/Zygote  ( 7777): v2
I/libpersona( 7777): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=7777 uid=10074 gids={50074, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/art     (  327): Explicit concurrent mark sweep GC freed 8750(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 326us total 12.924ms
,I/SELinux ( 7777): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/ActivityManager(  901): Killing 6836:com.samsung.helphub/1000 (adj 15): bgCount ##41
I/SELinux ( 7777): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7777): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  327): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 274us total 9.889ms
,I/art     (  327): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 430us total 10.195ms
D/TimaKeyStoreProvider( 7777): TimaSignature is unavailable
,D/ActivityThread( 7777): Added TimaKeyStore provider
,D/ResourcesManager( 7777): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/sCloudBackupApp( 7777): sCloudBackupApp Version Info : 3.13.7.KK_APP
I/SCloudBackupReceiver( 7777): Other Intent
,I/KnoxUsageLogPro( 7273): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7273): premStatus:2
,I/KnoxUsageLogPro( 7273): isEulaShown : false
,I/KnoxUsageLogPro( 7273): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7793): MountEmulatedStorage()
,E/Zygote  ( 7793): v2
I/libpersona( 7793): KNOX_SDCARD checking this for 10104
I/libpersona( 7793): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7793 uid=10104 gids={50104, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  901): Killing 6873:com.samsung.android.snote:provider/u0a168 (adj 15): bgCount ##41
,I/SELinux ( 7793): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7793): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7793): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7793): TimaSignature is unavailable
,D/ActivityThread( 7793): Added TimaKeyStore provider
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,D/ResourcesManager( 7793): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7809): MountEmulatedStorage()
E/Zygote  ( 7809): v2
I/libpersona( 7809): KNOX_SDCARD checking this for 10146
I/libpersona( 7809): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7809 uid=10146 gids={50146, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  901): Killing 6892:com.sec.kidsplat.installer/u0a189 (adj 15): bgCount ##41
,I/SELinux ( 7809): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7809): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7809): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7809): TimaSignature is unavailable
,D/ActivityThread( 7809): Added TimaKeyStore provider
,D/ResourcesManager( 7809): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/ContextImpl( 7809): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7809): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7809): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7809): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory( 7809): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,D/ResourcesManager( 7809): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7809): Loading: webviewchromium
,I/LibraryLoader( 7809): Time to load native libraries: 5 ms (timestamps 66-71)
,I/LibraryLoader( 7809): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7809): Binding Chromium to main looper Looper (main, tid 1) {3fa34315}
,I/LibraryLoader( 7809): Expected native library version number "",actual native library version number ""
,I/chromium( 7809): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7809): Initializing chromium process, renderers=0
,W/art     ( 7809): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7809): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7809): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46780 len=2953
,I/chromium( 7809): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229536 len:643667
,W/AudioManagerAndroid( 7809): Requires BLUETOOTH permission
,I/Adreno-EGL( 7809): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 7809): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7809): Build Date: 11/19/14 Wed
I/Adreno-EGL( 7809): Local Branch: mybranch5813579
I/Adreno-EGL( 7809): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 7809): Local Patches: NONE
I/Adreno-EGL( 7809): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,I/NSApplication( 7809): Starting up...
,I/ActivityManager(  901): Killing 6920:com.sec.android.app.samsungapps/u0a45 (adj 15): bgCount ##41
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7863): MountEmulatedStorage()
E/Zygote  ( 7863): v2
I/libpersona( 7863): KNOX_SDCARD checking this for 10158
I/libpersona( 7863): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7863 uid=10158 gids={50158, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 7863): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7863): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7863): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7863): TimaSignature is unavailable
,D/ActivityThread( 7863): Added TimaKeyStore provider
,D/ResourcesManager( 7863): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 7863): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7863): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7863): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 7863): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7863): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7863): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7878): MountEmulatedStorage()
E/Zygote  ( 7878): v2
I/libpersona( 7878): KNOX_SDCARD checking this for 10186
I/libpersona( 7878): KNOX_SDCARD not a persona
,I/dhcpcd  ( 7756): wlan0: acknowledged 192.168.1.128 from 192.168.1.1
,I/ActivityManager(  901): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7878 uid=10186 gids={50186, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
I/ActivityManager(  901): Killing 5656:com.sec.android.app.shealth/u0a40 (adj 15): bgCount ##41
,I/SELinux ( 7878): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7878): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7878): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7878): TimaSignature is unavailable
,D/ActivityThread( 7878): Added TimaKeyStore provider
,D/ResourcesManager( 7878): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,I/dhcpcd  ( 7756): wlan0: leased 192.168.1.128 for 86400 seconds
,D/ConnectivityService(  901): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,W/ResourcesManager( 7878): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7878): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7878): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService(  901): exchangeData() failure , invalid userId
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,D/RCPManagerService(  901): exchangeData() failure , invalid userId
,D/RCPManagerService(  901): exchangeData() failure , invalid userId
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService(  901): exchangeData() failure , invalid userId
,E/Zygote  ( 7916): MountEmulatedStorage()
I/libpersona( 7916): KNOX_SDCARD checking this for 10092
E/Zygote  ( 7916): v2
I/libpersona( 7916): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7916 uid=10092 gids={50092, 9997} abi=armeabi-v7a
,I/SELinux ( 7916): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7916): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7916): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/RCPManagerService(  901): exchangeData() failure , invalid userId
,D/RCPManagerService(  901): exchangeData() failure , invalid userId
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7124): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7124): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7124): StateMachine : Current State = 1
,D/SecurityLogAgent( 7124): StateMachine : Changed Current State = 1
,I/ActivityManager(  901): Killing 7022:com.samsung.android.scloud.sync/u0a76 (adj 15): bgCount ##41
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 7916): TimaSignature is unavailable
D/ActivityThread( 7916): Added TimaKeyStore provider
,E/Zygote  ( 7937): MountEmulatedStorage()
I/libpersona( 7937): KNOX_SDCARD checking this for 10200
E/Zygote  ( 7937): v2
I/libpersona( 7937): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7937 uid=10200 gids={50200, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7937): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7937): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7937): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7937): TimaSignature is unavailable
,D/ActivityThread( 7937): Added TimaKeyStore provider
,I/ActivityManager(  901): Killing 7039:com.sec.android.app.clockpackage/u0a106 (adj 15): bgCount ##41
,D/ResourcesManager( 7937): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,D/ResourcesManager( 7916): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/BadgeProvider( 7916): onCreate
,D/BadgeProvider( 7916): DatabaseHelper
,W/ActivityManager(  901): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/ActivityManager(  901): Killing 7066:com.sec.esdk.elm/u0a116 (adj 15): bgCount ##41
,D/BadgeProvider( 7916): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/iu.Environment( 2181): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,E/native  (  901): do suspend true
I/iu.UploadsManager( 2181): num queued entries: 0
I/iu.UploadsManager( 2181): num updated entries: 0
,I/iu.SyncManager( 2181): NEXT; no task
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,D/BadgeProvider( 7916): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 7916): sendNotify, [notify] : null
D/BadgeProvider( 7916): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7916): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7916): update, [UpdateCount] : 1
,D/WifiP2pService(  901): InactiveState{ what=143375 }
,D/WifiP2pService(  901): P2pEnabledState{ what=143375 }
D/Launcher.Model( 1447): reloadBadges entered.
,D/ConnectivityService(  901): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,E/Zygote  ( 7953): MountEmulatedStorage()
,E/Zygote  ( 7953): v2
I/libpersona( 7953): KNOX_SDCARD checking this for 10045
I/libpersona( 7953): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7953 uid=10045 gids={50045, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 7953): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7953): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7953): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7953): TimaSignature is unavailable
,D/ActivityThread( 7953): Added TimaKeyStore provider
,E/WifiStateMachine(  901): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG7005g"WPA_PSK
E/WifiStateMachine(  901): VerifyingLinkState enter
,D/StatusBar.NetworkController( 1192): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1192): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiNative-HAL(  901): callSECApiInt - ID [210]
,E/ConnectivityService(  901): updateNetworkInfo()
,D/ConnectivityService(  901): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService(  901): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine(  901): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  901): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver(  901): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker(  901): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  901): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 1192): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1192): onWifiSignalChanged enabled=true enabledDesc:null
D/ResourcesManager( 7953): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-1/base.apk
E/WifiStateMachine(  901): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
I/WifiTrafficPoller(  901): evaluateTrafficStatsPolling
D/StatusBar.NetworkController( 1192): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
I/WifiTrafficPoller(  901): evaluateTrafficStatsPolling
E/WifiStateMachine(  901): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/WifiTrafficPoller(  901): mBoosterFLAG : 0
I/WifiTrafficPoller(  901): current booster mode : FullMode
D/WifiNative-HAL(  901): callSECApiVoid - ID [212]
D/STATUSBAR-WifiQuickSettingButton( 1192): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1192): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1192): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
D/StatusBar.NetworkController( 1192): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1192): applyOpen
D/StatusBar.NetworkController( 1192): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1192): applyOpen
D/StatusBar.NetworkController( 1192): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1192): applyOpen
D/StatusBar.NetworkController( 1192): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1192): applyOpen
D/ConnectivityService(  901): Adding Route [fe80::/64 -> :: wlan0] to network 503
D/ConnectivityService(  901): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
D/ConnectivityService(  901): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService(  901): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  901): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  901): updateSourceRoutes : add src route for:192.168.1.128
V/        (  285): QcRouteController
I/ActivityManager(  901): Killing 7144:com.qualcomm.timeservice/1000 (adj 15): bgCount ##41
V/        (  285): QcRouteController
I/Hs20UtilService( 1313): Starting #8
I/Hs20UtilService( 1313): Message received 5007
D/NearbySettings( 1313): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1313): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1313): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1313): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1313): MountReceiver.mPrefHandler - 7002
,V/        (  285): QcRouteController
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6855): NETWORK_STATE_CHANGED_ACTION
,V/        (  285): QcRouteController
,I/Hs20UtilService( 1313): Starting #9
,I/Hs20UtilService( 1313): Message received 5007
,V/        (  285): QcRouteController
,V/        (  285): QcRouteController
,V/        (  285): QcRouteController
,V/        (  285): QcRouteController
,E/SMD     (  291): DCD ON
,D/NearbySettings( 1313): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1313): MountReceiver.onReceive - Keep current state
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6855): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  901): Setting Dns servers for network 503 to [/192.168.1.1]
,D/ConnectivityService(  901): LTETest block dns file not exists
,V/Nat464Xlat(  901): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  901): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService(  901): updateNetworkInfo()
D/ConnectivityService(  901): calling update connectivity
E/ConnectivityService(  901): updateNetworkInfo()
D/ConnectivityService(  901): ignoring duplicate network state non-change. WIFI, state = CONNECTING
D/ConnectivityService(  901): ignoring duplicate network state non-change. WIFI, state = CONNECTING
D/ConnectivityService(  901): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  901): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  901): calling update connectivity
D/ConnectivityService(  901): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  901):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  901):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  901):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  901):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/EntConnectivity(  901): Not allowed due to - mEnabled false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): Checking http://clients3.google.com/generate_204 on "NG7005g"
,I/System.out(  901): (HTTPLog)-Static: isSBSettingEnabled false
,D/ConnectivityService(  901): currentScore = 0, newScore = 60
D/ConnectivityService(  901):    accepting network in place of null
D/ConnectivityService(  901): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker(  901): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  901): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  901): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/TelephonyNetworkFactory( 1420): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/Hs20UtilService( 1313): Starting #10
,D/ConnectivityService(  901): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  901): MasterInitialState.processMessage what=3
D/SmartBondingService(  901): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/Hs20UtilService( 1313): Message received 5007
D/SmartBondingService(  901): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  901): getSBEnabled() enabled =false
D/ConnectivityService(  901): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/SmartBondingService(  901): getSBEnabled() enabled =false
D/SmartBondingService(  901): getSBEnabled() enabled =false
,D/SmartBondingService(  901): getNetworkEnabled : wifi : true mobile : true
,V/NetworkStats(  901): updateIfacesLocked()
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
V/NetworkStats(  901): performPollLocked(flags=0x1)
,D/NetworkStatsFactory(  901): UpdateStatsForKnox
D/ConnectivityService(  901): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  901): calling update connectivity
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/EntConnectivity(  901): Not allowed due to - mEnabled false
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
,V/NetworkStats(  901): performPollLocked() took 3ms
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
,V/NetworkStats(  901): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1192): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1192): updateDataNetType()
D/StatusBar.NetworkController( 1192): NoService, mRoamingIconId = 0
,E/StatusBar.NetworkController( 1192): updateLTEICONDataNetType:0
,D/ConnectivityService(  901): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1192): CM callback handler got msg 524290
,D/ConnectivityService(  901): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 2181): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1192): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1192): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1192): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1192): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1192): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
D/StatusBar.NetworkController( 1192): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1192): applyOpen
D/StatusBar.NetworkController( 1192): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1192): applyOpen
D/StatusBar.NetworkController( 1192): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1192): applyOpen
,D/StatusBar.NetworkController( 1192): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1192): applyOpen
,D/NearbySettings( 1313): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1313): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
,I/NearbySettings( 1313): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1313): MountReceiver.onReceive - Keep current state
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6855): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 1313): Starting #11
,I/Hs20UtilService( 1313): Message received 5007
,D/NearbySettings( 1313): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1313): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine(  901): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6855): NETWORK_STATE_CHANGED_ACTION
,I/System.out(  901): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/SurfaceFlinger(  257): id=17 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService(  901): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=901
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 09 Dec 2015 17:13:47 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449681228007], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449681227989]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): Validated
,D/ConnectivityService(  901): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  901): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  901):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  901):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  901):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  901): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  901): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  901): calling update connectivity
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  901): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  901): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1192): CM callback handler got msg 524290
D/ConnectivityService(  901): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 2181): CM callback handler got msg 524290
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1192): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1192): updateDataNetType()
D/StatusBar.NetworkController( 1192): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1192): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1192): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1192): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1192): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1192): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1192): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,D/ConnectivityService(  901): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  901): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  901): SmartBondingReceiver: wifi is connected
,D/SmartBondingService(  901): SmartBondingReceiver: wifi ap is not changed
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  901): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  901): getSBEnabled() enabled =false
,D/SmartBondingService(  901): getSBEnabled() enabled =false
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  901): getSBEnabled() enabled =false
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GpsLocationProvider(  901): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5849): type=WIFI subType= reason=null isConnected=true
,I/DBG_DM  ( 3457): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/PCWCLIENTTRACE_PushUtil( 7662): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7662): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7662): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7662): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,W/ContextImpl( 1852): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
W/ContextImpl( 1852): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/SmartBondingService(  901): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 3457): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/DIAGMON_AGENT( 7697): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7697): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/SecContentProvider2(  901): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  901): mCursor = null
,I/FOTA_Client( 6966): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 6966): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 6966): [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.511: ( 6985): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.511: ( 6985): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449681228554
,I/KLMS-2.4.511: ( 6985): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.511: ( 6985): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.511: ( 6985): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.511: ( 6985): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.511: ( 6985): StateImplV2(): networkChangeListener().END
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SO_AGENT( 7006): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 7751): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 6647): [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
,I/SA      ( 6647): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 6647): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6647): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6647): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 6647): [SCU] == networkStateCheck == true
,I/SA      ( 6647): [DM] getCountryCodeFromCSC : PL
I/SA      ( 6647): isChinaCountryCode : false
I/SA      ( 6647): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6647): [OR] == networkStateCheck true ==
,I/SA      ( 6647): [OR] GetMyCountryZoneTask
,I/SA      ( 6647): [OR] onReceive END
,I/SA      ( 6647): [SRS] prepareGetMyCountryZone
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6647): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6647): [SSP] query invoked
,I/SCloudBackupReceiver( 7777): Other Intent
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KnoxUsageLogPro( 7273): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 7273): premStatus:2
,I/KnoxUsageLogPro( 7273): isEulaShown : false
I/KnoxUsageLogPro( 7273): KnoxUsageReceiver onReceive : not Processible, just return
,I/SA      ( 6647): [TPMU] GetMccFromDB : null
,I/SA      ( 6647): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6647): [TPM] isNoProxy(default) : true
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/File    ( 6647): fail readDirectory() errno=2
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 7863): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7863): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 7863): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  901): exchangeData() failure , invalid userId
,D/RCPManagerService(  901): exchangeData() failure , invalid userId
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7124): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7124): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7124): StateMachine : Current State = 1
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7124): StateMachine : Changed Current State = 1
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/iu.Environment( 2181): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2181): num queued entries: 0
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/iu.UploadsManager( 2181): num updated entries: 0
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/iu.SyncManager( 2181): NEXT; no task
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 7953): notifyNetworkActivated
,W/ContextImpl( 7953): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  901): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7953): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7953): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7953): exit::IDLE
D/InitializeManagerStateMachine( 7953): entry::NETWORK_CHECK
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7953): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7953): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7953): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7953): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7953): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7953): entry::SUCCESS
D/hcjo    ( 7953): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 7953): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7953): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7953): exit::SUCCESS
D/InitializeManagerStateMachine( 7953): entry::IDLE
,D/ConnectivityService(  901): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
D/ConnectivityService(  901): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/SmartBondingService(  901): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  901): identical MTU - not setting
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  901): updateSourceRoutes : add src route for:fe80::ea50:8bff:fede:28a3
D/SmartBondingService(  901): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  901): getSBEnabled() enabled =false
D/SmartBondingService(  901): getSBEnabled() enabled =false
D/SmartBondingService(  901): getSBEnabled() enabled =false
,V/        (  285): QcRouteController
,V/        (  285): QcRouteController
,W/NetworkManagementService(  901): route cmd failed: 
W/NetworkManagementService(  901): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '74 route replace src v6 wlan0 fe80::ea50:8bff:fede:28a3 2 ::' failed with '400 74 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  901): '
W/NetworkManagementService(  901): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService(  901): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService(  901): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService(  901): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService(  901): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  901): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5625)
W/NetworkManagementService(  901): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5437)
W/NetworkManagementService(  901): 	at com.android.server.ConnectivityService.access$2300(ConnectivityService.java:229)
W/NetworkManagementService(  901): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2382)
W/NetworkManagementService(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  901): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
V/Nat464Xlat(  901): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  901): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  901): calling update connectivity
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  901): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  901): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1192): CM callback handler got msg 524295
,D/ConnectivityService(  901): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  901): calling update connectivity
D/ConnectivityManager.CallbackHandler( 2181): CM callback handler got msg 524295
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  901): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1192): CM callback handler got msg 524295
,D/ConnectivityService(  901): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 2181): CM callback handler got msg 524295
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,I/SA      ( 6647): [RC New] Execute method=[GET] start
,I/SA      ( 6647): [RC New] Security=[true]
,I/System.out( 6647): Thread-1081(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6647): Thread-1081(ApacheHTTPLog):isShipBuild true
,I/System.out( 6647): Thread-1081(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/SA      ( 6647): [RC New] [v2liruge] api execute + 651
,I/SA      ( 6647): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6647): AsyncTask #1 calls detatch()
,I/SA      ( 6647): [TPMU] getNetworkMcc : 
,I/SA      ( 6647): [SCU] saveMccToPreferece Start
I/SA      ( 6647): [SCU] RegionMCC : 260
,I/SA      ( 6647): [SSP] query invoked
,I/SA      ( 6647): [TPMU] GetMccFromDB : null
I/SA      ( 6647): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6647): [SCU] saveMccToPreferece End
I/SA      ( 6647): [RC New] executeRequest [v2liruge] end. 722
,I/SA      ( 6647): [RC New] Execute end
I/SA      ( 6647): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 6647): [OR] GetMyCountryZoneTask Success
,I/dhcpcd  ( 7756): wlan0: sending IPv6 Router Solicitation
,W/Atfwd_Sendcmd(  358): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PackageManager(  901): [MSG] WRITE_PACKAGE_RESTRICTIONS
,E/SMD     (  291): DCD ON
,I/jxcore-log( 7527): Test app app.js loaded
I/jxcore-log( 7527): 
,I/chromium( 7527): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/WifiStateMachine(  901): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/chromium( 7527): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 7527): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7527): 
,I/PowerManagerService(  901): [PWL] Off : 30s ago
,I/SurfaceFlinger(  257): id=17 Removed Uoast (8/9)
,I/SurfaceFlinger(  257): id=17 Removed Uoast (-2/9)
,D/PowerManagerService(  901): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 901) eventTime = 164888
,D/PowerManagerService(  901): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=901 (0x0)
,D/PowerManagerService(  901): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=901, ws=WorkSource{10067}) (elapsedTime=3528)
,I/GAV4    ( 7809): Thread[GAThread,5,main]: No campaign data found.
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  901): waitForAlarm result :4
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): stay LED for fully charged
D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,V/HeadsetService( 2936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2936): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:n  (  901): SIOP:: AP = 370, PST = 329, CUR = 450
,E/Watchdog(  901): !@Sync 5,
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7662): mConnectivityHandler : connected
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 7662): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE( 7662): ================================================
,I/CSTORAGE( 7662):  CSTORAGE_SKM_LIB v1.0.6
I/CSTORAGE( 7662): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 7662): [GetString-S]
,E/art     ( 7662): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 7662): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI( 7662): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 7662): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 7662): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7662): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 7662): [ensureRegistration] - No Samsung account
,E/SMD     (  291): DCD ON
,I/dhcpcd  ( 7756): wlan0: sending IPv6 Router Solicitation
,E/SMD     (  291): DCD ON
,I/dhcpcd  ( 7756): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 7756): wlan0: no IPv6 Routers available
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PreloadUpdateManagerStateMachine( 7953): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7953): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 7953): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7953): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7953): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7953): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7953): entry::IDLE
,E/SMD     (  291): DCD ON
,V/AlarmManager(  901): waitForAlarm result :8
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  (  901): SIOP:: AP = 320, PST = 326, CUR = 450
,E/SMD     (  291): DCD ON
,I/ActivityManager(  901): Waited long enough for: ServiceRecord{1bd683cf u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,I/PowerManagerService(  901): [PWL] Off : 50s ago
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/BatteryService(  901): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2936): Disconnected process message: 10
,D/SSRM:n  (  901): SIOP:: AP = 310, PST = 324, CUR = 450
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD ON
,W/Atfwd_Sendcmd(  358): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  291): DCD ON
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 310, PST = 322, CUR = 450
,E/Watchdog(  901): !@Sync 6
,E/SMD     (  291): DCD ON
,V/AlarmManager(  901): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1192): handleTimeUpdate
,D/KeyguardEffectViewController( 1192): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1192): *** don't update sliding image ***
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  901): stay LED for fully charged
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,V/HeadsetService( 2936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2936): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
I/MotionRecognitionService(  901): Plugged
I/MotionRecognitionService(  901): setPowerConnected  = true
,D/DateView( 1192): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1192): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 310, PST = 321, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,E/SMD     (  291): DCD ON
,V/HeadsetService( 2936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2936): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
D/BatteryService(  901): stay LED for fully charged
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  901): [PWL] Off : 75s ago
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD ON
,I/Atfwd_Sendcmd(  358): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  358): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 300, PST = 319, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  901): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,V/HeadsetService( 2936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2936): Disconnected process message: 10
,E/SMD     (  291): DCD ON
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD ON
,I/ClearcutLoggerApiImpl( 1862): disconnect managed GoogleApiClient
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,D/SSRM:n  (  901): SIOP:: AP = 300, PST = 317, CUR = 450
,E/Watchdog(  901): !@Sync 7
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD ON
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  358): AtCmdFwd service not published, waiting... retryCnt : 1
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,I/MotionRecognitionService(  901): setPowerConnected  = true
,V/HeadsetService( 2936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2936): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  901): stay LED for fully charged
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD ON
,V/AlarmManager(  901): waitForAlarm result :8
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,D/SSRM:n  (  901): SIOP:: AP = 300, PST = 315, CUR = 450
,E/SMD     (  291): DCD ON
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  358): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,V/HeadsetService( 2936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2936): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  901): stay LED for fully charged
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  901): [PWL] Off : 105s ago
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 300, PST = 314, CUR = 450
,E/SMD     (  291): DCD ON
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD ON
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  358): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 300, PST = 312, CUR = 450
,E/Watchdog(  901): !@Sync 8
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2936): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/BatteryService(  901): stay LED for fully charged
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 300, PST = 305, CUR = 450
,E/SMD     (  291): DCD ON
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD ON
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2936): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  901): stay LED for fully charged
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD ON
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  358): AtCmdFwd service not published, waiting... retryCnt : 4
,I/PowerManagerService(  901): [PWL] Off : 140s ago
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 290, PST = 302, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2936): Disconnected process message: 10
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  901): stay LED for fully charged
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/Watchdog(  901): !@Sync 9
,D/SSRM:n  (  901): SIOP:: AP = 290, PST = 300, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2936): Disconnected process message: 10
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/BatteryService(  901): stay LED for fully charged
,E/SMD     (  291): DCD ON
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD ON
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,D/SSRM:n  (  901): SIOP:: AP = 290, PST = 298, CUR = 450
,E/SMD     (  291): DCD ON
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  358): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2936): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  901): stay LED for fully charged
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 290, PST = 296, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
I/MotionRecognitionService(  901): Plugged
I/MotionRecognitionService(  901): setPowerConnected  = true
,V/HeadsetService( 2936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2936): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  901): stay LED for fully charged
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService(  901): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  901): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  901): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  901): initializing...
,I/TLC_TIMA_PKM_initialize(  901): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  901): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication(  901): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  901): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication(  901): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication(  901): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  901): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: (  901): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  901): App is not loaded in QSEE
,D/QSEECOMAPI: (  901): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  901): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  901): Trustlet response is completed
,E/SMD     (  291): DCD ON
,I/PowerManagerService(  901): [PWL] Off : 180s ago
,I/PowerManagerService(  901): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  901): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  901): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=901, ws=null) (elapsedTime=1499)
,E/Watchdog(  901): !@Sync 10
,D/SSRM:n  (  901): SIOP:: AP = 300, PST = 296, CUR = 450
,I/TLC_TIMA_PKM_measure_kernel(  901): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  901): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  901): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  901): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
I/MotionRecognitionService(  901): Plugged
I/MotionRecognitionService(  901): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 2936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2936): Disconnected process message: 10
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  901): stay LED for fully charged
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,I/Atfwd_Sendcmd(  358): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  358): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:n  (  901): SIOP:: AP = 290, PST = 295, CUR = 450
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD ON
,V/AlarmManager(  901): waitForAlarm result :4
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,I/ActivityManager(  901): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=8063 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 8063): MountEmulatedStorage()
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1192): handleTimeUpdate
,E/Zygote  ( 8063): v2
,I/libpersona( 8063): KNOX_SDCARD checking this for 10096
I/libpersona( 8063): KNOX_SDCARD not a persona
,I/SELinux ( 8063): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 8063): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 8063): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/KeyguardEffectViewController( 1192): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1192): *** don't update sliding image ***
,D/DateView( 1192): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1192): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/TimaKeyStoreProvider( 8063): TimaSignature is unavailable
,D/ActivityThread( 8063): Added TimaKeyStore provider
,D/ResourcesManager( 8063): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,I/ActivityManager(  901): Killing 7172:com.sec.android.widgetapp.SPlannerAppWidget/u0a171 (adj 15): bgCount ##41
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 290, PST = 294, CUR = 450
,E/SMD     (  291): DCD ON
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD ON
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  358): AtCmdFwd service not published, waiting... retryCnt : 1
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  901): stay LED for fully charged
,V/HeadsetService( 2936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2936): Disconnected process message: 10
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,E/SMD     (  291): DCD ON
,E/Watchdog(  901): !@Sync 11
,D/SSRM:n  (  901): SIOP:: AP = 290, PST = 293, CUR = 450
,E/SMD     (  291): DCD ON
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD ON
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD ON
,V/AlarmManager(  901): waitForAlarm result :8
,W/Atfwd_Sendcmd(  358): AtCmdFwd service not published, waiting... retryCnt : 2
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  901): stay LED for fully charged
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2936): Disconnected process message: 10
,D/SSRM:n  (  901): SIOP:: AP = 290, PST = 292, CUR = 450
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,I/PowerManagerService(  901): [PWL] Off : 225s ago
,E/SMD     (  291): DCD ON
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2936): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  901): stay LED for fully charged
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD ON
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,D/SSRM:n  (  901): SIOP:: AP = 290, PST = 291, CUR = 450
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD ON
,W/Atfwd_Sendcmd(  358): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  291): DCD ON
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  901): stay LED for fully charged
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,V/HeadsetService( 2936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2936): Disconnected process message: 10
,E/Watchdog(  901): !@Sync 12
,D/SSRM:n  (  901): SIOP:: AP = 290, PST = 291, CUR = 450
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 290, PST = 291, CUR = 450
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  358): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  291): DCD ON
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
I/MotionRecognitionService(  901): Plugged
I/MotionRecognitionService(  901): setPowerConnected  = true
,V/HeadsetService( 2936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2936): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  901): stay LED for fully charged
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 290, PST = 291, CUR = 450
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  901): stay LED for fully charged
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2936): Disconnected process message: 10
,E/Watchdog(  901): !@Sync 13
,D/SSRM:n  (  901): SIOP:: AP = 290, PST = 291, CUR = 450
,E/SMD     (  291): DCD ON
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,I/PowerManagerService(  901): [PWL] Off : 275s ago
,E/SMD     (  291): DCD ON
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD ON
,W/Atfwd_Sendcmd(  358): AtCmdFwd service not published, waiting... retryCnt : 5
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  901): stay LED for fully charged
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2936): Disconnected process message: 10
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  901): stay LED for fully charged
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2936): Disconnected process message: 10
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2936): Disconnected process message: 10
,E/Watchdog(  901): !@Sync 14
,D/SSRM:n  (  901): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  291): DCD ON
,I/Atfwd_Sendcmd(  358): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  358): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  901): stay LED for fully charged
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  901): Plugged
I/MotionRecognitionService(  901): setPowerConnected  = true
,V/HeadsetService( 2936): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2936): Disconnected process message: 10
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  291): DCD ON
,I/jxcore-log( 7527): Toggling radios to false
I/jxcore-log( 7527): 
,D/BluetoothAdapter( 7527): disable()
,D/SettingsProvider(  901): name = bluetooth_on
,D/BluetoothAdapterState( 2936): CURRENT_STATE=ON, MSG = USER_TURN_OFF
,D/BluetoothAdapterProperties( 2936): Setting state to 13
I/BluetoothAdapterState( 2936): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService( 2936): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 2936): updateAdapterState state is 13
,I/BluetoothPbapService( 2936): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,D/BluetoothAdapterService( 2936): Autoconnection is available 
,D/BluetoothAdapterService( 2936): updateAdapterState prevState = 12newState = 13
D/BluetoothAdapterService( 2936): terminating service from this receiver
,D/BluetoothSocket( 2936): close() in, this: android.bluetooth.BluetoothSocket@13dcac56, channel: 19, state: LISTENING
D/BluetoothSocket( 2936): close() this: android.bluetooth.BluetoothSocket@13dcac56, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1380ab7e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@11fbc4d7mSocket: android.net.LocalSocket@337681c4 impl:android.net.LocalSocketImpl@269728ad fd:FileDescriptor[72]
,D/BluetoothSocket( 2936): Closing mSocket: android.net.LocalSocket@337681c4 impl:android.net.LocalSocketImpl@269728ad fd:FileDescriptor[72]
,D/BluetoothAdapterProperties( 2936): onBluetoothDisable()
,D/SecContentProvider(  901): uri = 3 selection = isDiscoverableEnabled
,I/BluetoothAdapterState( 2936): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterProperties( 2936): Scan Mode:20
,D/BluetoothAdapterState( 2936): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,E/bt-btif ( 2936): btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,D/bt_vendor( 2936): op for 7
,E/bt-btif ( 2936): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,E/BtOppRfcommListener( 2936): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 2936): cmd socket is not created
D/bt_upio ( 2936): proc btwrite assertion
,D/btif_config_util( 2936): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2936): btm_ble_start_auto_conn start : 0, 0
,W/bt-btif ( 2936): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,W/bt-l2cap( 2936): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 2936): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2936): L2CAP - PSM: 0x001b not found for deregistration
D/bt_vendor( 2936): op for 7
,D/bt_upio ( 2936): BT_WAKE is asserted already
,D/bt_vendor( 2936): op for 7
,D/bt_upio ( 2936): BT_WAKE is asserted already
,D/bt_vendor( 2936): op for 7
D/bt_upio ( 2936): BT_WAKE is asserted already
,D/bt_vendor( 2936): op for 7
,D/bt_upio ( 2936): BT_WAKE is asserted already
,D/bt_vendor( 2936): op for 7
D/bt_upio ( 2936): BT_WAKE is asserted already
,D/bt_vendor( 2936): op for 7
,D/bt_upio ( 2936): BT_WAKE is asserted already
,D/bt_vendor( 2936): op for 7
,D/bt_upio ( 2936): BT_WAKE is asserted already
,D/bt_vendor( 2936): op for 7
,D/bt_upio ( 2936): BT_WAKE is asserted already
,D/bt_vendor( 2936): op for 7
D/bt_upio ( 2936): BT_WAKE is asserted already
,D/bt_vendor( 2936): op for 7
D/bt_upio ( 2936): BT_WAKE is asserted already
,D/bt_vendor( 2936): op for 7
D/bt_upio ( 2936): BT_WAKE is asserted already
,D/bt_vendor( 2936): op for 7
D/bt_upio ( 2936): BT_WAKE is asserted already
,D/bt_vendor( 2936): op for 7
,D/bt_upio ( 2936): BT_WAKE is asserted already
,D/bt_vendor( 2936): op for 7
,D/bt_upio ( 2936): BT_WAKE is asserted already
W/InputMethodManagerService(  901): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService(  901): [BT Setting State] State =13
,D/BluetoothManager( 7609): [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,I/WifiManager( 7527): packageName : com.test.thalitest
,D/SecContentProvider(  901): uri = 18 selection = isWifiEnabled
D/SecContentProvider2(  901): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  901): mCursor = null
,D/WifiService(  901): setWifiEnabled: false pid=7527, uid=10275
,D/SettingsProvider(  901): name = wifi_on
,I/SamsungIME( 1708): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/BluetoothSocket( 2936): close() in, this: android.bluetooth.BluetoothSocket@2dcdd773, channel: 5, state: LISTENING
D/BluetoothTile( 1192):  onBluetoothStateChange:
D/BluetoothSocket( 2936): close() this: android.bluetooth.BluetoothSocket@2dcdd773, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@237d98df, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@e3bf630mSocket: android.net.LocalSocket@2daaa2a9 impl:android.net.LocalSocketImpl@26ecf02e fd:FileDescriptor[74]
D/BluetoothSocket( 2936): Closing mSocket: android.net.LocalSocket@2daaa2a9 impl:android.net.LocalSocketImpl@26ecf02e fd:FileDescriptor[74]
,I/BtOppRfcommListener( 2936): stopping Accept Thread
D/BluetoothSocket( 2936): close() in, this: android.bluetooth.BluetoothSocket@35a477cf, channel: 12, state: LISTENING
D/BluetoothSocket( 2936): close() this: android.bluetooth.BluetoothSocket@35a477cf, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@22e09671, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2ca2455cmSocket: android.net.LocalSocket@3361c065 impl:android.net.LocalSocketImpl@1c5be13a fd:FileDescriptor[78]
D/BluetoothSocket( 2936): Closing mSocket: android.net.LocalSocket@3361c065 impl:android.net.LocalSocketImpl@1c5be13a fd:FileDescriptor[78]
D/BluetoothPbap( 1313): Proxy object disconnected
D/PbapServerProfile( 1313): Bluetooth service disconnected
V/BluetoothEventManager( 1313): Received android.bluetooth.adapter.action.STATE_CHANGED
I/BtOppRfcommListener( 2936): BluetoothSocket listen thread finished
,E/WifiStateMachine(  901): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 1301): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1301): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1301): P2P: Current p2p state = IDLE
,I/jxcore-log( 7527): Radios toggled
I/jxcore-log( 7527): 
,D/BluetoothTile( 1192):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 1192): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothTile( 1192):  handleUpdatestate:false name:null
,D/BluetoothTile( 1192):  handleUpdatestate:false name:null
W/ContextImpl( 1313): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
I/wpa_supplicant( 1301): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiConfigStore(  901): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/StatusBarManagerService(  901): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=true num=0 )
,D/StatusBarManagerService(  901): setIconVisibility slot=bluetooth visible=false
D/PhoneStatusBar( 1192): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=false num=0 )
D/STATUSBAR-QSTileView( 1192): onStateChanged: Bluetooth
,D/DockEventReceiver( 1313): finishStartingService: stopping service
,E/native  (  901): do suspend true
,D/BluetoothNotiBroadcastReceiver( 1313): onReceive
,D/WifiP2pService(  901): InactiveState{ what=143375 }
D/WifiP2pService(  901): P2pEnabledState{ what=143375 }
,D/CommandListener(  285): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 1192): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1192): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
,V/NativeCrypto( 1862): Read error: ssl=0x9b8f2000: I/O error during system call, Connection timed out
,D/AuthorizationBluetoothService( 1862): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
V/NativeCrypto( 1862): SSL shutdown failed: ssl=0x9b8f2000: I/O error during system call, Broken pipe
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): reportBadNetwork(NetworkAgentInfo [WIFI () - 503]) by 10015
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): ValidatedState{ when=0 what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): DefaultState{ when=0 what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): Checking http://clients3.google.com/generate_204 on "NG7005g"
I/System.out(  901): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid (  901): Tagging socket 386 with tag ffffffff00000000{4294967295,0} uid 10015, pid: 901, getuid(): 1000
,I/System.out(  901): (HTTPLog)-Static: isSBSettingEnabled false
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): Validated
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  901): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  901):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  901):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  901):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  901): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  901): calling update connectivity
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  901): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1192): CM callback handler got msg 524290
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  901): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 2181): CM callback handler got msg 524290
,E/ConnectivityService(  901): updateNetworkInfo()
D/ConnectivityService(  901): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  901): updateNetworkInfo()
D/ConnectivityService(  901): ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
D/NetUtils(  901): android_net_utils_resetConnections in env=0xa939d320 clazz=0x9addc98c iface=wlan0 mask=0x3
D/ConnectivityService(  901): NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 3
E/WifiConfigStore(  901): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,I/WifiTrafficPoller(  901): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1192): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1192): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1192): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1192): applyOpen
D/StatusBar.NetworkController( 1192): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1192): applyOpen
D/StatusBar.NetworkController( 1192): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1192): applyOpen
D/StatusBar.NetworkController( 1192): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1192): applyOpen
,D/WifiP2pService(  901): InactiveState{ what=131204 }
,D/WifiP2pService(  901): P2pEnabledState{ what=131204 }
D/WifiScanningService(  901): SCAN_AVAILABLE : 1
D/WifiScanningService(  901): DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  901): sending p2p connection changed broadcast: FAILED
D/RttService(  901): SCAN_AVAILABLE : 1
D/RttService(  901): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNetworkAgent(  901): NetworkAgent: NetworkAgent channel lost
,D/WifiDisplayController(  901): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter(  901): onP2pDisconnected
D/IpRemoteDisplayController(  901): disconnectWfdBridgeServer
D/IpRemoteDisplayController(  901): WfdBridgeServer is already null
,D/WifiP2pService(  901): sending p2p connection changed broadcast: DISCONNECTED
,E/WifiStateMachine(  901): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/WifiDisplayController(  901): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController(  901): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  901): disconnect
D/WifiDisplayController(  901): updateConnection
D/WifiDisplayController(  901): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter(  901): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiP2pService(  901): P2pDisablingState
,D/WifiP2pService(  901): P2pDisablingState{ what=147458 }
D/WifiP2pService(  901): p2p socket connection lost
,D/WifiP2pService(  901): P2pDisabledState
,D/WifiDisplayController(  901): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter(  901): onP2pDisconnected
D/IpRemoteDisplayController(  901): disconnectWfdBridgeServer
D/IpRemoteDisplayController(  901): WfdBridgeServer is already null
,D/AllShareCastTile( 1192): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,D/WifiDisplayAdapter(  901): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/AllShareCastTile( 1192): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,E/native  (  901): do suspend true
,I/Hs20UtilService( 1313): Starting #12
,I/Hs20UtilService( 1313): Message received 5007
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/WifiP2pService(  901): P2pDisabledState{ what=143375 }
D/WifiP2pService(  901): DefaultState{ what=143375 }
,D/NearbySettings( 1313): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1313): DMSUtil.isNetworkConnected - flag-null, state-null
D/CommandListener(  285): Clearing all IP addresses on wlan0
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1192): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1192): onWifiSignalChanged enabled=true enabledDesc:null
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/WifiTrafficPoller(  901): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1192): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1192): onWifiSignalChanged enabled=true enabledDesc:null
I/NearbySettings( 1313): MountReceiver.onReceive - Set preference state off
I/wpa_supplicant( 1301): p2p0: State: DISCONNECTED -> DISCONNECTED
,D/SmartBondingService(  901): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,V/NearbySettings( 1313): MountReceiver.mPrefHandler - 7002
,D/SecContentProvider2(  901): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  901): mCursor = null
,D/ConnectivityService(  901): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1192): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1192): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1192): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1192): applyOpen
D/StatusBar.NetworkController( 1192): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1192): applyOpen
D/StatusBar.NetworkController( 1192): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1192): applyOpen
D/StatusBar.NetworkController( 1192): refreshSignalCluster - setNWBoosterIndicators(false)
D/HotspotTile( 1192): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/StatusBar.NetworkController( 1192): applyOpen
D/STATUSBAR-WifiQuickSettingButton( 1192): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-QSTileView( 1192): onStateChanged: Wi-Fi
D/STATUSBAR-WifiQuickSettingButton( 1192): Wifi onReceive(0)
D/HotspotTile( 1192): onReceive : 0, 0
,D/WifiCredService( 1313): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/SmartBondingService(  901): getNetworkEnabled : wifi : false mobile : true
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6855): NETWORK_STATE_CHANGED_ACTION
,D/bt_vendor( 2936): op for 6
D/bt_vendor( 2936): op for 7
D/bt_upio ( 2936): BT_WAKE is asserted already
D/bt_userial( 2936): RX termination
W/bt_userial( 2936): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 2936): Leaving userial_read_thread()
W/bt-l2cap( 2936): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2936): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2936): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 2936): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2936): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2936): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 2936): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2936): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2936): L2CAP - PSM: 0x001b not found for deregistration
W/bt-btif ( 2936): ag scb idx 1 not allocated
W/bt-btif ( 2936): ag scb idx 2 not allocated
E/bt-btif ( 2936): BTA AG is already disabled, ignoring ...
D/bt_userial( 2936): userial_close_reader Joined userial reader thread: 0
D/bt_vendor( 2936): op for 9
D/bt_hwcfg( 2936): hw_epilog_process
D/bt_vendor( 2936): op for 4
I/bt_userial_vendor( 2936): device fd = 65 close
,D/bt_vendor( 2936): op for 0
D/bt_upio ( 2936): upio_set_bluetooth_power(on: 0)
D/bt_upio ( 2936): is_emulator_context : 0
D/bt_upio ( 2936): is_rfkill_disabled ? [0]
,D/bt_vendor( 2936): cleanup
,I/GKI_LINUX( 2936): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 2936): GKI_exit_task 0 done
I/GKI_LINUX( 2936): GKI_shutdown(): task [BTU] terminated
,D/BluetoothAdapterState( 2936): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/NearbySettings( 1313): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/BtConfig.SecureMode( 2936): isSecureModeOn:false
D/BluetoothAdapterService( 2936): mProfilesStarted : true supportedProfileServices.length : 12
V/NearbySettings( 1313): DMSUtil.isNetworkConnected - flag-null, state-null
W/BluetoothAdapterService( 2936): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 2936): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/BluetoothAdapterService( 2936): Not skipping com.android.bluetooth.gatt.GattService
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1313): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1313): MountReceiver.mPrefHandler - 7002
,W/BluetoothAdapterService( 2936): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,D/BtSettings.ProfileConfig( 2936): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,D/BtGatt.DebugUtils( 2936): handleDebugAction() action=null
,W/BluetoothAdapterService( 2936): Not skipping com.android.bluetooth.hfp.HeadsetService
,D/BtGatt.GattService( 2936): Received stop request...Stopping profile...
D/BtGatt.GattService( 2936): stop()
D/BtGatt.AdvertiseManager( 2936): advertise clients cleared
,D/BluetoothAdapterService( 2936): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18263104
,D/FileShare-Server( 7258): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/HeadsetService( 2936): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2936): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18263104
,W/BluetoothAdapterService( 2936): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 2936): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 2936): Not skipping com.android.bluetooth.a2dp.A2dpService
,D/AudioService(  901): onServiceDisconnected: Bluetooth profile: 1
,D/HeadsetProfile( 1313): Bluetooth service disconnected
,W/BluetoothAdapterService( 2936): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 2936): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 2936): Not skipping com.android.bluetooth.hid.HidService
W/BluetoothHeadset( 7609): Proxy not attached to service
,W/BluetoothAdapterService( 2936): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 2936): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 2936): Not skipping com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 2936): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 2936): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 2936): Not skipping com.android.bluetooth.pan.PanService
I/wpa_supplicant( 1301): Blacklist: Clear (all) 
,W/BluetoothAdapterService( 2936): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 2936): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 2936): Not skipping com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 2936): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 2936): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 2936): Not skipping com.broadcom.bt.service.sap.SapService
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  901): notifyType LOST for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  901): calling update connectivity
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/EntConnectivity(  901): Not allowed due to - mEnabled false
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  901): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  901):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1192): CM callback handler got msg 524292
,D/ConnectivityService(  901): sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,V/Nat464Xlat(  901): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  901): Disconnected - quitting
,D/ConnectivityService(  901): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  901): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1420): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/CSLegacyTypeTracker(  901): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  901): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=false
D/ConnectivityService(  901): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityManager.CallbackHandler( 2181): CM callback handler got msg 524292
,I/wpa_supplicant( 1301): p2p0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 1301): CTRL-EVENT-DISCONNECTED bssid=C0.AA.4A reason=3 locally_generated=1
,I/wpa_supplicant( 1301): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 1301): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.4A SSID=4E473730303567
I/wpa_supplicant( 1301): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/Zygote  ( 8141): MountEmulatedStorage()
E/Zygote  ( 8141): v2
I/libpersona( 8141): KNOX_SDCARD checking this for 10192
I/libpersona( 8141): KNOX_SDCARD not a persona
,I/SELinux ( 8141): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/ActivityManager(  901): Start proc com.samsung.shareshot for broadcast com.samsung.shareshot/.WifiDirectBroadcastReceiver: pid=8141 uid=10192 gids={50192, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ConnectivityService(  901): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  901): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  901): MasterInitialState.processMessage what=3
,W/BluetoothAdapterService( 2936): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 2936): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
I/SELinux ( 8141): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
W/BluetoothAdapterService( 2936): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 2936): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 2936): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
D/SmartBondingService(  901): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  901): getSBEnabled() enabled =false
D/SmartBondingService(  901): getSBEnabled() enabled =false
E/ConnectivityService(  901): updateNetworkInfo()
D/SmartBondingService(  901): getSBEnabled() enabled =false
D/ConnectivityService(  901): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  901): updateNetworkInfo()
D/ConnectivityService(  901): ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,V/NetworkStats(  901): updateIfacesLocked()
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
V/NetworkStats(  901): performPollLocked(flags=0x1)
,E/SELinux ( 8141): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/NetworkStatsFactory(  901): UpdateStatsForKnox
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  291): DCD ON
W/BluetoothAdapterService( 2936): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 2936): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 2936): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 2936): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 2936): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 2936): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,V/NetworkStats(  901): performPollLocked() took 4ms
,W/BluetoothAdapterService( 2936): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
E/BluetoothAdapterService(405156100)( 2936): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
D/BluetoothAdapterState( 2936): Stopping profile services that were post enabled
E/BluetoothAdapterService(405156100)( 2936): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2936): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 2936): Profile still running: com.android.bluetooth.hid.HidService
,D/SmartBondingService(  901): getNetworkEnabled : wifi : false mobile : true
,D/StatusBar.NetworkController( 1192): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1192): updateDataNetType()
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1192): NoService, mRoamingIconId = 0
W/BluetoothHeadsetServiceJni( 2936): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2936): Cleaning up Bluetooth Handsfree callback object
E/StatusBar.NetworkController( 1192): updateLTEICONDataNetType:0
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
V/NetworkStats(  901): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime(  901): currentTimeMillis() cache hit
,D/A2dpService( 2936): Received stop request...Stopping profile...
V/Avrcp   ( 2936): doQuit
,D/A2dpStateMachine( 2936): Exit Disconnected: -1
,D/StatusBar.NetworkController( 1192): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1192): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/Avrcp   ( 2936): Unregistering previous receiver
,I/wpa_supplicant( 1301): Blacklist: Clear (all) 
D/StatusBar.NetworkController( 1192): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/BluetoothAdapterService( 2936): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18263104
,D/StatusBar.NetworkController( 1192): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1192): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1192): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1192): applyOpen
D/StatusBar.NetworkController( 1192): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1192): applyOpen
D/StatusBar.NetworkController( 1192): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1192): applyOpen
D/StatusBar.NetworkController( 1192): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1192): applyOpen
,D/BluetoothA2dp(  901): Proxy object disconnected
D/AudioService(  901): onServiceDisconnected: Bluetooth profile: 2
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
,D/BluetoothA2dp( 3175): Proxy object disconnected
,D/BluetoothA2dp( 1313): Proxy object disconnected
D/A2dpProfile( 1313): Bluetooth service disconnected
D/HidService( 2936): Received stop request...Stopping profile...
D/HidService( 2936): Stopping Bluetooth HidService
W/BluetoothHidServiceJni( 2936): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 2936): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 2936): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 2936): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18263104
,D/BluetoothInputDevice( 1313): Proxy object disconnected
D/HidProfile( 1313): Bluetooth service disconnected
,D/HealthService( 2936): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2936): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18263104
,D/PanService( 2936): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2936): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18263104
,D/BluetoothPan(  901): BluetoothPAN Proxy object disconnected
D/BluetoothPan( 1313): BluetoothPAN Proxy object disconnected
,D/PanProfile( 1313): Bluetooth service disconnected
D/BluetoothMapService( 2936): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 2936): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18263104
,D/SapService( 2936): Received stop request...Stopping profile...
D/SapService( 2936): Stopping Bluetooth SapService
D/BluetoothAdapterService( 2936): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18263104
,E/BluetoothAdapterService(405156100)( 2936): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2936): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 2936): Profile still running: com.android.bluetooth.hid.HidService
D/BluetoothA2dp( 2936): Proxy object disconnected
D/BluetoothAdapterService( 2936): Bluetooth A2dp source service disconnected
,I/GKI_LINUX( 2936): gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 2936): GKI_exit_task 2 done
I/GKI_LINUX( 2936): GKI_shutdown(): task [A2DP-MEDIA] terminated
V/Avrcp   ( 2936): cleanup
E/BluetoothAdapterService(405156100)( 2936): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2936): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2936): Profile still running: com.android.bluetooth.map.BluetoothMapService
E/BluetoothAdapterService(405156100)( 2936): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2936): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2936): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni( 2936): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 2936): Cleaning up Bluetooth Health object
E/BluetoothAdapterService(405156100)( 2936): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2936): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2936): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 2936): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2936): Cleaning up Bluetooth PAN callback object
,E/BluetoothAdapterService(405156100)( 2936): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2936): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 2936): Profile still running: com.broadcom.bt.service.sap.SapService
E/BluetoothAdapterService(405156100)( 2936): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
D/BluetoothAdapterState( 2936): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
W/BluetoothSAPServiceJni( 2936): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 2936): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,D/BluetoothAdapterProperties( 2936): Setting state to 10
I/BluetoothAdapterState( 2936): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 2936): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 2936): updateAdapterState state is 10
,D/BluetoothMap( 1313): Proxy object disconnected
D/MapProfile( 1313): Bluetooth service disconnected
,D/Bluetoothsap( 1313): BluetoothSAP Proxy object disconnected
D/SapProfile( 1313): Bluetooth service disconnected
,D/BluetoothA2dp(  901): onBluetoothStateChange: up=false
D/BluetoothAdapterService( 2936): Autoconnection is available 
D/BluetoothAdapterService( 2936): updateAdapterState prevState = 13newState = 10
I/BluetoothAdapterState( 2936): Entering OffState
,D/BluetoothPbap( 1313): onBluetoothStateChange: up=false
,D/Bluetoothsap( 1313): onBluetoothStateChange: up=false
D/Bluetoothsap( 1313): Unbinding service...
,D/BluetoothA2dp( 3175): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 1313): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 2936): onBluetoothStateChange: up=false
,D/BluetoothMap( 1313): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 1313): onBluetoothStateChange: up=false
,D/BluetoothManagerService(  901): Broadcasting onBluetoothServiceDown() to 12 receivers.
,D/TimaKeyStoreProvider( 8141): TimaSignature is unavailable
,D/ActivityThread( 8141): Added TimaKeyStore provider
D/FileWriteThread_Telephony( 1420): FileWriteThread : threadType = 3
D/BluetoothManagerService(  901): Broadcasting onBluetoothServiceUp() to 0 receivers.
,D/FileWriteThread_Telephony( 1420): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1420): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1420): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1420): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1420): FileWriteThread : threadType = 3
,W/InputMethodManagerService(  901): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService(  901): [BT Setting State] State =10
I/InputMethodManagerService(  901): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,I/GKI_LINUX( 2936): gki_task task_id=1 [BTIF] terminating
,D/BluetoothAdapter( 1192): 523775917: getState() :  mService = null. Returning STATE_OFF
D/BluetoothTile( 1192):  onBluetoothPairedDevicesChanged:
I/SamsungIME( 1708): STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
D/BluetoothTile( 1192): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothAdapter( 1192): 523775917: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1192): 523775917: getState() :  mService = null. Returning STATE_OFF
D/StatusBarManagerService(  901): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=true num=0 )
,D/BluetoothAdapter( 1192): 523775917: getState() :  mService = null. Returning STATE_OFF
D/StatusBarManagerService(  901): setIconVisibility slot=bluetooth visible=false
D/BluetoothAdapter( 1192): 523775917: getState() :  mService = null. Returning STATE_OFF
D/STATUSBAR-QSTileView( 1192): onStateChanged: Bluetooth
,D/FileWriteThread_Telephony( 1420): FileWriteThread : threadType = 3
I/GKI_LINUX( 2936): GKI_exit_task 1 done
I/GKI_LINUX( 2936): GKI_shutdown(): task [BTIF] terminated
V/BluetoothEventManager( 1313): Received android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothManager( 7609): [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,D/FileWriteThread_Telephony( 1420): FileWriteThread : threadType = 3
I/BluetoothServiceJni( 2936): cleanupNative: return from cleanup
,D/FileWriteThread_Telephony( 1420): FileWriteThread : threadType = 3
,D/PhoneStatusBar( 1192): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=false num=0 )
,D/FileWriteThread_Telephony( 1420): FileWriteThread : threadType = 3
,D/BluetoothAdapter( 1862): 957670549: getState() :  mService = null. Returning STATE_OFF
I/art     ( 2936): System.exit called, status: 0
I/AndroidRuntime( 2936): VM exiting with result code 0, cleanup skipped.
,D/ResourcesManager( 8141): creating new AssetManager and set to /system/app/ShareShotService/ShareShotService.apk
,D/BluetoothAdapter( 1862): 957670549: getState() :  mService = null. Returning STATE_OFF
,D/FileWriteThread_Telephony( 1420): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1420): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1420): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1420): FileWriteThread : threadType = 3
,D/WifiDirectBR( 8141): WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/WifiDirectBR( 8141): WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
,W/ContextImpl( 8141): Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,D/WifiDirectBR( 8141): stopServiceTest : false
,D/WifiDirectBR( 8141): WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,I/ActivityManager(  901): Killing 7086:com.android.calendar/u0a172 (adj 15): bgCount ##41
,I/ActivityManager(  901): Process com.android.bluetooth (pid 2936)(adj 0) has died(209,1479)
,I/Hs20UtilService( 1313): Starting #13
,I/Hs20UtilService( 1313): Message received 5007
,I/wpa_supplicant( 1301): wlan0: CTRL-EVENT-TERMINATING 
,D/Tethering(  901): InitialState.processMessage what=4
,E/Tethering(  901): No numeric data
,D/Tethering(  901): sendTetherStateChangedBroadcast 0, 0, 0
,V/NetworkStats(  901): performPollLocked(flags=0x1)
,D/HotspotTile( 1192): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1192): updateTetherState():false, false
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
,D/NetworkStatsFactory(  901): UpdateStatsForKnox
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/NetworkStats(  901): performPollLocked() took 3ms
,D/NtpTrustedTime(  901): currentTimeMillis() cache hit
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
,D/NearbySettings( 1313): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1313): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1313): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1313): MountReceiver.mPrefHandler - 7002
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6855): NETWORK_STATE_CHANGED_ACTION
,E/SignOutReceiver( 6855): WIFI_STATE_CHANGED_ACTION
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7124): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7124): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7124): StateMachine : Current State = 1
D/SecurityLogAgent( 7124): StateMachine : Changed Current State = 1
,W/ContextImpl( 1313): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/DockEventReceiver( 1313): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1313): onReceive
,E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8174): MountEmulatedStorage()
E/Zygote  ( 8174): v2
I/libpersona( 8174): KNOX_SDCARD checking this for 1002
I/libpersona( 8174): KNOX_SDCARD not a persona
,I/ActivityManager(  901): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=8174 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,I/SELinux ( 8174): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 8174): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 8174): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/WifiStateMachine(  901): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
D/WifiNative-HAL(  901): callSECApiBoolean - ID [21]
,D/SmartBondingService(  901): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,D/StatusBar.NetworkController( 1192): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1192): onWifiSignalChanged enabled=false enabledDesc:null
D/STATUSBAR-WifiQuickSettingButton( 1192): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1192): Wifi onReceive(1)
D/HotspotTile( 1192): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/WifiCredService( 1313): Action received :android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-QSTileView( 1192): onStateChanged: Wi-Fi
D/HotspotTile( 1192): onReceive : 1, 0
D/SmartBondingService(  901): getNetworkEnabled : wifi : false mobile : true
,W/Settings( 1862): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TimaKeyStoreProvider( 8174): TimaSignature is unavailable
,D/ActivityThread( 8174): Added TimaKeyStore provider
,D/ResourcesManager( 8174): creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
,W/ResourcesManager( 8174): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,W/ResourcesManager( 8174): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/BluetoothA2dpSinkServiceJni( 8174): register_com_android_bluetooth_a2dp_sink
,D/BtSettings.ProfileConfig( 8174): Adding GattService
,D/BtSettings.ProfileConfig( 8174): Adding HeadsetService
D/BtSettings.ProfileConfig( 8174): Adding A2dpService
,D/BtSettings.ProfileConfig( 8174): Adding HidService
D/BtSettings.ProfileConfig( 8174): Adding HealthService
,D/BtSettings.ProfileConfig( 8174): Adding PanService
D/BtSettings.ProfileConfig( 8174): Adding BluetoothMapService
D/BtSettings.ProfileConfig( 8174): Adding SapService
,D/BtSettings.ProfileConfig( 8174): Adding HeadsetClientService
D/BtSettings.ProfileConfig( 8174): Adding A2dpSinkService
,D/BtSettings.ProfileConfig( 8174): Adding SapClientService
D/BtSettings.ProfileConfig( 8174): Adding HidDevService
I/BtSettings.ProfileConfig( 8174): *********Initializing Bluetooth Profile Settings*******
,D/SettingsProvider(  901): name = bt_svcst_com.android.bluetooth.gatt.GattService
D/SettingsProvider(  901): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  901): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  901): selectionArgs: false
D/SettingsProvider(  901): selectionArgs: 1002
D/SecContentProvider(  901): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  901): ret = -1
,D/SettingsProvider(  901): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/SettingsProvider(  901): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  901): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  901): selectionArgs: false
D/SettingsProvider(  901): selectionArgs: 1002
D/SecContentProvider(  901): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  901): ret = -1
,D/SettingsProvider(  901): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
D/SettingsProvider(  901): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  901): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  901): selectionArgs: false
D/SettingsProvider(  901): selectionArgs: 1002
D/SecContentProvider(  901): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  901): ret = -1
,D/SettingsProvider(  901): name = bt_svcst_com.android.bluetooth.hid.HidService
D/SettingsProvider(  901): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider(  901): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  901): selectionArgs: false
D/SettingsProvider(  901): selectionArgs: 1002
D/SecContentProvider(  901): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  901): ret = -1
,D/SettingsProvider(  901): name = bt_svcst_com.android.bluetooth.hdp.HealthService
D/SettingsProvider(  901): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  901): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  901): selectionArgs: false
D/SettingsProvider(  901): selectionArgs: 1002
D/SecContentProvider(  901): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  901): ret = -1
,D/SettingsProvider(  901): name = bt_svcst_com.android.bluetooth.pan.PanService
,D/SettingsProvider(  901): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  901): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  901): selectionArgs: false
D/SettingsProvider(  901): selectionArgs: 1002
D/SecContentProvider(  901): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  901): ret = -1
,D/SettingsProvider(  901): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
D/SettingsProvider(  901): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  901): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider(  901): selectionArgs: false
D/SettingsProvider(  901): selectionArgs: 1002
D/SecContentProvider(  901): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  901): ret = -1
,D/SettingsProvider(  901): name = bt_svcst_com.broadcom.bt.service.sap.SapService
,D/SettingsProvider(  901): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  901): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  901): selectionArgs: false
D/SettingsProvider(  901): selectionArgs: 1002
D/SecContentProvider(  901): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  901): ret = -1
,D/SettingsProvider(  901): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,D/SettingsProvider(  901): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  901): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  901): selectionArgs: false
D/SettingsProvider(  901): selectionArgs: 1002
D/SecContentProvider(  901): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  901): ret = -1
,D/SettingsProvider(  901): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,D/SettingsProvider(  901): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  901): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  901): selectionArgs: false
D/SettingsProvider(  901): selectionArgs: 1002
D/SecContentProvider(  901): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  901): ret = -1
,D/SettingsProvider(  901): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
D/SettingsProvider(  901): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  901): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  901): selectionArgs: false
D/SettingsProvider(  901): selectionArgs: 1002
D/SecContentProvider(  901): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  901): ret = -1
,D/SettingsProvider(  901): name = bt_svcst_com.android.bluetooth.hid.HidDevService
D/SettingsProvider(  901): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  901): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  901): selectionArgs: false
D/SettingsProvider(  901): selectionArgs: 1002
D/SecContentProvider(  901): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  901): ret = -1
,I/ActivityManager(  901): Killing 7197:com.sec.enterprise.knox.cloudmdm.smdms/u0a201 (adj 15): bgCount ##41
,D/AuthorizationBluetoothService( 1862): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/SignOutReceiver( 6855): WIFI_STATE_CHANGED_ACTION
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7124): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7124): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7124): StateMachine : Current State = 1
D/SecurityLogAgent( 7124): StateMachine : Changed Current State = 1
,E/WifiStateMachine(  901): skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,D/ConnectivityService(  901): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  901): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  901): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ApplicationPolicy(  901): updateDataUsageMap
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  901): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  901): getSBEnabled() enabled =false
D/SmartBondingService(  901): getSBEnabled() enabled =false
D/SmartBondingService(  901): getSBEnabled() enabled =false
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  901): getNetworkEnabled : wifi : false mobile : true
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3457): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NetworkMonitor( 5849): type=WIFI subType= reason=null isConnected=false
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PCWCLIENTTRACE_PushUtil( 7662): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7662): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7662): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7662): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
I/PCWCLIENTTRACE_SYSTEMReceiver( 7662): noConnectivity : true
,I/DBG_DM  ( 3457): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,I/DIAGMON_AGENT( 7697): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7697): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/FOTA_Client( 6966): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 6966): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 6966): [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.511: ( 6985): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.511: ( 6985): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449681519574
,I/KLMS-2.4.511: ( 6985): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.511: ( 6985): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.511: ( 6985): StateImplV2(): networkChangeListener().END
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SO_AGENT( 7006): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 7751): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 6647): [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
,I/SA      ( 6647): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 6647): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6647): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6647): [OR] == isSIMCardReady false ==
I/SA      ( 6647): [SCU] == networkStateCheck == false
I/SA      ( 6647): [OR] onReceive END
,E/SPPClientService( 7751): [[SystemStateMonitorService]] No Active Internet
,I/SCloudBackupReceiver( 7777): Other Intent
,I/KnoxUsageLogPro( 7273): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 7273): premStatus:2
,I/KnoxUsageLogPro( 7273): isEulaShown : false
I/KnoxUsageLogPro( 7273): KnoxUsageReceiver onReceive : not Processible, just return
,D/QuickConnect( 7863): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7863): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 7863): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService(  901): exchangeData() failure , invalid userId
,D/RCPManagerService(  901): exchangeData() failure , invalid userId
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7124): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7124): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7124): StateMachine : Current State = 1
D/SecurityLogAgent( 7124): StateMachine : Changed Current State = 1
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/iu.Environment( 2181): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2181): num queued entries: 0
,I/iu.UploadsManager( 2181): num updated entries: 0
,I/iu.SyncManager( 2181): NEXT; no task
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  291): DCD ON,
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,V/AlarmManager(  901): waitForAlarm result :4
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1192): handleTimeUpdate
,D/KeyguardEffectViewController( 1192): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1192): *** don't update sliding image ***
,D/DateView( 1192): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1192): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD ON
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  358): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  291): DCD ON
,I/PowerManagerService(  901): [PWL] Off : 330s ago
,I/PowerManagerService(  901): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  901): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  901): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=901, ws=null) (elapsedTime=12451),
,E/Watchdog(  901): !@Sync 15
,D/SSRM:n  (  901): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  291): DCD ON
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  901): stay LED for fully charged
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD ON
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD ON
,V/AlarmManager(  901): waitForAlarm result :8
,W/Atfwd_Sendcmd(  358): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,I/bootchecker(  353): bootchecker wake up!!
,E/SMD     (  291): DCD ON
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,D/SSRM:n  (  901): SIOP:: AP = 290, PST = 290, CUR = 450
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD ON
,W/Atfwd_Sendcmd(  358): AtCmdFwd service not published, waiting... retryCnt : 3
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  901): stay LED for fully charged
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD ON
,E/Watchdog(  901): !@Sync 16
,D/SSRM:n  (  901): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0,
D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  901): stay LED for fully charged
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD ON
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,D/SSRM:n  (  901): SIOP:: AP = 290, PST = 290, CUR = 450
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  358): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  901): Plugged
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD ON
,D/ConnectivityService(  901): Failed to find a new network - expiring NetTransition Wakelock
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,I/PowerManagerService(  901): [PWL] Off : 390s ago
,E/Watchdog(  901): !@Sync 17
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 289, CUR = 450
,E/SMD     (  291): DCD ON
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged,
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/BatteryService(  901): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD ON
,W/Atfwd_Sendcmd(  358): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 288, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 287, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/BatteryService(  901): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD ON
,E/Watchdog(  901): !@Sync 18
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 286, CUR = 450
,E/SMD     (  291): DCD ON
,I/Atfwd_Sendcmd(  358): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  358): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  901): Plugged
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 285, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 284, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,I/Atfwd_Daemon(  358): Stop the daemon....
,E/SMD     (  291): DCD ON
,E/Watchdog(  901): !@Sync 19
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 283, CUR = 450
,I/PowerManagerService(  901): [PWL] Off : 455s ago
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 282, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService(  901): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  901): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  901): TimaServiceHandler.handleMessage what =1
,E/SMD     (  291): DCD ON
,E/Watchdog(  901): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel(  901): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  901): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  901): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  901): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 290, PST = 281, CUR = 450
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,I/ActivityManager(  901): Killing 7110:com.android.providers.calendar/u0a51 (adj 15): bgCount ##41
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/Watchdog(  901): !@Sync 21
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON,
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  291): DCD ON
,I/PowerManagerService(  901): [PWL] Off : 525s ago
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/Watchdog(  901): !@Sync 22
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  901): stay LED for fully charged
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  901): stay LED for fully charged
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/Watchdog(  901): !@Sync 23
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  901): stay LED for fully charged
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,I/PowerManagerService(  901): [PWL] Off : 600s ago
,E/Watchdog(  901): !@Sync 24
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  901): stay LED for fully charged
D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
I/MotionRecognitionService(  901): Plugged
I/MotionRecognitionService(  901): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/Watchdog(  901): !@Sync 25
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,I/MotionRecognitionService(  901): Plugged
I/MotionRecognitionService(  901): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  901): stay LED for fully charged
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  901): stay LED for fully charged
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
I/MotionRecognitionService(  901): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  901): stay LED for fully charged
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/Watchdog(  901): !@Sync 26
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,V/AlarmManager(  901): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1192): handleTimeUpdate
,D/KeyguardEffectViewController( 1192): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1192): *** don't update sliding image ***
,D/LightsService(  901): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  901): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager(  901): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,D/DateView( 1192): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1192): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/LightsService(  901): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  901): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  901): unregisterListener ::   
,D/LightsService(  901): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
I/MotionRecognitionService(  901): Plugged
I/MotionRecognitionService(  901): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  901): stay LED for fully charged
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,I/PowerManagerService(  901): [PWL] Off : 680s ago
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/Watchdog(  901): !@Sync 27
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  901): stay LED for fully charged
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager(  901): waitForAlarm result :8
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/BatteryService(  901): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/Watchdog(  901): !@Sync 28
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/Watchdog(  901): !@Sync 29
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  901): stay LED for fully charged
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,I/PowerManagerService(  901): [PWL] Off : 765s ago
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/BatteryService(  901): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService(  901): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  901): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  901): TimaServiceHandler.handleMessage what =1
,E/SMD     (  291): DCD ON
,E/Watchdog(  901): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel(  901): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  901): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  901): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  901): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,I/MotionRecognitionService(  901): Plugged
I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/Watchdog(  901): !@Sync 31
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  901): stay LED for fully charged
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  901): stay LED for fully charged
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  901): stay LED for fully charged
,E/SMD     (  291): DCD ON
,E/Watchdog(  901): !@Sync 32
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  901): Plugged
I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
D/BatteryService(  901): stay LED for fully charged
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,I/PowerManagerService(  901): [PWL] Off : 855s ago
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  901): stay LED for fully charged
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/Watchdog(  901): !@Sync 33
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  901): stay LED for fully charged
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/Watchdog(  901): !@Sync 34
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  901): stay LED for fully charged
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  901): stay LED for fully charged
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/Watchdog(  901): !@Sync 35
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/BatteryService(  901): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/BatteryService(  901): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  901): [PWL] Off : 950s ago
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  901): stay LED for fully charged
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/Watchdog(  901): !@Sync 36
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/Watchdog(  901): !@Sync 37
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  901): stay LED for fully charged
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/Watchdog(  901): !@Sync 38
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  901): stay LED for fully charged
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,I/PowerManagerService(  901): [PWL] Off : 1050s ago
,E/Watchdog(  901): !@Sync 39
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/BatteryService(  901): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/TimaService(  901): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  901): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  901): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService(  901): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  901): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  901): Updating Usage Statistics in DB @ 1449682280416
,I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
,W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
,W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.o,s.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  901): stay LED for fully charged
D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService(  901): Plugged
I/MotionRecognitionService(  901): setPowerConnected  = true
D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  901): ::getAppControlDB: Exception to create DB
W/System.err(  901): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  901): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  901): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  901): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  901): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage(  901): Done Updating Usage Statistics in DB @ 1449682280634
,E/SMD     (  291): DCD ON
,E/Watchdog(  901): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel(  901): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  901): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  901): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  901): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  901): stay LED for fully charged
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  901): stay LED for fully charged
,E/SMD     (  291): DCD ON
,E/Watchdog(  901): !@Sync 41
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
I/MotionRecognitionService(  901): Plugged
I/MotionRecognitionService(  901): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  901): stay LED for fully charged
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  901): stay LED for fully charged
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/BatteryService(  901): stay LED for fully charged
,E/SMD     (  291): DCD ON
,E/Watchdog(  901): !@Sync 42
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  901): stay LED for fully charged
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,I/PowerManagerService(  901): [PWL] Off : 1155s ago
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  901): stay LED for fully charged
,E/SMD     (  291): DCD ON
,E/Watchdog(  901): !@Sync 43
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  901): stay LED for fully charged
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  901): !@Sync 44
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/BatteryService(  901): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/BatteryService(  901): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  901): Plugged
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  901): !@Sync 45
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  901): Plugged
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  901): !@Sync 46
,E/SMD     (  291): DCD ON
,I/PowerManagerService(  901): [PWL] Off : 1265s ago
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  901): Plugged
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  901): !@Sync 47
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  901): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  901): Plugged
I/MotionRecognitionService(  901): setPowerConnected  = true
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  901): stay LED for fully charged
,E/Watchdog(  901): !@Sync 48
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  901): stay LED for fully charged
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  901): Plugged
I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  901): stay LED for fully charged
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  901): stay LED for fully charged
,E/Watchdog(  901): !@Sync 49
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  901): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  901): stay LED for fully charged
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,D/TimaService(  901): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  901): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  901): TimaServiceHandler.handleMessage what =1
,E/SMD     (  291): DCD ON
,I/PowerManagerService(  901): [PWL] Off : 1380s ago
,I/PowerManagerService(  901): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  901): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  901): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=901, ws=null) (elapsedTime=1576)
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  901): !@Sync 50
,I/TLC_TIMA_PKM_measure_kernel(  901): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  901): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  901): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  901): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  901): Plugged
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  901): !@Sync 51
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  901): stay LED for fully charged
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,E/Watchdog(  901): !@Sync 52
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  901): stay LED for fully charged
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,I/MotionRecognitionService(  901): Plugged
I/MotionRecognitionService(  901): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,E/Watchdog(  901): !@Sync 53
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  901): stay LED for fully charged
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  901): stay LED for fully charged
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,I/PowerManagerService(  901): [PWL] Off : 1500s ago
,E/Watchdog(  901): !@Sync 54
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  901): stay LED for fully charged
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  901): stay LED for fully charged
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  901): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,E/Watchdog(  901): !@Sync 55
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  901): stay LED for fully charged
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,E/Watchdog(  901): !@Sync 56
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  901): stay LED for fully charged
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  901): stay LED for fully charged
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  901): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,E/Watchdog(  901): !@Sync 57
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  901): stay LED for fully charged
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
D/BatteryService(  901): stay LED for fully charged
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,E/Watchdog(  901): !@Sync 58
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  901): stay LED for fully charged
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,E/SMD     (  291): DCD ON
,I/PowerManagerService(  901): [PWL] Off : 1625s ago
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  901): stay LED for fully charged
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,E/Watchdog(  901): !@Sync 59
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  901): stay LED for fully charged
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  901): stay LED for fully charged
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,D/NetworkStatsFactory(  901): UpdateStatsForKnox
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/TimaService(  901): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  901): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  901): TimaServiceHandler.handleMessage what =1
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,V/AlarmManager(  901): waitForAlarm result :4
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.TIME_TICK
,D/LightsService(  901): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,D/KeyguardUpdateMonitor( 1192): handleTimeUpdate
,E/LightSensor(  901): Light old sensor_state 0, new sensor_state : 512 en : 1
,I/ProcessStatsService(  901): Prepared write state in 16ms
,D/SensorManager(  901): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,D/KeyguardEffectViewController( 1192): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1192): *** don't update sliding image ***
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/NetworkStats(  901): performPollLocked(flags=0x3)
,D/NtpTrustedTime(  901): currentTimeMillis() cache hit
,D/NetworkStatsFactory(  901): UpdateStatsForKnox
,D/ConnectivityService(  901): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  901): Plugged
I/MotionRecognitionService(  901): setPowerConnected  = true
,V/NetworkStats(  901): performPollLocked() took 26ms
,D/NtpTrustedTime(  901): currentTimeMillis() cache hit
,D/NtpTrustedTime(  901): currentTimeMillis() cache hit
D/NtpTrustedTime(  901): currentTimeMillis() cache hit
,D/DateView( 1192): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1192): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 2181): Aggregate from 1449680221947 (log), 1449680221947 (data)
,E/Watchdog(  901): !@Sync 60
,I/TLC_TIMA_PKM_measure_kernel(  901): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel(  901): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  901): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  901): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/LightsService(  901): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  901): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  901): unregisterListener ::   
D/LightsService(  901): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/ProcessStatsService(  901): Pruning old procstats: /data/system/procstats/state-2015-12-09-03-34-39.bin
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  901): stay LED for fully charged
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/BatteryService(  901): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  901): !@Sync 61
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,V/AlarmManager(  901): waitForAlarm result :8
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  901): Plugged
I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
D/BatteryService(  901): stay LED for fully charged
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  901): !@Sync 62
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,I/PowerManagerService(  901): [PWL] Off : 1755s ago
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  901): stay LED for fully charged
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,E/Watchdog(  901): !@Sync 63
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  901): Plugged
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,E/Watchdog(  901): !@Sync 64
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  901): stay LED for fully charged
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  901): Plugged
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,I/MotionRecognitionService(  901): Plugged
I/MotionRecognitionService(  901): setPowerConnected  = true
,D/BatteryService(  901): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  901): SIOP:: AP = 280, PST = 280, CUR = 450
,TIME-OUT KILL (timeout was 1800000ms),E/SMD     (  291): DCD ON
D/AndroidRuntime( 8318): 
D/AndroidRuntime( 8318): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8318): CheckJNI is OFF
D/AndroidRuntime( 8318): readGMSProperty: start
D/AndroidRuntime( 8318): readGMSProperty: already setted!!
D/AndroidRuntime( 8318): readGMSProperty: end
D/AndroidRuntime( 8318): addProductProperty: start
E/AffinityControl( 8318): AffinityControl: registerfunction enter
D/AndroidRuntime( 8318): Calling main entry com.android.commands.pm.Pm
D/PackageManager(  901): START PACKAGE DELETE: observer{824466891}
D/PackageManager(  901): pkg{<packageName>}
D/PackageManager(  901): user{0}
D/PackageManager(  901): caller{2000}
D/PackageManager(  901): flags{3}
D/PersonaManagerService(  901): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  901): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  901): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  901): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager(  901): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  901): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService(  901): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  901): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  901): getApplicationUninstallationEnabled
D/ApplicationPolicy(  901): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  901): !@killApplicatoin: 10275, uninstall pkg
I/ActivityManager(  901): Force stopping com.test.thalitest appid=10275 user=-1: uninstall pkg
I/ActivityManager(  901): Killing 7527:com.test.thalitest/u0a275 (adj 0): stop com.test.thalitest
W/PackageSettings(  901): Skipping PackageSetting{230e8c53 com.example.hello/10268} due to missing metadata
I/WindowState(  901): WIN DEATH: Window{31fdbc40 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  257): id=16 Removed NainActivit (5/8)
I/SurfaceFlinger(  257): id=16 Removed NainActivit (-2/8)
I/SurfaceFlinger(  257): id=16 Removed NainActivit (-2/8)
D/PointerIcon(  901): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  901): setMouseCustomIcon IconType is same.101
D/PointerIcon(  901): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  901): setHoveringSpenCustomIcon IconType is same.1
E/libprocessgroup(  901): failed to kill 1 processes for processgroup 7527
I/ActivityManager(  901): Killing 7916:com.sec.android.provider.badge/u0a92 (adj 13): empty for 1804s
I/ActivityManager(  901): Killing 1665:com.google.process.gapps/u0a15 (adj 13): empty for 1805s
I/ActivityManager(  901): Killing 7436:com.sec.android.widgetapp.activeapplicationwidget/u0a182 (adj 13): empty for 1831s
I/ActivityManager(  901): Killing 7420:com.sec.android.widgetapp.dualclockdigital/u0a115 (adj 13): empty for 1849s
I/ActivityManager(  901): Killing 7405:com.sec.android.widgetapp.digitalclock/u0a109 (adj 13): empty for 1849s
I/ActivityManager(  901): Killing 6673:com.android.mms/u0a55 (adj 15): empty for 1849s
D/CountryDetector(  901): No listener is left
I/ActivityManager(  901): Killing 5917:com.sec.android.gallery3d/u0a53 (adj 15): empty for 1849s
I/ActivityManager(  901): Killing 6163:com.android.vending/u0a33 (adj 15): empty for 1862s
I/ActivityManager(  901): Killing 7289:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty for 1862s
I/ActivityManager(  901): Killing 6132:com.sec.android.app.controlpanel/u0a134 (adj 15): empty for 1862s
E/Watchdog(  901): !@Sync 65
I/ActivityManager(  901): Killing 6064:com.samsung.android.app.galaxyfinder/u0a39 (adj 15): empty for 1862s
I/ActivityManager(  901): Killing 6021:sstream.app/u0a25 (adj 15): empty for 1863s
I/ActivityManager(  901):   Force finishing activity ActivityRecord{394b7b6a u0 com.test.thalitest/.MainActivity t4}
D/FocusedStackFrame(  901): Set to : 0
I/ActivityManager(  901): Force stopping com.test.thalitest appid=10275 user=0: pkg removed
I/ActivityManager(  901):   Force finishing activity ActivityRecord{394b7b6a u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager(  901): Duplicate finish request for ActivityRecord{394b7b6a u0 com.test.thalitest/.MainActivity t4 f}
I/art     ( 1580): Explicit concurrent mark sweep GC freed 4505(417KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 18MB/31MB, paused 568us total 40.473ms
I/art     ( 2181): Explicit concurrent mark sweep GC freed 7245(371KB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 22MB/30MB, paused 747us total 94.222ms
I/art     ( 4298): Explicit concurrent mark sweep GC freed 38047(2MB) AllocSpace objects, 9(144KB) LOS objects, 40% free, 15MB/26MB, paused 452us total 34.815ms
W/ActivityManager(  901): Spurious death for ProcessRecord{1711f9a8 7527:com.test.thalitest/u0a275}, curProc for 7527: null
W/libprocessgroup(  901): failed to open /acct/uid_10092/pid_7916/cgroup.procs: No such file or directory
W/libprocessgroup(  901): failed to open /acct/uid_10015/pid_1665/cgroup.procs: No such file or directory
W/libprocessgroup(  901): failed to open /acct/uid_10182/pid_7436/cgroup.procs: No such file or directory
I/art     ( 6855): Explicit concurrent mark sweep GC freed 6842(435KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 16MB/21MB, paused 347us total 24.714ms
W/libprocessgroup(  901): failed to open /acct/uid_10115/pid_7420/cgroup.procs: No such file or directory
W/libprocessgroup(  901): failed to open /acct/uid_10109/pid_7405/cgroup.procs: No such file or directory
W/libprocessgroup(  901): failed to open /acct/uid_10055/pid_6673/cgroup.procs: No such file or directory
W/libprocessgroup(  901): failed to open /acct/uid_10053/pid_5917/cgroup.procs: No such file or directory
W/libprocessgroup(  901): failed to open /acct/uid_10033/pid_6163/cgroup.procs: No such file or directory
W/libprocessgroup(  901): failed to open /acct/uid_1000/pid_7289/cgroup.procs: No such file or directory
W/libprocessgroup(  901): failed to open /acct/uid_10134/pid_6132/cgroup.procs: No such file or directory
W/libprocessgroup(  901): failed to open /acct/uid_10039/pid_6064/cgroup.procs: No such file or directory
W/libprocessgroup(  901): failed to open /acct/uid_10025/pid_6021/cgroup.procs: No such file or directory
D/ConnectivityService(  901): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
I/InputReader(  901): Reconfiguring input devices.  changes=0x00000010
E/SamsungIME( 1708): mOCRHelper is null
D/BatteryService(  901): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService(  901): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  901): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  901): stay LED for fully charged
D/ResourcesManager( 1447): creating new AssetManager and set to /system/priv-app/StoryAlbumWidget/StoryAlbumWidget.apk
W/GeofencerStateMachine( 1862): Ignoring removeGeofence because network location is disabled.
W/ResourcesManager( 1447): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1447): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
D/ResourcesManager( 1447): creating new AssetManager and set to /system/app/AccuweatherPhone2013_H_LMR/AccuweatherPhone2013_H_LMR.apk
W/ResourcesManager( 1447): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1447): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1447): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
D/ResourcesManager( 1447): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
W/ResourcesManager( 1447): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1447): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
I/KLMS-2.4.511: ( 6985): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.4.511: ( 6985): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1449683033162
I/KLMS-2.4.511: ( 6985): MainReciver(): PACKAGE_REMOVED
I/KLMS-2.4.511: ( 6985): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
I/art     (  901): Explicit concurrent mark sweep GC freed 36927(3MB) AllocSpace objects, 87(1574KB) LOS objects, 17% free, 38MB/46MB, paused 2.797ms total 183.089ms
D/ResourcesManager(  901): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/art     (  901): WaitForGcToComplete blocked for 124.189ms for cause Explicit
D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/RegisteredServicesCache( 1413): empty dynamic service
D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
D/ResourcesManager(  901): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/SecContentProvider2(  901): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  901): mCursor = null
D/ResourcesManager(  901): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager(  901): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Drive/Drive.apk
E/Zygote  ( 8355): MountEmulatedStorage()
E/Zygote  ( 8355): v2
I/libpersona( 8355): KNOX_SDCARD checking this for 10116
I/libpersona( 8355): KNOX_SDCARD not a persona
I/ActivityManager(  901): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8355 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
D/ResourcesManager(  901): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager(  901): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  901): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
I/art     (  327): Explicit concurrent mark sweep GC freed 8726(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 301us total 28.058ms
D/ResourcesManager(  901): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/ResourcesManager(  901): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Videos/Videos.apk
I/art     (  327): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 265us total 11.527ms
I/SELinux ( 8355): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 8355): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 8355): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/art     (  327): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 269us total 11.461ms
D/RCPManagerService(  901): PackageReceiver onReceive()
I/HarmonyEASService(  901): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy(  901): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  901): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  901): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  901): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  901): uID is 10275
V/EnterpriseBillingPolicy(  901): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  901): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  901): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  901): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  901): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  901): getBillingProfileForVpnEngine - start - com.test.thalitest
D/TimaKeyStoreProvider( 8355): TimaSignature is unavailable
V/EnterpriseBillingPolicyStorage(  901): getBillingProfileForVpnEngine - end - null
D/BatteryService(  901): Sending ACTION_BATTERY_CHANGED.
D/ActivityThread( 8355): Added TimaKeyStore provider
D/TaskPersister(  901): removeObsoleteFile: deleting file=4_task.xml
D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  901): Plugged
I/MotionRecognitionService(  901): setPowerConnected  = true
D/ResourcesManager( 8355): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/SurfaceWidgetView( 1447): destroyHardwareResources():284766507
V/WindowOrientationListener(  901): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  901): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  901): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  901): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  901): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/Launcher( 1447): onRestart, Launcher: 22501744
D/Launcher( 1447): onStart, Launcher: 22501744
D/Launcher.HomeView( 1447): onStart
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1994): [237392/8] Surface widget visibility changed visibility = true on instance = 1
V/ActivityThread( 1447): updateVisibility : ActivityRecord{23911769 token=android.os.BinderProxy@332fb3e5 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/SurfaceWidget.Renderer( 1994): [237392/8] SurfaceWidget drawing first frame
D/accuweather( 1994): [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
I/art     (  901): Explicit concurrent mark sweep GC freed 13281(763KB) AllocSpace objects, 2(32KB) LOS objects, 17% free, 38MB/46MB, paused 2.933ms total 293.644ms
D/elm:14491( 8355): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14491( 8355): ELMEngine.ELMEngine( context ).
D/elm:14491( 8355): MDMBridge.setEnterpriseBridge()
I/SurfaceFlinger(  257): id=18 createSurf (1080x1920),1 flag=4, Mauncher
D/StatusBarManagerService(  901): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/elm:14491( 8355): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
D/StatusBarManagerService(  901): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
D/elm:14491( 8355): ElmAgentService : onCreate()
D/elm:14491( 8355): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14491( 8355): MainReceiver.listeningToPackageRemoved()
D/elm:14491( 8355): MDMBridge.getInstance()
D/elm:14491( 8355): MDMBridge.getAllLicenseInfoFromSDK()
D/PointerIcon(  901): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  901): setMouseCustomIcon IconType is same.101
D/PointerIcon(  901): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/elm:14491( 8355): MDMBridge.getAllLicenseInfoFromSDK()
D/PointerIcon(  901): setHoveringSpenCustomIcon IconType is same.1
D/InputMethodManagerService(  901): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/InputMethodManagerService(  901): Got RemoteException sending setActive(false) notification to pid 7527 uid 10275
W/ContextImpl(  901): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
E/Zygote  ( 8376): MountEmulatedStorage()
E/Zygote  ( 8376): v2
I/ActivityManager(  901): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8376 uid=10021 gids={50021, 9997} abi=armeabi-v7a
I/libpersona( 8376): KNOX_SDCARD checking this for 10021
I/libpersona( 8376): KNOX_SDCARD not a persona
I/SELinux ( 8376): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/elm:14491( 8355): ElmAgentService : onDestroy().
I/SELinux ( 8376): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 8376): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager(  901): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
D/TimaKeyStoreProvider( 8376): TimaSignature is unavailable
D/ActivityThread( 8376): Added TimaKeyStore provider
I/Timeline(  901): Timeline: Activity_windows_visible id: ActivityRecord{9d0627a u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:1967019
D/ResourcesManager( 8376): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8376): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 8376): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8376): onReceive() : package name is not s health. Return !!!
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  901): checkUser: useridlist=null, currentuser=0
D/PackageManager(  901): delete codoeFile: 
D/ResourcesManager(  901): creating new AssetManager and set to /system/app/talkback/talkback.apk
I/AASAUninstall(  901):  com.test.thalitest not target!
D/PackageManager(  901): result of delete: 1{824466891}
D/AndroidRuntime( 8318): Shutting down VM
D/EnterpriseDeviceManagerService(  901): Package has changed for user 0
D/EnterpriseDeviceManagerService(  901): Admin package name: com.google.android.gms
D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Books/Books.apk
E/Zygote  ( 8393): MountEmulatedStorage()
E/Zygote  ( 8393): v2
I/libpersona( 8393): KNOX_SDCARD checking this for 10025
I/libpersona( 8393): KNOX_SDCARD not a persona
D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  901): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Videos/Videos.apk
I/ActivityManager(  901): Start proc sstream.app for broadcast sstream.app/.receiver.ApplicationCompatibleReceiver: pid=8393 uid=10025 gids={50025, 9997, 1028, 1015, 3003} abi=armeabi-v7a
D/ResourcesManager(  901): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  901): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
I/SELinux ( 8393): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
I/SELinux ( 8393): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Drive/Drive.apk
E/SELinux ( 8393): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  901): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Maps/Maps.apk
D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/TimaKeyStoreProvider( 8393): TimaSignature is unavailable
D/ResourcesManager(  901): creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
D/ActivityThread( 8393): Added TimaKeyStore provider
D/ResourcesManager(  901): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  901): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
D/ResourcesManager( 8393): creating new AssetManager and set to /system/priv-app/MagazineHome/MagazineHome.apk
W/ResourcesManager(  901): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  901): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  901): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8393): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  901): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
W/linker  ( 8393): libdmcAlwaysFD.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  901): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
D/MVFD_interface( 8393): <<<  caMVFace_FaceInit
W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  901): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
W/Resources(  901): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/UsbSettingsManager(  901): clearDefaults: com.test.thalitest
I/CrashAnrDetector(  901): onPackageRemoved : com.test.thalitest
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/sstream.app/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8393): Failed to ensure directory: /storage/extSdCard/Android/data/sstream.app/cache
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/sstream.app/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8393): Failed to ensure directory: /storage/extSdCard/Android/data/sstream.app/cache
D/HockeyApp( 8393): Current handler class = sstream.app.util.Log$1
D/ResourcesManager( 8393): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
E/SQLiteLog( 8393): (28) failed to open "/data/data/sstream.app/databases/sstream.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 8393): Failed to open database '/data/data/sstream.app/databases/sstream.db'.
E/SQLiteDatabase( 8393): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8393): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8393): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 8393): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 8393): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8393): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8393): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8393): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 8393): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 8393): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 8393): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 8393): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 8393): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 8393): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 8393): 	at sstream.app.provider.StoryProvider.delete(StoryProvider.java:90)
E/SQLiteDatabase( 8393): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:314)
E/SQLiteDatabase( 8393): 	at android.content.ContentResolver.delete(ContentResolver.java:1309)
E/SQLiteDatabase( 8393): 	at sstream.app.provider.DatabaseUtil.deleteConfigSettingForApp(DatabaseUtil.java:985)
E/SQLiteDatabase( 8393): 	at sstream.app.receiver.ApplicationCompatibleReceiver.onReceive(ApplicationCompatibleReceiver.java:216)
E/SQLiteDatabase( 8393): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2991)
E/SQLiteDatabase( 8393): 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
E/SQLiteDatabase( 8393): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
E/SQLiteDatabase( 8393): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8393): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 8393): 	at android.app.ActivityThread.main(ActivityThread.java:5940)
E/SQLiteDatabase( 8393): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 8393): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 8393): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1389)
E/SQLiteDatabase( 8393): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1184)

```
