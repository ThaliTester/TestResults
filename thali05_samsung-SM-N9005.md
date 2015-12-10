#### Test 5065027881383b1_thali05_samsung-SM-N9005 Logs


```
--------- beginning of main
E/SMD     (  301): DCD ON
,D/AndroidRuntime( 7266): 
D/AndroidRuntime( 7266): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7266): CheckJNI is OFF
D/AndroidRuntime( 7266): readGMSProperty: start
D/AndroidRuntime( 7266): readGMSProperty: already setted!!
D/AndroidRuntime( 7266): readGMSProperty: end
D/AndroidRuntime( 7266): addProductProperty: start
E/AffinityControl( 7266): AffinityControl: registerfunction enter
D/AndroidRuntime( 7266): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  904): inState():  stateMachine is null !!
I/PersonaManagerService(  904): PersonaId don't exist
I/ActivityManager(  904): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  904): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
I/ActivityManager(  904): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  904): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager(  904): mDVFSHelper.acquire()
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  904): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7281 uid=10280 gids={50280, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7266): Shutting down VM
E/Zygote  ( 7281): MountEmulatedStorage()
E/Zygote  ( 7281): v2
I/libpersona( 7281): KNOX_SDCARD checking this for 10280
I/libpersona( 7281): KNOX_SDCARD not a persona
D/PointerIcon(  904): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  904): setMouseCustomIcon IconType is same.101
D/PointerIcon(  904): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  904): setHoveringSpenCustomIcon IconType is same.1
I/SELinux ( 7281): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7281): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7281): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7281): TimaSignature is unavailable
D/ActivityThread( 7281): Added TimaKeyStore provider
D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SurfaceFlinger(  254): id=11 Removed YUIInstallC (5/8)
I/SurfaceFlinger(  254): id=11 Removed YUIInstallC (-2/8)
D/ResourcesManager( 7281): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
V/ActivityThread( 3480): updateVisibility : ActivityRecord{11acc83e token=android.os.BinderProxy@165cebc7 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
,I/WebViewFactory( 7281): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,D/ResourcesManager( 7281): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7281): Loading: webviewchromium
,I/LibraryLoader( 7281): Time to load native libraries: 6 ms (timestamps 3836-3842)
I/LibraryLoader( 7281): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7281): Binding Chromium to main looper Looper (main, tid 1) {1f6f76e5}
,I/LibraryLoader( 7281): Expected native library version number "",actual native library version number ""
,I/chromium( 7281): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7281): Initializing chromium process, renderers=0
,W/art     ( 7281): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7281): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7281): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46780 len=2953
,I/chromium( 7281): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229536 len:643667
,I/Adreno-EGL( 7281): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 7281): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7281): Build Date: 11/19/14 Wed
I/Adreno-EGL( 7281): Local Branch: mybranch5813579
I/Adreno-EGL( 7281): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 7281): Local Patches: NONE
I/Adreno-EGL( 7281): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,W/ActivityManager(  904): Activity pause timeout for ActivityRecord{3be1842c u0 com.test.thalitest/.MainActivity t4}
,W/chromium( 7281): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7281): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 7281): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7281): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 7281): CordovaWebView is running on device made by: samsung
,W/art     ( 7281): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7281): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity( 7281): performCreate Call secproduct feature valuefalse
D/Activity( 7281): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer( 7281): Render dirty regions requested: true
,D/Atlas   ( 7281): Validating map...
,D/ActivityManager(  904): post active user change for 0
D/KnoxTimeoutHandler(  904): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  904): handleActiveUserChange for user 0
,V/ActivityThread( 7281): updateVisibility : ActivityRecord{f96e16a token=android.os.BinderProxy@5015e0c {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/SurfaceFlinger(  254): id=15 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService(  904): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  904): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon(  904): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  904): setMouseCustomIcon IconType is same.101
D/PointerIcon(  904): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  904): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer( 7281): Initialized EGL, version 1.4
,I/OpenGLRenderer( 7281): HWUI protection enabled for context ,  &this =0xa1853060 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 7281): Enabling debug mode 0
,D/InputMethodManagerService(  904): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager(  904): mDVFSHelper.release()
W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Timeline(  904): Timeline: Activity_windows_visible id: ActivityRecord{3be1842c u0 com.test.thalitest/.MainActivity t4} time:154455
,W/IInputConnectionWrapper( 7281): showStatusIcon on inactive InputConnection
,I/Timeline( 7281): Timeline: Activity_idle id: android.os.BinderProxy@5015e0c time:154463
,D/JsMessageQueue( 7281): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 7281): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7281): 
,D/jxcore_app_log( 7281): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1355976192
D/JX-Cordova( 7281): jxcore cordova android initializing
,E/SMD     (  301): DCD ON
,W/jxcore-log( 7281): Initializing JXcore engine
W/jxcore-log( 7281): JXcore engine is ready
,W/jxcore-log( 7281): Starting JXcore engine
,E/auditd  ( 1871): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  904): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  904): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,D/SecurityLogAgent( 6912):  SeDenialReceiver : Intent Received : android.intent.action.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 6912):  SeDenialReceiver : File path = null
,W/jxcore-log( 7281): Platform android
W/jxcore-log( 7281): 
,W/jxcore-log( 7281): Process ARCH arm
W/jxcore-log( 7281): 
,I/jxcore-log( 7281): JXcore Cordova bridge is ready!
I/jxcore-log( 7281): 
,W/jxcore-log( 7281): JXcore engine is started
,I/PowerManagerService(  904): [PWL] Off : 50s ago
,D/SSRM:n  (  904): SIOP:: AP = 340, PST = 342, CUR = 450
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  904): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1188): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  904): Plugged
I/MotionRecognitionService(  904): setPowerConnected  = true
,V/HeadsetService( 2918): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2918): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1188):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1188): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1188): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1188): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1188): handleBatteryUpdate
,I/jxcore-log( 7281): Toggling radios to true
I/jxcore-log( 7281): 
,E/SMD     (  301): DCD ON
D/BluetoothAdapter( 7281): enable()
,D/BluetoothAdapter( 7281): enable(): BT is already enabled..!
,I/WifiManager( 7281): packageName : com.test.thalitest
,D/SecContentProvider(  904): uri = 18 selection = isWifiEnabled
D/SecContentProvider2(  904): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  904): mCursor = null
,D/WifiService(  904): setWifiEnabled: true pid=7281, uid=10280
,W/ActivityManager(  904): Permission Denial: getCurrentUser() from pid=7281, uid=10280 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  904): Failed getting userId using ActivityManagerNative
W/WifiService(  904): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7281, uid=10280 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  904): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23057)
W/WifiService(  904): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2181)
W/WifiService(  904): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2169)
W/WifiService(  904): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  904): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  904): name = wifi_on
,I/WifiService(  904): disconnect: pid=7281, uid=10280
,I/wpa_supplicant( 1294): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7281): Radios toggled
I/jxcore-log( 7281): 
,I/jxcore-log( 7281): Got Device Bluetooth address: E0:DB:10:1F:C9:5E
I/jxcore-log( 7281): 
,I/wpa_supplicant( 1294): CTRL-EVENT-DISCONNECTED bssid=C0.AA.4A reason=3 locally_generated=1
,I/jxcore-log( 7281): Perf Test app loaded loaded
I/jxcore-log( 7281): 
I/wpa_supplicant( 1294): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1294): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.4A SSID=4E473730303567
I/wpa_supplicant( 1294): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  904): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1294): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1294): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1294): Disconnected - do not scan
I/wpa_supplicant( 1294): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiConfigStore(  904): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,I/jxcore-log( 7281): check test folder
I/jxcore-log( 7281): 
,E/native  (  904): do suspend true
,I/jxcore-log( 7281): found test : ./testFindPeers.js
I/jxcore-log( 7281): 
,D/WifiP2pService(  904): InactiveState{ what=143375 }
,D/WifiP2pService(  904): P2pEnabledState{ what=143375 }
,D/CommandListener(  293): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 1188): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1188): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
,V/NativeCrypto( 1909): Read error: ssl=0xb4f64a00: I/O error during system call, Connection timed out
,E/WifiConfigStore(  904): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/ConnectivityService(  904): updateNetworkInfo()
I/WifiTrafficPoller(  904): evaluateTrafficStatsPolling
,D/ConnectivityService(  904): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,E/ConnectivityService(  904): updateNetworkInfo()
,V/NativeCrypto( 1909): SSL shutdown failed: ssl=0xb4f64a00: I/O error during system call, Broken pipe
,I/jxcore-log( 7281): found test : ./testSendData.js
I/jxcore-log( 7281): 
D/ConnectivityService(  904): ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
D/ConnectivityService(  904): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
D/NetUtils(  904): android_net_utils_resetConnections in env=0xad7b7f60 clazz=0x9bf5298c iface=wlan0 mask=0x3
,D/StatusBar.NetworkController( 1188): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1188): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1188): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1188): applyOpen
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
D/StatusBar.NetworkController( 1188): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1188): applyOpen
D/StatusBar.NetworkController( 1188): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1188): applyOpen
D/StatusBar.NetworkController( 1188): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1188): applyOpen
D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  904): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10015
D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  904): ValidatedState{ when=-1ms what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  904): DefaultState{ when=-1ms what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  904): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  904): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  904): Checking http://clients3.google.com/generate_204 on <unknown ssid>
D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/WifiStateMachine(  904): Start Disconnecting Watchdog 1
I/libpersona( 7365): KNOX_SDCARD checking this for 10038
I/System.out(  904): (HTTPLog)-Static: isSBSettingEnabled false
I/libpersona( 7365): KNOX_SDCARD not a persona
I/wpa_supplicant( 1294): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1294): P2P: Current p2p state = IDLE
I/ActivityManager(  904): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.samsung.myplace.WIFINotificationHandler: pid=7365 uid=10038 gids={50038, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/wpa_supplicant( 1294): wlan0: State: DISCONNECTED -> SCANNING
E/Zygote  ( 7365): MountEmulatedStorage()
E/Zygote  ( 7365): v2
I/wpa_supplicant( 1294): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1294): First Scan Start
I/qtaguid (  904): Tagging socket 390 with tag ffffffff00000000{4294967295,0} uid 10015, pid: 904, getuid(): 1000
E/native  (  904): do suspend true
,I/System.out(  904): (HTTPLog)-Static: isSBSettingEnabled false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  904): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  904): Validated
,I/SELinux ( 7365): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7365): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7365): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/wpa_supplicant( 1294): Scan requested (ret=0) - scan timeout 30 seconds
,D/WifiP2pService(  904): InactiveState{ what=143375 }
,D/WifiP2pService(  904): P2pEnabledState{ what=143375 }
,D/CommandListener(  293): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 1188): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1188): onWifiSignalChanged enabled=true enabledDesc:null
,I/WifiTrafficPoller(  904): evaluateTrafficStatsPolling
,D/WifiNetworkAgent(  904): NetworkAgent: NetworkAgent channel lost
,D/StatusBar.NetworkController( 1188): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1188): onWifiSignalChanged enabled=true enabledDesc:null
,D/SecContentProvider2(  904): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  904): mCursor = null
,D/TimaKeyStoreProvider( 7365): TimaSignature is unavailable
,D/ActivityThread( 7365): Added TimaKeyStore provider
,D/SecContentProvider2(  904): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  904): mCursor = null
,D/ResourcesManager( 7365): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,W/ResourcesManager( 7365): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ConnectivityService(  904): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  904): calling update connectivity
,D/EntConnectivity(  904): Not allowed due to - mEnabled false
D/ConnectivityService(  904):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  904):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  904): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  904):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1188): CM callback handler got msg 524292
,D/ConnectivityService(  904): sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 2204): CM callback handler got msg 524292
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  904): ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  904): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  904): Disconnected - quitting
,V/Nat464Xlat(  904): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  904): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  904): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1419): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CSLegacyTypeTracker(  904): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  904): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false,
D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  904): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,V/NetworkStats(  904): updateIfacesLocked()
D/NtpTrustedTime(  904): currentTimeMillis() cache hit
V/NetworkStats(  904): performPollLocked(flags=0x1)
,D/NetworkStatsFactory(  904): UpdateStatsForKnox
D/ConnectivityService(  904): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  904): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  904): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false,
D/SmartBondingService(  904): getSBEnabled() enabled =false
D/SmartBondingService(  904): getSBEnabled() enabled =false
D/SmartBondingService(  904): getSBEnabled() enabled =false
,V/NetworkStats(  904): performPollLocked() took 4ms
,D/Tethering(  904): MasterInitialState.processMessage what=3
D/NtpTrustedTime(  904): currentTimeMillis() cache hit
D/NtpTrustedTime(  904): currentTimeMillis() cache hit
,D/SmartBondingService(  904): getNetworkEnabled : wifi : true mobile : true
,D/NtpTrustedTime(  904): currentTimeMillis() cache hit
D/NtpTrustedTime(  904): currentTimeMillis() cache hit
D/NtpTrustedTime(  904): currentTimeMillis() cache hit
D/NtpTrustedTime(  904): currentTimeMillis() cache hit
D/NtpTrustedTime(  904): currentTimeMillis() cache hit
V/NetworkStats(  904): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1188): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1188): updateDataNetType()
D/StatusBar.NetworkController( 1188): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1188): updateLTEICONDataNetType:0
,E/ConnectivityService(  904): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,D/StatusBar.NetworkController( 1188): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1188): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1188): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1188): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1188): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1188): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1188): applyOpen
D/StatusBar.NetworkController( 1188): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1188): applyOpen
D/StatusBar.NetworkController( 1188): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1188): applyOpen
D/StatusBar.NetworkController( 1188): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1188): applyOpen
,I/chromium( 7281): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/chromium( 7281): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/FileWriteThread_Telephony( 1419): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1419): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1419): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1419): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1419): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1419): FileWriteThread : threadType = 3
,I/ServiceManager(  350): Waiting for service AtCmdFwd...
,D/FileWriteThread_Telephony( 1419): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1419): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1419): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1419): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1419): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1419): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1419): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1419): FileWriteThread : threadType = 3
,I/VlingoApplication( 7365): VlingoApplication appVersion ='11.2.2.0.37649', ro.csc.sales_code=XEO
,E/BluetoothHeadset( 7365): BTStateChangeCB is registed
,E/BluetoothHeadset( 7365): BluetoothHeadset service is binded
,I/ActivityManager(  904): Killing 4928:com.sec.spp.push/u0a43 (adj 15): bgCount ##41
,I/Hs20UtilService( 1304): Starting #6
,I/Hs20UtilService( 1304): Message received 5007
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1304): MountReceiver.mPrefHandler - 7002
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6714): NETWORK_STATE_CHANGED_ACTION
,D/SettingsProvider(  904): name = driving_mode_on
D/SettingsProvider(  904): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  904): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  904): selectionArgs: false
D/SettingsProvider(  904): selectionArgs: 10038
D/SecContentProvider(  904): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  904): ret = -1
,D/BluetoothManager( 7365): [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.media.ACTION_SCO_AUDIO_STATE_UPDATED
,I/Hs20UtilService( 1304): Starting #7
,I/Hs20UtilService( 1304): Message received 5007
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1304): MountReceiver.mPrefHandler - 7002
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6714): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  904): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  904): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  904): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  904): getSBEnabled() enabled =false
,D/SmartBondingService(  904): getSBEnabled() enabled =false
D/SmartBondingService(  904): getSBEnabled() enabled =false
,I/ApplicationPolicy(  904): updateDataUsageMap
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  904): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5716): type=WIFI subType= reason=null isConnected=false
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/Zygote  ( 7434): MountEmulatedStorage()
E/Zygote  ( 7434): v2
I/libpersona( 7434): KNOX_SDCARD checking this for 1000
I/libpersona( 7434): KNOX_SDCARD not a persona
,I/DBG_DM  ( 3480): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/SELinux ( 7434): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/ConnectivityService(  904): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ActivityManager(  904): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7434 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/DBG_DM  ( 3480): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,I/SELinux ( 7434): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7434): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7434): TimaSignature is unavailable
,D/ActivityThread( 7434): Added TimaKeyStore provider
,D/ResourcesManager( 7434): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/PCWCLIENTTRACE_LOG( 7434): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 7434): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 7434): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil( 7434): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 7434): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7434): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7434): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7434): noConnectivity : true
,I/ActivityManager(  904): Killing 6488:com.samsung.android.sdk.samsunglink/u0a48 (adj 15): bgCount ##41
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7460): MountEmulatedStorage()
I/ActivityManager(  904): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7460 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 7460): v2
I/libpersona( 7460): KNOX_SDCARD checking this for 10004
I/libpersona( 7460): KNOX_SDCARD not a persona
,I/SELinux ( 7460): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7460): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7460): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7460): TimaSignature is unavailable
,D/ActivityThread( 7460): Added TimaKeyStore provider
,D/ResourcesManager( 7460): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ServiceManager(  350): Waiting for service AtCmdFwd...
,I/ActivityManager(  904): Killing 6567:com.sec.android.provider.badge/u0a92 (adj 15): bgCount ##41
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7480): MountEmulatedStorage()
,E/Zygote  ( 7480): v2
I/libpersona( 7480): KNOX_SDCARD checking this for 1000
I/libpersona( 7480): KNOX_SDCARD not a persona
I/ActivityManager(  904): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7480 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7480): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7480): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7480): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  339): Explicit concurrent mark sweep GC freed 8768(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 446us total 18.874ms
,I/art     (  339): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 394us total 13.468ms
,I/art     (  339): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 387us total 13.848ms
,D/TimaKeyStoreProvider( 7480): TimaSignature is unavailable
,D/ActivityThread( 7480): Added TimaKeyStore provider
,D/ResourcesManager( 7480): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/wpa_supplicant( 1294): nl80211: Received scan results (8 BSSes)
,I/wpa_supplicant( 1294): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 1294): Trying to associate with C0.AA.4A (SSID='4E473730303567' freq=5220 MHz)
I/wpa_supplicant( 1294): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1294): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E473730303567
,D/SecContentProvider2(  904): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  904): mCursor = null
,I/DIAGMON_AGENT( 7480): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7480): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/wpa_supplicant( 1294): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1294): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E473730303567
,I/wpa_supplicant( 1294): Associated with C0.AA.4A
,D/SecContentProvider2(  904): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  904): mCursor = null
,I/wpa_supplicant( 1294): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1294): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.4A SSID=4E473730303567
,I/wpa_supplicant( 1294): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1294): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,I/wpa_supplicant( 1294): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.4A SSID=4E473730303567
,I/wpa_supplicant( 1294): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 1294): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1294): CTRL-EVENT-CONNECTED - Connection to C0.AA.4A completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 1294): Blacklist: Clear (temp) 
,I/wpa_supplicant( 1294): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.4A SSID=4E473730303567
,D/WifiNative-HAL(  904): callSECApiVoid - ID [50]
,D/StatusBar.NetworkController( 1188): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1188): onWifiSignalChanged enabled=true enabledDesc:null
,D/ConnectivityService(  904): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  904): Got NetworkAgent Messenger
D/ConnectivityService(  904): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  904): updateNetworkInfo()
D/ConnectivityService(  904): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService(  904): NetworkAgent connected
E/WifiConfigStore(  904): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  904): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  293): Setting iface cfg
,E/WifiStateMachine(  904): Start Dhcp Watchdog 2
,D/SecContentProvider2(  904): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  904): mCursor = null
,D/SecContentProvider2(  904): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  904): mCursor = null
,D/ConnectivityService(  904): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,I/DIAGMON_AGENT( 7480): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7480): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7480): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT( 7480): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/native  (  904): do suspend false
,D/WifiP2pService(  904): InactiveState{ what=143375 }
,D/SecContentProvider2(  904): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  904): mCursor = null
D/WifiP2pService(  904): P2pEnabledState{ what=143375 }
,I/FOTA_Client( 6780): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 6780): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 6780): [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.511: ( 6798): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.511: ( 6798): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449752968561
,I/KLMS-2.4.511: ( 6798): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.511: ( 6798): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.511: ( 6798): StateImplV2(): networkChangeListener().END
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7500): MountEmulatedStorage()
,E/Zygote  ( 7500): v2
,I/libpersona( 7500): KNOX_SDCARD checking this for 10036
,I/libpersona( 7500): KNOX_SDCARD not a persona
,I/SELinux ( 7500): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7500): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,I/ActivityManager(  904): Start proc com.samsung.android.app.pinboard:tagService for broadcast com.samsung.android.app.pinboard/.service.TagReadyReceiver: pid=7500 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  904): Killing 6582:com.sec.android.app.soundalive/u0a64 (adj 15): bgCount ##41
E/lowmemorykiller(  251): Error writing /proc/6582/oom_score_adj; errno=22
E/SELinux ( 7500): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/dhcpcd  ( 7507): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 7507): version 5.5.6 starting
,E/dhcpcd  ( 7507): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,D/TimaKeyStoreProvider( 7500): TimaSignature is unavailable
D/ActivityThread( 7500): Added TimaKeyStore provider
,D/ResourcesManager( 7500): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
W/ResourcesManager( 7500): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7500): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/dhcpcd  ( 7507): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7507): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7507): if(wlan0) info get Success. (MAC : C0.AA.4A)
I/dhcpcd  ( 7507): bssid match
I/dhcpcd  ( 7507): wlan0: rebinding lease of 192.168.1.128
E/Minikin ( 7500): addFont failed to create font /system/fonts/SamsungSans-light.ttf
D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ActivityManager(  904): Killing 5552:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
E/lowmemorykiller(  251): Error writing /proc/5552/oom_score_adj; errno=22
I/SO_AGENT( 6814): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7531): MountEmulatedStorage()
E/Zygote  ( 7531): v2
I/libpersona( 7531): KNOX_SDCARD checking this for 1000
I/libpersona( 7531): KNOX_SDCARD not a persona
I/SELinux ( 7531): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/ActivityManager(  904): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=7531 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 7531): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7531): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7531): TimaSignature is unavailable
D/ActivityThread( 7531): Added TimaKeyStore provider
D/ResourcesManager( 7531): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
I/ServiceManager(  350): Waiting for service AtCmdFwd...
I/dhcpcd  ( 7507): wlan0: acknowledged 192.168.1.128 from 192.168.1.1
I/dhcpcd  ( 7507): wlan0: leased 192.168.1.128 for 86400 seconds
D/ConnectivityService(  904): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  904): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7557): MountEmulatedStorage()
E/Zygote  ( 7557): v2
I/libpersona( 7557): KNOX_SDCARD checking this for 10043
I/libpersona( 7557): KNOX_SDCARD not a persona
I/ActivityManager(  904): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7557 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  904): Killing 6625:com.wsomacp/u0a29 (adj 15): bgCount ##41
I/SELinux ( 7557): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7557): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7557): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7557): TimaSignature is unavailable
D/ActivityThread( 7557): Added TimaKeyStore provider
D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  904): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager( 7557): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
E/SPPClientService( 7557): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 7557): [PushClientApplication] Push log off : This is Ship build version
D/SPPClientService( 7557): PushLog.txt file is not deleted.
D/SPPClientService( 7557): PushLog.txt file is not deleted.
D/SPPClientService( 7557): ============PushLog. stop!
E/SPPClientService( 7557): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
I/SA      ( 6522): [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
I/SA      ( 6522): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 6522): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 6522): [SLFUCHKMGR] constructor called
I/SA      ( 6522): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6522): [OR] == isSIMCardReady false ==
I/SA      ( 6522): [SCU] == networkStateCheck == false
I/SA      ( 6522): [OR] onReceive END
E/SPPClientService( 7557): [[SystemStateMonitorService]] No Active Internet
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7592): MountEmulatedStorage()
E/Zygote  ( 7592): v2
,I/libpersona( 7592): KNOX_SDCARD checking this for 10074
I/libpersona( 7592): KNOX_SDCARD not a persona
,I/SELinux ( 7592): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/ActivityManager(  904): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=7592 uid=10074 gids={50074, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 7592): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
I/ActivityManager(  904): Killing 6610:com.google.android.apps.docs/u0a112 (adj 15): bgCount ##41
E/SELinux ( 7592): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/native  (  904): do suspend true
,D/WifiP2pService(  904): InactiveState{ what=143375 }
,D/WifiP2pService(  904): P2pEnabledState{ what=143375 }
,D/ConnectivityService(  904): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,D/StatusBar.NetworkController( 1188): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
E/WifiStateMachine(  904): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG7005g"WPA_PSK
E/WifiStateMachine(  904): VerifyingLinkState enter
,D/STATUSBAR-WifiQuickSettingButton( 1188): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiNative-HAL(  904): callSECApiInt - ID [210]
,E/ConnectivityService(  904): updateNetworkInfo()
,D/ConnectivityService(  904): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService(  904): Adding iface wlan0 to network 503
,D/TimaKeyStoreProvider( 7592): TimaSignature is unavailable
,D/ActivityThread( 7592): Added TimaKeyStore provider
,D/WifiWatchdogStateMachine(  904): updateDnsLinkProperty: enter
D/WifiWatchdogStateMachine.DnsPinger(  904): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.DnsResolver(  904): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 1188): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1188): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiWatchdogStateMachine.SingDnsChecker(  904): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  904): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,E/WifiStateMachine(  904): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,E/WifiStateMachine(  904): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller(  904): evaluateTrafficStatsPolling
,I/WifiTrafficPoller(  904): evaluateTrafficStatsPolling
,I/WifiTrafficPoller(  904): mBoosterFLAG : 0
,I/WifiTrafficPoller(  904): current booster mode : FullMode
D/StatusBar.NetworkController( 1188): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1188): onWifiSignalChanged enabled=true enabledDesc:null
D/WifiNative-HAL(  904): callSECApiVoid - ID [212]
,D/StatusBar.NetworkController( 1188): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1188): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
D/StatusBar.NetworkController( 1188): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1188): applyOpen
D/StatusBar.NetworkController( 1188): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1188): applyOpen
D/StatusBar.NetworkController( 1188): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1188): applyOpen
D/StatusBar.NetworkController( 1188): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1188): applyOpen
,D/ResourcesManager( 7592): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,D/ConnectivityService(  904): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService(  904): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService(  904): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService(  904): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  904): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  904): updateSourceRoutes : add src route for:192.168.1.128
,V/        (  293): QcRouteController
,V/        (  293): QcRouteController
,I/sCloudBackupApp( 7592): sCloudBackupApp Version Info : 3.13.7.KK_APP
V/        (  293): QcRouteController
,I/SCloudBackupReceiver( 7592): Other Intent
,I/KnoxUsageLogPro( 7100): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7100): premStatus:2
,I/KnoxUsageLogPro( 7100): isEulaShown : false
I/KnoxUsageLogPro( 7100): KnoxUsageReceiver onReceive : not Processible, just return
,V/        (  293): QcRouteController
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,E/SMD     (  301): DCD ON
,V/        (  293): QcRouteController
,E/Zygote  ( 7623): MountEmulatedStorage()
,E/Zygote  ( 7623): v2
I/libpersona( 7623): KNOX_SDCARD checking this for 10104
,I/libpersona( 7623): KNOX_SDCARD not a persona
,V/        (  293): QcRouteController
,I/ActivityManager(  904): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7623 uid=10104 gids={50104, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/        (  293): QcRouteController
,I/ActivityManager(  904): Killing 6660:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
I/SELinux ( 7623): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7623): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7623): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,V/        (  293): QcRouteController
,D/TimaKeyStoreProvider( 7623): TimaSignature is unavailable
,D/ActivityThread( 7623): Added TimaKeyStore provider
,D/ConnectivityService(  904): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService(  904): LTETest block dns file not exists
,D/ResourcesManager( 7623): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,V/Nat464Xlat(  904): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  904): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  904): calling update connectivity
E/ConnectivityService(  904): updateNetworkInfo()
D/ConnectivityService(  904): ignoring duplicate network state non-change. WIFI, state = CONNECTING
E/ConnectivityService(  904): updateNetworkInfo()
D/ConnectivityService(  904): ignoring duplicate network state non-change. WIFI, state = CONNECTING
D/ConnectivityService(  904): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  904): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  904): calling update connectivity
D/ConnectivityService(  904): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  904):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  904):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  904):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  904):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/EntConnectivity(  904): Not allowed due to - mEnabled false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  904): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  904): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  904): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  904): Checking http://clients3.google.com/generate_204 on "NG7005g"
,I/System.out(  904): (HTTPLog)-Static: isSBSettingEnabled false
,D/ConnectivityService(  904): currentScore = 0, newScore = 60
D/ConnectivityService(  904):    accepting network in place of null
D/ConnectivityService(  904): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1419): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker(  904): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  904): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  904): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  904): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/SmartBondingService(  904): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  904): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  904): getSBEnabled() enabled =false
D/SmartBondingService(  904): getSBEnabled() enabled =false
D/SmartBondingService(  904): getSBEnabled() enabled =false
D/NtpTrustedTime(  904): currentTimeMillis() cache hit
V/NetworkStats(  904): updateIfacesLocked()
V/NetworkStats(  904): performPollLocked(flags=0x1)
,D/Tethering(  904): MasterInitialState.processMessage what=3
D/SmartBondingService(  904): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  904): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  904): getSBEnabled() enabled =false
D/SmartBondingService(  904): getSBEnabled() enabled =false
D/SmartBondingService(  904): getSBEnabled() enabled =false
D/NetworkStatsFactory(  904): UpdateStatsForKnox
D/ConnectivityService(  904): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  904): getNetworkEnabled : wifi : true mobile : true
,V/NetworkStats(  904): performPollLocked() took 4ms
,D/NtpTrustedTime(  904): currentTimeMillis() cache hit
D/EntConnectivity(  904): Not allowed due to - mEnabled false
,D/ConnectivityService(  904): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  904): calling update connectivity
D/ConnectivityService(  904):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  904):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  904): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  904):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  904): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  904): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
,D/ConnectivityService(  904): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService(  904): identical MTU - not setting
D/ConnectivityService(  904): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  904): updateSourceRoutes : add src route for:fe80::ea50:8bff:fede:28a3
D/ConnectivityManager.CallbackHandler( 1188): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 2204): CM callback handler got msg 524290
,V/        (  293): QcRouteController
,D/NtpTrustedTime(  904): currentTimeMillis() cache hit
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1188): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1188): updateDataNetType()
D/StatusBar.NetworkController( 1188): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1188): updateLTEICONDataNetType:0
,D/NtpTrustedTime(  904): currentTimeMillis() cache hit
D/NtpTrustedTime(  904): currentTimeMillis() cache hit
D/NtpTrustedTime(  904): currentTimeMillis() cache hit
D/NtpTrustedTime(  904): currentTimeMillis() cache hit
V/NetworkStats(  904): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  904): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1188): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1188): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1188): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1188): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1188): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
D/StatusBar.NetworkController( 1188): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1188): applyOpen
,D/StatusBar.NetworkController( 1188): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1188): applyOpen
D/StatusBar.NetworkController( 1188): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1188): applyOpen
D/StatusBar.NetworkController( 1188): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1188): applyOpen
,V/        (  293): QcRouteController
,W/NetworkManagementService(  904): route cmd failed: 
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
,I/System.out(  904): KnoxVpnUidStorageknoxVpnSupported API value returned is false
D/ConnectivityService(  904): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1188): CM callback handler got msg 524295
D/ConnectivityService(  904):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  904): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  904): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  904): calling update connectivity
D/ConnectivityService(  904):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  904):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 2204): CM callback handler got msg 524295
D/ConnectivityService(  904): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1188): CM callback handler got msg 524295
D/ConnectivityService(  904):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  904): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 2204): CM callback handler got msg 524295
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  904): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 10 Dec 2015 13:09:29 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449752969907], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449752969890]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  904): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  904): Validated
D/ConnectivityService(  904): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  904): rematching NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  904):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  904):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  904):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  904): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
,D/ConnectivityService(  904): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  904): calling update connectivity
D/ConnectivityService(  904):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  904):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  904): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1188): CM callback handler got msg 524290
D/ConnectivityService(  904):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  904): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 2204): CM callback handler got msg 524290
D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1188): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1188): updateDataNetType()
D/StatusBar.NetworkController( 1188): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1188): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1188): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1188): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1188): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1188): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1188): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7648): MountEmulatedStorage()
E/Zygote  ( 7648): v2
I/libpersona( 7648): KNOX_SDCARD checking this for 10146
I/libpersona( 7648): KNOX_SDCARD not a persona
,I/ServiceManager(  350): Waiting for service AtCmdFwd...
,I/SELinux ( 7648): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/ActivityManager(  904): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7648 uid=10146 gids={50146, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  904): Killing 6680:com.samsung.android.app.watchmanagerstub/u0a126 (adj 15): bgCount ##41
E/lowmemorykiller(  251): Error writing /proc/6680/oom_score_adj; errno=22
I/SELinux ( 7648): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7648): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7648): TimaSignature is unavailable
,D/ActivityThread( 7648): Added TimaKeyStore provider
,D/ResourcesManager( 7648): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7648): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7648): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7648): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7648): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GpsLocationProvider(  904): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3480): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  904): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 3480): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
D/SmartBondingService(  904): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  904): SmartBondingReceiver: wifi ap is not changed
D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1894): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
W/ContextImpl( 1894): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/SmartBondingService(  904): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  904): getSBEnabled() enabled =false
D/SmartBondingService(  904): getSBEnabled() enabled =false
D/SmartBondingService(  904): getSBEnabled() enabled =false
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5716): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  904): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  904): Explicit concurrent mark sweep GC freed 110916(6MB) AllocSpace objects, 27(480KB) LOS objects, 17% free, 37MB/45MB, paused 1.363ms total 114.052ms
D/SecContentProvider2(  904): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  904): mCursor = null
,I/WebViewFactory( 7648): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,D/ResourcesManager( 7648): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7648): Loading: webviewchromium
,I/LibraryLoader( 7648): Time to load native libraries: 7 ms (timestamps 2345-2352)
I/LibraryLoader( 7648): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7648): Binding Chromium to main looper Looper (main, tid 1) {27efca0e}
,I/LibraryLoader( 7648): Expected native library version number "",actual native library version number ""
,I/chromium( 7648): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7648): Initializing chromium process, renderers=0
,W/art     ( 7648): Attempt to remove local handle scope entry from IRT, ignoring
,D/ConnectivityService(  904): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,W/chromium( 7648): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7648): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46780 len=2953
,I/chromium( 7648): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229536 len:643667
,W/AudioManagerAndroid( 7648): Requires BLUETOOTH permission
,I/Adreno-EGL( 7648): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 7648): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7648): Build Date: 11/19/14 Wed
I/Adreno-EGL( 7648): Local Branch: mybranch5813579
I/Adreno-EGL( 7648): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 7648): Local Patches: NONE
I/Adreno-EGL( 7648): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,I/ServiceManager(  350): Waiting for service AtCmdFwd...
,I/NSApplication( 7648): Starting up...
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  904): Killing 6696:com.samsung.helphub/1000 (adj 15): bgCount ##41
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7707): MountEmulatedStorage()
,E/Zygote  ( 7707): v2
I/libpersona( 7707): KNOX_SDCARD checking this for 10158
I/libpersona( 7707): KNOX_SDCARD not a persona
,I/ActivityManager(  904): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7707 uid=10158 gids={50158, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 7707): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7707): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7707): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7707): TimaSignature is unavailable
,D/ActivityThread( 7707): Added TimaKeyStore provider
,D/ResourcesManager( 7707): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 7707): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7707): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7707): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 7707): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7707): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7707): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7727): MountEmulatedStorage()
E/Zygote  ( 7727): v2
I/libpersona( 7727): KNOX_SDCARD checking this for 10186
I/libpersona( 7727): KNOX_SDCARD not a persona
,I/ActivityManager(  904): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7727 uid=10186 gids={50186, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
I/ActivityManager(  904): Killing 6731:com.samsung.android.snote:provider/u0a168 (adj 15): bgCount ##41,
,I/SELinux ( 7727): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7727): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7727): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7727): TimaSignature is unavailable
,D/ActivityThread( 7727): Added TimaKeyStore provider
,D/ResourcesManager( 7727): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7727): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7727): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7727): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 7727): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7727): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService(  904): exchangeData() failure , invalid userId
,D/RCPManagerService(  904): exchangeData() failure , invalid userId
,D/RCPManagerService(  904): exchangeData() failure , invalid userId
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService(  904): exchangeData() failure , invalid userId
,E/Zygote  ( 7750): MountEmulatedStorage()
E/Zygote  ( 7750): v2
I/libpersona( 7750): KNOX_SDCARD checking this for 10092
I/libpersona( 7750): KNOX_SDCARD not a persona
,I/SELinux ( 7750): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SELinux ( 7750): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,D/RCPManagerService(  904): exchangeData() failure , invalid userId
,E/SELinux ( 7750): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/RCPManagerService(  904): exchangeData() failure , invalid userId
,I/ActivityManager(  904): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7750 uid=10092 gids={50092, 9997} abi=armeabi-v7a
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 6912): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6912): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6912): StateMachine : Current State = 1
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6912): StateMachine : Changed Current State = 1
,I/ActivityManager(  904): Killing 6749:com.sec.kidsplat.installer/u0a189 (adj 15): bgCount ##41
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/jxcore-log( 7281): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 7281): 
,D/TimaKeyStoreProvider( 7750): TimaSignature is unavailable
,D/ActivityThread( 7750): Added TimaKeyStore provider
,E/Zygote  ( 7771): MountEmulatedStorage()
E/Zygote  ( 7771): v2
I/libpersona( 7771): KNOX_SDCARD checking this for 10200
I/libpersona( 7771): KNOX_SDCARD not a persona
,I/ActivityManager(  904): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7771 uid=10200 gids={50200, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7771): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7771): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7771): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  904): Killing 5285:com.sec.android.app.samsungapps/u0a45 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7771): TimaSignature is unavailable
,D/ActivityThread( 7771): Added TimaKeyStore provider
,D/ResourcesManager( 7750): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/ResourcesManager( 7771): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,D/BadgeProvider( 7750): onCreate
,D/BadgeProvider( 7750): DatabaseHelper
,D/BadgeProvider( 7750): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/ActivityManager(  904): Killing 4424:com.sec.android.app.shealth/u0a40 (adj 15): bgCount ##41
,D/BadgeProvider( 7750): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7750): sendNotify, [notify] : null
D/BadgeProvider( 7750): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7750): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7750): update, [UpdateCount] : 1
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Launcher.Model( 1441): reloadBadges entered.
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 7788): MountEmulatedStorage()
E/Zygote  ( 7788): v2
,I/libpersona( 7788): KNOX_SDCARD checking this for 10045
,I/libpersona( 7788): KNOX_SDCARD not a persona
,I/ActivityManager(  904): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7788 uid=10045 gids={50045, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,W/ActivityManager(  904): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/art     (  339): Explicit concurrent mark sweep GC freed 8750(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 418us total 17.311ms
,W/Atfwd_Sendcmd(  350): AtCmdFwd service not published, waiting... retryCnt : 4
,I/art     (  339): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 280us total 11.020ms
,I/SELinux ( 7788): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/art     (  339): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 449us total 11.081ms
,I/SELinux ( 7788): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7788): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7788): TimaSignature is unavailable
,D/ActivityThread( 7788): Added TimaKeyStore provider
,D/ResourcesManager( 7788): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-1/base.apk
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 7788): notifyNetworkActivated
,W/ContextImpl( 7788): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  904): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/hcjo    ( 7788): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7788): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 7788): exit::IDLE
,D/InitializeManagerStateMachine( 7788): entry::NETWORK_CHECK
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7788): execute::NETWORK_CHECK:NETWORK_STATE_OK
,D/InitializeManagerStateMachine( 7788): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7788): entry::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 7788): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7788): exit::CHECK_COUNTRY_INFO,
,D/InitializeManagerStateMachine( 7788): entry::SUCCESS
D/hcjo    ( 7788): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 7788): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 7788): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7788): exit::SUCCESS
,D/InitializeManagerStateMachine( 7788): entry::IDLE
,I/Hs20UtilService( 1304): Starting #8
,I/Hs20UtilService( 1304): Message received 5007
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  904): Killing 6542:com.android.mms/u0a55 (adj 15): bgCount ##41
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6714): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 1304): Starting #9
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/Hs20UtilService( 1304): Message received 5007
,I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6714): NETWORK_STATE_CHANGED_ACTION
,D/CountryDetector(  904): No listener is left
,I/Hs20UtilService( 1304): Starting #10
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/Hs20UtilService( 1304): Message received 5007
,V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6714): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 1304): Starting #11
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1304): Message received 5007
,D/WifiStateMachine(  904): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6714): NETWORK_STATE_CHANGED_ACTION
,I/PCWCLIENTTRACE_PushUtil( 7434): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 7434): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7434): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7434): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/SurfaceFlinger(  254): id=16 createSurf (1x1),1 flag=4, Uoast
,I/DIAGMON_AGENT( 7480): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7480): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/PowerManagerService(  904): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=904
,E/SMD     (  301): DCD ON
,I/FOTA_Client( 6780): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 6780): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 6780): [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.511: ( 6798): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.511: ( 6798): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449752972709
,I/KLMS-2.4.511: ( 6798): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.511: ( 6798): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.511: ( 6798): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.511: ( 6798): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.511: ( 6798): StateImplV2(): networkChangeListener().END
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SO_AGENT( 6814): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,E/WifiStateMachine(  904): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 7557): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 6522): [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
,I/SA      ( 6522): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 6522): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6522): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6522): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6522): [SCU] == networkStateCheck == true
,I/SA      ( 6522): [DM] getCountryCodeFromCSC : PL
I/SA      ( 6522): isChinaCountryCode : false
I/SA      ( 6522): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6522): [OR] == networkStateCheck true ==
,I/SA      ( 6522): [OR] GetMyCountryZoneTask
,I/SA      ( 6522): [OR] onReceive END
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SCloudBackupReceiver( 7592): Other Intent
,I/KnoxUsageLogPro( 7100): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7100): premStatus:2
,I/KnoxUsageLogPro( 7100): isEulaShown : false
,I/KnoxUsageLogPro( 7100): KnoxUsageReceiver onReceive : not Processible, just return
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6522): [SRS] prepareGetMyCountryZone
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 7707): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7707): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7707): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6522): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,D/RCPManagerService(  904): exchangeData() failure , invalid userId
,D/RCPManagerService(  904): exchangeData() failure , invalid userId
,I/SA      ( 6522): [SSP] query invoked
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6912): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6912): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6912): StateMachine : Current State = 1
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 6912): StateMachine : Changed Current State = 1
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6522): [TPMU] GetMccFromDB : null
I/SA      ( 6522): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6522): [TPM] isNoProxy(default) : true
,E/File    ( 6522): fail readDirectory() errno=2
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7788): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7788): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7788): exit::IDLE
D/InitializeManagerStateMachine( 7788): entry::NETWORK_CHECK
D/ConnectivityService(  904): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7788): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7788): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7788): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7788): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7788): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7788): entry::SUCCESS
D/hcjo    ( 7788): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 7788): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7788): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7788): exit::SUCCESS
D/InitializeManagerStateMachine( 7788): entry::IDLE
,I/dhcpcd  ( 7507): wlan0: sending IPv6 Router Solicitation
,I/SA      ( 6522): [RC New] Execute method=[GET] start
,I/SA      ( 6522): [RC New] Security=[true]
,I/System.out( 6522): Thread-1065(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6522): Thread-1065(ApacheHTTPLog):isShipBuild true
,I/System.out( 6522): Thread-1065(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,E/Watchdog(  904): !@Sync 5
,I/SA      ( 6522): [RC New] [v2liruge] api execute + 784
,I/SA      ( 6522): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6522): AsyncTask #1 calls detatch()
,I/SA      ( 6522): [TPMU] getNetworkMcc : 
,I/SA      ( 6522): [SCU] saveMccToPreferece Start
,I/SA      ( 6522): [SCU] RegionMCC : 260
,I/SA      ( 6522): [SSP] query invoked
,I/SA      ( 6522): [TPMU] GetMccFromDB : null
,I/SA      ( 6522): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6522): [SCU] saveMccToPreferece End
,I/SA      ( 6522): [RC New] executeRequest [v2liruge] end. 881
,I/SA      ( 6522): [RC New] Execute end
,I/SA      ( 6522): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 6522): [OR] GetMyCountryZoneTask Success
,I/GAV4    ( 7648): Thread[GAThread,5,main]: No campaign data found.
,E/SMD     (  301): DCD ON
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SurfaceFlinger(  254): id=16 Removed Uoast (8/9)
,I/SurfaceFlinger(  254): id=16 Removed Uoast (-2/9)
,D/PowerManagerService(  904): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 904) eventTime = 167575
,D/PowerManagerService(  904): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=904 (0x0)
,D/PowerManagerService(  904): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=904, ws=WorkSource{10067}) (elapsedTime=3481)
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  904): stay LED for fully charged
D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  904): Plugged
I/MotionRecognitionService(  904): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1188): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1188): handleBatteryUpdate
,V/HeadsetService( 2918): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2918): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1188):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1188): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1188): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1188): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  904): SIOP:: AP = 340, PST = 336, CUR = 450
,I/dhcpcd  ( 7507): wlan0: sending IPv6 Router Solicitation
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7434): mConnectivityHandler : connected
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 7434): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE( 7434): ================================================
,I/CSTORAGE( 7434):  CSTORAGE_SKM_LIB v1.0.6
I/CSTORAGE( 7434): ================================================
I/PCWCLIENTTRACE_SecurePreferencesJNI( 7434): [GetString-S]
,E/art     ( 7434): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
W/PCWCLIENTTRACE_SecurePreferencesJNI( 7434): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI( 7434): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 7434): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7434): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7434): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 7434): [ensureRegistration] - No Samsung account
,E/SMD     (  301): DCD ON
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/dhcpcd  ( 7507): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 7507): wlan0: no IPv6 Routers available
,E/SMD     (  301): DCD ON
,D/PreloadUpdateManagerStateMachine( 7788): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7788): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 7788): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7788): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7788): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7788): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7788): entry::IDLE
,D/PreloadUpdateManagerStateMachine( 7788): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7788): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7788): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7788): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7788): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7788): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7788): entry::IDLE
,E/SMD     (  301): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): stay LED for fully charged
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1188): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1188):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryMeterView( 1188): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1188): handleBatteryUpdate
,V/HeadsetService( 2918): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2918): Disconnected process message: 10
,D/BatteryMeterView( 1188): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1188): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  904): SIOP:: AP = 320, PST = 331, CUR = 450
,E/SMD     (  301): DCD ON
,I/ActivityManager(  904): Waited long enough for: ServiceRecord{9e6f6aa u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,E/SMD     (  301): DCD ON
,I/PowerManagerService(  904): [PWL] Off : 75s ago
,I/ServiceManager(  350): Waiting for service AtCmdFwd...
,I/ServiceManager(  350): Waiting for service AtCmdFwd...
,E/SMD     (  301): DCD ON
,I/ServiceManager(  350): Waiting for service AtCmdFwd...
,I/ServiceManager(  350): Waiting for service AtCmdFwd...
,I/ServiceManager(  350): Waiting for service AtCmdFwd...
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 310, PST = 328, CUR = 450
,W/Atfwd_Sendcmd(  350): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  301): DCD ON
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  904): waitForAlarm result :8
,E/SMD     (  301): DCD ON
,E/Watchdog(  904): !@Sync 6
,E/SMD     (  301): DCD ON
,V/AlarmManager(  904): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1188): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1188): handleTimeUpdate
,D/KeyguardEffectViewController( 1188): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1188): *** don't update sliding image ***
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  904): stay LED for fully charged
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  904): Plugged
,D/KeyguardUpdateMonitor( 1188): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService(  904): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1188): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1188):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1188): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2918): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2918): Disconnected process message: 10
,D/BatteryMeterView( 1188): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1188): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1188): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1188): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  (  904): SIOP:: AP = 310, PST = 325, CUR = 450
,I/ClearcutLoggerApiImpl( 1909): disconnect managed GoogleApiClient
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  904): SIOP:: AP = 310, PST = 322, CUR = 450
,E/SMD     (  301): DCD ON
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  301): DCD ON
,I/PowerManagerService(  904): [PWL] Off : 105s ago
,I/Atfwd_Sendcmd(  350): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  350): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  301): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 310, PST = 320, CUR = 450
,E/SMD     (  301): DCD ON
,I/ServiceManager(  350): Waiting for service AtCmdFwd...
,E/SMD     (  301): DCD ON
,I/ServiceManager(  350): Waiting for service AtCmdFwd...
,I/ServiceManager(  350): Waiting for service AtCmdFwd...
,E/Watchdog(  904): !@Sync 7
,I/ServiceManager(  350): Waiting for service AtCmdFwd...
,E/SMD     (  301): DCD ON
,I/ServiceManager(  350): Waiting for service AtCmdFwd...
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  350): AtCmdFwd service not published, waiting... retryCnt : 1
,D/SSRM:n  (  904): SIOP:: AP = 310, PST = 319, CUR = 450
,E/SMD     (  301): DCD ON
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  301): DCD ON
,I/ServiceManager(  350): Waiting for service AtCmdFwd...
,I/ServiceManager(  350): Waiting for service AtCmdFwd...
,I/ServiceManager(  350): Waiting for service AtCmdFwd...
,E/SMD     (  301): DCD ON
,I/ServiceManager(  350): Waiting for service AtCmdFwd...
,I/ServiceManager(  350): Waiting for service AtCmdFwd...
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  350): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:n  (  904): SIOP:: AP = 300, PST = 317, CUR = 450
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,I/PowerManagerService(  904): [PWL] Off : 140s ago
,E/SMD     (  301): DCD ON
,I/ServiceManager(  350): Waiting for service AtCmdFwd...
,D/SSRM:n  (  904): SIOP:: AP = 300, PST = 315, CUR = 450
,I/ServiceManager(  350): Waiting for service AtCmdFwd...
,V/AlarmManager(  904): waitForAlarm result :4
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  350): Waiting for service AtCmdFwd...
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): stay LED for fully charged
D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1188): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1188):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1188): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1188): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1188): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2918): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2918): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1188): handleBatteryUpdate
,E/SMD     (  301): DCD ON
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  904): waitForAlarm result :8
,I/ServiceManager(  350): Waiting for service AtCmdFwd...
,I/ServiceManager(  350): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  350): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  301): DCD ON
,E/Watchdog(  904): !@Sync 8
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 300, PST = 311, CUR = 450
,E/SMD     (  301): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  904): Plugged
,D/KeyguardUpdateMonitor( 1188): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1188): handleBatteryUpdate
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1188):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1188): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1188): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1188): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2918): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2918): Disconnected process message: 10
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,I/ServiceManager(  350): Waiting for service AtCmdFwd...
,D/SSRM:n  (  904): SIOP:: AP = 300, PST = 307, CUR = 450
,E/SMD     (  301): DCD ON
,I/ServiceManager(  350): Waiting for service AtCmdFwd...
,I/ServiceManager(  350): Waiting for service AtCmdFwd...
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  904): Plugged
,D/KeyguardUpdateMonitor( 1188): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1188): handleBatteryUpdate
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1188):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  904): stay LED for fully charged
,D/BatteryMeterView( 1188): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1188): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1188): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2918): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2918): Disconnected process message: 10
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  350): Waiting for service AtCmdFwd...
,E/SMD     (  301): DCD ON
,I/ServiceManager(  350): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  350): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 300, PST = 305, CUR = 450
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/Watchdog(  904): !@Sync 9
,E/SMD     (  301): DCD ON
,I/PowerManagerService(  904): [PWL] Off : 180s ago
,D/SSRM:n  (  904): SIOP:: AP = 300, PST = 304, CUR = 450
,E/SMD     (  301): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1188): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1188): handleBatteryUpdate
,I/MotionRecognitionService(  904): Plugged
I/MotionRecognitionService(  904): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1188):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  904): stay LED for fully charged
,D/BatteryMeterView( 1188): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1188): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1188): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2918): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2918): Disconnected process message: 10
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  301): DCD ON
,I/ServiceManager(  350): Waiting for service AtCmdFwd...
,I/ServiceManager(  350): Waiting for service AtCmdFwd...
,I/ServiceManager(  350): Waiting for service AtCmdFwd...
,E/SMD     (  301): DCD ON
,I/ServiceManager(  350): Waiting for service AtCmdFwd...
,I/ServiceManager(  350): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  350): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:n  (  904): SIOP:: AP = 300, PST = 303, CUR = 450
,E/SMD     (  301): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  904): stay LED for fully charged
D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1188): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1188): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1188):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1188): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2918): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2918): Disconnected process message: 10
,D/BatteryMeterView( 1188): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1188): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 300, PST = 302, CUR = 450
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  904): stay LED for fully charged
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1188): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1188): handleBatteryUpdate
I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1188):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 2918): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2918): Disconnected process message: 10
,D/BatteryMeterView( 1188): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1188): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1188): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  301): DCD ON
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService(  904): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  904): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  904): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  904): initializing...
,I/TLC_TIMA_PKM_initialize(  904): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  904): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication(  904): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  904): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  904): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  904): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  904): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  904): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  904): App is not loaded in QSEE
,D/QSEECOMAPI: (  904): Loaded image: APP id = 4
,I/TZ: qc_tlc_communication(  904): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  904): Trustlet response is completed
,E/SMD     (  301): DCD ON
,E/Watchdog(  904): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel(  904): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  904): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  904): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  904): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 300, PST = 301, CUR = 450
,E/SMD     (  301): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  904): Plugged,
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 1188): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1188): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1188):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1188): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1188): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1188): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2918): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2918): Disconnected process message: 10
,E/SMD     (  301): DCD ON
,I/Atfwd_Sendcmd(  350): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  350): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  301): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 300, PST = 300, CUR = 450
,E/SMD     (  301): DCD ON
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  301): DCD ON
,I/PowerManagerService(  904): [PWL] Off : 225s ago
,V/AlarmManager(  904): waitForAlarm result :4
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  904): stay LED for fully charged
,I/ActivityManager(  904): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=7870 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,E/Zygote  ( 7870): MountEmulatedStorage()
,E/Zygote  ( 7870): v2
I/libpersona( 7870): KNOX_SDCARD checking this for 10096
I/libpersona( 7870): KNOX_SDCARD not a persona
,D/KeyguardUpdateMonitor( 1188): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1188): handleTimeUpdate
,I/MotionRecognitionService(  904): Plugged
I/MotionRecognitionService(  904): setPowerConnected  = true
,I/SELinux ( 7870): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,D/KeyguardUpdateMonitor( 1188): received broadcast android.intent.action.BATTERY_CHANGED
,I/SELinux ( 7870): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,V/HeadsetService( 2918): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2918): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1188): handleBatteryUpdate
,E/SELinux ( 7870): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/STATUSBAR-PhoneStatusBar( 1188):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1188): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1188): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1188): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardEffectViewController( 1188): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1188): *** don't update sliding image ***
,D/TimaKeyStoreProvider( 7870): TimaSignature is unavailable
,D/ActivityThread( 7870): Added TimaKeyStore provider
,D/ResourcesManager( 7870): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,D/DateView( 1188): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1188): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ActivityManager(  904): Killing 6830:com.samsung.android.scloud.sync/u0a76 (adj 15): bgCount ##41
,E/SMD     (  301): DCD ON
,E/SMD     (  301): DCD ON
,I/ServiceManager(  350): Waiting for service AtCmdFwd...
,D/SSRM:n  (  904): SIOP:: AP = 300, PST = 300, CUR = 450
,I/ServiceManager(  350): Waiting for service AtCmdFwd...
,I/ServiceManager(  350): Waiting for service AtCmdFwd...

```
