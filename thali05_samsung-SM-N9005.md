#### Test 5198634075bb434_thali05_samsung-SM-N9005 Logs


```
--------- beginning of main
E/SMD     (  289): DCD ON
--------- beginning of system
W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/AndroidRuntime( 7013): 
D/AndroidRuntime( 7013): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7013): CheckJNI is OFF
D/AndroidRuntime( 7013): readGMSProperty: start
D/AndroidRuntime( 7013): readGMSProperty: already setted!!
D/AndroidRuntime( 7013): readGMSProperty: end
D/AndroidRuntime( 7013): addProductProperty: start
E/AffinityControl( 7013): AffinityControl: registerfunction enter
D/AndroidRuntime( 7013): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  762): inState():  stateMachine is null !!
I/PersonaManagerService(  762): PersonaId don't exist
I/ActivityManager(  762): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  762): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  762): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  762): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager(  762): mDVFSHelper.acquire()
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  762): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7028 uid=10262 gids={50262, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 7028): MountEmulatedStorage()
E/Zygote  ( 7028): v2
I/libpersona( 7028): KNOX_SDCARD checking this for 10262
I/libpersona( 7028): KNOX_SDCARD not a persona
I/SELinux ( 7028): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7028): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
D/AndroidRuntime( 7013): Shutting down VM
D/PointerIcon(  762): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  762): setMouseCustomIcon IconType is same.101
D/PointerIcon(  762): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  762): setHoveringSpenCustomIcon IconType is same.1
E/SELinux ( 7028): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7028): TimaSignature is unavailable
D/ActivityThread( 7028): Added TimaKeyStore provider
I/SurfaceFlinger(  254): id=11 Removed YUIInstallC (5/8)
I/SurfaceFlinger(  254): id=11 Removed YUIInstallC (-2/8)
D/ConnectivityService(  762): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/ActivityThread( 3650): updateVisibility : ActivityRecord{3dd825a8 token=android.os.BinderProxy@ba20aa9 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
D/ResourcesManager( 7028): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,I/WebViewFactory( 7028): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,D/ResourcesManager( 7028): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7028): Loading: webviewchromium
,I/LibraryLoader( 7028): Time to load native libraries: 5 ms (timestamps 3863-3868)
I/LibraryLoader( 7028): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7028): Binding Chromium to main looper Looper (main, tid 1) {21c9f557}
,I/LibraryLoader( 7028): Expected native library version number "",actual native library version number ""
,I/chromium( 7028): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7028): Initializing chromium process, renderers=0
,W/art     ( 7028): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7028): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7028): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46780 len=2953
I/chromium( 7028): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229536 len:643667
,I/Adreno-EGL( 7028): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 7028): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7028): Build Date: 11/19/14 Wed
I/Adreno-EGL( 7028): Local Branch: mybranch5813579
I/Adreno-EGL( 7028): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 7028): Local Patches: NONE
I/Adreno-EGL( 7028): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,W/chromium( 7028): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7028): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/ActivityManager(  762): Activity pause timeout for ActivityRecord{1502b387 u0 com.test.thalitest/.MainActivity t4}
,W/art     ( 7028): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7028): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 7028): CordovaWebView is running on device made by: samsung
,W/art     ( 7028): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7028): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity( 7028): performCreate Call secproduct feature valuefalse
,D/Activity( 7028): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer( 7028): Render dirty regions requested: true
,D/Atlas   ( 7028): Validating map...
,D/ActivityManager(  762): post active user change for 0
,D/KnoxTimeoutHandler(  762): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  762): handleActiveUserChange for user 0
,V/ActivityThread( 7028): updateVisibility : ActivityRecord{a682a74 token=android.os.BinderProxy@18231986 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/SurfaceFlinger(  254): id=15 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService(  762): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  762): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon(  762): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  762): setMouseCustomIcon IconType is same.101
D/PointerIcon(  762): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  762): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer( 7028): Initialized EGL, version 1.4
,I/OpenGLRenderer( 7028): HWUI protection enabled for context ,  &this =0xa1853060 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 7028): Enabling debug mode 0
,D/InputMethodManagerService(  762): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager(  762): mDVFSHelper.release()
,I/Timeline(  762): Timeline: Activity_windows_visible id: ActivityRecord{1502b387 u0 com.test.thalitest/.MainActivity t4} time:154408
,W/IInputConnectionWrapper( 7028): showStatusIcon on inactive InputConnection
,I/Timeline( 7028): Timeline: Activity_idle id: android.os.BinderProxy@18231986 time:154411
,D/JsMessageQueue( 7028): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 7028): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7028): 
,D/jxcore_app_log( 7028): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1357820160
,D/JX-Cordova( 7028): jxcore cordova android initializing
,E/SMD     (  289): DCD ON
,W/jxcore-log( 7028): Initializing JXcore engine
,W/jxcore-log( 7028): JXcore engine is ready
,W/jxcore-log( 7028): Starting JXcore engine
,E/auditd  ( 1847): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  762): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
,D/SecurityLogAgent:SEDenialService(  762): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,E/Zygote  ( 7108): MountEmulatedStorage()
I/ActivityManager(  762): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7108 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/Zygote  ( 7108): v2
I/libpersona( 7108): KNOX_SDCARD checking this for 1000
I/libpersona( 7108): KNOX_SDCARD not a persona
,I/SELinux ( 7108): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7108): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7108): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7108): TimaSignature is unavailable
,D/ActivityThread( 7108): Added TimaKeyStore provider
,D/ResourcesManager( 7108): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 7108):  SeDenialReceiver : Intent Received : android.intent.action.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7108):  SeDenialReceiver : File path = null
,I/ActivityManager(  762): Killing 6021:com.sec.android.widgetapp.activeapplicationwidget/u0a182 (adj 15): bgCount ##41
,W/jxcore-log( 7028): Platform android
W/jxcore-log( 7028): 
,W/jxcore-log( 7028): Process ARCH arm
W/jxcore-log( 7028): 
,I/PowerManagerService(  762): [PWL] Off : 50s ago
,D/SSRM:n  (  762): SIOP:: AP = 330, PST = 340, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  762): stay LED for fully charged
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3125): Disconnected process message: 10
,I/jxcore-log( 7028): JXcore Cordova bridge is ready!
I/jxcore-log( 7028): 
W/jxcore-log( 7028): JXcore engine is started
,I/jxcore-log( 7028): Toggling radios to true
I/jxcore-log( 7028): 
,D/BluetoothAdapter( 7028): enable()
,D/BluetoothAdapter( 7028): enable(): BT is already enabled..!
,I/WifiManager( 7028): packageName : com.test.thalitest
D/SecContentProvider(  762): uri = 18 selection = isWifiEnabled
D/SecContentProvider2(  762): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  762): mCursor = null
,D/WifiService(  762): setWifiEnabled: true pid=7028, uid=10262
W/ActivityManager(  762): Permission Denial: getCurrentUser() from pid=7028, uid=10262 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  762): Failed getting userId using ActivityManagerNative
W/WifiService(  762): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7028, uid=10262 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  762): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23057)
W/WifiService(  762): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2181)
W/WifiService(  762): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2169)
W/WifiService(  762): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  762): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider(  762): name = wifi_on
,I/WifiService(  762): disconnect: pid=7028, uid=10262
,I/wpa_supplicant( 1297): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7028): Radios toggled
I/jxcore-log( 7028): 
,I/wpa_supplicant( 1297): CTRL-EVENT-DISCONNECTED bssid=C0.AA.4A reason=3 locally_generated=1
,I/wpa_supplicant( 1297): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1297): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.4A SSID=4E473730303567
I/wpa_supplicant( 1297): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  762): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1297): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1297): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1297): Disconnected - do not scan
I/wpa_supplicant( 1297): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiConfigStore(  762): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  762): do suspend true
,D/WifiP2pService(  762): InactiveState{ what=143375 }
,D/WifiP2pService(  762): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1186): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1186): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
,D/CommandListener(  283): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1665): Read error: ssl=0xa1b2ae00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1665): SSL shutdown failed: ssl=0xa1b2ae00: I/O error during system call, Broken pipe
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  762): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10015
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): ValidatedState{ when=0 what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): DefaultState{ when=0 what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Checking http://clients3.google.com/generate_204 on "NG7005g"
,I/System.out(  762): (HTTPLog)-Static: isSBSettingEnabled false
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Validated
,D/ConnectivityService(  762): Validated NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  762): rematching NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  762):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService(  762):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  762):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  762): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,D/ConnectivityService(  762): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  762): calling update connectivity
D/ConnectivityService(  762):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  762):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  762): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,I/WifiTrafficPoller(  762): evaluateTrafficStatsPolling
,E/WifiConfigStore(  762): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  762):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1186): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1186): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1186): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1186): refreshSignalCluster - setNWBoosterIndicators(false)
,E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
,D/StatusBar.NetworkController( 1186): applyOpen
,D/ConnectivityService(  762): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/StatusBar.NetworkController( 1186): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1186): applyOpen
D/StatusBar.NetworkController( 1186): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1186): applyOpen
D/StatusBar.NetworkController( 1186): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1186): applyOpen
,E/ConnectivityService(  762): updateNetworkInfo()
D/ConnectivityService(  762): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  762): updateNetworkInfo()
D/ConnectivityService(  762): ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
D/ConnectivityService(  762): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
D/NetUtils(  762): android_net_utils_resetConnections in env=0xad6fee80 clazz=0x9b9eb98c iface=wlan0 mask=0x3
,D/ConnectivityManager.CallbackHandler( 2247): CM callback handler got msg 524290
,E/WifiStateMachine(  762): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1297): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1297): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1297): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1297): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1297): First Scan Start
,E/native  (  762): do suspend true
,E/Zygote  ( 7126): MountEmulatedStorage()
I/libpersona( 7126): KNOX_SDCARD checking this for 10038
E/Zygote  ( 7126): v2
I/libpersona( 7126): KNOX_SDCARD not a persona
,I/ActivityManager(  762): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.samsung.myplace.WIFINotificationHandler: pid=7126 uid=10038 gids={50038, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 7126): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SELinux ( 7126): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/SELinux ( 7126): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/wpa_supplicant( 1297): Scan requested (ret=0) - scan timeout 30 seconds
,D/WifiP2pService(  762): InactiveState{ what=143375 }
,D/WifiP2pService(  762): P2pEnabledState{ what=143375 }
,D/CommandListener(  283): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 1186): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1186): onWifiSignalChanged enabled=true enabledDesc:null
I/WifiTrafficPoller(  762): evaluateTrafficStatsPolling
D/StatusBar.NetworkController( 1186): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1186): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiNetworkAgent(  762): NetworkAgent: NetworkAgent channel lost
,D/SecContentProvider2(  762): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  762): mCursor = null
,D/TimaKeyStoreProvider( 7126): TimaSignature is unavailable
,D/ActivityThread( 7126): Added TimaKeyStore provider
D/SecContentProvider2(  762): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  762): mCursor = null
,D/ResourcesManager( 7126): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,W/ResourcesManager( 7126): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ConnectivityService(  762): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  762): calling update connectivity
D/ConnectivityService(  762):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/EntConnectivity(  762): Not allowed due to - mEnabled false
D/ConnectivityService(  762):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  762): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1186): CM callback handler got msg 524292
D/ConnectivityService(  762):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  762): sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 2247): CM callback handler got msg 524292
V/Nat464Xlat(  762): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  762): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  762): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1419): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CSLegacyTypeTracker(  762): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  762): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  762): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  762): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/NetworkStats(  762): updateIfacesLocked()
D/Tethering(  762): MasterInitialState.processMessage what=3
D/SmartBondingService(  762): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  762): getSBEnabled() enabled =false
D/SmartBondingService(  762): getSBEnabled() enabled =false
D/SmartBondingService(  762): getSBEnabled() enabled =false
V/NetworkStats(  762): performPollLocked(flags=0x1)
D/NtpTrustedTime(  762): currentTimeMillis() cache hit
D/NetworkStatsFactory(  762): UpdateStatsForKnox
D/StatusBar.NetworkController( 1186): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1186): updateDataNetType()
D/StatusBar.NetworkController( 1186): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1186): updateLTEICONDataNetType:0
D/ConnectivityService(  762): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  762): getNetworkEnabled : wifi : true mobile : true
V/NetworkStats(  762): performPollLocked() took 6ms
D/NtpTrustedTime(  762): currentTimeMillis() cache hit
,D/NtpTrustedTime(  762): currentTimeMillis() cache hit
,D/NtpTrustedTime(  762): currentTimeMillis() cache hit
D/NtpTrustedTime(  762): currentTimeMillis() cache hit
D/NtpTrustedTime(  762): currentTimeMillis() cache hit
D/NtpTrustedTime(  762): currentTimeMillis() cache hit
,V/NetworkStats(  762): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  762): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1186): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1186): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1186): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1186): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1186): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1186): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1186): applyOpen
D/StatusBar.NetworkController( 1186): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1186): applyOpen
D/StatusBar.NetworkController( 1186): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1186): applyOpen
D/StatusBar.NetworkController( 1186): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1186): applyOpen
,I/VlingoApplication( 7126): VlingoApplication appVersion ='11.2.2.0.37649', ro.csc.sales_code=XEO
,D/FileWriteThread_Telephony( 1419): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1419): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1419): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1419): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1419): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1419): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1419): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1419): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1419): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1419): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1419): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1419): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1419): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1419): FileWriteThread : threadType = 3
,E/BluetoothHeadset( 7126): BTStateChangeCB is registed
,E/BluetoothHeadset( 7126): BluetoothHeadset service is binded
,I/ActivityManager(  762): Killing 6150:com.samsung.android.app.FileShareServer/u0a88 (adj 15): bgCount ##41
,I/Hs20UtilService( 1312): Starting #6
,I/Hs20UtilService( 1312): Message received 5007
D/NearbySettings( 1312): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1312): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1312): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1312): MountReceiver.mPrefHandler - 7002
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6786): NETWORK_STATE_CHANGED_ACTION
,D/SettingsProvider(  762): name = driving_mode_on
,D/SettingsProvider(  762): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  762): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  762): selectionArgs: false
D/SettingsProvider(  762): selectionArgs: 10038
,D/SecContentProvider(  762): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  762): ret = -1
,D/BluetoothManager( 7126): [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.media.ACTION_SCO_AUDIO_STATE_UPDATED
,I/Hs20UtilService( 1312): Starting #7
,I/Hs20UtilService( 1312): Message received 5007
,D/NearbySettings( 1312): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1312): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  762): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1312): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1312): MountReceiver.mPrefHandler - 7002
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6786): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy(  762): updateDataUsageMap
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  762): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  762): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GpsLocationProvider(  762): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  762): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  762): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  762): getSBEnabled() enabled =false
D/SmartBondingService(  762): getSBEnabled() enabled =false
D/SmartBondingService(  762): getSBEnabled() enabled =false
,D/SmartBondingService(  762): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3650): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
I/NetworkMonitor( 5141): type=WIFI subType= reason=null isConnected=false
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PCWCLIENTTRACE_PushUtil( 6529): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6529): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 6529): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6529): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6529): noConnectivity : true
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3650): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7187): MountEmulatedStorage()
I/ActivityManager(  762): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7187 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 7187): v2
I/libpersona( 7187): KNOX_SDCARD checking this for 10004
,I/libpersona( 7187): KNOX_SDCARD not a persona
,I/SELinux ( 7187): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7187): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7187): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7187): TimaSignature is unavailable
,D/ActivityThread( 7187): Added TimaKeyStore provider
,D/ResourcesManager( 7187): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager(  762): Killing 6167:com.sec.knox.bridge/1000 (adj 15): bgCount ##41
,E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7209): MountEmulatedStorage()
E/Zygote  ( 7209): v2
I/libpersona( 7209): KNOX_SDCARD checking this for 1000
I/libpersona( 7209): KNOX_SDCARD not a persona
,I/ActivityManager(  762): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7209 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7209): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7209): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7209): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/SMD     (  289): DCD ON
,D/TimaKeyStoreProvider( 7209): TimaSignature is unavailable
,D/ActivityThread( 7209): Added TimaKeyStore provider
,D/ResourcesManager( 7209): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT( 7209): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7209): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT( 7209): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7209): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7209): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT( 7209): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  762): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7228 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 7228): MountEmulatedStorage()
E/Zygote  ( 7228): v2
I/libpersona( 7228): KNOX_SDCARD checking this for 10014
I/libpersona( 7228): KNOX_SDCARD not a persona
,I/SELinux ( 7228): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7228): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7228): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7228): TimaSignature is unavailable
,D/ActivityThread( 7228): Added TimaKeyStore provider
,D/ResourcesManager( 7228): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/wpa_supplicant( 1297): nl80211: Received scan results (7 BSSes)
I/wpa_supplicant( 1297): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1297): Trying to associate with C0.AA.4A (SSID='4E473730303567' freq=5220 MHz)
I/wpa_supplicant( 1297): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1297): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E473730303567
,I/ActivityManager(  762): Killing 6197:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
,D/SecContentProvider2(  762): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  762): mCursor = null
,I/FOTA_Client( 7228): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7228): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/wpa_supplicant( 1297): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1297): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E473730303567
,I/wpa_supplicant( 1297): Associated with C0.AA.4A
,D/SecContentProvider2(  762): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  762): mCursor = null
,I/FOTA_Client( 7228): [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
,I/wpa_supplicant( 1297): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1297): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.4A SSID=4E473730303567
,D/SecContentProvider2(  762): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  762): mCursor = null
,I/wpa_supplicant( 1297): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1297): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1297): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.4A SSID=4E473730303567
,I/wpa_supplicant( 1297): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1297): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1297): CTRL-EVENT-CONNECTED - Connection to C0.AA.4A completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 1297): Blacklist: Clear (temp) 
I/wpa_supplicant( 1297): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.4A SSID=4E473730303567
,E/Zygote  ( 7252): MountEmulatedStorage()
E/Zygote  ( 7252): v2
I/libpersona( 7252): KNOX_SDCARD checking this for 10023
I/libpersona( 7252): KNOX_SDCARD not a persona
,I/ActivityManager(  762): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7252 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  762): Killing 5459:com.sec.android.widgetapp.SPlannerAppWidget/u0a171 (adj 15): bgCount ##41
,D/WifiNative-HAL(  762): callSECApiVoid - ID [50]
,I/SELinux ( 7252): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7252): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7252): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  322): Explicit concurrent mark sweep GC freed 8759(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 305us total 14.360ms
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 312us total 9.963ms
,D/TimaKeyStoreProvider( 7252): TimaSignature is unavailable
D/ActivityThread( 7252): Added TimaKeyStore provider
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 283us total 10.363ms
,D/StatusBar.NetworkController( 1186): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1186): onWifiSignalChanged enabled=true enabledDesc:null
,D/ConnectivityService(  762): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,E/WifiConfigStore(  762): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  762): Got NetworkAgent Messenger
D/ConnectivityService(  762): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  762): updateNetworkInfo()
D/ConnectivityService(  762): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService(  762): NetworkAgent connected
,E/WifiConfigStore(  762): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  283): Setting iface cfg
,E/WifiStateMachine(  762): Start Dhcp Watchdog 2
,D/SecContentProvider2(  762): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  762): mCursor = null
,D/ResourcesManager( 7252): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,D/ConnectivityService(  762): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,I/KLMS-2.4.511: ( 7252): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.511: ( 7252): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449063193705
,I/KLMS-2.4.511: ( 7252): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.511: ( 7252): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.511: ( 7252): StateImplV2(): networkChangeListener().END
,E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7269): MountEmulatedStorage()
I/libpersona( 7269): KNOX_SDCARD checking this for 10036
E/Zygote  ( 7269): v2
I/libpersona( 7269): KNOX_SDCARD not a persona
,I/ActivityManager(  762): Start proc com.samsung.android.app.pinboard:tagService for broadcast com.samsung.android.app.pinboard/.service.TagReadyReceiver: pid=7269 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  762): Killing 4806:com.android.calendar/u0a172 (adj 15): bgCount ##41
,E/native  (  762): do suspend false
,D/SecContentProvider2(  762): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  762): mCursor = null
,D/WifiP2pService(  762): InactiveState{ what=143375 }
D/WifiP2pService(  762): P2pEnabledState{ what=143375 }
,I/SELinux ( 7269): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7269): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7269): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7269): TimaSignature is unavailable
,D/ActivityThread( 7269): Added TimaKeyStore provider
,D/ResourcesManager( 7269): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,W/ResourcesManager( 7269): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7269): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Minikin ( 7269): addFont failed to create font /system/fonts/SamsungSans-light.ttf
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  762): Killing 5949:com.android.providers.calendar/u0a51 (adj 15): bgCount ##41
,E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
,E/dhcpcd  ( 7288): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 7288): version 5.5.6 starting
,E/dhcpcd  ( 7288): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,E/Zygote  ( 7289): MountEmulatedStorage()
E/Zygote  ( 7289): v2
I/libpersona( 7289): KNOX_SDCARD checking this for 10042
I/libpersona( 7289): KNOX_SDCARD not a persona
,I/ActivityManager(  762): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7289 uid=10042 gids={50042, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7289): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7289): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7289): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7289): TimaSignature is unavailable
,D/ActivityThread( 7289): Added TimaKeyStore provider
,I/dhcpcd  ( 7288): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7288): wlan0: sendmsg: Cannot assign requested address
,I/dhcpcd  ( 7288): if(wlan0) info get Success. (MAC : C0.AA.4A)
I/dhcpcd  ( 7288): bssid match
I/dhcpcd  ( 7288): wlan0: rebinding lease of 192.168.1.128
,D/ResourcesManager( 7289): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT( 7289): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5075): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 6627): [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
,I/SA      ( 6627): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 6627): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6627): [SLFUCHKMGR] constructor called
,I/SA      ( 6627): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6627): [OR] == isSIMCardReady false ==
,I/SA      ( 6627): [SCU] == networkStateCheck == false
I/SA      ( 6627): [OR] onReceive END
,E/SPPClientService( 5075): [[SystemStateMonitorService]] No Active Internet
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7318): MountEmulatedStorage()
E/Zygote  ( 7318): v2
I/libpersona( 7318): KNOX_SDCARD checking this for 10074
I/libpersona( 7318): KNOX_SDCARD not a persona
,I/ActivityManager(  762): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=7318 uid=10074 gids={50074, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 7318): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/ActivityManager(  762): Killing 5591:com.sec.android.app.music:service/u0a49 (adj 15): bgCount ##41
,I/SELinux ( 7318): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7318): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7318): TimaSignature is unavailable
,D/ActivityThread( 7318): Added TimaKeyStore provider
,D/ResourcesManager( 7318): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/jxcore-log( 7028): Got Device Bluetooth address: E0:DB:10:1F:C9:5E
I/jxcore-log( 7028): 
,I/jxcore-log( 7028): my name is : samsung-SM-N9005_PT6839
I/jxcore-log( 7028): 
,I/sCloudBackupApp( 7318): sCloudBackupApp Version Info : 3.13.7.KK_APP
,I/SCloudBackupReceiver( 7318): Other Intent
,E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/jxcore-log( 7028): attempting to connect to test coordinator
I/jxcore-log( 7028): 
,I/jxcore-log( 7028): check test folder
I/jxcore-log( 7028): 
,I/jxcore-log( 7028): found test : ./testFindPeers.js
I/jxcore-log( 7028): 
,I/ActivityManager(  762): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7337 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  762): Killing 5662:com.sec.android.app.myfiles/u0a56 (adj 15): bgCount ##41
,E/Zygote  ( 7337): MountEmulatedStorage()
I/libpersona( 7337): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7337): v2
I/libpersona( 7337): KNOX_SDCARD not a persona
,I/jxcore-log( 7028): found test : ./testReConnect.js
I/jxcore-log( 7028): 
,I/jxcore-log( 7028): found test : ./testSendData.js
I/jxcore-log( 7028): 
,I/SELinux ( 7337): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7337): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7337): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/jxcore-log( 7028): Test app app.js loaded
I/jxcore-log( 7028): 
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,I/chromium( 7028): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/TimaKeyStoreProvider( 7337): TimaSignature is unavailable
,D/ActivityThread( 7337): Added TimaKeyStore provider
,D/ResourcesManager( 7337): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7337): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro( 7337): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7337): premStatus:2
,I/KnoxUsageLogPro( 7337): isEulaShown : false
I/KnoxUsageLogPro( 7337): KnoxUsageReceiver onReceive : not Processible, just return
,I/chromium( 7028): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7352): MountEmulatedStorage()
,E/Zygote  ( 7352): v2
I/libpersona( 7352): KNOX_SDCARD checking this for 10104
I/libpersona( 7352): KNOX_SDCARD not a persona
,I/SELinux ( 7352): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7352): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7352): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  762): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7352 uid=10104 gids={50104, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  762): Killing 6296:flipboard.app/u0a125 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7352): TimaSignature is unavailable
,D/ActivityThread( 7352): Added TimaKeyStore provider
,D/ResourcesManager( 7352): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7368): MountEmulatedStorage()
,E/Zygote  ( 7368): v2
I/libpersona( 7368): KNOX_SDCARD checking this for 10146
I/libpersona( 7368): KNOX_SDCARD not a persona
,I/SELinux ( 7368): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7368): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7368): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  762): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7368 uid=10146 gids={50146, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  762): Killing 5850:com.google.android.talk/u0a131 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7368): TimaSignature is unavailable
,D/ActivityThread( 7368): Added TimaKeyStore provider
,D/ResourcesManager( 7368): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk,
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7368): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7368): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7368): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7368): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory( 7368): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,D/ResourcesManager( 7368): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7368): Loading: webviewchromium
,I/LibraryLoader( 7368): Time to load native libraries: 5 ms (timestamps 105-110)
,I/LibraryLoader( 7368): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7368): Binding Chromium to main looper Looper (main, tid 1) {22dfc76a}
,I/LibraryLoader( 7368): Expected native library version number "",actual native library version number ""
,I/chromium( 7368): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7368): Initializing chromium process, renderers=0
,W/art     ( 7368): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7368): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7368): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=42 off=46780 len=2953
,I/chromium( 7368): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:41 off:229536 len:643667
,W/AudioManagerAndroid( 7368): Requires BLUETOOTH permission
,I/Adreno-EGL( 7368): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 7368): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7368): Build Date: 11/19/14 Wed
I/Adreno-EGL( 7368): Local Branch: mybranch5813579
I/Adreno-EGL( 7368): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 7368): Local Patches: NONE
I/Adreno-EGL( 7368): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,I/NSApplication( 7368): Starting up...
,I/ActivityManager(  762): Killing 5762:com.google.android.gm/u0a128 (adj 15): bgCount ##41
,E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7422): MountEmulatedStorage()
E/Zygote  ( 7422): v2
I/libpersona( 7422): KNOX_SDCARD checking this for 10158
I/libpersona( 7422): KNOX_SDCARD not a persona
,I/ActivityManager(  762): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7422 uid=10158 gids={50158, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,I/SELinux ( 7422): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7422): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7422): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/dhcpcd  ( 7288): wlan0: acknowledged 192.168.1.128 from 192.168.1.1
,D/TimaKeyStoreProvider( 7422): TimaSignature is unavailable
,D/ActivityThread( 7422): Added TimaKeyStore provider
,I/dhcpcd  ( 7288): wlan0: leased 192.168.1.128 for 86400 seconds
,D/ResourcesManager( 7422): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,D/ConnectivityService(  762): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,W/ResourcesManager( 7422): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7422): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7422): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 7422): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7422): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7422): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  762): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7444 uid=10186 gids={50186, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,E/Zygote  ( 7444): MountEmulatedStorage()
E/Zygote  ( 7444): v2
I/libpersona( 7444): KNOX_SDCARD checking this for 10186
I/libpersona( 7444): KNOX_SDCARD not a persona
,I/ActivityManager(  762): Killing 6484:com.google.android.partnersetup/u0a19 (adj 15): bgCount ##41
I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/SELinux ( 7444): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7444): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7444): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7444): TimaSignature is unavailable
,D/ActivityThread( 7444): Added TimaKeyStore provider
,D/ResourcesManager( 7444): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7444): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7444): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7444): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 7444): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7444): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService(  762): exchangeData() failure , invalid userId
,D/RCPManagerService(  762): exchangeData() failure , invalid userId
,D/RCPManagerService(  762): exchangeData() failure , invalid userId
,E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService(  762): exchangeData() failure , invalid userId
,E/Zygote  ( 7482): MountEmulatedStorage()
E/Zygote  ( 7482): v2
I/libpersona( 7482): KNOX_SDCARD checking this for 10092
I/libpersona( 7482): KNOX_SDCARD not a persona
,I/ActivityManager(  762): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7482 uid=10092 gids={50092, 9997} abi=armeabi-v7a
,E/native  (  762): do suspend true
,I/SELinux ( 7482): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,D/WifiP2pService(  762): InactiveState{ what=143375 }
,D/WifiP2pService(  762): P2pEnabledState{ what=143375 }
I/SELinux ( 7482): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,D/RCPManagerService(  762): exchangeData() failure , invalid userId
E/SELinux ( 7482): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  762): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,E/WifiStateMachine(  762): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG7005g"WPA_PSK
E/WifiStateMachine(  762): VerifyingLinkState enter
,D/StatusBar.NetworkController( 1186): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1186): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiNative-HAL(  762): callSECApiInt - ID [210]
,E/ConnectivityService(  762): updateNetworkInfo()
,D/WifiWatchdogStateMachine(  762): updateDnsLinkProperty: enter
,D/ConnectivityService(  762): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService(  762): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine.DnsPinger(  762): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 1186): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1186): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiWatchdogStateMachine.DnsResolver(  762): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker(  762): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  762): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/RCPManagerService(  762): exchangeData() failure , invalid userId
,E/WifiStateMachine(  762): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
I/WifiTrafficPoller(  762): evaluateTrafficStatsPolling
D/StatusBar.NetworkController( 1186): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1186): onWifiSignalChanged enabled=true enabledDesc:null
,I/WifiTrafficPoller(  762): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  762): mBoosterFLAG : 0
I/WifiTrafficPoller(  762): current booster mode : FullMode
D/WifiNative-HAL(  762): callSECApiVoid - ID [212]
D/StatusBar.NetworkController( 1186): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1186): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
D/StatusBar.NetworkController( 1186): refreshSignalCluster - setNWBoosterIndicators(false)
D/TimaKeyStoreProvider( 7482): TimaSignature is unavailable
D/ActivityThread( 7482): Added TimaKeyStore provider
D/StatusBar.NetworkController( 1186): applyOpen
E/WifiStateMachine(  762): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/StatusBar.NetworkController( 1186): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1186): applyOpen
D/StatusBar.NetworkController( 1186): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1186): applyOpen
D/StatusBar.NetworkController( 1186): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1186): applyOpen
,D/ConnectivityService(  762): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService(  762): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService(  762): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService(  762): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  762): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  762): updateSourceRoutes : add src route for:192.168.1.128
V/        (  283): QcRouteController
,I/ActivityManager(  762): Killing 6412:com.android.defcontainer/u0a7 (adj 15): bgCount ##41
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7108): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 7108): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7108): StateMachine : Current State = 1
,D/SecurityLogAgent( 7108): StateMachine : Changed Current State = 1
,V/        (  283): QcRouteController
,V/        (  283): QcRouteController
,V/        (  283): QcRouteController
,V/        (  283): QcRouteController
,V/        (  283): QcRouteController
,V/        (  283): QcRouteController
,V/        (  283): QcRouteController
,D/ConnectivityService(  762): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService(  762): LTETest block dns file not exists
,I/art     (  762): Explicit concurrent mark sweep GC freed 96507(5MB) AllocSpace objects, 27(432KB) LOS objects, 17% free, 37MB/45MB, paused 1.871ms total 112.064ms
,I/ActivityManager(  762): Killing 6502:com.samsung.groupcast/u0a20 (adj 15): bgCount ##41
,V/Nat464Xlat(  762): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/ConnectivityService(  762): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  762): calling update connectivity
D/ConnectivityService(  762): ignoring duplicate network state non-change. WIFI, state = CONNECTING
D/EntConnectivity(  762): Not allowed due to - mEnabled false
E/ConnectivityService(  762): updateNetworkInfo()
,D/ConnectivityService(  762): ignoring duplicate network state non-change. WIFI, state = CONNECTING
E/ConnectivityService(  762): updateNetworkInfo()
D/ConnectivityService(  762): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  762): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  762): calling update connectivity
,D/ConnectivityService(  762): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Checking http://clients3.google.com/generate_204 on "NG7005g"
D/ConnectivityService(  762):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  762):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  762):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/System.out(  762): (HTTPLog)-Static: isSBSettingEnabled false
D/ConnectivityService(  762):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  762): currentScore = 0, newScore = 60
D/ConnectivityService(  762):    accepting network in place of null
D/ConnectivityService(  762): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1419): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker(  762): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  762): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7482): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/BadgeProvider( 7482): onCreate
,D/BadgeProvider( 7482): DatabaseHelper
,E/Zygote  ( 7522): MountEmulatedStorage()
I/libpersona( 7522): KNOX_SDCARD checking this for 10200
E/Zygote  ( 7522): v2
I/libpersona( 7522): KNOX_SDCARD not a persona
,I/ActivityManager(  762): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7522 uid=10200 gids={50200, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7522): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7522): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7522): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/System.out(  762): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/ConnectivityService(  762): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,W/ActivityManager(  762): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
D/ConnectivityService(  762): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,V/NetworkStats(  762): updateIfacesLocked()
D/NtpTrustedTime(  762): currentTimeMillis() cache hit
V/NetworkStats(  762): performPollLocked(flags=0x1)
D/ConnectivityService(  762): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  762): calling update connectivity
D/ConnectivityService(  762):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  762):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  762): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  762):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkStatsFactory(  762): UpdateStatsForKnox
D/Tethering(  762): MasterInitialState.processMessage what=3
D/ConnectivityService(  762): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  762): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/EntConnectivity(  762): Not allowed due to - mEnabled false
D/SmartBondingService(  762): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityManager.CallbackHandler( 1186): CM callback handler got msg 524290
D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  762): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  762): getSBEnabled() enabled =false
D/SmartBondingService(  762): getSBEnabled() enabled =false
D/SmartBondingService(  762): getSBEnabled() enabled =false
,D/StatusBar.NetworkController( 1186): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1186): updateDataNetType()
D/StatusBar.NetworkController( 1186): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1186): updateLTEICONDataNetType:0
,V/NetworkStats(  762): performPollLocked() took 3ms
D/NtpTrustedTime(  762): currentTimeMillis() cache hit
,D/ConnectivityManager.CallbackHandler( 2247): CM callback handler got msg 524290
,D/SmartBondingService(  762): getNetworkEnabled : wifi : true mobile : true
,D/StatusBar.NetworkController( 1186): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1186): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1186): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/NtpTrustedTime(  762): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1186): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1186): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
D/StatusBar.NetworkController( 1186): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1186): applyOpen
D/NtpTrustedTime(  762): currentTimeMillis() cache hit
D/NtpTrustedTime(  762): currentTimeMillis() cache hit
D/NtpTrustedTime(  762): currentTimeMillis() cache hit
D/NtpTrustedTime(  762): currentTimeMillis() cache hit
D/NtpTrustedTime(  762): currentTimeMillis() cache hit
V/NetworkStats(  762): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/StatusBar.NetworkController( 1186): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1186): applyOpen
D/StatusBar.NetworkController( 1186): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1186): applyOpen
D/StatusBar.NetworkController( 1186): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1186): applyOpen
,D/TimaKeyStoreProvider( 7522): TimaSignature is unavailable
,D/ActivityThread( 7522): Added TimaKeyStore provider
,D/BadgeProvider( 7482): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/ResourcesManager( 7522): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,D/BadgeProvider( 7482): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7482): sendNotify, [notify] : null
D/BadgeProvider( 7482): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7482): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7482): update, [UpdateCount] : 1
,D/Launcher.Model( 1448): reloadBadges entered.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 02 Dec 2015 13:33:15 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449063195932], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449063195902]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Validated
D/ConnectivityService(  762): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  762): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  762):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  762):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  762):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  762): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  762): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  762): calling update connectivity
D/ConnectivityService(  762):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  762):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  762): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  762):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  762): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 2247): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1186): CM callback handler got msg 524290
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1186): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1186): updateDataNetType()
D/StatusBar.NetworkController( 1186): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1186): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1186): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1186): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1186): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1186): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1186): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
,I/ActivityManager(  762): Killing 6067:sstream.app/u0a25 (adj 15): bgCount ##41
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2247): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2247): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1665): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1665): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 5422): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5422): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 5422): exit::IDLE
D/InitializeManagerStateMachine( 5422): entry::NETWORK_CHECK
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 5422): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5422): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5422): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5422): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5422): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5422): entry::SUCCESS
D/hcjo    ( 5422): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5422): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5422): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/ConnectivityService(  762): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 5422): exit::SUCCESS
D/InitializeManagerStateMachine( 5422): entry::IDLE
,I/Hs20UtilService( 1312): Starting #8
,I/Hs20UtilService( 1312): Message received 5007
,V/GLSActivity( 1665): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/NearbySettings( 1312): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1312): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  762): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1312): MountReceiver.onReceive - Keep current state
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1665): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SignOutReceiver( 6786): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 1312): Starting #9
,D/NearbySettings( 1312): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/Hs20UtilService( 1312): Message received 5007
I/NearbySettings( 1312): MountReceiver.onReceive - Keep current state
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6786): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 1312): Starting #10
,I/Hs20UtilService( 1312): Message received 5007
,D/NearbySettings( 1312): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1312): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/ConnectivityService(  762): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1312): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1312): MountReceiver.onReceive - Keep current state
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  289): DCD ON
,E/SignOutReceiver( 6786): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 1312): Starting #11
,I/Hs20UtilService( 1312): Message received 5007
,D/NearbySettings( 1312): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1312): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine(  762): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6786): NETWORK_STATE_CHANGED_ACTION
,I/SurfaceFlinger(  254): id=16 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService(  762): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=762
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GpsLocationProvider(  762): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  762): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  762): SmartBondingReceiver: wifi is connected
,D/SmartBondingService(  762): SmartBondingReceiver: wifi ap is not changed
D/ConnectivityService(  762): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  762): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  762): getSBEnabled() enabled =false
D/SmartBondingService(  762): getSBEnabled() enabled =false
,D/SmartBondingService(  762): getSBEnabled() enabled =false
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1884): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,W/ContextImpl( 1884): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/SmartBondingService(  762): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3650): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/NetworkMonitor( 5141): type=WIFI subType= reason=null isConnected=true
,I/DBG_DM  ( 3650): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PCWCLIENTTRACE_PushUtil( 6529): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6529): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6529): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6529): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7209): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7209): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/FOTA_Client( 7228): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7228): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7228): [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.511: ( 7252): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.511: ( 7252): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449063196695
,I/KLMS-2.4.511: ( 7252): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.511: ( 7252): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.511: ( 7252): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.511: ( 7252): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.511: ( 7252): StateImplV2(): networkChangeListener().END
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SO_AGENT( 7289): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5075): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,D/ConnectivityService(  762): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/SA      ( 6627): [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
,I/SA      ( 6627): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,I/SA      ( 6627): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6627): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6627): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6627): [SCU] == networkStateCheck == true
,I/SA      ( 6627): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 6627): isChinaCountryCode : false
I/SA      ( 6627): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6627): [OR] == networkStateCheck true ==
,I/SA      ( 6627): [OR] GetMyCountryZoneTask
,I/SA      ( 6627): [OR] onReceive END
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6627): [SRS] prepareGetMyCountryZone
,I/SCloudBackupReceiver( 7318): Other Intent
,I/KnoxUsageLogPro( 7337): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 7337): premStatus:2
,I/SA      ( 6627): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/KnoxUsageLogPro( 7337): isEulaShown : false
I/KnoxUsageLogPro( 7337): KnoxUsageReceiver onReceive : not Processible, just return
I/SA      ( 6627): [SSP] query invoked
,I/SA      ( 6627): [TPMU] GetMccFromDB : null
I/SA      ( 6627): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6627): [TPM] isNoProxy(default) : true
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/File    ( 6627): fail readDirectory() errno=2
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 7422): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7422): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7422): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  762): exchangeData() failure , invalid userId
,D/RCPManagerService(  762): exchangeData() failure , invalid userId
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7108): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7108): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7108): StateMachine : Current State = 1
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7108): StateMachine : Changed Current State = 1
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2247): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2247): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 5422): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5422): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 5422): exit::IDLE
D/InitializeManagerStateMachine( 5422): entry::NETWORK_CHECK
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 5422): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5422): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5422): entry::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 5422): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5422): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5422): entry::SUCCESS
D/hcjo    ( 5422): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5422): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5422): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/ConnectivityService(  762): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 5422): exit::SUCCESS
D/InitializeManagerStateMachine( 5422): entry::IDLE
,V/GLSActivity( 1665): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1665): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,I/SA      ( 6627): [RC New] Execute method=[GET] start
,I/SA      ( 6627): [RC New] Security=[true]
,I/System.out( 6627): Thread-1090(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6627): Thread-1090(ApacheHTTPLog):isShipBuild true
,I/System.out( 6627): Thread-1090(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/dhcpcd  ( 7288): wlan0: sending IPv6 Router Solicitation
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 4
,E/dhcpcd  ( 7288): wlan0: sendmsg: Cannot assign requested address
,I/SA      ( 6627): [RC New] [v2liruge] api execute + 874
,I/SA      ( 6627): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6627): AsyncTask #1 calls detatch()
,I/SA      ( 6627): [TPMU] getNetworkMcc : 
,I/SA      ( 6627): [SCU] saveMccToPreferece Start
,I/SA      ( 6627): [SCU] RegionMCC : 260
I/SA      ( 6627): [SSP] query invoked
,I/SA      ( 6627): [TPMU] GetMccFromDB : null
,I/SA      ( 6627): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6627): [SCU] saveMccToPreferece End
,I/SA      ( 6627): [RC New] executeRequest [v2liruge] end. 970
,I/SA      ( 6627): [RC New] Execute end
,I/SA      ( 6627): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 6627): [OR] GetMyCountryZoneTask Success
,E/WifiStateMachine(  762): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,E/SMD     (  289): DCD ON
,D/ConnectivityService(  762): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
,D/ConnectivityService(  762): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService(  762): identical MTU - not setting
,D/ConnectivityService(  762): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  762): updateSourceRoutes : add src route for:fe80::ea50:8bff:fede:28a3
,V/        (  283): QcRouteController
,D/SmartBondingService(  762): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  762): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  762): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  762): getSBEnabled() enabled =false
D/SmartBondingService(  762): getSBEnabled() enabled =false
D/SmartBondingService(  762): getSBEnabled() enabled =false
,V/        (  283): QcRouteController
,W/NetworkManagementService(  762): route cmd failed: 
W/NetworkManagementService(  762): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '74 route replace src v6 wlan0 fe80::ea50:8bff:fede:28a3 2 ::' failed with '400 74 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  762): '
W/NetworkManagementService(  762): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService(  762): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService(  762): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService(  762): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService(  762): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  762): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5625)
W/NetworkManagementService(  762): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5437)
W/NetworkManagementService(  762): 	at com.android.server.ConnectivityService.access$2300(ConnectivityService.java:229)
W/NetworkManagementService(  762): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2382)
W/NetworkManagementService(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  762): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/Nat464Xlat(  762): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  762): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  762): calling update connectivity
D/ConnectivityService(  762):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  762):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  762): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1186): CM callback handler got msg 524295
,D/ConnectivityService(  762):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  762): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  762): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  762): calling update connectivity
,D/ConnectivityService(  762):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  762):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  762): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 2247): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 1186): CM callback handler got msg 524295
,D/ConnectivityService(  762):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  762): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 2247): CM callback handler got msg 524295
,I/jxcore-log( 7028): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 7028): 
,I/SurfaceFlinger(  254): id=16 Removed Uoast (8/9)
,I/SurfaceFlinger(  254): id=16 Removed Uoast (-2/9)
,D/PowerManagerService(  762): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 762) eventTime = 164773
,D/PowerManagerService(  762): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=762 (0x0)
,D/PowerManagerService(  762): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=762, ws=WorkSource{10067}) (elapsedTime=3509)
,I/GAV4    ( 7368): Thread[GAThread,5,main]: No campaign data found.
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Watchdog(  762): !@Sync 5
,V/AlarmManager(  762): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1186): handleTimeUpdate
,D/KeyguardEffectViewController( 1186): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1186): *** don't update sliding image ***
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1186): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1186): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6529): mConnectivityHandler : connected
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 6529): [hasSamungAccount] - No Samsung Account
D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CSTORAGE( 6529): ================================================
I/CSTORAGE( 6529):  CSTORAGE_SKM_LIB v1.0.6
I/CSTORAGE( 6529): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 6529): [GetString-S]
E/art     ( 6529): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
W/PCWCLIENTTRACE_SecurePreferencesJNI( 6529): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6529): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 6529): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6529): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6529): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 6529): [ensureRegistration] - No Samsung account
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:n  (  762): SIOP:: AP = 340, PST = 335, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,I/dhcpcd  ( 7288): wlan0: sending IPv6 Router Solicitation
,I/ClearcutLoggerApiImpl( 1665): disconnect managed GoogleApiClient
,E/SMD     (  289): DCD ON
,D/PreloadUpdateManagerStateMachine( 5422): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5422): exit::IDLE
D/PreloadUpdateManagerStateMachine( 5422): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5422): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5422): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5422): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5422): entry::IDLE
,I/dhcpcd  ( 7288): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 7288): wlan0: no IPv6 Routers available
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/PreloadUpdateManagerStateMachine( 5422): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5422): exit::IDLE
D/PreloadUpdateManagerStateMachine( 5422): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5422): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/PreloadUpdateManagerStateMachine( 5422): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5422): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5422): entry::IDLE
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 320, PST = 327, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  762): stay LED for fully charged
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  762): [PWL] Off : 75s ago
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/SSRM:n  (  762): SIOP:: AP = 310, PST = 322, CUR = 450
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,E/Watchdog(  762): !@Sync 6
,D/SSRM:n  (  762): SIOP:: AP = 310, PST = 319, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,V/AlarmManager(  762): waitForAlarm result :4
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,I/ClearcutLoggerApiImpl( 1893): disconnect managed GoogleApiClient
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,V/AlarmManager(  762): waitForAlarm result :8
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 310, PST = 318, CUR = 450
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  762): [PWL] Off : 105s ago
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Atfwd_Sendcmd(  332): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  332): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 300, PST = 316, CUR = 450
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  762): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/Watchdog(  762): !@Sync 7
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/SSRM:n  (  762): SIOP:: AP = 300, PST = 314, CUR = 450
,E/SMD     (  289): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 1
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  762): stay LED for fully charged
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/SSRM:n  (  762): SIOP:: AP = 300, PST = 313, CUR = 450
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 2
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  762): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  762): [PWL] Off : 140s ago
,D/SSRM:n  (  762): SIOP:: AP = 300, PST = 312, CUR = 450
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  289): DCD ON
,E/Watchdog(  762): !@Sync 8
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 300, PST = 309, CUR = 450
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  762): stay LED for fully charged
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 300, PST = 305, CUR = 450
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  762): stay LED for fully charged
,E/SMD     (  289): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 300, PST = 303, CUR = 450
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  762): stay LED for fully charged
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,E/Watchdog(  762): !@Sync 9
,I/PowerManagerService(  762): [PWL] Off : 180s ago
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 300, PST = 302, CUR = 450
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/SSRM:n  (  762): SIOP:: AP = 300, PST = 301, CUR = 450
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 5
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  762): stay LED for fully charged
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 299, CUR = 450
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/TimaService(  762): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  762): TimaServiceHandler.handleMessage what =1
,D/TimaService(  762): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  762): initializing...
,I/TLC_TIMA_PKM_initialize(  762): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  762): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  762): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  762): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  762): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication(  762): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication(  762): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: (  762): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  762): App is not loaded in QSEE
,D/QSEECOMAPI: (  762): Loaded image: APP id = 3
,I/TZ: qc_tlc_communication(  762): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  762): Trustlet response is completed
,E/SMD     (  289): DCD ON
,E/Watchdog(  762): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel(  762): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  762): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  762): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  762): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 300, PST = 299, CUR = 450
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,I/Atfwd_Sendcmd(  332): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  332): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 300, PST = 299, CUR = 450
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  762): [PWL] Off : 225s ago
,E/SMD     (  289): DCD ON
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,V/AlarmManager(  762): waitForAlarm result :4
,E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/Zygote  ( 7650): MountEmulatedStorage()
,E/Zygote  ( 7650): v2
I/libpersona( 7650): KNOX_SDCARD checking this for 10096
I/libpersona( 7650): KNOX_SDCARD not a persona
,I/ActivityManager(  762): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=7650 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1186): handleTimeUpdate
,I/art     (  322): Explicit concurrent mark sweep GC freed 8728(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 536us total 38.282ms
,D/KeyguardEffectViewController( 1186): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1186): *** don't update sliding image ***
I/SELinux ( 7650): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 404us total 17.909ms
I/SELinux ( 7650): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7650): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 485us total 33.757ms
,D/TimaKeyStoreProvider( 7650): TimaSignature is unavailable
D/ActivityThread( 7650): Added TimaKeyStore provider
,D/DateView( 1186): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1186): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ResourcesManager( 7650): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,I/ActivityManager(  762): Killing 6115:com.samsung.android.app.galaxyfinder/u0a39 (adj 15): bgCount ##41
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 300, PST = 299, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/Watchdog(  762): !@Sync 11
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 298, CUR = 450
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 297, CUR = 450
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 296, CUR = 450
,E/SMD     (  289): DCD ON
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  762): stay LED for fully charged
D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  762): !@Sync 12
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 295, CUR = 450
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  762): [PWL] Off : 275s ago
,E/SMD     (  289): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,V/AlarmManager(  762): waitForAlarm result :8
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 294, CUR = 450
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  762): stay LED for fully charged
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 293, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  762): stay LED for fully charged
,E/Watchdog(  762): !@Sync 13
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 293, CUR = 450
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  762): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 292, CUR = 450
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  762): stay LED for fully charged
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 291, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
I/MotionRecognitionService(  762): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  762): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  762): !@Sync 14
,I/PowerManagerService(  762): [PWL] Off : 330s ago
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,I/Atfwd_Sendcmd(  332): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  332): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  762): stay LED for fully charged
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  762): stay LED for fully charged
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  762): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/Watchdog(  762): !@Sync 15
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/bootchecker(  325): bootchecker wake up!!
,E/SMD     (  289): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  762): !@Sync 16
,I/PowerManagerService(  762): [PWL] Off : 390s ago
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  762): stay LED for fully charged
,E/SMD     (  289): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 4
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  762): stay LED for fully charged
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/Watchdog(  762): !@Sync 17
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
I/MotionRecognitionService(  762): setPowerConnected  = true
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  762): stay LED for fully charged
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  762): stay LED for fully charged
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/Watchdog(  762): !@Sync 18
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  762): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,I/Atfwd_Sendcmd(  332): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  332): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  762): [PWL] Off : 455s ago
,E/SMD     (  289): DCD ON
,V/AlarmManager(  762): waitForAlarm result :8
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  762): stay LED for fully charged
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0,
D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  762): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,I/Atfwd_Daemon(  332): Stop the daemon....
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/Watchdog(  762): !@Sync 19
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,D/BatteryService(  762): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
D/BatteryService(  762): stay LED for fully charged
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService(  762): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  762): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  762): TimaServiceHandler.handleMessage what =1
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/Watchdog(  762): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel(  762): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  762): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  762): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  762): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
I/MotionRecognitionService(  762): Plugged
I/MotionRecognitionService(  762): setPowerConnected  = true
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  762): stay LED for fully charged
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,I/PowerManagerService(  762): [PWL] Off : 525s ago
,E/SMD     (  289): DCD ON
,W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,I/ActivityManager(  762): Killing 4594:com.sec.android.app.shealth/u0a40 (adj 15): bgCount ##41
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  762): stay LED for fully charged
,I/MotionRecognitionService(  762): Plugged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/Watchdog(  762): !@Sync 21
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  762): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/Watchdog(  762): !@Sync 22
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  762): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,E/Watchdog(  762): !@Sync 23
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,I/PowerManagerService(  762): [PWL] Off : 600s ago
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  762): Plugged
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,E/Watchdog(  762): !@Sync 24
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
I/MotionRecognitionService(  762): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  762): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,E/Watchdog(  762): !@Sync 25
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 289, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 288, CUR = 450
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  762): [PWL] Off : 680s ago
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 287, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,E/Watchdog(  762): !@Sync 26
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 286, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 285, CUR = 450
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 284, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,E/Watchdog(  762): !@Sync 27
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 283, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 282, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,E/Watchdog(  762): !@Sync 28
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  762): Plugged
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,I/PowerManagerService(  762): [PWL] Off : 765s ago
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  762): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,E/Watchdog(  762): !@Sync 29
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
I/MotionRecognitionService(  762): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  762): stay LED for fully charged
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/TimaService(  762): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  762): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  762): TimaServiceHandler.handleMessage what =1
,E/SMD     (  289): DCD ON
,E/Watchdog(  762): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel(  762): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  762): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  762): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  762): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
I/MotionRecognitionService(  762): Plugged
I/MotionRecognitionService(  762): setPowerConnected  = true
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  762): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 281, CUR = 450
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,V/AlarmManager(  762): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1186): handleTimeUpdate
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/KeyguardEffectViewController( 1186): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1186): *** don't update sliding image ***
,D/LightsService(  762): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  762): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager(  762): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,D/DateView( 1186): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1186): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  762): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LightsService(  762): [SvcLED]  onSensorChanged::light value = 11
,E/LightSensor(  762): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  762): unregisterListener ::   
,D/lights  (  762): led_pattern : 5 +
,D/lights  (  762): led_pattern : 5 -
,D/LightsService(  762): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,E/Watchdog(  762): !@Sync 31
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  762): stay LED for fully charged
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 281, CUR = 450
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 281, CUR = 450
,I/PowerManagerService(  762): [PWL] Off : 855s ago
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,E/Watchdog(  762): !@Sync 32
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,V/AlarmManager(  762): waitForAlarm result :8
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  762): stay LED for fully charged
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,E/Watchdog(  762): !@Sync 33
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
I/MotionRecognitionService(  762): Plugged
I/MotionRecognitionService(  762): setPowerConnected  = true
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  762): stay LED for fully charged
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,E/Watchdog(  762): !@Sync 34
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  762): [PWL] Off : 950s ago
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  762): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,E/Watchdog(  762): !@Sync 35
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
I/MotionRecognitionService(  762): Plugged
I/MotionRecognitionService(  762): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  762): stay LED for fully charged
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
D/BatteryService(  762): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
I/MotionRecognitionService(  762): Plugged
I/MotionRecognitionService(  762): setPowerConnected  = true
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  762): stay LED for fully charged
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,E/Watchdog(  762): !@Sync 36
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
I/MotionRecognitionService(  762): Plugged
I/MotionRecognitionService(  762): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  762): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/Watchdog(  762): !@Sync 37
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  762): stay LED for fully charged
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/BatteryService(  762): stay LED for fully charged
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/Watchdog(  762): !@Sync 38
,I/PowerManagerService(  762): [PWL] Off : 1050s ago
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/Watchdog(  762): !@Sync 39
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
I/MotionRecognitionService(  762): Plugged
I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3125): Disconnected process message: 10
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,D/TimaService(  762): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  762): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  762): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService(  762): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  762): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  762): Updating Usage Statistics in DB @ 1449064248753
,I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
,W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  762): ::getAppControlDB: Exception to create DB
W/System.err(  762): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  762): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  762): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage(  762): Done Updating Usage Statistics in DB @ 1449064248904
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/Watchdog(  762): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel(  762): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  762): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  762): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  762): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate,
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 290, PST = 281, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  762): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 281, CUR = 450
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/Watchdog(  762): !@Sync 41
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  762): Plugged
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  762): Plugged
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,I/PowerManagerService(  762): [PWL] Off : 1155s ago
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  762): Plugged
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/Watchdog(  762): !@Sync 42
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  762): stay LED for fully charged
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/Watchdog(  762): !@Sync 43
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
I/MotionRecognitionService(  762): Plugged
I/MotionRecognitionService(  762): setPowerConnected  = true
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  762): stay LED for fully charged
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
I/MotionRecognitionService(  762): Plugged
I/MotionRecognitionService(  762): setPowerConnected  = true
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  762): stay LED for fully charged
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/Watchdog(  762): !@Sync 44
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/Watchdog(  762): !@Sync 45
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,I/PowerManagerService(  762): [PWL] Off : 1265s ago
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/Watchdog(  762): !@Sync 46
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  762): Plugged
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/Watchdog(  762): !@Sync 47
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/Watchdog(  762): !@Sync 48
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  762): Plugged
I/MotionRecognitionService(  762): setPowerConnected  = true
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/Watchdog(  762): !@Sync 49
,I/PowerManagerService(  762): [PWL] Off : 1380s ago
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): stay LED for fully charged
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  762): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/TimaService(  762): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  762): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  762): TimaServiceHandler.handleMessage what =1
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/Watchdog(  762): !@Sync 50
,I/TLC_TIMA_PKM_measure_kernel(  762): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  762): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  762): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  762): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): stay LED for fully charged
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,V/AlarmManager(  762): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1186): handleTimeUpdate
,D/KeyguardEffectViewController( 1186): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1186): *** don't update sliding image ***
,D/LightsService(  762): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  762): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager(  762): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,D/DateView( 1186): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1186): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/LightsService(  762): [SvcLED]  onSensorChanged::light value = 8
,E/LightSensor(  762): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  762): unregisterListener ::   
,D/LightsService(  762): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/Watchdog(  762): !@Sync 51
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  762): stay LED for fully charged
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
I/MotionRecognitionService(  762): Plugged
I/MotionRecognitionService(  762): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  762): stay LED for fully charged
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/Watchdog(  762): !@Sync 52
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  762): stay LED for fully charged
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
I/MotionRecognitionService(  762): Plugged
I/MotionRecognitionService(  762): setPowerConnected  = true
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,V/AlarmManager(  762): waitForAlarm result :8
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
D/BatteryService(  762): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/Watchdog(  762): !@Sync 53
,I/PowerManagerService(  762): [PWL] Off : 1500s ago
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,E/SMD     (  289): DCD ON
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  762): !@Sync 54
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  762): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  762): !@Sync 55
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  762): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  762): !@Sync 56
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  762): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  762): !@Sync 57
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService(  762): [PWL] Off : 1625s ago
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  762): !@Sync 58
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  762): Plugged
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  762): Plugged
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  762): !@Sync 59
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/NetworkStatsFactory(  762): UpdateStatsForKnox
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,D/TimaService(  762): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  762): TimaServiceHandler.handleMessage what =1
,D/TimaService(  762): TIMA: checkEvent, operation: 50000 subject: 10000
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  762): !@Sync 60
,I/TLC_TIMA_PKM_measure_kernel(  762): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  762): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  762): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  762): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  762): !@Sync 61
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,I/PowerManagerService(  762): [PWL] Off : 1755s ago
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  762): !@Sync 62
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/Watchdog(  762): !@Sync 63
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  762): Plugged
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  762): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  762): Plugged
I/MotionRecognitionService(  762): setPowerConnected  = true
,D/BatteryService(  762): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  762): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  762): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  762): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  762): Plugged
,I/MotionRecognitionService(  762): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  762): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3125): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3125): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/Watchdog(  762): !@Sync 64
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,D/SSRM:n  (  762): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/jxcore-log( 7028): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7028): 
,E/SMD     (  289): DCD ON
,D/BatteryService(  762): !@BatteryListener : batteryPropertiesChanged!
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 7801): 
D/AndroidRuntime( 7801): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7801): CheckJNI is OFF
D/AndroidRuntime( 7801): readGMSProperty: start
D/AndroidRuntime( 7801): readGMSProperty: already setted!!
D/AndroidRuntime( 7801): readGMSProperty: end
D/AndroidRuntime( 7801): addProductProperty: start
E/AffinityControl( 7801): AffinityControl: registerfunction enter
D/AndroidRuntime( 7801): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService(  762): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager(  762): START PACKAGE DELETE: observer{576375758}
D/PackageManager(  762): pkg{<packageName>}
D/PackageManager(  762): user{0}
D/PackageManager(  762): caller{2000}
D/PackageManager(  762): flags{3}
D/PersonaManagerService(  762): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  762): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  762): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  762): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  762): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  762): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  762): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  762): getApplicationUninstallationEnabled
D/ApplicationPolicy(  762): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  762): !@killApplicatoin: 10262, uninstall pkg
I/ActivityManager(  762): Force stopping com.test.thalitest appid=10262 user=-1: uninstall pkg
I/ActivityManager(  762): Killing 7028:com.test.thalitest/u0a262 (adj 0): stop com.test.thalitest
W/PackageSettings(  762): Skipping PackageSetting{3a082c91 com.example.hello/10256} due to missing metadata
I/WindowState(  762): WIN DEATH: Window{321e5505 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  254): id=15 Removed NainActivit (5/8)
I/SurfaceFlinger(  254): id=15 Removed NainActivit (-2/8)
I/SurfaceFlinger(  254): id=15 Removed NainActivit (-2/8)
D/PointerIcon(  762): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  762): setMouseCustomIcon IconType is same.101
D/PointerIcon(  762): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  762): setHoveringSpenCustomIcon IconType is same.1
E/SMD     (  289): DCD ON
I/ActivityManager(  762): Killing 4440:com.sec.chaton/u0a102 (adj 11): empty for 1802s
I/ActivityManager(  762): Killing 7337:com.sec.knox.bridge/1000 (adj 11): empty for 1802s
I/ActivityManager(  762): Killing 7318:com.samsung.android.scloud.backup/u0a74 (adj 11): empty for 1802s
I/ActivityManager(  762): Killing 6627:com.osp.app.signin/u0a50 (adj 11): empty for 1802s
I/ActivityManager(  762): Killing 6561:com.policydm/1000 (adj 11): empty for 1802s
I/ActivityManager(  762): Killing 7289:com.sec.android.soagent/u0a42 (adj 11): empty for 1802s
I/ActivityManager(  762): Killing 7126:com.vlingo.midas/u0a38 (adj 11): empty for 1802s
I/ActivityManager(  762): Killing 7269:com.samsung.android.app.pinboard:tagService/u0a36 (adj 11): empty for 1802s
I/ActivityManager(  762): Killing 7252:com.samsung.klmsagent/u0a23 (adj 11): empty for 1802s
I/ActivityManager(  762): Killing 7228:com.sec.android.fotaclient/u0a14 (adj 11): empty for 1802s
I/ActivityManager(  762): Killing 7209:com.sec.android.diagmonagent/1000 (adj 13): empty for 1803s
I/ActivityManager(  762): Killing 7187:com.sec.android.cloudagent/u0a4 (adj 13): empty for 1803s
I/ActivityManager(  762): Killing 6529:com.sec.pcw.device/1000 (adj 13): empty for 1803s
I/ActivityManager(  762): Killing 6786:com.samsung.android.snote/u0a168 (adj 13): empty for 1803s
I/ActivityManager(  762): Killing 7482:com.sec.android.provider.badge/u0a92 (adj 13): empty for 1803s
I/ActivityManager(  762): Killing 6215:com.android.vending/u0a33 (adj 13): empty for 1869s
I/ActivityManager(  762): Killing 6683:com.google.android.apps.docs/u0a112 (adj 13): empty for 1873s
I/ActivityManager(  762): Killing 6609:com.google.android.gms:car/u0a15 (adj 13): empty for 1884s
I/ActivityManager(  762): Killing 6821:com.sec.kidsplat.installer/u0a189 (adj 13): empty for 1884s
I/ActivityManager(  762): Killing 6803:com.samsung.android.snote:provider/u0a168 (adj 15): empty for 1885s
I/ActivityManager(  762): Killing 6182:com.sec.android.app.controlpanel/u0a134 (adj 15): empty for 1885s
I/ActivityManager(  762): Killing 6766:com.samsung.helphub/1000 (adj 15): empty for 1885s
I/ActivityManager(  762): Killing 6750:com.samsung.android.app.watchmanagerstub/u0a126 (adj 15): empty for 1885s
I/ActivityManager(  762): Killing 6721:com.samsung.android.app.filterinstaller/1000 (adj 15): empty for 1885s
I/ActivityManager(  762): Killing 5835:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1887s
I/ActivityManager(  762): Killing 6658:com.sec.android.app.soundalive/u0a64 (adj 15): empty for 1887s
E/Watchdog(  762): !@Sync 65
I/ActivityManager(  762): Killing 5715:com.android.mms/u0a55 (adj 15): empty for 1887s
I/ActivityManager(  762): Killing 5609:com.sec.android.gallery3d/u0a53 (adj 15): empty for 1887s
I/ActivityManager(  762): Killing 6581:com.samsung.android.sdk.samsunglink/u0a48 (adj 15): empty for 1887s
I/ActivityManager(  762):   Force finishing activity ActivityRecord{1502b387 u0 com.test.thalitest/.MainActivity t4}
W/ActivityManager(  762): mDVFSHelper.acquire()
I/ProcessStatsService(  762): Prepared write state in 9ms
W/ActivityManager(  762): Spurious death for ProcessRecord{3a15baef 7028:com.test.thalitest/u0a262}, curProc for 7028: null
W/libprocessgroup(  762): failed to open /acct/uid_10033/pid_6215/cgroup.procs: No such file or directory
W/libprocessgroup(  762): failed to open /acct/uid_10102/pid_4440/cgroup.procs: No such file or directory
W/libprocessgroup(  762): failed to open /acct/uid_1000/pid_7337/cgroup.procs: No such file or directory
W/libprocessgroup(  762): failed to open /acct/uid_10074/pid_7318/cgroup.procs: No such file or directory
W/libprocessgroup(  762): failed to open /acct/uid_10050/pid_6627/cgroup.procs: No such file or directory
W/libprocessgroup(  762): failed to open /acct/uid_1000/pid_6561/cgroup.procs: No such file or directory
W/libprocessgroup(  762): failed to open /acct/uid_10042/pid_7289/cgroup.procs: No such file or directory
W/libprocessgroup(  762): failed to open /acct/uid_10038/pid_7126/cgroup.procs: No such file or directory
W/libprocessgroup(  762): failed to open /acct/uid_10036/pid_7269/cgroup.procs: No such file or directory
W/libprocessgroup(  762): failed to open /acct/uid_10023/pid_7252/cgroup.procs: No such file or directory
W/libprocessgroup(  762): failed to open /acct/uid_10014/pid_7228/cgroup.procs: No such file or directory
W/libprocessgroup(  762): failed to open /acct/uid_1000/pid_7209/cgroup.procs: No such file or directory
W/libprocessgroup(  762): failed to open /acct/uid_10004/pid_7187/cgroup.procs: No such file or directory
W/libprocessgroup(  762): failed to open /acct/uid_1000/pid_6529/cgroup.procs: No such file or directory
W/libprocessgroup(  762): failed to open /acct/uid_10168/pid_6786/cgroup.procs: No such file or directory
W/libprocessgroup(  762): failed to open /acct/uid_10092/pid_7482/cgroup.procs: No such file or directory
W/libprocessgroup(  762): failed to open /acct/uid_10015/pid_6609/cgroup.procs: No such file or directory
D/CountryDetector(  762): No listener is left
W/libprocessgroup(  762): failed to open /acct/uid_10189/pid_6821/cgroup.procs: No such file or directory
W/libprocessgroup(  762): failed to open /acct/uid_10168/pid_6803/cgroup.procs: No such file or directory
W/libprocessgroup(  762): failed to open /acct/uid_10134/pid_6182/cgroup.procs: No such file or directory
W/libprocessgroup(  762): failed to open /acct/uid_1000/pid_6766/cgroup.procs: No such file or directory
W/libprocessgroup(  762): failed to open /acct/uid_10126/pid_6750/cgroup.procs: No such file or directory
W/libprocessgroup(  762): failed to open /acct/uid_1000/pid_6721/cgroup.procs: No such file or directory
W/libprocessgroup(  762): failed to open /acct/uid_1000/pid_5835/cgroup.procs: No such file or directory
W/libprocessgroup(  762): failed to open /acct/uid_10064/pid_6658/cgroup.procs: No such file or directory
W/libprocessgroup(  762): failed to open /acct/uid_10055/pid_5715/cgroup.procs: No such file or directory
W/libprocessgroup(  762): failed to open /acct/uid_10112/pid_6683/cgroup.procs: No such file or directory
W/libprocessgroup(  762): failed to open /acct/uid_10053/pid_5609/cgroup.procs: No such file or directory
W/libprocessgroup(  762): failed to open /acct/uid_10048/pid_6581/cgroup.procs: No such file or directory
I/ProcessStatsService(  762): Prepared write state in 21ms
I/DBG_DM  ( 3650): [com.wssyncmldm.ui.XUIInstallConfirmActivity(477/onResume)] 
I/ActivityManager(  762): Force stopping com.test.thalitest appid=10262 user=0: pkg removed
I/DBG_DM  ( 3650): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 13
D/ResourcesManager(  762): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
I/DBG_DM  ( 3650): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
I/InputReader(  762): Reconfiguring input devices.  changes=0x00000010
E/SamsungIME( 1851): mOCRHelper is null
D/SSRM:n  (  762): SIOP:: AP = 290, PST = 281, CUR = 450
I/DBG_DM  ( 3650): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
I/DBG_DM  ( 3650): [com.wssyncmldm.ui.XUIInstallConfirmActivity(487/onResume)] Postpone Count : 13
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
W/GeofencerStateMachine( 1893): Ignoring removeGeofence because network location is disabled.
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
D/ConnectivityService(  762): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager( 1448): creating new AssetManager and set to /system/priv-app/StoryAlbumWidget/StoryAlbumWidget.apk
I/DBG_DM  ( 3650): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
W/ResourcesManager( 1448): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1448): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
I/ActivityManager(  762): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7840 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
E/Zygote  ( 7840): MountEmulatedStorage()
E/Zygote  ( 7840): v2
I/libpersona( 7840): KNOX_SDCARD checking this for 10023
I/libpersona( 7840): KNOX_SDCARD not a persona
I/DBG_DM  ( 3650): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
I/art     ( 4485): Explicit concurrent mark sweep GC freed 34425(1917KB) AllocSpace objects, 9(144KB) LOS objects, 40% free, 15MB/26MB, paused 567us total 85.284ms
I/art     ( 1580): Explicit concurrent mark sweep GC freed 34907(2MB) AllocSpace objects, 0(0B) LOS objects, 25% free, 19MB/25MB, paused 413us total 116.640ms
I/SELinux ( 7840): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7840): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7840): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/DBG_DM  ( 3650): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
D/ResourcesManager( 1448): creating new AssetManager and set to /system/app/AccuweatherPhone2013_H_LMR/AccuweatherPhone2013_H_LMR.apk
W/ResourcesManager( 1448): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1448): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1448): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
D/ResourcesManager( 1448): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
W/ResourcesManager( 1448): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1448): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
D/SecContentProvider2(  762): uri = 14 selection = getSealedState
D/SecContentProvider2(  762): mCursor = null
D/ApplicationPolicy(  762): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy(  762): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
I/DBG_DM  ( 3650): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 13
I/DBG_DM  ( 3650): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
I/art     (  762): Explicit concurrent mark sweep GC freed 20069(1762KB) AllocSpace objects, 7(112KB) LOS objects, 17% free, 37MB/45MB, paused 1.731ms total 170.476ms
D/ResourcesManager(  762): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
I/art     (  762): WaitForGcToComplete blocked for 93.258ms for cause Explicit
I/DBG_DM  ( 3650): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 3650): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false
I/DBG_DM  ( 3650): [IIlllIlIIlIllIlllIll(376/llIIllllIIlllIIIIlll)] 
I/DBG_DM  ( 3650): [IIlllIlIIlIllIlllIll(397/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
D/ActivityManager(  762): post active user change for 0
D/KnoxTimeoutHandler(  762): postActiveUserChange for user 0
I/DBG_DM  ( 3650): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
D/SecContentProvider2(  762): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  762): mCursor = null
D/TimaKeyStoreProvider( 7840): TimaSignature is unavailable
D/ActivityThread( 7840): Added TimaKeyStore provider
I/SurfaceFlinger(  254): id=17 createSurf (1080x1920),2 flag=404, YUIInstallC
D/StatusBarManagerService(  762): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/ResourcesManager(  762): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ResourcesManager(  762): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
D/PointerIcon(  762): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  762): setMouseCustomIcon IconType is same.101
D/PointerIcon(  762): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  762): setHoveringSpenCustomIcon IconType is same.1
V/ActivityThread( 3650): updateVisibility : ActivityRecord{3dd825a8 token=android.os.BinderProxy@ba20aa9 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
D/InputMethodManagerService(  762): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/StatusBarManagerService(  762): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
W/InputMethodManagerService(  762): Got RemoteException sending setActive(false) notification to pid 7028 uid 10262
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/ContextImpl(  762): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
I/Timeline( 3650): Timeline: Activity_idle id: android.os.BinderProxy@ba20aa9 time:1966772
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/RegisteredServicesCache( 1412): empty dynamic service
D/ResourcesManager( 7840): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
D/ResourcesManager(  762): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
W/ActivityManager(  762): mDVFSHelper.release()
D/ResourcesManager(  762): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
I/Timeline(  762): Timeline: Activity_windows_visible id: ActivityRecord{50c081d u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t2} time:1966790
D/ResourcesManager(  762): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/ResourcesManager(  762): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
D/ResourcesManager(  762): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager(  762): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(  762): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/Drive/Drive.apk
I/KLMS-2.4.511: ( 7840): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
I/KLMS-2.4.511: ( 7840): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1449065001723
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/Music2/Music2.apk
I/KLMS-2.4.511: ( 7840): MainReciver(): PACKAGE_REMOVED
I/KLMS-2.4.511: ( 7840): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/RCPManagerService(  762): PackageReceiver onReceive()
I/HarmonyEASService(  762): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy(  762): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  762): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  762): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  762): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  762): uID is 10262
V/EnterpriseBillingPolicy(  762): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  762): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  762): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  762): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  762): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  762): getBillingProfileForVpnEngine - start - com.test.thalitest
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
V/EnterpriseBillingPolicyStorage(  762): getBillingProfileForVpnEngine - end - null
E/Zygote  ( 7858): MountEmulatedStorage()
E/Zygote  ( 7858): v2
I/libpersona( 7858): KNOX_SDCARD checking this for 10116
I/libpersona( 7858): KNOX_SDCARD not a persona
I/ActivityManager(  762): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7858 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  762): Killing 7352:com.android.chrome/u0a104 (adj 15): empty for 1804s
I/art     (  762): Explicit concurrent mark sweep GC freed 11954(618KB) AllocSpace objects, 1(16KB) LOS objects, 17% free, 37MB/45MB, paused 4.698ms total 257.826ms
I/SELinux ( 7858): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7858): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7858): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7858): TimaSignature is unavailable
D/ActivityThread( 7858): Added TimaKeyStore provider
W/libprocessgroup(  762): failed to open /acct/uid_10104/pid_7352/cgroup.procs: No such file or directory
D/KnoxTimeoutHandler(  762): handleActiveUserChange for user 0
D/ResourcesManager( 7858): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
I/ProcessStatsService(  762): Pruning old procstats: /data/system/procstats/state-2015-12-01-17-53-06.bin
D/TaskPersister(  762): removeObsoleteFile: deleting file=4_task.xml
D/TaskPersister(  762): removeObsoleteFile: deleting file=2_task.xml
D/ResourcesManager(  762): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
D/elm:14491( 7858): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14491( 7858): ELMEngine.ELMEngine( context ).
D/elm:14491( 7858): MDMBridge.setEnterpriseBridge()
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/talkback/talkback.apk
D/elm:14491( 7858): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  762): checkUser: useridlist=null, currentuser=0
D/EnterpriseDeviceManagerService(  762): Package has changed for user 0
D/PackageManager(  762): delete codoeFile: 
D/EnterpriseDeviceManagerService(  762): Admin package name: com.google.android.gms
D/elm:14491( 7858): ElmAgentService : onCreate()
I/AASAUninstall(  762):  com.test.thalitest not target!
D/elm:14491( 7858): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/PackageManager(  762): result of delete: 1{576375758}
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
D/elm:14491( 7858): MainReceiver.listeningToPackageRemoved()
D/elm:14491( 7858): MDMBridge.getInstance()
D/elm:14491( 7858): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14491( 7858): MDMBridge.getAllLicenseInfoFromSDK()
D/AndroidRuntime( 7801): Shutting down VM
D/ResourcesManager(  762): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
W/Resources(  762): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  762): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
W/Resources(  762): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/Books/Books.apk
E/Zygote  ( 7875): MountEmulatedStorage()
E/Zygote  ( 7875): v2
I/libpersona( 7875): KNOX_SDCARD checking this for 10021
I/libpersona( 7875): KNOX_SDCARD not a persona
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
W/Resources(  762): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/Videos/Videos.apk
I/ActivityManager(  762): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=7875 uid=10021 gids={50021, 9997} abi=armeabi-v7a
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/elm:14491( 7858): ElmAgentService : onDestroy().
I/SELinux ( 7875): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/ResourcesManager(  762): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
I/ActivityManager(  762): Killing 7368:com.google.android.apps.magazines/u0a146 (adj 15): empty for 1805s
I/SELinux ( 7875): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
D/StatusBar( 1186): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
E/SELinux ( 7875): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/PersonaManager( 1186): isKioskContainerExistOnDevice
D/PersonaManager( 1186): isKioskContainerExistOnDevice
D/PanelView( 1186): There is/are notification(s) 
D/PanelView( 1186): There is/are notification(s) 
W/Resources(  762): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  762): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
W/Resources(  762): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  762): creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
D/TimaKeyStoreProvider( 7875): TimaSignature is unavailable
D/ActivityThread( 7875): Added TimaKeyStore provider
W/Resources(  762): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  762): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/Resources(  762): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
W/Resources(  762): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/Maps/Maps.apk
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
D/ResourcesManager(  762): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk

```
