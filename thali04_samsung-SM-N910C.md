#### Test 54312298c831015_thali04_samsung-SM-N910C Logs


```
--------- beginning of main
I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/AndroidRuntime(11746): 
D/AndroidRuntime(11746): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11746): CheckJNI is OFF
D/AndroidRuntime(11746): readGMSProperty: start
D/AndroidRuntime(11746): readGMSProperty: already setted!!
D/AndroidRuntime(11746): readGMSProperty: end
D/AndroidRuntime(11746): addProductProperty: start
E/AffinityControl(11746): AffinityControl: registerfunction enter
D/AndroidRuntime(11746): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3516): inState():  stateMachine is null !!
I/PersonaManagerService( 3516): PersonaId don't exist
I/ActivityManager( 3516): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3516): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
I/ActivityManager( 3516): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3516): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager( 3516): mDVFSHelper.acquire()
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/Zygote  (11764): MountEmulatedStorage()
E/Zygote  (11764): v2
I/libpersona(11764): KNOX_SDCARD checking this for 10523
I/libpersona(11764): KNOX_SDCARD not a persona
I/SELinux (11764): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3516): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=11764 uid=10523 gids={50523, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux (11764): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11764): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(11746): Shutting down VM
D/PointerIcon( 3516): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3516): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3516): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3516): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(11764): TimaSignature is unavailable
D/ActivityThread(11764): Added TimaKeyStore provider
I/SurfaceFlinger( 2849): id=11 Removed YUIInstallC (5/8)
I/SurfaceFlinger( 2849): id=11 Removed YUIInstallC (-2/8)
D/ResourcesManager(11764): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
V/ActivityThread( 6198): updateVisibility : ActivityRecord{d97ae37 token=android.os.BinderProxy@35e6b278 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
I/WebViewFactory(11764): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(11764): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(11764): Loading: webviewchromium
I/LibraryLoader(11764): Time to load native libraries: 3 ms (timestamps 6852-6855)
I/LibraryLoader(11764): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider(11764): Binding Chromium to main looper Looper (main, tid 1) {1a2fe046}
I/LibraryLoader(11764): Expected native library version number "",actual native library version number ""
I/chromium(11764): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(11764): Initializing chromium process, renderers=0
,W/art     (11764): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(11764): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(11764): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(11764): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,W/chromium(11764): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(11764): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (11764): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(11764): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(11764): CordovaWebView is running on device made by: samsung
,W/art     (11764): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11764): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity(11764): performCreate Call secproduct feature valuefalse
D/Activity(11764): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(11764): Render dirty regions requested: true
,D/ActivityManager( 3516): post active user change for 0
D/KnoxTimeoutHandler( 3516): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3516): handleActiveUserChange for user 0
,I/SurfaceFlinger( 2849): id=14 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService( 3516): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3516): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3516): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3516): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3516): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3516): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer(11764): Initialized EGL, version 1.4
,I/OpenGLRenderer(11764): HWUI protection enabled for context ,  &this =0xaf6641a0 ,&mEglDisplay = 1 , &mEglConfig = -1278639856 
,D/OpenGLRenderer(11764): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(11764): Enabling debug mode 0
D/mali_winsys(11764): new_window_surface returns 0x3000,  [1440x2560]-format:1
,V/ActivityThread(11764): updateVisibility : ActivityRecord{34d6e6f6 token=android.os.BinderProxy@39da42a5 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/InputMethodManagerService( 3516): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3516): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ContextImpl( 3516): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 3516): mDVFSHelper.release()
I/Timeline( 3516): Timeline: Activity_windows_visible id: ActivityRecord{28239c87 u0 com.test.thalitest/.MainActivity t26} time:137202
,W/IInputConnectionWrapper(11764): showStatusIcon on inactive InputConnection
,I/Timeline(11764): Timeline: Activity_idle id: android.os.BinderProxy@39da42a5 time:137211
,I/chromium(11764): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11764): 
,D/JsMessageQueue(11764): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log(11764): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1357424896
D/JX-Cordova(11764): jxcore cordova android initializing
,W/jxcore-log(11764): Initializing JXcore engine
W/jxcore-log(11764): JXcore engine is ready
,W/jxcore-log(11764): Starting JXcore engine
,E/auditd  ( 4619): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3516): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl( 3516): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3516): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(11764): Platform android
W/jxcore-log(11764): 
W/jxcore-log(11764): Process ARCH arm
W/jxcore-log(11764): 
,I/jxcore-log(11764): JXcore Cordova bridge is ready!
I/jxcore-log(11764): 
,W/jxcore-log(11764): JXcore engine is started
,I/jxcore-log(11764): Toggling radios to true
I/jxcore-log(11764): 
,D/BluetoothAdapter(11764): enable()
,D/BluetoothAdapter(11764): enable(): BT is already enabled..!
,D/WifiService( 3516): New client listening to asynchronous messages
,I/WifiManager(11764): packageName : com.test.thalitest
,D/SecContentProvider( 3516): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3516): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3516): mCursor = null
,D/WifiService( 3516): setWifiEnabled: true pid=11764, uid=10523
E/WifiService( 3516): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3516): Permission Denial: getCurrentUser() from pid=11764, uid=10523 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 3516): Failed getting userId using ActivityManagerNative
W/WifiService( 3516): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=11764, uid=10523 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3516): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3516): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3516): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3516): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3516): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider( 3516): name = wifi_on
,I/WifiService( 3516): disconnect: pid=11764, uid=10523
,I/wpa_supplicant( 3835): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log(11764): Radios toggled
I/jxcore-log(11764): 
,I/jxcore-log(11764): Got Device Bluetooth address: E0:DB:10:14:E2:C0
I/jxcore-log(11764): 
,I/wpa_supplicant( 3835): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/jxcore-log(11764): Perf Test app loaded loaded
I/jxcore-log(11764): 
I/wpa_supplicant( 3835): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 3835): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3835): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine( 3516): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 3835): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3835): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3835): Disconnected - do not scan
I/wpa_supplicant( 3835): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine( 3516): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3516): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3516): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3516): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/jxcore-log(11764): check test folder
I/jxcore-log(11764): 
,I/jxcore-log(11764): found test : ./testFindPeers.js
I/jxcore-log(11764): 
,E/WifiStateMachine( 3516): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3516): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3516): do suspend true
,D/WifiP2pService( 3516): InactiveState{ what=143375 }
,D/WifiP2pService( 3516): P2pEnabledState{ what=143375 }
,D/CommandListener( 2845): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,E/Netd    ( 2845): ifc_reset_connections failed on iface wlan0 for address 192.168.1.124/24 (Unknown error -1)
,I/jxcore-log(11764): found test : ./testSendData.js
I/jxcore-log(11764): 
E/WifiStateMachine( 3516): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/ConnectivityService( 3516): updateNetworkInfo()
,E/WifiConfigStore( 3516): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 3516): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3516): updateNetworkInfo()
D/ConnectivityService( 3516): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,I/WifiTrafficPoller( 3516): evaluateTrafficStatsPolling
,E/WifiStateMachine( 3516): Start Disconnecting Watchdog 1
I/wpa_supplicant( 3835): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3835): P2P: Current p2p state = IDLE
I/wpa_supplicant( 3835): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 3835): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3835): First Scan Start
D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
I/wpa_supplicant( 3835): Scan requested (ret=0) - scan timeout 30 seconds
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
E/WifiStateMachine( 3516): ConnectModeState: Network connection lost 
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
I/Hs20UtilService( 4082): Starting #8
E/WifiStateMachine( 3516): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - processMessage - processMsg
I/Hs20UtilService( 4082): Message received 5007
E/WifiStateMachine( 3516): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
D/NearbySettings( 8607): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 8607): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings( 8607): MountReceiver.onReceive - Create mPrefHandler
E/WifiStateMachine( 3516): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3516): do suspend true
,D/NearbySettings( 8607): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8607): DMSUtil.isNetworkConnected - flag-null, state-null
,D/WifiP2pService( 3516): InactiveState{ what=143375 }
D/WifiP2pService( 3516): P2pEnabledState{ what=143375 }
,I/NearbySettings( 8607): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/jxcore-log(11764): found test : ./testSendData2.js
I/jxcore-log(11764): 
,D/WifiService( 3516): New client listening to asynchronous messages
,E/jxcore  (11764): Error!: missing ) after argument list
E/jxcore  (11764): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":"30","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:74:21"}]
I/Choreographer(11764): Skipped 45 frames!  The application may be doing too much work on its main thread.
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
I/NearbySettings( 8607): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8607): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8607): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 8607): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11367): NETWORK_STATE_CHANGED_ACTION
,I/chromium(11764): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/CommandListener( 2845): Clearing all IP addresses on wlan0
,D/ConnectivityService( 3516): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,E/WifiStateMachine( 3516): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/EntConnectivity( 3516): Not allowed due to - mEnabled false
I/chromium(11764): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
D/ConnectivityManager.CallbackHandler( 3692): CM callback handler got msg 524292
D/ConnectivityService( 3516): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3516): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 3516): updateConfiguredNetworkExpiration - currTime: 1450738955606
D/WifiStateMachine( 3516): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
E/WifiStateMachine( 3516): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine( 3516): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityManager.CallbackHandler( 6696): CM callback handler got msg 524292
D/CSLegacyTypeTracker( 3516): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 3516): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 3516): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/TelephonyNetworkFactory( 3983): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine( 3516): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3516): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent( 3516): NetworkAgent: NetworkAgent channel lost
I/WifiTrafficPoller( 3516): evaluateTrafficStatsPolling
,E/WifiStateMachine( 3516): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3516): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
,E/WifiStateMachine( 3516): setDetailed state send new extra info"NG700"
D/SecContentProvider2( 3516): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3516): mCursor = null
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
,D/Tethering( 3516): MasterInitialState.processMessage what=3
D/EntConnectivity( 3516): Not allowed due to - mEnabled false
,D/SmartBondingService( 3516): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 3516): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/SmartBondingService( 3516): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3516): getSBEnabled() enabled =false
D/SmartBondingService( 3516): getSBEnabled() enabled =false
D/SmartBondingService( 3516): getSBEnabled() enabled =false
V/NetworkStats( 3516): updateIfacesLocked()
,V/NetworkStats( 3516): performPollLocked(flags=0x1)
D/NtpTrustedTime( 3516): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3692): updateDataNetType()
D/StatusBar.NetworkController( 3692): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3692): updateLTEICONDataNetType:0
D/NetworkStatsFactory( 3516): UpdateStatsForKnox
,D/SmartBondingService( 3516): getNetworkEnabled : wifi : true mobile : false
,V/NetworkStats( 3516): performPollLocked() took 3ms
D/NtpTrustedTime( 3516): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3516): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3516): currentTimeMillis() cache hit
D/NtpTrustedTime( 3516): currentTimeMillis() cache hit
D/NtpTrustedTime( 3516): currentTimeMillis() cache hit
V/NetworkStats( 3516): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/StatusBar.NetworkController( 3692): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3692): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3692): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,I/Hs20UtilService( 4082): Starting #9
I/Hs20UtilService( 4082): Message received 5007
,D/SecContentProvider2( 3516): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3516): mCursor = null
,D/NtpTrustedTime( 3516): currentTimeMillis() cache hit
D/NtpTrustedTime( 3516): currentTimeMillis() cache hit
,D/NearbySettings( 8607): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8607): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8607): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 8607): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8607): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8607): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8607): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11367): NETWORK_STATE_CHANGED_ACTION
,D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
,D/ConnectivityService( 3516): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/ApplicationPolicy( 3516): updateDataUsageMap
I/ApplicationPolicy( 3516): updateDataUsageMap  idList is null 
D/SmartBondingService( 3516): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3516): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3516): getSBEnabled() enabled =false
D/SmartBondingService( 3516): getSBEnabled() enabled =false
D/SmartBondingService( 3516): getSBEnabled() enabled =false
D/SmartBondingService( 3516): getNetworkEnabled : wifi : true mobile : false
D/GpsLocationProvider( 3516): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
W/SLocation( 3516): No Active Data Connection
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
I/DBG_DM  ( 6198): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
I/DBG_DM  ( 6198): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
E/Zygote  (11863): MountEmulatedStorage()
E/Zygote  (11863): v2
I/libpersona(11863): KNOX_SDCARD checking this for 10110
I/libpersona(11863): KNOX_SDCARD not a persona
I/SELinux (11863): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3516): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.iorg.vpn.cleanup.NetworkStateMonitor: pid=11863 uid=10110 gids={50110, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/SELinux (11863): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11863): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider(11863): TimaSignature is unavailable
D/ActivityThread(11863): Added TimaKeyStore provider
D/ResourcesManager(11863): creating new AssetManager and set to /data/app/com.facebook.appmanager-2/base.apk
D/ACRA    (11863): ACRA is enabled for com.facebook.appmanager, intializing...
I/DexLibLoader(11863): not using cross-dex optimization: ART in use
I/art     (11863): Thread[1,tid=11863,WaitingForJniOnLoad,Thread*=0xb4e08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/app/com.facebook.appmanager-2/lib/arm/libfbjni.so"
V/DexLibLoader(11863): about to lock: /data/data/com.facebook.appmanager/mdex_lock
V/DexLibLoader(11863): locking /data/data/com.facebook.appmanager/mdex_lock took 0 ms
V/DexLibLoader(11863): Secondary program dex metadata: classes2.dex 29f80981f469a774a4884b3db2df17e0be227159 secondary.dex01.Canary
D/DexLibLoader(11863): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex" is valid
D/DexLibLoader(11863): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex_opt" is valid
W/art     (11863): Attempt to remove local handle scope entry from IRT, ignoring
D/DexLibLoader(11863): loading pre-built fallback odex files
V/MultiDexClassLoader(11863): installing MultiDexClassLoader before application classloader
D/DexLibLoader(11863): released odex store lock
D/DexLibLoader(11863): DexLibLoader.loadAll took 36 ms
W/ca      (11863): Verify
W/LightSharedPreferencesImpl(11863): Failed to load preference file from Disk!
W/LightSharedPreferencesImpl(11863): java.io.FileNotFoundException: /data/data/com.facebook.appmanager/app_light_prefs/com.facebook.appmanager/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11863): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/LightSharedPreferencesImpl(11863): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/LightSharedPreferencesImpl(11863): 	at com.facebook.crudolib.b.k.a(LightSharedPreferencesStorage.java:56)
W/LightSharedPreferencesImpl(11863): 	at com.facebook.crudolib.b.g.run(LightSharedPreferencesImpl.java:61)
W/LightSharedPreferencesImpl(11863): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/LightSharedPreferencesImpl(11863): 	at com.facebook.common.executors.dj.run(WrappingExecutorService.java:77)
W/LightSharedPreferencesImpl(11863): 	at com.facebook.common.executors.u.run(DefaultConstrainedListeningExecutorService.java:327)
W/LightSharedPreferencesImpl(11863): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/LightSharedPreferencesImpl(11863): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/LightSharedPreferencesImpl(11863): 	at com.facebook.common.executors.cc.run(NamedThreadFactory.java:42)
W/LightSharedPreferencesImpl(11863): 	at java.lang.Thread.run(Thread.java:818)
W/LightSharedPreferencesImpl(11863): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11863): 	at libcore.io.Posix.open(Native Method)
W/LightSharedPreferencesImpl(11863): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/LightSharedPreferencesImpl(11863): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/LightSharedPreferencesImpl(11863): 	... 10 more
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/Zygote  (11892): MountEmulatedStorage()
E/Zygote  (11892): v2
I/libpersona(11892): KNOX_SDCARD checking this for 1000
I/libpersona(11892): KNOX_SDCARD not a persona
I/SELinux (11892): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11892): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3516): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=11892 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (11892): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3516): Killing 10949:com.sec.android.app.myfiles/u0a53 (adj 15): bgCount ##31
W/appmanager(:<default>):b(11863): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
I/wpa_supplicant( 3835): nl80211: Received scan results (10 BSSes)
I/wpa_supplicant( 3835): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3835): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3835): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 3835): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
E/WifiStateMachine( 3516): [1,450,738,956,664 ms] noteScanEnd no scan source
E/WifiStateMachine( 3516): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@89a22eb sup_state=SCANNING debouncing=false
W/appmanager(:<default>):b(11863): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
E/WifiStateMachine( 3516): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3516): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3516): setDetailed state send new extra info
D/SecContentProvider2( 3516): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3516): mCursor = null
D/TimaKeyStoreProvider(11892): TimaSignature is unavailable
D/ActivityThread(11892): Added TimaKeyStore provider
D/ResourcesManager(11892): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
I/PCWCLIENTTRACE_LOG(11892): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(11892): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(11892): new DMDBOpenHelper instance
I/wpa_supplicant( 3835): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 3835): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 3835): Associated with C0.AA.48
E/WifiStateMachine( 3516): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3516): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
I/PCWCLIENTTRACE_PushUtil(11892): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11892): sales region : global
I/PCWCLIENTTRACE_PushUtil(11892): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11892): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
E/WifiStateMachine( 3516): setDetailed state send new extra info"NG700"
I/PCWCLIENTTRACE_SYSTEMReceiver(11892): noConnectivity : true
D/SecContentProvider2( 3516): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3516): mCursor = null
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
W/appmanager(:<default>):QuickExperimentControllerImpl(11863): Exposure of experiment com.facebook.common.network.l@170bbdec occurred when no user was logged in
E/Zygote  (11914): MountEmulatedStorage()
E/Zygote  (11914): v2
I/libpersona(11914): KNOX_SDCARD checking this for 10135
I/libpersona(11914): KNOX_SDCARD not a persona
I/SELinux (11914): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11914): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3516): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=11914 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (11914): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/wpa_supplicant( 3835): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
W/BroadcastQueue( 3516): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{3b133a0a u0 ReceiverList{2e8eba75 11863 com.facebook.appmanager/10110/u0 remote:247d9dac}}
I/wpa_supplicant( 3835): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
W/BroadcastQueue( 3516): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{3b133a0a u0 ReceiverList{2e8eba75 11863 com.facebook.appmanager/10110/u0 remote:247d9dac}}
I/ActivityManager( 3516): Killing 10966:com.policydm/1000 (adj 15): bgCount ##31
E/WifiStateMachine( 3516): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3516): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
D/SecContentProvider2( 3516): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3516): mCursor = null
I/wpa_supplicant( 3835): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
I/wpa_supplicant( 3835): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 3835): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
E/WifiStateMachine( 3516): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
I/wpa_supplicant( 3835): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3835): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
E/WifiStateMachine( 3516): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
I/wpa_supplicant( 3835): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 3835): Blacklist: Clear (temp) 
I/wpa_supplicant( 3835): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/SecContentProvider2( 3516): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3516): mCursor = null
E/WifiStateMachine( 3516): Network connection established
D/WifiNative-HAL( 3516): callSECApiVoid - ID [50]
E/WifiStateMachine( 3516): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
E/WifiStateMachine( 3516): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
D/TimaKeyStoreProvider(11914): TimaSignature is unavailable
D/ActivityThread(11914): Added TimaKeyStore provider
D/ConnectivityService( 3516): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine( 3516): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3516): L2ConnectedState "NG700" nid=0
D/ConnectivityService( 3516): hsengiv:checkWhatTypeOfNetwork and the value is false
E/WifiConfigStore( 3516): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/ConnectivityService( 3516): updateNetworkInfo()
D/ConnectivityService( 3516): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
E/WifiStateMachine( 3516): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine( 3516): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3516): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3516): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ResourcesManager(11914): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/CommandListener( 2845): Setting iface cfg
E/WifiStateMachine( 3516): Start Dhcp Watchdog 2
,E/WifiStateMachine( 3516): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine( 3516): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,W/BroadcastQueue( 3516): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{23137874 u0 ReceiverList{168ca847 11863 com.facebook.appmanager/10110/u0 remote:1dbe3786}}
,E/WifiStateMachine( 3516): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3516): do suspend false
,D/SecContentProvider2( 3516): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3516): mCursor = null
D/WifiP2pService( 3516): InactiveState{ what=143375 }
,D/WifiP2pService( 3516): P2pEnabledState{ what=143375 }
,I/MusicStore(11914): Database version: 104
,D/ResourcesManager(11914): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11914): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11914): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (11914): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(11914): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (11914): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2a088d3a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(11914): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(11914): GMSCore installation verified
,I/ConfigStore(11914): Config Database version: 1
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11914): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/dhcpcd  (11951): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (11951): version 5.5.6 starting
,E/dhcpcd  (11951): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11914): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11914): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter( 3516): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3516): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3516): getStreamVolume 3 index 0
,I/MediaRouter(11914): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/dhcpcd  (11951): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (11951): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (11951): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  (11951): bssid match
,I/dhcpcd  (11951): wlan0: rebinding lease of 192.168.1.124
,E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11958): MountEmulatedStorage()
E/Zygote  (11958): v2
I/libpersona(11958): KNOX_SDCARD checking this for 10002
I/libpersona(11958): KNOX_SDCARD not a persona
,I/SELinux (11958): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3516): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=11958 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (11958): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11958): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11958): TimaSignature is unavailable
,D/ActivityThread(11958): Added TimaKeyStore provider
,I/art     ( 3516): Explicit concurrent mark sweep GC freed 61586(3MB) AllocSpace objects, 14(224KB) LOS objects, 24% free, 49MB/65MB, paused 2.484ms total 151.462ms
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11863): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11863): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,D/ResourcesManager(11958): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,D/WifiDisplayAdapter( 3516): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/NetworkMonitor(11914): type=WIFI subType= reason=null isConnected=false
,I/ActivityManager( 3516): Killing 10981:com.sec.android.provider.badge/u0a82 (adj 15): bgCount ##31
,W/appmanager(:<default>):QuickExperimentControllerImpl(11863): Exposure of experiment com.facebook.imagepipeline.a.g@223f8935 occurred when no user was logged in
,W/appmanager(:<default>):QuickExperimentControllerImpl(11863): Exposure of experiment com.facebook.imagepipeline.a.d@6ba3096 occurred when no user was logged in
,I/ActivityManager( 3516): Killing 11018:com.sec.spp.push/u0a39 (adj 15): bgCount ##31
,E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11978): MountEmulatedStorage()
E/Zygote  (11978): v2
I/libpersona(11978): KNOX_SDCARD checking this for 1000
I/libpersona(11978): KNOX_SDCARD not a persona
,I/SELinux (11978): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11978): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3516): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=11978 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux (11978): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (11863): Explicit concurrent mark sweep GC freed 46702(2MB) AllocSpace objects, 6(96KB) LOS objects, 22% free, 27MB/35MB, paused 1.233ms total 51.140ms
,W/appmanager(:<default>):m(11863): No feature status reporters found; is this dead code?
,D/TimaKeyStoreProvider(11978): TimaSignature is unavailable
,D/ActivityThread(11978): Added TimaKeyStore provider
,D/ResourcesManager(11978): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT(11978): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT(11978): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT(11978): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT(11978): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(11978): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11997): MountEmulatedStorage()
E/Zygote  (11997): v2
I/libpersona(11997): KNOX_SDCARD checking this for 10012
I/libpersona(11997): KNOX_SDCARD not a persona
,I/SELinux (11997): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11997): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11997): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3516): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=11997 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 8733(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 868us total 21.301ms
,D/TimaKeyStoreProvider(11997): TimaSignature is unavailable
,D/ActivityThread(11997): Added TimaKeyStore provider
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 840us total 18.497ms
,D/ResourcesManager(11997): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 626us total 19.312ms
,I/ActivityManager( 3516): Killing 11001:com.sec.android.app.soundalive/u0a59 (adj 15): bgCount ##31
,E/lowmemorykiller( 2828): Error writing /proc/11001/oom_score_adj; errno=22
,I/FOTA_Client(11997): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(11997): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(11997): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12013): MountEmulatedStorage()
E/Zygote  (12013): v2
I/libpersona(12013): KNOX_SDCARD checking this for 10021
I/libpersona(12013): KNOX_SDCARD not a persona
,I/SELinux (12013): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12013): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3516): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=12013 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
,E/SELinux (12013): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3516): Killing 10827:com.google.android.apps.docs/u0a101 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12013): TimaSignature is unavailable
,D/ActivityThread(12013): Added TimaKeyStore provider
,D/ResourcesManager(12013): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.521: (12013): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Dec 22 00:02:38 GMT+01:00 2015
,I/KLMS-2.4.521: (12013): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (12013): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12013): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (12013): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (12013): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (12013): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (12013): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.521: (12013): StateImplV2(): networkChangeListener().END
,E/Zygote  (12030): MountEmulatedStorage()
E/Zygote  (12030): v2
I/libpersona(12030): KNOX_SDCARD checking this for 10038
I/libpersona(12030): KNOX_SDCARD not a persona
,I/SELinux (12030): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12030): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3516): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=12030 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
E/SELinux (12030): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.4.521: (12013): KLMSIntentService(): onDestroy()
,I/ActivityManager( 3516): Killing 11042:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12030): TimaSignature is unavailable
,D/ActivityThread(12030): Added TimaKeyStore provider
,D/ResourcesManager(12030): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT(12030): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12045): MountEmulatedStorage()
E/Zygote  (12045): v2
I/libpersona(12045): KNOX_SDCARD checking this for 1000
I/libpersona(12045): KNOX_SDCARD not a persona
,I/SELinux (12045): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12045): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3516): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=12045 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux (12045): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3516): Killing 11097:com.wsomacp/u0a28 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12045): TimaSignature is unavailable
,D/ActivityThread(12045): Added TimaKeyStore provider
,D/ResourcesManager(12045): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12065): MountEmulatedStorage()
I/libpersona(12065): KNOX_SDCARD checking this for 10039
E/Zygote  (12065): v2
I/libpersona(12065): KNOX_SDCARD not a persona
,I/SELinux (12065): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12065): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3516): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=12065 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (12065): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3516): Killing 11056:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
,E/lowmemorykiller( 2828): Error writing /proc/11056/oom_score_adj; errno=22
,I/dhcpcd  (11951): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
,D/TimaKeyStoreProvider(12065): TimaSignature is unavailable
,D/ActivityThread(12065): Added TimaKeyStore provider
,D/ResourcesManager(12065): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,I/dhcpcd  (11951): wlan0: leased 192.168.1.124 for 86400 seconds
,E/WifiStateMachine( 3516): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3516): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/SPPClientService(12065): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(12065): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService(12065): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,D/SPPClientService(12065): PushLog.txt file is not deleted.
D/SPPClientService(12065): PushLog.txt file is not deleted.
D/SPPClientService(12065): ============PushLog. stop!
,I/SA      (11161): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11161): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      (11161): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      (11161): [SLFUCHKMGR] constructor called
,E/SPPClientService(12065): [[SystemStateMonitorService]] No Active Internet
,I/SA      (11161): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11161): [OR] == isSIMCardReady false ==
,I/SA      (11161): [SCU] == networkStateCheck == false
I/SA      (11161): [OR] onReceive END
,V/DownloadManager( 3715): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager( 3516): Killing 11125:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
,E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12093): MountEmulatedStorage()
,E/Zygote  (12093): v2
I/libpersona(12093): KNOX_SDCARD checking this for 10067
I/libpersona(12093): KNOX_SDCARD not a persona
,I/SELinux (12093): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3516): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=12093 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux (12093): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12093): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12093): TimaSignature is unavailable
,D/ActivityThread(12093): Added TimaKeyStore provider
,D/ResourcesManager(12093): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/sCloudBackupApp(12093): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(12093): Other Intent
,I/ActivityManager( 3516): Killing 11076:com.sec.android.automotive.drivelink/u0a102 (adj 13): bgCount ##31
,D/accuweather( 5200): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3776): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 6
,D/accuweather( 5200): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5200): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5200): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5200): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5200): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5200): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12122): MountEmulatedStorage()
E/Zygote  (12122): v2
I/libpersona(12122): KNOX_SDCARD checking this for 1000
I/libpersona(12122): KNOX_SDCARD not a persona
,I/SELinux (12122): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12122): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3516): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=12122 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux (12122): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12122): TimaSignature is unavailable
,D/ActivityThread(12122): Added TimaKeyStore provider
,D/ResourcesManager(12122): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(12122): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro(12122): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro(12122): premStatus:2
,I/KnoxUsageLogPro(12122): isEulaShown : false
I/KnoxUsageLogPro(12122): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
,E/WifiStateMachine( 3516): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine( 3516): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  ( 3516): do suspend true
,E/Zygote  (12137): MountEmulatedStorage()
E/Zygote  (12137): v2
I/libpersona(12137): KNOX_SDCARD checking this for 10090
I/libpersona(12137): KNOX_SDCARD not a persona
,I/SELinux (12137): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/WifiP2pService( 3516): InactiveState{ what=143375 }
D/WifiP2pService( 3516): P2pEnabledState{ what=143375 }
,I/ActivityManager( 3516): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=12137 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (12137): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12137): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3516): Killing 11220:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,E/WifiStateMachine( 3516): WifiStateMachine DHCP successful
,E/WifiStateMachine( 3516): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine( 3516): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine( 3516): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3516): Not connected state, yet.
E/WifiStateMachine( 3516): VerifyingLinkState enter
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiStateMachine( 3516): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine( 3516): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3516): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3516): callSECApiInt - ID [210]
,E/WifiStateMachine( 3516): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService( 3516): updateNetworkInfo()
,D/ConnectivityService( 3516): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 3516): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 3516): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 3516): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 3516): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker( 3516): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3516): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3516): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine( 3516): Now, connected state.
E/WifiStateMachine( 3516): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/WifiStateMachine( 3516): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/WifiTrafficPoller( 3516): evaluateTrafficStatsPolling
,E/WifiStateMachine( 3516): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/TimaKeyStoreProvider(12137): TimaSignature is unavailable
,D/ActivityThread(12137): Added TimaKeyStore provider
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
I/WifiTrafficPoller( 3516): evaluateTrafficStatsPolling
,D/WifiNative-HAL( 3516): callSECApiVoid - ID [212]
,D/ConnectivityService( 3516): Adding Route [fe80::/64 -> :: wlan0] to network 503
E/WifiStateMachine( 3516): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/ConnectivityService( 3516): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,I/WifiStateMachine( 3516): REQUEST_POWER_SAVE_ON
D/ConnectivityService( 3516): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService( 3516): Unexpected mtu value: 0, wlan0
,V/        ( 2845): QcRouteController
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,V/        ( 2845): QcRouteController
,D/ResourcesManager(12137): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,V/        ( 2845): QcRouteController
,V/        ( 2845): QcRouteController
,V/        ( 2845): QcRouteController
,V/        ( 2845): QcRouteController
,V/        ( 2845): QcRouteController
,V/        ( 2845): QcRouteController
,E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService( 3516): Setting Dns servers for network 503 to [/192.168.1.1]
,D/ConnectivityService( 3516): LTETest block dns file not exists
,E/Zygote  (12170): MountEmulatedStorage()
E/Zygote  (12170): v2
I/libpersona(12170): KNOX_SDCARD checking this for 10127
I/libpersona(12170): KNOX_SDCARD not a persona
,I/SELinux (12170): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3516): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=12170 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (12170): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3516): Killing 11203:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
,E/SELinux (12170): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ConnectivityService( 3516): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 3516): updateNetworkInfo()
E/ConnectivityService( 3516): updateNetworkInfo()
D/ConnectivityService( 3516): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 3516): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3516): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 3516): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3516): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3516): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3516): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService( 3516):    accepting network in place of null
,D/TelephonyNetworkFactory( 3983): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker( 3516): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 3516): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 3516): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/System.out( 3516): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 1000
,D/ConnectivityService( 3516): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService( 3516): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/EntConnectivity( 3516): Not allowed due to - mEnabled false
,D/ConnectivityManager.CallbackHandler( 3692): CM callback handler got msg 524290
,D/Tethering( 3516): MasterInitialState.processMessage what=3
D/SmartBondingService( 3516): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService( 3516): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3516): getSBEnabled() enabled =false
D/SmartBondingService( 3516): getSBEnabled() enabled =false
D/SmartBondingService( 3516): getSBEnabled() enabled =false
,V/NetworkStats( 3516): updateIfacesLocked()
D/NtpTrustedTime( 3516): currentTimeMillis() cache hit
V/NetworkStats( 3516): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 3516): UpdateStatsForKnox
,D/SmartBondingService( 3516): getNetworkEnabled : wifi : true mobile : false
,D/NtpTrustedTime( 3516): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3516): currentTimeMillis() cache hit
D/NtpTrustedTime( 3516): currentTimeMillis() cache hit
D/NtpTrustedTime( 3516): currentTimeMillis() cache hit
V/NetworkStats( 3516): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3692): updateDataNetType()
D/StatusBar.NetworkController( 3692): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3692): updateLTEICONDataNetType:0
D/ConnectivityManager.CallbackHandler( 6696): CM callback handler got msg 524290
V/NetworkStats( 3516): performPollLocked() took 10ms
D/NtpTrustedTime( 3516): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3516): currentTimeMillis() cache hit
D/NtpTrustedTime( 3516): currentTimeMillis() cache hit
D/TimaKeyStoreProvider(12170): TimaSignature is unavailable
,D/StatusBar.NetworkController( 3692): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3692): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3692): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/ActivityThread(12170): Added TimaKeyStore provider
D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/ResourcesManager(12170): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,D/KeyguardWallpaperUpdator(12170): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12170): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12170): stopCheckCategoryVersion
,E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
,I/System.out( 3516): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,E/Zygote  (12188): MountEmulatedStorage()
I/libpersona(12188): KNOX_SDCARD checking this for 10136
E/Zygote  (12188): v2
I/libpersona(12188): KNOX_SDCARD not a persona
,I/SELinux (12188): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12188): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3516): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=12188 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (12188): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3516): Killing 11237:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3516): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 21 Dec 2015 23:02:39 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450738959096], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450738959078]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3516): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3516): Validated
,D/ConnectivityService( 3516): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3516): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3516): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 3516): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3692): CM callback handler got msg 524290
,D/ConnectivityService( 3516): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 6696): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3692): updateDataNetType()
D/StatusBar.NetworkController( 3692): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3692): updateLTEICONDataNetType:0
D/TimaKeyStoreProvider(12188): TimaSignature is unavailable
,D/ActivityThread(12188): Added TimaKeyStore provider
,D/StatusBar.NetworkController( 3692): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3692): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3692): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/ResourcesManager(12188): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12188): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12188): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12188): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12188): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory(12188): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(12188): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,D/ConnectivityService( 3516): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3516): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3516): SmartBondingReceiver: wifi is connected
D/SmartBondingService( 3516): SmartBondingReceiver: wifi ap is not changed
,D/SmartBondingService( 3516): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService( 3516): getSBEnabled() enabled =false
,D/SmartBondingService( 3516): getSBEnabled() enabled =false
D/SmartBondingService( 3516): getSBEnabled() enabled =false
,D/SmartBondingService( 3516): getNetworkEnabled : wifi : true mobile : false
,I/DBG_DM  ( 6198): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 6198): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/NetworkMonitor(11914): type=WIFI subType= reason=null isConnected=true
,W/ResourceType( 5361): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5361): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/GpsLocationProvider( 3516): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/LibraryLoader(12188): Loading: webviewchromium
,I/LibraryLoader(12188): Time to load native libraries: 7 ms (timestamps 3461-3468)
,I/LibraryLoader(12188): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(12188): Binding Chromium to main looper Looper (main, tid 1) {38472ff4}
,I/LibraryLoader(12188): Expected native library version number "",actual native library version number ""
,I/chromium(12188): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,D/SecContentProvider2( 3516): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3516): mCursor = null
,I/BrowserStartupController(12188): Initializing chromium process, renderers=0
,W/art     (12188): Attempt to remove local handle scope entry from IRT, ignoring
,W/AudioManagerAndroid(12188): Requires BLUETOOTH permission
,W/chromium(12188): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(12188): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium(12188): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,I/NSApplication(12188): Starting up...
,E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12269): MountEmulatedStorage()
E/Zygote  (12269): v2
I/libpersona(12269): KNOX_SDCARD checking this for 10150
I/libpersona(12269): KNOX_SDCARD not a persona
,I/SELinux (12269): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12269): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3516): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=12269 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,E/SELinux (12269): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3516): Killing 11258:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12269): TimaSignature is unavailable
,D/ActivityThread(12269): Added TimaKeyStore provider
,D/ResourcesManager(12269): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(12269): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(12269): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12269): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect(12269): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12269): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect(12269): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12284): MountEmulatedStorage()
E/Zygote  (12284): v2
I/libpersona(12284): KNOX_SDCARD checking this for 10178
I/libpersona(12284): KNOX_SDCARD not a persona
,I/SELinux (12284): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12284): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12284): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3516): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=12284 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager( 3516): Killing 11274:com.samsung.helphub/1000 (adj 13): bgCount ##31
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 8752(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 863us total 22.046ms
,D/TimaKeyStoreProvider(12284): TimaSignature is unavailable
,D/ActivityThread(12284): Added TimaKeyStore provider
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.107ms total 19.342ms
,D/ResourcesManager(12284): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(12284): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager(12284): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12284): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12284): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(12284): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12284): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 625us total 18.540ms
,D/ConnectivityService( 3516): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/RCPManagerService( 3516): exchangeData() failure , invalid userId
,D/RCPManagerService( 3516): exchangeData() failure , invalid userId
,D/RCPManagerService( 3516): exchangeData() failure , invalid userId
,D/RCPManagerService( 3516): exchangeData() failure , invalid userId
,E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 3516): exchangeData() failure , invalid userId
,D/RCPManagerService( 3516): exchangeData() failure , invalid userId
,E/Zygote  (12307): MountEmulatedStorage()
E/Zygote  (12307): v2
I/libpersona(12307): KNOX_SDCARD checking this for 10082
I/libpersona(12307): KNOX_SDCARD not a persona
,I/SELinux (12307): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12307): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12307): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3516): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=12307 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12323): MountEmulatedStorage()
E/Zygote  (12323): v2
I/libpersona(12323): KNOX_SDCARD checking this for 1000
I/libpersona(12323): KNOX_SDCARD not a persona
,I/SELinux (12323): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12323): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12323): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3516): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=12323 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/SSRM:n  ( 3516): SIOP:: AP = 280, PST = 277, CUR = 59
,I/ActivityManager( 3516): Killing 11394:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12307): TimaSignature is unavailable
,D/ActivityThread(12307): Added TimaKeyStore provider
,I/ActivityManager( 3516): Killing 11415:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12323): TimaSignature is unavailable
,D/ActivityThread(12323): Added TimaKeyStore provider
,D/ResourcesManager(12307): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/ResourcesManager(12323): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/BadgeProvider(12307): onCreate
D/BadgeProvider(12307): DatabaseHelper
,I/ActivityManager( 3516): Killing 11433:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##31
,D/BadgeProvider(12307): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
W/ActivityManager( 3516): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/Launcher.Model( 4000): reloadBadges entered.
,D/BadgeProvider(12307): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12307): sendNotify, [notify] : null
D/BadgeProvider(12307): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12307): update, [BadgeCount] : badgecount=0
D/BadgeProvider(12307): update, [UpdateCount] : 1
,E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12340): MountEmulatedStorage()
E/Zygote  (12340): v2
I/libpersona(12340): KNOX_SDCARD checking this for 10013
I/libpersona(12340): KNOX_SDCARD not a persona
,I/SELinux (12340): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12340): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3516): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=12340 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,E/SELinux (12340): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/PowerManagerService( 3516): [PWL] Off : 50s ago
,D/TimaKeyStoreProvider(12340): TimaSignature is unavailable
,D/ActivityThread(12340): Added TimaKeyStore provider
,D/ResourcesManager(12340): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,D/WaitQueueForNetworkActivate(12340): notifyNetworkActivated
,W/ContextImpl(12340): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
W/ActivityManager( 3516): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3516): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-92
D/BatteryService( 3516): stay LED for fully charged
D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/hcjo    (12340): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12340): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12340): exit::IDLE
D/InitializeManagerStateMachine(12340): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12340): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12340): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12340): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12340): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12340): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12340): entry::SUCCESS
D/hcjo    (12340): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (12340): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    (12340): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine(12340): exit::SUCCESS
D/InitializeManagerStateMachine(12340): entry::IDLE
,I/Hs20UtilService( 4082): Starting #10
I/Hs20UtilService( 4082): Message received 5007
,I/ActivityManager( 3516): Killing 11476:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
,D/NearbySettings( 8607): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8607): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8607): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11764): setDiscoveryMode: Mode set to BLE
,I/NearbySettings( 8607): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8607): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8607): MountReceiver.onReceive - Keep current state
,I/jxcore-log(11764): BLE supported!!
I/jxcore-log(11764): 
,I/SignOutReceiver(11367): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4082): Starting #11
,I/Hs20UtilService( 4082): Message received 5007
,D/NearbySettings( 8607): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8607): MountReceiver.onReceive - Keep current state
,I/SignOutReceiver(11367): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4082): Starting #12
,I/Hs20UtilService( 4082): Message received 5007
,D/NearbySettings( 8607): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8607): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8607): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 8607): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8607): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8607): MountReceiver.onReceive - Keep current state
,I/SignOutReceiver(11367): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4082): Starting #13
,I/Hs20UtilService( 4082): Message received 5007
,D/NearbySettings( 8607): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8607): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine( 3516): callSECApi what=220
D/WifiStateMachine( 3516): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/SignOutReceiver(11367): NETWORK_STATE_CHANGED_ACTION
,I/PCWCLIENTTRACE_PushUtil(11892): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11892): sales region : global
I/PCWCLIENTTRACE_PushUtil(11892): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11892): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/SurfaceFlinger( 2849): id=15 createSurf (1x1),1 flag=4, Uoast
,I/DIAGMON_AGENT(11978): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(11978): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/PowerManagerService( 3516): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3516
,D/mali_winsys( 3692): new_window_surface returns 0x3000,  [1120x201]-format:1
,I/FOTA_Client(11997): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(11997): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(11997): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.521: (12013): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Dec 22 00:02:40 GMT+01:00 2015
,I/KLMS-2.4.521: (12013): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (12013): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12013): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (12013): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (12013): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12013): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (12013): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.521: (12013): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.521: (12013): NetworkChangeOperations(): uploadRequestLog().START 
,I/SO_AGENT(12030): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,I/KLMS-2.4.521: (12013): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.4.521: (12013): StateImplV2(): networkChangeListener().END
,I/KLMS-2.4.521: (12013): KLMSIntentService(): onDestroy()
,E/SPPClientService(12065): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      (11161): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11161): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (11161): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (11161): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11161): [OR] == isSIMCardReady false ==
,I/SA      (11161): [SCU] == networkStateCheck == true
I/SA      (11161): [DM] getCountryCodeFromCSC : PL
I/SA      (11161): isChinaCountryCode : false
I/SA      (11161): [SCU] is ChinestModel Data Restricted   : false
I/SA      (11161): [OR] == networkStateCheck true ==
,I/SA      (11161): [OR] GetMyCountryZoneTask
,I/SA      (11161): [OR] onReceive END
,I/SA      (11161): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 3715): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      (11161): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (11161): [SSP] query invoked
,I/SCloudBackupReceiver(12093): Other Intent
,I/SA      (11161): [TPMU] GetMccFromDB : null
I/SA      (11161): [SCU] getMccFromPreferece mcc = 260
,I/SA      (11161): [TPM] isNoProxy(default) : true
,D/accuweather( 5200): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3776): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 7
,D/accuweather( 5200): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5200): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5200): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
,D/accuweather( 5200): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5200): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5200): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro(12122): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro(12122): premStatus:2
,I/KnoxUsageLogPro(12122): isEulaShown : false
I/KnoxUsageLogPro(12122): KnoxUsageReceiver onReceive : not Processible, just return
,D/KeyguardWallpaperUpdator(12170): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12170): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12170): stopCheckCategoryVersion
,D/QuickConnect(12269): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12269): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect(12269): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 3516): exchangeData() failure , invalid userId
,D/RCPManagerService( 3516): exchangeData() failure , invalid userId
,D/hcjo    (12340): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12340): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12340): exit::IDLE
D/InitializeManagerStateMachine(12340): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12340): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12340): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12340): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12340): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12340): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12340): entry::SUCCESS
D/hcjo    (12340): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (12340): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12340): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine(12340): exit::SUCCESS
D/InitializeManagerStateMachine(12340): entry::IDLE
,I/SA      (11161): [RC New] Execute method=[GET] start
,I/SA      (11161): [RC New] Security=[true]
,I/System.out(11161): Thread-1540(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out(11161): Thread-1540(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11161): Thread-1540(ApacheHTTPLog):isShipBuild true
I/System.out(11161): Thread-1540(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 10045
,I/dhcpcd  (11951): wlan0: sending IPv6 Router Solicitation
,E/dhcpcd  (11951): wlan0: sendmsg: Cannot assign requested address
,I/SA      (11161): [RC New] [v2liruge] api execute + 744
I/SA      (11161): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out(11161): AsyncTask #1 calls detatch()
,I/SA      (11161): [TPMU] getNetworkMcc : 
,I/SA      (11161): [SCU] saveMccToPreferece Start
I/SA      (11161): [SCU] RegionMCC : 260
I/SA      (11161): [SSP] query invoked
,I/SA      (11161): [TPMU] GetMccFromDB : null
I/SA      (11161): [SCU] getMccFromPreferece mcc = 260
I/SA      (11161): [SCU] saveMccToPreferece End
,I/SA      (11161): [RC New] executeRequest [v2liruge] end. 773
I/SA      (11161): [RC New] Execute end
I/SA      (11161): [OR] GetMyCountryZoneTask mcc = 260
I/SA      (11161): [OR] GetMyCountryZoneTask Success
,E/WifiStateMachine( 3516): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService( 3516): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,V/        ( 2845): QcRouteController
,E/WifiStateMachine( 3516): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/SmartBondingService( 3516): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/SmartBondingService( 3516): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService( 3516): getSBEnabled() enabled =false
D/SmartBondingService( 3516): getSBEnabled() enabled =false
,D/SmartBondingService( 3516): getSBEnabled() enabled =false
,I/WifiStateMachine( 3516): REQUEST_POWER_SAVE_ON
,V/        ( 2845): QcRouteController
,W/NetworkManagementService( 3516): route cmd failed: 
W/NetworkManagementService( 3516): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '76 route replace src v6 wlan0 fe80::92b6:86ff:fe43:731c 2 ::' failed with '400 76 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService( 3516): '
W/NetworkManagementService( 3516): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService( 3516): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService( 3516): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService( 3516): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService( 3516): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService( 3516): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5738)
W/NetworkManagementService( 3516): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5545)
W/NetworkManagementService( 3516): 	at com.android.server.ConnectivityService.access$2600(ConnectivityService.java:231)
W/NetworkManagementService( 3516): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2436)
W/NetworkManagementService( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/ConnectivityService( 3516): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3692): CM callback handler got msg 524295
,D/ConnectivityService( 3516): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 6696): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 3692): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 6696): CM callback handler got msg 524295
,E/WifiStateMachine( 3516): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,D/WearableService( 4658): callingUid 10014, callindPid: 4658
,D/ResourcesManager(11914): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11914): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11914): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory(11914): Using the GMSCore's GoogleHttpClient
,I/MusicLeanback(11914): Conditions not met for autocaching.
I/MusicLeanback(11914): Stop autocaching.
,D/WearableClient(11914): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11914): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11914): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11914): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(11914): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils(11914): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/ActivityThread(11914): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@f21852 that was originally bound here
E/ActivityThread(11914): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@f21852 that was originally bound here
E/ActivityThread(11914): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(11914): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(11914): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(11914): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(11914): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(11914): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(11914): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11914): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11914): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11914): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(11914): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(11914): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(11914): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(11914): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(11914): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(11914): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(11914): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(11914): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(11914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(11914): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(11914): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(11914): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(11914): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(11914): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(11914): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/PackageManager( 3516): [MSG] WRITE_PACKAGE_RESTRICTIONS
,W/ContextImpl( 3516): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/SurfaceFlinger( 2849): id=15 Removed Uoast (8/9)
,I/SurfaceFlinger( 2849): id=15 Removed Uoast (-2/9)
,D/PowerManagerService( 3516): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3516) eventTime = 148043
,D/PowerManagerService( 3516): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3516 (0x0)
D/PowerManagerService( 3516): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3516, ws=WorkSource{10060}) (elapsedTime=3472)
,I/art     ( 3516): Explicit concurrent mark sweep GC freed 53148(3MB) AllocSpace objects, 7(112KB) LOS objects, 24% free, 48MB/64MB, paused 6.926ms total 196.290ms
,I/GAV4    (12188): Thread[GAThread,5,main]: No campaign data found.
,I/dhcpcd  (11951): wlan0: sending IPv6 Router Solicitation
,I/PCWCLIENTTRACE_SYSTEMReceiver(11892): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil(11892): [hasSamungAccount] - No Samsung Account
,W/ProcessCpuTracker( 3516): Skipping unknown process pid 12442
,I/CSTORAGE(11892): ================================================
I/CSTORAGE(11892):  CSTORAGE_SKM_LIB v1.0.15
I/CSTORAGE(11892): ================================================
I/PCWCLIENTTRACE_SecurePreferencesJNI(11892): [GetString-S]
,E/art     (11892): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
W/PCWCLIENTTRACE_SecurePreferencesJNI(11892): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI(11892): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil(11892): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11892): sales region : global
I/PCWCLIENTTRACE_PushUtil(11892): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler(11892): [ensureRegistration] - No Samsung account
,I/dhcpcd  (11951): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  (11951): wlan0: no IPv6 Routers available
,D/SSRM:n  ( 3516): SIOP:: AP = 270, PST = 275, CUR = 14,
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:43, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:67
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/PreloadUpdateManagerStateMachine(12340): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine(12340): exit::IDLE
,D/PreloadUpdateManagerStateMachine(12340): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (12340): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    (12340): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine(12340): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine(12340): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine(12340): entry::IDLE
,D/PreloadUpdateManagerStateMachine(12340): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(12340): exit::IDLE
,D/PreloadUpdateManagerStateMachine(12340): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (12340): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine(12340): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine(12340): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine(12340): entry::IDLE
,I/ActivityManager( 3516): Waited long enough for: ServiceRecord{1d62901 u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,E/Watchdog( 3516): !@Sync 5
,V/AlarmManager( 3516): waitForAlarm result :8
,D/SSRM:n  ( 3516): SIOP:: AP = 260, PST = 275, CUR = 43
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:54, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:64
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3516): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3516): [PWL] Off : 75s ago
,D/SSRM:n  ( 3516): SIOP:: AP = 260, PST = 274, CUR = 54
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:53, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:59
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
I/MotionRecognitionService( 3516): Plugged
I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ProcessCpuTracker( 3516): Skipping unknown process pid 12497
,D/SSRM:n  ( 3516): SIOP:: AP = 260, PST = 269, CUR = 53
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:52, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:69
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3516): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3516): !@Sync 6
,D/SSRM:n  ( 3516): SIOP:: AP = 250, PST = 265, CUR = 52,
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:49, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:49
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3516): [PWL] Off : 105s ago
,D/SSRM:n  ( 3516): SIOP:: AP = 250, PST = 263, CUR = 49
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!,
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0,
,D/BatteryService( 3516): online:4, current avg:47, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:48,
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 3516): Plugged,
I/MotionRecognitionService( 3516): setPowerConnected  = true
D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate,
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3516): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3516): SIOP:: AP = 250, PST = 262, CUR = 47
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:45, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:44
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ClearcutLoggerApiImpl( 4658): disconnect managed GoogleApiClient
,V/AlarmManager( 3516): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3692): handleTimeUpdate
,D/KeyguardEffectViewController( 3692): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3692): *** don't update sliding image ***
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/Watchdog( 3516): !@Sync 7
,V/AlarmManager( 3516): waitForAlarm result :8
,D/SSRM:n  ( 3516): SIOP:: AP = 250, PST = 260, CUR = 45
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:44, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:34
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3516): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3516): [PWL] Off : 140s ago
,D/SSRM:n  ( 3516): SIOP:: AP = 250, PST = 258, CUR = 44
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:41, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:44
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3516): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 250, PST = 256, CUR = 41
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:40, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:45
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3516): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3516): !@Sync 8
,D/SSRM:n  ( 3516): SIOP:: AP = 250, PST = 256, CUR = 40
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:38, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3516): SIOP:: AP = 250, PST = 254, CUR = 38
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3516): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3516): [PWL] Off : 180s ago
,D/SSRM:n  ( 3516): SIOP:: AP = 240, PST = 252, CUR = 37
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3516): !@Sync 9
,D/SSRM:n  ( 3516): SIOP:: AP = 240, PST = 251, CUR = 35
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:48
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3516): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3516): SIOP:: AP = 240, PST = 250, CUR = 35,
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3516): online:4, current avg:34, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 240, PST = 248, CUR = 34
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3516): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService( 3516): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3516): TimaServiceHandler.handleMessage what =1
,D/TimaService( 3516): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize( 3516): initializing...
,I/TLC_TIMA_PKM_initialize( 3516): root = 0, root_strlen = 1
I/TLC_TIMA_PKM_initialize( 3516): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 3516): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 3516): input max_recvmsg_size = 262196
,I/TZ: mc_tlc_communication( 3516): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 3516): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 3516): aligned max_sendmsg_size = 262208
,I/TZ: mc_tlc_communication( 3516): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 3516): device_id = 0x0
I/TZ: mc_tlc_communication( 3516): tlc_open() was called
I/TZ: mc_tlc_communication( 3516): Opening MobiCore device
,I/TZ: mc_tlc_communication( 3516): Allocating WSM for TCI
,I/TZ: mc_tlc_communication( 3516): Opening the session
,I/TZ: mc_tlc_communication( 3516): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 3516): Trustlet response is completed
,E/Watchdog( 3516): !@Sync 10
,D/SSRM:n  ( 3516): SIOP:: AP = 240, PST = 247, CUR = 35
,I/TLC_TIMA_PKM_measure_kernel( 3516): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3516): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3516): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3516): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3516): online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:55
D/BatteryService( 3516): stay LED for fully charged
D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 ,
,I/PowerManagerService( 3516): [PWL] Off : 225s ago
,D/SSRM:n  ( 3516): SIOP:: AP = 240, PST = 246, CUR = 35
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:33, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3516): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3516): SIOP:: AP = 240, PST = 245, CUR = 33
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3516): online:4, current avg:34, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3516): !@Sync 11,
,D/SSRM:n  ( 3516): SIOP:: AP = 240, PST = 245, CUR = 34
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
D/BatteryService( 3516): stay LED for fully charged
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3516): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 3516): SIOP:: AP = 240, PST = 244, CUR = 31
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3516): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 240, PST = 243, CUR = 30
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3516): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3516): [PWL] Off : 275s ago
,E/Watchdog( 3516): !@Sync 12
,D/SSRM:n  ( 3516): SIOP:: AP = 240, PST = 243, CUR = 32
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3516): SIOP:: AP = 240, PST = 242, CUR = 32
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3516): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3516): SIOP:: AP = 240, PST = 242, CUR = 29
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3516): !@Sync 13
,V/AlarmManager( 3516): waitForAlarm result :8
,D/SSRM:n  ( 3516): SIOP:: AP = 240, PST = 241, CUR = 28
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,W/ContextImpl( 3516): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3516): SIOP:: AP = 240, PST = 241, CUR = 28
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:34
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3516): [PWL] Off : 330s ago
,D/SSRM:n  ( 3516): SIOP:: AP = 240, PST = 240, CUR = 28
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3516): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3516): !@Sync 14
,D/SSRM:n  ( 3516): SIOP:: AP = 240, PST = 240, CUR = 28
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 240, PST = 240, CUR = 29
,W/ContextImpl( 3516): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 240, PST = 240, CUR = 28
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3516): !@Sync 15
,D/SSRM:n  ( 3516): SIOP:: AP = 240, PST = 240, CUR = 27
,W/ContextImpl( 3516): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 240, PST = 240, CUR = 27
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3516): [PWL] Off : 390s ago
,D/SSRM:n  ( 3516): SIOP:: AP = 240, PST = 240, CUR = 25
,W/ContextImpl( 3516): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18,
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3516): !@Sync 16
,D/SSRM:n  ( 3516): SIOP:: AP = 240, PST = 240, CUR = 25
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 240, PST = 240, CUR = 24
,W/ContextImpl( 3516): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 240, PST = 240, CUR = 26
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3516): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
D/BatteryService( 3516): stay LED for fully charged
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3516): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3692): handleTimeUpdate
,D/KeyguardEffectViewController( 3692): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3692): *** don't update sliding image ***
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/Watchdog( 3516): !@Sync 17
,V/AlarmManager( 3516): waitForAlarm result :8
,D/SSRM:n  ( 3516): SIOP:: AP = 240, PST = 240, CUR = 24
,W/ContextImpl( 3516): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:50
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 240, PST = 240, CUR = 25
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3516): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 240, PST = 240, CUR = 23
,W/ContextImpl( 3516): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3516): [PWL] Off : 455s ago
,E/Watchdog( 3516): !@Sync 18
,D/SSRM:n  ( 3516): SIOP:: AP = 240, PST = 240, CUR = 23
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 240, PST = 240, CUR = 24
,W/ContextImpl( 3516): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 240, PST = 240, CUR = 23
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3516): !@Sync 19
,D/SSRM:n  ( 3516): SIOP:: AP = 240, PST = 240, CUR = 24
,W/ContextImpl( 3516): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24,
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 240, PST = 240, CUR = 23
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 240, PST = 240, CUR = 25
,W/ContextImpl( 3516): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 3516): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3516): TIMA: checkEvent, operation: 50000 subject: 10000,
,D/TimaService( 3516): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 3516): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 3516): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3516): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3516): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3516): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:n  ( 3516): SIOP:: AP = 240, PST = 240, CUR = 22
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3516): [PWL] Off : 525s ago
,D/SSRM:n  ( 3516): SIOP:: AP = 240, PST = 240, CUR = 21
,W/ContextImpl( 3516): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 240, PST = 240, CUR = 21
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3516): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3516): !@Sync 21
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 239, CUR = 23
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3516): stay LED for fully charged
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 239, CUR = 22
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 239, CUR = 22,
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3516): !@Sync 22
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 238, CUR = 20,
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 238, CUR = 21
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3516): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3516): [PWL] Off : 600s ago
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 238, CUR = 19
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3516): !@Sync 23
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 237, CUR = 19
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 237, CUR = 18,
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:34
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 237, CUR = 17
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3516): !@Sync 24
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 236, CUR = 16
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 236, CUR = 18
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 236, CUR = 19
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3516): !@Sync 25
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 235, CUR = 19
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3516): [PWL] Off : 680s ago
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 235, CUR = 20
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3516): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 235, CUR = 19
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3516): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3692): handleTimeUpdate
,D/KeyguardEffectViewController( 3692): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3692): *** don't update sliding image ***
,D/LightsService( 3516): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,I/Sensors ( 3516): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager( 3516): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 6696): Aggregate from 1450737796739 (log), 1450737796739 (data)
,E/Watchdog( 3516): !@Sync 26
,I/Sensors ( 3516): #>LightSensor r=0 g=0 b=1 c=2 atime=238 again=64 lux=0.000000
,D/LightsService( 3516): [SvcLED]  onSensorChanged::light value = 0
,I/Sensors ( 3516): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager( 3516): unregisterListener ::   
,D/LightsService( 3516): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 234, CUR = 18
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 234, CUR = 17
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 234, CUR = 16
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3516): !@Sync 27
,V/AlarmManager( 3516): waitForAlarm result :8
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 233, CUR = 16
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 233, CUR = 18
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 233, CUR = 18
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3516): !@Sync 28
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 232, CUR = 18
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3516): [PWL] Off : 765s ago
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3516): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 232, CUR = 16
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-3
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 232, CUR = 16,
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3516): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3516): !@Sync 29
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 231, CUR = 16
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 231, CUR = 16
,V/AlarmManager( 3516): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3692): handleTimeUpdate
,D/KeyguardEffectViewController( 3692): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3692): *** don't update sliding image ***
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 231, CUR = 15
,D/TimaService( 3516): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3516): TIMA: checkEvent, operation: 50000 subject: 10000,
D/TimaService( 3516): TimaServiceHandler.handleMessage what =1,
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3516): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3516): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 3516): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 3516): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 16
,D/TimaService( 3516): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3516): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 16
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 16
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3516): !@Sync 31,
,V/AlarmManager( 3516): waitForAlarm result :8
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 15
,I/PowerManagerService( 3516): [PWL] Off : 855s ago
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:40
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 16
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 14
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3516): !@Sync 32
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 13
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:36
D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3516): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 14
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 14
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3516): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3516): !@Sync 33
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 13
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 13
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3516): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
I/MotionRecognitionService( 3516): Plugged
I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 14
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3516): !@Sync 34
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 14
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3516): [PWL] Off : 950s ago
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 11
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 11
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3516): !@Sync 35
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 13
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3516): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 12
,E/Watchdog( 3516): !@Sync 36
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 12
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 14
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 12
,E/Watchdog( 3516): !@Sync 37
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3516): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-2
D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 13,
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 13
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3516): [PWL] Off : 1050s ago
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 13
,E/Watchdog( 3516): !@Sync 38
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 13
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3516): stay LED for fully charged
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 11,
,E/Watchdog( 3516): !@Sync 39
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3516): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 12
,D/TimaService( 3516): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3516): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 3516): TimaServiceHandler.handleMessage what =1,
,I/UsageStatsService( 3516): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 3516): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 3516): Updating Usage Statistics in DB @ 1450740027501
,I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
,W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
,W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
,W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
,W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3516): ,	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3516): ::getAppControlDB: Exception to create DB
W/System.err( 3516): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3516): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage( 3516): Done Updating Usage Statistics in DB @ 1450740027587
,E/Watchdog( 3516): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 3516): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3516): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3516): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3516): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-3
D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3516): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 11
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3516): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-8
D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 11
,E/Watchdog( 3516): !@Sync 41
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3516): stay LED for fully charged
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 12
,I/PowerManagerService( 3516): [PWL] Off : 1155s ago,
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3516): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 11
,E/Watchdog( 3516): !@Sync 42
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 10,
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-3
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0,
D/BatteryService( 3516): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 11
,E/Watchdog( 3516): !@Sync 43
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13,
D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 11
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3516): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 11
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3516): stay LED for fully charged
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 10
,E/Watchdog( 3516): !@Sync 44
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-19
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3516): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 8
,I/PowerManagerService( 3516): [PWL] Off : 1265s ago
,E/Watchdog( 3516): !@Sync 45
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3516): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 9
,E/Watchdog( 3516): !@Sync 46
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 9
,I/art     ( 3516): Background sticky concurrent mark sweep GC freed 88209(9MB) AllocSpace objects, 383(5MB) LOS objects, 13% free, 49MB/57MB, paused 3.271ms total 112.907ms
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 9
,E/Watchdog( 3516): !@Sync 47
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3516): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 9
,E/Watchdog( 3516): !@Sync 48
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3516): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged,
,I/MotionRecognitionService( 3516): Plugged,
I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 8
,I/PowerManagerService( 3516): [PWL] Off : 1380s ago
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 7
,E/Watchdog( 3516): !@Sync 49
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3516): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-10
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 3516): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3516): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 3516): TimaServiceHandler.handleMessage what =1
,V/AlarmManager( 3516): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3692): handleTimeUpdate
,D/KeyguardEffectViewController( 3692): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3692): *** don't update sliding image ***
,D/LightsService( 3516): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,I/Sensors ( 3516): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager( 3516): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/Watchdog( 3516): !@Sync 50
,I/Sensors ( 3516): #>LightSensor r=0 g=0 b=1 c=2 atime=238 again=64 lux=0.000000
,D/LightsService( 3516): [SvcLED]  onSensorChanged::light value = 0
I/Sensors ( 3516): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager( 3516): unregisterListener ::   
,D/LightsService( 3516): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/TLC_TIMA_PKM_measure_kernel( 3516): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3516): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3516): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3516): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-23
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3516): !@Sync 51
,V/AlarmManager( 3516): waitForAlarm result :8
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3516): !@Sync 52
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 8,
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3516): [PWL] Off : 1500s ago
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3516): !@Sync 53
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-1
D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!,
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3516): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19,
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 3516): Plugged
I/MotionRecognitionService( 3516): setPowerConnected  = true
D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3516): !@Sync 54
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3516): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14,
D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3516): !@Sync 55
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-5
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3516): !@Sync 56
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-6
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-4
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3516): [PWL] Off : 1625s ago
,E/Watchdog( 3516): !@Sync 57
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-1
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,D/BatteryService( 3516): stay LED for fully charged
I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3516): !@Sync 58
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3516): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-4
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3516): !@Sync 59
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0,
D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3516): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3516): waitForAlarm result :4
,D/NetworkStatsFactory( 3516): UpdateStatsForKnox
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3692): handleTimeUpdate
,D/KeyguardEffectViewController( 3692): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 3692): *** don't update sliding image ***
,V/AlarmManager( 3516): OOI=Alarm{16d593a8 type 0 when 1450742416119 com.google.android.gms}
,V/GLSActivity( 4658): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4658): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3516): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
D/BatteryService( 3516): stay LED for fully charged
D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 3516): TIMA: TimaService scheduler is intialized. ,
,D/TimaService( 3516): TimaServiceHandler.handleMessage what =1,
,D/TimaService( 3516): TIMA: checkEvent, operation: 50000 subject: 10000,
,E/Watchdog( 3516): !@Sync 60
,I/TLC_TIMA_PKM_measure_kernel( 3516): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3516): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3516): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3516): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3516): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-3
D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3516): !@Sync 61
,V/AlarmManager( 3516): waitForAlarm result :8
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 7
,I/PowerManagerService( 3516): [PWL] Off : 1755s ago
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3516): !@Sync 62
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4400, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3516): !@Sync 63
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3516): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
D/BatteryService( 3516): stay LED for fully charged
D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3516): stay LED for fully charged
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3516): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-13
D/BatteryService( 3516): stay LED for fully charged
,D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3516): !@Sync 64
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3516): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-18
D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3516): Plugged
,I/MotionRecognitionService( 3516): setPowerConnected  = true
,D/BatteryService( 3516): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3516): SIOP:: AP = 230, PST = 230, CUR = 5
,TIME-OUT KILL (timeout was 1800000ms),D/BatteryService( 3516): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3516): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3516): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
D/BatteryService( 3516): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3516): stay LED for fully charged
I/MotionRecognitionService( 3516): Plugged
I/MotionRecognitionService( 3516): setPowerConnected  = true
D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5600): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5600): Disconnected process message: 10
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AndroidRuntime(13574): 
D/AndroidRuntime(13574): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(13574): CheckJNI is OFF
D/AndroidRuntime(13574): readGMSProperty: start
D/AndroidRuntime(13574): readGMSProperty: already setted!!
D/AndroidRuntime(13574): readGMSProperty: end
D/AndroidRuntime(13574): addProductProperty: start
E/AffinityControl(13574): AffinityControl: registerfunction enter
D/AndroidRuntime(13574): Calling main entry com.android.commands.pm.Pm
D/PackageManager( 3516): START PACKAGE DELETE: observer{460115530}
D/PackageManager( 3516): pkg{<packageName>}
D/PackageManager( 3516): user{0}
D/PackageManager( 3516): caller{2000}
D/PackageManager( 3516): flags{3}
D/PersonaManagerService( 3516): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService( 3516): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 3516): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 3516): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3516): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3516): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 3516): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 3516): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 3516): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3516): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 3516): !@killApplicatoin: 10523, uninstall pkg
I/ActivityManager( 3516): Force stopping com.test.thalitest appid=10523 user=-1: uninstall pkg
I/ActivityManager( 3516): Killing 11764:com.test.thalitest/u0a523 (adj 0): stop com.test.thalitest
I/ActivityManager( 3516): Killing 11161:com.osp.app.signin/u0a45 (adj 13): empty for 1809s
I/ActivityManager( 3516): Killing 12045:com.policydm/1000 (adj 13): empty for 1809s
E/lowmemorykiller( 2828): Error writing /proc/12045/oom_score_adj; errno=22
I/ActivityManager( 3516): Killing 12030:com.sec.android.soagent/u0a38 (adj 13): empty for 1809s
I/ActivityManager( 3516): Killing 12013:com.samsung.klmsagent/u0a21 (adj 13): empty for 1809s
I/ActivityManager( 3516): Killing 11997:com.sec.android.fotaclient/u0a12 (adj 13): empty for 1809s
I/ActivityManager( 3516): Killing 11978:com.sec.android.diagmonagent/1000 (adj 13): empty for 1809s
I/ActivityManager( 3516): Killing 11958:com.sec.android.cloudagent/u0a2 (adj 13): empty for 1809s
I/ActivityManager( 3516): Killing 11892:com.sec.pcw.device/1000 (adj 13): empty for 1809s
I/ActivityManager( 3516): Killing 11367:com.samsung.android.snote/u0a160 (adj 15): empty for 1809s
I/ActivityManager( 3516): Killing 8607:com.android.settings/1000 (adj 15): empty for 1809s
I/ActivityManager( 3516): Killing 12307:com.sec.android.provider.badge/u0a82 (adj 15): empty for 1809s
I/ActivityManager( 3516): Killing 11622:com.android.vending/u0a31 (adj 15): empty for 1839s
I/ActivityManager( 3516): Killing 10757:com.android.defcontainer/u0a5 (adj 15): empty for 1844s
I/ActivityManager( 3516): Killing 11459:com.sec.android.widgetapp.locationwidget/u0a22 (adj 15): empty for 1852s
I/ActivityManager( 3516): Killing 11492:com.android.calendar/u0a164 (adj 15): empty for 1852s
I/ActivityManager( 3516):   Force finishing activity ActivityRecord{28239c87 u0 com.test.thalitest/.MainActivity t26}
W/ActivityManager( 3516): mDVFSHelper.acquire()
D/WifiService( 3516): Client connection lost with reason: 4
I/WindowState( 3516): WIN DEATH: Window{2cd74605 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 3516): Client connection lost with reason: 4
I/SurfaceFlinger( 2849): id=14 Removed NainActivit (5/8)
I/SurfaceFlinger( 2849): id=14 Removed NainActivit (-2/8)
I/SurfaceFlinger( 2849): id=14 Removed NainActivit (-2/8)
D/PointerIcon( 3516): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3516): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3516): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3516): setHoveringSpenCustomIcon IconType is same.1
W/PackageSettings( 3516): Skipping PackageSetting{37ef03ff com.example.hello/10500} due to missing metadata
W/libprocessgroup( 3516): failed to open /acct/uid_1000/pid_8607/cgroup.procs: No such file or directory
W/libprocessgroup( 3516): failed to open /acct/uid_1000/pid_11978/cgroup.procs: No such file or directory
W/libprocessgroup( 3516): failed to open /acct/uid_10002/pid_11958/cgroup.procs: No such file or directory
W/libprocessgroup( 3516): failed to open /acct/uid_10160/pid_11367/cgroup.procs: No such file or directory
W/libprocessgroup( 3516): failed to open /acct/uid_10022/pid_11459/cgroup.procs: No such file or directory
W/libprocessgroup( 3516): failed to open /acct/uid_10005/pid_10757/cgroup.procs: No such file or directory
W/libprocessgroup( 3516): failed to open /acct/uid_10164/pid_11492/cgroup.procs: No such file or directory
W/libprocessgroup( 3516): failed to open /acct/uid_10012/pid_11997/cgroup.procs: No such file or directory
W/libprocessgroup( 3516): failed to open /acct/uid_1000/pid_11892/cgroup.procs: No such file or directory
W/libprocessgroup( 3516): failed to open /acct/uid_10082/pid_12307/cgroup.procs: No such file or directory
W/libprocessgroup( 3516): failed to open /acct/uid_10021/pid_12013/cgroup.procs: No such file or directory
W/libprocessgroup( 3516): failed to open /acct/uid_1000/pid_12045/cgroup.procs: No such file or directory
W/libprocessgroup( 3516): failed to open /acct/uid_10045/pid_11161/cgroup.procs: No such file or directory
W/libprocessgroup( 3516): failed to open /acct/uid_10038/pid_12030/cgroup.procs: No such file or directory
W/libprocessgroup( 3516): failed to open /acct/uid_10031/pid_11622/cgroup.procs: No such file or directory
I/ActivityManager( 3516): Force stopping com.test.thalitest appid=10523 user=0: pkg removed
I/ActivityManager( 3516):   Force finishing activity ActivityRecord{28239c87 u0 com.test.thalitest/.MainActivity t26 f}
W/ActivityManager( 3516): Duplicate finish request for ActivityRecord{28239c87 u0 com.test.thalitest/.MainActivity t26 f}
I/ProcessStatsService( 3516): Prepared write state in 22ms
I/DBG_DM  ( 6198): [com.wssyncmldm.ui.XUIInstallConfirmActivity(456/onResume)] 
I/art     ( 8924): Explicit concurrent mark sweep GC freed 28448(1607KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.140ms total 41.777ms
I/DBG_DM  ( 6198): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 8
I/ProcessStatsService( 3516): Prepared write state in 15ms
I/DBG_DM  ( 6198): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
I/art     ( 6696): Explicit concurrent mark sweep GC freed 9529(492KB) AllocSpace objects, 2(32KB) LOS objects, 20% free, 31MB/39MB, paused 1.415ms total 64.756ms
I/DBG_DM  ( 6198): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 6198): [com.wssyncmldm.ui.XUIInstallConfirmActivity(466/onResume)] Postpone Count : 8
I/ProcessStatsService( 3516): Prepared write state in 11ms
I/DBG_DM  ( 6198): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
I/ProcessStatsService( 3516): Prepared write state in 9ms
I/ProcessStatsService( 3516): Prepared write state in 9ms
I/DBG_DM  ( 6198): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
I/ProcessStatsService( 3516): Prepared write state in 9ms
I/art     ( 4056): Explicit concurrent mark sweep GC freed 33345(2044KB) AllocSpace objects, 1(39KB) LOS objects, 21% free, 28MB/36MB, paused 992us total 107.593ms
I/ProcessStatsService( 3516): Prepared write state in 7ms
I/DBG_DM  ( 6198): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
I/ProcessStatsService( 3516): Prepared write state in 7ms
D/SecContentProvider2( 3516): uri = 14 selection = getSealedState
D/SecContentProvider2( 3516): mCursor = null
I/ProcessStatsService( 3516): Prepared write state in 12ms
D/ApplicationPolicy( 3516): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3516): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
I/DBG_DM  ( 6198): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 8
I/ProcessStatsService( 3516): Prepared write state in 12ms
I/DBG_DM  ( 6198): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
I/DBG_DM  ( 6198): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 6198): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
I/DBG_DM  ( 6198): [llIIlIIlIllIllIlllII(376/llIIllllIIlllIIIIlll)] 
I/DBG_DM  ( 6198): [IIlIIIlllllIIlIIIlII(339/llllIlIIIllllIIlIlll)] No need to check encryption status
I/ProcessStatsService( 3516): Prepared write state in 12ms
I/DBG_DM  ( 6198): [llIIlIIlIllIllIlllII(405/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
I/ProcessStatsService( 3516): Prepared write state in 17ms
D/ActivityManager( 3516): post active user change for 0
D/KnoxTimeoutHandler( 3516): postActiveUserChange for user 0
I/DBG_DM  ( 6198): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
I/art     ( 3516): Explicit concurrent mark sweep GC freed 53634(5MB) AllocSpace objects, 169(2MB) LOS objects, 24% free, 49MB/65MB, paused 5.547ms total 190.919ms
I/art     ( 3516): WaitForGcToComplete blocked for 71.671ms for cause Explicit
I/ProcessStatsService( 3516): Prepared write state in 20ms
I/SurfaceFlinger( 2849): id=16 createSurf (1440x2560),2 flag=404, YUIInstallC
I/ProcessStatsService( 3516): Prepared write state in 14ms
D/StatusBarManagerService( 3516): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService( 3516): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/ProcessStatsService( 3516): Prepared write state in 13ms
D/PointerIcon( 3516): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3516): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3516): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3516): setHoveringSpenCustomIcon IconType is same.1
I/ProcessStatsService( 3516): Prepared write state in 12ms
I/ProcessStatsService( 3516): Prepared write state in 10ms
I/ProcessStatsService( 3516): Prepared write state in 9ms
I/ProcessStatsService( 3516): Prepared write state in 8ms
D/ResourcesManager( 3516): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
D/InputMethodManagerService( 3516): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
I/InputReader( 3516): Reconfiguring input devices.  changes=0x00000010
W/ContextImpl( 3516): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/InputMethodManagerService( 3516): Got RemoteException sending setActive(false) notification to pid 11764 uid 10523
E/SamsungIME( 4507): mOCRHelper is null
W/GeofencerStateMachine( 4658): Ignoring removeGeofence because network location is disabled.
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
V/ActivityThread( 6198): updateVisibility : ActivityRecord{d97ae37 token=android.os.BinderProxy@35e6b278 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
E/Zygote  (13594): MountEmulatedStorage()
E/Zygote  (13594): v2
I/libpersona(13594): KNOX_SDCARD checking this for 10063
I/libpersona(13594): KNOX_SDCARD not a persona
I/Timeline( 6198): Timeline: Activity_idle id: android.os.BinderProxy@35e6b278 time:1954336
I/SELinux (13594): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (13594): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (13594): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3516): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=13594 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/KnoxTimeoutHandler( 3516): handleActiveUserChange for user 0
W/ActivityManager( 3516): mDVFSHelper.release()
I/Timeline( 3516): Timeline: Activity_windows_visible id: ActivityRecord{3d06c390 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t24} time:1954352
D/ResourcesManager( 3516): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/ResourcesManager( 3516): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/StatusBar( 3692): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
D/PersonaManager( 3692): isKioskContainerExistOnDevice
D/PersonaManager( 3692): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3692): Icon Only
I/StatusBar( 3692): Icon Only
D/PanelView( 3692): There is/are notification(s) 
D/PanelView( 3692): There is/are notification(s) 
D/PersonaManager( 3692): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3692): Icon Only
I/StatusBar( 3692): Icon Only
D/PanelView( 3692): There is/are notification(s) 
I/art     ( 3516): Explicit concurrent mark sweep GC freed 5900(381KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 48MB/64MB, paused 2.907ms total 171.153ms
I/art     ( 3516): WaitForGcToComplete blocked for 225.840ms for cause Background
W/ResourceType( 5361): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5361): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
D/ResourcesManager( 3516): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
D/TimaKeyStoreProvider(13594): TimaSignature is unavailable
D/ActivityThread(13594): Added TimaKeyStore provider
D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/PackageManager( 3516): delete codoeFile: 
I/AASAUninstall( 3516):  com.test.thalitest not target!
D/PackageManager( 3516): result of delete: 1{460115530}
D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
D/AndroidRuntime(13574): Shutting down VM
D/ResourcesManager(13594): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/PanelView( 3692): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
D/ResourcesManager( 3516): creating new AssetManager and set to /data/app/com.facebook.katana-1/base.apk
I/ProcessStatsService( 3516): Pruning old procstats: /data/system/procstats/state-2015-12-21-00-51-07.bin
D/ResourcesManager( 3516): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/RegisteredServicesCache( 3965): empty dynamic service
D/VRSetupWizardStub/PackageIntentReceiver(13594): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(13594): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(13594): packagename:com.test.thalitest
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
D/SecContentProvider2( 3516): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3516): mCursor = null
E/Zygote  (13611): MountEmulatedStorage()
E/Zygote  (13611): v2
I/libpersona(13611): KNOX_SDCARD checking this for 10021
I/libpersona(13611): KNOX_SDCARD not a persona
I/SELinux (13611): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (13611): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (13611): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3516): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=13611 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
I/ActivityManager( 3516): Killing 12093:com.samsung.android.scloud.backup/u0a67 (adj 15): empty for 1809s
D/TimaKeyStoreProvider(13611): TimaSignature is unavailable
D/ActivityThread(13611): Added TimaKeyStore provider
D/ResourcesManager(13611): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
D/ResourcesManager( 3516): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager( 3516): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
D/ResourcesManager( 3516): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
I/KLMS-2.4.521: (13611): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Dec 22 00:32:50 GMT+01:00 2015
D/ResourcesManager( 3516): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
D/ResourcesManager( 3516): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager( 3516): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager( 3516): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
D/ResourcesManager( 3516): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/Books/Books.apk
I/KLMS-2.4.521: (13611): KLMSAbstractReciever(): onReceive().END.
D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/talkback/talkback.apk
D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
I/splitIntent( 3516): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3516): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/Drive/Drive.apk
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
I/KLMS-2.4.521: (13611): KLMSIntentService(): onCreate()
I/KLMS-2.4.521: (13611): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/EnterpriseDeviceManagerService( 3516): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3516): Admin package name: com.google.android.gms
D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/Music2/Music2.apk
E/Zygote  (13627): MountEmulatedStorage()
E/Zygote  (13627): v2
I/libpersona(13627): KNOX_SDCARD checking this for 10106
I/libpersona(13627): KNOX_SDCARD not a persona
D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
I/SELinux (13627): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
I/SELinux (13627): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/KLMS-2.4.521: (13611): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
E/SELinux (13627): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3516): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=13627 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
D/ResourcesManager( 3516): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
I/KLMS-2.4.521: (13611): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/KLMS-2.4.521: (13611): KLMSIntentService(): PACKAGE_REMOVED
I/KLMS-2.4.521: (13611): KLMSIntentService(): listeningToPackageRemoved().START
D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
I/KLMS-2.4.521: (13611): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
W/libprocessgroup( 3516): failed to open /acct/uid_10067/pid_12093/cgroup.procs: No such file or directory
D/RCPManager(12122):  in createShortcut() for packageName: com.test.thalitest userId0
D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/TimaKeyStoreProvider(13627): TimaSignature is unavailable
D/ActivityThread(13627): Added TimaKeyStore provider
D/RCPManagerService( 3516):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3516): queryAllProviders():  providerCallBack is not register for 0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
W/Resources( 3516): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3516): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
E/Zygote  (13642): MountEmulatedStorage()
E/Zygote  (13642): v2
I/libpersona(13642): KNOX_SDCARD checking this for 10160
I/libpersona(13642): KNOX_SDCARD not a persona
I/SELinux (13642): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (13642): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (13642): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3516): Start proc com.samsung.android.snote for broadcast com.samsung.android.snote/.library.plugin.PluginBroadcastReceiver: pid=13642 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3516): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
E/Zygote  (13652): MountEmulatedStorage()
E/Zygote  (13652): v2
I/libpersona(13652): KNOX_SDCARD checking this for 10050
I/libpersona(13652): KNOX_SDCARD not a persona
I/SELinux (13652): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager(13627): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
I/SELinux (13652): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3516): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=13652 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
E/SELinux (13652): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/RCPManagerService( 3516): PackageReceiver onReceive()
D/TimaKeyStoreProvider(13642): TimaSignature is unavailable
I/HarmonyEASService( 3516): onReceive : android.intent.action.PACKAGE_REMOVED for 0
W/Resources( 3516): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ActivityThread(13642): Added TimaKeyStore provider
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3516): checkUser: useridlist=null, currentuser=0
D/KnoxMUMContainerPolicy( 3516): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService( 3516): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 3516): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3516): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3516): uID is 10523
V/EnterpriseBillingPolicy( 3516): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3516): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 3516): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3516): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3516): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3516): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 3516): getBillingProfileForVpnEngine - end - null
D/elm:14491(13627): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14491(13627): ELMEngine.ELMEngine( context ).
D/elm:14491(13627): MDMBridge.setEnterpriseBridge()
W/Resources( 3516): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3516): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
E/Zygote  (13672): MountEmulatedStorage()
E/Zygote  (13672): v2
I/libpersona(13672): KNOX_SDCARD checking this for 10101
I/libpersona(13672): KNOX_SDCARD not a persona
I/SELinux (13672): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager( 3516): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
D/TimaKeyStoreProvider(13652): TimaSignature is unavailable
I/SELinux (13672): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (13672): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/ActivityThread(13652): Added TimaKeyStore provider
I/ActivityManager( 3516): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=13672 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/KLMS-2.4.521: (13611): KLMSIntentService(): listeningToPackageRemoved().END
D/elm:14491(13627): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/TaskPersister( 3516): removeObsoleteFile: deleting file=26_task.xml
D/TaskPersister( 3516): removeObsoleteFile: deleting file=24_task.xml
W/System.err( 3516): java.io.FileNotFoundException: /data/system/harmony_third_party_apps.xml.tmp: open failed: EROFS (Read-only file system)
I/KLMS-2.4.521: (13611): KLMSIntentService(): onDestroy()
W/System.err( 3516): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 3516): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 3516): 	at com.android.server.HarmonyEASService.saveHash(HarmonyEASService.java:303)
D/ResourcesManager(13652): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
W/System.err( 3516): 	at com.android.server.HarmonyEASService.access$000(HarmonyEASService.java:60)
W/System.err( 3516): 	at com.android.server.HarmonyEASService$PackageHandler.handleMessage(HarmonyEASService.java:100)
W/System.err( 3516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3516): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3516): 	at com.android.server.SystemServer.run(SystemServer.java:427)
W/System.err( 3516): 	at com.android.server.SystemServer.main(SystemServer.java:312)
W/System.err( 3516): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3516): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3516): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 3516): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/System.err( 3516): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err( 3516): 	at libcore.io.Posix.open(Native Method)
W/System.err( 3516): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 3516): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 3516): 	... 12 more

```
