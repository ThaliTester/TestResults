#### Test 58135655a685cd3_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
,I/PowerManagerService( 3525): [PWL] Off : 140s ago
D/SSRM:n  ( 3525): SIOP:: AP = 240, PST = 246, CUR = 39
--------- beginning of main
D/AndroidRuntime(11735): 
D/AndroidRuntime(11735): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11735): CheckJNI is OFF
D/AndroidRuntime(11735): readGMSProperty: start
D/AndroidRuntime(11735): readGMSProperty: already setted!!
D/AndroidRuntime(11735): readGMSProperty: end
D/AndroidRuntime(11735): addProductProperty: start
E/AffinityControl(11735): AffinityControl: registerfunction enter
D/AndroidRuntime(11735): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3525): inState():  stateMachine is null !!
I/PersonaManagerService( 3525): PersonaId don't exist
I/ActivityManager( 3525): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3525): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3525): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3525): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager( 3525): mDVFSHelper.acquire()
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/Zygote  (11753): MountEmulatedStorage()
E/Zygote  (11753): v2
I/libpersona(11753): KNOX_SDCARD checking this for 10628
I/libpersona(11753): KNOX_SDCARD not a persona
I/SELinux (11753): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3525): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=11753 uid=10628 gids={50628, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux (11753): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11753): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(11735): Shutting down VM
D/PointerIcon( 3525): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3525): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3525): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3525): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(11753): TimaSignature is unavailable
D/ActivityThread(11753): Added TimaKeyStore provider
I/SurfaceFlinger( 2849): id=11 Removed YUIInstallC (5/8)
I/SurfaceFlinger( 2849): id=11 Removed YUIInstallC (-2/8)
D/ResourcesManager(11753): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
V/ActivityThread( 6229): updateVisibility : ActivityRecord{11f8c6e9 token=android.os.BinderProxy@16cb5a2 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
I/WebViewFactory(11753): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(11753): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(11753): Loading: webviewchromium
I/LibraryLoader(11753): Time to load native libraries: 4 ms (timestamps 5162-5166)
I/LibraryLoader(11753): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(11753): Binding Chromium to main looper Looper (main, tid 1) {368f4400}
,I/LibraryLoader(11753): Expected native library version number "",actual native library version number ""
I/chromium(11753): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(11753): Initializing chromium process, renderers=0
,W/art     (11753): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(11753): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(11753): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
,I/chromium(11753): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3525): online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
D/BatteryService( 3525): stay LED for fully charged
D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 5621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5621): Disconnected process message: 10
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/chromium(11753): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(11753): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (11753): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(11753): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(11753): CordovaWebView is running on device made by: samsung
,W/art     (11753): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11753): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity(11753): performCreate Call secproduct feature valuefalse
D/Activity(11753): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(11753): Render dirty regions requested: true
,D/ActivityManager( 3525): post active user change for 0
D/KnoxTimeoutHandler( 3525): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3525): handleActiveUserChange for user 0
,I/SurfaceFlinger( 2849): id=14 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService( 3525): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3525): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3525): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3525): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3525): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3525): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer(11753): Initialized EGL, version 1.4
,I/OpenGLRenderer(11753): HWUI protection enabled for context ,  &this =0xaf645060 ,&mEglDisplay = 1 , &mEglConfig = -1278770928 
,D/OpenGLRenderer(11753): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(11753): Enabling debug mode 0
,D/mali_winsys(11753): new_window_surface returns 0x3000,  [1440x2560]-format:1
,V/ActivityThread(11753): updateVisibility : ActivityRecord{ffbad30 token=android.os.BinderProxy@35f856e7 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/InputMethodManagerService( 3525): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 3525): mDVFSHelper.release()
I/Timeline( 3525): Timeline: Activity_windows_visible id: ActivityRecord{2d3a4c95 u0 com.test.thalitest/.MainActivity t26} time:235614
,W/IInputConnectionWrapper(11753): showStatusIcon on inactive InputConnection
,I/Timeline(11753): Timeline: Activity_idle id: android.os.BinderProxy@35f856e7 time:235626
,I/chromium(11753): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11753): 
,D/JsMessageQueue(11753): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log(11753): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1357424896
,I/chromium(11753): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log(11753): Initializing JXcore engine
W/jxcore-log(11753): JXcore engine is ready
,E/auditd  ( 4610): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3525): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3525): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(11753): Starting JXcore engine
,W/jxcore-log(11753): Platform android
W/jxcore-log(11753): 
W/jxcore-log(11753): Process ARCH arm
W/jxcore-log(11753): 
,I/jxcore-log(11753): JXcore Cordova bridge is ready!
I/jxcore-log(11753): 
W/jxcore-log(11753): JXcore engine is started
,I/jxcore-log(11753): Toggling radios to true
I/jxcore-log(11753): 
,D/BluetoothAdapter(11753): enable()
,D/BluetoothAdapter(11753): enable(): BT is already enabled..!
,D/WifiService( 3525): New client listening to asynchronous messages
,I/WifiManager(11753): packageName : com.test.thalitest
,D/SecContentProvider( 3525): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3525): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3525): mCursor = null
,D/WifiService( 3525): setWifiEnabled: true pid=11753, uid=10628
,E/WifiService( 3525): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3525): Permission Denial: getCurrentUser() from pid=11753, uid=10628 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 3525): Failed getting userId using ActivityManagerNative
W/WifiService( 3525): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=11753, uid=10628 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3525): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3525): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3525): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3525): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3525): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider( 3525): name = wifi_on
I/WifiService( 3525): disconnect: pid=11753, uid=10628
,I/wpa_supplicant( 3826): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log(11753): Radios toggled
I/jxcore-log(11753): 
,I/jxcore-log(11753): My device name is: samsung-SM-N910C
I/jxcore-log(11753): 
,I/wpa_supplicant( 3826): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3826): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 3826): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3826): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine( 3525): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 3826): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3826): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3826): Disconnected - do not scan
I/wpa_supplicant( 3826): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine( 3525): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3525): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3525): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3525): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine( 3525): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3525): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/native  ( 3525): do suspend true
,D/WifiP2pService( 3525): InactiveState{ what=143375 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=143375 }
,D/CommandListener( 2845): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 3695): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
E/Netd    ( 2845): ifc_reset_connections failed on iface wlan0 for address 192.168.1.124/24 (Unknown error -1)
D/STATUSBAR-WifiQuickSettingButton( 3695): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,E/WifiStateMachine( 3525): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService( 3525): updateNetworkInfo()
,D/ConnectivityService( 3525): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,E/ConnectivityService( 3525): updateNetworkInfo()
E/WifiConfigStore( 3525): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 3525): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,I/WifiTrafficPoller( 3525): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 3695): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3695): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3695): applyOpen
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
,E/WifiStateMachine( 3525): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 3826): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3826): P2P: Current p2p state = IDLE
I/wpa_supplicant( 3826): wlan0: State: DISCONNECTED -> SCANNING
I/Hs20UtilService( 4102): Starting #8
I/wpa_supplicant( 3826): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3826): First Scan Start
,I/wpa_supplicant( 3826): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiStateMachine( 3525): ConnectModeState: Network connection lost 
,E/WifiStateMachine( 3525): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - processMessage - processMsg
,D/NearbySettings( 8862): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 8862): MountReceiver.onReceive - Start HandlerThread
,E/WifiStateMachine( 3525): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine( 3525): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
D/NearbySettings( 8862): MountReceiver.onReceive - Create mPrefHandler
E/native  ( 3525): do suspend true
I/Hs20UtilService( 4102): Message received 5007
,D/NearbySettings( 8862): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8862): DMSUtil.isNetworkConnected - flag-null, state-null
,D/WifiP2pService( 3525): InactiveState{ what=143375 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=143375 }
I/NearbySettings( 8862): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/StatusBar.NetworkController( 3695): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3695): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiService( 3525): New client listening to asynchronous messages
,I/NearbySettings( 8862): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8862): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 8862): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8862): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11392): NETWORK_STATE_CHANGED_ACTION
,D/CommandListener( 2845): Clearing all IP addresses on wlan0
,D/ConnectivityService( 3525): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,D/EntConnectivity( 3525): Not allowed due to - mEnabled false
E/WifiStateMachine( 3525): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityManager.CallbackHandler( 3695): CM callback handler got msg 524292
,D/WifiStateMachine( 3525): updateConfiguredNetworkExpiration - currTime: 1454591279731
D/ConnectivityService( 3525): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiStateMachine( 3525): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
E/WifiStateMachine( 3525): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine( 3525): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3525): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyNetworkFactory( 3984): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/WifiTrafficPoller( 3525): evaluateTrafficStatsPolling
E/WifiStateMachine( 3525): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3525): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/CSLegacyTypeTracker( 3525): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 3525): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 3525): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityManager.CallbackHandler( 6656): CM callback handler got msg 524292
,E/WifiStateMachine( 3525): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3525): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent( 3525): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine( 3525): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3525): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
,E/WifiStateMachine( 3525): setDetailed state send new extra info"NG700"
,D/StatusBar.NetworkController( 3695): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/SecContentProvider2( 3525): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3525): mCursor = null
D/STATUSBAR-WifiQuickSettingButton( 3695): onWifiSignalChanged enabled=true enabledDesc:null
,D/EntConnectivity( 3525): Not allowed due to - mEnabled false
,D/ConnectivityService( 3525): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/SmartBondingService( 3525): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering( 3525): MasterInitialState.processMessage what=3
D/SmartBondingService( 3525): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService( 3525): getSBEnabled() enabled =false
D/SmartBondingService( 3525): getSBEnabled() enabled =false
D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
D/SmartBondingService( 3525): getSBEnabled() enabled =false
V/NetworkStats( 3525): updateIfacesLocked()
V/NetworkStats( 3525): performPollLocked(flags=0x1)
D/SecContentProvider2( 3525): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3525): mCursor = null
,D/StatusBar.NetworkController( 3695): getUpdateDataNetType(): 0
,D/StatusBar.NetworkController( 3695): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3695): updateDataNetType()
D/StatusBar.NetworkController( 3695): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3695): updateLTEICONDataNetType:0
D/NetworkStatsFactory( 3525): UpdateStatsForKnox
,D/SmartBondingService( 3525): getNetworkEnabled : wifi : true mobile : false
,V/NetworkStats( 3525): performPollLocked() took 8ms
D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
V/NetworkStats( 3525): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 3695): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3695): updateTelephonySignalStrength: hasService=false ss=null
,D/StatusBar.NetworkController( 3695): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 3695): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3695): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
,I/Hs20UtilService( 4102): Starting #9
,I/Hs20UtilService( 4102): Message received 5007
,D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
,D/NearbySettings( 8862): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8862): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8862): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8862): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8862): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8862): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8862): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11392): NETWORK_STATE_CHANGED_ACTION
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,V/AlarmManager( 3525): waitForAlarm result :8
,D/ConnectivityService( 3525): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 3525): updateDataUsageMap
I/ApplicationPolicy( 3525): updateDataUsageMap  idList is null 
,D/SmartBondingService( 3525): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3525): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3525): getSBEnabled() enabled =false
D/SmartBondingService( 3525): getSBEnabled() enabled =false
D/SmartBondingService( 3525): getSBEnabled() enabled =false
,D/GpsLocationProvider( 3525): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3525): getNetworkEnabled : wifi : true mobile : false
,W/SLocation( 3525): No Active Data Connection
,I/DBG_DM  ( 6229): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/DBG_DM  ( 6229): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11859): MountEmulatedStorage()
E/Zygote  (11859): v2
I/libpersona(11859): KNOX_SDCARD checking this for 10110
I/libpersona(11859): KNOX_SDCARD not a persona
,I/SELinux (11859): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11859): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11859): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.iorg.vpn.cleanup.NetworkStateMonitor: pid=11859 uid=10110 gids={50110, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11859): TimaSignature is unavailable
,D/ActivityThread(11859): Added TimaKeyStore provider
,D/ResourcesManager(11859): creating new AssetManager and set to /data/app/com.facebook.appmanager-2/base.apk
,D/ACRA    (11859): ACRA is enabled for com.facebook.appmanager, intializing...
,I/DexLibLoader(11859): not using cross-dex optimization: ART in use
,I/art     (11859): Thread[1,tid=11859,WaitingForJniOnLoad,Thread*=0xb4e08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/app/com.facebook.appmanager-2/lib/arm/libfbjni.so"
,V/DexLibLoader(11859): about to lock: /data/data/com.facebook.appmanager/mdex_lock
,V/DexLibLoader(11859): locking /data/data/com.facebook.appmanager/mdex_lock took 1 ms
V/DexLibLoader(11859): Secondary program dex metadata: classes2.dex 29f80981f469a774a4884b3db2df17e0be227159 secondary.dex01.Canary
,D/DexLibLoader(11859): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex" is valid
D/DexLibLoader(11859): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex_opt" is valid
,W/art     (11859): Attempt to remove local handle scope entry from IRT, ignoring
D/DexLibLoader(11859): loading pre-built fallback odex files
,V/MultiDexClassLoader(11859): installing MultiDexClassLoader before application classloader
D/DexLibLoader(11859): released odex store lock
D/DexLibLoader(11859): DexLibLoader.loadAll took 19 ms
,W/ca      (11859): Verify
,W/LightSharedPreferencesImpl(11859): Failed to load preference file from Disk!
W/LightSharedPreferencesImpl(11859): java.io.FileNotFoundException: /data/data/com.facebook.appmanager/app_light_prefs/com.facebook.appmanager/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11859): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/LightSharedPreferencesImpl(11859): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/LightSharedPreferencesImpl(11859): 	at com.facebook.crudolib.b.k.a(LightSharedPreferencesStorage.java:56)
W/LightSharedPreferencesImpl(11859): 	at com.facebook.crudolib.b.g.run(LightSharedPreferencesImpl.java:61)
W/LightSharedPreferencesImpl(11859): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/LightSharedPreferencesImpl(11859): 	at com.facebook.common.executors.dj.run(WrappingExecutorService.java:77)
W/LightSharedPreferencesImpl(11859): 	at com.facebook.common.executors.u.run(DefaultConstrainedListeningExecutorService.java:327)
W/LightSharedPreferencesImpl(11859): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/LightSharedPreferencesImpl(11859): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/LightSharedPreferencesImpl(11859): 	at com.facebook.common.executors.cc.run(NamedThreadFactory.java:42)
W/LightSharedPreferencesImpl(11859): 	at java.lang.Thread.run(Thread.java:818)
W/LightSharedPreferencesImpl(11859): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11859): 	at libcore.io.Posix.open(Native Method)
W/LightSharedPreferencesImpl(11859): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/LightSharedPreferencesImpl(11859): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/LightSharedPreferencesImpl(11859): 	... 10 more
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11884): MountEmulatedStorage()
E/Zygote  (11884): v2
I/libpersona(11884): KNOX_SDCARD checking this for 1000
I/libpersona(11884): KNOX_SDCARD not a persona
,I/SELinux (11884): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11884): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11884): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3525): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=11884 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3525): Killing 9831:com.sec.android.app.shealth/u0a36 (adj 15): bgCount ##31
,W/appmanager(:<default>):b(11859): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/appmanager(:<default>):b(11859): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/TimaKeyStoreProvider(11884): TimaSignature is unavailable
,D/ActivityThread(11884): Added TimaKeyStore provider
,D/ResourcesManager(11884): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/PCWCLIENTTRACE_LOG(11884): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(11884): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(11884): new DMDBOpenHelper instance
,W/appmanager(:<default>):QuickExperimentControllerImpl(11859): Exposure of experiment com.facebook.common.network.l@2f02b977 occurred when no user was logged in
I/PCWCLIENTTRACE_PushUtil(11884): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11884): sales region : global
I/PCWCLIENTTRACE_PushUtil(11884): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11884): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver(11884): noConnectivity : true
,W/BroadcastQueue( 3525): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{28f8ddb0 u0 ReceiverList{2e57acf3 11859 com.facebook.appmanager/10110/u0 remote:266cf362}}
,W/BroadcastQueue( 3525): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{28f8ddb0 u0 ReceiverList{2e57acf3 11859 com.facebook.appmanager/10110/u0 remote:266cf362}}
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11908): MountEmulatedStorage()
I/libpersona(11908): KNOX_SDCARD checking this for 10135
E/Zygote  (11908): v2
I/libpersona(11908): KNOX_SDCARD not a persona
I/SELinux (11908): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11908): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11908): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=11908 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3525): Killing 10984:com.sec.android.provider.badge/u0a82 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(11908): TimaSignature is unavailable
,D/ActivityThread(11908): Added TimaKeyStore provider
,D/ResourcesManager(11908): creating new AssetManager and set to /system/app/Music2/Music2.apk
,W/BroadcastQueue( 3525): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{14f03374 u0 ReceiverList{54b6f47 11859 com.facebook.appmanager/10110/u0 remote:3eafba86}}
,I/MusicStore(11908): Database version: 104
,D/ResourcesManager(11908): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11908): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11908): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (11908): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(11908): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  (11908): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1935f354: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller(11908): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(11908): GMSCore installation verified
,I/ConfigStore(11908): Config Database version: 1
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11908): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,I/wpa_supplicant( 3826): nl80211: Received scan results (4 BSSes)
,I/wpa_supplicant( 3826): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3826): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3826): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 3826): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
E/WifiStateMachine( 3525): [1,454,591,280,766 ms] noteScanEnd no scan source
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11859): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
E/WifiStateMachine( 3525): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@21296866 sup_state=SCANNING debouncing=false
W/ContextImpl(11859): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/WifiStateMachine( 3525): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3525): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3525): setDetailed state send new extra info
,D/SecContentProvider2( 3525): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 3525): mCursor = null
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11908): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/ContextImpl(11908): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/appmanager(:<default>):QuickExperimentControllerImpl(11859): Exposure of experiment com.facebook.imagepipeline.a.g@cfc8b64 occurred when no user was logged in
,D/WifiDisplayAdapter( 3525): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,W/appmanager(:<default>):QuickExperimentControllerImpl(11859): Exposure of experiment com.facebook.imagepipeline.a.d@22efedc9 occurred when no user was logged in
,D/WifiDisplayAdapter( 3525): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3525): getStreamVolume 3 index 0
,I/MediaRouter(11908): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,I/art     (11859): Explicit concurrent mark sweep GC freed 45756(2MB) AllocSpace objects, 6(96KB) LOS objects, 22% free, 27MB/35MB, paused 812us total 22.220ms
,W/appmanager(:<default>):m(11859): No feature status reporters found; is this dead code?
,E/Zygote  (11943): MountEmulatedStorage()
,E/Zygote  (11943): v2
I/libpersona(11943): KNOX_SDCARD checking this for 10002
I/libpersona(11943): KNOX_SDCARD not a persona
I/SELinux (11943): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11943): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11943): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=11943 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/WifiDisplayAdapter( 3525): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/NetworkMonitor(11908): type=WIFI subType= reason=null isConnected=false
,D/TimaKeyStoreProvider(11943): TimaSignature is unavailable
,D/ActivityThread(11943): Added TimaKeyStore provider
,I/ActivityManager( 3525): Killing 10999:com.sec.android.app.samsungapps/u0a13 (adj 15): bgCount ##31
,I/wpa_supplicant( 3826): wlan0: State: ASSOCIATING -> ASSOCIATED
,I/wpa_supplicant( 3826): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
E/WifiStateMachine( 3525): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3525): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3525): setDetailed state send new extra info"NG700"
I/wpa_supplicant( 3826): Associated with C0.AA.48
D/SecContentProvider2( 3525): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3525): mCursor = null
,I/wpa_supplicant( 3826): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 3826): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 3826): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,E/WifiStateMachine( 3525): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3525): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,I/wpa_supplicant( 3826): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 3826): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 3826): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3826): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 3826): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 3826): Blacklist: Clear (temp) 
I/wpa_supplicant( 3826): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3525): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3525): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine( 3525): Network connection established
,D/WifiNative-HAL( 3525): callSECApiVoid - ID [50]
D/ResourcesManager(11943): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
E/WifiStateMachine( 3525): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine( 3525): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService( 3525): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine( 3525): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3525): L2ConnectedState "NG700" nid=0
D/ConnectivityService( 3525): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/WifiConfigStore( 3525): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 3525): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 3525): updateNetworkInfo()
,D/StatusBar.NetworkController( 3695): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3695): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3525): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
,E/WifiStateMachine( 3525): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3525): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3525): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/ActivityManager( 3525): Killing 11015:com.policydm/1000 (adj 13): bgCount ##31
,D/CommandListener( 2845): Setting iface cfg
,E/WifiStateMachine( 3525): Start Dhcp Watchdog 2
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/SecContentProvider2( 3525): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3525): mCursor = null
,E/Zygote  (11964): MountEmulatedStorage()
I/libpersona(11964): KNOX_SDCARD checking this for 1000
E/Zygote  (11964): v2
I/libpersona(11964): KNOX_SDCARD not a persona
I/SELinux (11964): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11964): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11964): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=11964 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/SecContentProvider2( 3525): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3525): mCursor = null
,E/WifiStateMachine( 3525): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3525): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,D/TimaKeyStoreProvider(11964): TimaSignature is unavailable
,D/ActivityThread(11964): Added TimaKeyStore provider
,I/art     ( 3525): Explicit concurrent mark sweep GC freed 76785(4MB) AllocSpace objects, 47(752KB) LOS objects, 24% free, 49MB/65MB, paused 1.943ms total 100.409ms
,D/ResourcesManager(11964): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT(11964): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,E/WifiStateMachine( 3525): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3525): do suspend false
,D/SecContentProvider2( 3525): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3525): mCursor = null
D/WifiP2pService( 3525): InactiveState{ what=143375 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=143375 }
,I/DIAGMON_AGENT(11964): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT(11964): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT(11964): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(11964): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11981): MountEmulatedStorage()
I/libpersona(11981): KNOX_SDCARD checking this for 10012
E/Zygote  (11981): v2
I/libpersona(11981): KNOX_SDCARD not a persona
,I/SELinux (11981): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11981): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3525): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=11981 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (11981): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11981): TimaSignature is unavailable
,D/ActivityThread(11981): Added TimaKeyStore provider
,D/ResourcesManager(11981): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager( 3525): Killing 11032:com.sec.android.app.soundalive/u0a59 (adj 15): bgCount ##31
,E/lowmemorykiller( 2828): Error writing /proc/11032/oom_score_adj; errno=22
,I/FOTA_Client(11981): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(11981): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(11981): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11997): MountEmulatedStorage()
I/libpersona(11997): KNOX_SDCARD checking this for 10021
E/Zygote  (11997): v2
I/libpersona(11997): KNOX_SDCARD not a persona
I/SELinux (11997): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11997): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11997): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=11997 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 3525): Killing 11053:com.wsomacp/u0a28 (adj 15): bgCount ##31
,E/lowmemorykiller( 2828): Error writing /proc/11053/oom_score_adj; errno=22
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 8743(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 480us total 10.874ms
,D/TimaKeyStoreProvider(11997): TimaSignature is unavailable
,D/ActivityThread(11997): Added TimaKeyStore provider
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 260us total 8.936ms
,D/ResourcesManager(11997): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 267us total 8.230ms
,I/KLMS-2.4.521: (11997): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Feb 04 14:08:01 GMT+01:00 2016
,I/KLMS-2.4.521: (11997): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (11997): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11997): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (11997): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
I/KLMS-2.4.521: (11997): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (11997): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (11997): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager( 3525): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=12014 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
E/Zygote  (12014): MountEmulatedStorage()
I/libpersona(12014): KNOX_SDCARD checking this for 10038
E/Zygote  (12014): v2
I/libpersona(12014): KNOX_SDCARD not a persona
,I/SELinux (12014): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12014): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12014): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/dhcpcd  (12013): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (12013): version 5.5.6 starting
,I/KLMS-2.4.521: (11997): StateImplV2(): networkChangeListener().END
,E/dhcpcd  (12013): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/KLMS-2.4.521: (11997): KLMSIntentService(): onDestroy()
,I/ActivityManager( 3525): Killing 11073:com.sec.spp.push/u0a39 (adj 15): bgCount ##31
,E/lowmemorykiller( 2828): Error writing /proc/11073/oom_score_adj; errno=22
,D/TimaKeyStoreProvider(12014): TimaSignature is unavailable
,D/ActivityThread(12014): Added TimaKeyStore provider
,D/ResourcesManager(12014): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/dhcpcd  (12013): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (12013): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (12013): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  (12013): bssid match
,I/dhcpcd  (12013): wlan0: rebinding lease of 192.168.1.124
,I/SO_AGENT(12014): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12035): MountEmulatedStorage()
E/Zygote  (12035): v2
I/libpersona(12035): KNOX_SDCARD checking this for 1000
I/libpersona(12035): KNOX_SDCARD not a persona
,I/SELinux (12035): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12035): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12035): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=12035 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3525): Killing 10861:com.google.android.apps.docs/u0a101 (adj 15): bgCount ##31
,E/lowmemorykiller( 2828): Error writing /proc/10861/oom_score_adj; errno=22
,D/TimaKeyStoreProvider(12035): TimaSignature is unavailable
,D/ActivityThread(12035): Added TimaKeyStore provider
,D/ResourcesManager(12035): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12055): MountEmulatedStorage()
I/libpersona(12055): KNOX_SDCARD checking this for 10039
E/Zygote  (12055): v2
I/libpersona(12055): KNOX_SDCARD not a persona
I/SELinux (12055): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12055): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12055): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=12055 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3525): Killing 11092:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12055): TimaSignature is unavailable
,D/ActivityThread(12055): Added TimaKeyStore provider
,D/ResourcesManager(12055): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService(12055): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(12055): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService(12055): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,D/SPPClientService(12055): PushLog.txt file is not deleted.
D/SPPClientService(12055): PushLog.txt file is not deleted.
D/SPPClientService(12055): ============PushLog. stop!
,I/SA      (11191): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11191): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      (11191): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      (11191): [SLFUCHKMGR] constructor called
,E/SPPClientService(12055): [[SystemStateMonitorService]] No Active Internet
,I/SA      (11191): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11191): [OR] == isSIMCardReady false ==
,I/SA      (11191): [SCU] == networkStateCheck == false
I/SA      (11191): [OR] onReceive END
,V/DownloadManager( 3719): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager( 3525): Killing 11130:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
,E/lowmemorykiller( 2828): Error writing /proc/11130/oom_score_adj; errno=22
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12075): MountEmulatedStorage()
I/libpersona(12075): KNOX_SDCARD checking this for 10067
E/Zygote  (12075): v2
I/libpersona(12075): KNOX_SDCARD not a persona
,I/SELinux (12075): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12075): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12075): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3525): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=12075 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12075): TimaSignature is unavailable
,D/ActivityThread(12075): Added TimaKeyStore provider
,D/ResourcesManager(12075): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/sCloudBackupApp(12075): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(12075): Other Intent
,I/ActivityManager( 3525): Killing 11154:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
,D/accuweather( 5191): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3776): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,D/accuweather( 5191): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5191): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5191): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5191): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5191): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5191): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12091): MountEmulatedStorage()
E/Zygote  (12091): v2
I/libpersona(12091): KNOX_SDCARD checking this for 1000
I/libpersona(12091): KNOX_SDCARD not a persona
,I/SELinux (12091): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12091): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12091): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=12091 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12091): TimaSignature is unavailable
,D/ActivityThread(12091): Added TimaKeyStore provider
,D/ResourcesManager(12091): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(12091): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro(12091): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro(12091): premStatus:2
,I/KnoxUsageLogPro(12091): isEulaShown : false
I/KnoxUsageLogPro(12091): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12106): MountEmulatedStorage()
I/libpersona(12106): KNOX_SDCARD checking this for 10090
E/Zygote  (12106): v2
I/libpersona(12106): KNOX_SDCARD not a persona
I/SELinux (12106): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12106): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12106): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=12106 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3525): Killing 11113:com.sec.android.automotive.drivelink/u0a102 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12106): TimaSignature is unavailable
,D/ActivityThread(12106): Added TimaKeyStore provider
,D/ResourcesManager(12106): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12122): MountEmulatedStorage()
I/libpersona(12122): KNOX_SDCARD checking this for 10127
E/Zygote  (12122): v2
I/libpersona(12122): KNOX_SDCARD not a persona
,I/SELinux (12122): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12122): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12122): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=12122 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3525): Killing 11247:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12122): TimaSignature is unavailable
,D/ActivityThread(12122): Added TimaKeyStore provider
,D/ResourcesManager(12122): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,D/KeyguardWallpaperUpdator(12122): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12122): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12122): stopCheckCategoryVersion
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12139): MountEmulatedStorage()
I/libpersona(12139): KNOX_SDCARD checking this for 10136
E/Zygote  (12139): v2
I/libpersona(12139): KNOX_SDCARD not a persona
I/SELinux (12139): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12139): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12139): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=12139 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3525): Killing 11266:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12139): TimaSignature is unavailable
,D/ActivityThread(12139): Added TimaKeyStore provider
,D/ResourcesManager(12139): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12139): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
W/ContextImpl(12139): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12139): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12139): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory(12139): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(12139): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(12139): Loading: webviewchromium
,I/LibraryLoader(12139): Time to load native libraries: 3 ms (timestamps 9273-9276)
I/LibraryLoader(12139): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(12139): Binding Chromium to main looper Looper (main, tid 1) {12a8f0c0}
,I/LibraryLoader(12139): Expected native library version number "",actual native library version number ""
,I/chromium(12139): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(12139): Initializing chromium process, renderers=0
,W/art     (12139): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(12139): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(12139): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium(12139): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,W/AudioManagerAndroid(12139): Requires BLUETOOTH permission
,I/NSApplication(12139): Starting up...
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12207): MountEmulatedStorage()
I/libpersona(12207): KNOX_SDCARD checking this for 10150
E/Zygote  (12207): v2
I/libpersona(12207): KNOX_SDCARD not a persona
I/SELinux (12207): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12207): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12207): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=12207 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager( 3525): Killing 11232:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12207): TimaSignature is unavailable
,D/ActivityThread(12207): Added TimaKeyStore provider
,D/ResourcesManager(12207): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(12207): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12207): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12207): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect(12207): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12207): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect(12207): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12222): MountEmulatedStorage()
I/libpersona(12222): KNOX_SDCARD checking this for 10178
E/Zygote  (12222): v2
I/libpersona(12222): KNOX_SDCARD not a persona
,I/SELinux (12222): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12222): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12222): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3525): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=12222 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager( 3525): Killing 11283:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12222): TimaSignature is unavailable
,D/ActivityThread(12222): Added TimaKeyStore provider
,D/ResourcesManager(12222): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(12222): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager(12222): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12222): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12222): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12222): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12222): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService( 3525): exchangeData() failure , invalid userId
,D/RCPManagerService( 3525): exchangeData() failure , invalid userId
,D/RCPManagerService( 3525): exchangeData() failure , invalid userId
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 3525): exchangeData() failure , invalid userId
,E/Zygote  (12245): MountEmulatedStorage()
E/Zygote  (12245): v2
I/libpersona(12245): KNOX_SDCARD checking this for 10082
I/libpersona(12245): KNOX_SDCARD not a persona
,I/SELinux (12245): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12245): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12245): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/RCPManagerService( 3525): exchangeData() failure , invalid userId
,I/ActivityManager( 3525): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=12245 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 8756(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 481us total 10.589ms
,D/RCPManagerService( 3525): exchangeData() failure , invalid userId
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 276us total 8.076ms
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider(12245): TimaSignature is unavailable
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/ActivityThread(12245): Added TimaKeyStore provider
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 360us total 8.444ms
,E/Zygote  (12261): MountEmulatedStorage()
I/libpersona(12261): KNOX_SDCARD checking this for 1000
E/Zygote  (12261): v2
I/libpersona(12261): KNOX_SDCARD not a persona
,I/SELinux (12261): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3525): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=12261 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux (12261): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12261): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3525): Killing 11415:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##31
I/ActivityManager( 3525): Killing 11298:com.samsung.helphub/1000 (adj 13): bgCount ##32
,D/TimaKeyStoreProvider(12261): TimaSignature is unavailable
,D/ActivityThread(12261): Added TimaKeyStore provider
,D/ResourcesManager(12245): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/ResourcesManager(12261): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/BadgeProvider(12245): onCreate
D/BadgeProvider(12245): DatabaseHelper
,I/ActivityManager( 3525): Killing 11432:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
,D/BadgeProvider(12245): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider(12245): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12245): sendNotify, [notify] : null
D/BadgeProvider(12245): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12245): update, [BadgeCount] : badgecount=0
D/BadgeProvider(12245): update, [UpdateCount] : 1
,D/Launcher.Model( 4001): reloadBadges entered.
,I/iu.Environment( 6656): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 6656): num queued entries: 0
,I/iu.UploadsManager( 6656): num updated entries: 0
I/iu.SyncManager( 6656): NEXT; no task
,W/ActivityManager( 3525): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12279): MountEmulatedStorage()
E/Zygote  (12279): v2
I/libpersona(12279): KNOX_SDCARD checking this for 10013
I/libpersona(12279): KNOX_SDCARD not a persona
,I/SELinux (12279): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12279): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12279): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3525): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=12279 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12279): TimaSignature is unavailable
,D/ActivityThread(12279): Added TimaKeyStore provider
,D/ResourcesManager(12279): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,I/ActivityManager( 3525): Killing 11449:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##31
,I/Hs20UtilService( 4102): Starting #10
,I/Hs20UtilService( 4102): Message received 5007
,D/NearbySettings( 8862): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8862): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8862): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 8862): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8862): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8862): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8862): MountReceiver.mPrefHandler - 7002
,I/dhcpcd  (12013): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
,I/SignOutReceiver(11392): NETWORK_STATE_CHANGED_ACTION
,I/dhcpcd  (12013): wlan0: leased 192.168.1.124 for 86400 seconds
,E/WifiStateMachine( 3525): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3525): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,I/jxcore-log(11753): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log(11753): 
,E/WifiStateMachine( 3525): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine( 3525): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  ( 3525): do suspend true
,D/WifiP2pService( 3525): InactiveState{ what=143375 }
D/WifiP2pService( 3525): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 3525): WifiStateMachine DHCP successful
,E/WifiStateMachine( 3525): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3525): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine( 3525): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3525): Not connected state, yet.
E/WifiStateMachine( 3525): VerifyingLinkState enter
,D/WifiStateMachine( 3525): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine( 3525): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3525): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3525): callSECApiInt - ID [210]
,E/WifiStateMachine( 3525): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
D/StatusBar.NetworkController( 3695): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3695): onWifiSignalChanged enabled=true enabledDesc:null
E/ConnectivityService( 3525): updateNetworkInfo()
,D/ConnectivityService( 3525): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 3525): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 3525): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 3525): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 3525): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 3525): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3525): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 3695): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3695): onWifiSignalChanged enabled=true enabledDesc:null
,I/Hs20UtilService( 4102): Starting #11
,I/Hs20UtilService( 4102): Message received 5007
,D/NearbySettings( 8862): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8862): MountReceiver.onReceive - Keep current state
,D/ConnectivityService( 3525): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService( 3525): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,E/WifiStateMachine( 3525): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine( 3525): Now, connected state.
E/WifiStateMachine( 3525): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,D/ConnectivityService( 3525): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService( 3525): Unexpected mtu value: 0, wlan0
,V/        ( 2845): QcRouteController
,E/WifiStateMachine( 3525): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/WifiTrafficPoller( 3525): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 3695): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3695): onWifiSignalChanged enabled=true enabledDesc:null
,V/        ( 2845): QcRouteController
,I/SignOutReceiver(11392): NETWORK_STATE_CHANGED_ACTION
,E/WifiStateMachine( 3525): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller( 3525): evaluateTrafficStatsPolling
D/WifiNative-HAL( 3525): callSECApiVoid - ID [212]
V/        ( 2845): QcRouteController
,E/WifiStateMachine( 3525): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/StatusBar.NetworkController( 3695): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3695): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3695): applyOpen
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
,I/WifiStateMachine( 3525): REQUEST_POWER_SAVE_ON
,V/        ( 2845): QcRouteController
,I/Hs20UtilService( 4102): Starting #12
I/Hs20UtilService( 4102): Message received 5007
,D/NearbySettings( 8862): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8862): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8862): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8862): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8862): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8862): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 8862): MountReceiver.mPrefHandler - 7002
,V/        ( 2845): QcRouteController
,V/        ( 2845): QcRouteController
,V/        ( 2845): QcRouteController
I/SignOutReceiver(11392): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4102): Starting #13
,I/Hs20UtilService( 4102): Message received 5007
,V/        ( 2845): QcRouteController
,D/NearbySettings( 8862): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8862): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine( 3525): callSECApi what=220
D/WifiStateMachine( 3525): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/ConnectivityService( 3525): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService( 3525): LTETest block dns file not exists
,D/ConnectivityService( 3525): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 3525): updateNetworkInfo()
E/ConnectivityService( 3525): updateNetworkInfo()
D/ConnectivityService( 3525): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 3525): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3525): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 3525): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3525): Connected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3525): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3525): Checking http://clients3.google.com/generate_204 on "NG700"
,I/System.out( 3525): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 1000
,D/ConnectivityService( 3525):    accepting network in place of null
,D/TelephonyNetworkFactory( 3984): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/CSLegacyTypeTracker( 3525): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 3525): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 3525): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService( 3525): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/Tethering( 3525): MasterInitialState.processMessage what=3
,D/EntConnectivity( 3525): Not allowed due to - mEnabled false
D/ConnectivityService( 3525): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
I/SignOutReceiver(11392): NETWORK_STATE_CHANGED_ACTION
D/SmartBondingService( 3525): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 3695): CM callback handler got msg 524290
D/SmartBondingService( 3525): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3525): getSBEnabled() enabled =false
D/SmartBondingService( 3525): getSBEnabled() enabled =false
D/SmartBondingService( 3525): getSBEnabled() enabled =false
,V/NetworkStats( 3525): updateIfacesLocked()
V/NetworkStats( 3525): performPollLocked(flags=0x1)
D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
,D/ConnectivityManager.CallbackHandler( 6656): CM callback handler got msg 524290
,D/SmartBondingService( 3525): getNetworkEnabled : wifi : true mobile : false
,D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
D/NetworkStatsFactory( 3525): UpdateStatsForKnox
,D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
V/NetworkStats( 3525): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
V/NetworkStats( 3525): performPollLocked() took 7ms
,D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
,I/SurfaceFlinger( 2849): id=15 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 3525): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3525
,D/mali_winsys( 3695): new_window_surface returns 0x3000,  [1120x201]-format:1
,D/StatusBar.NetworkController( 3695): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3695): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3695): updateDataNetType()
D/StatusBar.NetworkController( 3695): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3695): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3695): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3695): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3695): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 3695): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3695): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
,I/System.out( 3525): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3525): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 04 Feb 2016 13:08:02 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454591282862], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454591282849]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3525): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3525): Validated
,D/ConnectivityService( 3525): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3525): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3525): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 3525): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 3695): CM callback handler got msg 524290
D/ConnectivityService( 3525): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 6656): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 3695): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3695): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3695): updateDataNetType()
D/StatusBar.NetworkController( 3695): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3695): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3695): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3695): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3695): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3695): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3695): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,I/jxcore-log(11753): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log(11753): 
,I/jxcore-log(11753): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log(11753): 
,I/jxcore-log(11753): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log(11753): 
,I/jxcore-log(11753): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log(11753): 
,I/jxcore-log(11753): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log(11753): 
,I/jxcore-log(11753): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log(11753): 
,I/jxcore-log(11753): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log(11753): 
,D/ConnectivityService( 3525): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3525): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3525): SmartBondingReceiver: wifi is connected
D/SmartBondingService( 3525): SmartBondingReceiver: wifi ap is not changed
,D/SmartBondingService( 3525): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3525): getSBEnabled() enabled =false
D/SmartBondingService( 3525): getSBEnabled() enabled =false
D/SmartBondingService( 3525): getSBEnabled() enabled =false
,D/SmartBondingService( 3525): getNetworkEnabled : wifi : true mobile : false
,I/DBG_DM  ( 6229): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 6229): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/NetworkMonitor(11908): type=WIFI subType= reason=null isConnected=true
,W/ResourceType( 5344): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5344): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,I/PCWCLIENTTRACE_PushUtil(11884): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11884): sales region : global
I/PCWCLIENTTRACE_PushUtil(11884): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11884): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 3525): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/SecContentProvider2( 3525): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3525): mCursor = null
,I/DIAGMON_AGENT(11964): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(11964): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/FOTA_Client(11981): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(11981): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(11981): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.521: (11997): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Feb 04 14:08:03 GMT+01:00 2016
,I/KLMS-2.4.521: (11997): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (11997): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11997): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (11997): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (11997): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,V/GLSActivity( 4632): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SO_AGENT(12014): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,V/GLSActivity( 4632): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/KLMS-2.4.521: (11997): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (11997): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.521: (11997): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.521: (11997): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.521: (11997): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.4.521: (11997): StateImplV2(): networkChangeListener().END
,I/KLMS-2.4.521: (11997): KLMSIntentService(): onDestroy()
,E/SPPClientService(12055): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      (11191): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11191): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (11191): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (11191): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11191): [OR] == isSIMCardReady false ==
,I/SA      (11191): [SCU] == networkStateCheck == true
,I/SA      (11191): [DM] getCountryCodeFromCSC : PL
I/SA      (11191): isChinaCountryCode : false
I/SA      (11191): [SCU] is ChinestModel Data Restricted   : false
I/SA      (11191): [OR] == networkStateCheck true ==
I/SA      (11191): [OR] GetMyCountryZoneTask
I/SA      (11191): [OR] onReceive END
,I/SA      (11191): [SRS] prepareGetMyCountryZone
,I/SA      (11191): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (11191): [SSP] query invoked
,V/DownloadManager( 3719): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      (11191): [TPMU] GetMccFromDB : null
I/SA      (11191): [SCU] getMccFromPreferece mcc = 260
I/SA      (11191): [TPM] isNoProxy(default) : true
,I/art     ( 4632): Explicit concurrent mark sweep GC freed 71049(4MB) AllocSpace objects, 37(1456KB) LOS objects, 34% free, 30MB/46MB, paused 2.831ms total 43.050ms
,I/SCloudBackupReceiver(12075): Other Intent
,D/accuweather( 5191): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3776): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,D/accuweather( 5191): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5191): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5191): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5191): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5191): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5191): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro(12091): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro(12091): premStatus:2
,I/KnoxUsageLogPro(12091): isEulaShown : false
I/KnoxUsageLogPro(12091): KnoxUsageReceiver onReceive : not Processible, just return
,D/KeyguardWallpaperUpdator(12122): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12122): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12122): stopCheckCategoryVersion
,D/QuickConnect(12207): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12207): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect(12207): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 3525): exchangeData() failure , invalid userId
,D/RCPManagerService( 3525): exchangeData() failure , invalid userId
,W/art     (11330): Attempt to remove local handle scope entry from IRT, ignoring
,I/iu.Environment( 6656): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 6656): num queued entries: 0
,I/art     ( 3525): Explicit concurrent mark sweep GC freed 47748(2MB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 49MB/65MB, paused 2.699ms total 87.320ms
,I/iu.UploadsManager( 6656): num updated entries: 0
,I/iu.SyncManager( 6656): NEXT; no task
,D/WaitQueueForNetworkActivate(12279): notifyNetworkActivated
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 10014
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 10147
,W/ContextImpl(12279): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3525): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/hcjo    (12279): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12279): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12279): exit::IDLE
D/InitializeManagerStateMachine(12279): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12279): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12279): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12279): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12279): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12279): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12279): entry::SUCCESS
D/hcjo    (12279): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (12279): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12279): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine(12279): exit::SUCCESS
D/InitializeManagerStateMachine(12279): entry::IDLE
,I/SA      (11191): [RC New] Execute method=[GET] start
,I/SA      (11191): [RC New] Security=[true]
,I/System.out(11191): Thread-1540(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out(11191): Thread-1540(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11191): Thread-1540(ApacheHTTPLog):isShipBuild true
I/System.out(11191): Thread-1540(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 10045
,D/ConnectivityService( 3525): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/SA      (11191): [RC New] [v2liruge] api execute + 583
I/SA      (11191): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out(11191): AsyncTask #1 calls detatch()
I/SA      (11191): [TPMU] getNetworkMcc : 
,I/SA      (11191): [SCU] saveMccToPreferece Start
I/SA      (11191): [SCU] RegionMCC : 260
I/SA      (11191): [SSP] query invoked
,I/SA      (11191): [TPMU] GetMccFromDB : null
I/SA      (11191): [SCU] getMccFromPreferece mcc = 260
I/SA      (11191): [SCU] saveMccToPreferece End
,I/SA      (11191): [RC New] executeRequest [v2liruge] end. 603
I/SA      (11191): [RC New] Execute end
I/SA      (11191): [OR] GetMyCountryZoneTask mcc = 260
I/SA      (11191): [OR] GetMyCountryZoneTask Success
,I/dhcpcd  (12013): wlan0: sending IPv6 Router Solicitation
,E/dhcpcd  (12013): wlan0: sendmsg: Cannot assign requested address
,E/WifiStateMachine( 3525): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3525): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityService( 3525): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
V/        ( 2845): QcRouteController
D/SmartBondingService( 3525): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/SmartBondingService( 3525): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3525): getSBEnabled() enabled =false
D/SmartBondingService( 3525): getSBEnabled() enabled =false
D/SmartBondingService( 3525): getSBEnabled() enabled =false
,V/        ( 2845): QcRouteController
,W/NetworkManagementService( 3525): route cmd failed: 
W/NetworkManagementService( 3525): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '76 route replace src v6 wlan0 fe80::92b6:86ff:fe43:731c 2 ::' failed with '400 76 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService( 3525): '
W/NetworkManagementService( 3525): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService( 3525): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService( 3525): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService( 3525): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService( 3525): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService( 3525): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5738)
W/NetworkManagementService( 3525): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5545)
W/NetworkManagementService( 3525): 	at com.android.server.ConnectivityService.access$2600(ConnectivityService.java:231)
W/NetworkManagementService( 3525): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2436)
W/NetworkManagementService( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ConnectivityService( 3525): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3695): CM callback handler got msg 524295
D/ConnectivityService( 3525): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 3695): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 6656): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 6656): CM callback handler got msg 524295
,D/WearableService( 4632): callingUid 10014, callindPid: 4632
,D/ResourcesManager(11908): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11908): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11908): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory(11908): Using the GMSCore's GoogleHttpClient
,I/MusicLeanback(11908): Conditions not met for autocaching.
,I/MusicLeanback(11908): Stop autocaching.
,D/WearableClient(11908): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11908): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11908): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11908): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(11908): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils(11908): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/ActivityThread(11908): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@393ad1ac that was originally bound here
E/ActivityThread(11908): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@393ad1ac that was originally bound here
E/ActivityThread(11908): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(11908): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(11908): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(11908): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(11908): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(11908): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(11908): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11908): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11908): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11908): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(11908): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(11908): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(11908): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(11908): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(11908): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(11908): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(11908): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(11908): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(11908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(11908): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(11908): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(11908): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(11908): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(11908): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(11908): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/WifiStateMachine( 3525): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine( 3525): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/SurfaceFlinger( 2849): id=15 Removed Uoast (8/9)
,I/SurfaceFlinger( 2849): id=15 Removed Uoast (-2/9)
,D/PowerManagerService( 3525): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3525) eventTime = 243638
,D/PowerManagerService( 3525): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3525 (0x0)
D/PowerManagerService( 3525): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3525, ws=WorkSource{10060}) (elapsedTime=3466)
,I/jxcore-log(11753): Test app app.js loaded
I/jxcore-log(11753): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11753): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11753): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11753): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11753): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11753): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11753): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11753): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11753): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11753): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11753): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af3887e added. We now have 1 listener(s)
,I/jxcore-log(11753): BLE advertisement is supported
I/jxcore-log(11753): 
,I/chromium(11753): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log(11753): --= Surplus to requirements =--
I/jxcore-log(11753): 
I/jxcore-log(11753): ****TEST TOOK:  ms ****
I/jxcore-log(11753): 
I/jxcore-log(11753): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(11753): 
,D/AndroidRuntime(12391): 
D/AndroidRuntime(12391): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(12391): CheckJNI is OFF
,D/AndroidRuntime(12391): readGMSProperty: start
D/AndroidRuntime(12391): readGMSProperty: already setted!!
,D/AndroidRuntime(12391): readGMSProperty: end
D/AndroidRuntime(12391): addProductProperty: start
,E/AffinityControl(12391): AffinityControl: registerfunction enter
,D/AndroidRuntime(12391): Calling main entry com.android.commands.pm.Pm
,D/PersonaManagerService( 3525): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 3525): START PACKAGE DELETE: observer{942939816}
D/PackageManager( 3525): pkg{<packageName>}
D/PackageManager( 3525): user{0}
D/PackageManager( 3525): caller{2000}
D/PackageManager( 3525): flags{3}
D/PersonaManagerService( 3525): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3525): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3525): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3525): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 3525): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 3525): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 3525): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 3525): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3525): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 3525): !@killApplicatoin: 10628, uninstall pkg
I/ActivityManager( 3525): Force stopping com.test.thalitest appid=10628 user=-1: uninstall pkg
I/ActivityManager( 3525): Killing 11753:com.test.thalitest/u0a628 (adj 0): stop com.test.thalitest
,I/ActivityManager( 3525):   Force finishing activity ActivityRecord{2d3a4c95 u0 com.test.thalitest/.MainActivity t26}
,W/ActivityManager( 3525): mDVFSHelper.acquire()
,W/PackageSettings( 3525): Skipping PackageSetting{12e12d8a com.example.hello/10563} due to missing metadata
,I/ActivityManager( 3525): Force stopping com.test.thalitest appid=10628 user=0: pkg removed
,D/WifiService( 3525): Client connection lost with reason: 4
I/ActivityManager( 3525):   Force finishing activity ActivityRecord{2d3a4c95 u0 com.test.thalitest/.MainActivity t26 f}
W/ActivityManager( 3525): Duplicate finish request for ActivityRecord{2d3a4c95 u0 com.test.thalitest/.MainActivity t26 f}
,I/WindowState( 3525): WIN DEATH: Window{2a0d7d03 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger( 2849): id=14 Removed NainActivit (5/8)
,I/SurfaceFlinger( 2849): id=14 Removed NainActivit (-2/8)
,D/PointerIcon( 3525): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3525): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3525): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3525): setHoveringSpenCustomIcon IconType is same.1
,I/DBG_DM  ( 6229): [com.wssyncmldm.ui.XUIInstallConfirmActivity(456/onResume)] 
,I/DBG_DM  ( 6229): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 11
,I/DBG_DM  ( 6229): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,I/DBG_DM  ( 6229): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6229): [com.wssyncmldm.ui.XUIInstallConfirmActivity(466/onResume)] Postpone Count : 11
,D/ResourcesManager( 3525): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/art     ( 6656): Explicit concurrent mark sweep GC freed 25298(1450KB) AllocSpace objects, 3(48KB) LOS objects, 20% free, 31MB/39MB, paused 621us total 28.256ms
,I/art     ( 8956): Explicit concurrent mark sweep GC freed 27683(1574KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 426us total 25.369ms
I/DBG_DM  ( 6229): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk,
I/DBG_DM  ( 6229): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/art     ( 4050): Explicit concurrent mark sweep GC freed 30903(1914KB) AllocSpace objects, 0(0B) LOS objects, 21% free, 28MB/36MB, paused 455us total 32.417ms
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,I/InputReader( 3525): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,E/SamsungIME( 4473): mOCRHelper is null
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,W/GeofencerStateMachine( 4632): Ignoring removeGeofence because network location is disabled.
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/LWLocationManager(11467): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(11467): getLastUiLocationId() : mLastUiLocationId = -100
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,E/Zygote  (12404): MountEmulatedStorage()
E/Zygote  (12404): v2
I/libpersona(12404): KNOX_SDCARD checking this for 10063
I/libpersona(12404): KNOX_SDCARD not a persona
,I/ActivityManager( 3525): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=12404 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (12404): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/talkback/talkback.apk
,W/ResourceType( 5344): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5344): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,I/SELinux (12404): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12404): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/GAV4    (12139): Thread[GAThread,5,main]: No campaign data found.
,I/DBG_DM  ( 6229): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/ResourcesManager(11467): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/SecContentProvider2( 3525): uri = 14 selection = getSealedState
D/SecContentProvider2( 3525): mCursor = null
,D/TimaKeyStoreProvider(12404): TimaSignature is unavailable
,D/ActivityThread(12404): Added TimaKeyStore provider
,D/ApplicationPolicy( 3525): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3525): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/ResourcesManager(11467): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,I/DBG_DM  ( 6229): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 11
,I/art     ( 3525): Explicit concurrent mark sweep GC freed 27165(1943KB) AllocSpace objects, 5(80KB) LOS objects, 24% free, 49MB/65MB, paused 1.673ms total 109.142ms
,I/DBG_DM  ( 6229): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,I/DBG_DM  ( 6229): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6229): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 6229): [llIIlIIlIllIllIlllII(376/llIIllllIIlllIIIIlll)] 
,D/ResourcesManager(11467): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
I/DBG_DM  ( 6229): [IIlIIIlllllIIlIIIlII(339/llllIlIIIllllIIlIlll)] No need to check encryption status
,I/DBG_DM  ( 6229): [llIIlIIlIllIllIlllII(405/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
,D/ActivityManager( 3525): post active user change for 0
D/KnoxTimeoutHandler( 3525): postActiveUserChange for user 0
,I/DBG_DM  ( 6229): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
,I/SurfaceFlinger( 2849): id=16 createSurf (1440x2560),2 flag=404, YUIInstallC
,D/StatusBarManagerService( 3525): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3525): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/ResourcesManager(11467): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/ResourcesManager(12404): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,D/PointerIcon( 3525): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3525): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3525): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3525): setHoveringSpenCustomIcon IconType is same.1
V/ActivityThread( 6229): updateVisibility : ActivityRecord{11f8c6e9 token=android.os.BinderProxy@16cb5a2 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/InputMethodManagerService( 3525): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService( 3525): Got RemoteException sending setActive(false) notification to pid 11753 uid 10628
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(11467): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/PackageManager( 3525): delete codoeFile: 
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/VRSetupWizardStub/PackageIntentReceiver(12404): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(12404): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(12404): packagename:com.test.thalitest
,I/AASAUninstall( 3525):  com.test.thalitest not target!
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/PackageManager( 3525): result of delete: 1{942939816}
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/AndroidRuntime(12391): Shutting down VM
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/SecContentProvider2( 3525): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3525): mCursor = null
,D/EnterpriseDeviceManagerService( 3525): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3525): Admin package name: com.google.android.gms
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(11467): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/RegisteredServicesCache( 3967): empty dynamic service
,I/KLMS-2.4.521: (11997): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Feb 04 14:08:06 GMT+01:00 2016
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,I/KLMS-2.4.521: (11997): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 3525): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3525): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Music2/Music2.apk
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11467): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
I/KLMS-2.4.521: (11997): KLMSIntentService(): onCreate()
,I/Timeline( 6229): Timeline: Activity_idle id: android.os.BinderProxy@16cb5a2 time:244358
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,I/KLMS-2.4.521: (11997): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,I/KLMS-2.4.521: (11997): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (11997): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
E/Zygote  (12427): MountEmulatedStorage()
E/Zygote  (12427): v2
I/libpersona(12427): KNOX_SDCARD checking this for 10106
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
I/libpersona(12427): KNOX_SDCARD not a persona
,I/KLMS-2.4.521: (11997): KLMSIntentService(): PACKAGE_REMOVED
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(11467): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
I/KLMS-2.4.521: (11997): KLMSIntentService(): listeningToPackageRemoved().START
I/SELinux (12427): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,I/KLMS-2.4.521: (11997): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,I/ActivityManager( 3525): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=12427 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,I/SELinux (12427): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12427): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(11467): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager(11467): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(11467): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/RCPManager(12091):  in createShortcut() for packageName: com.test.thalitest userId0
D/ResourcesManager(11467): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/RCPManagerService( 3525):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3525): queryAllProviders():  providerCallBack is not register for 0
,D/TimaKeyStoreProvider(12427): TimaSignature is unavailable
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ActivityThread(12427): Added TimaKeyStore provider
,W/ActivityManager( 3525): mDVFSHelper.release()
D/ResourcesManager(11467): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
I/Timeline( 3525): Timeline: Activity_windows_visible id: ActivityRecord{274ad943 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t24} time:244410
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
,D/ResourcesManager(11467): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3525): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(12427): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,I/KLMS-2.4.521: (11997): KLMSIntentService(): listeningToPackageRemoved().END
,D/ResourcesManager(11467): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(11467): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(11467): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11467): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11467): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,E/Zygote  (12442): MountEmulatedStorage()
E/Zygote  (12442): v2
I/libpersona(12442): KNOX_SDCARD checking this for 10183
I/libpersona(12442): KNOX_SDCARD not a persona
,D/elm:14491(12427): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,I/SELinux (12442): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/elm:14491(12427): ELMEngine.ELMEngine( context ).
D/elm:14491(12427): MDMBridge.setEnterpriseBridge()
,I/ActivityManager( 3525): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=12442 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
,I/SELinux (12442): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/ResourcesManager(11467): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,E/SELinux (12442): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/elm:14491(12427): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,I/KLMS-2.4.521: (11997): KLMSIntentService(): onDestroy()
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/elm:14491(12427): ElmAgentService : onCreate()
D/elm:14491(12427): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/ResourcesManager(11467): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/elm:14491(12427): MainReceiver.listeningToPackageRemoved()
D/elm:14491(12427): MDMBridge.getInstance()
D/elm:14491(12427): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14491(12427): MDMBridge.getAllLicenseInfoFromSDK()
,D/TimaKeyStoreProvider(12442): TimaSignature is unavailable
,D/ActivityThread(12442): Added TimaKeyStore provider
,E/Zygote  (12458): MountEmulatedStorage()
E/Zygote  (12458): v2
I/libpersona(12458): KNOX_SDCARD checking this for 10101
I/libpersona(12458): KNOX_SDCARD not a persona
,D/ResourcesManager(11467): creating new AssetManager and set to /system/app/Videos/Videos.apk
I/SELinux (12458): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12458): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3525): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=12458 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (12458): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
W/ResourceType( 3525): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/TimaKeyStoreProvider(12458): TimaSignature is unavailable
,D/ActivityThread(12458): Added TimaKeyStore provider
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
D/ResourcesManager(12442): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/RCPManagerService( 3525): PackageReceiver onReceive()
,I/HarmonyEASService( 3525): onReceive : android.intent.action.PACKAGE_REMOVED for 0
E/Zygote  (12474): MountEmulatedStorage()
E/Zygote  (12474): v2
I/libpersona(12474): KNOX_SDCARD checking this for 10050
I/libpersona(12474): KNOX_SDCARD not a persona
,I/SELinux (12474): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/KnoxMUMContainerPolicy( 3525): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService( 3525): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 3525): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3525): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3525): uID is 10628
V/EnterpriseBillingPolicy( 3525): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3525): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 3525): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3525): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3525): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3525): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 3525): getBillingProfileForVpnEngine - end - null
I/SELinux (12474): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3525): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=12474 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
E/SELinux (12474): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 3525): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,D/ResourcesManager(11467): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/elm:14491(12427): ElmAgentService : onDestroy().
W/ResourcesManager( 3525): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3525): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3525): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider(12474): TimaSignature is unavailable
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/ActivityThread(12474): Added TimaKeyStore provider
,E/SQLiteLog(12442): (284) automatic index on shooting_modes(title_id)
D/ResourcesManager(12458): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,E/Zygote  (12489): MountEmulatedStorage()
E/Zygote  (12489): v2
I/libpersona(12489): KNOX_SDCARD checking this for 10019
I/libpersona(12489): KNOX_SDCARD not a persona
,I/SELinux (12489): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,I/SELinux (12489): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12489): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3525): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=12489 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,D/KnoxTimeoutHandler( 3525): handleActiveUserChange for user 0
,D/ResourcesManager(11467): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/ActivityManager( 3525): Killing 11484:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/TimaKeyStoreProvider(12489): TimaSignature is unavailable
,D/ActivityThread(12489): Added TimaKeyStore provider
W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TaskPersister( 3525): removeObsoleteFile: deleting file=26_task.xml
,D/UsbSettingsManager( 3525): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 3525): onPackageRemoved : com.test.thalitest
D/TaskPersister( 3525): removeObsoleteFile: deleting file=24_task.xml
D/ResourcesManager(12474): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/ResourcesManager(12474): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(12474): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12474): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12474): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12474): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(12474): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(12474): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12474): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/ActivityManager( 3525): Killing 11501:com.android.calendar/u0a164 (adj 13): bgCount ##31
,D/ResourcesManager(12489): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/ResourcesManager(11467): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/StatusBar( 3695): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 3695): isKioskContainerExistOnDevice
D/PersonaManager( 3695): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3695): Icon Only
I/StatusBar( 3695): Icon Only
D/PanelView( 3695): There is/are notification(s) 
D/PanelView( 3695): There is/are notification(s) 
,D/PersonaManager( 3695): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3695): Icon Only
I/StatusBar( 3695): Icon Only
D/PanelView( 3695): There is/are notification(s) 
,E/Zygote  (12505): MountEmulatedStorage()
I/libpersona(12505): KNOX_SDCARD checking this for 10190
E/Zygote  (12505): v2
I/libpersona(12505): KNOX_SDCARD not a persona
,I/SELinux (12505): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3525): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=12505 uid=10190 gids={50190, 9997} abi=armeabi-v7a
,I/SELinux (12505): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12505): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Killing 11467:com.sec.android.widgetapp.locationwidget/u0a22 (adj 13): bgCount ##31
,D/com.sec.android.service.health.upgrade.UninstallReceiver(12489): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver(12489): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver(12489): onReceive() : package name is not s health. Return !!!
I/ActivityManager( 3525): Killing 10799:com.android.defcontainer/u0a5 (adj 13): bgCount ##31
D/TimaKeyStoreProvider(12505): TimaSignature is unavailable
D/ActivityThread(12505): Added TimaKeyStore provider
,D/DocsApplication(12458): Installing DEX configuration.
,D/ResourcesManager(12505): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
D/DexInstaller(12458): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,I/PackageInfoHelper(12458): Provided clientMode=RELEASE, packageInfo=PackageInfo{3bbb601 com.google.android.apps.docs}
,D/TAG     (12458): onCreate()
,D/CrossAppStateProvider(12458): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,I/TapandpayWidget:TanpandpayAppWidgetProvider(12505): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(12505): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,I/TapandpayWidget:Utils(12505): Clear T&P info.
,D/TapandpayWidget:TanpandpayAppWidgetProvider(12505): Widget is not attached.
,I/ActivityManager( 3525): Killing 10386:com.android.vending/u0a31 (adj 13): bgCount ##31
,D/PackageBroadcastService( 6656): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 6656): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 6656): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6656): Module APK com.google.android.play.games already loaded
,D/PanelView( 3695): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,I/LocationSettingsChecker( 6656): Removing dialog suppression flag for package com.test.thalitest
,D/ChimeraCfgMgr( 6656): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6656): Module APK com.google.android.play.games already loaded
,D/gH_CompatibleDatabase( 6656): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 6656): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 6656): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 6656): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 6656): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 6656): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 6656): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 6656): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 6656): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 6656): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 6656): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 6656): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 6656): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/PCWCLIENTTRACE_PushUtil(11884): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11884): sales region : global
I/PCWCLIENTTRACE_PushUtil(11884): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11884): [onReceive] - android.intent.action.PACKAGE_REMOVED
,E/NetworkScheduler.SchedulerReceiver( 4632): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 4632): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/PackageManager( 3525): findPreferredActivity: No PreferredActivities set
,E/Zygote  (12531): MountEmulatedStorage()
,E/Zygote  (12531): v2
I/libpersona(12531): KNOX_SDCARD checking this for 10035
I/libpersona(12531): KNOX_SDCARD not a persona
I/SELinux (12531): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12531): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3525): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=12531 uid=10035 gids={50035, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
E/SELinux (12531): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12531): TimaSignature is unavailable
,D/ActivityThread(12531): Added TimaKeyStore provider
,I/Icing   ( 6656): doRemovePackageData com.test.thalitest
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/NearbySource(12474): Nearby Source Create!
,D/NearbyContext(12474): Nearby Context Create!
,D/ResourcesManager(12531): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,E/Zygote  (12551): MountEmulatedStorage()
E/Zygote  (12551): v2
I/libpersona(12551): KNOX_SDCARD checking this for 10031
I/libpersona(12551): KNOX_SDCARD not a persona
,W/FileUtils( 6656): Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,E/Icing   ( 6656): Failed to open Apps corpus file.
,E/Icing   ( 6656): Failed to open Apps corpus file.
,I/ActivityManager( 3525): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=12551 uid=10031 gids={50031, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SharedPreferencesImpl( 6656): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml to backup file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml.bak
,I/SELinux (12551): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,E/ActivityThread(11859): Failed to find provider info for com.facebook.appmanager.installrecord
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 8730(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 630us total 11.394ms
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12474): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource(12474): Samsung link source created
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 259us total 8.585ms
,I/SELinux (12551): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12551): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/FeatureConfig(12531): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
I/art     ( 2879): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 549us total 9.131ms
,E/SQLiteLog(12474): (28) failed to open "/data/data/com.sec.android.gallery3d/databases/local.db" with flag (131138) and mode_t (0) due to error (30)
,D/TimaKeyStoreProvider(12551): TimaSignature is unavailable
,D/ActivityThread(12551): Added TimaKeyStore provider
,E/SQLiteDatabase(12474): Failed to open database '/data/data/com.sec.android.gallery3d/databases/local.db'.
E/SQLiteDatabase(12474): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12474): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12474): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12474): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12474): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12474): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12474): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12474): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12474): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12474): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12474): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12474): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12474): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12474): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(12474): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteDatabase(12474): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteDatabase(12474): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteDatabase(12474): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:202)
E/SQLiteDatabase(12474): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:194)
E/SQLiteDatabase(12474): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(12474): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(12474): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12474): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12474): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12474): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12474): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12474): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12474): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12474): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12474): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper(12474): Couldn't open local.db for writing (will try read-only):
E/SQLiteOpenHelper(12474): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(12474): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(12474): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(12474): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(12474): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(12474): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(12474): 	at android.database.sqlite.SQLiteConne,ctionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(12474): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(12474): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(12474): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(12474): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(12474): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(12474): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(12474): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(12474): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteOpenHelper(12474): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteOpenHelper(12474): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteOpenHelper(12474): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:202)
E/SQLiteOpenHelper(12474): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:194)
E/SQLiteOpenHelper(12474): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(12474): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(12474): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(12474): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(12474): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(12474): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(12474): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(12474): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(12474): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(12474): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(12474): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper(12474): Opened local.db in read-only mode
D/ResourcesManager(12531): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
W/ResourcesManager(12531): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
D/WifiDisplayAdapter( 3525): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
W/ResourcesManager(12531): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12531): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12531): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12531): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(12531): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/ContactProvider(12474): getAllContactInfoList Start
D/ResourcesManager(12531): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
D/ResourcesManager(12551): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
D/WifiDisplayAdapter( 3525): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
W/ResourcesManager(12531): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12531): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12531): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/ResourcesManager(12531): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
W/ResourcesManager(12531): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager(12531): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12531): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager(12531): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12531): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12531): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12531): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/UsbHostManager( 3525): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
D/UsbHostManager( 3525): displayNotification : [02h,02h,01h]
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
D/UsbHostManager( 3525): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
D/UsbHostManager( 3525): displayNotification : [0ah,00h,00h]
D/UsbHostManager( 3525): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3525): displayNotification : [02h,0dh,00h]
D/UsbHostManager( 3525): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3525): displayNotification : [0ah,00h,01h]
D/UsbHostManager( 3525): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
D/UsbHostManager( 3525): displayNotification : [09h,00h,00h]
,D/UsbHostManager( 3525): usbDeviceRemoved : /dev/bus/usb/001/003
E/UsbHostManager( 3525): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
D/UsbSettingsManager( 3525): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
E/SharedPreferencesImpl(12474): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
E/Zygote  (12578): MountEmulatedStorage()
E/Zygote  (12578): v2
I/libpersona(12578): KNOX_SDCARD checking this for 10036
I/libpersona(12578): KNOX_SDCARD not a persona
I/SELinux (12578): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager(12531): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
I/SELinux (12578): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3525): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=12578 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
E/SELinux (12578): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3525): Killing 12245:com.sec.android.provider.badge/u0a82 (adj 13): bgCount ##31
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(12531): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
E/Zygote  (12590): MountEmulatedStorage()
E/Zygote  (12590): v2
I/libpersona(12590): KNOX_SDCARD checking this for 10052
I/libpersona(12590): KNOX_SDCARD not a persona
I/SELinux (12590): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
W/ResourcesManager(12531): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12531): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12531): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider(12578): TimaSignature is unavailable
W/ResourcesManager(12531): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
D/ActivityThread(12578): Added TimaKeyStore provider
I/SELinux (12590): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3525): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=12590 uid=10052 gids={50052, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
E/SELinux (12590): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/MtpClient(12474): onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
D/MtpClient(12474): ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
I/ActivityManager( 3525): Killing 8862:com.android.settings/1000 (adj 13): bgCount ##31
D/ResourcesManager(12531): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
W/ResourcesManager(12531): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12531): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12531): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/UsbHostManager( 3525): usbDeviceRemoved : /dev/bus/usb/001/001
E/UsbHostManager( 3525): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
D/ResourcesManager(12531): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/TimaKeyStoreProvider(12590): TimaSignature is unavailable
,D/ActivityThread(12590): Added TimaKeyStore provider
,W/ResourcesManager(12531): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12531): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12531): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12531): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12531): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(12531): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(12531): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12531): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager(12531): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager(12531): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ResourcesManager(12578): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
W/ResourcesManager(12531): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12531): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/EventHub( 3525): Removing device '/dev/input/event10' due to inotify event
,D/ResourcesManager(12531): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,D/ResourcesManager(12590): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
I/EventHub( 3525): Removing device '/dev/input/event7' due to inotify event
,D/WifiService( 3525): Client connection lost with reason: 4
,W/ResourcesManager(12590): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager(12590): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12531): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12531): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12531): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12531): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12531): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager(12590): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12590): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12590): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(12590): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/SSRM:n  ( 3525): SIOP:: AP = 290, PST = 247, CUR = 37
,D/PackageManager( 3525): [MSG] WRITE_PACKAGE_RESTRICTIONS
,E/AndroidRuntime( 3525): *** FATAL EXCEPTION IN SYSTEM PROCESS: PackageManager
E/AndroidRuntime( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'void android.util.XmlMoreAtomicFile.failWrite(java.io.FileOutputStream)' on a null object reference
E/AndroidRuntime( 3525): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1463)
E/AndroidRuntime( 3525): 	at com.android.server.pm.PackageManagerService$PackageHandler.doHandleMessage(PackageManagerService.java:1610)
E/AndroidRuntime( 3525): 	at com.android.server.pm.PackageManagerService$PackageHandler.handleMessage(PackageManagerService.java:1157)
E/AndroidRuntime( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 3525): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 3525): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,I/EventHub( 3525): Removing device '/dev/input/event8' due to inotify event
,D/ContactProvider(12474): getAllContactInfoList End
,I/syncContacts(12474): thread: 1748, sync time = 250
,D/ResourcesManager(12531): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager(12531): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager(12531): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(12531): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager(12531): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,I/EventHub( 3525): Removing device '/dev/input/event9' due to inotify event
,W/ResourcesManager(12531): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Mms/MmsApp(12590): [start]    onCreate() consume time = 0.0
,D/Mms/ArtClassLoader(12590): init before art
,D/Mms/ArtClassLoader(12590): init [DONE] art
,D/Mms/TelephonyPermission(12590): start operation mode monitor
,D/ResourcesManager(12590): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,I/EventHub( 3525): Removing device '/dev/input/event11' due to inotify event
E/SQLiteLog(12578): (28) failed to open "/data/data/com.sec.android.app.shealth/databases/base.db" with flag (131138) and mode_t (0) due to error (30)
,D/SHealthUpgrade(SHealthUpgradeUtil)(12578): isShealthServiceInstalled() : HealthService is Installed.
,W/ResourcesManager(12590): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/SHealthUpgrade(SHealthUpgradeUtil)(12578): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
,D/SHealthUpgrade(SHealthUpgradeUtil)(12578): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,E/SQLiteDatabase(12578): Failed to open database '/data/data/com.sec.android.app.shealth/databases/base.db'.
E/SQLiteDatabase(12578): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12578): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12578): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12578): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12578): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12578): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12578): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12578): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12578): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12578): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12578): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12578): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12578): 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:211)
E/SQLiteDatabase(12578): 	at android.database.sqlite.SQLiteSecureOpenHelper.getWritableDatabase(SQLiteSecureOpenHelper.java:151)
E/SQLiteDatabase(12578): 	at com.sec.android.app.shealth.framework.repository.database.DBManager.getWritableDatabase(DBManager.java:123)
E/SQLiteDatabase(12578): 	at com.sec.android.app.shealth.framework.repository.RepositoryInitializationTask.doInBackground(RepositoryInitializationTask.java:85)
E/SQLiteDatabase(12578): 	at com.sec.android.app.shealth.framework.repository.RepositoryInitializationTask.doInBackground(RepositoryInitializationTask.java:30)
E/SQLiteDatabase(12578): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase(12578): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase(12578): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase(12578): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase(12578): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase(12578): 	at java.lang.Thread.run(Thread.java:818)
,D/Mms/TelephonyPermission(12590): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission(12590): isDefault true
,D/Mms/MmsApp(12590): onCreate() com.android.mms
,D/ResourcesManager(12531): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
W/ResourcesManager(12531): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager(12531): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12531): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12531): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12531): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12531): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/EventHub( 3525): Removing device '/dev/input/event12' due to inotify event
,D/ResourcesManager(12531): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/Finsky  (12551): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/ResourcesManager(12531): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/Mms/MmsApp(12590): [start]    initCountryIso consume time = 112.249292
,D/CountryDetector( 3525): The first listener is added
I/EventHub( 3525): Removing device '/dev/input/event13' due to inotify event
,W/ResourcesManager(12531): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
D/SHealthUpgrade(SHealthUpgradeUtil)(12578): checkState()
W/ResourcesManager(12531): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/SHealthUpgrade(SHealthUpgradeUtil)(12578): checkState() : APP TYPE = Full
W/ResourcesManager(12531): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/SHealthUpgrade(SHealthUpgradeUtil)(12578): isFitnessWithGearInstalled() : Fitness with Gear isn't Installed.
,D/Mms/MmsApp(12590): [end]    initCountryIso consume time = 33.558542
,D/Mms/MmsConfig(12590): [start]    MmsConfig.init() consume time = 1.077708
,D/SHealthUpgrade(SHealthUpgradeUtil)(12578): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(12578): isShealthService1xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(12578): isShealthService1xInstalled() : HEALTH SERVICE VERSION is NOT 1.x !!!
,D/SHealthUpgrade(SHealthUpgradeUtil)(12578): isShealthService0xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(12578): isShealthService0xInstalled() : HEALTH SERVICE VERSION is NOT 0.x !!!
,D/SHealthUpgrade(SHealthUpgradeUtil)(12578): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(12578): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)(12578): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(12578): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
I/EventHub( 3525): Removing device '/dev/input/event14' due to inotify event
D/Mms/MmsConfig(12590): before partial update
,D/ResourcesManager(12531): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,E/SQLiteLog(12458): (28) failed to open "/data/data/com.google.android.apps.docs/databases/ClientFlag.db" with flag (131138) and mode_t (0) due to error (30)
,D/Mms/MmsConfig(12590): Load Resize quality : 80
,W/ResourcesManager(12531): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12531): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager(12531): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12531): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
E/SQLiteDatabase(12458): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase(12458): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12458): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12458): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12458): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12458): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12458): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12458): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12458): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12458): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12458): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12458): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12458): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12458): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12458): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(12458): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase(12458): 	at QF.provideClientFlag(ClientFlagsModule.java:71)
E/SQLiteDatabase(12458): 	at QH.a(GellyInjectorStore.java:215)
E/SQLiteDatabase(12458): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12458): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12458): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12458): 	at tQ.a(GellyInjectorStore.java:2039)
E/SQLiteDatabase(12458): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12458): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12458): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12458): 	at pG.a(GellyInjectorStore.java:478)
E/SQLiteDatabase(12458): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12458): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12458): 	at qD.a(GellyInjectorStore.java:118)
E/SQLiteDatabase(12458): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12458): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12458): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12458): 	at aEV.a(GellyInjectorStore.java:130)
E/SQLiteDatabase(12458): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12458): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12458): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12458): 	at aGH.a(GellyInjectorStore.java:227)
E/SQLiteDatabase(12458): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12458): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12458): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12458): 	at aGH.a(GellyInjectorStore.java:392)
E/SQLiteDatabase(12458): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12458): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12458): 	at aGH.a(GellyInjectorStore.java:369)
E/SQLiteDatabase(12458): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12458): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12458): 	at bsk.a(,RuntimeProvider.java:161)
E/SQLiteDatabase(12458): 	at agN.a(GellyInjectorStore.java:799)
E/SQLiteDatabase(12458): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12458): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12458): 	at pG.a(GellyInjectorStore.java:146)
E/SQLiteDatabase(12458): 	at pG.a(GellyInjectorStore.java:392)
E/SQLiteDatabase(12458): 	at bsh.a(GellyMembersInjector.java:30)
E/SQLiteDatabase(12458): 	at brQ.a(GellyInjector.java:119)
E/SQLiteDatabase(12458): 	at ajB.a(ScopedInjector.java:216)
E/SQLiteDatabase(12458): 	at com.google.android.apps.docs.DocsApplication.a(DocsApplication.java:235)
E/SQLiteDatabase(12458): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase(12458): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(12458): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(12458): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12458): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12458): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12458): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12458): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12458): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12458): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12458): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12458): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/ResourcesManager(12531): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/SQLiteOpenHelper(12458): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper(12458): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(12458): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(12458): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(12458): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(12458): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(12458): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(12458): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(12458): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(12458): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(12458): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(12458): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(12458): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(12458): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(12458): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(12458): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper(12458): 	at QF.provideClientFlag(ClientFlagsModule.java:71)
E/SQLiteOpenHelper(12458): 	at QH.a(GellyInjectorStore.java:215)
E/SQLiteOpenHelper(12458): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12458): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12458): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12458): 	at tQ.a(GellyInjectorStore.java:2039)
E/SQLiteOpenHelper(12458): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12458): 	at ,buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12458): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12458): 	at pG.a(GellyInjectorStore.java:478)
E/SQLiteOpenHelper(12458): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12458): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12458): 	at qD.a(GellyInjectorStore.java:118)
E/SQLiteOpenHelper(12458): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12458): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12458): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12458): 	at aEV.a(GellyInjectorStore.java:130)
E/SQLiteOpenHelper(12458): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12458): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12458): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12458): 	at aGH.a(GellyInjectorStore.java:227)
E/SQLiteOpenHelper(12458): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12458): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12458): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12458): 	at aGH.a(GellyInjectorStore.java:392)
E/SQLiteOpenHelper(12458): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12458): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12458): 	at aGH.a(GellyInjectorStore.java:369)
E/SQLiteOpenHelper(12458): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12458): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12458): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12458): 	at agN.a(GellyInjectorStore.java:799)
E/SQLiteOpenHelper(12458): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12458): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12458): 	at pG.a(GellyInjectorStore.java:146)
E/SQLiteOpenHelper(12458): 	at pG.a(GellyInjectorStore.java:392)
E/SQLiteOpenHelper(12458): 	at bsh.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper(12458): 	at brQ.a(GellyInjector.java:119)
E/SQLiteOpenHelper(12458): 	at ajB.a(ScopedInjector.java:216)
E/SQLiteOpenHelper(12458): 	at com.google.android.apps.docs.DocsApplication.a(DocsApplication.java:235)
E/SQLiteOpenHelper(12458): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper(12458): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(12458): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(12458): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(12458): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(12458): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(12458): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(12458): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(12458): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(12458): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(12458): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(12458): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/ResourcesManager(12531): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/SQLiteOpenHelper(12458): Opened ClientFlag.db in read-only mode
D/Mms/MmsConfig(12590):  enable multiwindow = true
D/SHealthUpgrade(SHealthUpgradeUtil)(12578): checkState() : =========== UPGRADE_STATE_APP_UPGRADE_DONE ===========
D/SHealthUpgrade(SHealthUpgradeUtil)(12578): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(12578): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
,D/SHealthUpgrade(SHealthUpgradeUtil)(12578): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
E/SQLiteLog(12458): (28) failed to open "/data/data/com.google.android.apps.docs/databases/DocList.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(12458): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase(12458): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12458): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12458): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12458): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12458): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12458): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12458): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12458): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12458): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12458): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12458): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12458): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12458): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12458): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12458): 	at aFu.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase(12458): 	at aFo.a(AbstractDatabaseInstance.java:457)
E/SQLiteDatabase(12458): 	at aFo.a(AbstractDatabaseInstance.java:453)
E/SQLiteDatabase(12458): 	at bjx.a(Suppliers.java:125)
E/SQLiteDatabase(12458): 	at aFp.run(AbstractDatabaseInstance.java:471)
E/AndroidRuntime(12458): FATAL EXCEPTION: Open database in background
E/AndroidRuntime(12458): Process: com.google.android.apps.docs, PID: 12458
E/AndroidRuntime(12458): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12458): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12458): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(12458): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(12458): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12458): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12458): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12458): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(12458): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(12458): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(12458): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(12458): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12458): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(12458): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(12458): 	at aFu.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime(12458): 	at aFo.a(AbstractDatabaseInstance.java:457)
E/AndroidRuntime(12458): 	at aFo.a(AbstractDatabaseInstance.java:453)
E/AndroidRuntime(12458): 	at bjx.a(Suppliers.java:125)
E/AndroidRuntime(12458): 	at aFp.run(AbstractDatabaseInstance.java:471)
,D/SHealthUpgrade(SHealthUpgradeUtil)(12578): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(12578): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
V/ApplicationPolicy( 3525): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.docs
,D/SHealthUpgrade(SHealthUpgradeUtil)(12578): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/ResourcesManager(12531): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,W/ResourcesManager(12531): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager(12531): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4384, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,E/SQLiteLog(12458): (28) failed to open "/data/data/com.google.android.apps.docs/databases/ClientFlag.db" with flag (131138) and mode_t (0) due to error (30)

```
