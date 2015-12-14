#### Test 50650278ec2c976_thali05_samsung-SM-N9005 Logs


```
--------- beginning of main
E/SMD     (  291): DCD ON
,D/AndroidRuntime( 7197): 
D/AndroidRuntime( 7197): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7197): CheckJNI is OFF
D/AndroidRuntime( 7197): readGMSProperty: start
D/AndroidRuntime( 7197): readGMSProperty: already setted!!
D/AndroidRuntime( 7197): readGMSProperty: end
D/AndroidRuntime( 7197): addProductProperty: start
E/AffinityControl( 7197): AffinityControl: registerfunction enter
D/AndroidRuntime( 7197): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  903): inState():  stateMachine is null !!
I/PersonaManagerService(  903): PersonaId don't exist
I/ActivityManager(  903): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  903): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
I/ActivityManager(  903): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  903): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager(  903): mDVFSHelper.acquire()
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  903): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7221 uid=10287 gids={50287, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/PointerIcon(  903): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  903): setMouseCustomIcon IconType is same.101
D/PointerIcon(  903): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  903): setHoveringSpenCustomIcon IconType is same.1
E/Zygote  ( 7221): MountEmulatedStorage()
I/libpersona( 7221): KNOX_SDCARD checking this for 10287
E/Zygote  ( 7221): v2
I/libpersona( 7221): KNOX_SDCARD not a persona
D/AndroidRuntime( 7197): Shutting down VM
I/SELinux ( 7221): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7221): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7221): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7221): TimaSignature is unavailable
D/ActivityThread( 7221): Added TimaKeyStore provider
I/SurfaceFlinger(  254): id=11 Removed YUIInstallC (5/8)
I/SurfaceFlinger(  254): id=11 Removed YUIInstallC (-2/8)
D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager( 7221): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
V/ActivityThread( 3716): updateVisibility : ActivityRecord{1c5a5f9c token=android.os.BinderProxy@18e5650d {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
,I/WebViewFactory( 7221): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,D/ResourcesManager( 7221): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7221): Loading: webviewchromium
,I/LibraryLoader( 7221): Time to load native libraries: 5 ms (timestamps 7241-7246)
,I/LibraryLoader( 7221): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7221): Binding Chromium to main looper Looper (main, tid 1) {188dc678}
,I/LibraryLoader( 7221): Expected native library version number "",actual native library version number ""
,I/chromium( 7221): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7221): Initializing chromium process, renderers=0
,W/art     ( 7221): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7221): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7221): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46780 len=2953
I/chromium( 7221): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229536 len:643667
,I/Adreno-EGL( 7221): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 7221): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7221): Build Date: 11/19/14 Wed
I/Adreno-EGL( 7221): Local Branch: mybranch5813579
I/Adreno-EGL( 7221): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 7221): Local Patches: NONE
I/Adreno-EGL( 7221): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,W/chromium( 7221): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7221): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 7221): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager(  903): Activity pause timeout for ActivityRecord{9527a09 u0 com.test.thalitest/.MainActivity t4}
,W/AwContents( 7221): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 7221): CordovaWebView is running on device made by: samsung
,W/art     ( 7221): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7221): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity( 7221): performCreate Call secproduct feature valuefalse
D/Activity( 7221): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer( 7221): Render dirty regions requested: true
,D/Atlas   ( 7221): Validating map...
,D/ActivityManager(  903): post active user change for 0
D/KnoxTimeoutHandler(  903): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  903): handleActiveUserChange for user 0
,V/ActivityThread( 7221): updateVisibility : ActivityRecord{32920c1 token=android.os.BinderProxy@178ab1cb {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/SurfaceFlinger(  254): id=15 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService(  903): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  903): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon(  903): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  903): setMouseCustomIcon IconType is same.101
D/PointerIcon(  903): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  903): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer( 7221): Initialized EGL, version 1.4
,I/OpenGLRenderer( 7221): HWUI protection enabled for context ,  &this =0xb3a6fab0 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 7221): Enabling debug mode 0
,D/InputMethodManagerService(  903): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Timeline(  903): Timeline: Activity_windows_visible id: ActivityRecord{9527a09 u0 com.test.thalitest/.MainActivity t4} time:157745
W/ActivityManager(  903): mDVFSHelper.release()
,W/IInputConnectionWrapper( 7221): showStatusIcon on inactive InputConnection
I/Timeline( 7221): Timeline: Activity_idle id: android.os.BinderProxy@178ab1cb time:157752
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/chromium( 7221): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7221): 
D/JsMessageQueue( 7221): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 7221): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1356769664
D/JX-Cordova( 7221): jxcore cordova android initializing
E/SMD     (  291): DCD ON
I/PowerManagerService(  903): [PWL] Off : 50s ago
D/BatteryService(  903): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService(  903): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  903): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  903): stay LED for fully charged
D/BatteryService(  903): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService(  903): Plugged
I/MotionRecognitionService(  903): setPowerConnected  = true
D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
V/HeadsetService( 3136): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3136): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SSRM:n  (  903): SIOP:: AP = 320, PST = 342, CUR = 450
I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,W/jxcore-log( 7221): Initializing JXcore engine
W/jxcore-log( 7221): JXcore engine is ready
,W/jxcore-log( 7221): Starting JXcore engine
,E/auditd  ( 1876): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  903): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
D/SecurityLogAgent:SEDenialService(  903): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,E/Zygote  ( 7293): MountEmulatedStorage()
I/ActivityManager(  903): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7293 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/Zygote  ( 7293): v2
I/libpersona( 7293): KNOX_SDCARD checking this for 1000
I/libpersona( 7293): KNOX_SDCARD not a persona
,I/SELinux ( 7293): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7293): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7293): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/jxcore-log( 7221): Platform android
W/jxcore-log( 7221): 
W/jxcore-log( 7221): Process ARCH arm
W/jxcore-log( 7221): 
,D/TimaKeyStoreProvider( 7293): TimaSignature is unavailable
,D/ActivityThread( 7293): Added TimaKeyStore provider
,D/ResourcesManager( 7293): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 7293):  SeDenialReceiver : Intent Received : android.intent.action.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7293):  SeDenialReceiver : File path = null
,I/ActivityManager(  903): Killing 5786:com.android.providers.calendar/u0a51 (adj 15): bgCount ##41
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/jxcore-log( 7221): JXcore Cordova bridge is ready!
I/jxcore-log( 7221): 
W/jxcore-log( 7221): JXcore engine is started
,E/SMD     (  291): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/jxcore-log( 7221): Toggling radios to true
I/jxcore-log( 7221): 
,D/BluetoothAdapter( 7221): enable()
,D/BluetoothAdapter( 7221): enable(): BT is already enabled..!
,I/WifiManager( 7221): packageName : com.test.thalitest
,D/SecContentProvider(  903): uri = 18 selection = isWifiEnabled
D/SecContentProvider2(  903): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  903): mCursor = null
,D/WifiService(  903): setWifiEnabled: true pid=7221, uid=10287
W/ActivityManager(  903): Permission Denial: getCurrentUser() from pid=7221, uid=10287 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  903): Failed getting userId using ActivityManagerNative
W/WifiService(  903): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7221, uid=10287 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  903): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23057)
W/WifiService(  903): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2181)
W/WifiService(  903): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2169)
W/WifiService(  903): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  903): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  903): name = wifi_on
,I/WifiService(  903): disconnect: pid=7221, uid=10287
,I/jxcore-log( 7221): Radios toggled
I/jxcore-log( 7221): 
I/wpa_supplicant( 1273): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 7221): Got Device Bluetooth address: E0:DB:10:1F:C9:5E
I/jxcore-log( 7221): 
I/jxcore-log( 7221): Perf Test app loaded loaded
I/jxcore-log( 7221): 
,I/jxcore-log( 7221): check test folder
I/jxcore-log( 7221): 
,I/jxcore-log( 7221): found test : ./testFindPeers.js
I/jxcore-log( 7221): 
,I/wpa_supplicant( 1273): CTRL-EVENT-DISCONNECTED bssid=C0.AA.4A reason=3 locally_generated=1
,I/wpa_supplicant( 1273): wlan0: State: COMPLETED -> DISCONNECTED
,I/jxcore-log( 7221): found test : ./testSendData.js
I/jxcore-log( 7221): 
,I/wpa_supplicant( 1273): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.4A SSID=4E473730303567
I/wpa_supplicant( 1273): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  903): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 1273): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1273): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1273): Disconnected - do not scan
I/wpa_supplicant( 1273): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiConfigStore(  903): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  903): do suspend true
,D/WifiP2pService(  903): InactiveState{ what=143375 }
,D/WifiP2pService(  903): P2pEnabledState{ what=143375 }
,D/CommandListener(  284): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1896): Read error: ssl=0x9b63ae00: I/O error during system call, Connection timed out
,D/StatusBar.NetworkController( 1192): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1192): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
,V/NativeCrypto( 1896): SSL shutdown failed: ssl=0x9b63ae00: I/O error during system call, Broken pipe
,E/WifiConfigStore(  903): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/ConnectivityService(  903): updateNetworkInfo()
D/ConnectivityService(  903): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  903): updateNetworkInfo()
D/ConnectivityService(  903): ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
D/ConnectivityService(  903): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,D/NetUtils(  903): android_net_utils_resetConnections in env=0xa93ad320 clazz=0x9be3998c iface=wlan0 mask=0x3
,I/WifiTrafficPoller(  903): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1192): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1192): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1192): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1192): applyOpen
,D/StatusBar.NetworkController( 1192): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1192): applyOpen
D/StatusBar.NetworkController( 1192): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1192): applyOpen
D/StatusBar.NetworkController( 1192): refreshSignalCluster - setNWBoosterIndicators(false)
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
D/StatusBar.NetworkController( 1192): applyOpen
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/WifiStateMachine(  903): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1273): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1273): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1273): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1273): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1273): First Scan Start
,E/native  (  903): do suspend true
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10015
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  903): ValidatedState{ when=-2ms what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  903): DefaultState{ when=-3ms what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  903): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  903): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  903): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,I/System.out(  903): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid (  903): Tagging socket 388 with tag ffffffff00000000{4294967295,0} uid 10015, pid: 903, getuid(): 1000
,I/System.out(  903): (HTTPLog)-Static: isSBSettingEnabled false
,E/Zygote  ( 7325): MountEmulatedStorage()
E/Zygote  ( 7325): v2
I/libpersona( 7325): KNOX_SDCARD checking this for 10038
I/libpersona( 7325): KNOX_SDCARD not a persona
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  903): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  903): Validated
,I/ActivityManager(  903): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.samsung.myplace.WIFINotificationHandler: pid=7325 uid=10038 gids={50038, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/wpa_supplicant( 1273): Scan requested (ret=0) - scan timeout 30 seconds
,I/SELinux ( 7325): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7325): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7325): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/WifiP2pService(  903): InactiveState{ what=143375 }
,D/WifiP2pService(  903): P2pEnabledState{ what=143375 }
,D/CommandListener(  284): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 1192): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1192): onWifiSignalChanged enabled=true enabledDesc:null
,I/WifiTrafficPoller(  903): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1192): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1192): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiNetworkAgent(  903): NetworkAgent: NetworkAgent channel lost
,D/SecContentProvider2(  903): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  903): mCursor = null
,D/SecContentProvider2(  903): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  903): mCursor = null
,D/TimaKeyStoreProvider( 7325): TimaSignature is unavailable
D/ActivityThread( 7325): Added TimaKeyStore provider
,D/ResourcesManager( 7325): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,W/ResourcesManager( 7325): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ConnectivityService(  903): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  903): calling update connectivity
D/ConnectivityService(  903):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  903):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  903): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  903):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  903): sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1192): CM callback handler got msg 524292
V/Nat464Xlat(  903): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  903): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  903): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CSLegacyTypeTracker(  903): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  903): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/EntConnectivity(  903): Not allowed due to - mEnabled false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  903): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  903): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  903): Disconnected - quitting
D/TelephonyNetworkFactory( 1420): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 2301): CM callback handler got msg 524292
,D/ConnectivityService(  903): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/NtpTrustedTime(  903): currentTimeMillis() cache hit
V/NetworkStats(  903): updateIfacesLocked()
V/NetworkStats(  903): performPollLocked(flags=0x1)
,D/SmartBondingService(  903): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkStatsFactory(  903): UpdateStatsForKnox
D/ConnectivityService(  903): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  903): MasterInitialState.processMessage what=3
D/SmartBondingService(  903): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  903): getSBEnabled() enabled =false
D/SmartBondingService(  903): getSBEnabled() enabled =false
D/SmartBondingService(  903): getSBEnabled() enabled =false
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1192): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1192): updateDataNetType()
D/StatusBar.NetworkController( 1192): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1192): updateLTEICONDataNetType:0
,D/SmartBondingService(  903): getNetworkEnabled : wifi : true mobile : true
,V/NetworkStats(  903): performPollLocked() took 6ms
D/NtpTrustedTime(  903): currentTimeMillis() cache hit
,E/ConnectivityService(  903): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,D/NtpTrustedTime(  903): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1192): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1192): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/NtpTrustedTime(  903): currentTimeMillis() cache hit
D/NtpTrustedTime(  903): currentTimeMillis() cache hit
D/NtpTrustedTime(  903): currentTimeMillis() cache hit
D/NtpTrustedTime(  903): currentTimeMillis() cache hit
V/NetworkStats(  903): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  903): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1192): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1192): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1192): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1192): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1192): applyOpen
,D/StatusBar.NetworkController( 1192): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1192): applyOpen
D/StatusBar.NetworkController( 1192): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1192): applyOpen
D/StatusBar.NetworkController( 1192): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1192): applyOpen
,I/Choreographer( 7221): Skipped 78 frames!  The application may be doing too much work on its main thread.
,I/chromium( 7221): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/chromium( 7221): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/FileWriteThread_Telephony( 1420): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1420): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1420): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1420): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1420): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1420): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1420): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1420): FileWriteThread : threadType = 3
,I/VlingoApplication( 7325): VlingoApplication appVersion ='11.2.2.0.37649', ro.csc.sales_code=XEO
,D/FileWriteThread_Telephony( 1420): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1420): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1420): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1420): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1420): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1420): FileWriteThread : threadType = 3
,E/BluetoothHeadset( 7325): BTStateChangeCB is registed
,E/BluetoothHeadset( 7325): BluetoothHeadset service is binded
,I/ActivityManager(  903): Killing 6292:flipboard.app/u0a125 (adj 15): bgCount ##41
,I/Hs20UtilService( 1324): Starting #6
,I/Hs20UtilService( 1324): Message received 5007
,D/NearbySettings( 1324): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1324): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1324): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1324): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1324): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1324): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1324): MountReceiver.mPrefHandler - 7002
,D/SettingsProvider(  903): name = driving_mode_on
,D/SettingsProvider(  903): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  903): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  903): selectionArgs: false
D/SettingsProvider(  903): selectionArgs: 10038
D/SecContentProvider(  903): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  903): ret = -1
,D/BluetoothManager( 7325): [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.media.ACTION_SCO_AUDIO_STATE_UPDATED
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6874): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 1324): Starting #7
,I/Hs20UtilService( 1324): Message received 5007
,D/NearbySettings( 1324): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1324): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1324): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1324): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1324): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1324): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1324): MountReceiver.mPrefHandler - 7002
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6874): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  903): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  903): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ApplicationPolicy(  903): updateDataUsageMap
D/SmartBondingService(  903): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  903): getSBEnabled() enabled =false
D/SmartBondingService(  903): getSBEnabled() enabled =false
D/SmartBondingService(  903): getSBEnabled() enabled =false
,D/SmartBondingService(  903): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3716): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/NetworkMonitor( 5869): type=WIFI subType= reason=null isConnected=false
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/PCWCLIENTTRACE_PushUtil( 6581): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6581): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6581): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6581): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
I/PCWCLIENTTRACE_SYSTEMReceiver( 6581): noConnectivity : true
I/DBG_DM  ( 3716): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7379): MountEmulatedStorage()
,I/ActivityManager(  903): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7379 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 7379): v2
,I/libpersona( 7379): KNOX_SDCARD checking this for 10004
I/libpersona( 7379): KNOX_SDCARD not a persona
,I/SELinux ( 7379): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7379): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7379): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7379): TimaSignature is unavailable
,D/ActivityThread( 7379): Added TimaKeyStore provider
,D/ResourcesManager( 7379): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager(  903): Killing 5648:com.google.android.gm/u0a128 (adj 15): bgCount ##41
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7396): MountEmulatedStorage()
,I/libpersona( 7396): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7396): v2
I/libpersona( 7396): KNOX_SDCARD not a persona
I/ActivityManager(  903): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7396 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7396): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7396): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7396): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7396): TimaSignature is unavailable
,D/ActivityThread( 7396): Added TimaKeyStore provider
,D/ResourcesManager( 7396): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT( 7396): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7396): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT( 7396): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7396): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7396): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7396): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,I/wpa_supplicant( 1273): nl80211: Received scan results (11 BSSes)
I/wpa_supplicant( 1273): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1273): Trying to associate with C0.AA.4A (SSID='4E473730303567' freq=5220 MHz)
I/wpa_supplicant( 1273): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1273): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E473730303567
,I/ActivityManager(  903): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7421 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 7421): MountEmulatedStorage()
E/Zygote  ( 7421): v2
I/libpersona( 7421): KNOX_SDCARD checking this for 10014
I/libpersona( 7421): KNOX_SDCARD not a persona
,D/SecContentProvider2(  903): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  903): mCursor = null
,I/SELinux ( 7421): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7421): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7421): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/wpa_supplicant( 1273): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1273): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E473730303567
,I/wpa_supplicant( 1273): Associated with C0.AA.4A
,D/SecContentProvider2(  903): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  903): mCursor = null
,I/wpa_supplicant( 1273): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1273): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.4A SSID=4E473730303567
,D/SecContentProvider2(  903): uri = 20 selection = getPromptCredentialsEnabled
,I/wpa_supplicant( 1273): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,D/SecContentProvider2(  903): mCursor = null
,I/wpa_supplicant( 1273): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,I/wpa_supplicant( 1273): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.4A SSID=4E473730303567
I/wpa_supplicant( 1273): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1273): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1273): CTRL-EVENT-CONNECTED - Connection to C0.AA.4A completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 1273): Blacklist: Clear (temp) 
I/wpa_supplicant( 1273): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.4A SSID=4E473730303567
,D/WifiNative-HAL(  903): callSECApiVoid - ID [50]
,D/TimaKeyStoreProvider( 7421): TimaSignature is unavailable
,D/ActivityThread( 7421): Added TimaKeyStore provider
,D/StatusBar.NetworkController( 1192): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1192): onWifiSignalChanged enabled=true enabledDesc:null
,D/ConnectivityService(  903): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,E/WifiConfigStore(  903): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  903): Got NetworkAgent Messenger
,D/ConnectivityService(  903): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  903): updateNetworkInfo()
D/ConnectivityService(  903): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  903): NetworkAgent connected
,E/WifiConfigStore(  903): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ResourcesManager( 7421): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,D/CommandListener(  284): Setting iface cfg
,E/WifiStateMachine(  903): Start Dhcp Watchdog 2
,D/SecContentProvider2(  903): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  903): mCursor = null
,D/ConnectivityService(  903): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,I/ActivityManager(  903): Killing 5917:com.sec.android.app.music:service/u0a49 (adj 15): bgCount ##41
,I/FOTA_Client( 7421): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7421): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,E/native  (  903): do suspend false
,D/SecContentProvider2(  903): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  903): mCursor = null
,D/WifiP2pService(  903): InactiveState{ what=143375 }
,D/WifiP2pService(  903): P2pEnabledState{ what=143375 }
,I/FOTA_Client( 7421): [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,W/Atfwd_Sendcmd(  352): AtCmdFwd service not published, waiting... retryCnt : 4
,E/Zygote  ( 7447): MountEmulatedStorage()
E/Zygote  ( 7447): v2
I/libpersona( 7447): KNOX_SDCARD checking this for 10023
I/libpersona( 7447): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7447 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7447): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/ActivityManager(  903): Killing 5988:com.sec.android.app.myfiles/u0a56 (adj 15): bgCount ##41
I/SELinux ( 7447): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7447): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7447): TimaSignature is unavailable
,D/ActivityThread( 7447): Added TimaKeyStore provider
I/art     (  329): Explicit concurrent mark sweep GC freed 8759(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 552us total 45.817ms
,E/dhcpcd  ( 7459): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 7459): version 5.5.6 starting
,I/art     (  329): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 523us total 16.174ms
,E/dhcpcd  ( 7459): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/art     (  329): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 389us total 14.678ms
,D/ResourcesManager( 7447): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.511: ( 7447): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.511: ( 7447): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450109412140
,I/KLMS-2.4.511: ( 7447): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.511: ( 7447): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.511: ( 7447): StateImplV2(): networkChangeListener().END
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,I/dhcpcd  ( 7459): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7459): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7459): if(wlan0) info get Success. (MAC : C0.AA.4A)
I/dhcpcd  ( 7459): bssid match
I/dhcpcd  ( 7459): wlan0: rebinding lease of 192.168.1.128
,E/Zygote  ( 7478): MountEmulatedStorage()
E/Zygote  ( 7478): v2
I/libpersona( 7478): KNOX_SDCARD checking this for 10036
I/libpersona( 7478): KNOX_SDCARD not a persona
,I/SELinux ( 7478): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7478): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7478): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  903): Start proc com.samsung.android.app.pinboard:tagService for broadcast com.samsung.android.app.pinboard/.service.TagReadyReceiver: pid=7478 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  903): Killing 6445:com.google.android.gms:car/u0a15 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7478): TimaSignature is unavailable
,D/ActivityThread( 7478): Added TimaKeyStore provider
,D/ResourcesManager( 7478): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,W/ResourcesManager( 7478): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7478): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/dhcpcd  ( 7459): wlan0: acknowledged 192.168.1.128 from 192.168.1.1
,I/dhcpcd  ( 7459): wlan0: leased 192.168.1.128 for 86400 seconds
,D/ConnectivityService(  903): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,E/Minikin ( 7478): addFont failed to create font /system/fonts/SamsungSans-light.ttf
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  903): Killing 6401:com.android.defcontainer/u0a7 (adj 15): bgCount ##41
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7499): MountEmulatedStorage()
,E/Zygote  ( 7499): v2
I/libpersona( 7499): KNOX_SDCARD checking this for 10042
I/libpersona( 7499): KNOX_SDCARD not a persona
,I/SELinux ( 7499): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/ActivityManager(  903): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7499 uid=10042 gids={50042, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7499): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7499): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7499): TimaSignature is unavailable
,D/ActivityThread( 7499): Added TimaKeyStore provider
,D/ResourcesManager( 7499): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT( 7499): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5090): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,E/SPPClientService( 5090): [[SystemStateMonitorService]] No Active Internet
,I/SA      ( 6664): [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
,I/SA      ( 6664): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 6664): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6664): [SLFUCHKMGR] constructor called
,I/SA      ( 6664): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6664): [OR] == isSIMCardReady false ==
,I/SA      ( 6664): [SCU] == networkStateCheck == false
I/SA      ( 6664): [OR] onReceive END
,I/ActivityManager(  903): Killing 6544:com.google.android.partnersetup/u0a19 (adj 15): bgCount ##41
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/SMD     (  291): DCD ON
,E/Zygote  ( 7532): MountEmulatedStorage()
E/Zygote  ( 7532): v2
I/libpersona( 7532): KNOX_SDCARD checking this for 10074
I/libpersona( 7532): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=7532 uid=10074 gids={50074, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 7532): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7532): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7532): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7532): TimaSignature is unavailable
,D/ActivityThread( 7532): Added TimaKeyStore provider
,D/ResourcesManager( 7532): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,E/native  (  903): do suspend true
,D/WifiP2pService(  903): InactiveState{ what=143375 }
D/WifiP2pService(  903): P2pEnabledState{ what=143375 }
,D/ConnectivityService(  903): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,D/StatusBar.NetworkController( 1192): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1192): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine(  903): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG7005g"WPA_PSK
E/WifiStateMachine(  903): VerifyingLinkState enter
,D/WifiNative-HAL(  903): callSECApiInt - ID [210]
,E/ConnectivityService(  903): updateNetworkInfo()
,D/ConnectivityService(  903): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
D/ConnectivityService(  903): Adding iface wlan0 to network 503,
D/WifiWatchdogStateMachine(  903): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  903): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
D/WifiWatchdogStateMachine.DnsResolver(  903): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker(  903): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  903): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/StatusBar.NetworkController( 1192): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1192): onWifiSignalChanged enabled=true enabledDesc:null
,I/sCloudBackupApp( 7532): sCloudBackupApp Version Info : 3.13.7.KK_APP
I/SCloudBackupReceiver( 7532): Other Intent
,E/WifiStateMachine(  903): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,I/KnoxUsageLogPro( 7038): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,E/WifiStateMachine(  903): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller(  903): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1192): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1192): onWifiSignalChanged enabled=true enabledDesc:null
,I/KnoxUsageLogPro( 7038): premStatus:2
,I/WifiTrafficPoller(  903): evaluateTrafficStatsPolling
,I/WifiTrafficPoller(  903): mBoosterFLAG : 0
,I/WifiTrafficPoller(  903): current booster mode : FullMode
D/WifiNative-HAL(  903): callSECApiVoid - ID [212]
,D/StatusBar.NetworkController( 1192): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1192): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
D/StatusBar.NetworkController( 1192): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1192): applyOpen
D/StatusBar.NetworkController( 1192): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1192): applyOpen
D/StatusBar.NetworkController( 1192): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1192): applyOpen
D/StatusBar.NetworkController( 1192): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1192): applyOpen
I/KnoxUsageLogPro( 7038): isEulaShown : false
I/KnoxUsageLogPro( 7038): KnoxUsageReceiver onReceive : not Processible, just return
,D/ConnectivityService(  903): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService(  903): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService(  903): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/ConnectivityService(  903): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  903): updateSourceRoutes : add source routing for type : 1
,D/ConnectivityService(  903): updateSourceRoutes : add src route for:192.168.1.128
,V/        (  284): QcRouteController
,E/Zygote  ( 7553): MountEmulatedStorage()
,E/Zygote  ( 7553): v2
I/libpersona( 7553): KNOX_SDCARD checking this for 10104
I/libpersona( 7553): KNOX_SDCARD not a persona
,V/        (  284): QcRouteController
,I/SELinux ( 7553): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/ActivityManager(  903): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7553 uid=10104 gids={50104, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7553): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7553): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  903): Killing 6562:com.samsung.groupcast/u0a20 (adj 15): bgCount ##41
,V/        (  284): QcRouteController
,D/TimaKeyStoreProvider( 7553): TimaSignature is unavailable
,D/ActivityThread( 7553): Added TimaKeyStore provider
,V/        (  284): QcRouteController
,D/ResourcesManager( 7553): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,V/        (  284): QcRouteController
,V/        (  284): QcRouteController
,V/        (  284): QcRouteController
,V/        (  284): QcRouteController
,D/ConnectivityService(  903): Setting Dns servers for network 503 to [/192.168.1.1]
,D/ConnectivityService(  903): LTETest block dns file not exists
,V/Nat464Xlat(  903): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/ConnectivityService(  903): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  903): calling update connectivity
,D/ConnectivityService(  903): ignoring duplicate network state non-change. WIFI, state = CONNECTING
D/EntConnectivity(  903): Not allowed due to - mEnabled false
E/ConnectivityService(  903): updateNetworkInfo()
D/ConnectivityService(  903): ignoring duplicate network state non-change. WIFI, state = CONNECTING
,E/ConnectivityService(  903): updateNetworkInfo()
D/ConnectivityService(  903): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  903): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  903): calling update connectivity
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  903): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  903): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  903): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  903): Checking http://clients3.google.com/generate_204 on "NG7005g"
,I/System.out(  903): (HTTPLog)-Static: isSBSettingEnabled false
,D/ConnectivityService(  903): rematching NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  903):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  903):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  903):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  903):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  903): currentScore = 0, newScore = 60
D/ConnectivityService(  903):    accepting network in place of null
D/ConnectivityService(  903): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1420): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CSLegacyTypeTracker(  903): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
E/CSLegacyTypeTracker(  903): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,E/Zygote  ( 7583): MountEmulatedStorage()
I/libpersona( 7583): KNOX_SDCARD checking this for 10146
E/Zygote  ( 7583): v2
I/libpersona( 7583): KNOX_SDCARD not a persona
,I/SELinux ( 7583): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7583): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7583): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  903): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7583 uid=10146 gids={50146, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  903): Killing 4576:com.sec.android.app.shealth/u0a40 (adj 15): bgCount ##41
,D/ConnectivityService(  903): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,I/System.out(  903): KnoxVpnUidStorageknoxVpnSupported API value returned is false
D/ConnectivityService(  903): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/Tethering(  903): MasterInitialState.processMessage what=3
,D/SmartBondingService(  903): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  903): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  903): getSBEnabled() enabled =false
D/SmartBondingService(  903): getSBEnabled() enabled =false
D/SmartBondingService(  903): getSBEnabled() enabled =false
,V/NetworkStats(  903): updateIfacesLocked()
,V/NetworkStats(  903): performPollLocked(flags=0x1)
D/NtpTrustedTime(  903): currentTimeMillis() cache hit
,D/NetworkStatsFactory(  903): UpdateStatsForKnox
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/EntConnectivity(  903): Not allowed due to - mEnabled false
,D/StatusBar.NetworkController( 1192): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1192): updateDataNetType()
D/StatusBar.NetworkController( 1192): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1192): updateLTEICONDataNetType:0
,D/SmartBondingService(  903): getNetworkEnabled : wifi : true mobile : true
D/NtpTrustedTime(  903): currentTimeMillis() cache hit
,D/ConnectivityService(  903): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  903): calling update connectivity
D/ConnectivityService(  903):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,V/NetworkStats(  903): performPollLocked() took 7ms
D/ConnectivityService(  903):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  903): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NtpTrustedTime(  903): currentTimeMillis() cache hit
,D/NtpTrustedTime(  903): currentTimeMillis() cache hit
D/NtpTrustedTime(  903): currentTimeMillis() cache hit
,D/NtpTrustedTime(  903): currentTimeMillis() cache hit
D/ConnectivityManager.CallbackHandler( 1192): CM callback handler got msg 524290
D/NtpTrustedTime(  903): currentTimeMillis() cache hit
D/ConnectivityService(  903):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,V/NetworkStats(  903): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  903): currentTimeMillis() cache hit
,D/ConnectivityService(  903): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 2301): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1192): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1192): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1192): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1192): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1192): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
D/StatusBar.NetworkController( 1192): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1192): applyOpen
D/StatusBar.NetworkController( 1192): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1192): applyOpen
D/StatusBar.NetworkController( 1192): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1192): applyOpen
D/StatusBar.NetworkController( 1192): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1192): applyOpen
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  903): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 14 Dec 2015 16:10:13 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450109413332], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450109413313]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  903): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  903): Validated
D/ConnectivityService(  903): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  903): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  903):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  903):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  903):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  903): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  903): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  903): calling update connectivity
D/ConnectivityService(  903):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  903):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  903): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1192): CM callback handler got msg 524290
D/ConnectivityService(  903):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  903): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 2301): CM callback handler got msg 524290
D/TimaKeyStoreProvider( 7583): TimaSignature is unavailable
D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1192): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1192): updateDataNetType()
D/StatusBar.NetworkController( 1192): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1192): updateLTEICONDataNetType:0
D/ActivityThread( 7583): Added TimaKeyStore provider
D/StatusBar.NetworkController( 1192): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1192): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1192): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1192): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1192): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
,D/ResourcesManager( 7583): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7583): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7583): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7583): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7583): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  903): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  903): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  903): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  903): SmartBondingReceiver: wifi ap is not changed
D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  903): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  903): getSBEnabled() enabled =false
D/SmartBondingService(  903): getSBEnabled() enabled =false
D/SmartBondingService(  903): getSBEnabled() enabled =false
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1887): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  903): getNetworkEnabled : wifi : true mobile : true
,W/ContextImpl( 1887): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GpsLocationProvider(  903): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 3716): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 3716): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5869): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  903): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  903): mCursor = null
,I/WebViewFactory( 7583): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,D/ResourcesManager( 7583): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7583): Loading: webviewchromium
,I/LibraryLoader( 7583): Time to load native libraries: 5 ms (timestamps 5547-5552)
,I/LibraryLoader( 7583): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7583): Binding Chromium to main looper Looper (main, tid 1) {272391ec}
,I/LibraryLoader( 7583): Expected native library version number "",actual native library version number ""
,I/chromium( 7583): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7583): Initializing chromium process, renderers=0
,W/art     ( 7583): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7583): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7583): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46780 len=2953
,I/chromium( 7583): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229536 len:643667
,W/AudioManagerAndroid( 7583): Requires BLUETOOTH permission
,I/Adreno-EGL( 7583): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 7583): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7583): Build Date: 11/19/14 Wed
I/Adreno-EGL( 7583): Local Branch: mybranch5813579
I/Adreno-EGL( 7583): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 7583): Local Patches: NONE
I/Adreno-EGL( 7583): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,E/Watchdog(  903): !@Sync 5
,I/NSApplication( 7583): Starting up...
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  903): Killing 6632:com.samsung.android.sdk.samsunglink/u0a48 (adj 15): bgCount ##41
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7659): MountEmulatedStorage()
,E/Zygote  ( 7659): v2
I/libpersona( 7659): KNOX_SDCARD checking this for 10158
I/libpersona( 7659): KNOX_SDCARD not a persona
,D/ConnectivityService(  903): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/ActivityManager(  903): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7659 uid=10158 gids={50158, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
I/SELinux ( 7659): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7659): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7659): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7659): TimaSignature is unavailable
,D/ActivityThread( 7659): Added TimaKeyStore provider
,D/ResourcesManager( 7659): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 7659): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7659): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7659): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 7659): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7659): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7659): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7674): MountEmulatedStorage()
E/Zygote  ( 7674): v2
,I/libpersona( 7674): KNOX_SDCARD checking this for 10186
I/libpersona( 7674): KNOX_SDCARD not a persona
,I/SELinux ( 7674): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7674): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,I/ActivityManager(  903): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7674 uid=10186 gids={50186, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,E/SELinux ( 7674): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  903): Killing 6688:com.android.mms/u0a55 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7674): TimaSignature is unavailable
,D/ActivityThread( 7674): Added TimaKeyStore provider
,D/CountryDetector(  903): No listener is left
,D/ResourcesManager( 7674): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7674): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7674): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7674): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 7674): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7674): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService(  903): exchangeData() failure , invalid userId
,D/RCPManagerService(  903): exchangeData() failure , invalid userId
,D/RCPManagerService(  903): exchangeData() failure , invalid userId
,D/BadgeProvider( 6716): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/Launcher.Model( 1445): reloadBadges entered.
,D/BadgeProvider( 6716): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 6716): sendNotify, [notify] : null
,D/BadgeProvider( 6716): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 6716): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 6716): update, [UpdateCount] : 1
,D/RCPManagerService(  903): exchangeData() failure , invalid userId
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  903): exchangeData() failure , invalid userId
,D/RCPManagerService(  903): exchangeData() failure , invalid userId
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7293): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 7293): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 7293): StateMachine : Current State = 1
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7293): StateMachine : Changed Current State = 1
,I/ActivityManager(  903): Killing 6731:com.sec.android.app.soundalive/u0a64 (adj 15): bgCount ##41
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7704): MountEmulatedStorage()
,E/Zygote  ( 7704): v2
I/libpersona( 7704): KNOX_SDCARD checking this for 10200
,I/libpersona( 7704): KNOX_SDCARD not a persona
,I/ActivityManager(  903): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7704 uid=10200 gids={50200, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7704): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7704): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7704): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7704): TimaSignature is unavailable
,D/ActivityThread( 7704): Added TimaKeyStore provider
,D/ResourcesManager( 7704): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,I/jxcore-log( 7221): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 7221): 
,I/ActivityManager(  903): Killing 5704:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ActivityManager(  903): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/hcjo    ( 5451): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5451): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5451): exit::IDLE
D/InitializeManagerStateMachine( 5451): entry::NETWORK_CHECK
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 5451): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5451): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5451): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5451): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5451): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5451): entry::SUCCESS
D/hcjo    ( 5451): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5451): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 5451): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 5451): exit::SUCCESS
D/InitializeManagerStateMachine( 5451): entry::IDLE
,I/Hs20UtilService( 1324): Starting #8
,I/Hs20UtilService( 1324): Message received 5007
,D/NearbySettings( 1324): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1324): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1324): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1324): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1324): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1324): MountReceiver.onReceive - Keep current state
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6874): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 1324): Starting #9
,I/Hs20UtilService( 1324): Message received 5007
,D/NearbySettings( 1324): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1324): MountReceiver.onReceive - Keep current state
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6874): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 1324): Starting #10
,I/Hs20UtilService( 1324): Message received 5007
,D/NearbySettings( 1324): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1324): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1324): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/ConnectivityService(  903): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1324): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1324): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1324): MountReceiver.onReceive - Keep current state
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6874): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 1324): Starting #11
,I/Hs20UtilService( 1324): Message received 5007
,D/NearbySettings( 1324): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1324): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine(  903): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6874): NETWORK_STATE_CHANGED_ACTION
,I/SurfaceFlinger(  254): id=16 createSurf (1x1),1 flag=4, Uoast
,I/PCWCLIENTTRACE_PushUtil( 6581): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6581): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6581): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6581): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
D/PackageManager(  903): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/PowerManagerService(  903): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=903
,I/DIAGMON_AGENT( 7396): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT( 7396): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/FOTA_Client( 7421): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7421): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7421): [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.511: ( 7447): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.511: ( 7447): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450109415625
,I/KLMS-2.4.511: ( 7447): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.511: ( 7447): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.511: ( 7447): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.511: ( 7447): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.511: ( 7447): StateImplV2(): networkChangeListener().END
,E/SMD     (  291): DCD ON
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SO_AGENT( 7499): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5090): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 6664): [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
I/SA      ( 6664): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,I/SA      ( 6664): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6664): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6664): [OR] == isSIMCardReady false ==
D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6664): [SCU] == networkStateCheck == true
,I/SA      ( 6664): [DM] getCountryCodeFromCSC : PL
I/SA      ( 6664): isChinaCountryCode : false
I/SA      ( 6664): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6664): [OR] == networkStateCheck true ==
,I/SA      ( 6664): [OR] GetMyCountryZoneTask
,I/SA      ( 6664): [OR] onReceive END
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6664): [SRS] prepareGetMyCountryZone
,I/SCloudBackupReceiver( 7532): Other Intent
,I/SA      ( 6664): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6664): [SSP] query invoked
,I/KnoxUsageLogPro( 7038): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 7038): premStatus:2
,I/KnoxUsageLogPro( 7038): isEulaShown : false
I/KnoxUsageLogPro( 7038): KnoxUsageReceiver onReceive : not Processible, just return
,I/art     (  903): Explicit concurrent mark sweep GC freed 71239(4MB) AllocSpace objects, 11(224KB) LOS objects, 17% free, 37MB/45MB, paused 1.700ms total 134.790ms
,I/SA      ( 6664): [TPMU] GetMccFromDB : null
I/SA      ( 6664): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6664): [TPM] isNoProxy(default) : true
,E/File    ( 6664): fail readDirectory() errno=2
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 7659): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7659): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7659): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/RCPManagerService(  903): exchangeData() failure , invalid userId
,D/RCPManagerService(  903): exchangeData() failure , invalid userId
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7293): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7293): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7293): StateMachine : Current State = 1
D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7293): StateMachine : Changed Current State = 1
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 5451): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5451): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5451): exit::IDLE
,D/InitializeManagerStateMachine( 5451): entry::NETWORK_CHECK
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 5451): execute::NETWORK_CHECK:NETWORK_STATE_OK
,D/InitializeManagerStateMachine( 5451): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5451): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5451): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5451): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5451): entry::SUCCESS
D/hcjo    ( 5451): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5451): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5451): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 5451): exit::SUCCESS
,D/InitializeManagerStateMachine( 5451): entry::IDLE
,E/WifiStateMachine(  903): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/dhcpcd  ( 7459): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7459): wlan0: sendmsg: Cannot assign requested address
,I/SA      ( 6664): [RC New] Execute method=[GET] start
,I/SA      ( 6664): [RC New] Security=[true]
,I/System.out( 6664): Thread-1110(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6664): Thread-1110(ApacheHTTPLog):isShipBuild true
,I/System.out( 6664): Thread-1110(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,D/BatteryService(  903): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService(  903): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  903): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  903): stay LED for fully charged
D/BatteryService(  903): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  903): Plugged
I/MotionRecognitionService(  903): setPowerConnected  = true
,V/HeadsetService( 3136): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3136): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  903): SIOP:: AP = 350, PST = 338, CUR = 450
,D/ConnectivityService(  903): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
,D/ConnectivityService(  903): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService(  903): identical MTU - not setting
,D/ConnectivityService(  903): updateSourceRoutes : add source routing for type : 1
,D/ConnectivityService(  903): updateSourceRoutes : add src route for:fe80::ea50:8bff:fede:28a3
,V/        (  284): QcRouteController
,D/SmartBondingService(  903): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  903): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  903): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  903): getSBEnabled() enabled =false
,D/SmartBondingService(  903): getSBEnabled() enabled =false
,D/SmartBondingService(  903): getSBEnabled() enabled =false
,V/        (  284): QcRouteController
,W/NetworkManagementService(  903): route cmd failed: 
W/NetworkManagementService(  903): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '74 route replace src v6 wlan0 fe80::ea50:8bff:fede:28a3 2 ::' failed with '400 74 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  903): '
W/NetworkManagementService(  903): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService(  903): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService(  903): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService(  903): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService(  903): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  903): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5625)
W/NetworkManagementService(  903): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5437)
W/NetworkManagementService(  903): 	at com.android.server.ConnectivityService.access$2300(ConnectivityService.java:229)
W/NetworkManagementService(  903): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2382)
W/NetworkManagementService(  903): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  903): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  903): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/Nat464Xlat(  903): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  903): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  903): calling update connectivity
D/ConnectivityService(  903):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  903):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  903): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1192): CM callback handler got msg 524295
,D/ConnectivityService(  903):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  903): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  903): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  903): calling update connectivity
D/ConnectivityService(  903):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  903):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  903): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 2301): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1192): CM callback handler got msg 524295
,D/ConnectivityService(  903):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  903): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 2301): CM callback handler got msg 524295
,I/SA      ( 6664): [RC New] [v2liruge] api execute + 858
,I/SA      ( 6664): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6664): AsyncTask #1 calls detatch()
,I/SA      ( 6664): [TPMU] getNetworkMcc : 
,I/SA      ( 6664): [SCU] saveMccToPreferece Start
,I/SA      ( 6664): [SCU] RegionMCC : 260
I/SA      ( 6664): [SSP] query invoked
,I/SA      ( 6664): [TPMU] GetMccFromDB : null
,I/SA      ( 6664): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6664): [SCU] saveMccToPreferece End
,I/SA      ( 6664): [RC New] executeRequest [v2liruge] end. 934
,I/SA      ( 6664): [RC New] Execute end
,I/SA      ( 6664): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 6664): [OR] GetMyCountryZoneTask Success
,I/GAV4    ( 7583): Thread[GAThread,5,main]: No campaign data found.
,E/SMD     (  291): DCD ON
,I/SurfaceFlinger(  254): id=16 Removed Uoast (8/9)
,I/SurfaceFlinger(  254): id=16 Removed Uoast (-2/9)
,D/PowerManagerService(  903): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 903) eventTime = 170433
,D/PowerManagerService(  903): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=903 (0x0)
,D/PowerManagerService(  903): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=903, ws=WorkSource{10067}) (elapsedTime=3499)
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6581): mConnectivityHandler : connected
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 6581): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE( 6581): ================================================
,I/CSTORAGE( 6581):  CSTORAGE_SKM_LIB v1.0.6
I/CSTORAGE( 6581): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 6581): [GetString-S]
E/art     ( 6581): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6581): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6581): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 6581): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6581): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6581): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 6581): [ensureRegistration] - No Samsung account
,I/dhcpcd  ( 7459): wlan0: sending IPv6 Router Solicitation
,E/SMD     (  291): DCD ON
,I/dhcpcd  ( 7459): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 7459): wlan0: no IPv6 Routers available
,E/SMD     (  291): DCD ON
,D/PreloadUpdateManagerStateMachine( 5451): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5451): exit::IDLE
D/PreloadUpdateManagerStateMachine( 5451): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5451): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5451): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5451): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5451): entry::IDLE
,D/PreloadUpdateManagerStateMachine( 5451): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5451): exit::IDLE
D/PreloadUpdateManagerStateMachine( 5451): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5451): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/PreloadUpdateManagerStateMachine( 5451): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5451): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5451): entry::IDLE
,D/BatteryService(  903): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  903): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  903): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  903): stay LED for fully charged
D/BatteryService(  903): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  903): Plugged
,I/MotionRecognitionService(  903): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3136): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3136): Disconnected process message: 10
,D/SSRM:n  (  903): SIOP:: AP = 320, PST = 330, CUR = 450
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,I/PowerManagerService(  903): [PWL] Off : 75s ago
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD ON
,W/Atfwd_Sendcmd(  352): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:n  (  903): SIOP:: AP = 310, PST = 325, CUR = 450
,E/SMD     (  291): DCD ON
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD ON
,E/Watchdog(  903): !@Sync 6
,E/SMD     (  291): DCD ON
,V/AlarmManager(  903): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1192): handleTimeUpdate
,D/KeyguardEffectViewController( 1192): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1192): *** don't update sliding image ***
,D/BatteryService(  903): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  903): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  903): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  903): stay LED for fully charged
,D/BatteryService(  903): Sending ACTION_BATTERY_CHANGED.
,V/HeadsetService( 3136): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3136): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
I/MotionRecognitionService(  903): Plugged
,I/MotionRecognitionService(  903): setPowerConnected  = true
,D/DateView( 1192): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1192): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  (  903): SIOP:: AP = 310, PST = 322, CUR = 450
,E/SMD     (  291): DCD ON
,I/ClearcutLoggerApiImpl( 1896): disconnect managed GoogleApiClient
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  903): SIOP:: AP = 310, PST = 319, CUR = 450
,E/SMD     (  291): DCD ON
,V/AlarmManager(  903): waitForAlarm result :4
,D/ConnectivityService(  903): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  903): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  903): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  903): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  903): stay LED for fully charged
,D/BatteryService(  903): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  903): Plugged
I/MotionRecognitionService(  903): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3136): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3136): Disconnected process message: 10
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager(  903): waitForAlarm result :8
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD ON
,I/PowerManagerService(  903): [PWL] Off : 105s ago
,I/Atfwd_Sendcmd(  352): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  352): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  903): SIOP:: AP = 300, PST = 316, CUR = 450
,D/BatteryService(  903): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,E/Watchdog(  903): !@Sync 7
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  352): AtCmdFwd service not published, waiting... retryCnt : 1
,D/SSRM:n  (  903): SIOP:: AP = 300, PST = 314, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  903): !@BatteryListener : batteryPropertiesChanged!
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  352): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:n  (  903): SIOP:: AP = 300, PST = 313, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  903): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,I/PowerManagerService(  903): [PWL] Off : 140s ago
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,D/SSRM:n  (  903): SIOP:: AP = 300, PST = 312, CUR = 450
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,D/BatteryService(  903): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  903): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  903): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  903): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  903): Plugged
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,I/MotionRecognitionService(  903): setPowerConnected  = true
,D/BatteryService(  903): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3136): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3136): Disconnected process message: 10
,E/SMD     (  291): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  352): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  291): DCD ON
,E/Watchdog(  903): !@Sync 8
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  903): SIOP:: AP = 300, PST = 310, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  903): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,D/SSRM:n  (  903): SIOP:: AP = 300, PST = 305, CUR = 450
,E/SMD     (  291): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,D/BatteryService(  903): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  352): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  903): SIOP:: AP = 300, PST = 303, CUR = 450
,D/BatteryService(  903): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/Watchdog(  903): !@Sync 9
,E/SMD     (  291): DCD ON
,I/PowerManagerService(  903): [PWL] Off : 180s ago
,D/SSRM:n  (  903): SIOP:: AP = 300, PST = 302, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  903): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  903): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  903): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  903): stay LED for fully charged
,D/BatteryService(  903): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,I/MotionRecognitionService(  903): Plugged
I/MotionRecognitionService(  903): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3136): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3136): Disconnected process message: 10
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  352): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:n  (  903): SIOP:: AP = 300, PST = 301, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  903): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  903): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0,
D/BatteryService(  903): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  903): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  903): Plugged
,I/MotionRecognitionService(  903): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
,V/HeadsetService( 3136): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3136): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  903): stay LED for fully charged
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  903): SIOP:: AP = 290, PST = 299, CUR = 450
,D/BatteryService(  903): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  903): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  903): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  903): stay LED for fully charged
,D/BatteryService(  903): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
I/MotionRecognitionService(  903): Plugged
,I/MotionRecognitionService(  903): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3136): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3136): Disconnected process message: 10
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService(  903): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  903): TimaServiceHandler.handleMessage what =1
,D/TimaService(  903): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  903): initializing...
,I/TLC_TIMA_PKM_initialize(  903): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  903): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  903): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  903): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication(  903): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  903): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  903): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  903): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  903): App is not loaded in QSEE
,D/QSEECOMAPI: (  903): Loaded image: APP id = 4
,I/TZ: qc_tlc_communication(  903): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  903): Trustlet response is completed
,E/SMD     (  291): DCD ON
,E/Watchdog(  903): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel(  903): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  903): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  903): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  903): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  903): SIOP:: AP = 300, PST = 299, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  903): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  903): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  903): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  903): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
I/MotionRecognitionService(  903): Plugged
,I/MotionRecognitionService(  903): setPowerConnected  = true
,V/HeadsetService( 3136): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3136): Disconnected process message: 10
,D/BatteryService(  903): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,I/Atfwd_Sendcmd(  352): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  352): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  903): SIOP:: AP = 300, PST = 299, CUR = 450
,E/SMD     (  291): DCD ON
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD ON
,I/PowerManagerService(  903): [PWL] Off : 225s ago
,V/AlarmManager(  903): waitForAlarm result :4
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  903): checkUser: useridlist=null, currentuser=0
,D/BatteryService(  903): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  903): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  903): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  903): stay LED for fully charged
,I/ActivityManager(  903): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=7794 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1192): handleTimeUpdate
,D/BatteryService(  903): Sending ACTION_BATTERY_CHANGED.
,E/Zygote  ( 7794): MountEmulatedStorage()
,E/Zygote  ( 7794): v2
I/libpersona( 7794): KNOX_SDCARD checking this for 10096
I/libpersona( 7794): KNOX_SDCARD not a persona
,I/MotionRecognitionService(  903): Plugged
,I/MotionRecognitionService(  903): setPowerConnected  = true
,I/SELinux ( 7794): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7794): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7794): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/KeyguardEffectViewController( 1192): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1192): *** don't update sliding image ***
D/KeyguardUpdateMonitor( 1192): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1192):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1192): handleBatteryUpdate
D/BatteryMeterView( 1192): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3136): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3136): Disconnected process message: 10
,D/TimaKeyStoreProvider( 7794): TimaSignature is unavailable
,D/ActivityThread( 7794): Added TimaKeyStore provider
,D/ResourcesManager( 7794): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,D/DateView( 1192): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1192): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ActivityManager(  903): Killing 6778:com.wsomacp/u0a29 (adj 15): bgCount ##41
,E/lowmemorykiller(  251): Error writing /proc/6778/oom_score_adj; errno=22
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,D/SSRM:n  (  903): SIOP:: AP = 290, PST = 298, CUR = 450
,I/ServiceManager(  352): Waiting for service AtCmdFwd...
,I/ServiceManager(  352): Waiting for service AtCmdFwd...

```
