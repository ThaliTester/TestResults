#### Test 50650278e989a4f_thali05_samsung-SM-N9005 Logs


```
--------- beginning of main
E/SMD     (  289): DCD ON
--------- beginning of system
W/ContextImpl(  776): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/AndroidRuntime( 7075): 
D/AndroidRuntime( 7075): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7075): CheckJNI is OFF
D/AndroidRuntime( 7075): readGMSProperty: start
D/AndroidRuntime( 7075): readGMSProperty: already setted!!
D/AndroidRuntime( 7075): readGMSProperty: end
D/AndroidRuntime( 7075): addProductProperty: start
E/AffinityControl( 7075): AffinityControl: registerfunction enter
D/AndroidRuntime( 7075): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  776): inState():  stateMachine is null !!
I/PersonaManagerService(  776): PersonaId don't exist
I/ActivityManager(  776): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  776): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  776): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  776): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager(  776): mDVFSHelper.acquire()
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  776): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7090 uid=10294 gids={50294, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 7090): MountEmulatedStorage()
E/Zygote  ( 7090): v2
I/libpersona( 7090): KNOX_SDCARD checking this for 10294
I/libpersona( 7090): KNOX_SDCARD not a persona
I/SELinux ( 7090): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7090): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7090): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime( 7075): Shutting down VM
D/PointerIcon(  776): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  776): setMouseCustomIcon IconType is same.101
D/PointerIcon(  776): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  776): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider( 7090): TimaSignature is unavailable
D/ActivityThread( 7090): Added TimaKeyStore provider
I/SurfaceFlinger(  254): id=11 Removed YUIInstallC (5/8)
I/SurfaceFlinger(  254): id=11 Removed YUIInstallC (-2/8)
V/ActivityThread( 3580): updateVisibility : ActivityRecord{cb738a token=android.os.BinderProxy@23c745a3 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
D/ConnectivityService(  776): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager( 7090): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,I/WebViewFactory( 7090): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,D/ResourcesManager( 7090): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7090): Loading: webviewchromium
,I/LibraryLoader( 7090): Time to load native libraries: 6 ms (timestamps 4179-4185)
,I/LibraryLoader( 7090): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7090): Binding Chromium to main looper Looper (main, tid 1) {1948b6a1}
,I/LibraryLoader( 7090): Expected native library version number "",actual native library version number ""
,I/chromium( 7090): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7090): Initializing chromium process, renderers=0
,W/art     ( 7090): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7090): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7090): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46780 len=2953
I/chromium( 7090): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229536 len:643667
,I/Adreno-EGL( 7090): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 7090): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7090): Build Date: 11/19/14 Wed
I/Adreno-EGL( 7090): Local Branch: mybranch5813579
I/Adreno-EGL( 7090): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 7090): Local Patches: NONE
I/Adreno-EGL( 7090): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,W/chromium( 7090): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7090): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/ActivityManager(  776): Activity pause timeout for ActivityRecord{227253a3 u0 com.test.thalitest/.MainActivity t4}
,W/art     ( 7090): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7090): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 7090): CordovaWebView is running on device made by: samsung
,W/art     ( 7090): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 7090): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity( 7090): performCreate Call secproduct feature valuefalse
D/Activity( 7090): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer( 7090): Render dirty regions requested: true
,D/Atlas   ( 7090): Validating map...
,D/ActivityManager(  776): post active user change for 0
,D/KnoxTimeoutHandler(  776): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  776): handleActiveUserChange for user 0
,V/ActivityThread( 7090): updateVisibility : ActivityRecord{10912776 token=android.os.BinderProxy@20fbba38 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/SurfaceFlinger(  254): id=14 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService(  776): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  776): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/OpenGLRenderer( 7090): Initialized EGL, version 1.4
,D/PointerIcon(  776): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  776): setMouseCustomIcon IconType is same.101
D/PointerIcon(  776): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  776): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer( 7090): HWUI protection enabled for context ,  &this =0xa1753060 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 7090): Enabling debug mode 0
,D/InputMethodManagerService(  776): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false,
,W/ContextImpl(  776): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager(  776): mDVFSHelper.release()
,I/Timeline(  776): Timeline: Activity_windows_visible id: ActivityRecord{227253a3 u0 com.test.thalitest/.MainActivity t4} time:154863
,W/IInputConnectionWrapper( 7090): showStatusIcon on inactive InputConnection
,I/Timeline( 7090): Timeline: Activity_idle id: android.os.BinderProxy@20fbba38 time:154866
,D/JsMessageQueue( 7090): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 7090): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7090): 
,D/jxcore_app_log( 7090): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1358876416
,D/JX-Cordova( 7090): jxcore cordova android initializing
,E/SMD     (  289): DCD ON
,W/jxcore-log( 7090): Initializing JXcore engine
,W/jxcore-log( 7090): JXcore engine is ready
,W/jxcore-log( 7090): Starting JXcore engine
,E/auditd  ( 1874): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  776): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  776): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
D/SecurityLogAgent:SEDenialService(  776): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,E/Zygote  ( 7159): MountEmulatedStorage()
I/libpersona( 7159): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7159): v2
I/libpersona( 7159): KNOX_SDCARD not a persona
,I/ActivityManager(  776): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7159 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/art     (  320): Explicit concurrent mark sweep GC freed 8752(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 297us total 26.346ms
,I/SELinux ( 7159): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7159): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7159): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 263us total 13.185ms
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 268us total 9.488ms
,D/TimaKeyStoreProvider( 7159): TimaSignature is unavailable
,D/ActivityThread( 7159): Added TimaKeyStore provider
,D/ResourcesManager( 7159): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 7159):  SeDenialReceiver : Intent Received : android.intent.action.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7159):  SeDenialReceiver : File path = null
,I/ActivityManager(  776): Killing 4591:com.android.providers.calendar/u0a51 (adj 15): bgCount ##41
,W/jxcore-log( 7090): Platform android
W/jxcore-log( 7090): 
W/jxcore-log( 7090): Process ARCH arm
W/jxcore-log( 7090): 
,I/jxcore-log( 7090): JXcore Cordova bridge is ready!
I/jxcore-log( 7090): 
W/jxcore-log( 7090): JXcore engine is started
,D/SSRM:n  (  776): SIOP:: AP = 330, PST = 330, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/MotionRecognitionService(  776): Plugged
I/MotionRecognitionService(  776): setPowerConnected  = true
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
D/HeadsetStateMachine( 3126): Disconnected process message: 10
D/BatteryService(  776): stay LED for fully charged
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log( 7090): Toggling radios to true
I/jxcore-log( 7090): 
,D/BluetoothAdapter( 7090): enable()
,D/BluetoothAdapter( 7090): enable(): BT is already enabled..!
,I/WifiManager( 7090): packageName : com.test.thalitest
,D/SecContentProvider(  776): uri = 18 selection = isWifiEnabled
D/SecContentProvider2(  776): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  776): mCursor = null
,D/WifiService(  776): setWifiEnabled: true pid=7090, uid=10294
W/ActivityManager(  776): Permission Denial: getCurrentUser() from pid=7090, uid=10294 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  776): Failed getting userId using ActivityManagerNative
W/WifiService(  776): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7090, uid=10294 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  776): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23057)
W/WifiService(  776): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2181)
W/WifiService(  776): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2169)
W/WifiService(  776): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  776): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider(  776): name = wifi_on
,I/WifiService(  776): disconnect: pid=7090, uid=10294
,I/jxcore-log( 7090): Radios toggled
I/jxcore-log( 7090): 
,I/jxcore-log( 7090): Got Device Bluetooth address: E0:DB:10:1F:C9:5E
I/jxcore-log( 7090): 
,I/jxcore-log( 7090): Perf Test app loaded loaded
I/jxcore-log( 7090): 
,I/wpa_supplicant( 1276): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7090): check test folder
I/jxcore-log( 7090): 
,I/jxcore-log( 7090): found test : ./testFindPeers.js
I/jxcore-log( 7090): 
,I/wpa_supplicant( 1276): CTRL-EVENT-DISCONNECTED bssid=C0.AA.4A reason=3 locally_generated=1
I/jxcore-log( 7090): found test : ./testSendData.js
I/jxcore-log( 7090): 
,I/wpa_supplicant( 1276): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1276): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.4A SSID=4E473730303567
I/wpa_supplicant( 1276): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  776): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1276): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1276): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1276): Disconnected - do not scan
I/wpa_supplicant( 1276): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiConfigStore(  776): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  776): do suspend true
,D/WifiP2pService(  776): InactiveState{ what=143375 }
,D/WifiP2pService(  776): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1186): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1186): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
,D/CommandListener(  284): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1892): Read error: ssl=0x9a3a8e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1892): SSL shutdown failed: ssl=0x9a3a8e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10015
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  776): ValidatedState{ when=-1ms what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  776): DefaultState{ when=-1ms what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  776): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  776): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  776): Checking http://clients3.google.com/generate_204 on "NG7005g"
D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out(  776): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid (  776): Tagging socket 372 with tag ffffffff00000000{4294967295,0} uid 10015, pid: 776, getuid(): 1000
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out(  776): (HTTPLog)-Static: isSBSettingEnabled false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  776): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  776): Validated
D/ConnectivityService(  776): Validated NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  776): rematching NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService(  776):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  776):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  776):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  776): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,D/ConnectivityService(  776): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  776): calling update connectivity
D/ConnectivityService(  776):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  776):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  776): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  776):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1186): CM callback handler got msg 524290
D/ConnectivityService(  776): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 2228): CM callback handler got msg 524290
,E/ConnectivityService(  776): updateNetworkInfo()
D/ConnectivityService(  776): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService(  776): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,D/NetUtils(  776): android_net_utils_resetConnections in env=0xa93ac320 clazz=0x9bcd398c iface=wlan0 mask=0x3
,E/WifiConfigStore(  776): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,I/WifiTrafficPoller(  776): evaluateTrafficStatsPolling
,E/WifiStateMachine(  776): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1276): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1276): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1276): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1276): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1276): First Scan Start
,D/StatusBar.NetworkController( 1186): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1186): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1186): refreshSignalCluster - setNWBoosterIndicators(false)
,E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/native  (  776): do suspend true
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
D/StatusBar.NetworkController( 1186): applyOpen
D/StatusBar.NetworkController( 1186): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1186): applyOpen
D/StatusBar.NetworkController( 1186): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1186): applyOpen
D/StatusBar.NetworkController( 1186): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1186): applyOpen
,E/Zygote  ( 7190): MountEmulatedStorage()
E/Zygote  ( 7190): v2
I/libpersona( 7190): KNOX_SDCARD checking this for 10038
I/libpersona( 7190): KNOX_SDCARD not a persona
,I/chromium( 7090): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/ActivityManager(  776): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.samsung.myplace.WIFINotificationHandler: pid=7190 uid=10038 gids={50038, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 7190): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/wpa_supplicant( 1276): Scan requested (ret=0) - scan timeout 30 seconds
,I/SELinux ( 7190): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7190): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/chromium( 7090): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/WifiP2pService(  776): InactiveState{ what=143375 }
,D/WifiP2pService(  776): P2pEnabledState{ what=143375 }
,D/CommandListener(  284): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 1186): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1186): onWifiSignalChanged enabled=true enabledDesc:null
,I/WifiTrafficPoller(  776): evaluateTrafficStatsPolling
,D/WifiNetworkAgent(  776): NetworkAgent: NetworkAgent channel lost
,D/StatusBar.NetworkController( 1186): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1186): onWifiSignalChanged enabled=true enabledDesc:null
,D/SecContentProvider2(  776): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  776): mCursor = null
,D/SecContentProvider2(  776): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  776): mCursor = null
,D/TimaKeyStoreProvider( 7190): TimaSignature is unavailable
,D/ActivityThread( 7190): Added TimaKeyStore provider
,D/ResourcesManager( 7190): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,W/ResourcesManager( 7190): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ConnectivityService(  776): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  776): calling update connectivity
D/ConnectivityService(  776):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/EntConnectivity(  776): Not allowed due to - mEnabled false
D/ConnectivityService(  776):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  776): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  776):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  776): sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/Nat464Xlat(  776): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  776): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  776): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 2228): CM callback handler got msg 524292
,D/CSLegacyTypeTracker(  776): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  776): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  776): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  776): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  776): Disconnected - quitting
D/ConnectivityService(  776): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityManager.CallbackHandler( 1186): CM callback handler got msg 524292
,D/TelephonyNetworkFactory( 1415): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  776): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,E/ConnectivityService(  776): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/SmartBondingService(  776): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NtpTrustedTime(  776): currentTimeMillis() cache hit
V/NetworkStats(  776): updateIfacesLocked()
V/NetworkStats(  776): performPollLocked(flags=0x1)
,D/SmartBondingService(  776): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/NetworkStatsFactory(  776): UpdateStatsForKnox
D/SmartBondingService(  776): getSBEnabled() enabled =false
D/SmartBondingService(  776): getSBEnabled() enabled =false
D/SmartBondingService(  776): getSBEnabled() enabled =false
D/ConnectivityService(  776): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  776): MasterInitialState.processMessage what=3
,V/NetworkStats(  776): performPollLocked() took 3ms
D/NtpTrustedTime(  776): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1186): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1186): updateDataNetType()
D/StatusBar.NetworkController( 1186): NoService, mRoamingIconId = 0
,E/StatusBar.NetworkController( 1186): updateLTEICONDataNetType:0
,D/NtpTrustedTime(  776): currentTimeMillis() cache hit
,D/SmartBondingService(  776): getNetworkEnabled : wifi : true mobile : true
,D/NtpTrustedTime(  776): currentTimeMillis() cache hit,
V/NetworkStats(  776): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  776): currentTimeMillis() cache hit
D/NtpTrustedTime(  776): currentTimeMillis() cache hit
,D/NtpTrustedTime(  776): currentTimeMillis() cache hit
D/NtpTrustedTime(  776): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1186): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1186): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1186): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
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
,D/FileWriteThread_Telephony( 1415): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1415): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1415): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1415): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1415): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1415): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1415): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1415): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1415): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1415): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1415): FileWriteThread : threadType = 3
I/VlingoApplication( 7190): VlingoApplication appVersion ='11.2.2.0.37649', ro.csc.sales_code=XEO
,D/FileWriteThread_Telephony( 1415): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1415): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1415): FileWriteThread : threadType = 3
,E/BluetoothHeadset( 7190): BTStateChangeCB is registed
,E/BluetoothHeadset( 7190): BluetoothHeadset service is binded
,I/ActivityManager(  776): Killing 6063:com.samsung.android.app.FileShareServer/u0a88 (adj 15): bgCount ##41
,D/SettingsProvider(  776): name = driving_mode_on
D/SettingsProvider(  776): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  776): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  776): selectionArgs: false
D/SettingsProvider(  776): selectionArgs: 10038
D/SecContentProvider(  776): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  776): ret = -1
,D/BluetoothManager( 7190): [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.media.ACTION_SCO_AUDIO_STATE_UPDATED
,I/Hs20UtilService( 1328): Starting #6
,I/Hs20UtilService( 1328): Message received 5007
,D/NearbySettings( 1328): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1328): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  776): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1328): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  776): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1328): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1328): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1328): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1328): MountReceiver.mPrefHandler - 7002
,D/ConnectivityService(  776): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6834): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 1328): Starting #7
,I/Hs20UtilService( 1328): Message received 5007
D/NearbySettings( 1328): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1328): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  776): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1328): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  776): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1328): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1328): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1328): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1328): MountReceiver.mPrefHandler - 7002
,D/ConnectivityService(  776): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6834): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  776): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  776): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  776): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GpsLocationProvider(  776): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/ApplicationPolicy(  776): updateDataUsageMap
,D/SmartBondingService(  776): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  776): getSBEnabled() enabled =false
,D/SmartBondingService(  776): getSBEnabled() enabled =false
D/SmartBondingService(  776): getSBEnabled() enabled =false
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/SmartBondingService(  776): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  776): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3580): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,D/ConnectivityService(  776): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  776): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5758): type=WIFI subType= reason=null isConnected=false
,I/PCWCLIENTTRACE_PushUtil( 6552): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6552): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6552): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6552): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 3580): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
I/PCWCLIENTTRACE_SYSTEMReceiver( 6552): noConnectivity : true
,E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7253): MountEmulatedStorage()
,E/Zygote  ( 7253): v2
I/libpersona( 7253): KNOX_SDCARD checking this for 10004
I/libpersona( 7253): KNOX_SDCARD not a persona
,I/SELinux ( 7253): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7253): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7253): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  776): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7253 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 7253): TimaSignature is unavailable
,D/ActivityThread( 7253): Added TimaKeyStore provider
,D/ResourcesManager( 7253): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager(  776): Killing 6080:com.sec.knox.bridge/1000 (adj 15): bgCount ##41
,E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7275): MountEmulatedStorage()
E/Zygote  ( 7275): v2
I/libpersona( 7275): KNOX_SDCARD checking this for 1000
I/libpersona( 7275): KNOX_SDCARD not a persona
I/SELinux ( 7275): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7275): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7275): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager(  776): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7275 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/TimaKeyStoreProvider( 7275): TimaSignature is unavailable
D/ActivityThread( 7275): Added TimaKeyStore provider
D/ResourcesManager( 7275): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
I/DIAGMON_AGENT( 7275): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
I/DIAGMON_AGENT( 7275): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
I/wpa_supplicant( 1276): nl80211: Received scan results (7 BSSes)
I/wpa_supplicant( 1276): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1276): Trying to associate with C0.AA.4A (SSID='4E473730303567' freq=5220 MHz)
I/wpa_supplicant( 1276): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1276): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E473730303567
D/SecContentProvider2(  776): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  776): mCursor = null
I/wpa_supplicant( 1276): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1276): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E473730303567
I/wpa_supplicant( 1276): Associated with C0.AA.4A
I/wpa_supplicant( 1276): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1276): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.4A SSID=4E473730303567
D/SecContentProvider2(  776): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  776): mCursor = null
I/wpa_supplicant( 1276): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1276): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1276): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.4A SSID=4E473730303567
I/wpa_supplicant( 1276): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1276): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1276): CTRL-EVENT-CONNECTED - Connection to C0.AA.4A completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1276): Blacklist: Clear (temp) 
I/wpa_supplicant( 1276): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.4A SSID=4E473730303567
D/SecContentProvider2(  776): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  776): mCursor = null
D/WifiNative-HAL(  776): callSECApiVoid - ID [50]
D/StatusBar.NetworkController( 1186): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1186): onWifiSignalChanged enabled=true enabledDesc:null
D/ConnectivityService(  776): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  776): Got NetworkAgent Messenger
D/ConnectivityService(  776): hsengiv:checkWhatTypeOfNetwork and the value is false
E/WifiConfigStore(  776): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/ConnectivityService(  776): updateNetworkInfo()
D/ConnectivityService(  776): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  776): NetworkAgent connected
I/DIAGMON_AGENT( 7275): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
E/WifiConfigStore(  776): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
I/DIAGMON_AGENT( 7275): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
I/DIAGMON_AGENT( 7275): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
D/CommandListener(  284): Setting iface cfg
I/DIAGMON_AGENT( 7275): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
E/WifiStateMachine(  776): Start Dhcp Watchdog 2
D/SecContentProvider2(  776): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  776): mCursor = null
D/ConnectivityService(  776): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/native  (  776): do suspend false
D/SecContentProvider2(  776): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  776): mCursor = null
D/WifiP2pService(  776): InactiveState{ what=143375 }
D/WifiP2pService(  776): P2pEnabledState{ what=143375 }
E/Zygote  ( 7295): MountEmulatedStorage()
E/Zygote  ( 7295): v2
I/libpersona( 7295): KNOX_SDCARD checking this for 10014
I/libpersona( 7295): KNOX_SDCARD not a persona
I/ActivityManager(  776): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7295 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7295): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7295): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7295): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7295): TimaSignature is unavailable
I/ServiceManager(  335): Waiting for service AtCmdFwd...
D/ActivityThread( 7295): Added TimaKeyStore provider
D/ResourcesManager( 7295): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
I/ActivityManager(  776): Killing 6140:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
,I/FOTA_Client( 7295): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7295): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,E/dhcpcd  ( 7313): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 7313): version 5.5.6 starting
,E/dhcpcd  ( 7313): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/FOTA_Client( 7295): [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7322): MountEmulatedStorage()
I/libpersona( 7322): KNOX_SDCARD checking this for 10023
E/Zygote  ( 7322): v2
I/libpersona( 7322): KNOX_SDCARD not a persona
,I/ActivityManager(  776): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7322 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  776): Killing 5625:com.google.android.talk/u0a131 (adj 15): bgCount ##41
,I/SELinux ( 7322): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7322): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7322): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/dhcpcd  ( 7313): wlan0: sending IPv6 Router Solicitation
,E/dhcpcd  ( 7313): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7313): if(wlan0) info get Success. (MAC : C0.AA.4A)
I/dhcpcd  ( 7313): bssid match
I/dhcpcd  ( 7313): wlan0: rebinding lease of 192.168.1.128
,D/TimaKeyStoreProvider( 7322): TimaSignature is unavailable
,D/ActivityThread( 7322): Added TimaKeyStore provider
,D/ResourcesManager( 7322): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.511: ( 7322): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.511: ( 7322): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450233094522
,I/KLMS-2.4.511: ( 7322): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  776): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.511: ( 7322): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.511: ( 7322): StateImplV2(): networkChangeListener().END
,E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7346): MountEmulatedStorage()
,E/Zygote  ( 7346): v2
,I/libpersona( 7346): KNOX_SDCARD checking this for 10036
,I/libpersona( 7346): KNOX_SDCARD not a persona
,I/SELinux ( 7346): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/ActivityManager(  776): Start proc com.samsung.android.app.pinboard:tagService for broadcast com.samsung.android.app.pinboard/.service.TagReadyReceiver: pid=7346 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  776): Killing 5554:com.google.android.gm/u0a128 (adj 15): bgCount ##41
,I/SELinux ( 7346): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7346): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7346): TimaSignature is unavailable
,D/ActivityThread( 7346): Added TimaKeyStore provider
,D/ResourcesManager( 7346): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,W/ResourcesManager( 7346): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7346): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Minikin ( 7346): addFont failed to create font /system/fonts/SamsungSans-light.ttf
,D/ConnectivityService(  776): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  776): Killing 5806:com.sec.android.app.music:service/u0a49 (adj 15): bgCount ##41
,E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
,E/SMD     (  289): DCD ON
,E/Zygote  ( 7363): MountEmulatedStorage()
E/Zygote  ( 7363): v2
I/libpersona( 7363): KNOX_SDCARD checking this for 10042
I/libpersona( 7363): KNOX_SDCARD not a persona
,I/SELinux ( 7363): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/ActivityManager(  776): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7363 uid=10042 gids={50042, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7363): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7363): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7363): TimaSignature is unavailable
,D/ActivityThread( 7363): Added TimaKeyStore provider
,D/ResourcesManager( 7363): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT( 7363): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,D/ConnectivityService(  776): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5008): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 6637): [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
,I/SA      ( 6637): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 6637): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6637): [SLFUCHKMGR] constructor called
,E/SPPClientService( 5008): [[SystemStateMonitorService]] No Active Internet
,I/SA      ( 6637): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6637): [OR] == isSIMCardReady false ==
,I/SA      ( 6637): [SCU] == networkStateCheck == false
I/SA      ( 6637): [OR] onReceive END
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ActivityManager(  776): Killing 5876:com.sec.android.app.myfiles/u0a56 (adj 15): bgCount ##41
,E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7383): MountEmulatedStorage()
E/Zygote  ( 7383): v2
I/libpersona( 7383): KNOX_SDCARD checking this for 10074
I/libpersona( 7383): KNOX_SDCARD not a persona
,I/SELinux ( 7383): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7383): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,I/ActivityManager(  776): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=7383 uid=10074 gids={50074, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,E/SELinux ( 7383): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7383): TimaSignature is unavailable
,D/ActivityThread( 7383): Added TimaKeyStore provider
,D/ResourcesManager( 7383): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/sCloudBackupApp( 7383): sCloudBackupApp Version Info : 3.13.7.KK_APP
I/SCloudBackupReceiver( 7383): Other Intent
,E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7399): MountEmulatedStorage()
,E/Zygote  ( 7399): v2
I/libpersona( 7399): KNOX_SDCARD checking this for 1000
,I/libpersona( 7399): KNOX_SDCARD not a persona
,I/ActivityManager(  776): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7399 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  776): Killing 6242:flipboard.app/u0a125 (adj 15): bgCount ##41
,I/SELinux ( 7399): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7399): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7399): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7399): TimaSignature is unavailable
,D/ActivityThread( 7399): Added TimaKeyStore provider
,D/ResourcesManager( 7399): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7399): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro( 7399): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7399): premStatus:2
,I/KnoxUsageLogPro( 7399): isEulaShown : false
,I/KnoxUsageLogPro( 7399): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
,I/dhcpcd  ( 7313): wlan0: acknowledged 192.168.1.128 from 192.168.1.1
,I/dhcpcd  ( 7313): wlan0: leased 192.168.1.128 for 86400 seconds
,I/ActivityManager(  776): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7414 uid=10104 gids={50104, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  776): Killing 6389:com.google.android.gms:car/u0a15 (adj 15): bgCount ##41
,E/Zygote  ( 7414): MountEmulatedStorage()
E/Zygote  ( 7414): v2
I/libpersona( 7414): KNOX_SDCARD checking this for 10104
I/libpersona( 7414): KNOX_SDCARD not a persona
,D/ConnectivityService(  776): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,D/ConnectivityService(  776): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,I/SELinux ( 7414): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7414): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7414): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7414): TimaSignature is unavailable
,D/ActivityThread( 7414): Added TimaKeyStore provider
,D/ResourcesManager( 7414): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7447): MountEmulatedStorage()
E/Zygote  ( 7447): v2
I/libpersona( 7447): KNOX_SDCARD checking this for 10146
I/libpersona( 7447): KNOX_SDCARD not a persona
,I/SELinux ( 7447): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7447): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7447): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager(  776): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7447 uid=10146 gids={50146, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  776): Killing 6369:com.android.defcontainer/u0a7 (adj 15): bgCount ##41
,I/art     (  320): Explicit concurrent mark sweep GC freed 8744(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 956us total 34.020ms
,D/TimaKeyStoreProvider( 7447): TimaSignature is unavailable
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 491us total 16.813ms
,D/ActivityThread( 7447): Added TimaKeyStore provider
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 397us total 14.387ms
,D/ResourcesManager( 7447): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7447): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7447): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7447): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,I/PowerManagerService(  776): [PWL] Off : 75s ago
I/PowerManagerService(  776): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  776): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  776): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=776, ws=null) (elapsedTime=3619)
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7447): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/native  (  776): do suspend true
,D/WifiP2pService(  776): InactiveState{ what=143375 }
D/WifiP2pService(  776): P2pEnabledState{ what=143375 }
,D/ConnectivityService(  776): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,D/StatusBar.NetworkController( 1186): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1186): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine(  776): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG7005g"WPA_PSK
E/WifiStateMachine(  776): VerifyingLinkState enter
,D/WifiNative-HAL(  776): callSECApiInt - ID [210]
,E/ConnectivityService(  776): updateNetworkInfo()
,D/ConnectivityService(  776): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService(  776): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine(  776): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  776): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver(  776): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker(  776): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  776): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 1186): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1186): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine(  776): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,I/WifiTrafficPoller(  776): evaluateTrafficStatsPolling
,E/WifiStateMachine(  776): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/StatusBar.NetworkController( 1186): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1186): onWifiSignalChanged enabled=true enabledDesc:null
I/WifiTrafficPoller(  776): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  776): mBoosterFLAG : 0
I/WifiTrafficPoller(  776): current booster mode : FullMode
D/WifiNative-HAL(  776): callSECApiVoid - ID [212]
,D/StatusBar.NetworkController( 1186): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1186): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
,D/StatusBar.NetworkController( 1186): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1186): applyOpen
D/StatusBar.NetworkController( 1186): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1186): applyOpen
D/StatusBar.NetworkController( 1186): refreshSignalCluster - setNWBoosterIndicators(false)
D/ConnectivityService(  776): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/StatusBar.NetworkController( 1186): applyOpen
D/ConnectivityService(  776): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/StatusBar.NetworkController( 1186): refreshSignalCluster - setNWBoosterIndicators(false)
D/ConnectivityService(  776): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,D/StatusBar.NetworkController( 1186): applyOpen
E/ConnectivityService(  776): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  776): updateSourceRoutes : add source routing for type : 1
,D/ConnectivityService(  776): updateSourceRoutes : add src route for:192.168.1.128
V/        (  284): QcRouteController
,V/        (  284): QcRouteController
,V/        (  284): QcRouteController
,V/        (  284): QcRouteController
,V/        (  284): QcRouteController
,V/        (  284): QcRouteController
,V/        (  284): QcRouteController
,I/WebViewFactory( 7447): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,D/ResourcesManager( 7447): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7447): Loading: webviewchromium
,I/LibraryLoader( 7447): Time to load native libraries: 6 ms (timestamps 2966-2972)
,I/LibraryLoader( 7447): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7447): Binding Chromium to main looper Looper (main, tid 1) {5ede97c}
,I/LibraryLoader( 7447): Expected native library version number "",actual native library version number ""
,I/chromium( 7447): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,V/        (  284): QcRouteController
,I/BrowserStartupController( 7447): Initializing chromium process, renderers=0
,W/art     ( 7447): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7447): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7447): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46780 len=2953
W/AudioManagerAndroid( 7447): Requires BLUETOOTH permission
,I/chromium( 7447): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229536 len:643667
,D/ConnectivityService(  776): updateSourceRoutes : add src route for:fe80::ea50:8bff:fede:28a3
,V/        (  284): QcRouteController
,I/Adreno-EGL( 7447): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 7447): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7447): Build Date: 11/19/14 Wed
I/Adreno-EGL( 7447): Local Branch: mybranch5813579
I/Adreno-EGL( 7447): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 7447): Local Patches: NONE
I/Adreno-EGL( 7447): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,V/        (  284): QcRouteController
,W/NetworkManagementService(  776): route cmd failed: 
W/NetworkManagementService(  776): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '70 route replace src v6 wlan0 fe80::ea50:8bff:fede:28a3 2 ::' failed with '400 70 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  776): '
W/NetworkManagementService(  776): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService(  776): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService(  776): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService(  776): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService(  776): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  776): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5625)
W/NetworkManagementService(  776): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5437)
W/NetworkManagementService(  776): 	at com.android.server.ConnectivityService.updateNetworkInfo(ConnectivityService.java:6197)
W/NetworkManagementService(  776): 	at com.android.server.ConnectivityService.access$2400(ConnectivityService.java:229)
W/NetworkManagementService(  776): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2395)
W/NetworkManagementService(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  776): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ConnectivityService(  776): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService(  776): LTETest block dns file not exists
,V/Nat464Xlat(  776): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  776): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  776): calling update connectivity
D/EntConnectivity(  776): Not allowed due to - mEnabled false
D/ConnectivityService(  776): ignoring duplicate network state non-change. WIFI, state = CONNECTING
E/ConnectivityService(  776): updateNetworkInfo()
D/ConnectivityService(  776): ignoring duplicate network state non-change. WIFI, state = CONNECTING
E/ConnectivityService(  776): updateNetworkInfo()
D/ConnectivityService(  776): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  776): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  776): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  776): calling update connectivity
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  776): Connected
D/ConnectivityService(  776): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  776): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  776):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  776): Checking http://clients3.google.com/generate_204 on "NG7005g"
D/ConnectivityService(  776):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
I/System.out(  776): (HTTPLog)-Static: isSBSettingEnabled false
D/ConnectivityService(  776):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  776):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  776): currentScore = 0, newScore = 60
D/ConnectivityService(  776):    accepting network in place of null
D/ConnectivityService(  776): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1415): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/CSLegacyTypeTracker(  776): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  776): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  776): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  776): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  776): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
V/NetworkStats(  776): updateIfacesLocked()
D/NtpTrustedTime(  776): currentTimeMillis() cache hit
V/NetworkStats(  776): performPollLocked(flags=0x1)
D/SmartBondingService(  776): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkStatsFactory(  776): UpdateStatsForKnox
D/SmartBondingService(  776): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  776): getSBEnabled() enabled =false
D/Tethering(  776): MasterInitialState.processMessage what=3
D/ConnectivityService(  776): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  776): getSBEnabled() enabled =false
D/StatusBar.NetworkController( 1186): getUpdateDataNetType(): 0
D/SmartBondingService(  776): getSBEnabled() enabled =false
D/StatusBar.NetworkController( 1186): updateDataNetType()
D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1186): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1186): updateLTEICONDataNetType:0
D/EntConnectivity(  776): Not allowed due to - mEnabled false
D/ConnectivityService(  776): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  776): calling update connectivity
D/ConnectivityService(  776):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  776):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NtpTrustedTime(  776): currentTimeMillis() cache hit
D/ConnectivityService(  776): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1186): CM callback handler got msg 524290
D/ConnectivityService(  776):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/NetworkStats(  776): performPollLocked() took 6ms
D/ConnectivityService(  776): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/StatusBar.NetworkController( 1186): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1186): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1186): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1186): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1186): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
D/StatusBar.NetworkController( 1186): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1186): applyOpen
D/StatusBar.NetworkController( 1186): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1186): applyOpen
D/StatusBar.NetworkController( 1186): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1186): applyOpen
D/StatusBar.NetworkController( 1186): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1186): applyOpen
D/SmartBondingService(  776): getNetworkEnabled : wifi : true mobile : true
D/ConnectivityManager.CallbackHandler( 2228): CM callback handler got msg 524290
D/NtpTrustedTime(  776): currentTimeMillis() cache hit
,D/NtpTrustedTime(  776): currentTimeMillis() cache hit
D/NtpTrustedTime(  776): currentTimeMillis() cache hit
D/NtpTrustedTime(  776): currentTimeMillis() cache hit
D/NtpTrustedTime(  776): currentTimeMillis() cache hit
V/NetworkStats(  776): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  776): currentTimeMillis() cache hit
,I/NSApplication( 7447): Starting up...
,I/System.out(  776): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  776): Killing 6515:com.google.android.partnersetup/u0a19 (adj 15): bgCount ##41
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  776): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 16 Dec 2015 02:31:36 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450233096788], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450233096770]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  776): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  776): Validated
,D/ConnectivityService(  776): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  776): rematching NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  776):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  776):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  776):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  776): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  776): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  776): calling update connectivity
D/ConnectivityService(  776):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  776):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  776): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  776):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1186): CM callback handler got msg 524290
D/ConnectivityService(  776): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  776): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 2228): CM callback handler got msg 524290
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1186): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1186): updateDataNetType()
D/StatusBar.NetworkController( 1186): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1186): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1186): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1186): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1186): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1186): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1186): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
,E/Zygote  ( 7531): MountEmulatedStorage()
E/Zygote  ( 7531): v2
I/libpersona( 7531): KNOX_SDCARD checking this for 10158
I/libpersona( 7531): KNOX_SDCARD not a persona
,I/SELinux ( 7531): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/ActivityManager(  776): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7531 uid=10158 gids={50158, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 7531): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7531): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7531): TimaSignature is unavailable
,D/ActivityThread( 7531): Added TimaKeyStore provider
,D/ResourcesManager( 7531): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 7531): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7531): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7531): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 7531): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7531): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7531): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7549): MountEmulatedStorage()
,E/Zygote  ( 7549): v2
I/libpersona( 7549): KNOX_SDCARD checking this for 10186
,I/libpersona( 7549): KNOX_SDCARD not a persona
W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 4
,I/SELinux ( 7549): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,D/ConnectivityService(  776): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  776): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7549 uid=10186 gids={50186, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/SELinux ( 7549): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,I/ActivityManager(  776): Killing 6533:com.samsung.groupcast/u0a20 (adj 15): bgCount ##41
,E/SELinux ( 7549): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GpsLocationProvider(  776): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  776): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  776): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  776): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  776): SmartBondingReceiver: wifi ap is not changed
D/ConnectivityService(  776): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  776): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  776): getSBEnabled() enabled =false
D/SmartBondingService(  776): getSBEnabled() enabled =false
D/SmartBondingService(  776): getSBEnabled() enabled =false
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  776): getNetworkEnabled : wifi : true mobile : true
D/ConnectivityService(  776): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1882): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,W/ContextImpl( 1882): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  776): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NetworkMonitor( 5758): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 7549): TimaSignature is unavailable
,I/DBG_DM  ( 3580): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 3580): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/ActivityThread( 7549): Added TimaKeyStore provider
,I/jxcore-log( 7090): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 7090): 
,D/ResourcesManager( 7549): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7549): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7549): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7549): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 7549): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7549): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/art     (  776): Explicit concurrent mark sweep GC freed 103180(5MB) AllocSpace objects, 32(560KB) LOS objects, 17% free, 37MB/45MB, paused 1.437ms total 104.334ms
D/SecContentProvider2(  776): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  776): mCursor = null
,D/RCPManagerService(  776): exchangeData() failure , invalid userId
,D/RCPManagerService(  776): exchangeData() failure , invalid userId
,D/RCPManagerService(  776): exchangeData() failure , invalid userId
,D/BadgeProvider( 6699): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/RCPManagerService(  776): exchangeData() failure , invalid userId
,D/BadgeProvider( 6699): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 6699): sendNotify, [notify] : null
D/BadgeProvider( 6699): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 6699): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 6699): update, [UpdateCount] : 1
,D/Launcher.Model( 1425): reloadBadges entered.
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  776): exchangeData() failure , invalid userId
,D/RCPManagerService(  776): exchangeData() failure , invalid userId
,D/ConnectivityService(  776): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7159): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 7159): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7159): StateMachine : Current State = 1
,D/ConnectivityService(  776): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7159): StateMachine : Changed Current State = 1
,I/ActivityManager(  776): Killing 5991:sstream.app/u0a25 (adj 15): bgCount ##41
,D/ConnectivityService(  776): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7583): MountEmulatedStorage()
E/Zygote  ( 7583): v2
I/libpersona( 7583): KNOX_SDCARD checking this for 10200
I/libpersona( 7583): KNOX_SDCARD not a persona
,I/ActivityManager(  776): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7583 uid=10200 gids={50200, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7583): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7583): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7583): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  776): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/TimaKeyStoreProvider( 7583): TimaSignature is unavailable
,D/ActivityThread( 7583): Added TimaKeyStore provider
,D/ResourcesManager( 7583): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,I/ActivityManager(  776): Killing 6040:com.samsung.android.app.galaxyfinder/u0a39 (adj 15): bgCount ##41
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 5360): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5360): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5360): exit::IDLE
D/InitializeManagerStateMachine( 5360): entry::NETWORK_CHECK
,D/ConnectivityService(  776): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  776): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 5360): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5360): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5360): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5360): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5360): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5360): entry::SUCCESS
D/hcjo    ( 5360): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5360): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 5360): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  776): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 5360): exit::SUCCESS
D/InitializeManagerStateMachine( 5360): entry::IDLE
,W/ActivityManager(  776): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/Hs20UtilService( 1328): Starting #8
I/Hs20UtilService( 1328): Message received 5007
,D/NearbySettings( 1328): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1328): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  776): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1328): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  776): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1328): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1328): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1328): MountReceiver.onReceive - Keep current state
,D/ConnectivityService(  776): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6834): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 1328): Starting #9
,D/NearbySettings( 1328): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/Hs20UtilService( 1328): Message received 5007
I/NearbySettings( 1328): MountReceiver.onReceive - Keep current state
,D/ConnectivityService(  776): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6834): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 1328): Starting #10
,I/Hs20UtilService( 1328): Message received 5007
,D/NearbySettings( 1328): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1328): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  776): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1328): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  776): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1328): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1328): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1328): MountReceiver.onReceive - Keep current state
,D/ConnectivityService(  776): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6834): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 1328): Starting #11
,I/Hs20UtilService( 1328): Message received 5007
,D/NearbySettings( 1328): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1328): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine(  776): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,E/SMD     (  289): DCD ON
,D/ConnectivityService(  776): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6834): NETWORK_STATE_CHANGED_ACTION
,I/SurfaceFlinger(  254): id=15 createSurf (1x1),1 flag=4, Uoast
,I/PCWCLIENTTRACE_PushUtil( 6552): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6552): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 6552): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6552): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/PowerManagerService(  776): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=776
,I/DIAGMON_AGENT( 7275): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7275): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/FOTA_Client( 7295): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7295): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7295): [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.511: ( 7322): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.511: ( 7322): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450233098170
,I/KLMS-2.4.511: ( 7322): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  776): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.511: ( 7322): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.511: ( 7322): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.511: ( 7322): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.511: ( 7322): StateImplV2(): networkChangeListener().END
,D/ConnectivityService(  776): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SO_AGENT( 7363): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/ConnectivityService(  776): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
,E/SPPClientService( 5008): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 6637): [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
,I/SA      ( 6637): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,I/SA      ( 6637): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6637): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6637): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 6637): [SCU] == networkStateCheck == true
,I/SA      ( 6637): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 6637): isChinaCountryCode : false
I/SA      ( 6637): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6637): [OR] == networkStateCheck true ==
,I/SA      ( 6637): [OR] GetMyCountryZoneTask
,I/SA      ( 6637): [OR] onReceive END
,I/SA      ( 6637): [SRS] prepareGetMyCountryZone
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SCloudBackupReceiver( 7383): Other Intent
,I/KnoxUsageLogPro( 7399): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7399): premStatus:2
,I/KnoxUsageLogPro( 7399): isEulaShown : false
,I/KnoxUsageLogPro( 7399): KnoxUsageReceiver onReceive : not Processible, just return
,I/SA      ( 6637): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6637): [SSP] query invoked
,I/SA      ( 6637): [TPMU] GetMccFromDB : null
,I/SA      ( 6637): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6637): [TPM] isNoProxy(default) : true
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/File    ( 6637): fail readDirectory() errno=2
,D/QuickConnect( 7531): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7531): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7531): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  776): exchangeData() failure , invalid userId
,D/RCPManagerService(  776): exchangeData() failure , invalid userId
,D/ConnectivityService(  776): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7159): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 7159): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7159): StateMachine : Current State = 1
,D/ConnectivityService(  776): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 7159): StateMachine : Changed Current State = 1
,D/ConnectivityService(  776): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 5360): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5360): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 5360): exit::IDLE
D/InitializeManagerStateMachine( 5360): entry::NETWORK_CHECK
,D/ConnectivityService(  776): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 5360): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5360): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5360): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5360): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5360): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5360): entry::SUCCESS
D/hcjo    ( 5360): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/ConnectivityService(  776): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/hcjo    ( 5360): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 5360): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 5360): exit::SUCCESS
D/InitializeManagerStateMachine( 5360): entry::IDLE
,I/dhcpcd  ( 7313): wlan0: sending IPv6 Router Solicitation
,I/SA      ( 6637): [RC New] Execute method=[GET] start
,I/SA      ( 6637): [RC New] Security=[true]
,I/System.out( 6637): Thread-1101(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6637): Thread-1101(ApacheHTTPLog):isShipBuild true
I/System.out( 6637): Thread-1101(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,E/Watchdog(  776): !@Sync 5
,E/WifiStateMachine(  776): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/SA      ( 6637): [RC New] [v2liruge] api execute + 712
,I/SA      ( 6637): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6637): AsyncTask #1 calls detatch()
,I/SA      ( 6637): [TPMU] getNetworkMcc : 
,I/SA      ( 6637): [SCU] saveMccToPreferece Start
,I/SA      ( 6637): [SCU] RegionMCC : 260
I/SA      ( 6637): [SSP] query invoked
,I/SA      ( 6637): [TPMU] GetMccFromDB : null
,I/SA      ( 6637): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6637): [SCU] saveMccToPreferece End
,I/SA      ( 6637): [RC New] executeRequest [v2liruge] end. 788
,I/SA      ( 6637): [RC New] Execute end
,I/SA      ( 6637): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 6637): [OR] GetMyCountryZoneTask Success
,V/AlarmManager(  776): waitForAlarm result :4
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  776): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  776): <AppSync3 Whitelist>
V/AlarmManager(  776): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1186): handleTimeUpdate
,D/KeyguardEffectViewController( 1186): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1186): *** don't update sliding image ***
,E/SMD     (  289): DCD ON
,D/DateView( 1186): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1186): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GAV4    ( 7447): Thread[GAThread,5,main]: No campaign data found.
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SurfaceFlinger(  254): id=15 Removed Uoast (8/9)
,I/SurfaceFlinger(  254): id=15 Removed Uoast (-2/9)
,D/PowerManagerService(  776): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 776) eventTime = 167836
,D/PowerManagerService(  776): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=776 (0x0)
D/PowerManagerService(  776): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=776, ws=WorkSource{10067}) (elapsedTime=3466)
,D/SSRM:n  (  776): SIOP:: AP = 330, PST = 324, CUR = 450
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  776): stay LED for fully charged
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,I/dhcpcd  ( 7313): wlan0: sending IPv6 Router Solicitation
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6552): mConnectivityHandler : connected
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 6552): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE( 6552): ================================================
,I/CSTORAGE( 6552):  CSTORAGE_SKM_LIB v1.0.6
I/CSTORAGE( 6552): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 6552): [GetString-S]
,E/art     ( 6552): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
W/PCWCLIENTTRACE_SecurePreferencesJNI( 6552): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 6552): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 6552): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6552): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 6552): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 6552): [ensureRegistration] - No Samsung account
,E/SMD     (  289): DCD ON
,W/ContextImpl(  776): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/dhcpcd  ( 7313): wlan0: sending IPv6 Router Solicitation,
,I/dhcpcd  ( 7313): wlan0: no IPv6 Routers available,
,E/SMD     (  289): DCD ON
,D/PreloadUpdateManagerStateMachine( 5360): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5360): exit::IDLE
D/PreloadUpdateManagerStateMachine( 5360): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5360): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5360): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5360): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5360): entry::IDLE
,D/PreloadUpdateManagerStateMachine( 5360): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5360): exit::IDLE
D/PreloadUpdateManagerStateMachine( 5360): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5360): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/PreloadUpdateManagerStateMachine( 5360): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5360): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5360): entry::IDLE
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 310, PST = 320, CUR = 450
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,I/ActivityManager(  776): Waited long enough for: ServiceRecord{3bce1ef9 u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,E/SMD     (  289): DCD ON
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ClearcutLoggerApiImpl( 1892): disconnect managed GoogleApiClient
,V/AlarmManager(  776): waitForAlarm result :8
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/SSRM:n  (  776): SIOP:: AP = 300, PST = 315, CUR = 450
,E/SMD     (  289): DCD ON
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 5
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  776): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,W/ContextImpl(  776): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  776): [PWL] Off : 105s ago
,E/SMD     (  289): DCD ON
,E/Watchdog(  776): !@Sync 6
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 300, PST = 312, CUR = 450
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/BatteryService(  776): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 300, PST = 310, CUR = 450
,E/SMD     (  289): DCD ON
,V/AlarmManager(  776): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.TIME_TICK
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/KeyguardUpdateMonitor( 1186): handleTimeUpdate
,D/BatteryService(  776): stay LED for fully charged
,D/KeyguardEffectViewController( 1186): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1186): *** don't update sliding image ***
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,I/MotionRecognitionService(  776): Plugged
I/MotionRecognitionService(  776): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/DateView( 1186): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1186): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 2228): Aggregate from 1450231343290 (log), 1450231343290 (data)
,E/SMD     (  289): DCD ON
,W/ContextImpl(  776): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Atfwd_Sendcmd(  335): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  335): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 300, PST = 309, CUR = 450
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450,
D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  776): stay LED for fully charged
,E/SMD     (  289): DCD ON
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/Watchdog(  776): !@Sync 7
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/PowerManagerService(  776): [PWL] Off : 140s ago
,D/SSRM:n  (  776): SIOP:: AP = 300, PST = 308, CUR = 450
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 1
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,W/ContextImpl(  776): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/SSRM:n  (  776): SIOP:: AP = 300, PST = 307, CUR = 450
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/BatteryService(  776): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,V/AlarmManager(  776): waitForAlarm result :8
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 290, PST = 306, CUR = 450
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,W/ContextImpl(  776): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  289): DCD ON
,E/Watchdog(  776): !@Sync 8
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 290, PST = 302, CUR = 450
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  776): Plugged
I/MotionRecognitionService(  776): setPowerConnected  = true
,D/BatteryService(  776): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  776): [PWL] Off : 180s ago
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/SSRM:n  (  776): SIOP:: AP = 290, PST = 298, CUR = 450
,E/SMD     (  289): DCD ON
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,W/ContextImpl(  776): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 290, PST = 296, CUR = 450
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  776): Plugged
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
I/MotionRecognitionService(  776): setPowerConnected  = true
,D/BatteryService(  776): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/Watchdog(  776): !@Sync 9
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 290, PST = 295, CUR = 450
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  776): stay LED for fully charged
D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,E/SMD     (  289): DCD ON
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
I/MotionRecognitionService(  776): Plugged
I/MotionRecognitionService(  776): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  776): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:n  (  776): SIOP:: AP = 290, PST = 294, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/BatteryService(  776): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 290, PST = 293, CUR = 450
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,W/ContextImpl(  776): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  776): [PWL] Off : 225s ago
,D/TimaService(  776): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  776): TimaServiceHandler.handleMessage what =1
,D/TimaService(  776): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  776): initializing...
,I/TLC_TIMA_PKM_initialize(  776): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  776): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  776): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  776): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  776): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  776): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  776): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: (  776): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  776): App is not loaded in QSEE
,D/QSEECOMAPI: (  776): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  776): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  776): Trustlet response is completed
,E/SMD     (  289): DCD ON
,E/Watchdog(  776): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel(  776): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  776): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  776): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  776): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 290, PST = 292, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,I/Atfwd_Sendcmd(  335): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  335): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/jxcore-log( 7090): Connected to the server!
I/jxcore-log( 7090): 
,I/chromium( 7090): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 290, PST = 291, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,W/ContextImpl(  776): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  776): waitForAlarm result :4
,E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,I/ActivityManager(  776): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=7686 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1186): handleTimeUpdate
,E/Zygote  ( 7686): MountEmulatedStorage()
,D/KeyguardEffectViewController( 1186): onReceive action : android.intent.action.TIME_TICK
,E/Zygote  ( 7686): v2
I/libpersona( 7686): KNOX_SDCARD checking this for 10096
I/libpersona( 7686): KNOX_SDCARD not a persona
,I/KeyguardEffectViewController( 1186): *** don't update sliding image ***
,I/SELinux ( 7686): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7686): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7686): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/DateView( 1186): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1186): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/TimaKeyStoreProvider( 7686): TimaSignature is unavailable
,D/ActivityThread( 7686): Added TimaKeyStore provider
,D/ResourcesManager( 7686): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,I/ActivityManager(  776): Killing 4545:com.sec.android.app.shealth/u0a40 (adj 15): bgCount ##41
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/SSRM:n  (  776): SIOP:: AP = 290, PST = 290, CUR = 450
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 1
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/Watchdog(  776): !@Sync 11
,E/SMD     (  289): DCD ON
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/SSRM:n  (  776): SIOP:: AP = 290, PST = 290, CUR = 450
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,W/ContextImpl(  776): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 2
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  776): [PWL] Off : 275s ago
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,V/AlarmManager(  776): waitForAlarm result :8
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:n  (  776): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  289): DCD ON
,W/ContextImpl(  776): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/BatteryService(  776): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,E/Watchdog(  776): !@Sync 12
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  776): Plugged
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/BatteryService(  776): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 4
,D/SSRM:n  (  776): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,W/ContextImpl(  776): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  776): Plugged
I/MotionRecognitionService(  776): setPowerConnected  = true
,D/BatteryService(  776): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,E/Watchdog(  776): !@Sync 13
,E/SMD     (  289): DCD ON
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/SSRM:n  (  776): SIOP:: AP = 290, PST = 290, CUR = 450
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,W/ContextImpl(  776): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 5
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  776): stay LED for fully charged
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  776): [PWL] Off : 330s ago
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  289): DCD ON
,W/ContextImpl(  776): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  776): Plugged
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/BatteryService(  776): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,E/Watchdog(  776): !@Sync 14
,E/SMD     (  289): DCD ON
,I/Atfwd_Sendcmd(  335): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  335): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:n  (  776): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  776): Plugged
I/MotionRecognitionService(  776): setPowerConnected  = true
,D/BatteryService(  776): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  289): DCD ON
,W/ContextImpl(  776): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  776): stay LED for fully charged
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 289, CUR = 450
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  776): Plugged
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/BatteryService(  776): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,E/Watchdog(  776): !@Sync 15
,E/SMD     (  289): DCD ON
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 288, CUR = 450
,E/SMD     (  289): DCD ON
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,W/ContextImpl(  776): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 2
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  776): [PWL] Off : 390s ago
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 287, CUR = 450
,E/SMD     (  289): DCD ON
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/BatteryService(  776): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,I/bootchecker(  327): bootchecker wake up!!
,E/SMD     (  289): DCD ON
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 286, CUR = 450
,E/SMD     (  289): DCD ON
,W/ContextImpl(  776): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  776): Plugged
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/BatteryService(  776): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  776): !@Sync 16
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 285, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  776): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 284, CUR = 450
,E/SMD     (  289): DCD ON
,W/ContextImpl(  776): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 290, PST = 284, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  776): Plugged
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/BatteryService(  776): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  776): !@Sync 17
,E/SMD     (  289): DCD ON
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 283, CUR = 450
,E/SMD     (  289): DCD ON
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,W/ContextImpl(  776): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 5
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/BatteryService(  776): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 282, CUR = 450
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  776): [PWL] Off : 455s ago
,E/SMD     (  289): DCD ON
,V/AlarmManager(  776): waitForAlarm result :8
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  776): Plugged
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/BatteryService(  776): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  289): DCD ON
,W/ContextImpl(  776): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,E/Watchdog(  776): !@Sync 18
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,I/Atfwd_Sendcmd(  335): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  335): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  289): DCD ON
,W/ContextImpl(  776): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  289): DCD ON
,I/Atfwd_Daemon(  335): Stop the daemon....
,E/SMD     (  289): DCD ON
,E/Watchdog(  776): !@Sync 19
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  289): DCD ON
,W/ContextImpl(  776): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/BatteryService(  776): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  289): DCD ON
,W/ContextImpl(  776): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  776): [PWL] Off : 525s ago
,D/TimaService(  776): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  776): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  776): TimaServiceHandler.handleMessage what =1
,E/SMD     (  289): DCD ON
,E/Watchdog(  776): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel(  776): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  776): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  776): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  776): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/BatteryService(  776): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 290, PST = 281, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  776): Plugged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  776): stay LED for fully charged
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  289): DCD ON
,W/ContextImpl(  776): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,I/ActivityManager(  776): Killing 6608:com.samsung.android.sdk.samsunglink/u0a48 (adj 15): bgCount ##41
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/BatteryService(  776): stay LED for fully charged
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/Watchdog(  776): !@Sync 21
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true,
,D/BatteryService(  776): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  776): Plugged
I/MotionRecognitionService(  776): setPowerConnected  = true
,D/BatteryService(  776): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/Watchdog(  776): !@Sync 22
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/BatteryService(  776): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,I/PowerManagerService(  776): [PWL] Off : 600s ago
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/Watchdog(  776): !@Sync 23
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,W/art     (  776): Suspending all threads took: 8.283ms
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  776): stay LED for fully charged
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  776): Plugged
I/MotionRecognitionService(  776): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/Watchdog(  776): !@Sync 24
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  776): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450,
D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  776): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/Watchdog(  776): !@Sync 25
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  776): [PWL] Off : 680s ago
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  776): setPowerConnected  = true
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/BatteryService(  776): stay LED for fully charged
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/Watchdog(  776): !@Sync 26
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  776): stay LED for fully charged
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/Watchdog(  776): !@Sync 27
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
D/BatteryService(  776): stay LED for fully charged
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/BatteryService(  776): stay LED for fully charged
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,I/PowerManagerService(  776): [PWL] Off : 765s ago
,E/SMD     (  289): DCD ON
,E/Watchdog(  776): !@Sync 28
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  776): stay LED for fully charged
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  776): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/Watchdog(  776): !@Sync 29
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  776): stay LED for fully charged
D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  776): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
I/MotionRecognitionService(  776): Plugged
I/MotionRecognitionService(  776): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  776): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,D/TimaService(  776): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  776): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  776): TimaServiceHandler.handleMessage what =1
,E/SMD     (  289): DCD ON
,E/Watchdog(  776): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel(  776): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  776): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  776): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  776): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,V/AlarmManager(  776): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1186): handleTimeUpdate
,D/KeyguardEffectViewController( 1186): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1186): *** don't update sliding image ***
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  776): stay LED for fully charged
,D/LightsService(  776): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  776): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager(  776): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1186): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1186): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/LightsService(  776): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  776): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  776): unregisterListener ::   
,D/LightsService(  776): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,I/PowerManagerService(  776): [PWL] Off : 855s ago
,E/SMD     (  289): DCD ON
,E/Watchdog(  776): !@Sync 31
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,V/AlarmManager(  776): waitForAlarm result :8
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/Watchdog(  776): !@Sync 32
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/BatteryService(  776): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/BatteryService(  776): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  776): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/Watchdog(  776): !@Sync 33
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/BatteryService(  776): stay LED for fully charged
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  776): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/Watchdog(  776): !@Sync 34
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0,
D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  776): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  776): [PWL] Off : 950s ago
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0,
D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  776): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/BatteryService(  776): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/Watchdog(  776): !@Sync 35
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/BatteryService(  776): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  776): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  776): stay LED for fully charged
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/Watchdog(  776): !@Sync 36
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/BatteryService(  776): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/Watchdog(  776): !@Sync 37
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  776): stay LED for fully charged
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  776): [PWL] Off : 1050s ago
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  776): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,V/AlarmManager(  776): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1186): handleTimeUpdate
,D/KeyguardEffectViewController( 1186): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1186): *** don't update sliding image ***
,D/daemonapp( 2951): [MSC_Accu_Daemon]>>> AWDS:70 [0:0] Act : widgetappapaccuweatherdaemonactionAUTOREFRESH, run:true
,D/comsamsunglog( 2951): [MSC_Accu_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 2951): [MSC_Accu_Daemon]>>> daemonapp [Version : 14123102 ] [ 1 ] 
,D/comsamsunglog( 2951): [MSC_Accu_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 2951): [MSC_Accu_Daemon]>>> ====================================================================================================================
D/daemonapp( 2951): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/DateView( 1186): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1186): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/daemonapp( 2951): [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
,D/daemonapp( 2951): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/daemonapp( 2951): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/daemonapp( 2951): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/daemonapp( 2951): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 2951): [MSC_Accu_Daemon]>>> AWDS:113 [0:0] SerStus:true,TmpS:1,AtRfr:3, checkCurrent: 0
,D/daemonapp( 2951): [MSC_Accu_Daemon]>>> AWDS:322 [0:0] Act: ACTION_SEC_AUTO_REFRESH
,D/daemonapp( 2951): [MSC_Accu_Daemon]>>> AWDS:1501 [0:0] Cncl30MinRftAl
,D/daemonapp( 2951): [MSC_Accu_Daemon]>>> AWDS:326 [0:0] !!!! isScreenOn = false
,D/daemonapp( 2951): [MSC_Accu_Daemon]>>> AWDS:328 [0:0] !!!! isScreenOn = false
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  776): Plugged
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/BatteryService(  776): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/Watchdog(  776): !@Sync 38
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/BatteryService(  776): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/Watchdog(  776): !@Sync 39
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/BatteryService(  776): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,V/AlarmManager(  776): waitForAlarm result :8
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/BatteryService(  776): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/TimaService(  776): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  776): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  776): TimaServiceHandler.handleMessage what =1
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,I/UsageStatsService(  776): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  776): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  776): Updating Usage Statistics in DB @ 1450234147353
,I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
,W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
,W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
,W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
,W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
,W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
,W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
,W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
,W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
,W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  776): ::getAppControlDB: Exception to create DB
W/System.err(  776): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  776): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  776): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  776): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage(  776): Done Updating Usage Statistics in DB @ 1450234147543
,E/SMD     (  289): DCD ON
,E/Watchdog(  776): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel(  776): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  776): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  776): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  776): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  776): stay LED for fully charged
D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
I/MotionRecognitionService(  776): Plugged
I/MotionRecognitionService(  776): setPowerConnected  = true
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  776): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  776): [PWL] Off : 1155s ago
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/Watchdog(  776): !@Sync 41
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/BatteryService(  776): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  776): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/Watchdog(  776): !@Sync 42
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  776): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/Watchdog(  776): !@Sync 43
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  776): Plugged
D/BatteryService(  776): stay LED for fully charged
I/MotionRecognitionService(  776): setPowerConnected  = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/Watchdog(  776): !@Sync 44
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  776): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  776): [PWL] Off : 1265s ago
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  776): stay LED for fully charged
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/Watchdog(  776): !@Sync 45
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  776): stay LED for fully charged
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  776): Plugged
I/MotionRecognitionService(  776): setPowerConnected  = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  776): stay LED for fully charged
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/Watchdog(  776): !@Sync 46
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/BatteryService(  776): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/BatteryService(  776): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  776): stay LED for fully charged
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/Watchdog(  776): !@Sync 47
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  776): stay LED for fully charged
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  776): !@Sync 48
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/BatteryService(  776): stay LED for fully charged
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  776): [PWL] Off : 1380s ago
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  776): !@Sync 49
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  776): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/TimaService(  776): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  776): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  776): TimaServiceHandler.handleMessage what =1
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  776): !@Sync 50
,I/TLC_TIMA_PKM_measure_kernel(  776): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  776): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  776): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  776): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  776): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  776): !@Sync 51
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  776): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
I/MotionRecognitionService(  776): Plugged
I/MotionRecognitionService(  776): setPowerConnected  = true
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  776): stay LED for fully charged
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  776): !@Sync 52
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  776): stay LED for fully charged
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  776): [PWL] Off : 1500s ago
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  776): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  776): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  776): !@Sync 53
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  776): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  776): !@Sync 54
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  776): stay LED for fully charged
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/BatteryService(  776): stay LED for fully charged
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  776): !@Sync 55
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/BatteryService(  776): stay LED for fully charged
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
I/MotionRecognitionService(  776): Plugged
I/MotionRecognitionService(  776): setPowerConnected  = true
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  776): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/Watchdog(  776): !@Sync 56
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
I/MotionRecognitionService(  776): Plugged
I/MotionRecognitionService(  776): setPowerConnected  = true
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  776): stay LED for fully charged
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  776): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  776): [PWL] Off : 1625s ago
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  776): stay LED for fully charged
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/Watchdog(  776): !@Sync 57
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
I/MotionRecognitionService(  776): Plugged
I/MotionRecognitionService(  776): setPowerConnected  = true
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  776): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/Watchdog(  776): !@Sync 58
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  776): stay LED for fully charged
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/Watchdog(  776): !@Sync 59
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/NetworkStatsFactory(  776): UpdateStatsForKnox
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  776): stay LED for fully charged
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  776): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService(  776): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  776): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  776): TimaServiceHandler.handleMessage what =1
,E/SMD     (  289): DCD ON
,E/Watchdog(  776): !@Sync 60
,I/TLC_TIMA_PKM_measure_kernel(  776): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  776): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  776): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  776): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  776): setPowerConnected  = true
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  776): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,V/AlarmManager(  776): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1186): handleTimeUpdate
,D/LightsService(  776): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  776): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): stay LED for fully charged
,D/KeyguardEffectViewController( 1186): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1186): *** don't update sliding image ***
,D/SensorManager(  776): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,I/ProcessStatsService(  776): Prepared write state in 11ms
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,V/NetworkStats(  776): performPollLocked(flags=0x3)
D/NtpTrustedTime(  776): currentTimeMillis() cache hit
,D/NetworkStatsFactory(  776): UpdateStatsForKnox
,D/ConnectivityService(  776): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/NetworkStats(  776): performPollLocked() took 6ms
,D/NtpTrustedTime(  776): currentTimeMillis() cache hit
,I/ProcessStatsService(  776): Prepared write state in 11ms
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/NtpTrustedTime(  776): currentTimeMillis() cache hit
,D/NtpTrustedTime(  776): currentTimeMillis() cache hit
,V/AlarmManager(  776): OOI=Alarm{c94b39e type 0 when 1450236570128 com.google.android.gms}
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  776): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1186): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,D/DateView( 1186): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/LightsService(  776): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  776): Light old sensor_state 512, new sensor_state : 0 en : 0
,I/ProcessStatsService(  776): Pruning old procstats: /data/system/procstats/state-2015-12-15-15-43-14.bin
,D/SensorManager(  776): unregisterListener ::   
D/LightsService(  776): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  289): DCD ON,
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  776): [PWL] Off : 1755s ago
,E/SMD     (  289): DCD ON
,E/Watchdog(  776): !@Sync 61
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): stay LED for fully charged
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  776): Plugged
I/MotionRecognitionService(  776): setPowerConnected  = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  776): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  776): Plugged
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
I/MotionRecognitionService(  776): setPowerConnected  = true
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,V/AlarmManager(  776): waitForAlarm result :8
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/BatteryService(  776): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/Watchdog(  776): !@Sync 62
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  776): stay LED for fully charged
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/BatteryService(  776): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/Watchdog(  776): !@Sync 63
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  776): Plugged
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/BatteryService(  776): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  776): Plugged
I/MotionRecognitionService(  776): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  776): stay LED for fully charged
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  776): stay LED for fully charged
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  776): Plugged
I/MotionRecognitionService(  776): setPowerConnected  = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/Watchdog(  776): !@Sync 64
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  776): stay LED for fully charged
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  776): Plugged
I/MotionRecognitionService(  776): setPowerConnected  = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  776): stay LED for fully charged
D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  776): stay LED for fully charged
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,I/MotionRecognitionService(  776): Plugged
I/MotionRecognitionService(  776): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/Watchdog(  776): !@Sync 65
,D/BatteryService(  776): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  776): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  776): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  776): stay LED for fully charged
,D/BatteryService(  776): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1186): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  776): Plugged
,I/MotionRecognitionService(  776): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1186): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1186):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3126): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3126): Disconnected process message: 10
D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1186): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  776): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,TIME-OUT KILL (timeout was 1800000ms),E/SMD     (  289): DCD ON
D/AndroidRuntime( 7849): 
D/AndroidRuntime( 7849): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7849): CheckJNI is OFF
D/AndroidRuntime( 7849): readGMSProperty: start
D/AndroidRuntime( 7849): readGMSProperty: already setted!!
D/AndroidRuntime( 7849): readGMSProperty: end
D/AndroidRuntime( 7849): addProductProperty: start
E/AffinityControl( 7849): AffinityControl: registerfunction enter
D/AndroidRuntime( 7849): Calling main entry com.android.commands.pm.Pm
D/PackageManager(  776): START PACKAGE DELETE: observer{876531327}
D/PackageManager(  776): pkg{<packageName>}
D/PackageManager(  776): user{0}
D/PackageManager(  776): caller{2000}
D/PackageManager(  776): flags{3}
D/PersonaManagerService(  776): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  776): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  776): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  776): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  776): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  776): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  776): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  776): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  776): getApplicationUninstallationEnabled
D/ApplicationPolicy(  776): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  776): !@killApplicatoin: 10294, uninstall pkg
I/ActivityManager(  776): Force stopping com.test.thalitest appid=10294 user=-1: uninstall pkg
I/ActivityManager(  776): Killing 7090:com.test.thalitest/u0a294 (adj 0): stop com.test.thalitest
W/PackageSettings(  776): Skipping PackageSetting{2d8c6ac3 com.example.hello/10292} due to missing metadata
I/WindowState(  776): WIN DEATH: Window{40f0301 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  254): id=14 Removed NainActivit (5/8)
I/SurfaceFlinger(  254): id=14 Removed NainActivit (-2/8)
D/PointerIcon(  776): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  776): setMouseCustomIcon IconType is same.101
D/PointerIcon(  776): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  776): setHoveringSpenCustomIcon IconType is same.1
E/libprocessgroup(  776): failed to kill 1 processes for processgroup 7090
I/ActivityManager(  776): Killing 6106:com.sec.chaton/u0a102 (adj 11): empty for 1806s
I/ActivityManager(  776): Killing 7399:com.sec.knox.bridge/1000 (adj 11): empty for 1806s
I/ActivityManager(  776): Killing 7383:com.samsung.android.scloud.backup/u0a74 (adj 11): empty for 1806s
I/ActivityManager(  776): Killing 6637:com.osp.app.signin/u0a50 (adj 11): empty for 1806s
I/ActivityManager(  776): Killing 6587:com.policydm/1000 (adj 11): empty for 1806s
I/ActivityManager(  776): Killing 7363:com.sec.android.soagent/u0a42 (adj 11): empty for 1806s
I/ActivityManager(  776): Killing 7190:com.vlingo.midas/u0a38 (adj 11): empty for 1806s
I/ActivityManager(  776): Killing 7346:com.samsung.android.app.pinboard:tagService/u0a36 (adj 11): empty for 1806s
I/ActivityManager(  776): Killing 7322:com.samsung.klmsagent/u0a23 (adj 11): empty for 1806s
I/ActivityManager(  776): Killing 7295:com.sec.android.fotaclient/u0a14 (adj 11): empty for 1806s
I/ActivityManager(  776): Killing 7275:com.sec.android.diagmonagent/1000 (adj 13): empty for 1807s
I/ActivityManager(  776): Killing 7253:com.sec.android.cloudagent/u0a4 (adj 13): empty for 1807s
I/ActivityManager(  776): Killing 6552:com.sec.pcw.device/1000 (adj 13): empty for 1807s
I/ActivityManager(  776): Killing 6834:com.samsung.android.snote/u0a168 (adj 13): empty for 1807s
I/ActivityManager(  776): Killing 6699:com.sec.android.provider.badge/u0a92 (adj 13): empty for 1807s
I/ActivityManager(  776): Killing 1680:com.google.process.gapps/u0a15 (adj 13): empty for 1808s
I/ActivityManager(  776): Killing 6156:com.android.vending/u0a33 (adj 13): empty for 1876s
I/ActivityManager(  776): Killing 6879:com.sec.kidsplat.installer/u0a189 (adj 13): empty for 1891s
I/ActivityManager(  776): Killing 6855:com.samsung.android.snote:provider/u0a168 (adj 13): empty for 1891s
I/ActivityManager(  776): Killing 6125:com.sec.android.app.controlpanel/u0a134 (adj 13): empty for 1892s
I/ActivityManager(  776): Killing 6816:com.samsung.helphub/1000 (adj 15): empty for 1892s
I/ActivityManager(  776): Killing 6801:com.samsung.android.app.watchmanagerstub/u0a126 (adj 15): empty for 1892s
I/ActivityManager(  776): Killing 6773:com.samsung.android.app.filterinstaller/1000 (adj 15): empty for 1892s
I/ActivityManager(  776): Killing 6727:com.google.android.apps.docs/u0a112 (adj 15): empty for 1892s
I/ActivityManager(  776): Killing 6742:com.wsomacp/u0a29 (adj 15): empty for 1893s
I/ActivityManager(  776): Killing 5609:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1893s
I/ActivityManager(  776): Killing 6684:com.sec.android.app.soundalive/u0a64 (adj 15): empty for 1893s
I/ActivityManager(  776): Killing 6658:com.android.mms/u0a55 (adj 15): empty for 1894s
I/ActivityManager(  776): Killing 5822:com.sec.android.gallery3d/u0a53 (adj 15): empty for 1894s
I/ActivityManager(  776):   Force finishing activity ActivityRecord{227253a3 u0 com.test.thalitest/.MainActivity t4}
W/ActivityManager(  776): mDVFSHelper.acquire()
W/ActivityManager(  776): Spurious death for ProcessRecord{16e2ce4c 7090:com.test.thalitest/u0a294}, curProc for 7090: null
W/libprocessgroup(  776): failed to open /acct/uid_10015/pid_1680/cgroup.procs: No such file or directory
W/libprocessgroup(  776): failed to open /acct/uid_10102/pid_6106/cgroup.procs: No such file or directory
W/libprocessgroup(  776): failed to open /acct/uid_1000/pid_7399/cgroup.procs: No such file or directory
W/libprocessgroup(  776): failed to open /acct/uid_10074/pid_7383/cgroup.procs: No such file or directory
W/libprocessgroup(  776): failed to open /acct/uid_10050/pid_6637/cgroup.procs: No such file or directory
W/libprocessgroup(  776): failed to open /acct/uid_1000/pid_6587/cgroup.procs: No such file or directory
W/libprocessgroup(  776): failed to open /acct/uid_10042/pid_7363/cgroup.procs: No such file or directory
W/libprocessgroup(  776): failed to open /acct/uid_10038/pid_7190/cgroup.procs: No such file or directory
W/libprocessgroup(  776): failed to open /acct/uid_10036/pid_7346/cgroup.procs: No such file or directory
W/libprocessgroup(  776): failed to open /acct/uid_10023/pid_7322/cgroup.procs: No such file or directory
W/libprocessgroup(  776): failed to open /acct/uid_10014/pid_7295/cgroup.procs: No such file or directory
W/libprocessgroup(  776): failed to open /acct/uid_1000/pid_7275/cgroup.procs: No such file or directory
W/libprocessgroup(  776): failed to open /acct/uid_10004/pid_7253/cgroup.procs: No such file or directory
W/libprocessgroup(  776): failed to open /acct/uid_1000/pid_6552/cgroup.procs: No such file or directory
W/libprocessgroup(  776): failed to open /acct/uid_10168/pid_6834/cgroup.procs: No such file or directory
W/libprocessgroup(  776): failed to open /acct/uid_10092/pid_6699/cgroup.procs: No such file or directory
W/libprocessgroup(  776): failed to open /acct/uid_10112/pid_6727/cgroup.procs: No such file or directory
D/CountryDetector(  776): No listener is left
W/libprocessgroup(  776): failed to open /acct/uid_10189/pid_6879/cgroup.procs: No such file or directory
W/libprocessgroup(  776): failed to open /acct/uid_10168/pid_6855/cgroup.procs: No such file or directory
W/libprocessgroup(  776): failed to open /acct/uid_10134/pid_6125/cgroup.procs: No such file or directory
W/libprocessgroup(  776): failed to open /acct/uid_1000/pid_6816/cgroup.procs: No such file or directory
W/libprocessgroup(  776): failed to open /acct/uid_10126/pid_6801/cgroup.procs: No such file or directory
W/libprocessgroup(  776): failed to open /acct/uid_1000/pid_6773/cgroup.procs: No such file or directory
W/libprocessgroup(  776): failed to open /acct/uid_10064/pid_6684/cgroup.procs: No such file or directory
W/libprocessgroup(  776): failed to open /acct/uid_10055/pid_6658/cgroup.procs: No such file or directory
W/libprocessgroup(  776): failed to open /acct/uid_10033/pid_6156/cgroup.procs: No such file or directory
W/libprocessgroup(  776): failed to open /acct/uid_10053/pid_5822/cgroup.procs: No such file or directory
I/DBG_DM  ( 3580): [com.wssyncmldm.ui.XUIInstallConfirmActivity(477/onResume)] 
W/libprocessgroup(  776): failed to open /acct/uid_10029/pid_6742/cgroup.procs: No such file or directory
D/ConnectivityService(  776): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/libprocessgroup(  776): failed to open /acct/uid_1000/pid_5609/cgroup.procs: No such file or directory
I/ActivityManager(  776): Force stopping com.test.thalitest appid=10294 user=0: pkg removed
I/DBG_DM  ( 3580): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 18
I/DBG_DM  ( 3580): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
I/DBG_DM  ( 3580): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 3580): [com.wssyncmldm.ui.XUIInstallConfirmActivity(487/onResume)] Postpone Count : 18
I/DBG_DM  ( 3580): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
I/DBG_DM  ( 3580): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
D/ResourcesManager(  776): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/ResourcesManager(  776): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ResourcesManager(  776): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
D/ResourcesManager(  776): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
I/InputReader(  776): Reconfiguring input devices.  changes=0x00000010
D/ResourcesManager(  776): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/ResourcesManager(  776): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
I/art     ( 1593): Explicit concurrent mark sweep GC freed 32866(2MB) AllocSpace objects, 1(39KB) LOS objects, 24% free, 18MB/25MB, paused 737us total 74.220ms
I/art     ( 4448): Explicit concurrent mark sweep GC freed 34430(1917KB) AllocSpace objects, 9(144KB) LOS objects, 40% free, 15MB/26MB, paused 730us total 40.407ms
D/ResourcesManager(  776): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
E/SamsungIME( 1719): mOCRHelper is null
W/GeofencerStateMachine( 1892): Ignoring removeGeofence because network location is disabled.
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  776): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager(  776): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager(  776): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager(  776): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager(  776): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
D/ResourcesManager(  776): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
E/Zygote  ( 7904): MountEmulatedStorage()
E/Zygote  ( 7904): v2
I/libpersona( 7904): KNOX_SDCARD checking this for 10023
I/libpersona( 7904): KNOX_SDCARD not a persona
I/ActivityManager(  776): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7904 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
I/art     ( 2228): Explicit concurrent mark sweep GC freed 38236(2MB) AllocSpace objects, 9(144KB) LOS objects, 25% free, 22MB/30MB, paused 885us total 109.205ms
D/ResourcesManager( 1425): creating new AssetManager and set to /system/priv-app/StoryAlbumWidget/StoryAlbumWidget.apk
W/ResourcesManager( 1425): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1425): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
D/ResourcesManager(  776): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
I/DBG_DM  ( 3580): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
D/ResourcesManager(  776): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager(  776): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(  776): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager(  776): creating new AssetManager and set to /system/app/Books/Books.apk
I/SELinux ( 7904): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7904): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7904): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/SecContentProvider2(  776): uri = 14 selection = getSealedState
D/SecContentProvider2(  776): mCursor = null
D/ResourcesManager( 1425): creating new AssetManager and set to /system/app/AccuweatherPhone2013_H_LMR/AccuweatherPhone2013_H_LMR.apk
W/ResourcesManager( 1425): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1425): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1425): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
D/ResourcesManager(  776): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ApplicationPolicy(  776): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy(  776): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/ResourcesManager( 1425): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
D/ResourcesManager(  776): creating new AssetManager and set to /system/app/Drive/Drive.apk
W/ResourcesManager( 1425): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1425): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
I/DBG_DM  ( 3580): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 18
D/ResourcesManager(  776): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
I/DBG_DM  ( 3580): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
D/ResourcesManager(  776): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
I/DBG_DM  ( 3580): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 3580): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false
I/DBG_DM  ( 3580): [IIlllIlIIlIllIlllIll(376/llIIllllIIlllIIIIlll)] 
I/DBG_DM  ( 3580): [IIlllIlIIlIllIlllIll(397/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
D/ActivityManager(  776): post active user change for 0
D/KnoxTimeoutHandler(  776): postActiveUserChange for user 0
D/ResourcesManager(  776): creating new AssetManager and set to /system/app/Music2/Music2.apk
I/DBG_DM  ( 3580): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
D/TimaKeyStoreProvider( 7904): TimaSignature is unavailable
I/SurfaceFlinger(  254): id=16 createSurf (1080x1920),2 flag=404, YUIInstallC
D/ActivityThread( 7904): Added TimaKeyStore provider
D/StatusBarManagerService(  776): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  776): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon(  776): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  776): setMouseCustomIcon IconType is same.101
D/PointerIcon(  776): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  776): setHoveringSpenCustomIcon IconType is same.1
V/ActivityThread( 3580): updateVisibility : ActivityRecord{cb738a token=android.os.BinderProxy@23c745a3 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
D/ResourcesManager(  776): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/InputMethodManagerService(  776): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/InputMethodManagerService(  776): Got RemoteException sending setActive(false) notification to pid 7090 uid 10294
W/ContextImpl(  776): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/ResourcesManager( 7904): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
D/ResourcesManager(  776): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/ResourcesManager(  776): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
I/Timeline( 3580): Timeline: Activity_idle id: android.os.BinderProxy@23c745a3 time:1973589
D/ResourcesManager(  776): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ResourcesManager(  776): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/SecContentProvider2(  776): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  776): mCursor = null
D/RegisteredServicesCache( 1409): empty dynamic service
I/KLMS-2.4.511: ( 7904): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
W/ActivityManager(  776): mDVFSHelper.release()
I/Timeline(  776): Timeline: Activity_windows_visible id: ActivityRecord{345022f3 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t2} time:1973611
I/KLMS-2.4.511: ( 7904): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1450234907208
D/RCPManagerService(  776): PackageReceiver onReceive()
I/HarmonyEASService(  776): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/KLMS-2.4.511: ( 7904): MainReciver(): PACKAGE_REMOVED
D/KnoxMUMContainerPolicy(  776): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  776): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  776): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  776): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  776): uID is 10294
V/EnterpriseBillingPolicy(  776): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  776): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  776): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  776): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  776): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  776): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  776): getBillingProfileForVpnEngine - end - null
I/KLMS-2.4.511: ( 7904): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
D/KnoxTimeoutHandler(  776): handleActiveUserChange for user 0
D/TaskPersister(  776): removeObsoleteFile: deleting file=4_task.xml
D/TaskPersister(  776): removeObsoleteFile: deleting file=2_task.xml
D/StatusBar( 1186): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
D/PersonaManager( 1186): isKioskContainerExistOnDevice
D/PersonaManager( 1186): isKioskContainerExistOnDevice
D/PanelView( 1186): There is/are notification(s) 
D/PanelView( 1186): There is/are notification(s) 
D/ResourcesManager(  776): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager(  776): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
D/ResourcesManager(  776): creating new AssetManager and set to /system/app/talkback/talkback.apk
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  776): checkUser: useridlist=null, currentuser=0
D/EnterpriseDeviceManagerService(  776): Package has changed for user 0
D/EnterpriseDeviceManagerService(  776): Admin package name: com.google.android.gms
D/ResourcesManager(  776): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
W/Resources(  776): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  776): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
W/Resources(  776): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  776): creating new AssetManager and set to /system/app/Books/Books.apk
E/Zygote  ( 7924): MountEmulatedStorage()
E/Zygote  ( 7924): v2
I/libpersona( 7924): KNOX_SDCARD checking this for 10116
I/libpersona( 7924): KNOX_SDCARD not a persona
D/ResourcesManager(  776): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  776): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
I/ActivityManager(  776): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7924 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  776): Killing 7414:com.android.chrome/u0a104 (adj 15): empty for 1808s
W/Resources(  776): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  776): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/ResourcesManager(  776): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
I/art     (  776): Explicit concurrent mark sweep GC freed 25825(1971KB) AllocSpace objects, 10(160KB) LOS objects, 17% free, 37MB/45MB, paused 1.774ms total 291.014ms
I/SELinux ( 7924): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7924): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
D/ResourcesManager(  776): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
E/SELinux ( 7924): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/Resources(  776): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  776): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
W/Resources(  776): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  776): creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
D/TimaKeyStoreProvider( 7924): TimaSignature is unavailable
D/ActivityThread( 7924): Added TimaKeyStore provider
W/Resources(  776): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  776): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  776): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/Resources(  776): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  776): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  776): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  776): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  776): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
W/Resources(  776): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  776): creating new AssetManager and set to /system/app/Maps/Maps.apk
D/ResourcesManager(  776): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
E/SMD     (  289): DCD ON
D/ResourcesManager(  776): creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
D/ResourcesManager(  776): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
W/libprocessgroup(  776): failed to open /acct/uid_10104/pid_7414/cgroup.procs: No such file or directory
W/Resources(  776): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  776): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  776): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
W/ResourcesManager(  776): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  776): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  776): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources(  776): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  776): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/ResourcesManager( 7924): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/ResourcesManager(  776): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
D/ResourcesManager(  776): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/PackageManager(  776): delete codoeFile: 
I/AASAUninstall(  776):  com.test.thalitest not target!
D/PackageManager(  776): result of delete: 1{876531327}
D/AndroidRuntime( 7849): Shutting down VM
D/elm:14491( 7924): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/ResourcesManager(  776): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
D/elm:14491( 7924): ELMEngine.ELMEngine( context ).
D/elm:14491( 7924): MDMBridge.setEnterpriseBridge()
W/Resources(  776): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  776): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk

```
