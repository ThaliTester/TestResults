#### Test 575312430087a60_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3525): online:4, current avg:60, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:104
D/BatteryService( 3525): stay LED for fully charged
D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 3525): Plugged
I/MotionRecognitionService( 3525): setPowerConnected  = true
--------- beginning of main
D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AndroidRuntime(11640): 
D/AndroidRuntime(11640): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11640): CheckJNI is OFF
D/AndroidRuntime(11640): readGMSProperty: start
D/AndroidRuntime(11640): readGMSProperty: already setted!!
D/AndroidRuntime(11640): readGMSProperty: end
D/AndroidRuntime(11640): addProductProperty: start
E/AffinityControl(11640): AffinityControl: registerfunction enter
D/AndroidRuntime(11640): Calling main entry com.android.commands.am.Am
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
E/Zygote  (11658): MountEmulatedStorage()
I/libpersona(11658): KNOX_SDCARD checking this for 10612
E/Zygote  (11658): v2
I/libpersona(11658): KNOX_SDCARD not a persona
I/SELinux (11658): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11658): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3525): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=11658 uid=10612 gids={50612, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/SELinux (11658): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(11640): Shutting down VM
D/PointerIcon( 3525): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3525): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3525): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3525): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(11658): TimaSignature is unavailable
D/ActivityThread(11658): Added TimaKeyStore provider
I/SurfaceFlinger( 2848): id=11 Removed YUIInstallC (5/8)
I/SurfaceFlinger( 2848): id=11 Removed YUIInstallC (-2/8)
D/ResourcesManager(11658): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
V/ActivityThread( 6244): updateVisibility : ActivityRecord{2da6e1cc token=android.os.BinderProxy@dbee7d9 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
I/WebViewFactory(11658): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(11658): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(11658): Loading: webviewchromium
I/LibraryLoader(11658): Time to load native libraries: 4 ms (timestamps 4971-4975)
I/LibraryLoader(11658): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(11658): Binding Chromium to main looper Looper (main, tid 1) {20b2b9cf}
I/LibraryLoader(11658): Expected native library version number "",actual native library version number ""
I/chromium(11658): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController(11658): Initializing chromium process, renderers=0
W/art     (11658): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium(11658): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium(11658): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(11658): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
W/chromium(11658): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium(11658): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     (11658): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents(11658): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine(11658): CordovaWebView is running on device made by: samsung
W/art     (11658): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11658): Attempt to remove local handle scope entry from IRT, ignoring
D/Activity(11658): performCreate Call secproduct feature valuefalse
D/Activity(11658): performCreate Call debug elastic valuetrue
D/OpenGLRenderer(11658): Render dirty regions requested: true
D/ActivityManager( 3525): post active user change for 0
D/KnoxTimeoutHandler( 3525): postActiveUserChange for user 0
W/ActivityManager( 3525): Activity pause timeout for ActivityRecord{241543e4 u0 com.test.thalitest/.MainActivity t26}
D/KnoxTimeoutHandler( 3525): handleActiveUserChange for user 0
I/SurfaceFlinger( 2848): id=14 createSurf (1x1),1 flag=404, NainActivit
D/StatusBarManagerService( 3525): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService( 3525): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 3525): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3525): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3525): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3525): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer(11658): Initialized EGL, version 1.4
I/OpenGLRenderer(11658): HWUI protection enabled for context ,  &this =0xaf545060 ,&mEglDisplay = 1 , &mEglConfig = -1279823600 
D/OpenGLRenderer(11658): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(11658): Enabling debug mode 0
D/mali_winsys(11658): new_window_surface returns 0x3000,  [1440x2560]-format:1
V/ActivityThread(11658): updateVisibility : ActivityRecord{379bb4bf token=android.os.BinderProxy@2c98a1e2 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
D/InputMethodManagerService( 3525): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ActivityManager( 3525): mDVFSHelper.release()
I/Timeline( 3525): Timeline: Activity_windows_visible id: ActivityRecord{241543e4 u0 com.test.thalitest/.MainActivity t26} time:115517
W/IInputConnectionWrapper(11658): showStatusIcon on inactive InputConnection
I/Timeline(11658): Timeline: Activity_idle id: android.os.BinderProxy@2c98a1e2 time:115529
I/chromium(11658): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11658): 
,D/JsMessageQueue(11658): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log(11658): JniHelper::setJavaVM(0xb4d5c280), pthread_self() = -1360570624
I/chromium(11658): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log(11658): Initializing JXcore engine
W/jxcore-log(11658): JXcore engine is ready
,E/auditd  ( 4629): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3525): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3525): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(11658): Starting JXcore engine
,W/jxcore-log(11658): Platform android
W/jxcore-log(11658): 
W/jxcore-log(11658): Process ARCH arm
W/jxcore-log(11658): 
,I/jxcore-log(11658): JXcore Cordova bridge is ready!
I/jxcore-log(11658): 
W/jxcore-log(11658): JXcore engine is started
,I/jxcore-log(11658): Toggling radios to true
I/jxcore-log(11658): 
,D/BluetoothAdapter(11658): enable()
,D/BluetoothAdapter(11658): enable(): BT is already enabled..!
,D/WifiService( 3525): New client listening to asynchronous messages
,I/WifiManager(11658): packageName : com.test.thalitest
,D/SecContentProvider( 3525): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3525): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3525): mCursor = null
D/WifiService( 3525): setWifiEnabled: true pid=11658, uid=10612
E/WifiService( 3525): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3525): Permission Denial: getCurrentUser() from pid=11658, uid=10612 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3525): Failed getting userId using ActivityManagerNative
W/WifiService( 3525): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=11658, uid=10612 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3525): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3525): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3525): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3525): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3525): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider( 3525): name = wifi_on
I/WifiService( 3525): disconnect: pid=11658, uid=10612
,I/wpa_supplicant( 3834): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log(11658): Radios toggled
I/jxcore-log(11658): 
,I/jxcore-log(11658): My device name is: samsung-SM-N910C
I/jxcore-log(11658): 
,I/wpa_supplicant( 3834): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3834): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 3834): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3834): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine( 3525): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 3834): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3834): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3834): Disconnected - do not scan
I/wpa_supplicant( 3834): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine( 3525): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3525): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3525): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3525): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine( 3525): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3525): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3525): do suspend true
,D/WifiP2pService( 3525): InactiveState{ what=143375 }
D/WifiP2pService( 3525): P2pEnabledState{ what=143375 }
,D/CommandListener( 2844): Clearing all IP addresses on wlan0
,E/Netd    ( 2844): ifc_reset_connections failed on iface wlan0 for address 192.168.1.124/24 (Unknown error -1)
D/StatusBar.NetworkController( 3694): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,E/WifiStateMachine( 3525): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService( 3525): updateNetworkInfo()
E/WifiConfigStore( 3525): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 3525): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3525): updateNetworkInfo()
D/ConnectivityService( 3525): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,I/WifiTrafficPoller( 3525): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
,I/Hs20UtilService( 4055): Starting #8
,I/Hs20UtilService( 4055): Message received 5007
,E/WifiStateMachine( 3525): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 3834): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3834): P2P: Current p2p state = IDLE
I/wpa_supplicant( 3834): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 3834): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3834): First Scan Start
E/WifiStateMachine( 3525): ConnectModeState: Network connection lost 
E/WifiStateMachine( 3525): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - processMessage - processMsg
E/WifiStateMachine( 3525): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine( 3525): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3525): do suspend true
,I/wpa_supplicant( 3834): Scan requested (ret=0) - scan timeout 30 seconds
,D/NearbySettings( 8888): MountReceiver.onReceive - Create HandlerThread
,D/NearbySettings( 8888): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings( 8888): MountReceiver.onReceive - Create mPrefHandler
,D/NearbySettings( 8888): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8888): DMSUtil.isNetworkConnected - flag-null, state-null
D/WifiP2pService( 3525): InactiveState{ what=143375 }
D/WifiP2pService( 3525): P2pEnabledState{ what=143375 }
I/NearbySettings( 8888): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
D/WifiService( 3525): New client listening to asynchronous messages
I/NearbySettings( 8888): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8888): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8888): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8888): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11314): NETWORK_STATE_CHANGED_ACTION
,D/CommandListener( 2844): Clearing all IP addresses on wlan0
D/ConnectivityService( 3525): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/EntConnectivity( 3525): Not allowed due to - mEnabled false
E/WifiStateMachine( 3525): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityManager.CallbackHandler( 3694): CM callback handler got msg 524292
D/WifiStateMachine( 3525): updateConfiguredNetworkExpiration - currTime: 1454092019459
D/WifiStateMachine( 3525): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
E/WifiStateMachine( 3525): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine( 3525): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityService( 3525): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3525): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 3525): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3525): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/CSLegacyTypeTracker( 3525): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 3525): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 3525): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory( 3982): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine( 3525): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3525): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent( 3525): NetworkAgent: NetworkAgent channel lost
D/ConnectivityManager.CallbackHandler( 6602): CM callback handler got msg 524292
,I/WifiTrafficPoller( 3525): evaluateTrafficStatsPolling
,E/WifiStateMachine( 3525): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3525): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine( 3525): setDetailed state send new extra info"NG700"
D/SecContentProvider2( 3525): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3525): mCursor = null
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
D/EntConnectivity( 3525): Not allowed due to - mEnabled false
D/SecContentProvider2( 3525): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3525): mCursor = null
,D/SmartBondingService( 3525): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService( 3525): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/ConnectivityService( 3525): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/SmartBondingService( 3525): getSBEnabled() enabled =false
D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
V/NetworkStats( 3525): updateIfacesLocked()
V/NetworkStats( 3525): performPollLocked(flags=0x1)
D/SmartBondingService( 3525): getSBEnabled() enabled =false
D/SmartBondingService( 3525): getSBEnabled() enabled =false
,D/Tethering( 3525): MasterInitialState.processMessage what=3
D/NetworkStatsFactory( 3525): UpdateStatsForKnox
,D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3694): updateDataNetType()
D/StatusBar.NetworkController( 3694): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3694): updateLTEICONDataNetType:0
,D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
V/NetworkStats( 3525): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
,V/NetworkStats( 3525): performPollLocked() took 3ms
D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
D/SmartBondingService( 3525): getNetworkEnabled : wifi : true mobile : false
,D/StatusBar.NetworkController( 3694): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
,I/Hs20UtilService( 4055): Starting #9
,I/Hs20UtilService( 4055): Message received 5007
,D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
,D/NearbySettings( 8888): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8888): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8888): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8888): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8888): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8888): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8888): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11314): NETWORK_STATE_CHANGED_ACTION
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/ConnectivityService( 3525): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 3525): updateDataUsageMap
,I/ApplicationPolicy( 3525): updateDataUsageMap  idList is null 
D/SmartBondingService( 3525): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3525): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3525): getSBEnabled() enabled =false
D/SmartBondingService( 3525): getSBEnabled() enabled =false
D/GpsLocationProvider( 3525): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3525): getSBEnabled() enabled =false
,D/SmartBondingService( 3525): getNetworkEnabled : wifi : true mobile : false
W/SLocation( 3525): No Active Data Connection
,I/DBG_DM  ( 6244): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/DBG_DM  ( 6244): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11769): MountEmulatedStorage()
E/Zygote  (11769): v2
I/libpersona(11769): KNOX_SDCARD checking this for 10110
I/libpersona(11769): KNOX_SDCARD not a persona
,I/SELinux (11769): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11769): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3525): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.iorg.vpn.cleanup.NetworkStateMonitor: pid=11769 uid=10110 gids={50110, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux (11769): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,V/AlarmManager( 3525): waitForAlarm result :8
,D/TimaKeyStoreProvider(11769): TimaSignature is unavailable
,D/ActivityThread(11769): Added TimaKeyStore provider
,D/ResourcesManager(11769): creating new AssetManager and set to /data/app/com.facebook.appmanager-2/base.apk
,D/ACRA    (11769): ACRA is enabled for com.facebook.appmanager, intializing...
,I/DexLibLoader(11769): not using cross-dex optimization: ART in use
,I/art     (11769): Thread[1,tid=11769,WaitingForJniOnLoad,Thread*=0xb4d08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/app/com.facebook.appmanager-2/lib/arm/libfbjni.so"
,V/DexLibLoader(11769): about to lock: /data/data/com.facebook.appmanager/mdex_lock
,V/DexLibLoader(11769): locking /data/data/com.facebook.appmanager/mdex_lock took 1 ms
V/DexLibLoader(11769): Secondary program dex metadata: classes2.dex 29f80981f469a774a4884b3db2df17e0be227159 secondary.dex01.Canary
D/DexLibLoader(11769): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex" is valid
,D/DexLibLoader(11769): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex_opt" is valid
,W/art     (11769): Attempt to remove local handle scope entry from IRT, ignoring
D/DexLibLoader(11769): loading pre-built fallback odex files
,V/MultiDexClassLoader(11769): installing MultiDexClassLoader before application classloader
,D/DexLibLoader(11769): released odex store lock
D/DexLibLoader(11769): DexLibLoader.loadAll took 15 ms
,W/ca      (11769): Verify
,W/LightSharedPreferencesImpl(11769): Failed to load preference file from Disk!
W/LightSharedPreferencesImpl(11769): java.io.FileNotFoundException: /data/data/com.facebook.appmanager/app_light_prefs/com.facebook.appmanager/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11769): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/LightSharedPreferencesImpl(11769): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/LightSharedPreferencesImpl(11769): 	at com.facebook.crudolib.b.k.a(LightSharedPreferencesStorage.java:56)
W/LightSharedPreferencesImpl(11769): 	at com.facebook.crudolib.b.g.run(LightSharedPreferencesImpl.java:61)
W/LightSharedPreferencesImpl(11769): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/LightSharedPreferencesImpl(11769): 	at com.facebook.common.executors.dj.run(WrappingExecutorService.java:77)
W/LightSharedPreferencesImpl(11769): 	at com.facebook.common.executors.u.run(DefaultConstrainedListeningExecutorService.java:327)
W/LightSharedPreferencesImpl(11769): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/LightSharedPreferencesImpl(11769): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/LightSharedPreferencesImpl(11769): 	at com.facebook.common.executors.cc.run(NamedThreadFactory.java:42)
W/LightSharedPreferencesImpl(11769): 	at java.lang.Thread.run(Thread.java:818)
W/LightSharedPreferencesImpl(11769): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11769): 	at libcore.io.Posix.open(Native Method)
W/LightSharedPreferencesImpl(11769): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/LightSharedPreferencesImpl(11769): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/LightSharedPreferencesImpl(11769): 	... 10 more
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11794): MountEmulatedStorage()
E/Zygote  (11794): v2
I/libpersona(11794): KNOX_SDCARD checking this for 1000
I/libpersona(11794): KNOX_SDCARD not a persona
,I/SELinux (11794): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11794): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11794): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3525): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=11794 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3525): Killing 10903:com.sec.android.app.myfiles/u0a53 (adj 15): bgCount ##31
W/appmanager(:<default>):b(11769): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/appmanager(:<default>):b(11769): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/TimaKeyStoreProvider(11794): TimaSignature is unavailable
,D/ActivityThread(11794): Added TimaKeyStore provider
,W/appmanager(:<default>):QuickExperimentControllerImpl(11769): Exposure of experiment com.facebook.common.network.l@28e8abbd occurred when no user was logged in
,D/ResourcesManager(11794): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,W/BroadcastQueue( 3525): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{ec6d5c8 u0 ReceiverList{4b0966b 11769 com.facebook.appmanager/10110/u0 remote:1d8a37ba}}
W/BroadcastQueue( 3525): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{ec6d5c8 u0 ReceiverList{4b0966b 11769 com.facebook.appmanager/10110/u0 remote:1d8a37ba}}
,I/PCWCLIENTTRACE_LOG(11794): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(11794): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(11794): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil(11794): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11794): sales region : global
I/PCWCLIENTTRACE_PushUtil(11794): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11794): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
I/PCWCLIENTTRACE_SYSTEMReceiver(11794): noConnectivity : true
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11826): MountEmulatedStorage()
E/Zygote  (11826): v2
I/libpersona(11826): KNOX_SDCARD checking this for 10135
I/libpersona(11826): KNOX_SDCARD not a persona
,I/SELinux (11826): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11826): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11826): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3525): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=11826 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3525): Killing 10921:com.policydm/1000 (adj 15): bgCount ##31
E/lowmemorykiller( 2826): Error writing /proc/10921/oom_score_adj; errno=22
,D/TimaKeyStoreProvider(11826): TimaSignature is unavailable
,D/ActivityThread(11826): Added TimaKeyStore provider
,W/BroadcastQueue( 3525): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{1ca9300c u0 ReceiverList{3afe9f3f 11769 com.facebook.appmanager/10110/u0 remote:25a24f5e}}
,D/ResourcesManager(11826): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/MusicStore(11826): Database version: 104
,D/ResourcesManager(11826): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11826): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11826): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (11826): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(11826): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  (11826): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@29a1d133: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(11826): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(11826): GMSCore installation verified
,I/ConfigStore(11826): Config Database version: 1
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11826): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/ContextImpl(11826): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
W/ContextImpl(11826): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,I/wpa_supplicant( 3834): nl80211: Received scan results (2 BSSes)
I/wpa_supplicant( 3834): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 3834): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3834): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 3834): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3525): [1,454,092,020,514 ms] noteScanEnd no scan source
,E/WifiStateMachine( 3525): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@62f5216 sup_state=SCANNING debouncing=false
,E/WifiStateMachine( 3525): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3525): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3525): setDetailed state send new extra info
,D/SecContentProvider2( 3525): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3525): mCursor = null
,I/art     ( 3525): Explicit concurrent mark sweep GC freed 63885(3MB) AllocSpace objects, 11(176KB) LOS objects, 24% free, 49MB/65MB, paused 1.221ms total 81.423ms
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11769): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11769): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,D/WifiDisplayAdapter( 3525): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3525): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3525): getStreamVolume 3 index 0
,I/MediaRouter(11826): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,W/appmanager(:<default>):QuickExperimentControllerImpl(11769): Exposure of experiment com.facebook.imagepipeline.a.g@24dc7a00 occurred when no user was logged in
,W/appmanager(:<default>):QuickExperimentControllerImpl(11769): Exposure of experiment com.facebook.imagepipeline.a.d@1283a8f5 occurred when no user was logged in
,E/Zygote  (11852): MountEmulatedStorage()
I/libpersona(11852): KNOX_SDCARD checking this for 10002
E/Zygote  (11852): v2
I/libpersona(11852): KNOX_SDCARD not a persona
I/SELinux (11852): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11852): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11852): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/wpa_supplicant( 3834): wlan0: State: ASSOCIATING -> ASSOCIATED
I/ActivityManager( 3525): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=11852 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/wpa_supplicant( 3834): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 3834): Associated with C0.AA.48
,E/WifiStateMachine( 3525): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
,E/WifiStateMachine( 3525): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3525): setDetailed state send new extra info"NG700"
,I/art     (11769): Explicit concurrent mark sweep GC freed 43979(2MB) AllocSpace objects, 6(96KB) LOS objects, 22% free, 27MB/35MB, paused 600us total 26.268ms
W/appmanager(:<default>):m(11769): No feature status reporters found; is this dead code?
,D/SecContentProvider2( 3525): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3525): mCursor = null
,D/WifiDisplayAdapter( 3525): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/TimaKeyStoreProvider(11852): TimaSignature is unavailable
,D/ActivityThread(11852): Added TimaKeyStore provider
,I/wpa_supplicant( 3834): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 3834): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3525): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
,E/WifiStateMachine( 3525): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
I/NetworkMonitor(11826): type=WIFI subType= reason=null isConnected=false
,D/SecContentProvider2( 3525): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3525): mCursor = null
,I/wpa_supplicant( 3834): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 3834): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 3834): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/ActivityManager( 3525): Killing 10936:com.sec.android.provider.badge/u0a82 (adj 15): bgCount ##31
,E/WifiStateMachine( 3525): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3525): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,I/wpa_supplicant( 3834): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3834): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 3834): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3834): Blacklist: Clear (temp) 
I/wpa_supplicant( 3834): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3525): Network connection established
,D/WifiNative-HAL( 3525): callSECApiVoid - ID [50]
E/WifiStateMachine( 3525): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine( 3525): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ResourcesManager(11852): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,D/ConnectivityService( 3525): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine( 3525): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3525): L2ConnectedState "NG700" nid=0
E/WifiConfigStore( 3525): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 3525): hsengiv:checkWhatTypeOfNetwork and the value is false
,E/ConnectivityService( 3525): updateNetworkInfo()
D/ConnectivityService( 3525): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3525): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine( 3525): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3525): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3525): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener( 2844): Setting iface cfg
,E/WifiStateMachine( 3525): Start Dhcp Watchdog 2
,D/SecContentProvider2( 3525): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3525): mCursor = null
,E/WifiStateMachine( 3525): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3525): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/ActivityManager( 3525): Killing 10965:com.sec.spp.push/u0a39 (adj 15): bgCount ##31
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11876): MountEmulatedStorage()
E/Zygote  (11876): v2
I/libpersona(11876): KNOX_SDCARD checking this for 1000
I/libpersona(11876): KNOX_SDCARD not a persona
,I/SELinux (11876): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11876): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11876): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3525): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=11876 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11876): TimaSignature is unavailable
,D/ActivityThread(11876): Added TimaKeyStore provider
,D/ResourcesManager(11876): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT(11876): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,E/WifiStateMachine( 3525): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3525): do suspend false
,D/SecContentProvider2( 3525): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3525): mCursor = null
,D/WifiP2pService( 3525): InactiveState{ what=143375 }
D/WifiP2pService( 3525): P2pEnabledState{ what=143375 }
,I/DIAGMON_AGENT(11876): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT(11876): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT(11876): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(11876): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11892): MountEmulatedStorage()
I/libpersona(11892): KNOX_SDCARD checking this for 10012
E/Zygote  (11892): v2
I/libpersona(11892): KNOX_SDCARD not a persona
I/SELinux (11892): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11892): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11892): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=11892 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11892): TimaSignature is unavailable
,D/ActivityThread(11892): Added TimaKeyStore provider
,D/ResourcesManager(11892): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager( 3525): Killing 10957:com.sec.android.app.soundalive/u0a59 (adj 15): bgCount ##31
,E/lowmemorykiller( 2826): Error writing /proc/10957/oom_score_adj; errno=22
,I/FOTA_Client(11892): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(11892): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(11892): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11908): MountEmulatedStorage()
I/libpersona(11908): KNOX_SDCARD checking this for 10021
E/Zygote  (11908): v2
I/libpersona(11908): KNOX_SDCARD not a persona
I/SELinux (11908): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11908): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11908): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3525): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=11908 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 3525): Killing 10994:com.wsomacp/u0a28 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(11908): TimaSignature is unavailable
,D/ActivityThread(11908): Added TimaKeyStore provider
,D/ResourcesManager(11908): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.521: (11908): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jan 29 19:27:00 GMT+01:00 2016
,I/KLMS-2.4.521: (11908): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (11908): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11908): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (11908): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (11908): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (11908): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,E/dhcpcd  (11924): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (11924): version 5.5.6 starting
,I/KLMS-2.4.521: (11908): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,E/dhcpcd  (11924): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/KLMS-2.4.521: (11908): StateImplV2(): networkChangeListener().END
,E/Zygote  (11926): MountEmulatedStorage()
E/Zygote  (11926): v2
I/libpersona(11926): KNOX_SDCARD checking this for 10038
I/libpersona(11926): KNOX_SDCARD not a persona
,I/SELinux (11926): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11926): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11926): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=11926 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/KLMS-2.4.521: (11908): KLMSIntentService(): onDestroy()
,I/ActivityManager( 3525): Killing 10787:com.google.android.apps.docs/u0a101 (adj 15): bgCount ##31
,E/lowmemorykiller( 2826): Error writing /proc/10787/oom_score_adj; errno=22
,D/TimaKeyStoreProvider(11926): TimaSignature is unavailable
,D/ActivityThread(11926): Added TimaKeyStore provider
,D/ResourcesManager(11926): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/dhcpcd  (11924): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (11924): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (11924): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  (11924): bssid match
I/dhcpcd  (11924): wlan0: rebinding lease of 192.168.1.124
,I/SO_AGENT(11926): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11946): MountEmulatedStorage()
E/Zygote  (11946): v2
I/libpersona(11946): KNOX_SDCARD checking this for 1000
I/libpersona(11946): KNOX_SDCARD not a persona
,I/SELinux (11946): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11946): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11946): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3525): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=11946 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3525): Killing 11029:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##31
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 8742(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 283us total 10.101ms
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 266us total 8.012ms
,D/TimaKeyStoreProvider(11946): TimaSignature is unavailable
D/ActivityThread(11946): Added TimaKeyStore provider
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 603us total 8.689ms
,D/ResourcesManager(11946): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11966): MountEmulatedStorage()
I/libpersona(11966): KNOX_SDCARD checking this for 10039
E/Zygote  (11966): v2
I/libpersona(11966): KNOX_SDCARD not a persona
,I/SELinux (11966): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11966): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3525): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=11966 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (11966): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Killing 11010:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(11966): TimaSignature is unavailable
,D/ActivityThread(11966): Added TimaKeyStore provider
,D/ResourcesManager(11966): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService(11966): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(11966): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService(11966): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,D/SPPClientService(11966): PushLog.txt file is not deleted.
D/SPPClientService(11966): PushLog.txt file is not deleted.
D/SPPClientService(11966): ============PushLog. stop!
,I/SA      (11104): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11104): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      (11104): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      (11104): [SLFUCHKMGR] constructor called
E/SPPClientService(11966): [[SystemStateMonitorService]] No Active Internet
I/SA      (11104): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11104): [OR] == isSIMCardReady false ==
,I/SA      (11104): [SCU] == networkStateCheck == false
I/SA      (11104): [OR] onReceive END
,V/DownloadManager( 3716): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11986): MountEmulatedStorage()
E/Zygote  (11986): v2
I/libpersona(11986): KNOX_SDCARD checking this for 10067
I/libpersona(11986): KNOX_SDCARD not a persona
,I/SELinux (11986): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11986): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11986): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=11986 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager( 3525): Killing 11084:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(11986): TimaSignature is unavailable
,D/ActivityThread(11986): Added TimaKeyStore provider
,D/ResourcesManager(11986): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/sCloudBackupApp(11986): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(11986): Other Intent
,I/ActivityManager( 3525): Killing 11049:com.sec.android.automotive.drivelink/u0a102 (adj 13): bgCount ##31
,D/accuweather( 5202): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3797): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,D/accuweather( 5202): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5202): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5202): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
,D/accuweather( 5202): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5202): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5202): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12002): MountEmulatedStorage()
E/Zygote  (12002): v2
I/libpersona(12002): KNOX_SDCARD checking this for 1000
I/libpersona(12002): KNOX_SDCARD not a persona
,I/SELinux (12002): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12002): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12002): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=12002 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12002): TimaSignature is unavailable
,D/ActivityThread(12002): Added TimaKeyStore provider
,D/ResourcesManager(12002): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(12002): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro(12002): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro(12002): premStatus:2
,I/KnoxUsageLogPro(12002): isEulaShown : false
I/KnoxUsageLogPro(12002): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12017): MountEmulatedStorage()
E/Zygote  (12017): v2
I/libpersona(12017): KNOX_SDCARD checking this for 10090
I/libpersona(12017): KNOX_SDCARD not a persona
,I/SELinux (12017): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12017): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12017): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=12017 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3525): Killing 11176:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12017): TimaSignature is unavailable
,D/ActivityThread(12017): Added TimaKeyStore provider
,D/ResourcesManager(12017): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12033): MountEmulatedStorage()
I/libpersona(12033): KNOX_SDCARD checking this for 10127
E/Zygote  (12033): v2
I/libpersona(12033): KNOX_SDCARD not a persona
,I/SELinux (12033): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12033): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12033): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=12033 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3525): Killing 11160:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12033): TimaSignature is unavailable
,D/ActivityThread(12033): Added TimaKeyStore provider
,D/ResourcesManager(12033): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,D/KeyguardWallpaperUpdator(12033): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12033): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12033): stopCheckCategoryVersion
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12049): MountEmulatedStorage()
E/Zygote  (12049): v2
I/libpersona(12049): KNOX_SDCARD checking this for 10136
I/libpersona(12049): KNOX_SDCARD not a persona
,I/SELinux (12049): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12049): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12049): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=12049 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3525): Killing 11193:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12049): TimaSignature is unavailable
,D/ActivityThread(12049): Added TimaKeyStore provider
,D/ResourcesManager(12049): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12049): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
W/ContextImpl(12049): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12049): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12049): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory(12049): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(12049): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(12049): Loading: webviewchromium
,I/LibraryLoader(12049): Time to load native libraries: 2 ms (timestamps 9283-9285)
I/LibraryLoader(12049): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(12049): Binding Chromium to main looper Looper (main, tid 1) {321e4d8f}
,I/LibraryLoader(12049): Expected native library version number "",actual native library version number ""
,I/chromium(12049): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(12049): Initializing chromium process, renderers=0
,W/art     (12049): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(12049): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(12049): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium(12049): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
W/AudioManagerAndroid(12049): Requires BLUETOOTH permission
,I/NSApplication(12049): Starting up...
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12117): MountEmulatedStorage()
I/libpersona(12117): KNOX_SDCARD checking this for 10150
E/Zygote  (12117): v2
I/libpersona(12117): KNOX_SDCARD not a persona
I/SELinux (12117): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12117): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12117): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=12117 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager( 3525): Killing 11211:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##31
,E/lowmemorykiller( 2826): Error writing /proc/11211/oom_score_adj; errno=22
,D/TimaKeyStoreProvider(12117): TimaSignature is unavailable
,D/ActivityThread(12117): Added TimaKeyStore provider
,D/ResourcesManager(12117): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(12117): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(12117): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12117): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect(12117): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12117): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect(12117): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12132): MountEmulatedStorage()
E/Zygote  (12132): v2
I/libpersona(12132): KNOX_SDCARD checking this for 10178
I/libpersona(12132): KNOX_SDCARD not a persona
,I/SELinux (12132): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12132): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12132): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3525): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=12132 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager( 3525): Killing 11228:com.samsung.helphub/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12132): TimaSignature is unavailable
,D/ActivityThread(12132): Added TimaKeyStore provider
,D/ResourcesManager(12132): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(12132): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager(12132): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12132): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12132): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12132): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12132): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService( 3525): exchangeData() failure , invalid userId
,D/RCPManagerService( 3525): exchangeData() failure , invalid userId
,D/RCPManagerService( 3525): exchangeData() failure , invalid userId
,D/RCPManagerService( 3525): exchangeData() failure , invalid userId
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12155): MountEmulatedStorage()
I/libpersona(12155): KNOX_SDCARD checking this for 10082
E/Zygote  (12155): v2
I/libpersona(12155): KNOX_SDCARD not a persona
,I/SELinux (12155): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12155): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12155): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/RCPManagerService( 3525): exchangeData() failure , invalid userId
,I/ActivityManager( 3525): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=12155 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,D/RCPManagerService( 3525): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider(12155): TimaSignature is unavailable
,D/ActivityThread(12155): Added TimaKeyStore provider
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12171): MountEmulatedStorage()
I/libpersona(12171): KNOX_SDCARD checking this for 1000
E/Zygote  (12171): v2
I/libpersona(12171): KNOX_SDCARD not a persona
I/SELinux (12171): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12171): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12171): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=12171 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3525): Killing 11337:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##31
,I/ActivityManager( 3525): Killing 11354:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12171): TimaSignature is unavailable
,D/ActivityThread(12171): Added TimaKeyStore provider
,D/ResourcesManager(12155): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/ResourcesManager(12171): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/BadgeProvider(12155): onCreate
D/BadgeProvider(12155): DatabaseHelper
,I/ActivityManager( 3525): Killing 11373:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##31
,D/BadgeProvider(12155): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider(12155): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12155): sendNotify, [notify] : null
D/BadgeProvider(12155): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12155): update, [BadgeCount] : badgecount=0
D/BadgeProvider(12155): update, [UpdateCount] : 1
,D/Launcher.Model( 4004): reloadBadges entered.
,I/iu.Environment( 6602): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 6602): num queued entries: 0
,I/iu.UploadsManager( 6602): num updated entries: 0
I/iu.SyncManager( 6602): NEXT; no task
,W/ActivityManager( 3525): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12190): MountEmulatedStorage()
E/Zygote  (12190): v2
I/libpersona(12190): KNOX_SDCARD checking this for 10013
I/libpersona(12190): KNOX_SDCARD not a persona
,I/SELinux (12190): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12190): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12190): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3525): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=12190 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 8764(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 586us total 10.508ms
,D/TimaKeyStoreProvider(12190): TimaSignature is unavailable
,D/ActivityThread(12190): Added TimaKeyStore provider
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 376us total 8.709ms
,D/ResourcesManager(12190): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 259us total 8.319ms
,I/ActivityManager( 3525): Killing 11410:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
,I/Hs20UtilService( 4055): Starting #10
,I/Hs20UtilService( 4055): Message received 5007
,D/NearbySettings( 8888): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8888): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8888): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8888): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8888): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8888): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8888): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11314): NETWORK_STATE_CHANGED_ACTION
,I/dhcpcd  (11924): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
,I/dhcpcd  (11924): wlan0: leased 192.168.1.124 for 86400 seconds
,E/WifiStateMachine( 3525): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3525): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine( 3525): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine( 3525): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  ( 3525): do suspend true
,D/WifiP2pService( 3525): InactiveState{ what=143375 }
D/WifiP2pService( 3525): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 3525): WifiStateMachine DHCP successful
,E/WifiStateMachine( 3525): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3525): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine( 3525): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3525): Not connected state, yet.
E/WifiStateMachine( 3525): VerifyingLinkState enter
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiStateMachine( 3525): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine( 3525): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3525): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3525): callSECApiInt - ID [210]
E/WifiStateMachine( 3525): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService( 3525): updateNetworkInfo()
,D/ConnectivityService( 3525): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 3525): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 3525): updateDnsLinkProperty: enter
D/WifiWatchdogStateMachine.DnsPinger( 3525): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 3525): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 3525): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3525): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,I/Hs20UtilService( 4055): Starting #11
,I/Hs20UtilService( 4055): Message received 5007
,D/NearbySettings( 8888): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8888): MountReceiver.onReceive - Keep current state
,E/WifiStateMachine( 3525): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine( 3525): Now, connected state.
E/WifiStateMachine( 3525): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SignOutReceiver(11314): NETWORK_STATE_CHANGED_ACTION
,E/WifiStateMachine( 3525): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/WifiTrafficPoller( 3525): evaluateTrafficStatsPolling
D/ConnectivityService( 3525): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService( 3525): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
D/ConnectivityService( 3525): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService( 3525): Unexpected mtu value: 0, wlan0
,V/        ( 2844): QcRouteController
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3525): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/WifiTrafficPoller( 3525): evaluateTrafficStatsPolling
D/WifiNative-HAL( 3525): callSECApiVoid - ID [212]
,E/WifiStateMachine( 3525): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/StatusBar.NetworkController( 3694): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
I/WifiStateMachine( 3525): REQUEST_POWER_SAVE_ON
,V/        ( 2844): QcRouteController
,I/jxcore-log(11658): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log(11658): 
,I/Hs20UtilService( 4055): Starting #12
,I/Hs20UtilService( 4055): Message received 5007
,D/NearbySettings( 8888): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8888): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8888): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8888): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8888): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8888): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 8888): MountReceiver.mPrefHandler - 7002
,V/        ( 2844): QcRouteController
,V/        ( 2844): QcRouteController
,I/SignOutReceiver(11314): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2844): QcRouteController
,I/Hs20UtilService( 4055): Starting #13
,I/Hs20UtilService( 4055): Message received 5007
,D/NearbySettings( 8888): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 8888): MountReceiver.onReceive - Keep current state
,V/        ( 2844): QcRouteController
,V/        ( 2844): QcRouteController
,I/WifiStateMachine( 3525): callSECApi what=220
D/WifiStateMachine( 3525): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,V/        ( 2844): QcRouteController
,I/SignOutReceiver(11314): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService( 3525): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService( 3525): LTETest block dns file not exists
,D/ConnectivityService( 3525): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 3525): updateNetworkInfo()
E/ConnectivityService( 3525): updateNetworkInfo()
D/ConnectivityService( 3525): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 3525): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3525): rematching NetworkAgentInfo [WIFI () - 503]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3525): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3525): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3525): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3525): Checking http://clients3.google.com/generate_204 on "NG700"
,I/System.out( 3525): (HTTPLog)-Static: isSBSettingEnabled false
D/ConnectivityService( 3525):    accepting network in place of null
,D/EnterpriseController( 2844): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2844): getNetworkForDns: using netid 503 for uid 1000
,D/TelephonyNetworkFactory( 3982): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/CSLegacyTypeTracker( 3525): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 3525): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 3525): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService( 3525): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3525): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3525): Validated
,D/Tethering( 3525): MasterInitialState.processMessage what=3
D/EntConnectivity( 3525): Not allowed due to - mEnabled false
D/ConnectivityService( 3525): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/SmartBondingService( 3525): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService( 3525): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/ConnectivityManager.CallbackHandler( 3694): CM callback handler got msg 524290
D/SmartBondingService( 3525): getSBEnabled() enabled =false
D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
D/ConnectivityService( 3525): Validated NetworkAgentInfo [WIFI () - 503]
D/SmartBondingService( 3525): getSBEnabled() enabled =false
D/ConnectivityManager.CallbackHandler( 6602): CM callback handler got msg 524290
D/ConnectivityService( 3525): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkStatsFactory( 3525): UpdateStatsForKnox
D/ConnectivityService( 3525): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 3525): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/SmartBondingService( 3525): getSBEnabled() enabled =false
V/NetworkStats( 3525): updateIfacesLocked()
V/NetworkStats( 3525): performPollLocked(flags=0x1)
D/ConnectivityService( 3525): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 3694): CM callback handler got msg 524290
D/SmartBondingService( 3525): getNetworkEnabled : wifi : true mobile : false
,D/ConnectivityManager.CallbackHandler( 6602): CM callback handler got msg 524290
,D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
,I/SurfaceFlinger( 2848): id=15 createSurf (1x1),1 flag=4, Uoast
D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
,V/NetworkStats( 3525): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
V/NetworkStats( 3525): performPollLocked() took 7ms
D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
,D/PowerManagerService( 3525): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3525
,D/mali_winsys( 3694): new_window_surface returns 0x3000,  [1120x201]-format:1
,D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3694): updateDataNetType()
D/StatusBar.NetworkController( 3694): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3694): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3694): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 3694): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3694): updateDataNetType()
D/StatusBar.NetworkController( 3694): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3694): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3694): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3694): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,I/jxcore-log(11658): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log(11658): 
,I/jxcore-log(11658): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log(11658): 
,I/jxcore-log(11658): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log(11658): 
,I/jxcore-log(11658): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log(11658): 
,D/ConnectivityService( 3525): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3525): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3525): SmartBondingReceiver: wifi is connected
D/SmartBondingService( 3525): SmartBondingReceiver: wifi ap is not changed
D/SmartBondingService( 3525): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3525): getSBEnabled() enabled =false
D/SmartBondingService( 3525): getSBEnabled() enabled =false
D/SmartBondingService( 3525): getSBEnabled() enabled =false
,D/SmartBondingService( 3525): getNetworkEnabled : wifi : true mobile : false
,I/DBG_DM  ( 6244): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 6244): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/GpsLocationProvider( 3525): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/ResourceType( 5346): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5346): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,I/NetworkMonitor(11826): type=WIFI subType= reason=null isConnected=true
,I/PCWCLIENTTRACE_PushUtil(11794): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11794): sales region : global
I/PCWCLIENTTRACE_PushUtil(11794): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11794): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/SecContentProvider2( 3525): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3525): mCursor = null
,I/DIAGMON_AGENT(11876): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(11876): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/FOTA_Client(11892): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(11892): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(11892): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.521: (11908): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jan 29 19:27:03 GMT+01:00 2016
,I/KLMS-2.4.521: (11908): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (11908): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11908): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (11908): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/SO_AGENT(11926): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,I/KLMS-2.4.521: (11908): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (11908): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (11908): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.521: (11908): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.521: (11908): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.521: (11908): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.4.521: (11908): StateImplV2(): networkChangeListener().END
,E/SPPClientService(11966): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/KLMS-2.4.521: (11908): KLMSIntentService(): onDestroy()
,I/SA      (11104): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11104): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (11104): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (11104): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11104): [OR] == isSIMCardReady false ==
,I/SA      (11104): [SCU] == networkStateCheck == true
I/SA      (11104): [DM] getCountryCodeFromCSC : PL
I/SA      (11104): isChinaCountryCode : false
I/SA      (11104): [SCU] is ChinestModel Data Restricted   : false
I/SA      (11104): [OR] == networkStateCheck true ==
,I/SA      (11104): [OR] GetMyCountryZoneTask
I/SA      (11104): [OR] onReceive END
,I/SA      (11104): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 3716): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      (11104): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (11104): [SSP] query invoked
,I/SCloudBackupReceiver(11986): Other Intent
,D/accuweather( 5202): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/SA      (11104): [TPMU] GetMccFromDB : null
,I/SA      (11104): [SCU] getMccFromPreferece mcc = 260
I/SA      (11104): [TPM] isNoProxy(default) : true
,D/daemonapp( 3797): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,D/accuweather( 5202): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5202): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5202): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5202): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5202): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5202): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro(12002): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro(12002): premStatus:2
,I/KnoxUsageLogPro(12002): isEulaShown : false
I/KnoxUsageLogPro(12002): KnoxUsageReceiver onReceive : not Processible, just return
,D/KeyguardWallpaperUpdator(12033): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12033): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12033): stopCheckCategoryVersion
,D/QuickConnect(12117): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12117): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect(12117): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 3525): exchangeData() failure , invalid userId
,D/RCPManagerService( 3525): exchangeData() failure , invalid userId
,I/iu.Environment( 6602): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 6602): num queued entries: 0
,I/iu.UploadsManager( 6602): num updated entries: 0
,I/iu.SyncManager( 6602): NEXT; no task
,D/WaitQueueForNetworkActivate(12190): notifyNetworkActivated
,D/EnterpriseController( 2844): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2844): getNetworkForDns: using netid 503 for uid 10014
,W/ContextImpl(12190): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3525): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/hcjo    (12190): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12190): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12190): exit::IDLE
D/InitializeManagerStateMachine(12190): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12190): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12190): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12190): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12190): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12190): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12190): entry::SUCCESS
D/hcjo    (12190): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    (12190): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12190): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine(12190): exit::SUCCESS
D/InitializeManagerStateMachine(12190): entry::IDLE
,I/SA      (11104): [RC New] Execute method=[GET] start
,I/SA      (11104): [RC New] Security=[true]
,I/System.out(11104): Thread-1525(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out(11104): Thread-1525(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11104): Thread-1525(ApacheHTTPLog):isShipBuild true
I/System.out(11104): Thread-1525(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2844): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2844): getNetworkForDns: using netid 503 for uid 10045
,D/ConnectivityService( 3525): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/SA      (11104): [RC New] [v2liruge] api execute + 598
I/SA      (11104): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out(11104): AsyncTask #1 calls detatch()
,I/SA      (11104): [TPMU] getNetworkMcc : 
,I/SA      (11104): [SCU] saveMccToPreferece Start
I/SA      (11104): [SCU] RegionMCC : 260
I/SA      (11104): [SSP] query invoked
,I/art     ( 3525): Explicit concurrent mark sweep GC freed 52124(2MB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 48MB/64MB, paused 1.228ms total 73.861ms
,I/SA      (11104): [TPMU] GetMccFromDB : null
I/SA      (11104): [SCU] getMccFromPreferece mcc = 260
I/SA      (11104): [SCU] saveMccToPreferece End
,I/SA      (11104): [RC New] executeRequest [v2liruge] end. 696
I/SA      (11104): [RC New] Execute end
I/SA      (11104): [OR] GetMyCountryZoneTask mcc = 260
I/SA      (11104): [OR] GetMyCountryZoneTask Success
,I/dhcpcd  (11924): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (11924): wlan0: sendmsg: Cannot assign requested address
,D/WearableService( 4667): callingUid 10014, callindPid: 4667
,D/ResourcesManager(11826): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11826): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11826): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory(11826): Using the GMSCore's GoogleHttpClient
,I/MusicLeanback(11826): Conditions not met for autocaching.
I/MusicLeanback(11826): Stop autocaching.
,D/WearableClient(11826): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11826): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11826): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11826): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(11826): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils(11826): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/ActivityThread(11826): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@12a3036b that was originally bound here
E/ActivityThread(11826): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@12a3036b that was originally bound here
E/ActivityThread(11826): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(11826): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(11826): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(11826): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(11826): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(11826): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(11826): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11826): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11826): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11826): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(11826): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(11826): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(11826): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(11826): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(11826): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(11826): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(11826): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(11826): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(11826): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(11826): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(11826): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(11826): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(11826): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(11826): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(11826): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/WifiStateMachine( 3525): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine( 3525): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/jxcore-log(11658): Test app app.js loaded
I/jxcore-log(11658): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11658): setDiscoveryMode: Mode set to BLE
,I/jxcore-log(11658): BLE advertisement is supported
I/jxcore-log(11658): 
,I/chromium(11658): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/SurfaceFlinger( 2848): id=15 Removed Uoast (8/9)
,I/SurfaceFlinger( 2848): id=15 Removed Uoast (-2/9)
,D/PowerManagerService( 3525): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3525) eventTime = 123634
,D/PowerManagerService( 3525): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3525 (0x0)
D/PowerManagerService( 3525): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3525, ws=WorkSource{10060}) (elapsedTime=3470)
,E/WifiStateMachine( 3525): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3525): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityService( 3525): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
V/        ( 2844): QcRouteController
,D/SmartBondingService( 3525): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
D/SmartBondingService( 3525): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3525): getSBEnabled() enabled =false
D/SmartBondingService( 3525): getSBEnabled() enabled =false
D/SmartBondingService( 3525): getSBEnabled() enabled =false
,V/        ( 2844): QcRouteController
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
,D/ConnectivityManager.CallbackHandler( 3694): CM callback handler got msg 524295
,D/ConnectivityService( 3525): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 6602): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 3694): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 6602): CM callback handler got msg 524295
,V/AlarmManager( 3525): waitForAlarm result :4
,V/AlarmManager( 3525): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 3525): <AppSync3 Whitelist>
,V/AlarmManager( 3525): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3694): handleTimeUpdate
,D/KeyguardEffectViewController( 3694): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3694): *** don't update sliding image ***
,D/SSRM:n  ( 3525): SIOP:: AP = 310, PST = 295, CUR = 60
D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:-267, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:133
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/PowerManagerService( 3525): [PWL] Off : 30s ago
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/GAV4    (12049): Thread[GAThread,5,main]: No campaign data found.
,D/PackageManager( 3525): [MSG] WRITE_PACKAGE_RESTRICTIONS,
,I/PCWCLIENTTRACE_SYSTEMReceiver(11794): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil(11794): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE(11794): ================================================
,I/CSTORAGE(11794):  CSTORAGE_SKM_LIB v1.0.15
I/CSTORAGE(11794): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI(11794): [GetString-S]
E/art     (11794): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI(11794): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI(11794): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil(11794): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil(11794): sales region : global
I/PCWCLIENTTRACE_PushUtil(11794): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler(11794): [ensureRegistration] - No Samsung account
,I/dhcpcd  (11924): wlan0: sending IPv6 Router Solicitation
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ProcessCpuTracker( 3525): Skipping unknown process pid 12321
,W/ProcessCpuTracker( 3525): Skipping unknown process pid 12325
,I/dhcpcd  (11924): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  (11924): wlan0: no IPv6 Routers available
,D/PreloadUpdateManagerStateMachine(12190): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(12190): exit::IDLE
D/PreloadUpdateManagerStateMachine(12190): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (12190): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    (12190): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine(12190): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine(12190): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine(12190): entry::IDLE
,E/Watchdog( 3525): !@Sync 4
,D/SSRM:n  ( 3525): SIOP:: AP = 290, PST = 290, CUR = -267
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:-33, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:108
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2869): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3525): SIOP:: AP = 270, PST = 288, CUR = -33
,I/PowerManagerService( 3525): [PWL] Off : 50s ago
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:47, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:88
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 3525): SIOP:: AP = 270, PST = 283, CUR = 47
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:69, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:77
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3525): !@Sync 5
,D/SSRM:n  ( 3525): SIOP:: AP = 260, PST = 281, CUR = 69
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:74, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:82
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3525): [PWL] Off : 75s ago
,D/SSRM:n  ( 3525): SIOP:: AP = 260, PST = 280, CUR = 74
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:73, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:63
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate,
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3525): waitForAlarm result :8
,I/ClearcutLoggerApiImpl( 4667): disconnect managed GoogleApiClient
,D/SSRM:n  ( 3525): SIOP:: AP = 260, PST = 279, CUR = 73
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3525): online:4, current avg:69, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:70
D/BatteryService( 3525): stay LED for fully charged
D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3525): !@Sync 6
,D/SSRM:n  ( 3525): SIOP:: AP = 260, PST = 275, CUR = 69
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:65, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:67
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2869): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3525): [PWL] Off : 105s ago
,D/SSRM:n  ( 3525): SIOP:: AP = 250, PST = 273, CUR = 65
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:63, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:63
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 3525): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3694): handleTimeUpdate
,D/KeyguardEffectViewController( 3694): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3694): *** don't update sliding image ***
,D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 3525): SIOP:: AP = 250, PST = 272, CUR = 63
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:58, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:55
D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3525): !@Sync 7
,D/SSRM:n  ( 3525): SIOP:: AP = 250, PST = 269, CUR = 58
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:56, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:49
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3525): [PWL] Off : 140s ago
,D/SSRM:n  ( 3525): SIOP:: AP = 250, PST = 265, CUR = 56
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:54, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:59
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3525): waitForAlarm result :8
,D/SSRM:n  ( 3525): SIOP:: AP = 250, PST = 263, CUR = 54
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:51, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:53
D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3525): !@Sync 8
,D/SSRM:n  ( 3525): SIOP:: AP = 250, PST = 261, CUR = 51
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,I/MMD     ( 2869): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3525): SIOP:: AP = 250, PST = 260, CUR = 51
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:50, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3525): [PWL] Off : 180s ago
,D/SSRM:n  ( 3525): SIOP:: AP = 250, PST = 257, CUR = 50
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:49, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:66
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3525): !@Sync 9
,D/SSRM:n  ( 3525): SIOP:: AP = 250, PST = 256, CUR = 49
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:47, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:49
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3525): SIOP:: AP = 250, PST = 255, CUR = 47
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:45, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:46
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 250, PST = 255, CUR = 45
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService( 3525): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3525): TimaServiceHandler.handleMessage what =1
,D/TimaService( 3525): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize( 3525): initializing...
,I/TLC_TIMA_PKM_initialize( 3525): root = 0, root_strlen = 1,
I/TLC_TIMA_PKM_initialize( 3525): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 3525): input max_sendmsg_size = 262196
,I/TZ: mc_tlc_communication( 3525): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 3525): root = 0, root_len = 1
,I/TZ: mc_tlc_communication( 3525): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 3525): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 3525): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 3525): device_id = 0x0
I/TZ: mc_tlc_communication( 3525): tlc_open() was called
I/TZ: mc_tlc_communication( 3525): Opening MobiCore device
,I/TZ: mc_tlc_communication( 3525): Allocating WSM for TCI
,I/TZ: mc_tlc_communication( 3525): Opening the session
,I/TZ: mc_tlc_communication( 3525): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 3525): Trustlet response is completed
,E/Watchdog( 3525): !@Sync 10
,D/SSRM:n  ( 3525): SIOP:: AP = 240, PST = 253, CUR = 45
,I/TLC_TIMA_PKM_measure_kernel( 3525): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3525): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3525): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3525): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3525): online:4, current avg:44, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:42
D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,I/MMD     ( 2869): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3525): [PWL] Off : 225s ago
,D/SSRM:n  ( 3525): SIOP:: AP = 240, PST = 252, CUR = 44
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:43, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3525): SIOP:: AP = 240, PST = 251, CUR = 43
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3525): !@Sync 11
,D/SSRM:n  ( 3525): SIOP:: AP = 240, PST = 250, CUR = 43,
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:43, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:55
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3525): SIOP:: AP = 240, PST = 248, CUR = 43
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:43, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 240, PST = 248, CUR = 43
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3525): online:4, current avg:42, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
I/MotionRecognitionService( 3525): setPowerConnected  = true
D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3525): [PWL] Off : 275s ago
,E/Watchdog( 3525): !@Sync 12
,D/SSRM:n  ( 3525): SIOP:: AP = 240, PST = 247, CUR = 42
,I/MMD     ( 2869): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:41, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:55
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 240, PST = 246, CUR = 41
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:40, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:34
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3525): SIOP:: AP = 240, PST = 245, CUR = 40
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:45
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3525): !@Sync 13
,D/SSRM:n  ( 3525): SIOP:: AP = 240, PST = 245, CUR = 39
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:38, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3525): SIOP:: AP = 240, PST = 245, CUR = 38
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3525): waitForAlarm result :8
,I/PowerManagerService( 3525): [PWL] Off : 330s ago
,D/SSRM:n  ( 3525): SIOP:: AP = 240, PST = 244, CUR = 37
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3525): !@Sync 14
,D/SSRM:n  ( 3525): SIOP:: AP = 240, PST = 244, CUR = 37,
,I/MMD     ( 2869): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:38, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 240, PST = 244, CUR = 38
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3525): SIOP:: AP = 240, PST = 243, CUR = 39
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:38, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:41
D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3525): !@Sync 15
,D/SSRM:n  ( 3525): SIOP:: AP = 240, PST = 243, CUR = 38
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:38, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:41
D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 240, PST = 243, CUR = 38
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3525): [PWL] Off : 390s ago
,D/SSRM:n  ( 3525): SIOP:: AP = 240, PST = 242, CUR = 35
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:34, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:45
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3525): !@Sync 16
,D/SSRM:n  ( 3525): SIOP:: AP = 240, PST = 242, CUR = 34
,I/MMD     ( 2869): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:34, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:45
D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 240, PST = 242, CUR = 34
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:45
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 240, PST = 241, CUR = 32
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:33, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3525): !@Sync 17
,D/SSRM:n  ( 3525): SIOP:: AP = 240, PST = 241, CUR = 33
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3525): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 240, PST = 241, CUR = 32
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:33, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 240, PST = 240, CUR = 33
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3525): [PWL] Off : 455s ago
,E/Watchdog( 3525): !@Sync 18
,D/SSRM:n  ( 3525): SIOP:: AP = 240, PST = 240, CUR = 32
,I/MMD     ( 2869): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 240, PST = 240, CUR = 32
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:34
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 240, PST = 240, CUR = 32
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3525): !@Sync 19
,D/SSRM:n  ( 3525): SIOP:: AP = 240, PST = 240, CUR = 31
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 240, PST = 240, CUR = 30
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 240, PST = 240, CUR = 29
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 3525): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3525): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 3525): TimaServiceHandler.handleMessage what =1,
,E/Watchdog( 3525): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 3525): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3525): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3525): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3525): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:n  ( 3525): SIOP:: AP = 240, PST = 240, CUR = 28
,I/MMD     ( 2869): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 3525): [PWL] Off : 525s ago
,D/SSRM:n  ( 3525): SIOP:: AP = 240, PST = 240, CUR = 28
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3525): SIOP:: AP = 240, PST = 240, CUR = 28
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3525): !@Sync 21
,D/SSRM:n  ( 3525): SIOP:: AP = 240, PST = 240, CUR = 28
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3525): SIOP:: AP = 240, PST = 240, CUR = 28,
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:34
D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 239, CUR = 27
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3525): !@Sync 22
,D/SSRM:n  ( 3525): SIOP:: AP = 240, PST = 239, CUR = 26
,I/MMD     ( 2869): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 239, CUR = 26,
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3525): [PWL] Off : 600s ago
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 238, CUR = 27
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3525): !@Sync 23
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 238, CUR = 27
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 238, CUR = 26
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 237, CUR = 27
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3525): !@Sync 24
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 237, CUR = 25
,I/MMD     ( 2869): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 236, CUR = 25,
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 236, CUR = 24
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3525): !@Sync 25
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 236, CUR = 24
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3525): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
,D/BatteryService( 3525): stay LED for fully charged
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3525): [PWL] Off : 680s ago
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 235, CUR = 23,
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 235, CUR = 24
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3525): !@Sync 26
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 235, CUR = 25
,I/MMD     ( 2869): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4400, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3525): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 234, CUR = 25
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
D/BatteryService( 3525): stay LED for fully charged
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 234, CUR = 24
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
D/BatteryService( 3525): stay LED for fully charged
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3525): !@Sync 27
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 234, CUR = 24,
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 233, CUR = 24
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 233, CUR = 22
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3525): !@Sync 28
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 233, CUR = 22
,I/MMD     ( 2869): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3525): [PWL] Off : 765s ago
,V/AlarmManager( 3525): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3694): handleTimeUpdate
,D/KeyguardEffectViewController( 3694): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3694): *** don't update sliding image ***
,D/LightsService( 3525): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,I/Sensors ( 3525): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager( 3525): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 6602): Aggregate from 1454090962714 (log), 1454090962714 (data)
,I/Sensors ( 3525): #>LightSensor r=0 g=0 b=1 c=2 atime=238 again=64 lux=0.000000
,D/LightsService( 3525): [SvcLED]  onSensorChanged::light value = 0
I/Sensors ( 3525): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager( 3525): unregisterListener ::   
D/LightsService( 3525): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 232, CUR = 23
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/BatteryService( 3525): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 232, CUR = 22
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3525): !@Sync 29
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 232, CUR = 21
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 231, CUR = 22
,V/AlarmManager( 3525): waitForAlarm result :8
,V/AlarmManager( 3525): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3694): handleTimeUpdate
,D/KeyguardEffectViewController( 3694): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3694): *** don't update sliding image ***
,D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate,
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 231, CUR = 21
,D/TimaService( 3525): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3525): TIMA: checkEvent, operation: 50000 subject: 10000,
,D/TimaService( 3525): TimaServiceHandler.handleMessage what =1
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3525): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 3525): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3525): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3525): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3525): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 231, CUR = 22
,W/ProcessCpuTracker( 3525): Skipping unknown process pid 12975
,I/MMD     ( 2869): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 230, CUR = 20
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 230, CUR = 19
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3525): !@Sync 31
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 230, CUR = 20
,I/PowerManagerService( 3525): [PWL] Off : 855s ago
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 230, CUR = 20
,V/AlarmManager( 3525): waitForAlarm result :8
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 230, CUR = 21
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3525): !@Sync 32
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 230, CUR = 21
,I/MMD     ( 2869): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 230, CUR = 19
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 230, CUR = 19
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3525): !@Sync 33
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 230, CUR = 20
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 230, CUR = 18
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 230, CUR = 20
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3525): !@Sync 34
,I/MMD     ( 2869): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 230, CUR = 19
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3525): [PWL] Off : 950s ago
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 230, CUR = 18
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 230, CUR = 19
,E/Watchdog( 3525): !@Sync 35
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 230, CUR = 18
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 230, CUR = 18
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 230, CUR = 17
,E/Watchdog( 3525): !@Sync 36
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2869): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 230, CUR = 18
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 230, CUR = 18
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 230, CUR = 18
,E/Watchdog( 3525): !@Sync 37
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 230, CUR = 16
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 230, CUR = 17
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3525): [PWL] Off : 1050s ago
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 230, CUR = 17
,E/Watchdog( 3525): !@Sync 38
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,I/MMD     ( 2869): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 230, CUR = 17
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 230, CUR = 17
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 230, CUR = 17
,E/Watchdog( 3525): !@Sync 39
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 230, CUR = 17
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3525): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 230, CUR = 17
,V/AlarmManager( 3525): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3694): handleTimeUpdate
,D/KeyguardEffectViewController( 3694): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3694): *** don't update sliding image ***
,V/GLSActivity( 4667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/art     ( 4667): Explicit concurrent mark sweep GC freed 77530(4MB) AllocSpace objects, 24(912KB) LOS objects, 34% free, 30MB/46MB, paused 1.883ms total 67.330ms
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 230, CUR = 17
,D/TimaService( 3525): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3525): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 3525): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 3525): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 3525): handleMessage : MSG_UPDATE_USAGE_DB
I/ApplicationUsage( 3525): Updating Usage Statistics in DB @ 1454093113763
,I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3525): ,	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3525): 	,at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): ,	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252),
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	,at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	,at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
,W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3525): ::getAppControlDB: Exception to create DB
W/System.err( 3525): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3525): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage( 3525): Done Updating Usage Statistics in DB @ 1454093113822
,E/Watchdog( 3525): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 3525): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3525): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3525): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3525): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2869): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 230, CUR = 16
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 230, CUR = 17
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 230, CUR = 15
,E/Watchdog( 3525): !@Sync 41
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 230, CUR = 15
,I/PowerManagerService( 3525): [PWL] Off : 1155s ago
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 230, CUR = 17
,V/AlarmManager( 3525): waitForAlarm result :8
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 230, CUR = 15
,E/Watchdog( 3525): !@Sync 42
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3525): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2869): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 230, CUR = 14
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 230, CUR = 15
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 230, CUR = 14
,E/Watchdog( 3525): !@Sync 43
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/BatteryService( 3525): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 230, CUR = 14
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 230, CUR = 13
,I/art     ( 3525): Background sticky concurrent mark sweep GC freed 94968(9MB) AllocSpace objects, 368(5MB) LOS objects, 13% free, 49MB/57MB, paused 3.459ms total 121.260ms
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,TIME-OUT KILL (timeout was 1200000ms),D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 230, CUR = 13
D/AndroidRuntime(13268): 
D/AndroidRuntime(13268): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(13268): CheckJNI is OFF
D/AndroidRuntime(13268): readGMSProperty: start
D/AndroidRuntime(13268): readGMSProperty: already setted!!
D/AndroidRuntime(13268): readGMSProperty: end
D/AndroidRuntime(13268): addProductProperty: start
E/AffinityControl(13268): AffinityControl: registerfunction enter
D/AndroidRuntime(13268): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 3525): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 3525): START PACKAGE DELETE: observer{107577231}
D/PackageManager( 3525): pkg{<packageName>}
D/PackageManager( 3525): user{0}
D/PackageManager( 3525): caller{2000}
D/PackageManager( 3525): flags{3}
D/PersonaManagerService( 3525): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 3525): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 3525): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3525): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3525): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3525): !@killApplicatoin: 10612, uninstall pkg
D/PackageManagerService( 3525): deletePackage- pkg:com.test.thalitest, edmuserId:0
I/ActivityManager( 3525): Force stopping com.test.thalitest appid=10612 user=-1: uninstall pkg
D/PackageManagerService( 3525): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 3525): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3525): getApplicationUninstallationEnabled :  enabled true
I/ActivityManager( 3525): Killing 11658:com.test.thalitest/u0a612 (adj 0): stop com.test.thalitest
I/ActivityManager( 3525):   Force finishing activity ActivityRecord{241543e4 u0 com.test.thalitest/.MainActivity t26}
W/ActivityManager( 3525): mDVFSHelper.acquire()
W/PackageSettings( 3525): Skipping PackageSetting{115eb83a com.example.hello/10563} due to missing metadata
D/WifiService( 3525): Client connection lost with reason: 4
I/WindowState( 3525): WIN DEATH: Window{78bb80a u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger( 2848): id=14 Removed NainActivit (5/8)
I/SurfaceFlinger( 2848): id=14 Removed NainActivit (-2/8)
D/PointerIcon( 3525): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3525): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3525): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3525): setHoveringSpenCustomIcon IconType is same.1
I/DBG_DM  ( 6244): [com.wssyncmldm.ui.XUIInstallConfirmActivity(456/onResume)] 
I/ActivityManager( 3525): Force stopping com.test.thalitest appid=10612 user=0: pkg removed
I/DBG_DM  ( 6244): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 10
I/DBG_DM  ( 6244): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
I/DBG_DM  ( 6244): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 6244): [com.wssyncmldm.ui.XUIInstallConfirmActivity(466/onResume)] Postpone Count : 10
I/DBG_DM  ( 6244): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
I/DBG_DM  ( 6244): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
I/art     ( 8802): Explicit concurrent mark sweep GC freed 31625(1742KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.252ms total 45.606ms
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
E/SamsungIME( 4458): mOCRHelper is null
W/GeofencerStateMachine( 4667): Ignoring removeGeofence because network location is disabled.
I/art     ( 6602): Explicit concurrent mark sweep GC freed 31275(1806KB) AllocSpace objects, 5(80KB) LOS objects, 20% free, 31MB/39MB, paused 2.134ms total 106.113ms
I/InputReader( 3525): Reconfiguring input devices.  changes=0x00000010
D/LWLocationManager(11393): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(11393): getLastUiLocationId() : mLastUiLocationId = -100
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
I/art     ( 4070): Explicit concurrent mark sweep GC freed 33303(2041KB) AllocSpace objects, 1(39KB) LOS objects, 21% free, 28MB/36MB, paused 1.135ms total 69.038ms
E/Zygote  (13299): MountEmulatedStorage()
E/Zygote  (13299): v2
I/libpersona(13299): KNOX_SDCARD checking this for 10063
I/libpersona(13299): KNOX_SDCARD not a persona
W/ResourceType( 5346): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5346): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
I/SELinux (13299): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (13299): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3525): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=13299 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (13299): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/DBG_DM  ( 6244): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
D/SecContentProvider2( 3525): uri = 14 selection = getSealedState
D/SecContentProvider2( 3525): mCursor = null
D/ApplicationPolicy( 3525): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3525): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/TimaKeyStoreProvider(13299): TimaSignature is unavailable
D/ActivityThread(13299): Added TimaKeyStore provider
I/DBG_DM  ( 6244): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 10
I/DBG_DM  ( 6244): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
D/ResourcesManager(11393): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
I/DBG_DM  ( 6244): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 6244): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
I/DBG_DM  ( 6244): [llIIlIIlIllIllIlllII(376/llIIllllIIlllIIIIlll)] 
I/DBG_DM  ( 6244): [IIlIIIlllllIIlIIIlII(339/llllIlIIIllllIIlIlll)] No need to check encryption status
I/DBG_DM  ( 6244): [llIIlIIlIllIllIlllII(405/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
D/ActivityManager( 3525): post active user change for 0
D/KnoxTimeoutHandler( 3525): postActiveUserChange for user 0
I/DBG_DM  ( 6244): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
I/SurfaceFlinger( 2848): id=16 createSurf (1440x2560),2 flag=404, YUIInstallC
D/StatusBarManagerService( 3525): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService( 3525): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 3525): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3525): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3525): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3525): setHoveringSpenCustomIcon IconType is same.1
V/ActivityThread( 6244): updateVisibility : ActivityRecord{2da6e1cc token=android.os.BinderProxy@dbee7d9 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
I/art     ( 3525): Explicit concurrent mark sweep GC freed 19297(1551KB) AllocSpace objects, 7(112KB) LOS objects, 24% free, 49MB/65MB, paused 2.652ms total 180.576ms
D/ResourcesManager( 3525): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/art     ( 3525): WaitForGcToComplete blocked for 173.270ms for cause Explicit
D/ResourcesManager(11393): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ResourcesManager(13299): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/VRSetupWizardStub/PackageIntentReceiver(13299): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(13299): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(13299): packagename:com.test.thalitest
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager(11393): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/SecContentProvider2( 3525): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3525): mCursor = null
I/KLMS-2.4.521: (11908): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jan 29 19:47:11 GMT+01:00 2016
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
D/ResourcesManager( 3525): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
I/KLMS-2.4.521: (11908): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 3525): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3525): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
D/ResourcesManager(11393): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
D/InputMethodManagerService( 3525): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
I/KLMS-2.4.521: (11908): KLMSIntentService(): onCreate()
E/Zygote  (13317): MountEmulatedStorage()
E/Zygote  (13317): v2
I/libpersona(13317): KNOX_SDCARD checking this for 10106
I/libpersona(13317): KNOX_SDCARD not a persona
W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/SELinux (13317): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
W/InputMethodManagerService( 3525): Got RemoteException sending setActive(false) notification to pid 11658 uid 10612
D/ResourcesManager(11393): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
I/KLMS-2.4.521: (11908): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/SELinux (13317): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3525): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=13317 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
I/KLMS-2.4.521: (11908): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
E/SELinux (13317): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/Timeline( 6244): Timeline: Activity_idle id: android.os.BinderProxy@dbee7d9 time:1329564
D/RegisteredServicesCache( 3964): empty dynamic service
I/KLMS-2.4.521: (11908): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/KLMS-2.4.521: (11908): KLMSIntentService(): PACKAGE_REMOVED
I/KLMS-2.4.521: (11908): KLMSIntentService(): listeningToPackageRemoved().START
D/ResourcesManager(11393): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
W/ActivityManager( 3525): mDVFSHelper.release()
I/KLMS-2.4.521: (11908): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
I/Timeline( 3525): Timeline: Activity_windows_visible id: ActivityRecord{2ac5a169 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t24} time:1329585
D/ResourcesManager(11393): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
D/RCPManager(12002):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3525):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3525): queryAllProviders():  providerCallBack is not register for 0
D/TimaKeyStoreProvider(13317): TimaSignature is unavailable
D/ActivityThread(13317): Added TimaKeyStore provider
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(11393): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
I/art     ( 3525): Explicit concurrent mark sweep GC freed 6257(330KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 49MB/65MB, paused 1.556ms total 127.917ms
D/ResourcesManager(11393): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
E/Zygote  (13335): MountEmulatedStorage()
E/Zygote  (13335): v2
I/libpersona(13335): KNOX_SDCARD checking this for 10050
I/libpersona(13335): KNOX_SDCARD not a persona
I/SELinux (13335): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3525): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=13335 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/SELinux (13335): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (13335): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(11393): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
W/ResourcesManager(11393): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/ResourcesManager(11393): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/PackageManager( 3525): delete codoeFile: 
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
D/ResourcesManager(11393): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
I/AASAUninstall( 3525):  com.test.thalitest not target!
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/PackageManager( 3525): result of delete: 1{107577231}
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/AndroidRuntime(13268): Shutting down VM
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(11393): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/TimaKeyStoreProvider(13335): TimaSignature is unavailable
D/ActivityThread(13335): Added TimaKeyStore provider
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
I/KLMS-2.4.521: (11908): KLMSIntentService(): listeningToPackageRemoved().END
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
E/Zygote  (13348): MountEmulatedStorage()
E/Zygote  (13348): v2
I/libpersona(13348): KNOX_SDCARD checking this for 10183
I/libpersona(13348): KNOX_SDCARD not a persona
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
I/SELinux (13348): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager(13317): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/ResourcesManager(11393): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Music2/Music2.apk
I/SELinux (13348): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
W/ResourcesManager(11393): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(11393): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11393): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/ActivityManager( 3525): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=13348 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
W/ResourcesManager(11393): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
E/SELinux (13348): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/ResourcesManager(11393): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/elm:14491(13317): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14491(13317): ELMEngine.ELMEngine( context ).
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
D/elm:14491(13317): MDMBridge.setEnterpriseBridge()
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
I/KLMS-2.4.521: (11908): KLMSIntentService(): onDestroy()
D/ResourcesManager(11393): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/TimaKeyStoreProvider(13348): TimaSignature is unavailable
E/Zygote  (13363): MountEmulatedStorage()
I/libpersona(13363): KNOX_SDCARD checking this for 10101
E/Zygote  (13363): v2
I/libpersona(13363): KNOX_SDCARD not a persona
D/ActivityThread(13348): Added TimaKeyStore provider
I/SELinux (13363): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3525): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=13363 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ResourcesManager(11393): creating new AssetManager and set to /system/app/Videos/Videos.apk
I/SELinux (13363): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (13363): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/elm:14491(13317): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14491(13317): ElmAgentService : onCreate()
D/elm:14491(13317): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
D/elm:14491(13317): MainReceiver.listeningToPackageRemoved()
D/elm:14491(13317): MDMBridge.getInstance()
D/elm:14491(13317): MDMBridge.getAllLicenseInfoFromSDK()
D/ResourcesManager( 3525): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/elm:14491(13317): MDMBridge.getAllLicenseInfoFromSDK()
I/ActivityManager( 3525): Killing 11425:com.android.calendar/u0a164 (adj 13): bgCount ##31
D/RCPManagerService( 3525): PackageReceiver onReceive()
I/HarmonyEASService( 3525): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy( 3525): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService( 3525): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 3525): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3525): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3525): uID is 10612
V/EnterpriseBillingPolicy( 3525): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3525): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 3525): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3525): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3525): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3525): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 3525): getBillingProfileForVpnEngine - end - null
D/TimaKeyStoreProvider(13363): TimaSignature is unavailable
D/ActivityThread(13363): Added TimaKeyStore provider
D/ResourcesManager(11393): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/ResourcesManager(13335): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(11393): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
W/ResourcesManager(13335): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(13335): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(13335): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(13335): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13335): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(13335): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(13335): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(13335): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/ResourcesManager(13348): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
D/ResourcesManager(11393): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
E/Zygote  (13382): MountEmulatedStorage()
E/Zygote  (13382): v2
I/libpersona(13382): KNOX_SDCARD checking this for 10019
I/libpersona(13382): KNOX_SDCARD not a persona
I/SELinux (13382): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (13382): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3525): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=13382 uid=10019 gids={50019, 9997} abi=armeabi-v7a
E/SELinux (13382): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/elm:14491(13317): ElmAgentService : onDestroy().
D/ResourcesManager(11393): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
E/SQLiteLog(13348): (284) automatic index on shooting_modes(title_id)
D/ResourcesManager(11393): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/TimaKeyStoreProvider(13382): TimaSignature is unavailable
D/ActivityThread(13382): Added TimaKeyStore provider
D/ResourcesManager(11393): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
I/ActivityManager( 3525): Killing 11393:com.sec.android.widgetapp.locationwidget/u0a22 (adj 13): bgCount ##31
D/KnoxTimeoutHandler( 3525): handleActiveUserChange for user 0
D/ResourcesManager(13363): creating new AssetManager and set to /system/app/Drive/Drive.apk
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/Zygote  (13398): MountEmulatedStorage()
E/Zygote  (13398): v2
I/libpersona(13398): KNOX_SDCARD checking this for 10190
I/libpersona(13398): KNOX_SDCARD not a persona
I/SELinux (13398): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (13398): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (13398): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3525): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=13398 uid=10190 gids={50190, 9997} abi=armeabi-v7a
D/TaskPersister( 3525): removeObsoleteFile: deleting file=26_task.xml
D/TaskPersister( 3525): removeObsoleteFile: deleting file=24_task.xml
D/StatusBar( 3694): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
D/PersonaManager( 3694): isKioskContainerExistOnDevice
D/PersonaManager( 3694): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3694): Icon Only
I/StatusBar( 3694): Icon Only
D/PanelView( 3694): There is/are notification(s) 
D/PanelView( 3694): There is/are notification(s) 
D/PersonaManager( 3694): isKioskContainerExistOnDevice
I/ActivityManager( 3525): Killing 10722:com.android.defcontainer/u0a5 (adj 13): bgCount ##31
I/PhoneStatusBar( 3694): Icon Only
I/StatusBar( 3694): Icon Only
D/PanelView( 3694): There is/are notification(s) 
D/PackageManager( 3525): findPreferredActivity: No PreferredActivities set
D/TimaKeyStoreProvider(13398): TimaSignature is unavailable
D/ActivityThread(13398): Added TimaKeyStore provider
D/ResourcesManager(13382): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/NearbySource(13335): Nearby Source Create!
D/NearbyContext(13335): Nearby Context Create!
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/talkback/talkback.apk
D/EnterpriseDeviceManagerService( 3525): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3525): Admin package name: com.google.android.gms
D/ResourcesManager(13398): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
W/ContextImpl(13335): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource(13335): Samsung link source created
W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
I/TapandpayWidget:TanpandpayAppWidgetProvider(13398): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(13398): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
D/WifiDisplayAdapter( 3525): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/com.sec.android.service.health.upgrade.UninstallReceiver(13382): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver(13382): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver(13382): onReceive() : package name is not s health. Return !!!
D/PanelView( 3694): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
I/TapandpayWidget:Utils(13398): Clear T&P info.
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
D/TapandpayWidget:TanpandpayAppWidgetProvider(13398): Widget is not attached.

```
