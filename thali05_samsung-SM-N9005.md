#### Test 50650278923ff9f_thali05_samsung-SM-N9005 Logs


```
--------- beginning of system
W/ContextImpl(  752): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/PowerManagerService(  752): [PWL] Off : 15s ago
--------- beginning of main
E/SMD     (  296): DCD ON
,D/AndroidRuntime( 7199): 
D/AndroidRuntime( 7199): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7199): CheckJNI is OFF
D/AndroidRuntime( 7199): readGMSProperty: start
D/AndroidRuntime( 7199): readGMSProperty: already setted!!
D/AndroidRuntime( 7199): readGMSProperty: end
D/AndroidRuntime( 7199): addProductProperty: start
E/AffinityControl( 7199): AffinityControl: registerfunction enter
D/AndroidRuntime( 7199): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  752): inState():  stateMachine is null !!
I/PersonaManagerService(  752): PersonaId don't exist
I/ActivityManager(  752): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  752): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  752): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  752): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager(  752): mDVFSHelper.acquire()
D/FocusedStackFrame(  752): Set to : 0
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7216): MountEmulatedStorage()
E/Zygote  ( 7216): v2
I/libpersona( 7216): KNOX_SDCARD checking this for 10296
I/libpersona( 7216): KNOX_SDCARD not a persona
I/ActivityManager(  752): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7216 uid=10296 gids={50296, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7199): Shutting down VM
I/SELinux ( 7216): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7216): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
D/PointerIcon(  752): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  752): setMouseCustomIcon IconType is same.101
D/PointerIcon(  752): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  752): setHoveringSpenCustomIcon IconType is same.1
E/SELinux ( 7216): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7216): TimaSignature is unavailable
D/ActivityThread( 7216): Added TimaKeyStore provider
V/WindowOrientationListener(  752): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  752): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  752): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  752): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  752): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager(  752): Display changed displayId=0
D/ConnectivityService(  752): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager( 7216): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/SurfaceWidgetView( 1446): destroyHardwareResources():523058240
I/SurfaceFlinger(  256): id=14 Removed Mauncher (5/8)
I/SurfaceFlinger(  256): id=14 Removed Mauncher (-2/8)
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1812): [237392/8] Surface widget visibility changed visibility = false on instance = 1
V/ActivityThread( 1446): updateVisibility : ActivityRecord{d603dbc token=android.os.BinderProxy@39c0f80 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1446): onTrimMemory. Level: 20
,I/WebViewFactory( 7216): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,D/ResourcesManager( 7216): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7216): Loading: webviewchromium
,I/LibraryLoader( 7216): Time to load native libraries: 6 ms (timestamps 3330-3336)
I/LibraryLoader( 7216): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7216): Binding Chromium to main looper Looper (main, tid 1) {304f493c}
,I/LibraryLoader( 7216): Expected native library version number "",actual native library version number ""
,I/chromium( 7216): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7216): Initializing chromium process, renderers=0
,W/art     ( 7216): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7216): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7216): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46780 len=2953
,I/chromium( 7216): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229536 len:643667
,I/Adreno-EGL( 7216): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 7216): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7216): Build Date: 11/19/14 Wed
I/Adreno-EGL( 7216): Local Branch: mybranch5813579
I/Adreno-EGL( 7216): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 7216): Local Patches: NONE
I/Adreno-EGL( 7216): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,W/ActivityManager(  752): Activity pause timeout for ActivityRecord{24c0368f u0 com.test.thalitest/.MainActivity t4}
,W/chromium( 7216): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7216): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 7216): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7216): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 7216): CordovaWebView is running on device made by: samsung
,W/art     ( 7216): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7216): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity( 7216): performCreate Call secproduct feature valuefalse
D/Activity( 7216): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer( 7216): Render dirty regions requested: true
,D/Atlas   ( 7216): Validating map...
,D/ActivityManager(  752): post active user change for 0
D/KnoxTimeoutHandler(  752): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  752): handleActiveUserChange for user 0
,V/ActivityThread( 7216): updateVisibility : ActivityRecord{132bcb35 token=android.os.BinderProxy@ff2b21f {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/SurfaceFlinger(  256): id=16 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService(  752): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  752): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon(  752): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  752): setMouseCustomIcon IconType is same.101
D/PointerIcon(  752): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  752): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer( 7216): Initialized EGL, version 1.4
,I/OpenGLRenderer( 7216): HWUI protection enabled for context ,  &this =0xa1753060 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 7216): Enabling debug mode 0
,D/InputMethodManagerService(  752): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl(  752): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager(  752): mDVFSHelper.release()
,I/Timeline(  752): Timeline: Activity_windows_visible id: ActivityRecord{24c0368f u0 com.test.thalitest/.MainActivity t4} time:153921
,W/ContextImpl(  752): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 7216): showStatusIcon on inactive InputConnection
,I/Timeline( 7216): Timeline: Activity_idle id: android.os.BinderProxy@ff2b21f time:153928
,I/chromium( 7216): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7216): 
,D/JsMessageQueue( 7216): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 7216): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1258382464
,D/JX-Cordova( 7216): jxcore cordova android initializing
,E/SMD     (  296): DCD ON
,W/jxcore-log( 7216): Initializing JXcore engine
,W/jxcore-log( 7216): JXcore engine is ready
W/jxcore-log( 7216): Starting JXcore engine
,E/auditd  ( 1864): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  752): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl(  752): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  752): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,D/SecurityLogAgent( 6941):  SeDenialReceiver : Intent Received : android.intent.action.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 6941):  SeDenialReceiver : File path = null
,W/jxcore-log( 7216): Platform android
W/jxcore-log( 7216): 
,W/jxcore-log( 7216): Process ARCH arm
W/jxcore-log( 7216): 
,I/jxcore-log( 7216): JXcore Cordova bridge is ready!
I/jxcore-log( 7216): 
,W/jxcore-log( 7216): JXcore engine is started
,D/SSRM:n  (  752): SIOP:: AP = 330, PST = 333, CUR = 450
,I/jxcore-log( 7216): Toggling radios to true
I/jxcore-log( 7216): 
,D/BluetoothAdapter( 7216): enable()
,D/BluetoothAdapter( 7216): enable(): BT is already enabled..!
,I/WifiManager( 7216): packageName : com.test.thalitest
,D/SecContentProvider(  752): uri = 18 selection = isWifiEnabled
D/SecContentProvider2(  752): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  752): mCursor = null
,D/WifiService(  752): setWifiEnabled: true pid=7216, uid=10296
W/ActivityManager(  752): Permission Denial: getCurrentUser() from pid=7216, uid=10296 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  752): Failed getting userId using ActivityManagerNative
W/WifiService(  752): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7216, uid=10296 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  752): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23057)
W/WifiService(  752): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2181)
W/WifiService(  752): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2169)
W/WifiService(  752): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  752): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider(  752): name = wifi_on
,I/WifiService(  752): disconnect: pid=7216, uid=10296
,I/jxcore-log( 7216): Radios toggled
I/jxcore-log( 7216): 
I/wpa_supplicant( 1274): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 7216): Got Device Bluetooth address: E0:DB:10:1F:C9:5E
I/jxcore-log( 7216): 
,I/jxcore-log( 7216): Perf Test app loaded loaded
I/jxcore-log( 7216): 
,I/jxcore-log( 7216): check test folder
I/jxcore-log( 7216): 
,I/jxcore-log( 7216): found test : ./testFindPeers.js
I/jxcore-log( 7216): 
,I/wpa_supplicant( 1274): CTRL-EVENT-DISCONNECTED bssid=C0.AA.4A reason=3 locally_generated=1
,I/wpa_supplicant( 1274): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1274): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.4A SSID=4E473730303567
I/wpa_supplicant( 1274): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  752): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1274): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1274): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1274): Disconnected - do not scan
I/wpa_supplicant( 1274): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiConfigStore(  752): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,I/jxcore-log( 7216): found test : ./testSendData.js
I/jxcore-log( 7216): 
,E/native  (  752): do suspend true
,D/WifiP2pService(  752): InactiveState{ what=143375 }
,D/WifiP2pService(  752): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1184): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
,D/CommandListener(  291): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1924): Read error: ssl=0x9b72be00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1924): SSL shutdown failed: ssl=0x9b72be00: I/O error during system call, Broken pipe
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  752): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10015
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  752): ValidatedState{ when=-6ms what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  752): DefaultState{ when=-7ms what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  752): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  752): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  752): Checking http://clients3.google.com/generate_204 on "NG7005g"
,I/System.out(  752): (HTTPLog)-Static: isSBSettingEnabled false
,E/ConnectivityService(  752): updateNetworkInfo()
,D/ConnectivityService(  752): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  752): updateNetworkInfo()
D/ConnectivityService(  752): ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
,D/ConnectivityService(  752): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
D/NetUtils(  752): android_net_utils_resetConnections in env=0xa9395b70 clazz=0x9c0d998c iface=wlan0 mask=0x3
I/qtaguid (  752): Tagging socket 386 with tag ffffffff00000000{4294967295,0} uid 10015, pid: 752, getuid(): 1000
I/System.out(  752): (HTTPLog)-Static: isSBSettingEnabled false
D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/WifiConfigStore(  752): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/WifiTrafficPoller(  752): evaluateTrafficStatsPolling
D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  752): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/StatusBar.NetworkController( 1184): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1184): onWifiSignalChanged enabled=true enabledDesc:null
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
D/StatusBar.NetworkController( 1184): applyOpen
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  752): Validated
,E/WifiStateMachine(  752): Start Disconnecting Watchdog 1
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  752): stay LED for fully charged
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/wpa_supplicant( 1274): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1274): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1274): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1274): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1274): First Scan Start
,E/native  (  752): do suspend true
,I/ActivityManager(  752): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.samsung.myplace.WIFINotificationHandler: pid=7309 uid=10038 gids={50038, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/MotionRecognitionService(  752): Plugged
I/MotionRecognitionService(  752): setPowerConnected  = true
,E/Zygote  ( 7309): MountEmulatedStorage()
I/libpersona( 7309): KNOX_SDCARD checking this for 10038
E/Zygote  ( 7309): v2
I/libpersona( 7309): KNOX_SDCARD not a persona
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/chromium( 7216): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/SELinux ( 7309): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/SELinux ( 7309): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7309): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/wpa_supplicant( 1274): Scan requested (ret=0) - scan timeout 30 seconds
,I/chromium( 7216): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/WifiP2pService(  752): InactiveState{ what=143375 }
,D/WifiP2pService(  752): P2pEnabledState{ what=143375 }
,D/CommandListener(  291): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 1184): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1184): onWifiSignalChanged enabled=true enabledDesc:null
,I/WifiTrafficPoller(  752): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1184): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1184): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiNetworkAgent(  752): NetworkAgent: NetworkAgent channel lost
,D/TimaKeyStoreProvider( 7309): TimaSignature is unavailable
,D/ActivityThread( 7309): Added TimaKeyStore provider
,V/GLSActivity( 1924): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SecContentProvider2(  752): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  752): mCursor = null
,D/SecContentProvider2(  752): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  752): mCursor = null
,I/VacuumService( 1924): Vacuum at: now=1450280782868 tag=VacuumService
,D/ResourcesManager( 7309): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,W/ResourcesManager( 7309): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ConnectivityService(  752): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  752): calling update connectivity
D/ConnectivityService(  752):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/EntConnectivity(  752): Not allowed due to - mEnabled false
D/ConnectivityService(  752):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  752): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  752):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1184): CM callback handler got msg 524292
D/ConnectivityService(  752): sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/Nat464Xlat(  752): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  752): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  752): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/CSLegacyTypeTracker(  752): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/TelephonyNetworkFactory( 1416): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CSLegacyTypeTracker(  752): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService(  752): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  752): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  752): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  752): Disconnected - quitting
,D/ConnectivityManager.CallbackHandler( 2183): CM callback handler got msg 524292
,D/SmartBondingService(  752): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  752): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  752): getSBEnabled() enabled =false
D/SmartBondingService(  752): getSBEnabled() enabled =false
D/NtpTrustedTime(  752): currentTimeMillis() cache hit
V/NetworkStats(  752): updateIfacesLocked()
D/SmartBondingService(  752): getSBEnabled() enabled =false
V/NetworkStats(  752): performPollLocked(flags=0x1)
D/NetworkStatsFactory(  752): UpdateStatsForKnox
D/ConnectivityService(  752): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Tethering(  752): MasterInitialState.processMessage what=3
,D/ConnectivityService(  752): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/NtpTrustedTime(  752): currentTimeMillis() cache hit
V/NetworkStats(  752): performPollLocked() took 4ms
,D/StatusBar.NetworkController( 1184): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1184): updateDataNetType()
D/StatusBar.NetworkController( 1184): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1184): updateLTEICONDataNetType:0
D/SmartBondingService(  752): getNetworkEnabled : wifi : true mobile : true
,D/NtpTrustedTime(  752): currentTimeMillis() cache hit
V/NetworkStats(  752): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  752): currentTimeMillis() cache hit
D/NtpTrustedTime(  752): currentTimeMillis() cache hit
D/NtpTrustedTime(  752): currentTimeMillis() cache hit
D/NtpTrustedTime(  752): currentTimeMillis() cache hit
D/NtpTrustedTime(  752): currentTimeMillis() cache hit
,E/ConnectivityService(  752): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,D/StatusBar.NetworkController( 1184): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1184): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1184): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1184): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1184): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,D/FileWriteThread_Telephony( 1416): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1416): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1416): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1416): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1416): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1416): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1416): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1416): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1416): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1416): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1416): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1416): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1416): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1416): FileWriteThread : threadType = 3
,I/VlingoApplication( 7309): VlingoApplication appVersion ='11.2.2.0.37649', ro.csc.sales_code=XEO
,E/BluetoothHeadset( 7309): BTStateChangeCB is registed
,E/BluetoothHeadset( 7309): BluetoothHeadset service is binded
,I/ActivityManager(  752): Killing 6368:com.sec.pcw.device/1000 (adj 15): bgCount ##41
,I/Hs20UtilService( 1361): Starting #6
,I/Hs20UtilService( 1361): Message received 5007
,D/NearbySettings( 1361): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1361): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  752): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1361): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  752): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1361): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1361): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1361): MountReceiver.onReceive - Set preference state off
,D/SettingsProvider(  752): name = driving_mode_on
V/NearbySettings( 1361): MountReceiver.mPrefHandler - 7002
D/SettingsProvider(  752): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  752): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  752): selectionArgs: false
D/SettingsProvider(  752): selectionArgs: 10038
D/SecContentProvider(  752): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  752): ret = -1
,D/BluetoothManager( 7309): [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.media.ACTION_SCO_AUDIO_STATE_UPDATED
,D/ConnectivityService(  752): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6649): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 1361): Starting #7
,D/NearbySettings( 1361): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/Hs20UtilService( 1361): Message received 5007
V/NearbySettings( 1361): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  752): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1361): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  752): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1361): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1361): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1361): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1361): MountReceiver.mPrefHandler - 7002
,D/ConnectivityService(  752): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6649): NETWORK_STATE_CHANGED_ACTION
,E/SMD     (  296): DCD ON
,D/ConnectivityService(  752): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,I/ApplicationPolicy(  752): updateDataUsageMap
,D/ConnectivityService(  752): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  752): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GpsLocationProvider(  752): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  752): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  752): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  752): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3371): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,D/ConnectivityService(  752): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NetworkMonitor( 5632): type=WIFI subType= reason=null isConnected=false
,D/ConnectivityService(  752): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
D/ConnectivityService(  752): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3371): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
,D/SmartBondingService(  752): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  752): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  752): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  752): getSBEnabled() enabled =false
D/SmartBondingService(  752): getSBEnabled() enabled =false
D/SmartBondingService(  752): getSBEnabled() enabled =false
,D/SmartBondingService(  752): getNetworkEnabled : wifi : true mobile : true
,E/Zygote  ( 7356): MountEmulatedStorage()
E/Zygote  ( 7356): v2
I/libpersona( 7356): KNOX_SDCARD checking this for 1000
I/libpersona( 7356): KNOX_SDCARD not a persona
,I/SELinux ( 7356): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7356): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7356): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  752): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7356 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 7356): TimaSignature is unavailable
,D/ActivityThread( 7356): Added TimaKeyStore provider
,D/ResourcesManager( 7356): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/PCWCLIENTTRACE_LOG( 7356): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 7356): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 7356): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil( 7356): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 7356): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7356): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7356): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
I/PCWCLIENTTRACE_SYSTEMReceiver( 7356): noConnectivity : true
,I/ActivityManager(  752): Killing 5910:com.samsung.android.app.galaxyfinder/u0a39 (adj 15): bgCount ##41
,E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7372): MountEmulatedStorage()
E/Zygote  ( 7372): v2
I/libpersona( 7372): KNOX_SDCARD checking this for 10004
I/libpersona( 7372): KNOX_SDCARD not a persona
,I/ActivityManager(  752): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7372 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7372): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7372): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7372): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7372): TimaSignature is unavailable
,D/ActivityThread( 7372): Added TimaKeyStore provider
,D/ResourcesManager( 7372): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager(  752): Killing 6402:com.policydm/1000 (adj 15): bgCount ##41
,E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7389): MountEmulatedStorage()
E/Zygote  ( 7389): v2
I/libpersona( 7389): KNOX_SDCARD checking this for 1000
I/libpersona( 7389): KNOX_SDCARD not a persona
,I/ActivityManager(  752): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7389 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 7389): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7389): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7389): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7389): TimaSignature is unavailable
D/ActivityThread( 7389): Added TimaKeyStore provider
D/ResourcesManager( 7389): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
I/DIAGMON_AGENT( 7389): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
I/DIAGMON_AGENT( 7389): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
I/DIAGMON_AGENT( 7389): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
I/DIAGMON_AGENT( 7389): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
I/DIAGMON_AGENT( 7389): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT( 7389): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
I/FOTA_Client( 6754): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
I/FOTA_Client( 6754): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
I/FOTA_Client( 6754): [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
I/wpa_supplicant( 1274): nl80211: Received scan results (10 BSSes)
I/wpa_supplicant( 1274): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1274): Trying to associate with C0.AA.4A (SSID='4E473730303567' freq=5220 MHz)
I/wpa_supplicant( 1274): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1274): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E473730303567
I/KLMS-2.4.511: ( 6780): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.4.511: ( 6780): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450280784152
I/KLMS-2.4.511: ( 6780): MainReciver(): NETWORK_STATE_CHANGED_ACTION
D/ConnectivityService(  752): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  752): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/KLMS-2.4.511: ( 6780): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
I/KLMS-2.4.511: ( 6780): StateImplV2(): networkChangeListener().END
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
D/SecContentProvider2(  752): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  752): mCursor = null
I/wpa_supplicant( 1274): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1274): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E473730303567
I/wpa_supplicant( 1274): Associated with C0.AA.4A
E/Zygote  ( 7405): MountEmulatedStorage()
E/Zygote  ( 7405): v2
I/libpersona( 7405): KNOX_SDCARD checking this for 10036
I/libpersona( 7405): KNOX_SDCARD not a persona
I/wpa_supplicant( 1274): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1274): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.4A SSID=4E473730303567
I/ActivityManager(  752): Start proc com.samsung.android.app.pinboard:tagService for broadcast com.samsung.android.app.pinboard/.service.TagReadyReceiver: pid=7405 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  752): Killing 4853:com.sec.spp.push/u0a43 (adj 15): bgCount ##41
I/SELinux ( 7405): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7405): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
D/SecContentProvider2(  752): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  752): mCursor = null
D/SecContentProvider2(  752): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  752): mCursor = null
E/SELinux ( 7405): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/wpa_supplicant( 1274): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1274): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1274): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.4A SSID=4E473730303567
I/wpa_supplicant( 1274): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1274): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1274): CTRL-EVENT-CONNECTED - Connection to C0.AA.4A completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1274): Blacklist: Clear (temp) 
I/wpa_supplicant( 1274): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.4A SSID=4E473730303567
D/WifiNative-HAL(  752): callSECApiVoid - ID [50]
D/StatusBar.NetworkController( 1184): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1184): onWifiSignalChanged enabled=true enabledDesc:null
D/TimaKeyStoreProvider( 7405): TimaSignature is unavailable
D/ActivityThread( 7405): Added TimaKeyStore provider
D/ConnectivityService(  752): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  752): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  752): hsengiv:checkWhatTypeOfNetwork and the value is false
D/ConnectivityService(  752): Got NetworkAgent Messenger
E/ConnectivityService(  752): updateNetworkInfo()
D/ConnectivityService(  752): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  752): NetworkAgent connected
D/ResourcesManager( 7405): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
W/ResourcesManager( 7405): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7405): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
E/WifiConfigStore(  752): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/CommandListener(  291): Setting iface cfg
E/WifiStateMachine(  752): Start Dhcp Watchdog 2
D/SecContentProvider2(  752): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  752): mCursor = null
D/ConnectivityService(  752): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/Minikin ( 7405): addFont failed to create font /system/fonts/SamsungSans-light.ttf
D/ConnectivityService(  752): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ActivityManager(  752): Killing 6422:com.samsung.android.sdk.samsunglink/u0a48 (adj 15): bgCount ##41
I/SO_AGENT( 6798): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
E/native  (  752): do suspend false
E/Zygote  ( 7422): MountEmulatedStorage()
E/Zygote  ( 7422): v2
I/libpersona( 7422): KNOX_SDCARD checking this for 1000
I/libpersona( 7422): KNOX_SDCARD not a persona
D/SecContentProvider2(  752): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  752): mCursor = null
D/WifiP2pService(  752): InactiveState{ what=143375 }
D/WifiP2pService(  752): P2pEnabledState{ what=143375 }
I/SELinux ( 7422): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/ActivityManager(  752): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=7422 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 7422): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7422): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ServiceManager(  366): Waiting for service AtCmdFwd...
D/TimaKeyStoreProvider( 7422): TimaSignature is unavailable
D/ActivityThread( 7422): Added TimaKeyStore provider
D/ResourcesManager( 7422): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
D/ConnectivityService(  752): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  752): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7442): MountEmulatedStorage()
E/Zygote  ( 7442): v2
I/libpersona( 7442): KNOX_SDCARD checking this for 10043
I/libpersona( 7442): KNOX_SDCARD not a persona
,I/ActivityManager(  752): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7442 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  752): Killing 6499:com.sec.android.provider.badge/u0a92 (adj 15): bgCount ##41
,I/SELinux ( 7442): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7442): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7442): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,E/dhcpcd  ( 7448): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 7448): version 5.5.6 starting
,E/dhcpcd  ( 7448): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,D/ConnectivityService(  752): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  752): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 7442): TimaSignature is unavailable
,D/ActivityThread( 7442): Added TimaKeyStore provider
,D/ResourcesManager( 7442): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService( 7442): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 7442): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 7442): PushLog.txt file is not deleted.
,D/SPPClientService( 7442): PushLog.txt file is not deleted.
D/SPPClientService( 7442): ============PushLog. stop!
,I/dhcpcd  ( 7448): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7448): wlan0: sendmsg: Cannot assign requested address
,I/dhcpcd  ( 7448): if(wlan0) info get Success. (MAC : C0.AA.4A)
I/dhcpcd  ( 7448): bssid match
I/dhcpcd  ( 7448): wlan0: rebinding lease of 192.168.1.128
,E/SPPClientService( 7442): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 6451): [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
,I/SA      ( 6451): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 6451): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6451): [SLFUCHKMGR] constructor called
,I/SA      ( 6451): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6451): [OR] == isSIMCardReady false ==
,I/SA      ( 6451): [SCU] == networkStateCheck == false
I/SA      ( 6451): [OR] onReceive END
,E/SPPClientService( 7442): [[SystemStateMonitorService]] No Active Internet
,E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
,I/dhcpcd  ( 7448): wlan0: acknowledged 192.168.1.128 from 192.168.1.1
,E/Zygote  ( 7468): MountEmulatedStorage()
E/Zygote  ( 7468): v2
I/libpersona( 7468): KNOX_SDCARD checking this for 10074
I/libpersona( 7468): KNOX_SDCARD not a persona
,I/dhcpcd  ( 7448): wlan0: leased 192.168.1.128 for 86400 seconds
,D/ConnectivityService(  752): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,I/SELinux ( 7468): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7468): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7468): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  752): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=7468 uid=10074 gids={50074, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  752): Killing 6515:com.sec.android.app.soundalive/u0a64 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7468): TimaSignature is unavailable
,D/ActivityThread( 7468): Added TimaKeyStore provider
,I/art     (  348): Explicit concurrent mark sweep GC freed 8770(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 391us total 17.722ms
,I/art     (  348): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 278us total 10.599ms
,D/ResourcesManager( 7468): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/art     (  348): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 297us total 10.196ms
,I/sCloudBackupApp( 7468): sCloudBackupApp Version Info : 3.13.7.KK_APP
,I/SCloudBackupReceiver( 7468): Other Intent
,E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7495): MountEmulatedStorage()
E/Zygote  ( 7495): v2
I/libpersona( 7495): KNOX_SDCARD checking this for 1000
I/libpersona( 7495): KNOX_SDCARD not a persona
,I/SELinux ( 7495): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/ActivityManager(  752): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7495 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  752): Killing 5484:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
,I/SELinux ( 7495): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7495): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7495): TimaSignature is unavailable
,D/ActivityThread( 7495): Added TimaKeyStore provider
,D/ResourcesManager( 7495): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7495): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro( 7495): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7495): premStatus:2
,I/KnoxUsageLogPro( 7495): isEulaShown : false
,I/KnoxUsageLogPro( 7495): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7518): MountEmulatedStorage()
E/Zygote  ( 7518): v2
I/libpersona( 7518): KNOX_SDCARD checking this for 10104
I/libpersona( 7518): KNOX_SDCARD not a persona
,I/ActivityManager(  752): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7518 uid=10104 gids={50104, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  752): Killing 6535:com.wsomacp/u0a29 (adj 15): bgCount ##41
,I/SELinux ( 7518): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7518): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7518): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7518): TimaSignature is unavailable
,D/ActivityThread( 7518): Added TimaKeyStore provider
,D/ResourcesManager( 7518): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7536): MountEmulatedStorage()
,E/Zygote  ( 7536): v2
I/libpersona( 7536): KNOX_SDCARD checking this for 10146
I/libpersona( 7536): KNOX_SDCARD not a persona
,I/SELinux ( 7536): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7536): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7536): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  752): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7536 uid=10146 gids={50146, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  752): Killing 6551:com.google.android.apps.docs/u0a112 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7536): TimaSignature is unavailable
,D/ActivityThread( 7536): Added TimaKeyStore provider
,E/native  (  752): do suspend true
,D/WifiP2pService(  752): InactiveState{ what=143375 },
D/WifiP2pService(  752): P2pEnabledState{ what=143375 }
,D/ConnectivityService(  752): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,E/WifiStateMachine(  752): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG7005g"WPA_PSK
E/WifiStateMachine(  752): VerifyingLinkState enter
,D/StatusBar.NetworkController( 1184): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1184): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiNative-HAL(  752): callSECApiInt - ID [210]
,E/ConnectivityService(  752): updateNetworkInfo()
,D/ConnectivityService(  752): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService(  752): Adding iface wlan0 to network 503
,D/ResourcesManager( 7536): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/WifiWatchdogStateMachine(  752): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  752): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver(  752): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker(  752): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  752): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 1184): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1184): onWifiSignalChanged enabled=true enabledDesc:null
,D/ConnectivityService(  752): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService(  752): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService(  752): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService(  752): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  752): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  752): updateSourceRoutes : add src route for:192.168.1.128
,V/        (  291): QcRouteController
,E/WifiStateMachine(  752): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,I/WifiTrafficPoller(  752): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1184): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1184): onWifiSignalChanged enabled=true enabledDesc:null
,I/WifiTrafficPoller(  752): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  752): mBoosterFLAG : 0
,I/WifiTrafficPoller(  752): current booster mode : FullMode
D/WifiNative-HAL(  752): callSECApiVoid - ID [212]
,D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1184): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,E/WifiStateMachine(  752): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,V/        (  291): QcRouteController
,V/        (  291): QcRouteController
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7536): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7536): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,V/        (  291): QcRouteController
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7536): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7536): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,V/        (  291): QcRouteController
,V/        (  291): QcRouteController
,V/        (  291): QcRouteController
,V/        (  291): QcRouteController
,D/ConnectivityService(  752): Setting Dns servers for network 503 to [/192.168.1.1]
,D/ConnectivityService(  752): LTETest block dns file not exists
V/Nat464Xlat(  752): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  752): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  752): calling update connectivity
E/ConnectivityService(  752): updateNetworkInfo()
D/ConnectivityService(  752): ignoring duplicate network state non-change. WIFI, state = CONNECTING
E/ConnectivityService(  752): updateNetworkInfo()
D/ConnectivityService(  752): ignoring duplicate network state non-change. WIFI, state = CONNECTING
D/ConnectivityService(  752): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  752): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  752): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  752): calling update connectivity
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  752): Connected
D/ConnectivityService(  752): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  752): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  752):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  752): Checking http://clients3.google.com/generate_204 on "NG7005g"
D/ConnectivityService(  752):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/EntConnectivity(  752): Not allowed due to - mEnabled false
D/ConnectivityService(  752):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  752):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/System.out(  752): (HTTPLog)-Static: isSBSettingEnabled false
D/ConnectivityService(  752): currentScore = 0, newScore = 60
D/ConnectivityService(  752):    accepting network in place of null
D/ConnectivityService(  752): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1416): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/CSLegacyTypeTracker(  752): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  752): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  752): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  752): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  752): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/SmartBondingService(  752): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  752): MasterInitialState.processMessage what=3
D/SmartBondingService(  752): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  752): getSBEnabled() enabled =false
D/ConnectivityService(  752): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  752): calling update connectivity
D/ConnectivityService(  752):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  752):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  752): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/SmartBondingService(  752): getSBEnabled() enabled =false
D/ConnectivityService(  752):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  752): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/NetworkStats(  752): updateIfacesLocked()
D/EntConnectivity(  752): Not allowed due to - mEnabled false
V/NetworkStats(  752): performPollLocked(flags=0x1)
D/NtpTrustedTime(  752): currentTimeMillis() cache hit
D/SmartBondingService(  752): getSBEnabled() enabled =false
D/ConnectivityManager.CallbackHandler( 2183): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 1184): CM callback handler got msg 524290
D/NetworkStatsFactory(  752): UpdateStatsForKnox
D/ConnectivityService(  752): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  752): getNetworkEnabled : wifi : true mobile : true
V/NetworkStats(  752): performPollLocked() took 3ms
D/NtpTrustedTime(  752): currentTimeMillis() cache hit
D/NtpTrustedTime(  752): currentTimeMillis() cache hit
D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1184): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1184): updateDataNetType()
D/StatusBar.NetworkController( 1184): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1184): updateLTEICONDataNetType:0
V/NetworkStats(  752): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  752): currentTimeMillis() cache hit
D/NtpTrustedTime(  752): currentTimeMillis() cache hit
D/NtpTrustedTime(  752): currentTimeMillis() cache hit
D/NtpTrustedTime(  752): currentTimeMillis() cache hit
D/NtpTrustedTime(  752): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1184): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1184): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1184): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1184): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
D/StatusBar.NetworkController( 1184): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): applyOpen
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,I/System.out(  752): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/WebViewFactory( 7536): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,D/ResourcesManager( 7536): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  752): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 16 Dec 2015 15:46:25 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450280785497], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450280785479]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  752): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  752): Validated
,D/ConnectivityService(  752): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  752): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  752):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  752):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  752):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  752): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  752): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  752): calling update connectivity
D/ConnectivityService(  752):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  752):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  752): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  752):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  752): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1184): CM callback handler got msg 524290
D/ConnectivityService(  752): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 2183): CM callback handler got msg 524290
,I/LibraryLoader( 7536): Loading: webviewchromium
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1184): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1184): updateDataNetType()
D/StatusBar.NetworkController( 1184): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1184): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1184): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1184): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1184): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1184): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
,I/LibraryLoader( 7536): Time to load native libraries: 6 ms (timestamps 601-607)
,I/LibraryLoader( 7536): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7536): Binding Chromium to main looper Looper (main, tid 1) {2cb3acb3}
,I/LibraryLoader( 7536): Expected native library version number "",actual native library version number ""
,I/chromium( 7536): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7536): Initializing chromium process, renderers=0
,W/art     ( 7536): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7536): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7536): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46780 len=2953
,I/chromium( 7536): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229536 len:643667
,W/AudioManagerAndroid( 7536): Requires BLUETOOTH permission
,I/Adreno-EGL( 7536): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 7536): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7536): Build Date: 11/19/14 Wed
I/Adreno-EGL( 7536): Local Branch: mybranch5813579
I/Adreno-EGL( 7536): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 7536): Local Patches: NONE
I/Adreno-EGL( 7536): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,I/NSApplication( 7536): Starting up...
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  752): Killing 6584:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7608): MountEmulatedStorage()
,E/Zygote  ( 7608): v2
I/libpersona( 7608): KNOX_SDCARD checking this for 10158
I/libpersona( 7608): KNOX_SDCARD not a persona
,I/ActivityManager(  752): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7608 uid=10158 gids={50158, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 7608): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7608): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7608): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7608): TimaSignature is unavailable
,D/ActivityThread( 7608): Added TimaKeyStore provider
,D/ResourcesManager( 7608): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 7608): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7608): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7608): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 7608): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7608): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7608): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7623): MountEmulatedStorage()
,E/Zygote  ( 7623): v2
I/libpersona( 7623): KNOX_SDCARD checking this for 10186
I/libpersona( 7623): KNOX_SDCARD not a persona
,I/SELinux ( 7623): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7623): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,I/ActivityManager(  752): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7623 uid=10186 gids={50186, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,E/SELinux ( 7623): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  752): Killing 6612:com.samsung.android.app.watchmanagerstub/u0a126 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7623): TimaSignature is unavailable
,D/ActivityThread( 7623): Added TimaKeyStore provider
,D/ResourcesManager( 7623): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7623): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7623): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7623): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7623): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7623): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ConnectivityService(  752): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  752): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  752): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  752): SmartBondingReceiver: wifi ap is not changed
D/ConnectivityService(  752): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  752): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/GpsLocationProvider(  752): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  752): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  752): getSBEnabled() enabled =false
D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  752): getSBEnabled() enabled =false
D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  752): getSBEnabled() enabled =false
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  752): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  752): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  752): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  752): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  752): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  752): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  752): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 3371): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
W/ContextImpl( 1915): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
W/ContextImpl( 1915): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,I/DBG_DM  ( 3371): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/NetworkMonitor( 5632): type=WIFI subType= reason=null isConnected=true
,I/art     (  752): Explicit concurrent mark sweep GC freed 82748(4MB) AllocSpace objects, 20(368KB) LOS objects, 17% free, 38MB/46MB, paused 1.312ms total 95.412ms
,D/SecContentProvider2(  752): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  752): mCursor = null
,D/RCPManagerService(  752): exchangeData() failure , invalid userId
,D/ConnectivityService(  752): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
,D/ConnectivityService(  752): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService(  752): identical MTU - not setting
D/ConnectivityService(  752): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  752): updateSourceRoutes : add src route for:fe80::ea50:8bff:fede:28a3
,D/SmartBondingService(  752): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  752): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  752): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  752): getSBEnabled() enabled =false
,V/        (  291): QcRouteController
D/SmartBondingService(  752): getSBEnabled() enabled =false
D/SmartBondingService(  752): getSBEnabled() enabled =false
,D/RCPManagerService(  752): exchangeData() failure , invalid userId
,V/        (  291): QcRouteController
,D/RCPManagerService(  752): exchangeData() failure , invalid userId
,W/NetworkManagementService(  752): route cmd failed: 
W/NetworkManagementService(  752): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '74 route replace src v6 wlan0 fe80::ea50:8bff:fede:28a3 2 ::' failed with '400 74 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  752): '
W/NetworkManagementService(  752): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService(  752): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService(  752): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService(  752): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService(  752): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  752): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5625)
W/NetworkManagementService(  752): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5437)
W/NetworkManagementService(  752): 	at com.android.server.ConnectivityService.access$2300(ConnectivityService.java:229)
W/NetworkManagementService(  752): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2382)
W/NetworkManagementService(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  752): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/Nat464Xlat(  752): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  752): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  752): calling update connectivity
D/ConnectivityService(  752):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  752):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  752): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  752):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1184): CM callback handler got msg 524295
D/ConnectivityService(  752): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  752): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  752): calling update connectivity
D/ConnectivityService(  752):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  752):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 2183): CM callback handler got msg 524295
,D/ConnectivityService(  752): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  752):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1184): CM callback handler got msg 524295
,D/ConnectivityService(  752): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 2183): CM callback handler got msg 524295
,E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService(  752): exchangeData() failure , invalid userId
,E/Zygote  ( 7649): MountEmulatedStorage()
,E/Zygote  ( 7649): v2
I/libpersona( 7649): KNOX_SDCARD checking this for 10092
I/libpersona( 7649): KNOX_SDCARD not a persona
,I/ActivityManager(  752): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7649 uid=10092 gids={50092, 9997} abi=armeabi-v7a
,I/SELinux ( 7649): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  752): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  752): exchangeData() failure , invalid userId
,I/SELinux ( 7649): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,D/RCPManagerService(  752): exchangeData() failure , invalid userId
,E/SELinux ( 7649): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  752): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6941): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6941): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6941): StateMachine : Current State = 1
,D/ConnectivityService(  752): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6941): StateMachine : Changed Current State = 1
E/SMD     (  296): DCD ON
,I/ActivityManager(  752): Killing 6627:com.samsung.helphub/1000 (adj 15): bgCount ##41
,E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
D/ConnectivityService(  752): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  752): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 7649): TimaSignature is unavailable
,D/ActivityThread( 7649): Added TimaKeyStore provider
,E/Zygote  ( 7664): MountEmulatedStorage()
,E/Zygote  ( 7664): v2
I/libpersona( 7664): KNOX_SDCARD checking this for 10200
I/libpersona( 7664): KNOX_SDCARD not a persona
,I/ActivityManager(  752): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7664 uid=10200 gids={50200, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7664): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/ActivityManager(  752): Killing 6666:com.samsung.android.snote:provider/u0a168 (adj 15): bgCount ##41
I/SELinux ( 7664): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7664): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7664): TimaSignature is unavailable
,D/ActivityThread( 7664): Added TimaKeyStore provider
,D/ResourcesManager( 7649): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/BadgeProvider( 7649): onCreate
,D/BadgeProvider( 7649): DatabaseHelper
,D/ResourcesManager( 7664): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,D/BadgeProvider( 7649): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/ActivityManager(  752): Killing 6685:com.sec.kidsplat.installer/u0a189 (adj 15): bgCount ##41
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Launcher.Model( 1446): reloadBadges entered.
D/BadgeProvider( 7649): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7649): sendNotify, [notify] : null
D/BadgeProvider( 7649): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7649): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7649): update, [UpdateCount] : 1
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 5217): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5217): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5217): exit::IDLE
D/InitializeManagerStateMachine( 5217): entry::NETWORK_CHECK
,D/ConnectivityService(  752): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  752): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 5217): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5217): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5217): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5217): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5217): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5217): entry::SUCCESS
D/hcjo    ( 5217): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5217): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 5217): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  752): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 5217): exit::SUCCESS
D/InitializeManagerStateMachine( 5217): entry::IDLE
,D/ConnectivityService(  752): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/Hs20UtilService( 1361): Starting #8
,I/Hs20UtilService( 1361): Message received 5007
,D/NearbySettings( 1361): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1361): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  752): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1361): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/ConnectivityService(  752): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1361): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1361): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1361): MountReceiver.onReceive - Keep current state
,D/ConnectivityService(  752): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ActivityManager(  752): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,E/SignOutReceiver( 6649): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 1361): Starting #9
,I/Hs20UtilService( 1361): Message received 5007
D/NearbySettings( 1361): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1361): MountReceiver.onReceive - Keep current state
,D/ConnectivityService(  752): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6649): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 1361): Starting #10
,D/NearbySettings( 1361): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/Hs20UtilService( 1361): Message received 5007
,V/NearbySettings( 1361): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  752): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1361): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/ConnectivityService(  752): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1361): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1361): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1361): MountReceiver.onReceive - Keep current state
,D/ConnectivityService(  752): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6649): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 1361): Starting #11
,D/NearbySettings( 1361): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/Hs20UtilService( 1361): Message received 5007
I/NearbySettings( 1361): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine(  752): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/ConnectivityService(  752): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6649): NETWORK_STATE_CHANGED_ACTION
,I/PCWCLIENTTRACE_PushUtil( 7356): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7356): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7356): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7356): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/SurfaceFlinger(  256): id=17 createSurf (1x1),1 flag=4, Uoast
,I/DIAGMON_AGENT( 7389): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7389): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/PowerManagerService(  752): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=752
,I/FOTA_Client( 6754): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 6754): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 6754): [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.511: ( 6780): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.511: ( 6780): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450280786631
,I/KLMS-2.4.511: ( 6780): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  752): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  752): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.511: ( 6780): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.511: ( 6780): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.511: ( 6780): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.511: ( 6780): StateImplV2(): networkChangeListener().END
,D/ConnectivityService(  752): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SO_AGENT( 6798): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/ConnectivityService(  752): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  752): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 7442): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 6451): [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
,I/SA      ( 6451): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 6451): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6451): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6451): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 6451): [SCU] == networkStateCheck == true
,I/SA      ( 6451): [DM] getCountryCodeFromCSC : PL
I/SA      ( 6451): isChinaCountryCode : false
I/SA      ( 6451): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6451): [OR] == networkStateCheck true ==
,I/SA      ( 6451): [OR] GetMyCountryZoneTask
,I/SA      ( 6451): [OR] onReceive END
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6451): [SRS] prepareGetMyCountryZone
,I/SCloudBackupReceiver( 7468): Other Intent
,D/ConnectivityService(  752): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6451): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6451): [SSP] query invoked
,I/KnoxUsageLogPro( 7495): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 7495): premStatus:2
,I/KnoxUsageLogPro( 7495): isEulaShown : false
I/KnoxUsageLogPro( 7495): KnoxUsageReceiver onReceive : not Processible, just return
,I/SA      ( 6451): [TPMU] GetMccFromDB : null
I/SA      ( 6451): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6451): [TPM] isNoProxy(default) : true
,E/File    ( 6451): fail readDirectory() errno=2
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 7608): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7608): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7608): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  752): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  752): exchangeData() failure , invalid userId
,D/RCPManagerService(  752): exchangeData() failure , invalid userId
,D/ConnectivityService(  752): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6941): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6941): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6941): StateMachine : Current State = 1
D/ConnectivityService(  752): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6941): StateMachine : Changed Current State = 1
,D/ConnectivityService(  752): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  752): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 5217): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5217): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5217): exit::IDLE
D/InitializeManagerStateMachine( 5217): entry::NETWORK_CHECK
,D/ConnectivityService(  752): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  752): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 5217): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5217): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5217): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5217): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5217): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5217): entry::SUCCESS
D/hcjo    ( 5217): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5217): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 5217): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  752): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 5217): exit::SUCCESS
D/InitializeManagerStateMachine( 5217): entry::IDLE
,I/SA      ( 6451): [RC New] Execute method=[GET] start
,I/SA      ( 6451): [RC New] Security=[true]
,I/System.out( 6451): Thread-1050(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6451): Thread-1050(ApacheHTTPLog):isShipBuild true
I/System.out( 6451): Thread-1050(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,I/jxcore-log( 7216): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 7216): 
,W/ProcessCpuTracker(  752): Skipping unknown process pid 7305
,W/ProcessCpuTracker(  752): Skipping unknown process pid 7306
W/ProcessCpuTracker(  752): Skipping unknown process pid 7307
,W/ProcessCpuTracker(  752): Skipping unknown process pid 7308
W/ProcessCpuTracker(  752): Skipping unknown process pid 7315
,W/ProcessCpuTracker(  752): Skipping unknown process pid 7316
,I/SA      ( 6451): [RC New] [v2liruge] api execute + 864
,I/SA      ( 6451): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6451): AsyncTask #1 calls detatch()
,I/SA      ( 6451): [TPMU] getNetworkMcc : 
,I/SA      ( 6451): [SCU] saveMccToPreferece Start
,I/SA      ( 6451): [SCU] RegionMCC : 260
I/SA      ( 6451): [SSP] query invoked
,I/SA      ( 6451): [TPMU] GetMccFromDB : null
,I/SA      ( 6451): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6451): [SCU] saveMccToPreferece End
,I/SA      ( 6451): [RC New] executeRequest [v2liruge] end. 941
,I/SA      ( 6451): [RC New] Execute end
,I/SA      ( 6451): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 6451): [OR] GetMyCountryZoneTask Success
,W/Atfwd_Sendcmd(  366): AtCmdFwd service not published, waiting... retryCnt : 4
,E/WifiStateMachine(  752): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/dhcpcd  ( 7448): wlan0: sending IPv6 Router Solicitation
,E/SMD     (  296): DCD ON
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  752): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SurfaceFlinger(  256): id=17 Removed Uoast (8/9)
,I/SurfaceFlinger(  256): id=17 Removed Uoast (-2/9)
,D/PowerManagerService(  752): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 752) eventTime = 165147
,D/PowerManagerService(  752): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=752 (0x0)
,D/PowerManagerService(  752): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=752, ws=WorkSource{10067}) (elapsedTime=3504)
,I/GAV4    ( 7536): Thread[GAThread,5,main]: No campaign data found.
,E/Watchdog(  752): !@Sync 5
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7356): mConnectivityHandler : connected
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 7356): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE( 7356): ================================================
,I/CSTORAGE( 7356):  CSTORAGE_SKM_LIB v1.0.6
I/CSTORAGE( 7356): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 7356): [GetString-S]
E/art     ( 7356): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 7356): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI( 7356): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 7356): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7356): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7356): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 7356): [ensureRegistration] - No Samsung account
,V/AlarmManager(  752): waitForAlarm result :4
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PowerManagerService(  752): [PWL] Off : 30s ago
,D/SSRM:n  (  752): SIOP:: AP = 330, PST = 327, CUR = 450
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  752): Plugged
I/MotionRecognitionService(  752): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  752): stay LED for fully charged
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,I/dhcpcd  ( 7448): wlan0: sending IPv6 Router Solicitation
,E/SMD     (  296): DCD ON
,D/PreloadUpdateManagerStateMachine( 5217): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5217): exit::IDLE
D/PreloadUpdateManagerStateMachine( 5217): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5217): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5217): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5217): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5217): entry::IDLE
,W/ContextImpl(  752): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PreloadUpdateManagerStateMachine( 5217): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5217): exit::IDLE
D/PreloadUpdateManagerStateMachine( 5217): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5217): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5217): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5217): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5217): entry::IDLE
,I/dhcpcd  ( 7448): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 7448): wlan0: no IPv6 Routers available
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 310, PST = 321, CUR = 450
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD ON
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,I/PowerManagerService(  752): [PWL] Off : 50s ago
,D/SSRM:n  (  752): SIOP:: AP = 310, PST = 319, CUR = 450
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD ON
,W/Atfwd_Sendcmd(  366): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  296): DCD ON
,W/ContextImpl(  752): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  296): DCD ON
,V/AlarmManager(  752): waitForAlarm result :8
,E/Watchdog(  752): !@Sync 6
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 300, PST = 316, CUR = 450
,V/AlarmManager(  752): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1184): handleTimeUpdate
,D/KeyguardEffectViewController( 1184): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1184): *** don't update sliding image ***
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  752): stay LED for fully charged
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  752): Plugged
I/MotionRecognitionService(  752): setPowerConnected  = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/DateView( 1184): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1184): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PhenotypeConfigurator( 1924): Scheduling Phenotype for one-off execution 1531 seconds from now (1450280823209)
,D/GetConfigurationSnapshotOperation( 1924): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1924): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1924): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  752): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1924): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 1924): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1924): Tagging socket 79 with tag 1000120100000000{268440065,0} uid -1, pid: 1924, getuid(): 10015
,I/qtaguid ( 1924): Tagging socket 86 with tag 1000120100000000{268440065,0} uid -1, pid: 1924, getuid(): 10015
,D/LocationManagerService(  752): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1924): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1924): Tagging socket 79 with tag 1000120100000000{268440065,0} uid -1, pid: 1924, getuid(): 10015
,D/LocationManagerService(  752): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1924): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1924): Tagging socket 79 with tag 1000120100000000{268440065,0} uid -1, pid: 1924, getuid(): 10015
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON,
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 300, PST = 314, CUR = 450
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  752): stay LED for fully charged
,E/SMD     (  296): DCD ON
,W/ContextImpl(  752): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  752): [PWL] Off : 75s ago
,E/SMD     (  296): DCD ON
,I/Atfwd_Sendcmd(  366): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  366): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 300, PST = 312, CUR = 450
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD ON
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,E/Watchdog(  752): !@Sync 7
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,I/ClearcutLoggerApiImpl( 1924): disconnect managed GoogleApiClient
,E/SMD     (  296): DCD ON
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,D/SSRM:n  (  752): SIOP:: AP = 300, PST = 311, CUR = 450
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  752): stay LED for fully charged
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,W/Atfwd_Sendcmd(  366): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  296): DCD ON
,W/ContextImpl(  752): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  296): DCD ON
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD ON
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,D/SSRM:n  (  752): SIOP:: AP = 300, PST = 309, CUR = 450
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  752): stay LED for fully charged
,W/Atfwd_Sendcmd(  366): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  296): DCD ON
,I/PowerManagerService(  752): [PWL] Off : 105s ago
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 300, PST = 308, CUR = 450
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/BatteryService(  752): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,E/SMD     (  296): DCD ON
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD ON
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,W/ContextImpl(  752): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  366): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  296): DCD ON
,V/AlarmManager(  752): waitForAlarm result :8
,E/Watchdog(  752): !@Sync 8
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 300, PST = 305, CUR = 450
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
I/MotionRecognitionService(  752): Plugged
I/MotionRecognitionService(  752): setPowerConnected  = true
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  752): stay LED for fully charged
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 290, PST = 301, CUR = 450
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD ON
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,W/ContextImpl(  752): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  296): DCD ON
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  366): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  296): DCD ON
,I/PowerManagerService(  752): [PWL] Off : 140s ago
,D/SSRM:n  (  752): SIOP:: AP = 290, PST = 299, CUR = 450
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  752): stay LED for fully charged
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/Watchdog(  752): !@Sync 9
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 290, PST = 297, CUR = 450
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD ON
,W/ContextImpl(  752): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  296): DCD ON
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD ON
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,D/SSRM:n  (  752): SIOP:: AP = 290, PST = 296, CUR = 450
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  366): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 290, PST = 295, CUR = 450
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD ON
,W/ContextImpl(  752): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService(  752): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  752): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  752): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  752): initializing...
,I/TLC_TIMA_PKM_initialize(  752): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  752): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  752): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication(  752): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  752): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  752): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  752): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  752): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  752): App is not loaded in QSEE
,D/QSEECOMAPI: (  752): Loaded image: APP id = 3,
,I/TZ: qc_tlc_communication(  752): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  752): Trustlet response is completed
,E/SMD     (  296): DCD ON
,E/Watchdog(  752): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel(  752): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  752): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  752): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  752): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/PowerManagerService(  752): [PWL] Off : 180s ago
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 300, PST = 295, CUR = 450
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/BatteryService(  752): stay LED for fully charged
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,I/Atfwd_Sendcmd(  366): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  366): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 290, PST = 294, CUR = 450
,E/SMD     (  296): DCD ON
,W/ContextImpl(  752): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  296): DCD ON
,V/AlarmManager(  752): waitForAlarm result :4
,E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  752): stay LED for fully charged
,I/ActivityManager(  752): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=7766 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1184): handleTimeUpdate
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,E/Zygote  ( 7766): MountEmulatedStorage()
,E/Zygote  ( 7766): v2
I/libpersona( 7766): KNOX_SDCARD checking this for 10096
I/libpersona( 7766): KNOX_SDCARD not a persona
,D/KeyguardEffectViewController( 1184): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1184): *** don't update sliding image ***
,I/MotionRecognitionService(  752): Plugged
I/MotionRecognitionService(  752): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
I/SELinux ( 7766): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
I/SELinux ( 7766): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SELinux ( 7766): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/DateView( 1184): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1184): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/TimaKeyStoreProvider( 7766): TimaSignature is unavailable
,D/ActivityThread( 7766): Added TimaKeyStore provider
,D/ResourcesManager( 7766): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,I/ActivityManager(  752): Killing 6010:com.android.vending/u0a33 (adj 15): bgCount ##41
,E/SMD     (  296): DCD ON
,I/ActivityManager(  752): Killing 4334:com.sec.android.app.shealth/u0a40 (adj 15): bgCount ##41
,D/SSRM:n  (  752): SIOP:: AP = 290, PST = 293, CUR = 450
,E/SMD     (  296): DCD ON
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD ON
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,I/jxcore-log( 7216): Connected to the server!
I/jxcore-log( 7216): 
,I/chromium( 7216): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  366): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  296): DCD ON
,E/Watchdog(  752): !@Sync 11
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 290, PST = 292, CUR = 450
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD ON
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,W/ContextImpl(  752): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  366): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 290, PST = 291, CUR = 450
,E/SMD     (  296): DCD ON
,I/PowerManagerService(  752): [PWL] Off : 225s ago
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  752): Plugged
I/MotionRecognitionService(  752): setPowerConnected  = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  752): stay LED for fully charged
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD ON
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 290, PST = 291, CUR = 450
,W/Atfwd_Sendcmd(  366): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  296): DCD ON
,W/ContextImpl(  752): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  752): stay LED for fully charged
,E/SMD     (  296): DCD ON
,V/AlarmManager(  752): waitForAlarm result :8
,E/Watchdog(  752): !@Sync 12
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 290, PST = 291, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON,
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,I/MotionRecognitionService(  752): Plugged
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  752): setPowerConnected  = true
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,D/BatteryService(  752): stay LED for fully charged
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD ON
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,D/SSRM:n  (  752): SIOP:: AP = 290, PST = 291, CUR = 450
,W/Atfwd_Sendcmd(  366): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  296): DCD ON
,W/ContextImpl(  752): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): stay LED for fully charged
D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 290, PST = 291, CUR = 450
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD ON
,E/Watchdog(  752): !@Sync 13
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 290, PST = 291, CUR = 450
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD ON
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,W/ContextImpl(  752): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  752): [PWL] Off : 275s ago
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD ON
,W/Atfwd_Sendcmd(  366): AtCmdFwd service not published, waiting... retryCnt : 5
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/BatteryService(  752): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  296): DCD ON
,W/ContextImpl(  752): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD ON
,E/Watchdog(  752): !@Sync 14
,E/SMD     (  296): DCD ON
,I/Atfwd_Sendcmd(  366): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  366): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:n  (  752): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,I/MotionRecognitionService(  752): Plugged
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/BatteryService(  752): stay LED for fully charged
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  296): DCD ON
,W/ContextImpl(  752): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): stay LED for fully charged
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,D/SSRM:n  (  752): SIOP:: AP = 290, PST = 290, CUR = 450
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD ON
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  366): AtCmdFwd service not published, waiting... retryCnt : 1
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD ON
,E/Watchdog(  752): !@Sync 15
,I/PowerManagerService(  752): [PWL] Off : 330s ago
,E/SMD     (  296): DCD ON
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,D/SSRM:n  (  752): SIOP:: AP = 290, PST = 290, CUR = 450
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD ON
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,W/ContextImpl(  752): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD ON
,W/Atfwd_Sendcmd(  366): AtCmdFwd service not published, waiting... retryCnt : 2
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/BatteryService(  752): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): stay LED for fully charged
D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  752): Plugged
I/MotionRecognitionService(  752): setPowerConnected  = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,I/bootchecker(  360): bootchecker wake up!!
,E/SMD     (  296): DCD ON
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD ON
,W/Atfwd_Sendcmd(  366): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:n  (  752): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  296): DCD ON
,W/ContextImpl(  752): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD ON
,E/Watchdog(  752): !@Sync 16
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  752): stay LED for fully charged
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  752): Plugged
I/MotionRecognitionService(  752): setPowerConnected  = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD ON
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  366): AtCmdFwd service not published, waiting... retryCnt : 4
,D/SSRM:n  (  752): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  296): DCD ON
,W/ContextImpl(  752): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  752): stay LED for fully charged
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
I/MotionRecognitionService(  752): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  752): stay LED for fully charged
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
I/MotionRecognitionService(  752): Plugged
I/MotionRecognitionService(  752): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  752): !@Sync 17
,I/PowerManagerService(  752): [PWL] Off : 390s ago
,E/SMD     (  296): DCD ON
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 289, CUR = 450
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD ON
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,W/ContextImpl(  752): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  366): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD ON
,W/Atfwd_Sendcmd(  366): AtCmdFwd service not published, waiting... retryCnt : 5
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  752): stay LED for fully charged
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
I/MotionRecognitionService(  752): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 288, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  752): stay LED for fully charged
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 287, CUR = 450
,E/SMD     (  296): DCD ON
,W/ContextImpl(  752): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  296): DCD ON
,V/AlarmManager(  752): waitForAlarm result :8
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  752): !@Sync 18
,E/SMD     (  296): DCD ON
,I/Atfwd_Sendcmd(  366): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  366): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 286, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 285, CUR = 450
,W/ContextImpl(  752): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
I/MotionRecognitionService(  752): setPowerConnected  = true
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  752): stay LED for fully charged
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 284, CUR = 450
,E/SMD     (  296): DCD ON
,I/Atfwd_Daemon(  366): Stop the daemon....
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  752): stay LED for fully charged
,E/Watchdog(  752): !@Sync 19
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 283, CUR = 450
,E/SMD     (  296): DCD ON
,W/ContextImpl(  752): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  752): [PWL] Off : 455s ago
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 282, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  296): DCD ON
,W/ContextImpl(  752): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService(  752): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  752): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  752): TimaServiceHandler.handleMessage what =1
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
D/BatteryService(  752): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,E/Watchdog(  752): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel(  752): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  752): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  752): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  752): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 290, PST = 281, CUR = 450,
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  752): Plugged
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/BatteryService(  752): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 281, CUR = 450
,W/ContextImpl(  752): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  752): !@Sync 21
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/BatteryService(  752): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 281, CUR = 450
,I/PowerManagerService(  752): [PWL] Off : 525s ago
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  752): !@Sync 22
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/BatteryService(  752): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  752): stay LED for fully charged
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/Watchdog(  752): !@Sync 23
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
I/MotionRecognitionService(  752): Plugged
I/MotionRecognitionService(  752): setPowerConnected  = true
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  752): stay LED for fully charged
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  752): stay LED for fully charged
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2915): Disconnected process message: 10
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  752): stay LED for fully charged
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/Watchdog(  752): !@Sync 24
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService(  752): [PWL] Off : 600s ago
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/Watchdog(  752): !@Sync 25
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/BatteryService(  752): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged,
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  752): stay LED for fully charged
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  752): setPowerConnected  = true
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  752): stay LED for fully charged
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/Watchdog(  752): !@Sync 26
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  752): stay LED for fully charged
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  752): stay LED for fully charged
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,I/PowerManagerService(  752): [PWL] Off : 680s ago
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/Watchdog(  752): !@Sync 27
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  752): stay LED for fully charged
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  752): stay LED for fully charged
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/Watchdog(  752): !@Sync 28
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/BatteryService(  752): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,I/MotionRecognitionService(  752): Plugged
I/MotionRecognitionService(  752): setPowerConnected  = true
,D/BatteryService(  752): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/Watchdog(  752): !@Sync 29
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  752): stay LED for fully charged
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  752): stay LED for fully charged
D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,I/PowerManagerService(  752): [PWL] Off : 765s ago
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/BatteryService(  752): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,D/TimaService(  752): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  752): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  752): TimaServiceHandler.handleMessage what =1
,E/SMD     (  296): DCD ON
,E/Watchdog(  752): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel(  752): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  752): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  752): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  752): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  752): stay LED for fully charged
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
I/MotionRecognitionService(  752): Plugged
I/MotionRecognitionService(  752): setPowerConnected  = true
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  752): stay LED for fully charged
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/Watchdog(  752): !@Sync 31
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  752): stay LED for fully charged
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/BatteryService(  752): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  752): stay LED for fully charged
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/Watchdog(  752): !@Sync 32
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  752): stay LED for fully charged
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,I/PowerManagerService(  752): [PWL] Off : 855s ago
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/BatteryService(  752): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/Watchdog(  752): !@Sync 33
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/BatteryService(  752): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,I/MotionRecognitionService(  752): Plugged
I/MotionRecognitionService(  752): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  752): stay LED for fully charged
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/BatteryService(  752): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/Watchdog(  752): !@Sync 34
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/BatteryService(  752): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/BatteryService(  752): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/BatteryService(  752): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/Watchdog(  752): !@Sync 35
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  752): Plugged
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/BatteryService(  752): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,I/MotionRecognitionService(  752): Plugged
I/MotionRecognitionService(  752): setPowerConnected  = true
,D/BatteryService(  752): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,I/PowerManagerService(  752): [PWL] Off : 950s ago
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,I/MotionRecognitionService(  752): Plugged
I/MotionRecognitionService(  752): setPowerConnected  = true
,D/BatteryService(  752): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/Watchdog(  752): !@Sync 36
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/BatteryService(  752): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/BatteryService(  752): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2915): Disconnected process message: 10
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/Watchdog(  752): !@Sync 37
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/BatteryService(  752): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  752): Plugged
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/BatteryService(  752): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/Watchdog(  752): !@Sync 38
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/BatteryService(  752): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  752): Plugged
I/MotionRecognitionService(  752): setPowerConnected  = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
D/BatteryService(  752): stay LED for fully charged
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,I/MotionRecognitionService(  752): Plugged
I/MotionRecognitionService(  752): setPowerConnected  = true
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  752): stay LED for fully charged
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/Watchdog(  752): !@Sync 39
,I/PowerManagerService(  752): [PWL] Off : 1050s ago
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  752): stay LED for fully charged
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  752): stay LED for fully charged
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,D/TimaService(  752): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  752): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  752): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService(  752): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  752): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  752): Updating Usage Statistics in DB @ 1450281838901
,I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
,W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
,W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
,W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
,W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
,W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  752): ::getAppControlDB: Exception to create DB
W/System.err(  752): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  752): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  752): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage(  752): Done Updating Usage Statistics in DB @ 1450281839111
,E/SMD     (  296): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  752): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  752): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  752): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  752): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  752): !@Sync 40
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/BatteryService(  752): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,I/MotionRecognitionService(  752): setPowerConnected  = true
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  752): stay LED for fully charged
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/BatteryService(  752): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/Watchdog(  752): !@Sync 41
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  752): setPowerConnected  = true
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/BatteryService(  752): stay LED for fully charged
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/Watchdog(  752): !@Sync 42
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/BatteryService(  752): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService(  752): [PWL] Off : 1155s ago
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  752): stay LED for fully charged
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/Watchdog(  752): !@Sync 43
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  752): Plugged
I/MotionRecognitionService(  752): setPowerConnected  = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  752): stay LED for fully charged
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  752): stay LED for fully charged
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
I/MotionRecognitionService(  752): Plugged
I/MotionRecognitionService(  752): setPowerConnected  = true
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  752): stay LED for fully charged
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/Watchdog(  752): !@Sync 44
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  752): stay LED for fully charged
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  752): stay LED for fully charged
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  752): stay LED for fully charged
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/Watchdog(  752): !@Sync 45
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  752): stay LED for fully charged
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
D/BatteryService(  752): stay LED for fully charged
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  752): stay LED for fully charged
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/Watchdog(  752): !@Sync 46
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  752): stay LED for fully charged
,E/SMD     (  296): DCD ON
,I/PowerManagerService(  752): [PWL] Off : 1265s ago
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
I/MotionRecognitionService(  752): Plugged
I/MotionRecognitionService(  752): setPowerConnected  = true
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  752): stay LED for fully charged
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  752): stay LED for fully charged
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/Watchdog(  752): !@Sync 47
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
I/MotionRecognitionService(  752): setPowerConnected  = true
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  752): stay LED for fully charged
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  752): stay LED for fully charged
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/Watchdog(  752): !@Sync 48
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  752): stay LED for fully charged
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/Watchdog(  752): !@Sync 49
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
D/BatteryService(  752): stay LED for fully charged
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  752): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  752): stay LED for fully charged
,E/SMD     (  296): DCD ON
,D/TimaService(  752): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  752): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  752): TimaServiceHandler.handleMessage what =1
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/Watchdog(  752): !@Sync 50
,I/TLC_TIMA_PKM_measure_kernel(  752): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  752): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  752): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  752): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/PowerManagerService(  752): [PWL] Off : 1380s ago
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/Watchdog(  752): !@Sync 51
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  752): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/Watchdog(  752): !@Sync 52
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  752): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0,
D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  752): stay LED for fully charged
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  752): !@Sync 53
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,V/AlarmManager(  752): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1184): handleTimeUpdate
,D/KeyguardEffectViewController( 1184): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1184): *** don't update sliding image ***
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/LightsService(  752): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  752): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager(  752): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,D/DateView( 1184): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1184): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/LightsService(  752): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  752): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  752): unregisterListener ::   
,D/LightsService(  752): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  752): waitForAlarm result :8
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Watchdog(  752): !@Sync 54
,I/PowerManagerService(  752): [PWL] Off : 1500s ago
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/BatteryService(  752): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,V/AlarmManager(  752): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1184): handleTimeUpdate
,D/KeyguardEffectViewController( 1184): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1184): *** don't update sliding image ***
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/ConnectivityService(  752): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1184): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1184): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  752): !@Sync 55
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  752): stay LED for fully charged
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,V/AlarmManager(  752): waitForAlarm result :8
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  752): stay LED for fully charged
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  752): !@Sync 56
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  752): !@Sync 57
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  752): stay LED for fully charged
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/BatteryService(  752): stay LED for fully charged
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  752): !@Sync 58
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,I/PowerManagerService(  752): [PWL] Off : 1625s ago
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  752): stay LED for fully charged
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  752): !@Sync 59
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,I/MotionRecognitionService(  752): Plugged
I/MotionRecognitionService(  752): setPowerConnected  = true
,D/BatteryService(  752): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/NetworkStatsFactory(  752): UpdateStatsForKnox
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/TimaService(  752): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  752): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  752): TimaServiceHandler.handleMessage what =1
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,I/TLC_TIMA_PKM_measure_kernel(  752): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  752): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,D/TimaService(  752): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  752): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  752): !@Sync 60
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  752): stay LED for fully charged
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  752): !@Sync 61
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  752): stay LED for fully charged
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,I/MotionRecognitionService(  752): Plugged
I/MotionRecognitionService(  752): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,I/MotionRecognitionService(  752): Plugged
I/MotionRecognitionService(  752): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  752): stay LED for fully charged
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/Watchdog(  752): !@Sync 62
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
I/MotionRecognitionService(  752): Plugged
I/MotionRecognitionService(  752): setPowerConnected  = true
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/BatteryService(  752): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/BatteryService(  752): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,I/PowerManagerService(  752): [PWL] Off : 1755s ago
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,I/MotionRecognitionService(  752): Plugged
I/MotionRecognitionService(  752): setPowerConnected  = true
,D/BatteryService(  752): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/Watchdog(  752): !@Sync 63
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/BatteryService(  752): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/Watchdog(  752): !@Sync 64
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  752): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,I/MotionRecognitionService(  752): Plugged
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  752): stay LED for fully charged
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/Watchdog(  752): !@Sync 65
,D/BatteryService(  752): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  752): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  752): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  752): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  752): Plugged
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,I/MotionRecognitionService(  752): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  752): stay LED for fully charged
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2915): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2915): Disconnected process message: 10
,D/SSRM:n  (  752): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  296): DCD ON
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 7915): 
D/AndroidRuntime( 7915): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7915): CheckJNI is OFF
D/AndroidRuntime( 7915): readGMSProperty: start
D/AndroidRuntime( 7915): readGMSProperty: already setted!!
D/AndroidRuntime( 7915): readGMSProperty: end
D/AndroidRuntime( 7915): addProductProperty: start
E/AffinityControl( 7915): AffinityControl: registerfunction enter
D/AndroidRuntime( 7915): Calling main entry com.android.commands.pm.Pm
D/PackageManager(  752): START PACKAGE DELETE: observer{818178090}
D/PackageManager(  752): pkg{<packageName>}
D/PackageManager(  752): user{0}
D/PackageManager(  752): caller{2000}
D/PackageManager(  752): flags{3}
D/PersonaManagerService(  752): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  752): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  752): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  752): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  752): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  752): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  752): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  752): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  752): getApplicationUninstallationEnabled
D/ApplicationPolicy(  752): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  752): !@killApplicatoin: 10296, uninstall pkg
I/ActivityManager(  752): Force stopping com.test.thalitest appid=10296 user=-1: uninstall pkg
I/ActivityManager(  752): Killing 7216:com.test.thalitest/u0a296 (adj 0): stop com.test.thalitest
W/PackageSettings(  752): Skipping PackageSetting{1910c392 com.example.hello/10292} due to missing metadata
I/WindowState(  752): WIN DEATH: Window{17ecc64d u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  256): id=16 Removed NainActivit (5/8)
I/SurfaceFlinger(  256): id=16 Removed NainActivit (-2/8)
I/SurfaceFlinger(  256): id=16 Removed NainActivit (-2/8)
D/PointerIcon(  752): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  752): setMouseCustomIcon IconType is same.101
D/PointerIcon(  752): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  752): setHoveringSpenCustomIcon IconType is same.1
I/ActivityManager(  752): Killing 7518:com.android.chrome/u0a104 (adj 11): empty for 1808s
E/lowmemorykiller(  253): Error writing /proc/7518/oom_score_adj; errno=22
I/ActivityManager(  752): Killing 4177:com.sec.chaton/u0a102 (adj 11): empty for 1808s
I/ActivityManager(  752): Killing 7495:com.sec.knox.bridge/1000 (adj 11): empty for 1808s
I/ActivityManager(  752): Killing 7468:com.samsung.android.scloud.backup/u0a74 (adj 11): empty for 1808s
I/ActivityManager(  752): Killing 6451:com.osp.app.signin/u0a50 (adj 11): empty for 1808s
I/ActivityManager(  752): Killing 7422:com.policydm/1000 (adj 11): empty for 1808s
E/SMD     (  296): DCD ON
I/ActivityManager(  752): Killing 6798:com.sec.android.soagent/u0a42 (adj 11): empty for 1808s
I/ActivityManager(  752): Killing 7309:com.vlingo.midas/u0a38 (adj 11): empty for 1808s
I/ActivityManager(  752): Killing 7405:com.samsung.android.app.pinboard:tagService/u0a36 (adj 11): empty for 1808s
I/ActivityManager(  752): Killing 6780:com.samsung.klmsagent/u0a23 (adj 11): empty for 1808s
I/ActivityManager(  752): Killing 6754:com.sec.android.fotaclient/u0a14 (adj 11): empty for 1808s
I/ActivityManager(  752): Killing 7389:com.sec.android.diagmonagent/1000 (adj 11): empty for 1808s
I/ActivityManager(  752): Killing 7372:com.sec.android.cloudagent/u0a4 (adj 13): empty for 1808s
I/ActivityManager(  752): Killing 7356:com.sec.pcw.device/1000 (adj 13): empty for 1808s
I/ActivityManager(  752): Killing 6649:com.samsung.android.snote/u0a168 (adj 13): empty for 1808s
I/ActivityManager(  752): Killing 7649:com.sec.android.provider.badge/u0a92 (adj 13): empty for 1809s
I/ActivityManager(  752): Killing 7129:com.sec.android.widgetapp.activeapplicationwidget/u0a182 (adj 13): empty for 1833s
I/ActivityManager(  752): Killing 7113:com.sec.android.widgetapp.dualclockdigital/u0a115 (adj 13): empty for 1859s
I/ActivityManager(  752): Killing 7098:com.sec.android.widgetapp.digitalclock/u0a109 (adj 13): empty for 1859s
I/ActivityManager(  752): Killing 6471:com.android.mms/u0a55 (adj 13): empty for 1859s
I/ActivityManager(  752): Killing 5699:com.sec.android.gallery3d/u0a53 (adj 13): empty for 1859s
I/ActivityManager(  752): Killing 6924:com.android.providers.calendar/u0a51 (adj 15): empty for 1870s
I/ActivityManager(  752): Killing 6895:com.android.calendar/u0a172 (adj 15): empty for 1871s
I/ActivityManager(  752): Killing 6996:com.sec.android.widgetapp.SPlannerAppWidget/u0a171 (adj 15): empty for 1871s
I/ActivityManager(  752): Killing 6958:com.qualcomm.timeservice/1000 (adj 15): empty for 1873s
I/ActivityManager(  752): Killing 5979:com.sec.android.app.controlpanel/u0a134 (adj 15): empty for 1874s
I/ActivityManager(  752): Killing 6870:com.sec.esdk.elm/u0a116 (adj 15): empty for 1874s
I/ActivityManager(  752): Killing 6843:com.sec.android.app.clockpackage/u0a106 (adj 15): empty for 1874s
I/ActivityManager(  752): Killing 6816:com.samsung.android.scloud.sync/u0a76 (adj 15): empty for 1875s
I/ActivityManager(  752):   Force finishing activity ActivityRecord{24c0368f u0 com.test.thalitest/.MainActivity t4}
D/FocusedStackFrame(  752): Set to : 0
I/ActivityManager(  752): Force stopping com.test.thalitest appid=10296 user=0: pkg removed
I/ActivityManager(  752):   Force finishing activity ActivityRecord{24c0368f u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager(  752): Duplicate finish request for ActivityRecord{24c0368f u0 com.test.thalitest/.MainActivity t4 f}
I/art     ( 1580): Explicit concurrent mark sweep GC freed 3233(382KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 19MB/31MB, paused 573us total 30.861ms
I/art     ( 4241): Explicit concurrent mark sweep GC freed 34474(1920KB) AllocSpace objects, 9(144KB) LOS objects, 40% free, 15MB/26MB, paused 488us total 29.225ms
I/art     ( 2183): Explicit concurrent mark sweep GC freed 4748(199KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 22MB/30MB, paused 590us total 99.069ms
W/ActivityManager(  752): Spurious death for ProcessRecord{15d9561b 7216:com.test.thalitest/u0a296}, curProc for 7216: null
W/libprocessgroup(  752): failed to open /acct/uid_10092/pid_7649/cgroup.procs: No such file or directory
W/libprocessgroup(  752): failed to open /acct/uid_10104/pid_7518/cgroup.procs: No such file or directory
W/libprocessgroup(  752): failed to open /acct/uid_10102/pid_4177/cgroup.procs: No such file or directory
W/libprocessgroup(  752): failed to open /acct/uid_10109/pid_7098/cgroup.procs: No such file or directory
W/libprocessgroup(  752): failed to open /acct/uid_10055/pid_6471/cgroup.procs: No such file or directory
W/libprocessgroup(  752): failed to open /acct/uid_10050/pid_6451/cgroup.procs: No such file or directory
W/libprocessgroup(  752): failed to open /acct/uid_1000/pid_7422/cgroup.procs: No such file or directory
D/CountryDetector(  752): No listener is left
W/libprocessgroup(  752): failed to open /acct/uid_10042/pid_6798/cgroup.procs: No such file or directory
W/libprocessgroup(  752): failed to open /acct/uid_10053/pid_5699/cgroup.procs: No such file or directory
W/libprocessgroup(  752): failed to open /acct/uid_10036/pid_7405/cgroup.procs: No such file or directory
W/libprocessgroup(  752): failed to open /acct/uid_10023/pid_6780/cgroup.procs: No such file or directory
W/libprocessgroup(  752): failed to open /acct/uid_1000/pid_6958/cgroup.procs: No such file or directory
W/libprocessgroup(  752): failed to open /acct/uid_1000/pid_7389/cgroup.procs: No such file or directory
W/libprocessgroup(  752): failed to open /acct/uid_10004/pid_7372/cgroup.procs: No such file or directory
W/libprocessgroup(  752): failed to open /acct/uid_1000/pid_7356/cgroup.procs: No such file or directory
W/libprocessgroup(  752): failed to open /acct/uid_10168/pid_6649/cgroup.procs: No such file or directory
I/ProcessStatsService(  752): Prepared write state in 6ms
W/libprocessgroup(  752): failed to open /acct/uid_10182/pid_7129/cgroup.procs: No such file or directory
W/libprocessgroup(  752): failed to open /acct/uid_10115/pid_7113/cgroup.procs: No such file or directory
W/libprocessgroup(  752): failed to open /acct/uid_10051/pid_6924/cgroup.procs: No such file or directory
W/libprocessgroup(  752): failed to open /acct/uid_10171/pid_6996/cgroup.procs: No such file or directory
W/libprocessgroup(  752): failed to open /acct/uid_10134/pid_5979/cgroup.procs: No such file or directory
W/libprocessgroup(  752): failed to open /acct/uid_10172/pid_6895/cgroup.procs: No such file or directory
W/libprocessgroup(  752): failed to open /acct/uid_10106/pid_6843/cgroup.procs: No such file or directory
W/libprocessgroup(  752): failed to open /acct/uid_10076/pid_6816/cgroup.procs: No such file or directory
W/libprocessgroup(  752): failed to open /acct/uid_1000/pid_7495/cgroup.procs: No such file or directory
W/libprocessgroup(  752): failed to open /acct/uid_10074/pid_7468/cgroup.procs: No such file or directory
W/libprocessgroup(  752): failed to open /acct/uid_10038/pid_7309/cgroup.procs: No such file or directory
W/libprocessgroup(  752): failed to open /acct/uid_10014/pid_6754/cgroup.procs: No such file or directory
W/libprocessgroup(  752): failed to open /acct/uid_10116/pid_6870/cgroup.procs: No such file or directory
I/ProcessStatsService(  752): Prepared write state in 6ms
D/ConnectivityService(  752): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager(  752): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
I/art     (  752): Explicit concurrent mark sweep GC freed 18745(1738KB) AllocSpace objects, 20(320KB) LOS objects, 17% free, 38MB/46MB, paused 1.787ms total 158.202ms
D/ResourcesManager( 1446): creating new AssetManager and set to /system/priv-app/StoryAlbumWidget/StoryAlbumWidget.apk
D/ResourcesManager(  752): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/art     (  752): WaitForGcToComplete blocked for 25.248ms for cause Explicit
W/ResourcesManager( 1446): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1446): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
D/ResourcesManager( 1446): creating new AssetManager and set to /system/app/AccuweatherPhone2013_H_LMR/AccuweatherPhone2013_H_LMR.apk
W/ResourcesManager( 1446): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1446): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1446): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
D/ResourcesManager( 1446): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
I/InputReader(  752): Reconfiguring input devices.  changes=0x00000010
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
E/SamsungIME( 1723): mOCRHelper is null
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
W/GeofencerStateMachine( 1924): Ignoring removeGeofence because network location is disabled.
W/ResourcesManager( 1446): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1446): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
D/ResourcesManager(  752): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ResourcesManager(  752): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
D/ResourcesManager(  752): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
E/Zygote  ( 7952): MountEmulatedStorage()
E/Zygote  ( 7952): v2
I/libpersona( 7952): KNOX_SDCARD checking this for 10023
I/libpersona( 7952): KNOX_SDCARD not a persona
D/ResourcesManager(  752): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  752): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
I/ActivityManager(  752): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7952 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
D/ResourcesManager(  752): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
I/ProcessStatsService(  752): Prepared write state in 10ms
D/ResourcesManager(  752): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
I/ProcessStatsService(  752): Prepared write state in 8ms
I/SELinux ( 7952): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/ResourcesManager(  752): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
I/SELinux ( 7952): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7952): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(  752): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
I/ProcessStatsService(  752): Prepared write state in 18ms
D/ResourcesManager(  752): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
I/ProcessStatsService(  752): Prepared write state in 21ms
D/TimaKeyStoreProvider( 7952): TimaSignature is unavailable
D/ActivityThread( 7952): Added TimaKeyStore provider
D/ResourcesManager(  752): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
I/ProcessStatsService(  752): Prepared write state in 17ms
I/ProcessStatsService(  752): Pruning old procstats: /data/system/procstats/state-2015-12-16-02-32-16.bin
D/ResourcesManager(  752): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
D/ResourcesManager(  752): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager(  752): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/SurfaceWidgetView( 1446): destroyHardwareResources():523058240
D/ResourcesManager(  752): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
I/ProcessStatsService(  752): Prepared write state in 12ms
V/WindowOrientationListener(  752): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  752): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  752): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  752): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  752): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
I/ProcessStatsService(  752): Prepared write state in 10ms
D/Launcher( 1446): onRestart, Launcher: 347126758
I/ProcessStatsService(  752): Prepared write state in 10ms
D/Launcher( 1446): onStart, Launcher: 347126758
D/Launcher.HomeView( 1446): onStart
V/ActivityThread( 1446): updateVisibility : ActivityRecord{d603dbc token=android.os.BinderProxy@39c0f80 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/SecContentProvider2(  752): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  752): mCursor = null
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1812): [237392/8] Surface widget visibility changed visibility = true on instance = 1
D/ResourcesManager( 7952): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
D/SurfaceWidget.Renderer( 1812): [237392/8] SurfaceWidget drawing first frame
D/accuweather( 1812): [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
I/SurfaceFlinger(  256): id=18 createSurf (1080x1920),1 flag=4, Mauncher
I/ProcessStatsService(  752): Prepared write state in 18ms
D/StatusBarManagerService(  752): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  752): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon(  752): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  752): setMouseCustomIcon IconType is same.101
D/PointerIcon(  752): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  752): setHoveringSpenCustomIcon IconType is same.1
I/ProcessStatsService(  752): Prepared write state in 12ms
D/ResourcesManager(  752): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager(  752): creating new AssetManager and set to /system/app/Books/Books.apk
D/RegisteredServicesCache( 1404): empty dynamic service
D/ResourcesManager(  752): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
I/ProcessStatsService(  752): Prepared write state in 18ms
I/KLMS-2.4.511: ( 7952): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/ResourcesManager(  752): creating new AssetManager and set to /system/app/Drive/Drive.apk
I/KLMS-2.4.511: ( 7952): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1450282597565
I/KLMS-2.4.511: ( 7952): MainReciver(): PACKAGE_REMOVED
I/KLMS-2.4.511: ( 7952): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
D/ResourcesManager(  752): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
I/ProcessStatsService(  752): Prepared write state in 10ms
D/ResourcesManager(  752): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager(  752): creating new AssetManager and set to /system/app/Music2/Music2.apk
I/ProcessStatsService(  752): Prepared write state in 10ms
D/ResourcesManager(  752): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  752): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
I/ProcessStatsService(  752): Prepared write state in 10ms
D/ResourcesManager(  752): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
I/ProcessStatsService(  752): Prepared write state in 10ms
D/ResourcesManager(  752): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ResourcesManager(  752): creating new AssetManager and set to /system/app/Videos/Videos.apk
I/ProcessStatsService(  752): Prepared write state in 19ms
D/ResourcesManager(  752): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
D/RCPManagerService(  752): PackageReceiver onReceive()
I/HarmonyEASService(  752): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy(  752): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  752): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  752): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  752): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  752): uID is 10296
V/EnterpriseBillingPolicy(  752): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  752): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  752): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  752): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  752): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  752): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  752): getBillingProfileForVpnEngine - end - null
D/TaskPersister(  752): removeObsoleteFile: deleting file=4_task.xml
D/InputMethodManagerService(  752): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  752): checkUser: useridlist=null, currentuser=0
W/InputMethodManagerService(  752): Got RemoteException sending setActive(false) notification to pid 7216 uid 10296
D/ResourcesManager(  752): creating new AssetManager and set to /system/app/talkback/talkback.apk
W/ContextImpl(  752): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
E/Zygote  ( 7973): MountEmulatedStorage()
E/Zygote  ( 7973): v2
I/libpersona( 7973): KNOX_SDCARD checking this for 10116
I/libpersona( 7973): KNOX_SDCARD not a persona
I/art     (  752): Explicit concurrent mark sweep GC freed 15544(926KB) AllocSpace objects, 4(115KB) LOS objects, 17% free, 38MB/46MB, paused 3.011ms total 413.366ms
I/SELinux ( 7973): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7973): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
I/ActivityManager(  752): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7973 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
E/SELinux ( 7973): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/EnterpriseDeviceManagerService(  752): Package has changed for user 0
D/EnterpriseDeviceManagerService(  752): Admin package name: com.google.android.gms
I/ActivityManager(  752): Killing 7536:com.google.android.apps.magazines/u0a146 (adj 15): empty for 1810s
D/TimaKeyStoreProvider( 7973): TimaSignature is unavailable
D/ActivityThread( 7973): Added TimaKeyStore provider
D/ResourcesManager(  752): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
D/ResourcesManager(  752): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
W/Resources(  752): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  752): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
W/Resources(  752): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  752): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  752): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  752): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
W/Resources(  752): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  752): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/ResourcesManager(  752): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/ResourcesManager(  752): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
W/Resources(  752): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  752): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
W/Resources(  752): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  752): creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
W/Resources(  752): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  752): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/PackageManager(  752): delete codoeFile: 
D/ResourcesManager(  752): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
I/AASAUninstall(  752):  com.test.thalitest not target!
D/PackageManager(  752): result of delete: 1{818178090}
W/Resources(  752): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  752): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/AndroidRuntime( 7915): Shutting down VM
D/ResourcesManager(  752): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  752): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  752): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
W/Resources(  752): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  752): creating new AssetManager and set to /system/app/Maps/Maps.apk
D/ResourcesManager(  752): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  752): creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
D/ResourcesManager(  752): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
W/Resources(  752): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  752): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  752): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
W/ResourcesManager(  752): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  752): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  752): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources(  752): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  752): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/ResourcesManager(  752): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
D/ResourcesManager(  752): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager(  752): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
W/Resources(  752): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  752): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}

```
