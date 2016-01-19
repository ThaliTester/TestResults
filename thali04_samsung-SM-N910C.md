#### Test 564496607226f84_thali04_samsung-SM-N910C Logs


```
--------- beginning of system,
D/SSRM:n  ( 3521): SIOP:: AP = 250, PST = 271, CUR = 45
D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:60, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:70
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3521): stay LED for fully charged
I/MotionRecognitionService( 3521): Plugged
I/MotionRecognitionService( 3521): setPowerConnected  = true
--------- beginning of main
D/KeyguardUpdateMonitor( 3688): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3688): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 3688):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
D/BatteryMeterView( 3688): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3688): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3688): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AndroidRuntime(11835): 
D/AndroidRuntime(11835): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11835): CheckJNI is OFF
D/AndroidRuntime(11835): readGMSProperty: start
D/AndroidRuntime(11835): readGMSProperty: already setted!!
D/AndroidRuntime(11835): readGMSProperty: end
D/AndroidRuntime(11835): addProductProperty: start
E/AffinityControl(11835): AffinityControl: registerfunction enter
D/AndroidRuntime(11835): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3521): inState():  stateMachine is null !!
I/PersonaManagerService( 3521): PersonaId don't exist
I/ActivityManager( 3521): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3521): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3521): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3521): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager( 3521): mDVFSHelper.acquire()
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/Zygote  (11854): MountEmulatedStorage()
I/libpersona(11854): KNOX_SDCARD checking this for 10588
E/Zygote  (11854): v2
I/libpersona(11854): KNOX_SDCARD not a persona
I/SELinux (11854): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11854): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3521): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=11854 uid=10588 gids={50588, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/SELinux (11854): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(11835): Shutting down VM
D/PointerIcon( 3521): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3521): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3521): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3521): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(11854): TimaSignature is unavailable
D/ActivityThread(11854): Added TimaKeyStore provider
I/SurfaceFlinger( 2848): id=11 Removed YUIInstallC (5/8)
I/SurfaceFlinger( 2848): id=11 Removed YUIInstallC (-2/8)
D/ResourcesManager(11854): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
V/ActivityThread( 6263): updateVisibility : ActivityRecord{2e4cb17a token=android.os.BinderProxy@3fc0078f {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
I/WebViewFactory(11854): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(11854): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(11854): Loading: webviewchromium
I/LibraryLoader(11854): Time to load native libraries: 4 ms (timestamps 4854-4858)
I/LibraryLoader(11854): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(11854): Binding Chromium to main looper Looper (main, tid 1) {3bd14bf5}
,I/LibraryLoader(11854): Expected native library version number "",actual native library version number ""
I/chromium(11854): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(11854): Initializing chromium process, renderers=0
,W/art     (11854): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(11854): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(11854): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(11854): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,W/chromium(11854): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium(11854): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (11854): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(11854): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(11854): CordovaWebView is running on device made by: samsung
,W/art     (11854): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11854): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity(11854): performCreate Call secproduct feature valuefalse
D/Activity(11854): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(11854): Render dirty regions requested: true
,D/ActivityManager( 3521): post active user change for 0
D/KnoxTimeoutHandler( 3521): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3521): handleActiveUserChange for user 0
,I/SurfaceFlinger( 2848): id=14 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService( 3521): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3521): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3521): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3521): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3521): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3521): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer(11854): Initialized EGL, version 1.4
,I/OpenGLRenderer(11854): HWUI protection enabled for context ,  &this =0xaf5ad1a0 ,&mEglDisplay = 1 , &mEglConfig = -1279692528 
,D/OpenGLRenderer(11854): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(11854): Enabling debug mode 0
,D/mali_winsys(11854): new_window_surface returns 0x3000,  [1440x2560]-format:1
,V/ActivityThread(11854): updateVisibility : ActivityRecord{33ce1c65 token=android.os.BinderProxy@1b47d900 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/InputMethodManagerService( 3521): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 3521): mDVFSHelper.release()
I/Timeline( 3521): Timeline: Activity_windows_visible id: ActivityRecord{e6d7fc5 u0 com.test.thalitest/.MainActivity t26} time:135216
,W/IInputConnectionWrapper(11854): showStatusIcon on inactive InputConnection
,I/Timeline(11854): Timeline: Activity_idle id: android.os.BinderProxy@1b47d900 time:135226
,D/JsMessageQueue(11854): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium(11854): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11854): 
,D/jxcore_app_log(11854): JniHelper::setJavaVM(0xb4d5c280), pthread_self() = -1358476672
,I/chromium(11854): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,W/jxcore-log(11854): Initializing JXcore engine
W/jxcore-log(11854): JXcore engine is ready
,E/auditd  ( 4604): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3521): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3521): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(11854): Starting JXcore engine
,W/jxcore-log(11854): Platform android
W/jxcore-log(11854): 
W/jxcore-log(11854): Process ARCH arm
W/jxcore-log(11854): 
,I/jxcore-log(11854): JXcore Cordova bridge is ready!
I/jxcore-log(11854): 
W/jxcore-log(11854): JXcore engine is started
,I/jxcore-log(11854): Toggling radios to true
I/jxcore-log(11854): 
,D/BluetoothAdapter(11854): enable()
D/BluetoothAdapter(11854): enable(): BT is already enabled..!
,D/WifiService( 3521): New client listening to asynchronous messages
,I/WifiManager(11854): packageName : com.test.thalitest
,D/SecContentProvider( 3521): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3521): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3521): mCursor = null
,D/WifiService( 3521): setWifiEnabled: true pid=11854, uid=10588
E/WifiService( 3521): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3521): Permission Denial: getCurrentUser() from pid=11854, uid=10588 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 3521): Failed getting userId using ActivityManagerNative
W/WifiService( 3521): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=11854, uid=10588 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3521): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3521): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3521): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3521): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3521): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider( 3521): name = wifi_on
,I/WifiService( 3521): disconnect: pid=11854, uid=10588
,I/wpa_supplicant( 3824): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log(11854): Radios toggled
I/jxcore-log(11854): 
,I/jxcore-log(11854): My device name is: samsung-SM-N910C
I/jxcore-log(11854): 
,I/wpa_supplicant( 3824): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3824): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 3824): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3824): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine( 3521): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 3824): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3824): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3824): Disconnected - do not scan
I/wpa_supplicant( 3824): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine( 3521): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3521): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3521): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3521): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine( 3521): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3521): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3521): do suspend true
,D/WifiP2pService( 3521): InactiveState{ what=143375 }
,D/WifiP2pService( 3521): P2pEnabledState{ what=143375 }
,D/CommandListener( 2843): Clearing all IP addresses on wlan0
,E/Netd    ( 2843): ifc_reset_connections failed on iface wlan0 for address 192.168.1.124/24 (Unknown error -1)
,D/StatusBar.NetworkController( 3688): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3688): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,E/WifiStateMachine( 3521): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService( 3521): updateNetworkInfo()
D/ConnectivityService( 3521): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3521): updateNetworkInfo()
D/ConnectivityService( 3521): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore( 3521): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/WifiTrafficPoller( 3521): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 3688): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3688): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3688): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3688): applyOpen
D/StatusBar.NetworkController( 3688): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3688): applyOpen
D/StatusBar.NetworkController( 3688): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3688): applyOpen
D/StatusBar.NetworkController( 3688): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3688): applyOpen
,E/WifiStateMachine( 3521): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 3824): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3824): P2P: Current p2p state = IDLE
I/wpa_supplicant( 3824): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 3824): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3824): First Scan Start
,I/Hs20UtilService( 4110): Starting #8
I/wpa_supplicant( 3824): Scan requested (ret=0) - scan timeout 30 seconds
I/Hs20UtilService( 4110): Message received 5007
,E/WifiStateMachine( 3521): ConnectModeState: Network connection lost 
,D/NearbySettings( 8813): MountReceiver.onReceive - Create HandlerThread
,D/NearbySettings( 8813): MountReceiver.onReceive - Start HandlerThread
,D/NearbySettings( 8813): MountReceiver.onReceive - Create mPrefHandler
D/NearbySettings( 8813): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 3521): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - processMessage - processMsg
V/NearbySettings( 8813): DMSUtil.isNetworkConnected - flag-null, state-null
,E/WifiStateMachine( 3521): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine( 3521): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3521): do suspend true
,D/WifiP2pService( 3521): InactiveState{ what=143375 }
D/WifiP2pService( 3521): P2pEnabledState{ what=143375 }
,I/NearbySettings( 8813): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/StatusBar.NetworkController( 3688): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3688): onWifiSignalChanged enabled=true enabledDesc:null
,D/CommandListener( 2843): Clearing all IP addresses on wlan0
D/ConnectivityService( 3521): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/WifiService( 3521): New client listening to asynchronous messages
D/EntConnectivity( 3521): Not allowed due to - mEnabled false
,D/ConnectivityManager.CallbackHandler( 3688): CM callback handler got msg 524292
D/ConnectivityService( 3521): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3521): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker( 3521): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
I/NearbySettings( 8813): DMSUtil.isNetworkConnected - P2P: IDLE
D/CSLegacyTypeTracker( 3521): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
I/NearbySettings( 8813): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
D/ConnectivityService( 3521): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/NearbySettings( 8813): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8813): MountReceiver.mPrefHandler - 7002
D/ConnectivityManager.CallbackHandler( 6781): CM callback handler got msg 524292
E/WifiStateMachine( 3521): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/TelephonyNetworkFactory( 3973): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiStateMachine( 3521): updateConfiguredNetworkExpiration - currTime: 1453202084392
D/WifiStateMachine( 3521): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
E/WifiStateMachine( 3521): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine( 3521): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine( 3521): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3521): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 3521): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3521): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine( 3521): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3521): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent( 3521): NetworkAgent: NetworkAgent channel lost
,D/EntConnectivity( 3521): Not allowed due to - mEnabled false
I/WifiTrafficPoller( 3521): evaluateTrafficStatsPolling
D/ConnectivityService( 3521): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,E/WifiStateMachine( 3521): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3521): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine( 3521): setDetailed state send new extra info"NG700"
,D/SecContentProvider2( 3521): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3521): mCursor = null
,D/Tethering( 3521): MasterInitialState.processMessage what=3
,D/StatusBar.NetworkController( 3688): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/SmartBondingService( 3521): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/STATUSBAR-WifiQuickSettingButton( 3688): onWifiSignalChanged enabled=true enabledDesc:null
D/SmartBondingService( 3521): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
V/NetworkStats( 3521): updateIfacesLocked()
V/NetworkStats( 3521): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 3521): UpdateStatsForKnox
D/SmartBondingService( 3521): getSBEnabled() enabled =false
D/SmartBondingService( 3521): getSBEnabled() enabled =false
D/SmartBondingService( 3521): getSBEnabled() enabled =false
,D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
V/NetworkStats( 3521): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
D/SmartBondingService( 3521): getNetworkEnabled : wifi : true mobile : false
D/StatusBar.NetworkController( 3688): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3688): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3688): updateDataNetType()
D/StatusBar.NetworkController( 3688): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3688): updateLTEICONDataNetType:0
,D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
V/NetworkStats( 3521): performPollLocked() took 5ms
,D/StatusBar.NetworkController( 3688): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3688): updateTelephonySignalStrength: hasService=false ss=null
,D/StatusBar.NetworkController( 3688): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3688): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3688): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3688): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3688): applyOpen
D/StatusBar.NetworkController( 3688): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3688): applyOpen
D/StatusBar.NetworkController( 3688): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3688): applyOpen
D/StatusBar.NetworkController( 3688): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3688): applyOpen
,I/SignOutReceiver(11468): NETWORK_STATE_CHANGED_ACTION
,D/SecContentProvider2( 3521): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3521): mCursor = null
,D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
,I/Hs20UtilService( 4110): Starting #9
I/Hs20UtilService( 4110): Message received 5007
,D/NearbySettings( 8813): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8813): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8813): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8813): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8813): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8813): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 8813): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11468): NETWORK_STATE_CHANGED_ACTION
,D/FileWriteThread_Telephony( 3973): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3973): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3973): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3973): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3973): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3973): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3973): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3973): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3973): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3973): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3973): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3973): FileWriteThread : threadType = 3
,D/ConnectivityService( 3521): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 3521): updateDataUsageMap
,I/ApplicationPolicy( 3521): updateDataUsageMap  idList is null 
D/SmartBondingService( 3521): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3521): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3521): getSBEnabled() enabled =false
D/SmartBondingService( 3521): getSBEnabled() enabled =false
D/SmartBondingService( 3521): getSBEnabled() enabled =false
,D/GpsLocationProvider( 3521): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3521): getNetworkEnabled : wifi : true mobile : false
,W/SLocation( 3521): No Active Data Connection
,I/DBG_DM  ( 6263): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/DBG_DM  ( 6263): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11946): MountEmulatedStorage()
E/Zygote  (11946): v2
I/libpersona(11946): KNOX_SDCARD checking this for 10110
I/libpersona(11946): KNOX_SDCARD not a persona
,I/SELinux (11946): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11946): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3521): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.iorg.vpn.cleanup.NetworkStateMonitor: pid=11946 uid=10110 gids={50110, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,E/SELinux (11946): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11946): TimaSignature is unavailable
,D/ActivityThread(11946): Added TimaKeyStore provider
,D/ResourcesManager(11946): creating new AssetManager and set to /data/app/com.facebook.appmanager-2/base.apk
,D/ACRA    (11946): ACRA is enabled for com.facebook.appmanager, intializing...
,I/DexLibLoader(11946): not using cross-dex optimization: ART in use
,I/art     (11946): Thread[1,tid=11946,WaitingForJniOnLoad,Thread*=0xb4d08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/app/com.facebook.appmanager-2/lib/arm/libfbjni.so"
,V/DexLibLoader(11946): about to lock: /data/data/com.facebook.appmanager/mdex_lock
,V/DexLibLoader(11946): locking /data/data/com.facebook.appmanager/mdex_lock took 0 ms
V/DexLibLoader(11946): Secondary program dex metadata: classes2.dex 29f80981f469a774a4884b3db2df17e0be227159 secondary.dex01.Canary
,D/DexLibLoader(11946): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex" is valid
D/DexLibLoader(11946): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex_opt" is valid
,W/art     (11946): Attempt to remove local handle scope entry from IRT, ignoring
D/DexLibLoader(11946): loading pre-built fallback odex files
,V/MultiDexClassLoader(11946): installing MultiDexClassLoader before application classloader
D/DexLibLoader(11946): released odex store lock
D/DexLibLoader(11946): DexLibLoader.loadAll took 20 ms
,W/ca      (11946): Verify
,W/LightSharedPreferencesImpl(11946): Failed to load preference file from Disk!
W/LightSharedPreferencesImpl(11946): java.io.FileNotFoundException: /data/data/com.facebook.appmanager/app_light_prefs/com.facebook.appmanager/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11946): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/LightSharedPreferencesImpl(11946): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/LightSharedPreferencesImpl(11946): 	at com.facebook.crudolib.b.k.a(LightSharedPreferencesStorage.java:56)
W/LightSharedPreferencesImpl(11946): 	at com.facebook.crudolib.b.g.run(LightSharedPreferencesImpl.java:61)
W/LightSharedPreferencesImpl(11946): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/LightSharedPreferencesImpl(11946): 	at com.facebook.common.executors.dj.run(WrappingExecutorService.java:77)
W/LightSharedPreferencesImpl(11946): 	at com.facebook.common.executors.u.run(DefaultConstrainedListeningExecutorService.java:327)
W/LightSharedPreferencesImpl(11946): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/LightSharedPreferencesImpl(11946): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/LightSharedPreferencesImpl(11946): 	at com.facebook.common.executors.cc.run(NamedThreadFactory.java:42)
W/LightSharedPreferencesImpl(11946): 	at java.lang.Thread.run(Thread.java:818)
W/LightSharedPreferencesImpl(11946): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11946): 	at libcore.io.Posix.open(Native Method)
W/LightSharedPreferencesImpl(11946): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/LightSharedPreferencesImpl(11946): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/LightSharedPreferencesImpl(11946): 	... 10 more
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11971): MountEmulatedStorage()
I/libpersona(11971): KNOX_SDCARD checking this for 1000
E/Zygote  (11971): v2
I/libpersona(11971): KNOX_SDCARD not a persona
,I/SELinux (11971): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11971): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11971): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=11971 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3521): Killing 11056:com.policydm/1000 (adj 15): bgCount ##31
,W/appmanager(:<default>):b(11946): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/appmanager(:<default>):b(11946): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/TimaKeyStoreProvider(11971): TimaSignature is unavailable
D/ActivityThread(11971): Added TimaKeyStore provider
,D/ResourcesManager(11971): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/PCWCLIENTTRACE_LOG(11971): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(11971): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(11971): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil(11971): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11971): sales region : global
I/PCWCLIENTTRACE_PushUtil(11971): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11971): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
I/PCWCLIENTTRACE_SYSTEMReceiver(11971): noConnectivity : true
,W/appmanager(:<default>):QuickExperimentControllerImpl(11946): Exposure of experiment com.facebook.common.network.l@3b66ff13 occurred when no user was logged in
,W/BroadcastQueue( 3521): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{56cb4a0 u0 ReceiverList{31c9c9a3 11946 com.facebook.appmanager/10110/u0 remote:1df7d4d2}}
,W/BroadcastQueue( 3521): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{56cb4a0 u0 ReceiverList{31c9c9a3 11946 com.facebook.appmanager/10110/u0 remote:1df7d4d2}}
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11994): MountEmulatedStorage()
I/libpersona(11994): KNOX_SDCARD checking this for 10135
E/Zygote  (11994): v2
I/libpersona(11994): KNOX_SDCARD not a persona
,I/SELinux (11994): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11994): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=11994 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (11994): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Killing 11071:com.sec.android.app.samsungapps/u0a13 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(11994): TimaSignature is unavailable
,D/ActivityThread(11994): Added TimaKeyStore provider
,D/ResourcesManager(11994): creating new AssetManager and set to /system/app/Music2/Music2.apk
,W/BroadcastQueue( 3521): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{11395764 u0 ReceiverList{a93ecf7 11946 com.facebook.appmanager/10110/u0 remote:13d9e0f6}}
,I/MusicStore(11994): Database version: 104
,D/ResourcesManager(11994): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11994): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11994): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (11994): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(11994): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (11994): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@311fa2f9: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(11994): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(11994): GMSCore installation verified
,I/ConfigStore(11994): Config Database version: 1
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11994): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11946): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/ContextImpl(11946): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/ContextImpl(11994): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
W/ContextImpl(11994): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
W/appmanager(:<default>):QuickExperimentControllerImpl(11946): Exposure of experiment com.facebook.imagepipeline.a.g@34a31ec9 occurred when no user was logged in
W/appmanager(:<default>):QuickExperimentControllerImpl(11946): Exposure of experiment com.facebook.imagepipeline.a.d@189a74da occurred when no user was logged in
,D/WifiDisplayAdapter( 3521): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3521): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3521): getStreamVolume 3 index 0
,I/MediaRouter(11994): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/wpa_supplicant( 3824): nl80211: Received scan results (6 BSSes)
I/wpa_supplicant( 3824): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3824): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3824): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 3824): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
E/WifiStateMachine( 3521): [1,453,202,085,446 ms] noteScanEnd no scan source
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/WifiStateMachine( 3521): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@1bb5cdd8 sup_state=SCANNING debouncing=false
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,I/art     (11946): Explicit concurrent mark sweep GC freed 48144(2MB) AllocSpace objects, 6(96KB) LOS objects, 22% free, 27MB/35MB, paused 796us total 26.825ms
,W/appmanager(:<default>):m(11946): No feature status reporters found; is this dead code?
,E/Zygote  (12029): MountEmulatedStorage()
I/libpersona(12029): KNOX_SDCARD checking this for 10002
E/Zygote  (12029): v2
I/libpersona(12029): KNOX_SDCARD not a persona
,I/SELinux (12029): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12029): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12029): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=12029 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/WifiStateMachine( 3521): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3521): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3521): setDetailed state send new extra info
,D/SecContentProvider2( 3521): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3521): mCursor = null
,I/art     ( 2878): Explicit concurrent mark sweep GC freed 8725(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 519us total 10.590ms
,D/WifiDisplayAdapter( 3521): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/art     ( 2878): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 259us total 7.988ms
,I/NetworkMonitor(11994): type=WIFI subType= reason=null isConnected=false
,I/ActivityManager( 3521): Killing 11089:com.sec.android.app.myfiles/u0a53 (adj 15): bgCount ##31
,I/art     ( 2878): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 262us total 7.925ms
,D/TimaKeyStoreProvider(12029): TimaSignature is unavailable
,D/ActivityThread(12029): Added TimaKeyStore provider
,D/ResourcesManager(12029): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/wpa_supplicant( 3824): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 3824): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 3824): Associated with C0.AA.48
,E/WifiStateMachine( 3521): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3521): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3521): setDetailed state send new extra info"NG700"
,D/SecContentProvider2( 3521): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3521): mCursor = null
,I/ActivityManager( 3521): Killing 10951:com.google.android.apps.docs/u0a101 (adj 13): bgCount ##31
,I/wpa_supplicant( 3824): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 3824): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3521): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3521): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,D/SecContentProvider2( 3521): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3521): mCursor = null
,I/wpa_supplicant( 3824): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 3824): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
I/wpa_supplicant( 3824): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/WifiStateMachine( 3521): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3521): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,I/wpa_supplicant( 3824): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3824): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 3824): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 3824): Blacklist: Clear (temp) 
I/wpa_supplicant( 3824): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3521): Network connection established
,D/WifiNative-HAL( 3521): callSECApiVoid - ID [50]
,E/WifiStateMachine( 3521): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/Zygote  (12049): MountEmulatedStorage()
,I/libpersona(12049): KNOX_SDCARD checking this for 1000
E/Zygote  (12049): v2
I/libpersona(12049): KNOX_SDCARD not a persona
I/SELinux (12049): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12049): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12049): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=12049 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/WifiStateMachine( 3521): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,E/WifiStateMachine( 3521): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService( 3521): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine( 3521): L2ConnectedState "NG700" nid=0
E/WifiConfigStore( 3521): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService( 3521): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 3521): updateNetworkInfo()
D/ConnectivityService( 3521): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,I/art     ( 3521): Explicit concurrent mark sweep GC freed 60581(3MB) AllocSpace objects, 14(224KB) LOS objects, 24% free, 49MB/65MB, paused 2.590ms total 89.027ms
,E/WifiStateMachine( 3521): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine( 3521): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3521): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3521): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/StatusBar.NetworkController( 3688): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3688): onWifiSignalChanged enabled=true enabledDesc:null
,D/TimaKeyStoreProvider(12049): TimaSignature is unavailable
,D/ActivityThread(12049): Added TimaKeyStore provider
,D/CommandListener( 2843): Setting iface cfg
,E/WifiStateMachine( 3521): Start Dhcp Watchdog 2
,D/SecContentProvider2( 3521): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3521): mCursor = null
,D/ResourcesManager(12049): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,E/WifiStateMachine( 3521): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3521): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/DIAGMON_AGENT(12049): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT(12049): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT(12049): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,E/WifiStateMachine( 3521): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3521): do suspend false
,I/DIAGMON_AGENT(12049): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(12049): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/SecContentProvider2( 3521): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3521): mCursor = null
D/WifiP2pService( 3521): InactiveState{ what=143375 }
D/WifiP2pService( 3521): P2pEnabledState{ what=143375 }
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/Zygote  (12067): MountEmulatedStorage()
I/libpersona(12067): KNOX_SDCARD checking this for 10012
E/Zygote  (12067): v2
I/libpersona(12067): KNOX_SDCARD not a persona
I/SELinux (12067): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12067): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12067): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=12067 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/TimaKeyStoreProvider(12067): TimaSignature is unavailable
D/ActivityThread(12067): Added TimaKeyStore provider
D/ResourcesManager(12067): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
I/ActivityManager( 3521): Killing 11113:com.sec.android.provider.badge/u0a82 (adj 15): bgCount ##31
E/lowmemorykiller( 2826): Error writing /proc/11113/oom_score_adj; errno=22
I/FOTA_Client(12067): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
I/FOTA_Client(12067): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
I/FOTA_Client(12067): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/Zygote  (12083): MountEmulatedStorage()
I/libpersona(12083): KNOX_SDCARD checking this for 10021
E/Zygote  (12083): v2
I/libpersona(12083): KNOX_SDCARD not a persona
I/SELinux (12083): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12083): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12083): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=12083 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
I/ActivityManager( 3521): Killing 11152:com.sec.spp.push/u0a39 (adj 15): bgCount ##31
E/lowmemorykiller( 2826): Error writing /proc/11152/oom_score_adj; errno=22
D/TimaKeyStoreProvider(12083): TimaSignature is unavailable
D/ActivityThread(12083): Added TimaKeyStore provider
D/ResourcesManager(12083): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
I/KLMS-2.4.521: (12083): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Jan 19 12:14:45 GMT+01:00 2016
I/KLMS-2.4.521: (12083): KLMSAbstractReciever(): onReceive().END.
I/KLMS-2.4.521: (12083): KLMSIntentService(): onCreate()
I/KLMS-2.4.521: (12083): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.4.521: (12083): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/KLMS-2.4.521: (12083): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/KLMS-2.4.521: (12083): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
I/KLMS-2.4.521: (12083): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
I/KLMS-2.4.521: (12083): StateImplV2(): networkChangeListener().END
E/Zygote  (12099): MountEmulatedStorage()
I/libpersona(12099): KNOX_SDCARD checking this for 10038
E/Zygote  (12099): v2
I/libpersona(12099): KNOX_SDCARD not a persona
I/SELinux (12099): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12099): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12099): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=12099 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
I/KLMS-2.4.521: (12083): KLMSIntentService(): onDestroy()
I/ActivityManager( 3521): Killing 11168:com.sec.android.app.soundalive/u0a59 (adj 15): bgCount ##31
D/TimaKeyStoreProvider(12099): TimaSignature is unavailable
D/ActivityThread(12099): Added TimaKeyStore provider
D/ResourcesManager(12099): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
E/dhcpcd  (12114): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/dhcpcd  (12114): version 5.5.6 starting
E/dhcpcd  (12114): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/SO_AGENT(12099): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/Zygote  (12120): MountEmulatedStorage()
I/libpersona(12120): KNOX_SDCARD checking this for 1000
E/Zygote  (12120): v2
I/libpersona(12120): KNOX_SDCARD not a persona
I/SELinux (12120): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3521): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=12120 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux (12120): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12120): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Killing 11204:com.wsomacp/u0a28 (adj 15): bgCount ##31
I/dhcpcd  (12114): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (12114): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (12114): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  (12114): bssid match
I/dhcpcd  (12114): wlan0: rebinding lease of 192.168.1.124
D/TimaKeyStoreProvider(12120): TimaSignature is unavailable
D/ActivityThread(12120): Added TimaKeyStore provider
D/ResourcesManager(12120): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/Zygote  (12141): MountEmulatedStorage()
I/libpersona(12141): KNOX_SDCARD checking this for 10039
E/Zygote  (12141): v2
I/libpersona(12141): KNOX_SDCARD not a persona
I/SELinux (12141): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12141): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12141): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=12141 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3521): Killing 11238:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##31
D/TimaKeyStoreProvider(12141): TimaSignature is unavailable
D/ActivityThread(12141): Added TimaKeyStore provider
D/ResourcesManager(12141): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
E/SPPClientService(12141): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(12141): [PushClientApplication] Push log off : This is Ship build version
E/SPPClientService(12141): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
D/SPPClientService(12141): PushLog.txt file is not deleted.
D/SPPClientService(12141): PushLog.txt file is not deleted.
D/SPPClientService(12141): ============PushLog. stop!
I/SA      (11283): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
I/SA      (11283): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      (11283): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      (11283): [SLFUCHKMGR] constructor called
E/SPPClientService(12141): [[SystemStateMonitorService]] No Active Internet
I/SA      (11283): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11283): [OR] == isSIMCardReady false ==
I/SA      (11283): [SCU] == networkStateCheck == false
I/SA      (11283): [OR] onReceive END
I/ActivityManager( 3521): Killing 11219:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
V/DownloadManager( 3714): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/Zygote  (12161): MountEmulatedStorage()
E/Zygote  (12161): v2
I/libpersona(12161): KNOX_SDCARD checking this for 10067
I/libpersona(12161): KNOX_SDCARD not a persona
I/SELinux (12161): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12161): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12161): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=12161 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
D/TimaKeyStoreProvider(12161): TimaSignature is unavailable
D/ActivityThread(12161): Added TimaKeyStore provider
D/ResourcesManager(12161): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
I/sCloudBackupApp(12161): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(12161): Other Intent
I/ActivityManager( 3521): Killing 11185:com.samsung.android.sdk.samsunglink/u0a42 (adj 13): bgCount ##31
D/accuweather( 5194): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/daemonapp( 3773): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
D/accuweather( 5194): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5194): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5194): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5194): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
D/accuweather( 5194): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/accuweather( 5194): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/Zygote  (12177): MountEmulatedStorage()
E/Zygote  (12177): v2
I/libpersona(12177): KNOX_SDCARD checking this for 1000
I/libpersona(12177): KNOX_SDCARD not a persona
I/SELinux (12177): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12177): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12177): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=12177 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/TimaKeyStoreProvider(12177): TimaSignature is unavailable
D/ActivityThread(12177): Added TimaKeyStore provider
D/ResourcesManager(12177): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
W/ResourcesManager(12177): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/KnoxUsageLogPro(12177): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro(12177): premStatus:2
I/KnoxUsageLogPro(12177): isEulaShown : false
I/KnoxUsageLogPro(12177): KnoxUsageReceiver onReceive : not Processible, just return
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/Zygote  (12192): MountEmulatedStorage()
E/Zygote  (12192): v2
I/libpersona(12192): KNOX_SDCARD checking this for 10090
I/libpersona(12192): KNOX_SDCARD not a persona
I/SELinux (12192): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12192): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12192): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=12192 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3521): Killing 11137:com.sec.android.automotive.drivelink/u0a102 (adj 13): bgCount ##31
D/TimaKeyStoreProvider(12192): TimaSignature is unavailable
D/ActivityThread(12192): Added TimaKeyStore provider
D/ResourcesManager(12192): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/Zygote  (12208): MountEmulatedStorage()
I/libpersona(12208): KNOX_SDCARD checking this for 10127
E/Zygote  (12208): v2
I/libpersona(12208): KNOX_SDCARD not a persona
I/SELinux (12208): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12208): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12208): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=12208 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3521): Killing 11304:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
D/TimaKeyStoreProvider(12208): TimaSignature is unavailable
D/ActivityThread(12208): Added TimaKeyStore provider
D/ResourcesManager(12208): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
D/KeyguardWallpaperUpdator(12208): cancelUpdateWallpaper
D/KeyguardWallpaperUpdator(12208): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12208): stopCheckCategoryVersion
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/Zygote  (12224): MountEmulatedStorage()
I/libpersona(12224): KNOX_SDCARD checking this for 10136
E/Zygote  (12224): v2
I/libpersona(12224): KNOX_SDCARD not a persona
I/SELinux (12224): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12224): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12224): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=12224 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3521): Killing 11335:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
I/art     ( 2878): Explicit concurrent mark sweep GC freed 8754(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 556us total 11.065ms
D/TimaKeyStoreProvider(12224): TimaSignature is unavailable
D/ActivityThread(12224): Added TimaKeyStore provider
I/art     ( 2878): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 445us total 8.753ms
D/ResourcesManager(12224): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
I/art     ( 2878): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 271us total 8.364ms
E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
W/ContextImpl(12224): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
W/ContextImpl(12224): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
W/ContextImpl(12224): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
W/ContextImpl(12224): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
I/WebViewFactory(12224): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(12224): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(12224): Loading: webviewchromium
I/LibraryLoader(12224): Time to load native libraries: 2 ms (timestamps 9029-9031)
I/LibraryLoader(12224): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider(12224): Binding Chromium to main looper Looper (main, tid 1) {1b2e75b5}
I/LibraryLoader(12224): Expected native library version number "",actual native library version number ""
I/chromium(12224): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(12224): Initializing chromium process, renderers=0
,W/art     (12224): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(12224): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(12224): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium(12224): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,W/AudioManagerAndroid(12224): Requires BLUETOOTH permission
,I/NSApplication(12224): Starting up...
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12292): MountEmulatedStorage()
I/libpersona(12292): KNOX_SDCARD checking this for 10150
E/Zygote  (12292): v2
I/libpersona(12292): KNOX_SDCARD not a persona
,I/SELinux (12292): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12292): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12292): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=12292 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager( 3521): Killing 11355:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12292): TimaSignature is unavailable
,D/ActivityThread(12292): Added TimaKeyStore provider
,D/ResourcesManager(12292): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(12292): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12292): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager(12292): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect(12292): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12292): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect(12292): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12307): MountEmulatedStorage()
I/libpersona(12307): KNOX_SDCARD checking this for 10178
E/Zygote  (12307): v2
I/libpersona(12307): KNOX_SDCARD not a persona
I/SELinux (12307): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12307): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12307): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=12307 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager( 3521): Killing 11371:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12307): TimaSignature is unavailable
,D/ActivityThread(12307): Added TimaKeyStore provider
,D/ResourcesManager(12307): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(12307): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager(12307): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12307): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12307): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12307): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12307): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService( 3521): exchangeData() failure , invalid userId
,D/RCPManagerService( 3521): exchangeData() failure , invalid userId
,D/RCPManagerService( 3521): exchangeData() failure , invalid userId
,D/RCPManagerService( 3521): exchangeData() failure , invalid userId
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12330): MountEmulatedStorage()
I/libpersona(12330): KNOX_SDCARD checking this for 10082
E/Zygote  (12330): v2
I/libpersona(12330): KNOX_SDCARD not a persona
I/SELinux (12330): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12330): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12330): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=12330 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,D/RCPManagerService( 3521): exchangeData() failure , invalid userId
,D/RCPManagerService( 3521): exchangeData() failure , invalid userId
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(12330): TimaSignature is unavailable
D/ActivityThread(12330): Added TimaKeyStore provider
,E/Zygote  (12346): MountEmulatedStorage()
I/libpersona(12346): KNOX_SDCARD checking this for 1000
E/Zygote  (12346): v2
I/libpersona(12346): KNOX_SDCARD not a persona
,I/SELinux (12346): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12346): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=12346 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (12346): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Killing 11386:com.samsung.helphub/1000 (adj 13): bgCount ##31
,I/ActivityManager( 3521): Killing 11490:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##31
,D/ResourcesManager(12330): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/TimaKeyStoreProvider(12346): TimaSignature is unavailable
,D/ActivityThread(12346): Added TimaKeyStore provider
,D/ResourcesManager(12346): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/BadgeProvider(12330): onCreate
D/BadgeProvider(12330): DatabaseHelper
,D/BadgeProvider(12330): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/ActivityManager( 3521): Killing 11508:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
,D/BadgeProvider(12330): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12330): sendNotify, [notify] : null
D/BadgeProvider(12330): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12330): update, [BadgeCount] : badgecount=0
D/BadgeProvider(12330): update, [UpdateCount] : 1
,D/Launcher.Model( 3996): reloadBadges entered.
,I/iu.Environment( 6781): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 6781): num queued entries: 0
,I/iu.UploadsManager( 6781): num updated entries: 0
I/iu.SyncManager( 6781): NEXT; no task
,W/ActivityManager( 3521): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12364): MountEmulatedStorage()
E/Zygote  (12364): v2
I/libpersona(12364): KNOX_SDCARD checking this for 10013
I/libpersona(12364): KNOX_SDCARD not a persona
,I/SELinux (12364): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12364): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=12364 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux (12364): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12364): TimaSignature is unavailable
,D/ActivityThread(12364): Added TimaKeyStore provider
,D/ResourcesManager(12364): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,I/ActivityManager( 3521): Killing 11526:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##31
,I/Hs20UtilService( 4110): Starting #10
,I/Hs20UtilService( 4110): Message received 5007
,D/NearbySettings( 8813): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8813): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8813): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 8813): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8813): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8813): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8813): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11468): NETWORK_STATE_CHANGED_ACTION
,I/dhcpcd  (12114): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
,I/jxcore-log(11854): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log(11854): 
,I/dhcpcd  (12114): wlan0: leased 192.168.1.124 for 86400 seconds
,E/WifiStateMachine( 3521): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3521): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine( 3521): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine( 3521): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  ( 3521): do suspend true
,D/WifiP2pService( 3521): InactiveState{ what=143375 }
D/WifiP2pService( 3521): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 3521): WifiStateMachine DHCP successful
,E/WifiStateMachine( 3521): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3521): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine( 3521): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3521): Not connected state, yet.
E/WifiStateMachine( 3521): VerifyingLinkState enter
,D/StatusBar.NetworkController( 3688): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3688): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiStateMachine( 3521): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine( 3521): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3521): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3521): callSECApiInt - ID [210]
E/WifiStateMachine( 3521): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
E/ConnectivityService( 3521): updateNetworkInfo()
,D/ConnectivityService( 3521): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 3521): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 3521): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 3521): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 3521): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 3521): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3521): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 3688): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3688): onWifiSignalChanged enabled=true enabledDesc:null
,I/Hs20UtilService( 4110): Starting #11
,I/Hs20UtilService( 4110): Message received 5007
,D/NearbySettings( 8813): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8813): MountReceiver.onReceive - Keep current state
,E/WifiStateMachine( 3521): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine( 3521): Now, connected state.
E/WifiStateMachine( 3521): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,D/ConnectivityService( 3521): Adding Route [fe80::/64 -> :: wlan0] to network 503
,E/WifiStateMachine( 3521): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
D/ConnectivityService( 3521): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService( 3521): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/WifiStateMachine( 3521): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
E/ConnectivityService( 3521): Unexpected mtu value: 0, wlan0
,I/WifiTrafficPoller( 3521): evaluateTrafficStatsPolling
V/        ( 2843): QcRouteController
,E/WifiStateMachine( 3521): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/StatusBar.NetworkController( 3688): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3688): onWifiSignalChanged enabled=true enabledDesc:null
,I/WifiTrafficPoller( 3521): evaluateTrafficStatsPolling
,V/        ( 2843): QcRouteController
D/WifiNative-HAL( 3521): callSECApiVoid - ID [212]
,D/StatusBar.NetworkController( 3688): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3688): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3688): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3688): applyOpen
D/StatusBar.NetworkController( 3688): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3688): applyOpen
D/StatusBar.NetworkController( 3688): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3688): applyOpen
D/StatusBar.NetworkController( 3688): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3688): applyOpen
I/WifiStateMachine( 3521): REQUEST_POWER_SAVE_ON
,V/        ( 2843): QcRouteController
,I/SignOutReceiver(11468): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2843): QcRouteController
,I/Hs20UtilService( 4110): Starting #12
I/Hs20UtilService( 4110): Message received 5007
,D/NearbySettings( 8813): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8813): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8813): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,V/        ( 2843): QcRouteController
I/NearbySettings( 8813): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8813): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8813): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 8813): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11468): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2843): QcRouteController
,V/        ( 2843): QcRouteController
,I/Hs20UtilService( 4110): Starting #13
,D/NearbySettings( 8813): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/Hs20UtilService( 4110): Message received 5007
I/NearbySettings( 8813): MountReceiver.onReceive - Keep current state
,V/        ( 2843): QcRouteController
,I/WifiStateMachine( 3521): callSECApi what=220
D/WifiStateMachine( 3521): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/ConnectivityService( 3521): Setting Dns servers for network 503 to [/192.168.1.1]
,D/ConnectivityService( 3521): LTETest block dns file not exists
D/ConnectivityService( 3521): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 3521): updateNetworkInfo()
D/ConnectivityService( 3521): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3521): updateNetworkInfo()
D/ConnectivityService( 3521): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
I/SignOutReceiver(11468): NETWORK_STATE_CHANGED_ACTION
D/ConnectivityService( 3521): rematching NetworkAgentInfo [WIFI () - 503]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3521): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3521): Connected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3521): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3521): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 3521):    accepting network in place of null
,D/TelephonyNetworkFactory( 3973): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CSLegacyTypeTracker( 3521): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
E/CSLegacyTypeTracker( 3521): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/ConnectivityService( 3521): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService( 3521): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/EntConnectivity( 3521): Not allowed due to - mEnabled false
,D/ConnectivityService( 3521): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 3688): CM callback handler got msg 524290
D/Tethering( 3521): MasterInitialState.processMessage what=3
,D/ConnectivityManager.CallbackHandler( 6781): CM callback handler got msg 524290
D/SmartBondingService( 3521): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService( 3521): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3521): getSBEnabled() enabled =false
D/SmartBondingService( 3521): getSBEnabled() enabled =false
D/SmartBondingService( 3521): getSBEnabled() enabled =false
,D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
V/NetworkStats( 3521): updateIfacesLocked()
V/NetworkStats( 3521): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 3521): UpdateStatsForKnox
,D/SmartBondingService( 3521): getNetworkEnabled : wifi : true mobile : false
,D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
V/NetworkStats( 3521): performPollLocked() took 3ms
,I/System.out( 3521): (HTTPLog)-Static: isSBSettingEnabled false
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
,D/EnterpriseController( 2843): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2843): getNetworkForDns: using netid 503 for uid 1000
,D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
V/NetworkStats( 3521): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
,I/SurfaceFlinger( 2848): id=15 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 3521): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3521
,D/mali_winsys( 3688): new_window_surface returns 0x3000,  [1120x201]-format:1
,D/StatusBar.NetworkController( 3688): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3688): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3688): updateDataNetType()
D/StatusBar.NetworkController( 3688): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3688): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3688): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3688): updateTelephonySignalStrength: hasService=false ss=null
,D/StatusBar.NetworkController( 3688): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3688): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3688): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3688): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3688): applyOpen
D/StatusBar.NetworkController( 3688): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3688): applyOpen
D/StatusBar.NetworkController( 3688): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3688): applyOpen
D/StatusBar.NetworkController( 3688): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3688): applyOpen
,I/System.out( 3521): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/jxcore-log(11854): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log(11854): 
,I/jxcore-log(11854): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log(11854): 
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3521): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 19 Jan 2016 11:14:47 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453202087524], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453202087501]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3521): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3521): Validated
,D/ConnectivityService( 3521): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3521): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3521): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 3521): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 3688): CM callback handler got msg 524290
D/ConnectivityService( 3521): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 6781): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 3688): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3688): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3688): updateDataNetType()
D/StatusBar.NetworkController( 3688): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3688): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3688): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3688): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3688): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 3688): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3688): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,I/jxcore-log(11854): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log(11854): 
,I/jxcore-log(11854): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log(11854): 
,I/jxcore-log(11854): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log(11854): 
,I/jxcore-log(11854): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log(11854): 
,D/ConnectivityService( 3521): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3521): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3521): SmartBondingReceiver: wifi is connected
D/SmartBondingService( 3521): SmartBondingReceiver: wifi ap is not changed
,D/SmartBondingService( 3521): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService( 3521): getSBEnabled() enabled =false
D/SmartBondingService( 3521): getSBEnabled() enabled =false
D/SmartBondingService( 3521): getSBEnabled() enabled =false
,D/SmartBondingService( 3521): getNetworkEnabled : wifi : true mobile : false
,D/GpsLocationProvider( 3521): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 6263): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 6263): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/NetworkMonitor(11994): type=WIFI subType= reason=null isConnected=true
,W/ResourceType( 5358): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5358): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,I/PCWCLIENTTRACE_PushUtil(11971): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11971): sales region : global
I/PCWCLIENTTRACE_PushUtil(11971): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11971): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/SecContentProvider2( 3521): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3521): mCursor = null
,I/DIAGMON_AGENT(12049): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(12049): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/FOTA_Client(12067): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(12067): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(12067): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.521: (12083): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Jan 19 12:14:48 GMT+01:00 2016
,I/KLMS-2.4.521: (12083): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (12083): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12083): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/SO_AGENT(12099): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,I/KLMS-2.4.521: (12083): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (12083): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12083): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (12083): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.521: (12083): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.521: (12083): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.521: (12083): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.4.521: (12083): StateImplV2(): networkChangeListener().END
,I/KLMS-2.4.521: (12083): KLMSIntentService(): onDestroy()
,E/SPPClientService(12141): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      (11283): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11283): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (11283): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (11283): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11283): [OR] == isSIMCardReady false ==
,I/SA      (11283): [SCU] == networkStateCheck == true
I/SA      (11283): [DM] getCountryCodeFromCSC : PL
I/SA      (11283): isChinaCountryCode : false
I/SA      (11283): [SCU] is ChinestModel Data Restricted   : false
I/SA      (11283): [OR] == networkStateCheck true ==
,I/SA      (11283): [OR] GetMyCountryZoneTask
I/SA      (11283): [OR] onReceive END
I/SA      (11283): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 3714): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      (11283): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (11283): [SSP] query invoked
,I/SCloudBackupReceiver(12161): Other Intent
,I/SA      (11283): [TPMU] GetMccFromDB : null
I/SA      (11283): [SCU] getMccFromPreferece mcc = 260
I/SA      (11283): [TPM] isNoProxy(default) : true
,D/accuweather( 5194): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3773): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,D/accuweather( 5194): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5194): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5194): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5194): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5194): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5194): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro(12177): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro(12177): premStatus:2
,I/KnoxUsageLogPro(12177): isEulaShown : false
I/KnoxUsageLogPro(12177): KnoxUsageReceiver onReceive : not Processible, just return
,D/KeyguardWallpaperUpdator(12208): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12208): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12208): stopCheckCategoryVersion
,D/QuickConnect(12292): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12292): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect(12292): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 3521): exchangeData() failure , invalid userId
,D/RCPManagerService( 3521): exchangeData() failure , invalid userId
,I/iu.Environment( 6781): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 6781): num queued entries: 0
,I/iu.UploadsManager( 6781): num updated entries: 0
,I/iu.SyncManager( 6781): NEXT; no task
,D/EnterpriseController( 2843): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2843): getNetworkForDns: using netid 503 for uid 10014
,D/WaitQueueForNetworkActivate(12364): notifyNetworkActivated
,W/ContextImpl(12364): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3521): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/hcjo    (12364): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12364): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12364): exit::IDLE
D/InitializeManagerStateMachine(12364): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12364): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12364): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12364): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12364): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12364): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12364): entry::SUCCESS
D/hcjo    (12364): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (12364): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12364): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine(12364): exit::SUCCESS
D/InitializeManagerStateMachine(12364): entry::IDLE
,E/WifiStateMachine( 3521): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3521): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityService( 3521): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
V/        ( 2843): QcRouteController
,D/SmartBondingService( 3521): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/SmartBondingService( 3521): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3521): getSBEnabled() enabled =false
D/SmartBondingService( 3521): getSBEnabled() enabled =false
D/SmartBondingService( 3521): getSBEnabled() enabled =false
,I/SA      (11283): [RC New] Execute method=[GET] start
,V/        ( 2843): QcRouteController
,W/NetworkManagementService( 3521): route cmd failed: 
W/NetworkManagementService( 3521): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '76 route replace src v6 wlan0 fe80::92b6:86ff:fe43:731c 2 ::' failed with '400 76 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService( 3521): '
W/NetworkManagementService( 3521): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService( 3521): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService( 3521): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService( 3521): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService( 3521): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService( 3521): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5738)
W/NetworkManagementService( 3521): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5545)
W/NetworkManagementService( 3521): 	at com.android.server.ConnectivityService.access$2600(ConnectivityService.java:231)
W/NetworkManagementService( 3521): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2436)
W/NetworkManagementService( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ConnectivityService( 3521): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 3688): CM callback handler got msg 524295
D/ConnectivityService( 3521): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 6781): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 3688): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 6781): CM callback handler got msg 524295
I/SA      (11283): [RC New] Security=[true]
I/System.out(11283): Thread-1550(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out(11283): Thread-1550(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11283): Thread-1550(ApacheHTTPLog):isShipBuild true
I/System.out(11283): Thread-1550(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/EnterpriseController( 2843): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2843): getNetworkForDns: using netid 503 for uid 10045
,D/ConnectivityService( 3521): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/GCM     ( 6781): Message from null null
E/GCM     ( 6781): Dropping message from null
,I/SA      (11283): [RC New] [v2liruge] api execute + 622
I/SA      (11283): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out(11283): AsyncTask #1 calls detatch()
I/SA      (11283): [TPMU] getNetworkMcc : 
,I/SA      (11283): [SCU] saveMccToPreferece Start
I/SA      (11283): [SCU] RegionMCC : 260
I/SA      (11283): [SSP] query invoked
,I/SA      (11283): [TPMU] GetMccFromDB : null
I/SA      (11283): [SCU] getMccFromPreferece mcc = 260
I/SA      (11283): [SCU] saveMccToPreferece End
,I/SA      (11283): [RC New] executeRequest [v2liruge] end. 644
I/SA      (11283): [RC New] Execute end
I/SA      (11283): [OR] GetMyCountryZoneTask mcc = 260
I/SA      (11283): [OR] GetMyCountryZoneTask Success
,I/jxcore-log(11854): Test app app.js loaded
I/jxcore-log(11854): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11854): setDiscoveryMode: Mode set to BLE
,I/jxcore-log(11854): BLE advertisement is supported
I/jxcore-log(11854): 
,I/chromium(11854): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/dhcpcd  (12114): wlan0: sending IPv6 Router Solicitation
,D/WearableService( 4645): callingUid 10014, callindPid: 4645
,D/ResourcesManager(11994): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11994): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11994): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory(11994): Using the GMSCore's GoogleHttpClient
,D/WearableClient(11994): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11994): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11994): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11994): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(11994): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils(11994): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/WifiStateMachine( 3521): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine( 3521): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/art     ( 3521): Explicit concurrent mark sweep GC freed 55148(3MB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 49MB/65MB, paused 2.387ms total 156.930ms
,I/MusicLeanback(11994): Conditions not met for autocaching.
I/MusicLeanback(11994): Stop autocaching.
,E/ActivityThread(11994): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@339c9f7b that was originally bound here
E/ActivityThread(11994): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@339c9f7b that was originally bound here
E/ActivityThread(11994): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(11994): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(11994): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(11994): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(11994): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(11994): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(11994): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11994): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11994): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11994): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(11994): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(11994): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(11994): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(11994): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(11994): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(11994): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(11994): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(11994): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(11994): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(11994): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(11994): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(11994): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(11994): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(11994): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(11994): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/SurfaceFlinger( 2848): id=15 Removed Uoast (8/9)
,I/SurfaceFlinger( 2848): id=15 Removed Uoast (-2/9)
,D/PowerManagerService( 3521): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3521) eventTime = 143443
,D/PowerManagerService( 3521): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3521 (0x0)
D/PowerManagerService( 3521): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3521, ws=WorkSource{10060}) (elapsedTime=3492)
,I/GAV4    (12224): Thread[GAThread,5,main]: No campaign data found.
,D/SSRM:n  ( 3521): SIOP:: AP = 290, PST = 270, CUR = 60
,I/PowerManagerService( 3521): [PWL] Off : 50s ago
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:-199, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:115
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3688): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3688): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3688):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3688): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3688): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3688): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/PackageManager( 3521): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/PCWCLIENTTRACE_SYSTEMReceiver(11971): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil(11971): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE(11971): ================================================
,I/CSTORAGE(11971):  CSTORAGE_SKM_LIB v1.0.15
I/CSTORAGE(11971): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI(11971): [GetString-S]
E/art     (11971): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
W/PCWCLIENTTRACE_SecurePreferencesJNI(11971): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI(11971): [GetString-E]
I/PCWCLIENTTRACE_PushUtil(11971): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11971): sales region : global
I/PCWCLIENTTRACE_PushUtil(11971): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler(11971): [ensureRegistration] - No Samsung account
,I/dhcpcd  (12114): wlan0: sending IPv6 Router Solicitation
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/dhcpcd  (12114): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  (12114): wlan0: no IPv6 Routers available
,D/PreloadUpdateManagerStateMachine(12364): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(12364): exit::IDLE
,D/PreloadUpdateManagerStateMachine(12364): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (12364): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    (12364): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine(12364): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine(12364): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine(12364): entry::IDLE
,V/AlarmManager( 3521): waitForAlarm result :8
,D/SSRM:n  ( 3521): SIOP:: AP = 270, PST = 270, CUR = -199
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:-25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:81
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3688): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3688): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3688):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3688): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3688): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3688): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ActivityManager( 3521): Waited long enough for: ServiceRecord{6fbddfa u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,E/Watchdog( 3521): !@Sync 5
,D/SSRM:n  ( 3521): SIOP:: AP = 260, PST = 269, CUR = -25
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:71
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3688): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3688): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3688):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3688): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3688): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3688): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3521): [PWL] Off : 75s ago
,D/SSRM:n  ( 3521): SIOP:: AP = 250, PST = 268, CUR = 35
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:52, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:47
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3688): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3688): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3688):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3688): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3688): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3688): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ProcessCpuTracker( 3521): Skipping unknown process pid 12593
,I/ClearcutLoggerApiImpl( 4645): disconnect managed GoogleApiClient
,D/SSRM:n  ( 3521): SIOP:: AP = 250, PST = 267, CUR = 52
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:56, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:78
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3688): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3688): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3688):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3688): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3688): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3688): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3521): !@Sync 6
,D/SSRM:n  ( 3521): SIOP:: AP = 250, PST = 266, CUR = 56
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:54, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:46
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3688): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3688): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3688):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3688): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3688): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3688): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3521): [PWL] Off : 105s ago
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 260, CUR = 54
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:52, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:61
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3688): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3688): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3688):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3688): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3688): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3688): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 258, CUR = 52
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:49, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:44
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3688): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3688): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3688):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3688): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3688): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3688): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3521): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3688): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3688): handleTimeUpdate
,D/KeyguardEffectViewController( 3688): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3688): *** don't update sliding image ***
,D/DateView( 3688): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3688): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/Watchdog( 3521): !@Sync 7
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 257, CUR = 49
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:46, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:45
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3688): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3688): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3688):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3688): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3688): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3688): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3521): [PWL] Off : 140s ago
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 256, CUR = 46,
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:43, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3688): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3688): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3688):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3688): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3688): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3688): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 252, CUR = 43
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:41, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:38
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3688): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3688): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3688):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3688): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3688): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3688): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3521): !@Sync 8
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 250, CUR = 41
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3688): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3688): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3688):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3688): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3688): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3688): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 248, CUR = 39
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:38, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3688): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3688): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3688):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5649): Disconnected process message: 10
,D/BatteryMeterView( 3688): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3688): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3688): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11854): --= Surplus to requirements =--
I/jxcore-log(11854): 
I/jxcore-log(11854): ****TEST TOOK:  ms ****
I/jxcore-log(11854): 
I/jxcore-log(11854): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(11854): 
,D/AndroidRuntime(12704): 
D/AndroidRuntime(12704): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(12704): CheckJNI is OFF
,D/AndroidRuntime(12704): readGMSProperty: start
D/AndroidRuntime(12704): readGMSProperty: already setted!!
,D/AndroidRuntime(12704): readGMSProperty: end
D/AndroidRuntime(12704): addProductProperty: start
,E/AffinityControl(12704): AffinityControl: registerfunction enter
,D/AndroidRuntime(12704): Calling main entry com.android.commands.pm.Pm
,D/PackageManager( 3521): START PACKAGE DELETE: observer{747314304}
D/PackageManager( 3521): pkg{<packageName>}
D/PackageManager( 3521): user{0}
D/PackageManager( 3521): caller{2000}
D/PackageManager( 3521): flags{3}
,D/PersonaManagerService( 3521): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 3521): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 3521): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3521): isFromApprovedUnInstaller: isApproved before exit: true
,D/PackageManager( 3521): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3521): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 3521): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 3521): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 3521): getApplicationUninstallationEnabled
,D/ApplicationPolicy( 3521): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 3521): !@killApplicatoin: 10588, uninstall pkg
I/ActivityManager( 3521): Force stopping com.test.thalitest appid=10588 user=-1: uninstall pkg
,I/ActivityManager( 3521): Killing 11854:com.test.thalitest/u0a588 (adj 0): stop com.test.thalitest
,I/ActivityManager( 3521):   Force finishing activity ActivityRecord{e6d7fc5 u0 com.test.thalitest/.MainActivity t26}
,W/ActivityManager( 3521): mDVFSHelper.acquire()
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/PackageSettings( 3521): Skipping PackageSetting{37ebb65c com.example.hello/10563} due to missing metadata
,E/JavaBinder( 3521): !!! FAILED BINDER TRANSACTION !!!
,I/DBG_DM  ( 6263): [com.wssyncmldm.ui.XUIInstallConfirmActivity(456/onResume)] 
,D/PointerIcon( 3521): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 3521): setMouseCustomIcon IconType is same.101
,D/PointerIcon( 3521): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3521): setHoveringSpenCustomIcon IconType is same.1
,D/WifiService( 3521): Client connection lost with reason: 4
,I/WindowState( 3521): WIN DEATH: Window{17220db3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger( 2848): id=14 Removed NainActivit (5/8)
,I/SurfaceFlinger( 2848): id=14 Removed NainActivit (-2/8)
,I/SurfaceFlinger( 2848): id=14 Removed NainActivit (-2/8)
,I/DBG_DM  ( 6263): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 10
,I/ActivityManager( 3521): Force stopping com.test.thalitest appid=10588 user=0: pkg removed
,E/libprocessgroup( 3521): failed to kill 1 processes for processgroup 11854
,I/DBG_DM  ( 6263): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,I/DBG_DM  ( 6263): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6263): [com.wssyncmldm.ui.XUIInstallConfirmActivity(466/onResume)] Postpone Count : 10
,I/DBG_DM  ( 6263): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,I/art     ( 9047): Explicit concurrent mark sweep GC freed 30852(1709KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.078ms total 55.485ms
,I/DBG_DM  ( 6263): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/art     ( 4049): Explicit concurrent mark sweep GC freed 30954(1918KB) AllocSpace objects, 0(0B) LOS objects, 21% free, 28MB/36MB, paused 1.440ms total 98.581ms
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/InputReader( 3521): Reconfiguring input devices.  changes=0x00000010
E/SamsungIME( 4484): mOCRHelper is null
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
I/art     ( 6781): Explicit concurrent mark sweep GC freed 28339(1600KB) AllocSpace objects, 3(48KB) LOS objects, 20% free, 31MB/39MB, paused 1.826ms total 127.075ms
,W/GeofencerStateMachine( 4645): Ignoring removeGeofence because network location is disabled.
,D/LWLocationManager(11546): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(11546): getLastUiLocationId() : mLastUiLocationId = -100
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/EnterpriseDeviceManagerService( 3521): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3521): Admin package name: com.google.android.gms
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,E/Zygote  (12737): MountEmulatedStorage()
E/Zygote  (12737): v2
I/libpersona(12737): KNOX_SDCARD checking this for 10063
I/libpersona(12737): KNOX_SDCARD not a persona
,I/SELinux (12737): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3521): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=12737 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,I/SELinux (12737): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12737): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/DBG_DM  ( 6263): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,W/ResourceType( 5358): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5358): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/SecContentProvider2( 3521): uri = 14 selection = getSealedState
D/SecContentProvider2( 3521): mCursor = null
,D/ApplicationPolicy( 3521): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3521): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,W/ResourcesManager( 3521): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 3521): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 3521): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3521): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider(12737): TimaSignature is unavailable
,D/ActivityThread(12737): Added TimaKeyStore provider
,W/ResourcesManager( 3521): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/DBG_DM  ( 6263): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 10
,W/ResourcesManager( 3521): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/DBG_DM  ( 6263): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,I/art     ( 3521): Explicit concurrent mark sweep GC freed 28733(2MB) AllocSpace objects, 45(720KB) LOS objects, 24% free, 49MB/65MB, paused 3.290ms total 200.470ms
,I/art     ( 3521): WaitForGcToComplete blocked for 130.329ms for cause Explicit
D/ResourcesManager( 3521): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/DBG_DM  ( 6263): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6263): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 6263): [llIIlIIlIllIllIlllII(376/llIIllllIIlllIIIIlll)] 
,I/DBG_DM  ( 6263): [IIlIIIlllllIIlIIIlII(339/llllIlIIIllllIIlIlll)] No need to check encryption status
,I/DBG_DM  ( 6263): [llIIlIIlIllIllIlllII(405/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ActivityManager( 3521): post active user change for 0
D/KnoxTimeoutHandler( 3521): postActiveUserChange for user 0
,I/DBG_DM  ( 6263): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(12737): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,I/SurfaceFlinger( 2848): id=16 createSurf (1440x2560),2 flag=404, YUIInstallC
,D/StatusBarManagerService( 3521): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/ResourcesManager(11546): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/StatusBarManagerService( 3521): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,D/PointerIcon( 3521): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3521): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3521): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3521): setHoveringSpenCustomIcon IconType is same.1
,V/ActivityThread( 6263): updateVisibility : ActivityRecord{2e4cb17a token=android.os.BinderProxy@3fc0078f {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/InputMethodManagerService( 3521): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/VRSetupWizardStub/PackageIntentReceiver(12737): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(12737): Action Package Remove
W/InputMethodManagerService( 3521): Got RemoteException sending setActive(false) notification to pid 11854 uid 10588
D/VRSetupWizardStub/PackageIntentReceiver(12737): packagename:com.test.thalitest
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ResourcesManager(11546): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,I/KLMS-2.4.521: (12083): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Jan 19 12:16:55 GMT+01:00 2016
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,I/KLMS-2.4.521: (12083): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 3521): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3521): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/KLMS-2.4.521: (12083): KLMSIntentService(): onCreate()
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
I/KLMS-2.4.521: (12083): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(11546): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,I/KLMS-2.4.521: (12083): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,I/KLMS-2.4.521: (12083): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12083): KLMSIntentService(): PACKAGE_REMOVED
,I/KLMS-2.4.521: (12083): KLMSIntentService(): listeningToPackageRemoved().START
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,I/KLMS-2.4.521: (12083): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,D/ResourcesManager(11546): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,E/Zygote  (12757): MountEmulatedStorage()
I/libpersona(12757): KNOX_SDCARD checking this for 10106
E/Zygote  (12757): v2
I/libpersona(12757): KNOX_SDCARD not a persona
,I/SELinux (12757): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/Timeline( 6263): Timeline: Activity_idle id: android.os.BinderProxy@3fc0078f time:268023
,I/SELinux (12757): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12757): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=12757 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,D/ResourcesManager( 3521): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/RCPManager(12177):  in createShortcut() for packageName: com.test.thalitest userId0
,D/RCPManagerService( 3521):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3521): queryAllProviders():  providerCallBack is not register for 0
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(12757): TimaSignature is unavailable
,D/ActivityThread(12757): Added TimaKeyStore provider
,D/SecContentProvider2( 3521): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3521): mCursor = null
,D/ResourcesManager(11546): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,E/Zygote  (12772): MountEmulatedStorage()
E/Zygote  (12772): v2
I/libpersona(12772): KNOX_SDCARD checking this for 10050
I/libpersona(12772): KNOX_SDCARD not a persona
,I/SELinux (12772): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12772): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=12772 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
E/SELinux (12772): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/RegisteredServicesCache( 3961): empty dynamic service
,D/TimaKeyStoreProvider(12772): TimaSignature is unavailable
,D/ActivityThread(12772): Added TimaKeyStore provider
,W/ActivityManager( 3521): mDVFSHelper.release()
I/Timeline( 3521): Timeline: Activity_windows_visible id: ActivityRecord{2a270a9e u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t24} time:268087
,D/ResourcesManager(11546): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(12757): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(12772): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager(12772): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(12772): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/elm:14491(12757): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
W/ResourcesManager(12772): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12772): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12772): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(12772): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/elm:14491(12757): ELMEngine.ELMEngine( context ).
W/ResourcesManager(12772): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12772): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/elm:14491(12757): MDMBridge.setEnterpriseBridge()
,D/ResourcesManager(11546): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,I/KLMS-2.4.521: (12083): KLMSIntentService(): listeningToPackageRemoved().END
,E/Zygote  (12787): MountEmulatedStorage()
,E/Zygote  (12787): v2
I/libpersona(12787): KNOX_SDCARD checking this for 10101
I/libpersona(12787): KNOX_SDCARD not a persona
,I/SELinux (12787): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,I/SELinux (12787): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12787): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/ResourcesManager(11546): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,I/ActivityManager( 3521): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=12787 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/elm:14491(12757): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:14491(12757): ElmAgentService : onCreate()
I/KLMS-2.4.521: (12083): KLMSIntentService(): onDestroy()
,D/elm:14491(12757): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/ResourcesManager(11546): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/elm:14491(12757): MainReceiver.listeningToPackageRemoved()
D/elm:14491(12757): MDMBridge.getInstance()
D/elm:14491(12757): MDMBridge.getAllLicenseInfoFromSDK()
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
D/elm:14491(12757): MDMBridge.getAllLicenseInfoFromSDK()
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(12787): TimaSignature is unavailable
,D/ActivityThread(12787): Added TimaKeyStore provider
,I/art     ( 3521): Explicit concurrent mark sweep GC freed 7330(353KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 49MB/65MB, paused 7.559ms total 221.995ms
,D/ResourcesManager(11546): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,E/Zygote  (12805): MountEmulatedStorage()
E/Zygote  (12805): v2
I/libpersona(12805): KNOX_SDCARD checking this for 10183
I/libpersona(12805): KNOX_SDCARD not a persona
W/ResourcesManager(11546): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/SELinux (12805): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12805): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=12805 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
,E/SELinux (12805): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager(11546): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/TimaKeyStoreProvider(12805): TimaSignature is unavailable
,D/ActivityThread(12805): Added TimaKeyStore provider
,D/ResourcesManager(12787): creating new AssetManager and set to /system/app/Drive/Drive.apk
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12820): MountEmulatedStorage()
E/Zygote  (12820): v2
I/libpersona(12820): KNOX_SDCARD checking this for 10019
I/libpersona(12820): KNOX_SDCARD not a persona
,I/SELinux (12820): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12820): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12820): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=12820 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,D/ResourcesManager(12805): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,D/elm:14491(12757): ElmAgentService : onDestroy().
,I/ActivityManager( 3521): Killing 11563:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
,I/art     ( 2878): Explicit concurrent mark sweep GC freed 8735(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 403us total 10.847ms
,D/TimaKeyStoreProvider(12820): TimaSignature is unavailable
I/ActivityManager( 3521): Killing 11579:com.android.calendar/u0a164 (adj 13): bgCount ##31
,D/ActivityThread(12820): Added TimaKeyStore provider
,I/art     ( 2878): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 609us total 8.956ms
,D/ResourcesManager(12820): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/ResourcesManager(11546): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,I/art     ( 2878): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 427us total 9.301ms
,E/SQLiteLog(12805): (284) automatic index on shooting_modes(title_id)
,D/DocsApplication(12787): Installing DEX configuration.
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
,D/com.sec.android.service.health.upgrade.UninstallReceiver(12820): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver(12820): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver(12820): onReceive() : package name is not s health. Return !!!
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
D/DexInstaller(12787): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11546): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
I/PackageInfoHelper(12787): Provided clientMode=RELEASE, packageInfo=PackageInfo{9658a32 com.google.android.apps.docs}
,D/TAG     (12787): onCreate()
,D/PackageManager( 3521): delete codoeFile: 
,D/CrossAppStateProvider(12787): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
D/PackageManager( 3521): findPreferredActivity: No PreferredActivities set
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager(11546): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,E/Zygote  (12838): MountEmulatedStorage()
E/Zygote  (12838): v2
I/libpersona(12838): KNOX_SDCARD checking this for 10190
I/AASAUninstall( 3521):  com.test.thalitest not target!
I/libpersona(12838): KNOX_SDCARD not a persona
D/PackageManager( 3521): result of delete: 1{747314304}
I/SELinux (12838): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
W/ResourcesManager(11546): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(11546): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11546): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11546): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
I/SELinux (12838): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12838): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=12838 uid=10190 gids={50190, 9997} abi=armeabi-v7a
D/AndroidRuntime(12704): Shutting down VM
D/ResourcesManager(11546): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
D/LocationWidgetApplication(11546): getLastUiLocationId() : mLastUiLocationId = -100
D/TimaKeyStoreProvider(12838): TimaSignature is unavailable
D/ActivityThread(12838): Added TimaKeyStore provider
,I/ActivityManager( 3521): Killing 10867:com.android.defcontainer/u0a5 (adj 13): bgCount ##31
,D/ResourcesManager(12838): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
,W/ResourceType( 3521): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/NearbySource(12772): Nearby Source Create!
D/NearbyContext(12772): Nearby Context Create!
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
I/TapandpayWidget:TanpandpayAppWidgetProvider(12838): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(12838): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(11546): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/TapandpayWidget:Utils(12838): Clear T&P info.
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/TapandpayWidget:TanpandpayAppWidgetProvider(12838): Widget is not attached.
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(11546): creating new AssetManager and set to /system/app/Videos/Videos.apk
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
W/ContextImpl(12772): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource(12772): Samsung link source created
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,I/PCWCLIENTTRACE_PushUtil(11971): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil(11971): sales region : global
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
I/PCWCLIENTTRACE_PushUtil(11971): getPushTypeList : [SPP, GCM]
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,I/PCWCLIENTTRACE_SYSTEMReceiver(11971): [onReceive] - android.intent.action.PACKAGE_REMOVED
I/ActivityManager( 3521): Killing 11736:com.android.vending/u0a31 (adj 13): bgCount ##31
,W/ResourcesManager( 3521): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3521): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
W/ResourcesManager( 3521): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3521): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager( 3521): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/WifiDisplayAdapter( 3521): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ResourcesManager( 3521): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager(11546): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,E/Zygote  (12856): MountEmulatedStorage()
I/libpersona(12856): KNOX_SDCARD checking this for 10035
E/Zygote  (12856): v2
I/libpersona(12856): KNOX_SDCARD not a persona
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
I/SELinux (12856): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3521): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=12856 uid=10035 gids={50035, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/SELinux (12856): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
E/SELinux (12856): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Killing 12330:com.sec.android.provider.badge/u0a82 (adj 13): bgCount ##31
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Music2/Music2.apk
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,D/ResourcesManager(11546): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/PackageBroadcastService( 6781): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 6781): Clearing selected account for com.test.thalitest
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(11546): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,D/RCPManagerService( 3521): PackageReceiver onReceive()
I/HarmonyEASService( 3521): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/TimaKeyStoreProvider(12856): TimaSignature is unavailable
,D/ActivityThread(12856): Added TimaKeyStore provider
,D/WifiDisplayAdapter( 3521): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/KnoxMUMContainerPolicy( 3521): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService( 3521): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 3521): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3521): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3521): uID is 10588
V/EnterpriseBillingPolicy( 3521): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3521): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 3521): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3521): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3521): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3521): getBillingProfileForVpnEngine - start - com.test.thalitest
D/ResourcesManager(11546): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
V/EnterpriseBillingPolicyStorage( 3521): getBillingProfileForVpnEngine - end - null
,D/UsbSettingsManager( 3521): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 3521): onPackageRemoved : com.test.thalitest
,D/ResourcesManager(11546): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ChimeraCfgMgr( 6781): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6781): Module APK com.google.android.play.games already loaded
,D/ResourcesManager(11546): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ContactProvider(12772): getAllContactInfoList Start
D/ResourcesManager(11546): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/ResourcesManager(11546): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
,D/ResourcesManager(12856): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/ChimeraCfgMgr( 6781): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6781): Module APK com.google.android.play.games already loaded
,D/ResourcesManager(11546): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/KnoxTimeoutHandler( 3521): handleActiveUserChange for user 0
,D/TaskPersister( 3521): removeObsoleteFile: deleting file=26_task.xml
D/TaskPersister( 3521): removeObsoleteFile: deleting file=24_task.xml
,I/LocationSettingsChecker( 6781): Removing dialog suppression flag for package com.test.thalitest
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11546): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,E/Zygote  (12877): MountEmulatedStorage()
,E/Zygote  (12877): v2
I/libpersona(12877): KNOX_SDCARD checking this for 10052
I/libpersona(12877): KNOX_SDCARD not a persona
,I/SELinux (12877): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3521): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=12877 uid=10052 gids={50052, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,I/SELinux (12877): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12877): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/gH_CompatibleDatabase( 6781): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 6781): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 6781): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 6781): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/ResourcesManager(11546): creating new AssetManager and set to /system/app/Books/Books.apk
,I/FeatureConfig(12856): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/gH_CompatibleDatabase( 6781): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 6781): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/StatusBar( 3688): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/gH_CompatibleDatabase( 6781): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/ResourcesManager(12856): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager(12856): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager(12856): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12856): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12856): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12856): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(12856): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager(11546): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
,D/gH_CompatibleDatabase( 6781): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 6781): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 6781): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 6781): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 6781): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 6781): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
D/ResourcesManager(12856): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
D/PersonaManager( 3688): isKioskContainerExistOnDevice
,D/PersonaManager( 3688): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3688): Icon Only
I/StatusBar( 3688): Icon Only
D/PanelView( 3688): There is/are notification(s) 
D/PanelView( 3688): There is/are notification(s) 
,W/ResourcesManager(12856): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12856): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12856): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/PersonaManager( 3688): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3688): Icon Only
,I/StatusBar( 3688): Icon Only
,D/PanelView( 3688): There is/are notification(s) 
,D/ResourcesManager(12856): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager(12856): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager(12856): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12856): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager(12856): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12856): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12856): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12856): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider(12877): TimaSignature is unavailable
D/ActivityThread(12877): Added TimaKeyStore provider
,I/ActivityManager( 3521): Killing 8813:com.android.settings/1000 (adj 13): bgCount ##31
,D/ResourcesManager(11546): creating new AssetManager and set to /system/app/Drive/Drive.apk
,E/NetworkScheduler.SchedulerReceiver( 4645): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 4645): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/ResourcesManager(12856): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager(12856): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(12856): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12856): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12856): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12856): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager(11546): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(12877): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
W/ResourcesManager(12877): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
W/ResourcesManager(12877): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12877): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12877): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12877): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(12877): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/WifiService( 3521): Client connection lost with reason: 4
,D/ResourcesManager(12856): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,W/ResourcesManager(12856): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12856): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12856): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/Icing   ( 6781): doRemovePackageData com.test.thalitest
,E/Zygote  (12900): MountEmulatedStorage()
E/Zygote  (12900): v2
I/libpersona(12900): KNOX_SDCARD checking this for 10036
I/libpersona(12900): KNOX_SDCARD not a persona
D/ResourcesManager(12856): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,I/SELinux (12900): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,W/ResourcesManager(12856): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(12856): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12856): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12856): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12856): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(12856): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(12856): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12856): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,V/AlarmManager( 3521):  next == MAX_VALUE
,I/SELinux (12900): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/PanelView( 3688): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,E/SELinux (12900): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(12856): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager(12856): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12856): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12856): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/ActivityManager( 3521): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=12900 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager( 3521): Killing 12029:com.sec.android.cloudagent/u0a2 (adj 13): bgCount ##31
,D/ResourcesManager(11546): creating new AssetManager and set to /system/app/FBInstagram_stub/FBInstagram_stub.apk
,D/ResourcesManager(12856): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager(12856): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12856): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12856): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12856): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12856): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider(12900): TimaSignature is unavailable
,D/ActivityThread(12900): Added TimaKeyStore provider
D/ResourcesManager(12856): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager(12856): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager(12856): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12856): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager(12856): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,W/ResourcesManager(12856): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager(11546): creating new AssetManager and set to /system/app/FBMessenger_stub/FBMessenger_stub.apk
,D/ResourcesManager(12856): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(12856): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager(12856): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12856): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12856): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12856): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12856): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/Mms/MmsApp(12877): [start]    onCreate() consume time = 0.0
,D/ResourcesManager(11546): creating new AssetManager and set to /system/app/FBPagesManager_stub/FBPagesManager_stub.apk
,E/ActivityThread(11946): Failed to find provider info for com.facebook.appmanager.installrecord
,D/ResourcesManager(12856): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/Mms/ArtClassLoader(12877): init before art
,D/Mms/TelephonyPermission(12877): start operation mode monitor
D/ContactProvider(12772): getAllContactInfoList End
,D/Mms/ArtClassLoader(12877): init [DONE] art
,D/ResourcesManager(12900): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager(12877): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,I/syncContacts(12772): thread: 1753, sync time = 276
,W/ResourcesManager(12877): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11546): creating new AssetManager and set to /system/app/Maps/Maps.apk
,E/SQLiteLog(12787): (28) failed to open "/data/data/com.google.android.apps.docs/databases/ClientFlag.db" with flag (131138) and mode_t (0) due to error (30)
,D/ResourcesManager(12856): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,W/ResourcesManager(12856): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12856): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12856): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager(11546): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(12856): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,E/Zygote  (12920): MountEmulatedStorage()
E/Zygote  (12920): v2
I/libpersona(12920): KNOX_SDCARD checking this for 10031
I/libpersona(12920): KNOX_SDCARD not a persona
E/SQLiteDatabase(12787): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase(12787): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12787): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12787): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12787): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12787): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12787): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12787): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12787): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12787): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12787): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12787): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12787): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12787): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12787): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(12787): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase(12787): 	at QF.provideClientFlag(ClientFlagsModule.java:71)
E/SQLiteDatabase(12787): 	at QH.a(GellyInjectorStore.java:215)
E/SQLiteDatabase(12787): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12787): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12787): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12787): 	at tQ.a(GellyInjectorStore.java:2039)
E/SQLiteDatabase(12787): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12787): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12787): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12787): 	at pG.a(GellyInjectorStore.java:478)
E/SQLiteDatabase(12787): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12787): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12787): 	at qD.a(GellyInjectorStore.java:118)
E/SQLiteDatabase(12787): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12787): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12787): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12787): 	at aEV.a(GellyInjectorStore.java:130)
E/SQLiteDatabase(12787): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12787): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12787): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12787): 	at aGH.a(GellyInjectorStore.java:227)
E/SQLiteDatabase(12787): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12787): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12787): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12787): 	at aGH.a(GellyInjectorStore.java:392)
E/SQLiteDatabase(12787): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12787): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12787): 	at aGH.a(GellyInjectorStore.java:369)
E/SQLiteDatabase(12787): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12787): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12787): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12787): 	at agN.a(GellyInjectorStore.java:799)
E/SQLiteDatabase(12787): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12787): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12787): 	at pG.a(GellyInjectorStore.java:146)
E/SQLiteD,atabase(12787): 	at pG.a(GellyInjectorStore.java:392)
E/SQLiteDatabase(12787): 	at bsh.a(GellyMembersInjector.java:30)
E/SQLiteDatabase(12787): 	at brQ.a(GellyInjector.java:119)
E/SQLiteDatabase(12787): 	at ajB.a(ScopedInjector.java:216)
E/SQLiteDatabase(12787): 	at com.google.android.apps.docs.DocsApplication.a(DocsApplication.java:235)
E/SQLiteDatabase(12787): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase(12787): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(12787): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(12787): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12787): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12787): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12787): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12787): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12787): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12787): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12787): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12787): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper(12787): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper(12787): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(12787): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(12787): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(12787): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(12787): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(12787): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(12787): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(12787): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(12787): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(12787): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(12787): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(12787): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(12787): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(12787): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(12787): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper(12787): 	at QF.provideClientFlag(ClientFlagsModule.java:71)
E/SQLiteOpenHelper(12787): 	at QH.a(GellyInjectorStore.java:215)
E/SQLiteOpenHelper(12787): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12787): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12787): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12787): 	at tQ.a(GellyInjectorStore.java:2039)
E/SQLiteOpenHelper(12787): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12787): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12787): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12787): 	at pG.a(GellyInjectorStore.java:478)
E/SQLiteOpenHelper(12787): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12787): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12787): 	at qD.a(GellyInjectorStore.java:118)
E/SQLiteOpenHelper(12787): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12787): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12787): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12787): 	at aEV.a(GellyInjectorStore.java:130)
E/SQLiteOpenHelper(12787): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12787): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12787): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12787): 	at aGH.a(GellyInjectorStore.java:227)
E/SQLiteOpenHelper(12787): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12787): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12787): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12787): 	at aGH.a(GellyInjectorStore.java:392)
E/SQLiteOpenHelper(12787): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12787): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12787): 	at aGH.a(GellyInjectorStore.java:369)
E/SQLiteOpenHelper(12787): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12787): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12787): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12787): 	at agN.a(GellyInjectorStore.java:799)
E/SQLiteOpenHelper(12787): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12787): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12787): 	at pG.a(GellyInjectorStore.java:146)
E/SQLiteOpenHelper(12787): 	at pG.a(GellyInjectorStore.java:392)
E/SQLiteOpenHelper(12787): 	at bsh.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper(12787): 	at brQ.a(GellyInjector.java:119)
E/SQLiteOpenHelper(12787): 	at ajB.a(ScopedInjector.java:216)
E/SQLiteOpenHelper(12787): 	at com.google.android.apps.docs.DocsApplication.a(DocsApplication.java:235)
E/SQLiteOpenHelper(12787): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper(12787): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(12787): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(12787): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(12787): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(12787): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(12787): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(12787): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(12787): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(12787): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(12787): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(12787): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/ResourcesManager(12856): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12856): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager(12856): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
I/SELinux (12920): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
W/ResourcesManager(12856): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12856): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12856): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/SQLiteOpenHelper(12787): Opened ClientFlag.db in read-only mode
I/SELinux (12920): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3521): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=12920 uid=10031 gids={50031, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ResourcesManager(12856): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
E/SELinux (12920): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
W/ResourcesManager(12856): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager(12856): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ResourcesManager(11546): creating new AssetManager and set to /system/app/PENUP/PENUP.apk
D/Mms/TelephonyPermission(12877): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission(12877): isDefault true
D/Mms/MmsApp(12877): onCreate() com.android.mms
W/GalaxyFinderApplication(12856): system/finder_cp/cpdata.xml file not found
E/SQLiteLog(12787): (28) failed to open "/data/data/com.google.android.apps.docs/databases/DocList.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase(12787): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase(12787): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12787): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12787): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12787): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12787): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12787): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12787): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12787): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12787): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12787): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12787): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12787): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12787): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12787): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12787): 	at aFu.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase(12787): 	at aFo.a(AbstractDatabaseInstance.java:457)
E/SQLiteDatabase(12787): 	at aFo.a(AbstractDatabaseInstance.java:453)
E/SQLiteDatabase(12787): 	at bjx.a(Suppliers.java:125)
E/SQLiteDatabase(12787): 	at aFp.run(AbstractDatabaseInstance.java:471)
E/AndroidRuntime(12787): FATAL EXCEPTION: Open database in background
E/AndroidRuntime(12787): Process: com.google.android.apps.docs, PID: 12787
E/AndroidRuntime(12787): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12787): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12787): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(12787): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(12787): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12787): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12787): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12787): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(12787): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(12787): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(12787): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(12787): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12787): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(12787): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(12787): 	at aFu.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime(12787): 	at aFo.a(AbstractDatabaseInstance.java:457)
E/AndroidRuntime(12787): 	at aFo.a(AbstractDatabaseInstance.java:453)
E/AndroidRuntime(12787): 	at bjx.a(Suppliers.java:125)
E/AndroidRuntime(12787): 	at aFp.run(AbstractDatabaseInstance.java:471)
D/TimaKeyStoreProvider(12920): TimaSignature is unavailable
D/ActivityThread(12920): Added TimaKeyStore provider
V/ApplicationPolicy( 3521): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.docs
,D/ResourcesManager(11546): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(11546): creating new AssetManager and set to /system/app/SecCalculator2/SecCalculator2.apk
D/ResourcesManager(11546): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
E/SQLiteLog(12787): (28) failed to open "/data/data/com.google.android.apps.docs/databases/ClientFlag.db" with flag (131138) and mode_t (0) due to error (30)
D/ResourcesManager(12920): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
D/Mms/MmsApp(12877): [start]    initCountryIso consume time = 71.430875
D/CountryDetector( 3521): The first listener is added
E/SQLiteDatabase(12787): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase(12787): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12787): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12787): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12787): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12787): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12787): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12787): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12787): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12787): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12787): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12787): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12787): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12787): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12787): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(12787): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase(12787): 	at com.google.android.apps.docs.DocsApplication.i(DocsApplication.java:349)
E/SQLiteDatabase(12787): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:229)
E/SQLiteDatabase(12787): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(12787): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(12787): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12787): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12787): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12787): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12787): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12787): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12787): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12787): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12787): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper(12787): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper(12787): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(12787): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(12787): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(12787): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(12787): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(12787): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(12787): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(12787): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(12787): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(12787): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(12787): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(12787): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(12787): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(12787): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(12787): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper(12787): 	at com.google.android.apps.docs.DocsApplication.i(DocsApplication.java:349)
E/SQLiteOpenHelper(12787): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:229)
E/SQLiteOpenHelper(12787): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(12787): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(12787): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(12787): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(12787): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(12787): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(12787): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(12787): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(12787): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(12787): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(12787): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper(12787): Opened ClientFlag.db in read-only mode
E/Zygote  (12941): MountEmulatedStorage()
E/Zygote  (12941): v2
I/libpersona(12941): KNOX_SDCARD checking this for 1000
I/libpersona(12941): KNOX_SDCARD not a persona
I/SELinux (12941): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
E/DropBoxManagerService( 3521): Can't write: system_app_crash
E/DropBoxManagerService( 3521): java.io.FileNotFoundException: /data/system/dropbox/drop196.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3521): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3521): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3521): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3521): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3521): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3521): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3521): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3521): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3521): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3521): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3521): 	... 5 more
I/SELinux (12941): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12941): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=12941 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/UsbHostManager( 3521): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
I/Process (12787): Sending signal. PID: 12787 SIG: 9
D/UsbHostManager( 3521): displayNotification : [02h,02h,01h]
D/UsbHostManager( 3521): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
D/UsbHostManager( 3521): displayNotification : [0ah,00h,00h]
D/UsbHostManager( 3521): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3521): displayNotification : [02h,0dh,00h]
D/UsbHostManager( 3521): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3521): displayNotification : [0ah,00h,01h]
D/UsbHostManager( 3521): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
D/UsbHostManager( 3521): displayNotification : [09h,00h,00h]
D/UsbHostManager( 3521): usbDeviceRemoved : /dev/bus/usb/001/003
E/UsbHostManager( 3521): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
D/UsbSettingsManager( 3521): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
D/Mms/MmsApp(12877): [end]    initCountryIso consume time = 15.198042
D/Mms/MmsConfig(12877): [start]    MmsConfig.init() consume time = 0.064208
D/MtpClient(12772): onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
D/MtpClient(12772): ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
D/Mms/MmsConfig(12877): before partial update
D/ResourcesManager(11546): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/TimaKeyStoreProvider(12941): TimaSignature is unavailable
,D/Mms/MmsConfig(12877): Load Resize quality : 80
,D/ActivityThread(12941): Added TimaKeyStore provider
,D/Mms/MmsConfig(12877):  enable multiwindow = true
,D/SHealthUpgrade(SHealthUpgradeUtil)(12900): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(12900): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(12900): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,E/JavaBinder( 3521): !!! FAILED BINDER TRANSACTION !!!
E/lowmemorykiller( 2826): Error writing /proc/12787/oom_score_adj; errno=22
,E/SQLiteLog(12900): (28) failed to open "/data/data/com.sec.android.app.shealth/databases/base.db" with flag (131138) and mode_t (0) due to error (30)
I/ActivityManager( 3521): Killing 12049:com.sec.android.diagmonagent/1000 (adj 13): bgCount ##31
,E/SQLiteDatabase(12900): Failed to open database '/data/data/com.sec.android.app.shealth/databases/base.db'.
E/SQLiteDatabase(12900): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12900): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12900): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12900): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12900): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12900): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12900): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12900): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12900): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12900): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12900): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12900): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12900): 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:211)
E/SQLiteDatabase(12900): 	at android.database.sqlite.SQLiteSecureOpenHelper.getWritableDatabase(SQLiteSecureOpenHelper.java:151)
E/SQLiteDatabase(12900): 	at com.sec.android.app.shealth.framework.repository.database.DBManager.getWritableDatabase(DBManager.java:123)
E/SQLiteDatabase(12900): 	at com.sec.android.app.shealth.framework.repository.RepositoryInitializationTask.doInBackground(RepositoryInitializationTask.java:85)
E/SQLiteDatabase(12900): 	at com.sec.android.app.shealth.framework.repository.RepositoryInitializationTask.doInBackground(RepositoryInitializationTask.java:30)
E/SQLiteDatabase(12900): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase(12900): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase(12900): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase(12900): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase(12900): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase(12900): 	at java.lang.Thread.run(Thread.java:818)
,D/UsbHostManager( 3521): usbDeviceRemoved : /dev/bus/usb/001/001
E/UsbHostManager( 3521): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
,D/ResourcesManager(12941): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk
,E/Mms/MessageUtils(12877): setCountryDetector : update country detector info 
E/Mms/MessageUtils(12877): updateCountryIso : update country iso info 
I/ActivityManager( 3521): Process com.google.android.apps.docs (pid 12787)(adj 9) has died(211,1193)
,I/EventHub( 3521): Removing device '/dev/input/event10' due to inotify event
D/ResourcesManager(11546): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
D/SHealthUpgrade(SHealthUpgradeUtil)(12900): checkState()
D/SHealthUpgrade(SHealthUpgradeUtil)(12900): checkState() : APP TYPE = Full
,D/Mms/PackageInfo(12877): com.sec.imsservice is not installed
D/Mms/MmsConfig(12877): [end]    init() consume time = 69.7415
,D/SHealthUpgrade(SHealthUpgradeUtil)(12900): isFitnessWithGearInstalled() : Fitness with Gear isn't Installed.
D/Mms/Contact(12877): [start]    init() consume time = 1.515542
,D/SHealthUpgrade(SHealthUpgradeUtil)(12900): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(12900): isShealthService1xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(12900): isShealthService1xInstalled() : HEALTH SERVICE VERSION is NOT 1.x !!!
,D/SHealthUpgrade(SHealthUpgradeUtil)(12900): isShealthService0xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(12900): isShealthService0xInstalled() : HEALTH SERVICE VERSION is NOT 0.x !!!
,D/SHealthUpgrade(SHealthUpgradeUtil)(12900): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(12900): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)(12900): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(12900): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,W/ContextImpl(12941): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2994 
,D/TP/MmsSmsProvider( 3973): query,matched:13, calling pid = 12877
,D/Mms/Contact(12877): [end]    init consume time = 27.437583
,D/TP/MmsSmsProvider( 3973): match 13:Elapsed time : 7.561 ms
,D/Mms/DraftCache(12877): [start]    rebuildCache consume time = 6.229625
,I/EventHub( 3521): Removing device '/dev/input/event7' due to inotify event
,D/TP/MmsSmsProvider( 3973): query,matched:12, calling pid = 12877
,D/ResourcesManager(11546): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,D/TP/MmsSmsProvider( 3973): match 12:Elapsed time : 14.814 ms
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/Mms/TelephonyUtils(12877): getSubId from simSlot 0, return Value = -1
,D/Mms/DownloadManager(12877): roaming -> false (slotId = 0)
D/Mms/DownloadManager(12877): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager(12877): auto download without roaming -> true
,D/Mms/DownloadManager(12877): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,E/Mms/TelephonyUtils(12877): subID is null or 0 length, so get DefaultSubId!!
,D/Mms/TelephonyUtils(12877): getSubId from simSlot 1, return Value = 9223372036854775807
,D/Mms/DownloadManager(12877): roaming -> false (slotId = 1)
,D/Mms/DownloadManager(12877): [NotificationTransaction] getAutoDownloadState simSlot : 1
,D/Mms/DownloadManager(12877): auto download without roaming -> true
,D/Mms/DownloadManager(12877): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
,D/Mms/DownloadManager(12877): auto download during roaming secondary -> false
I/EventHub( 3521): Removing device '/dev/input/event8' due to inotify event
,D/Mms/DownloadManager(12877): mAutoDownload ------> true
,E/Zygote  (12976): MountEmulatedStorage()
,E/Zygote  (12976): v2
,I/libpersona(12976): KNOX_SDCARD checking this for 10121
I/libpersona(12976): KNOX_SDCARD not a persona
,I/SELinux (12976): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12976): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12976): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=12976 uid=10121 gids={50121, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,I/EventHub( 3521): Removing device '/dev/input/event9' due to inotify event
,E/Zygote  (12991): MountEmulatedStorage()
E/Zygote  (12991): v2
I/libpersona(12991): KNOX_SDCARD checking this for 10116
I/libpersona(12991): KNOX_SDCARD not a persona
,I/SELinux (12991): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/EventHub( 3521): Removing device '/dev/input/event11' due to inotify event
,I/ActivityManager( 3521): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=12991 uid=10116 gids={50116, 9997, 1023} abi=armeabi-v7a
,I/SELinux (12991): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12991): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SHealthUpgrade(SHealthUpgradeUtil)(12900): checkState() : =========== UPGRADE_STATE_APP_UPGRADE_DONE ===========
,D/TimaKeyStoreProvider(12976): TimaSignature is unavailable
,D/ActivityThread(12976): Added TimaKeyStore provider
D/SHealthUpgrade(SHealthUpgradeUtil)(12900): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(12900): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(12900): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)(12900): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(12900): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(12900): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,I/EventHub( 3521): Removing device '/dev/input/event12' due to inotify event
,D/Mms/MmsApp(12877): [end]    onCreate() consume time = 230.302209
,D/ResourcesManager(11546): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,D/Mms/Conversation(12877): [start]    init() consume time = 7.828708
,D/Mms/FreeMessageStatusReceiver(12877): onReceive, action : android.intent.action.PACKAGE_REMOVED
,D/Mms/DraftCache(12877): [end]    rebuildCache consume time = 6.626625
,D/TP/MmsSmsProvider( 3973): deleteConversation threadId: 9223372036854775807
,D/Mms/DownloadManager(12877): Service state changed: Bundle[mParcelledData.dataSize=692]
D/Mms/DownloadManager(12877): roaming ------> false, mSimSlot = 0
,D/Mms/TelephonyUtils(12877): getSubId from simSlot 0, return Value = -1
,D/com.sec.android.service.health.keyManager.KeyManager(12900): Current encrypted state : -1
,I/SecSQLiteOpenHelper(12900): getWritableDatabase(pwd)
I/SecSQLiteOpenHelper(12900): getDatabaseLocked(b,b,pwd)...
I/SecSQLiteOpenHelper(12900): Open platform.db in secure mode
D/SecSQLiteDatabase(12900): Android Version: 5.0.1
D/SecSQLiteDatabase(12900): Load library secsqlite.so for Android 5.0.1
,I/EventHub( 3521): Removing device '/dev/input/event13' due to inotify event
,D/Mms/DownloadManager(12877): roaming -> false (slotId = 0)
D/Mms/DownloadManager(12877): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager(12877): auto download without roaming -> true
D/Mms/DownloadManager(12877): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager(12877): mAutoDownload ------> true
,D/TimaKeyStoreProvider(12991): TimaSignature is unavailable
,I/SecSQLiteDatabase(12900): openSecureDatabase...
D/ActivityThread(12991): Added TimaKeyStore provider
,I/SecSQLiteDatabase(12900): private openSecureDatabase...
I/SecSQLiteConnectionPool(12900): OpenSecure
I/SecSQLiteConnectionPool(12900): OpenSecure with password
I/SecSQLiteConnectionPool(12900): openSecureConnectionLocked
,D/Mms/FreeMessageReceiverService(12877): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService(12877): onHandleIntent: ACTION_PACKAGE_REMOVED
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/SecSQLiteDatabase(12900): Failed to open database '/data/data/com.sec.android.app.shealth/databases/platform.db'.
E/SecSQLiteDatabase(12900): samsung.database.sqlite.SecSQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SecSQLiteDatabase(12900): 	at samsung.database.sqlite.SecSQLiteConnection.nativeOpen(Native Method)
E/SecSQLiteDatabase(12900): 	at samsung.database.sqlite.SecSQLiteConnection.open(SecSQLiteConnection.java:233)
E/SecSQLiteDatabase(12900): 	at samsung.database.sqlite.SecSQLiteConnection.openSecure(SecSQLiteConnection.java:217)
E/SecSQLiteDatabase(12900): 	at samsung.database.sqlite.SecSQLiteConnectionPool.openSecureConnectionLocked(SecSQLiteConnectionPool.java:472)
E/SecSQLiteDatabase(12900): 	at samsung.database.sqlite.SecSQLiteConnectionPool.openSecure(SecSQLiteConnectionPool.java:214)
E/SecSQLiteDatabase(12900): 	at samsung.database.sqlite.SecSQLiteConnectionPool.openSecure(SecSQLiteConnectionPool.java:195)
E/SecSQLiteDatabase(12900): 	at samsung.database.sqlite.SecSQLiteDatabase.openInnerSecureDatabase(SecSQLiteDatabase.java:821)
E/SecSQLiteDatabase(12900): 	at samsung.database.sqlite.SecSQLiteDatabase.openSecureDatabase(SecSQLiteDatabase.java:794)
E/SecSQLiteDatabase(12900): 	at samsung.database.sqlite.SecSQLiteDatabase.openSecureDatabase(SecSQLiteDatabase.java:678)
E/SecSQLiteDatabase(12900): 	at samsung.database.sqlite.SecSQLiteOpenHelper.getDatabaseLocked(SecSQLiteOpenHelper.java:306)
E/SecSQLiteDatabase(12900): 	at samsung.database.sqlite.SecSQLiteOpenHelper.getWritableDatabase(SecSQLiteOpenHelper.java:243)
E/SecSQLiteDatabase(12900): 	at com.sec.android.service.health.keyManager.KeyManager.isDbOpened(Unknown Source)
E/SecSQLiteDatabase(12900): 	at com.sec.android.service.health.keyManager.KeyManager.arrangeDbKey(Unknown Source)
E/SecSQLiteDatabase(12900): 	at com.sec.android.service.health.keyManager.KeyManager.isDefaultPassword(Unknown Source)
E/SecSQLiteDatabase(12900): 	at com.sec.android.service.health.keyManager.KeyManager.isSecureStorageSupported(Unknown Source)
E/SecSQLiteDatabase(12900): 	at com.sec.android.service.health.keyManager.KeyManager.isSecureStorageSupported(Unknown Source)
E/SecSQLiteDatabase(12900): 	at com.sec.android.app.shealth.SHealthApplication.startKeyManager(SHealthApplication.java:221)
E/SecSQLiteDatabase(12900): 	at com.sec.android.app.shealth.SHealthApplication.onCreate(SHealthApplication.java:199)
E/SecSQLiteDatabase(12900): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SecSQLiteDatabase(12900): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SecSQLiteDatabase(12900): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SecSQLiteDatabase(12900): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SecSQLiteDatabase(12900): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SecSQLiteDatabase(12900): 	at android.os.Looper.loop(Looper.java:145)
E/SecSQLiteDatabase(12900): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SecSQLiteDatabase(12900): 	at java.lang.reflect.Method.invoke(Native Method)
E/SecSQLiteDatabase(12900): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SecSQLiteDatabase(12900): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SecSQLiteDatabase(12900): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
D/SecSQLiteOpenHelper(12900): ...getDatabaseLocked(b,b,pwd)
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(12976): creating new AssetManager and set to /system/app/GearManagerStub/GearManagerStub.apk
,I/EventHub( 3521): Removing device '/dev/input/event14' due to inotify event
,E/Zygote  (13008): MountEmulatedStorage()
E/Zygote  (13008): v2
I/libpersona(13008): KNOX_SDCARD checking this for 1000
I/libpersona(13008): KNOX_SDCARD not a persona
,I/SELinux (13008): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (13008): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027,
I/ActivityManager( 3521): Start proc com.android.settings for broadcast com.android.settings/.TactileAssistBroadcastReceiver: pid=13008 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux (13008): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(13008): TimaSignature is unavailable
,D/ActivityThread(13008): Added TimaKeyStore provider
,I/SecureStorage(12820): [INFO]: SPID(0x00000000)Processing data
,D/ResourcesManager(12991): creating new AssetManager and set to /system/app/FilterProvider/FilterProvider.apk

```
