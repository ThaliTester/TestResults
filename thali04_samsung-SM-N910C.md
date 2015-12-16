#### Test 506502783fcf234_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
D/SSRM:n  ( 3528): SIOP:: AP = 260, PST = 272, CUR = 29
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:51, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:57
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3528): stay LED for fully charged
I/MotionRecognitionService( 3528): Plugged
I/MotionRecognitionService( 3528): setPowerConnected  = true
--------- beginning of main
D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AndroidRuntime(11731): 
D/AndroidRuntime(11731): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11731): CheckJNI is OFF
D/AndroidRuntime(11731): readGMSProperty: start
D/AndroidRuntime(11731): readGMSProperty: already setted!!
D/AndroidRuntime(11731): readGMSProperty: end
D/AndroidRuntime(11731): addProductProperty: start
E/AffinityControl(11731): AffinityControl: registerfunction enter
D/AndroidRuntime(11731): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3528): inState():  stateMachine is null !!
I/PersonaManagerService( 3528): PersonaId don't exist
I/ActivityManager( 3528): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3528): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3528): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3528): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager( 3528): mDVFSHelper.acquire()
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/Zygote  (11750): MountEmulatedStorage()
I/libpersona(11750): KNOX_SDCARD checking this for 10504
E/Zygote  (11750): v2
I/libpersona(11750): KNOX_SDCARD not a persona
I/SELinux (11750): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3528): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=11750 uid=10504 gids={50504, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux (11750): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11750): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(11731): Shutting down VM
D/PointerIcon( 3528): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3528): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3528): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3528): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(11750): TimaSignature is unavailable
D/ActivityThread(11750): Added TimaKeyStore provider
I/SurfaceFlinger( 2850): id=11 Removed YUIInstallC (5/8)
I/SurfaceFlinger( 2850): id=11 Removed YUIInstallC (-2/8)
D/ResourcesManager(11750): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
V/ActivityThread( 6269): updateVisibility : ActivityRecord{fa12aef token=android.os.BinderProxy@11ad3750 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
I/WebViewFactory(11750): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(11750): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(11750): Loading: webviewchromium
I/LibraryLoader(11750): Time to load native libraries: 3 ms (timestamps 4782-4785)
I/LibraryLoader(11750): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(11750): Binding Chromium to main looper Looper (main, tid 1) {3d4b1ede}
I/LibraryLoader(11750): Expected native library version number "",actual native library version number ""
I/chromium(11750): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController(11750): Initializing chromium process, renderers=0
W/art     (11750): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium(11750): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium(11750): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(11750): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
W/chromium(11750): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium(11750): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     (11750): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents(11750): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine(11750): CordovaWebView is running on device made by: samsung
W/art     (11750): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11750): Attempt to remove local handle scope entry from IRT, ignoring
D/Activity(11750): performCreate Call secproduct feature valuefalse
D/Activity(11750): performCreate Call debug elastic valuetrue
D/OpenGLRenderer(11750): Render dirty regions requested: true
D/ActivityManager( 3528): post active user change for 0
D/KnoxTimeoutHandler( 3528): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3528): handleActiveUserChange for user 0
I/SurfaceFlinger( 2850): id=14 createSurf (1x1),1 flag=404, NainActivit
D/StatusBarManagerService( 3528): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService( 3528): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 3528): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3528): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3528): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3528): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer(11750): Initialized EGL, version 1.4
I/OpenGLRenderer(11750): HWUI protection enabled for context ,  &this =0xaf545060 ,&mEglDisplay = 1 , &mEglConfig = -1279692528 
D/OpenGLRenderer(11750): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(11750): Enabling debug mode 0
D/mali_winsys(11750): new_window_surface returns 0x3000,  [1440x2560]-format:1
V/ActivityThread(11750): updateVisibility : ActivityRecord{396afb8e token=android.os.BinderProxy@13354d1d {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
D/InputMethodManagerService( 3528): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ActivityManager( 3528): mDVFSHelper.release()
I/Timeline( 3528): Timeline: Activity_windows_visible id: ActivityRecord{2e4b8d41 u0 com.test.thalitest/.MainActivity t26} time:135142
W/IInputConnectionWrapper(11750): showStatusIcon on inactive InputConnection
I/Timeline(11750): Timeline: Activity_idle id: android.os.BinderProxy@13354d1d time:135150
D/JsMessageQueue(11750): Set native->JS mode to OnlineEventsBridgeMode
I/chromium(11750): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11750): 
D/jxcore_app_log(11750): JniHelper::setJavaVM(0xb4d5c280), pthread_self() = -1358476672
D/JX-Cordova(11750): jxcore cordova android initializing
,I/MMD     ( 2874): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,W/jxcore-log(11750): Initializing JXcore engine
W/jxcore-log(11750): JXcore engine is ready
,W/jxcore-log(11750): Starting JXcore engine
,E/auditd  ( 4613): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3528): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3528): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(11750): Platform android
W/jxcore-log(11750): 
W/jxcore-log(11750): Process ARCH arm
W/jxcore-log(11750): 
,I/jxcore-log(11750): JXcore Cordova bridge is ready!
I/jxcore-log(11750): 
W/jxcore-log(11750): JXcore engine is started
,I/jxcore-log(11750): Toggling radios to true
I/jxcore-log(11750): 
,D/BluetoothAdapter(11750): enable()
D/BluetoothAdapter(11750): enable(): BT is already enabled..!
,D/WifiService( 3528): New client listening to asynchronous messages
,I/WifiManager(11750): packageName : com.test.thalitest
,D/SecContentProvider( 3528): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3528): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3528): mCursor = null
,D/WifiService( 3528): setWifiEnabled: true pid=11750, uid=10504
E/WifiService( 3528): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3528): Permission Denial: getCurrentUser() from pid=11750, uid=10504 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 3528): Failed getting userId using ActivityManagerNative
W/WifiService( 3528): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=11750, uid=10504 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3528): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3528): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3528): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3528): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3528): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider( 3528): name = wifi_on
I/WifiService( 3528): disconnect: pid=11750, uid=10504
,I/wpa_supplicant( 3836): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log(11750): Radios toggled
I/jxcore-log(11750): 
,I/wpa_supplicant( 3836): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3836): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 3836): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3836): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine( 3528): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 3836): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3836): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3836): Disconnected - do not scan
I/wpa_supplicant( 3836): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine( 3528): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3528): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3528): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3528): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/jxcore-log(11750): Got Device Bluetooth address: E0:DB:10:14:E2:C0
I/jxcore-log(11750): 
,I/jxcore-log(11750): Perf Test app loaded loaded
I/jxcore-log(11750): 
,E/WifiStateMachine( 3528): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
I/jxcore-log(11750): check test folder
I/jxcore-log(11750): 
,E/WifiStateMachine( 3528): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3528): do suspend true
,I/jxcore-log(11750): found test : ./testFindPeers.js
I/jxcore-log(11750): 
,D/WifiP2pService( 3528): InactiveState{ what=143375 }
,D/WifiP2pService( 3528): P2pEnabledState{ what=143375 }
,D/CommandListener( 2846): Clearing all IP addresses on wlan0
,E/Netd    ( 2846): ifc_reset_connections failed on iface wlan0 for address 192.168.1.124/24 (Unknown error -1)
,D/StatusBar.NetworkController( 3694): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,E/WifiStateMachine( 3528): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/ConnectivityService( 3528): updateNetworkInfo()
E/WifiConfigStore( 3528): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService( 3528): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3528): updateNetworkInfo()
,I/WifiTrafficPoller( 3528): evaluateTrafficStatsPolling
D/ConnectivityService( 3528): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
,I/jxcore-log(11750): found test : ./testSendData.js
I/jxcore-log(11750): 
,D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
,I/Hs20UtilService( 4103): Starting #8
,I/Hs20UtilService( 4103): Message received 5007
,D/NearbySettings( 8926): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 8926): MountReceiver.onReceive - Start HandlerThread
,D/NearbySettings( 8926): MountReceiver.onReceive - Create mPrefHandler
,D/NearbySettings( 8926): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8926): DMSUtil.isNetworkConnected - flag-null, state-null
,E/WifiStateMachine( 3528): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 3836): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3836): P2P: Current p2p state = IDLE
I/wpa_supplicant( 3836): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 3836): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3836): First Scan Start
,E/WifiStateMachine( 3528): ConnectModeState: Network connection lost 
,E/WifiStateMachine( 3528): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - processMessage - processMsg
I/NearbySettings( 8926): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
E/WifiStateMachine( 3528): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
I/wpa_supplicant( 3836): Scan requested (ret=0) - scan timeout 30 seconds
E/WifiStateMachine( 3528): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3528): do suspend true
,D/WifiService( 3528): New client listening to asynchronous messages
,I/NearbySettings( 8926): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8926): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8926): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8926): MountReceiver.mPrefHandler - 7002
,D/WifiP2pService( 3528): InactiveState{ what=143375 }
D/WifiP2pService( 3528): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,I/SignOutReceiver(11408): NETWORK_STATE_CHANGED_ACTION
,D/CommandListener( 2846): Clearing all IP addresses on wlan0
D/ConnectivityService( 3528): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,D/EntConnectivity( 3528): Not allowed due to - mEnabled false
,E/WifiStateMachine( 3528): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/WifiStateMachine( 3528): updateConfiguredNetworkExpiration - currTime: 1450238338135
D/WifiStateMachine( 3528): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
,D/ConnectivityManager.CallbackHandler( 3694): CM callback handler got msg 524292
E/WifiStateMachine( 3528): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine( 3528): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/WifiTrafficPoller( 3528): evaluateTrafficStatsPolling
E/WifiStateMachine( 3528): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3528): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 3528): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3528): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent( 3528): NetworkAgent: NetworkAgent channel lost
,D/ConnectivityService( 3528): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3528): ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityManager.CallbackHandler( 6682): CM callback handler got msg 524292
,D/TelephonyNetworkFactory( 3983): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,D/CSLegacyTypeTracker( 3528): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,D/CSLegacyTypeTracker( 3528): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,D/ConnectivityService( 3528): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,E/WifiStateMachine( 3528): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3528): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine( 3528): setDetailed state send new extra info"NG700"
,D/SecContentProvider2( 3528): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3528): mCursor = null
,D/EntConnectivity( 3528): Not allowed due to - mEnabled false
I/Hs20UtilService( 4103): Starting #9
D/Tethering( 3528): MasterInitialState.processMessage what=3
D/SmartBondingService( 3528): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService( 3528): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
I/Hs20UtilService( 4103): Message received 5007
D/ConnectivityService( 3528): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/SmartBondingService( 3528): getSBEnabled() enabled =false
D/SmartBondingService( 3528): getSBEnabled() enabled =false
D/SmartBondingService( 3528): getSBEnabled() enabled =false
D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3694): updateDataNetType()
D/StatusBar.NetworkController( 3694): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3694): updateLTEICONDataNetType:0
V/NetworkStats( 3528): updateIfacesLocked()
D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
V/NetworkStats( 3528): performPollLocked(flags=0x1)
D/SmartBondingService( 3528): getNetworkEnabled : wifi : true mobile : false
D/NetworkStatsFactory( 3528): UpdateStatsForKnox
D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 3694): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
V/NetworkStats( 3528): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
V/NetworkStats( 3528): performPollLocked() took 16ms
D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 3694): applyOpen
,D/SecContentProvider2( 3528): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3528): mCursor = null
,D/NearbySettings( 8926): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
,V/NearbySettings( 8926): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8926): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8926): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8926): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8926): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8926): MountReceiver.mPrefHandler - 7002
,I/chromium(11750): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/SignOutReceiver(11408): NETWORK_STATE_CHANGED_ACTION
,D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
,I/chromium(11750): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
,D/ConnectivityService( 3528): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 3528): updateDataUsageMap
,I/ApplicationPolicy( 3528): updateDataUsageMap  idList is null 
,D/SmartBondingService( 3528): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3528): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3528): getSBEnabled() enabled =false
D/SmartBondingService( 3528): getSBEnabled() enabled =false
D/SmartBondingService( 3528): getSBEnabled() enabled =false
,D/GpsLocationProvider( 3528): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3528): getNetworkEnabled : wifi : true mobile : false
,W/SLocation( 3528): No Active Data Connection
,I/DBG_DM  ( 6269): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/DBG_DM  ( 6269): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11874): MountEmulatedStorage()
E/Zygote  (11874): v2
I/libpersona(11874): KNOX_SDCARD checking this for 10110
I/libpersona(11874): KNOX_SDCARD not a persona
,I/SELinux (11874): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11874): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11874): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3528): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.iorg.vpn.cleanup.NetworkStateMonitor: pid=11874 uid=10110 gids={50110, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11874): TimaSignature is unavailable
,D/ActivityThread(11874): Added TimaKeyStore provider
,D/ResourcesManager(11874): creating new AssetManager and set to /data/app/com.facebook.appmanager-2/base.apk
,D/ACRA    (11874): ACRA is enabled for com.facebook.appmanager, intializing...
,I/DexLibLoader(11874): not using cross-dex optimization: ART in use
,I/art     (11874): Thread[1,tid=11874,WaitingForJniOnLoad,Thread*=0xb4d08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/app/com.facebook.appmanager-2/lib/arm/libfbjni.so"
,V/DexLibLoader(11874): about to lock: /data/data/com.facebook.appmanager/mdex_lock
,V/DexLibLoader(11874): locking /data/data/com.facebook.appmanager/mdex_lock took 0 ms
V/DexLibLoader(11874): Secondary program dex metadata: classes2.dex 29f80981f469a774a4884b3db2df17e0be227159 secondary.dex01.Canary
,D/DexLibLoader(11874): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex" is valid
D/DexLibLoader(11874): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex_opt" is valid
,W/art     (11874): Attempt to remove local handle scope entry from IRT, ignoring
D/DexLibLoader(11874): loading pre-built fallback odex files
,V/MultiDexClassLoader(11874): installing MultiDexClassLoader before application classloader
,D/DexLibLoader(11874): released odex store lock
D/DexLibLoader(11874): DexLibLoader.loadAll took 28 ms
,W/ca      (11874): Verify
,W/LightSharedPreferencesImpl(11874): Failed to load preference file from Disk!
W/LightSharedPreferencesImpl(11874): java.io.FileNotFoundException: /data/data/com.facebook.appmanager/app_light_prefs/com.facebook.appmanager/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11874): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/LightSharedPreferencesImpl(11874): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/LightSharedPreferencesImpl(11874): 	at com.facebook.crudolib.b.k.a(LightSharedPreferencesStorage.java:56)
W/LightSharedPreferencesImpl(11874): 	at com.facebook.crudolib.b.g.run(LightSharedPreferencesImpl.java:61)
W/LightSharedPreferencesImpl(11874): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/LightSharedPreferencesImpl(11874): 	at com.facebook.common.executors.dj.run(WrappingExecutorService.java:77)
W/LightSharedPreferencesImpl(11874): 	at com.facebook.common.executors.u.run(DefaultConstrainedListeningExecutorService.java:327)
W/LightSharedPreferencesImpl(11874): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/LightSharedPreferencesImpl(11874): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/LightSharedPreferencesImpl(11874): 	at com.facebook.common.executors.cc.run(NamedThreadFactory.java:42)
W/LightSharedPreferencesImpl(11874): 	at java.lang.Thread.run(Thread.java:818)
W/LightSharedPreferencesImpl(11874): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11874): 	at libcore.io.Posix.open(Native Method)
W/LightSharedPreferencesImpl(11874): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/LightSharedPreferencesImpl(11874): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/LightSharedPreferencesImpl(11874): 	... 10 more
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11908): MountEmulatedStorage()
E/Zygote  (11908): v2
I/libpersona(11908): KNOX_SDCARD checking this for 1000
I/libpersona(11908): KNOX_SDCARD not a persona
,I/SELinux (11908): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3528): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=11908 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux (11908): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11908): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/appmanager(:<default>):b(11874): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,I/ActivityManager( 3528): Killing 10990:com.policydm/1000 (adj 15): bgCount ##31
,I/wpa_supplicant( 3836): nl80211: Received scan results (15 BSSes)
I/wpa_supplicant( 3836): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3836): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3836): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 3836): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3528): [1,450,238,339,175 ms] noteScanEnd no scan source
,E/WifiStateMachine( 3528): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@317c3623 sup_state=SCANNING debouncing=false
,E/WifiStateMachine( 3528): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
,E/WifiStateMachine( 3528): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3528): setDetailed state send new extra info
,D/SecContentProvider2( 3528): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 3528): mCursor = null
,D/TimaKeyStoreProvider(11908): TimaSignature is unavailable
,W/appmanager(:<default>):b(11874): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/ActivityThread(11908): Added TimaKeyStore provider
,D/ResourcesManager(11908): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/PCWCLIENTTRACE_LOG(11908): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(11908): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(11908): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil(11908): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11908): sales region : global
I/PCWCLIENTTRACE_PushUtil(11908): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11908): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver(11908): noConnectivity : true
,I/wpa_supplicant( 3836): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 3836): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 3836): Associated with C0.AA.48
E/WifiStateMachine( 3528): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3528): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3528): setDetailed state send new extra info"NG700"
,D/SecContentProvider2( 3528): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3528): mCursor = null
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,I/wpa_supplicant( 3836): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 3836): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3528): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3528): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,W/appmanager(:<default>):QuickExperimentControllerImpl(11874): Exposure of experiment com.facebook.common.network.l@1e5db144 occurred when no user was logged in
,D/SecContentProvider2( 3528): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3528): mCursor = null
,I/wpa_supplicant( 3836): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,E/Zygote  (11930): MountEmulatedStorage()
E/Zygote  (11930): v2
I/libpersona(11930): KNOX_SDCARD checking this for 10135
I/wpa_supplicant( 3836): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/libpersona(11930): KNOX_SDCARD not a persona
I/wpa_supplicant( 3836): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/SELinux (11930): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/wpa_supplicant( 3836): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3836): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,I/wpa_supplicant( 3836): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3836): Blacklist: Clear (temp) 
I/wpa_supplicant( 3836): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
I/SELinux (11930): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11930): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3528): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=11930 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3528): Killing 11006:com.sec.android.app.samsungapps/u0a13 (adj 15): bgCount ##31
,W/BroadcastQueue( 3528): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{3480bccc u0 ReceiverList{37fd66ff 11874 com.facebook.appmanager/10110/u0 remote:31445e1e}}
,W/BroadcastQueue( 3528): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{3480bccc u0 ReceiverList{37fd66ff 11874 com.facebook.appmanager/10110/u0 remote:31445e1e}}
,E/WifiStateMachine( 3528): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
,E/WifiStateMachine( 3528): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine( 3528): Network connection established
,D/WifiNative-HAL( 3528): callSECApiVoid - ID [50]
,E/WifiStateMachine( 3528): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine( 3528): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService( 3528): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine( 3528): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService( 3528): hsengiv:checkWhatTypeOfNetwork and the value is false
D/ConnectivityService( 3528): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/WifiStateMachine( 3528): L2ConnectedState "NG700" nid=0
E/ConnectivityService( 3528): updateNetworkInfo()
E/WifiConfigStore( 3528): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/TimaKeyStoreProvider(11930): TimaSignature is unavailable
,D/ActivityThread(11930): Added TimaKeyStore provider
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3528): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine( 3528): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3528): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3528): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener( 2846): Setting iface cfg
,E/WifiStateMachine( 3528): Start Dhcp Watchdog 2
,D/SecContentProvider2( 3528): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3528): mCursor = null
,D/ResourcesManager(11930): creating new AssetManager and set to /system/app/Music2/Music2.apk
,E/WifiStateMachine( 3528): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3528): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,W/BroadcastQueue( 3528): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{1b0125a6 u0 ReceiverList{3a70e301 11874 com.facebook.appmanager/10110/u0 remote:251c20e8}}
,E/WifiStateMachine( 3528): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3528): do suspend false
,D/SecContentProvider2( 3528): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3528): mCursor = null
D/WifiP2pService( 3528): InactiveState{ what=143375 }
,D/WifiP2pService( 3528): P2pEnabledState{ what=143375 }
,I/MusicStore(11930): Database version: 104
,D/ResourcesManager(11930): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11930): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11930): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (11930): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(11930): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  (11930): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@39e36a52: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(11930): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(11930): GMSCore installation verified
,I/ConfigStore(11930): Config Database version: 1
,E/dhcpcd  (11966): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11930): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,I/dhcpcd  (11966): version 5.5.6 starting
,E/dhcpcd  (11966): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11930): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11930): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,I/dhcpcd  (11966): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (11966): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (11966): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  (11966): bssid match
I/dhcpcd  (11966): wlan0: rebinding lease of 192.168.1.124
,D/WifiDisplayAdapter( 3528): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3528): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3528): getStreamVolume 3 index 0
,I/MediaRouter(11930): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/art     ( 3528): Explicit concurrent mark sweep GC freed 59492(3MB) AllocSpace objects, 14(224KB) LOS objects, 24% free, 49MB/65MB, paused 2.265ms total 147.652ms
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11874): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11874): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/Zygote  (11974): MountEmulatedStorage()
E/Zygote  (11974): v2
I/libpersona(11974): KNOX_SDCARD checking this for 10002
I/libpersona(11974): KNOX_SDCARD not a persona
,I/SELinux (11974): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11974): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11974): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3528): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=11974 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/WifiDisplayAdapter( 3528): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/art     ( 2884): Explicit concurrent mark sweep GC freed 8726(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 869us total 26.143ms
,I/NetworkMonitor(11930): type=WIFI subType= reason=null isConnected=false
,I/art     ( 2884): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 815us total 18.372ms
,I/ActivityManager( 3528): Killing 11024:com.sec.android.app.myfiles/u0a53 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(11974): TimaSignature is unavailable
,D/ActivityThread(11974): Added TimaKeyStore provider
,V/AlarmManager( 3528): waitForAlarm result :8
,I/art     ( 2884): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.083ms total 19.246ms
,D/ResourcesManager(11974): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,W/appmanager(:<default>):QuickExperimentControllerImpl(11874): Exposure of experiment com.facebook.imagepipeline.a.g@1d4b65ad occurred when no user was logged in
,W/appmanager(:<default>):QuickExperimentControllerImpl(11874): Exposure of experiment com.facebook.imagepipeline.a.d@3e07792e occurred when no user was logged in
,I/ActivityManager( 3528): Killing 11043:com.sec.android.provider.badge/u0a82 (adj 15): bgCount ##31
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,I/art     (11874): Explicit concurrent mark sweep GC freed 48021(2MB) AllocSpace objects, 6(96KB) LOS objects, 22% free, 27MB/35MB, paused 927us total 46.637ms
,W/appmanager(:<default>):m(11874): No feature status reporters found; is this dead code?
,E/Zygote  (11994): MountEmulatedStorage()
E/Zygote  (11994): v2
I/libpersona(11994): KNOX_SDCARD checking this for 1000
I/libpersona(11994): KNOX_SDCARD not a persona
,I/SELinux (11994): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3528): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=11994 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux (11994): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11994): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11994): TimaSignature is unavailable
,D/ActivityThread(11994): Added TimaKeyStore provider
,D/ResourcesManager(11994): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT(11994): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT(11994): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT(11994): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT(11994): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(11994): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12012): MountEmulatedStorage()
E/Zygote  (12012): v2
I/libpersona(12012): KNOX_SDCARD checking this for 10012
I/libpersona(12012): KNOX_SDCARD not a persona
I/SELinux (12012): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3528): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=12012 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (12012): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12012): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider(12012): TimaSignature is unavailable
D/ActivityThread(12012): Added TimaKeyStore provider
D/ResourcesManager(12012): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
I/ActivityManager( 3528): Killing 11059:com.sec.spp.push/u0a39 (adj 15): bgCount ##31
I/FOTA_Client(12012): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
I/FOTA_Client(12012): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
I/FOTA_Client(12012): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/Zygote  (12038): MountEmulatedStorage()
E/Zygote  (12038): v2
I/libpersona(12038): KNOX_SDCARD checking this for 10021
I/libpersona(12038): KNOX_SDCARD not a persona
I/SELinux (12038): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12038): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3528): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=12038 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
E/SELinux (12038): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3528): Killing 11078:com.sec.android.app.soundalive/u0a59 (adj 15): bgCount ##31
E/lowmemorykiller( 2826): Error writing /proc/11078/oom_score_adj; errno=22
D/TimaKeyStoreProvider(12038): TimaSignature is unavailable
D/ActivityThread(12038): Added TimaKeyStore provider
D/ResourcesManager(12038): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
I/KLMS-2.4.521: (12038): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Dec 16 04:59:00 GMT+01:00 2015
I/KLMS-2.4.521: (12038): KLMSAbstractReciever(): onReceive().END.
I/KLMS-2.4.521: (12038): KLMSIntentService(): onCreate()
I/KLMS-2.4.521: (12038): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.4.521: (12038): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
I/KLMS-2.4.521: (12038): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/KLMS-2.4.521: (12038): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
I/KLMS-2.4.521: (12038): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
I/KLMS-2.4.521: (12038): StateImplV2(): networkChangeListener().END
E/Zygote  (12055): MountEmulatedStorage()
E/Zygote  (12055): v2
I/libpersona(12055): KNOX_SDCARD checking this for 10038
I/libpersona(12055): KNOX_SDCARD not a persona
I/SELinux (12055): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3528): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=12055 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
I/SELinux (12055): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12055): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.4.521: (12038): KLMSIntentService(): onDestroy()
I/ActivityManager( 3528): Killing 10889:com.google.android.apps.docs/u0a101 (adj 15): bgCount ##31
D/TimaKeyStoreProvider(12055): TimaSignature is unavailable
D/ActivityThread(12055): Added TimaKeyStore provider
I/dhcpcd  (11966): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
D/ResourcesManager(12055): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
I/SO_AGENT(12055): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
I/dhcpcd  (11966): wlan0: leased 192.168.1.124 for 86400 seconds
E/WifiStateMachine( 3528): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3528): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
E/Zygote  (12073): MountEmulatedStorage()
E/Zygote  (12073): v2
I/libpersona(12073): KNOX_SDCARD checking this for 1000
I/libpersona(12073): KNOX_SDCARD not a persona
I/SELinux (12073): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3528): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=12073 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux (12073): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3528): Killing 11110:com.wsomacp/u0a28 (adj 15): bgCount ##31
E/SELinux (12073): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider(12073): TimaSignature is unavailable
D/ActivityThread(12073): Added TimaKeyStore provider
D/ResourcesManager(12073): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/Zygote  (12109): MountEmulatedStorage()
E/Zygote  (12109): v2
I/libpersona(12109): KNOX_SDCARD checking this for 10039
I/libpersona(12109): KNOX_SDCARD not a persona
I/SELinux (12109): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3528): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=12109 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (12109): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3528): Killing 11157:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##31
E/SELinux (12109): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider(12109): TimaSignature is unavailable
D/ActivityThread(12109): Added TimaKeyStore provider
D/ResourcesManager(12109): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
E/SPPClientService(12109): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(12109): [PushClientApplication] Push log off : This is Ship build version
E/SPPClientService(12109): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
D/SPPClientService(12109): PushLog.txt file is not deleted.
D/SPPClientService(12109): PushLog.txt file is not deleted.
D/SPPClientService(12109): ============PushLog. stop!
I/SA      (11200): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
I/SA      (11200): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      (11200): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      (11200): [SLFUCHKMGR] constructor called
E/SPPClientService(12109): [[SystemStateMonitorService]] No Active Internet
I/SA      (11200): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11200): [OR] == isSIMCardReady false ==
I/SA      (11200): [SCU] == networkStateCheck == false
I/SA      (11200): [OR] onReceive END
V/DownloadManager( 5727): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager( 3528): Killing 11090:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/Zygote  (12136): MountEmulatedStorage()
I/libpersona(12136): KNOX_SDCARD checking this for 10067
E/Zygote  (12136): v2
I/libpersona(12136): KNOX_SDCARD not a persona
I/SELinux (12136): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12136): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3528): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=12136 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux (12136): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider(12136): TimaSignature is unavailable
D/ActivityThread(12136): Added TimaKeyStore provider
D/ResourcesManager(12136): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
E/WifiStateMachine( 3528): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine( 3528): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  ( 3528): do suspend true
D/WifiP2pService( 3528): InactiveState{ what=143375 }
D/WifiP2pService( 3528): P2pEnabledState{ what=143375 }
E/WifiStateMachine( 3528): WifiStateMachine DHCP successful
E/WifiStateMachine( 3528): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3528): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine( 3528): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3528): Not connected state, yet.
E/WifiStateMachine( 3528): VerifyingLinkState enter
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiStateMachine( 3528): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine( 3528): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3528): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3528): callSECApiInt - ID [210]
,E/WifiStateMachine( 3528): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService( 3528): updateNetworkInfo()
,D/ConnectivityService( 3528): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 3528): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 3528): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 3528): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.DnsResolver( 3528): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 3528): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3528): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3528): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine( 3528): Now, connected state.
E/WifiStateMachine( 3528): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/WifiStateMachine( 3528): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/WifiTrafficPoller( 3528): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3528): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller( 3528): evaluateTrafficStatsPolling
D/WifiNative-HAL( 3528): callSECApiVoid - ID [212]
,D/ConnectivityService( 3528): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService( 3528): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService( 3528): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/WifiStateMachine( 3528): ConnectedState Enter  mScreenOn=false scanperiod=20000
I/WifiStateMachine( 3528): REQUEST_POWER_SAVE_ON
,E/ConnectivityService( 3528): Unexpected mtu value: 0, wlan0
,V/        ( 2846): QcRouteController
,D/StatusBar.NetworkController( 3694): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
,I/sCloudBackupApp(12136): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(12136): Other Intent
,I/ActivityManager( 3528): Killing 11180:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
,V/        ( 2846): QcRouteController
,D/accuweather( 5189): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,V/        ( 2846): QcRouteController
,D/daemonapp( 3776): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 7
,D/accuweather( 5189): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5189): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5189): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5189): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,V/        ( 2846): QcRouteController
,D/accuweather( 5189): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5189): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,V/        ( 2846): QcRouteController
,E/Zygote  (12165): MountEmulatedStorage()
E/Zygote  (12165): v2
I/libpersona(12165): KNOX_SDCARD checking this for 1000
I/libpersona(12165): KNOX_SDCARD not a persona
,I/SELinux (12165): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,V/        ( 2846): QcRouteController
,I/SELinux (12165): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,V/        ( 2846): QcRouteController
,I/ActivityManager( 3528): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=12165 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux (12165): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/        ( 2846): QcRouteController
,D/TimaKeyStoreProvider(12165): TimaSignature is unavailable
,D/ActivityThread(12165): Added TimaKeyStore provider
,D/ConnectivityService( 3528): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService( 3528): LTETest block dns file not exists
,D/ConnectivityService( 3528): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 3528): updateNetworkInfo()
E/ConnectivityService( 3528): updateNetworkInfo()
D/ConnectivityService( 3528): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 3528): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3528): rematching NetworkAgentInfo [WIFI () - 503]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3528): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3528): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3528): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3528): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService( 3528):    accepting network in place of null
,D/TelephonyNetworkFactory( 3983): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/System.out( 3528): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 503 for uid 1000
,E/CSLegacyTypeTracker( 3528): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 3528): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 3528): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService( 3528): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/Tethering( 3528): MasterInitialState.processMessage what=3
,D/SmartBondingService( 3528): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService( 3528): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3528): getSBEnabled() enabled =false
D/SmartBondingService( 3528): getSBEnabled() enabled =false
D/SmartBondingService( 3528): getSBEnabled() enabled =false
D/EntConnectivity( 3528): Not allowed due to - mEnabled false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3528): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3528): Validated
V/NetworkStats( 3528): updateIfacesLocked()
D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
V/NetworkStats( 3528): performPollLocked(flags=0x1)
D/ConnectivityService( 3528): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/SmartBondingService( 3528): getNetworkEnabled : wifi : true mobile : false
,D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
D/NetworkStatsFactory( 3528): UpdateStatsForKnox
,D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
V/NetworkStats( 3528): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/ResourcesManager(12165): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
,W/ResourcesManager(12165): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3694): updateDataNetType()
D/StatusBar.NetworkController( 3694): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3694): updateLTEICONDataNetType:0
,D/ConnectivityManager.CallbackHandler( 3694): CM callback handler got msg 524290
V/NetworkStats( 3528): performPollLocked() took 7ms
D/ConnectivityService( 3528): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3528): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3528): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 3528): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
,D/ConnectivityManager.CallbackHandler( 3694): CM callback handler got msg 524290
D/ConnectivityService( 3528): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 6682): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 6682): CM callback handler got msg 524290
,D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 3694): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3694): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
,D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3694): updateDataNetType()
D/StatusBar.NetworkController( 3694): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3694): updateLTEICONDataNetType:0
D/StatusBar.NetworkController( 3694): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3694): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:"NG700"
I/KnoxUsageLogPro(12165): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro(12165): premStatus:2
I/KnoxUsageLogPro(12165): isEulaShown : false
I/KnoxUsageLogPro(12165): KnoxUsageReceiver onReceive : not Processible, just return
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12186): MountEmulatedStorage()
E/Zygote  (12186): v2
I/libpersona(12186): KNOX_SDCARD checking this for 10090
I/libpersona(12186): KNOX_SDCARD not a persona
I/SELinux (12186): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12186): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3528): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=12186 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (12186): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3528): Killing 11132:com.sec.android.automotive.drivelink/u0a102 (adj 13): bgCount ##31
D/TimaKeyStoreProvider(12186): TimaSignature is unavailable
D/ActivityThread(12186): Added TimaKeyStore provider
,D/ResourcesManager(12186): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12202): MountEmulatedStorage()
E/Zygote  (12202): v2
I/libpersona(12202): KNOX_SDCARD checking this for 10127
I/libpersona(12202): KNOX_SDCARD not a persona
,I/SELinux (12202): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12202): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3528): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=12202 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (12202): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3528): Killing 11272:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12202): TimaSignature is unavailable
,D/ActivityThread(12202): Added TimaKeyStore provider
,D/ResourcesManager(12202): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,D/KeyguardWallpaperUpdator(12202): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12202): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12202): stopCheckCategoryVersion
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12222): MountEmulatedStorage()
,E/Zygote  (12222): v2
I/libpersona(12222): KNOX_SDCARD checking this for 10136
I/libpersona(12222): KNOX_SDCARD not a persona
,I/SELinux (12222): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3528): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=12222 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (12222): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3528): Killing 11289:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
E/SELinux (12222): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/art     ( 2884): Explicit concurrent mark sweep GC freed 8753(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 884us total 23.494ms
,D/TimaKeyStoreProvider(12222): TimaSignature is unavailable
,D/ActivityThread(12222): Added TimaKeyStore provider
,D/ResourcesManager(12222): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
I/art     ( 2884): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 842us total 18.477ms
,I/art     ( 2884): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 844us total 18.503ms
,D/ConnectivityService( 3528): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3528): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3528): SmartBondingReceiver: wifi is connected
D/SmartBondingService( 3528): SmartBondingReceiver: wifi ap is not changed
,D/SmartBondingService( 3528): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3528): getSBEnabled() enabled =false
,D/SmartBondingService( 3528): getSBEnabled() enabled =false
,D/SmartBondingService( 3528): getSBEnabled() enabled =false
,D/SmartBondingService( 3528): getNetworkEnabled : wifi : true mobile : false
,I/DBG_DM  ( 6269): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 6269): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/NetworkMonitor(11930): type=WIFI subType= reason=null isConnected=true
,W/ResourceType( 5317): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
,W/ResourceType( 5317): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12222): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12222): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/GpsLocationProvider( 3528): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12222): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12222): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/SecContentProvider2( 3528): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3528): mCursor = null
,I/WebViewFactory(12222): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(12222): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(12222): Loading: webviewchromium
,I/LibraryLoader(12222): Time to load native libraries: 4 ms (timestamps 1489-1493)
I/LibraryLoader(12222): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(12222): Binding Chromium to main looper Looper (main, tid 1) {deb644c}
,I/LibraryLoader(12222): Expected native library version number "",actual native library version number ""
,I/chromium(12222): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(12222): Initializing chromium process, renderers=0
,W/art     (12222): Attempt to remove local handle scope entry from IRT, ignoring
,W/AudioManagerAndroid(12222): Requires BLUETOOTH permission
,W/chromium(12222): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(12222): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium(12222): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,I/NSApplication(12222): Starting up...
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12295): MountEmulatedStorage()
E/Zygote  (12295): v2
I/libpersona(12295): KNOX_SDCARD checking this for 10150
I/libpersona(12295): KNOX_SDCARD not a persona
,I/SELinux (12295): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12295): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3528): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=12295 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,E/SELinux (12295): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3528): Killing 11257:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12295): TimaSignature is unavailable
,D/ActivityThread(12295): Added TimaKeyStore provider
,D/ResourcesManager(12295): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(12295): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(12295): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12295): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect(12295): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12295): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,D/ConnectivityService( 3528): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/QuickConnect(12295): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12310): MountEmulatedStorage()
E/Zygote  (12310): v2
I/libpersona(12310): KNOX_SDCARD checking this for 10178
I/libpersona(12310): KNOX_SDCARD not a persona
,I/SELinux (12310): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12310): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3528): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=12310 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,E/SELinux (12310): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3528): Killing 11307:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12310): TimaSignature is unavailable
,D/ActivityThread(12310): Added TimaKeyStore provider
,D/ResourcesManager(12310): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(12310): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager(12310): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12310): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12310): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12310): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,W/ResourcesManager(12310): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService( 3528): exchangeData() failure , invalid userId
,D/RCPManagerService( 3528): exchangeData() failure , invalid userId
,D/RCPManagerService( 3528): exchangeData() failure , invalid userId
,D/RCPManagerService( 3528): exchangeData() failure , invalid userId
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 3528): exchangeData() failure , invalid userId
,D/RCPManagerService( 3528): exchangeData() failure , invalid userId
,E/Zygote  (12333): MountEmulatedStorage()
E/Zygote  (12333): v2
I/libpersona(12333): KNOX_SDCARD checking this for 10082
I/libpersona(12333): KNOX_SDCARD not a persona
,I/SELinux (12333): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12333): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12333): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3528): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=12333 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12349): MountEmulatedStorage()
E/Zygote  (12349): v2
I/libpersona(12349): KNOX_SDCARD checking this for 1000
I/libpersona(12349): KNOX_SDCARD not a persona
,I/SELinux (12349): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/TimaKeyStoreProvider(12333): TimaSignature is unavailable
,D/ActivityThread(12333): Added TimaKeyStore provider
,I/ActivityManager( 3528): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=12349 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux (12349): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3528): Killing 11323:com.samsung.helphub/1000 (adj 13): bgCount ##31
,E/SELinux (12349): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3528): Killing 11431:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12349): TimaSignature is unavailable
,D/ActivityThread(12349): Added TimaKeyStore provider
,D/ResourcesManager(12333): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/ResourcesManager(12349): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/BadgeProvider(12333): onCreate
D/BadgeProvider(12333): DatabaseHelper
,W/ActivityManager( 3528): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/ActivityManager( 3528): Killing 11448:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
,D/BadgeProvider(12333): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider(12333): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12333): sendNotify, [notify] : null
D/BadgeProvider(12333): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12333): update, [BadgeCount] : badgecount=0
D/BadgeProvider(12333): update, [UpdateCount] : 1
,D/Launcher.Model( 4004): reloadBadges entered.
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12366): MountEmulatedStorage()
,E/Zygote  (12366): v2
I/libpersona(12366): KNOX_SDCARD checking this for 10013
I/libpersona(12366): KNOX_SDCARD not a persona
,I/SELinux (12366): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12366): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3528): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=12366 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,E/SELinux (12366): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12366): TimaSignature is unavailable
,D/ActivityThread(12366): Added TimaKeyStore provider
,D/ResourcesManager(12366): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,D/WaitQueueForNetworkActivate(12366): notifyNetworkActivated
,W/ContextImpl(12366): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
I/jxcore-log(11750): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log(11750): 
,W/ActivityManager( 3528): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/hcjo    (12366): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12366): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12366): exit::IDLE
D/InitializeManagerStateMachine(12366): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12366): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12366): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12366): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12366): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12366): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12366): entry::SUCCESS
D/hcjo    (12366): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (12366): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12366): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine(12366): exit::SUCCESS
D/InitializeManagerStateMachine(12366): entry::IDLE
,I/Hs20UtilService( 4103): Starting #10
,I/Hs20UtilService( 4103): Message received 5007
,D/NearbySettings( 8926): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8926): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8926): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 8926): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8926): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8926): MountReceiver.onReceive - Keep current state
,I/ActivityManager( 3528): Killing 11466:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##31
,I/SignOutReceiver(11408): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4103): Starting #11
,I/Hs20UtilService( 4103): Message received 5007
,D/NearbySettings( 8926): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8926): MountReceiver.onReceive - Keep current state
,I/SignOutReceiver(11408): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4103): Starting #12
,I/Hs20UtilService( 4103): Message received 5007
,D/NearbySettings( 8926): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8926): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8926): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 8926): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8926): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8926): MountReceiver.onReceive - Keep current state
E/WifiStateMachine( 3528): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3528): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityService( 3528): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,V/        ( 2846): QcRouteController
,D/SmartBondingService( 3528): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
D/SmartBondingService( 3528): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3528): getSBEnabled() enabled =false
D/SmartBondingService( 3528): getSBEnabled() enabled =false
D/SmartBondingService( 3528): getSBEnabled() enabled =false
,I/SignOutReceiver(11408): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2846): QcRouteController
,W/NetworkManagementService( 3528): route cmd failed: 
W/NetworkManagementService( 3528): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '76 route replace src v6 wlan0 fe80::92b6:86ff:fe43:731c 2 ::' failed with '400 76 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService( 3528): '
W/NetworkManagementService( 3528): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService( 3528): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService( 3528): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService( 3528): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService( 3528): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService( 3528): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5738)
W/NetworkManagementService( 3528): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5545)
W/NetworkManagementService( 3528): 	at com.android.server.ConnectivityService.access$2600(ConnectivityService.java:231)
W/NetworkManagementService( 3528): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2436)
W/NetworkManagementService( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/ConnectivityService( 3528): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3694): CM callback handler got msg 524295
,I/Hs20UtilService( 4103): Starting #13
,D/ConnectivityService( 3528): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3694): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 6682): CM callback handler got msg 524295
,D/NearbySettings( 8926): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8926): MountReceiver.onReceive - Keep current state
,D/ConnectivityManager.CallbackHandler( 6682): CM callback handler got msg 524295
,I/Hs20UtilService( 4103): Message received 5007
,I/WifiStateMachine( 3528): callSECApi what=220
D/WifiStateMachine( 3528): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/SignOutReceiver(11408): NETWORK_STATE_CHANGED_ACTION
,I/PCWCLIENTTRACE_PushUtil(11908): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11908): sales region : global
I/PCWCLIENTTRACE_PushUtil(11908): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11908): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/SurfaceFlinger( 2850): id=15 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 3528): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3528
,D/mali_winsys( 3694): new_window_surface returns 0x3000,  [1120x201]-format:1
,I/DIAGMON_AGENT(11994): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(11994): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/FOTA_Client(12012): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(12012): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(12012): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.521: (12038): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Dec 16 04:59:03 GMT+01:00 2015
,I/KLMS-2.4.521: (12038): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (12038): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12038): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (12038): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (12038): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12038): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (12038): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.521: (12038): StateImplV2(): networkChangeListener().START
,I/SO_AGENT(12055): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,I/KLMS-2.4.521: (12038): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.521: (12038): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.4.521: (12038): StateImplV2(): networkChangeListener().END
,I/KLMS-2.4.521: (12038): KLMSIntentService(): onDestroy()
,E/SPPClientService(12109): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      (11200): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
I/SA      (11200): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (11200): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (11200): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11200): [OR] == isSIMCardReady false ==
,I/SA      (11200): [SCU] == networkStateCheck == true
I/SA      (11200): [DM] getCountryCodeFromCSC : PL
I/SA      (11200): isChinaCountryCode : false
I/SA      (11200): [SCU] is ChinestModel Data Restricted   : false
I/SA      (11200): [OR] == networkStateCheck true ==
,I/SA      (11200): [OR] GetMyCountryZoneTask
,I/SA      (11200): [OR] onReceive END
,I/SA      (11200): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 5727): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      (11200): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (11200): [SSP] query invoked
,I/SCloudBackupReceiver(12136): Other Intent
,I/SA      (11200): [TPMU] GetMccFromDB : null
,I/SA      (11200): [SCU] getMccFromPreferece mcc = 260
D/accuweather( 5189): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/SA      (11200): [TPM] isNoProxy(default) : true
,D/daemonapp( 3776): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 7
,D/accuweather( 5189): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5189): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
,D/accuweather( 5189): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5189): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5189): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5189): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro(12165): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro(12165): premStatus:2
,I/KnoxUsageLogPro(12165): isEulaShown : false
I/KnoxUsageLogPro(12165): KnoxUsageReceiver onReceive : not Processible, just return
,D/KeyguardWallpaperUpdator(12202): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12202): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12202): stopCheckCategoryVersion
,D/QuickConnect(12295): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12295): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect(12295): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 3528): exchangeData() failure , invalid userId
,D/RCPManagerService( 3528): exchangeData() failure , invalid userId
,D/hcjo    (12366): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12366): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12366): exit::IDLE
D/InitializeManagerStateMachine(12366): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12366): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12366): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12366): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12366): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12366): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12366): entry::SUCCESS
D/hcjo    (12366): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (12366): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12366): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine(12366): exit::SUCCESS
D/InitializeManagerStateMachine(12366): entry::IDLE
,I/SA      (11200): [RC New] Execute method=[GET] start
,I/SA      (11200): [RC New] Security=[true]
,I/System.out(11200): Thread-1550(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out(11200): Thread-1550(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11200): Thread-1550(ApacheHTTPLog):isShipBuild true
I/System.out(11200): Thread-1550(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 503 for uid 10045
,I/dhcpcd  (11966): wlan0: sending IPv6 Router Solicitation
,I/SA      (11200): [RC New] [v2liruge] api execute + 705,
,I/WifiStateMachine( 3528): REQUEST_POWER_SAVE_ON
,D/SSRM:n  ( 3528): SIOP:: AP = 270, PST = 270, CUR = 51
,I/SA      (11200): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out(11200): AsyncTask #1 calls detatch()
,I/SA      (11200): [TPMU] getNetworkMcc : 
,I/SA      (11200): [SCU] saveMccToPreferece Start
I/SA      (11200): [SCU] RegionMCC : 260
I/SA      (11200): [SSP] query invoked
,I/SA      (11200): [TPMU] GetMccFromDB : null
I/SA      (11200): [SCU] getMccFromPreferece mcc = 260
I/SA      (11200): [SCU] saveMccToPreferece End
,I/SA      (11200): [RC New] executeRequest [v2liruge] end. 778
I/SA      (11200): [RC New] Execute end
I/SA      (11200): [OR] GetMyCountryZoneTask mcc = 260
I/SA      (11200): [OR] GetMyCountryZoneTask Success
,E/WifiStateMachine( 3528): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/PowerManagerService( 3528): [PWL] Off : 50s ago
,D/WearableService( 4615): callingUid 10014, callindPid: 4615
,D/ResourcesManager(11930): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11930): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11930): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:70
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,I/GHttpClientFactory(11930): Using the GMSCore's GoogleHttpClient
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MusicLeanback(11930): Conditions not met for autocaching.
I/MusicLeanback(11930): Stop autocaching.
,D/WearableClient(11930): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11930): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11930): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11930): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(11930): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils(11930): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/ActivityThread(11930): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@3b443d0c that was originally bound here
E/ActivityThread(11930): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@3b443d0c that was originally bound here
E/ActivityThread(11930): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(11930): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(11930): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(11930): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(11930): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(11930): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(11930): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11930): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11930): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11930): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(11930): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(11930): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(11930): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(11930): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(11930): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(11930): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(11930): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(11930): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(11930): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(11930): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(11930): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(11930): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(11930): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(11930): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(11930): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/PackageManager( 3528): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/SurfaceFlinger( 2850): id=15 Removed Uoast (8/9)
I/SurfaceFlinger( 2850): id=15 Removed Uoast (-2/9)
,D/PowerManagerService( 3528): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3528) eventTime = 146179
,D/PowerManagerService( 3528): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3528 (0x0)
D/PowerManagerService( 3528): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3528, ws=WorkSource{10060}) (elapsedTime=3496)
,I/art     ( 3528): Explicit concurrent mark sweep GC freed 51468(3MB) AllocSpace objects, 7(112KB) LOS objects, 24% free, 48MB/64MB, paused 4.167ms total 175.114ms
,I/GAV4    (12222): Thread[GAThread,5,main]: No campaign data found.
,I/dhcpcd  (11966): wlan0: sending IPv6 Router Solicitation
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PCWCLIENTTRACE_SYSTEMReceiver(11908): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil(11908): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE(11908): ================================================
,I/CSTORAGE(11908):  CSTORAGE_SKM_LIB v1.0.15
I/CSTORAGE(11908): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI(11908): [GetString-S]
,E/art     (11908): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI(11908): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,I/PCWCLIENTTRACE_SecurePreferencesJNI(11908): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil(11908): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil(11908): sales region : global
I/PCWCLIENTTRACE_PushUtil(11908): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler(11908): [ensureRegistration] - No Samsung account
,I/dhcpcd  (11966): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  (11966): wlan0: no IPv6 Routers available
,D/PreloadUpdateManagerStateMachine(12366): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(12366): exit::IDLE
D/PreloadUpdateManagerStateMachine(12366): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (12366): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    (12366): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine(12366): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine(12366): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine(12366): entry::IDLE
,D/PreloadUpdateManagerStateMachine(12366): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(12366): exit::IDLE
D/PreloadUpdateManagerStateMachine(12366): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (12366): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine(12366): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine(12366): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine(12366): entry::IDLE
,D/SSRM:n  ( 3528): SIOP:: AP = 260, PST = 267, CUR = 28
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:45, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:52
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ActivityManager( 3528): Waited long enough for: ServiceRecord{362009ab u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService},
,E/Watchdog( 3528): !@Sync 5
,D/SSRM:n  ( 3528): SIOP:: AP = 250, PST = 265, CUR = 45
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:48, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:45
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3528): [PWL] Off : 75s ago
,D/SSRM:n  ( 3528): SIOP:: AP = 250, PST = 264, CUR = 48
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:47, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:46
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/art     ( 4615): Explicit concurrent mark sweep GC freed 60814(3MB) AllocSpace objects, 44(2MB) LOS objects, 34% free, 30MB/46MB, paused 1.882ms total 65.203ms
,I/ClearcutLoggerApiImpl( 4615): disconnect managed GoogleApiClient
,D/SSRM:n  ( 3528): SIOP:: AP = 250, PST = 263, CUR = 47
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:43, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3528): !@Sync 6
,D/SSRM:n  ( 3528): SIOP:: AP = 250, PST = 261, CUR = 43
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:40, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2874): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3528): [PWL] Off : 105s ago
,D/SSRM:n  ( 3528): SIOP:: AP = 240, PST = 256, CUR = 40
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:38, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3528): SIOP:: AP = 240, PST = 254, CUR = 38
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:36, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:52
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3528): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3694): handleTimeUpdate
,D/KeyguardEffectViewController( 3694): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3694): *** don't update sliding image ***
,D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/Watchdog( 3528): !@Sync 7
,D/SSRM:n  ( 3528): SIOP:: AP = 240, PST = 253, CUR = 36
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:36, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 3528): [PWL] Off : 140s ago
,D/SSRM:n  ( 3528): SIOP:: AP = 240, PST = 250, CUR = 36,
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:34, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 240, PST = 249, CUR = 34
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3528): !@Sync 8
,D/SSRM:n  ( 3528): SIOP:: AP = 240, PST = 248, CUR = 32
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2874): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,V/AlarmManager( 3528): waitForAlarm result :8
,D/SSRM:n  ( 3528): SIOP:: AP = 240, PST = 247, CUR = 31
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3528): [PWL] Off : 180s ago
,D/SSRM:n  ( 3528): SIOP:: AP = 240, PST = 245, CUR = 28
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,I/jxcore-log(11750): Connected to the server!
I/jxcore-log(11750): 
,I/chromium(11750): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,E/Watchdog( 3528): !@Sync 9
,D/SSRM:n  ( 3528): SIOP:: AP = 240, PST = 244, CUR = 28
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3528): stay LED for fully charged
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3528): SIOP:: AP = 240, PST = 243, CUR = 27
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 240, PST = 242, CUR = 28
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService( 3528): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3528): TimaServiceHandler.handleMessage what =1
,D/TimaService( 3528): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize( 3528): initializing...
,I/TLC_TIMA_PKM_initialize( 3528): root = 0, root_strlen = 1
I/TLC_TIMA_PKM_initialize( 3528): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 3528): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 3528): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 3528): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 3528): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 3528): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 3528): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 3528): device_id = 0x0
I/TZ: mc_tlc_communication( 3528): tlc_open() was called
,I/TZ: mc_tlc_communication( 3528): Opening MobiCore device
,I/TZ: mc_tlc_communication( 3528): Allocating WSM for TCI
,I/TZ: mc_tlc_communication( 3528): Opening the session
,I/TZ: mc_tlc_communication( 3528): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 3528): Trustlet response is completed
,E/Watchdog( 3528): !@Sync 10
,D/SSRM:n  ( 3528): SIOP:: AP = 240, PST = 241, CUR = 28
,I/TLC_TIMA_PKM_measure_kernel( 3528): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3528): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,W/ProcessCpuTracker( 3528): Skipping unknown process pid 12700
,D/TimaService( 3528): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3528): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
D/BatteryService( 3528): stay LED for fully charged
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2874): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3528): [PWL] Off : 225s ago
,D/SSRM:n  ( 3528): SIOP:: AP = 240, PST = 241, CUR = 27
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3528): SIOP:: AP = 240, PST = 240, CUR = 26
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 11
,D/SSRM:n  ( 3528): SIOP:: AP = 240, PST = 240, CUR = 24
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:34
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3528): SIOP:: AP = 240, PST = 240, CUR = 26
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 239, CUR = 25
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3528): [PWL] Off : 275s ago
,E/Watchdog( 3528): !@Sync 12
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 239, CUR = 24,
,I/MMD     ( 2874): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3528): stay LED for fully charged
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 238, CUR = 24
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 237, CUR = 23
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 13,
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 237, CUR = 24
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 236, CUR = 22
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3528): [PWL] Off : 330s ago
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 236, CUR = 21
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3528): !@Sync 14
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 235, CUR = 19
,I/MMD     ( 2874): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3528): waitForAlarm result :8
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 235, CUR = 21
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 235, CUR = 20
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 15
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 234, CUR = 18
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 234, CUR = 22
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged,
I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3528): [PWL] Off : 390s ago
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 233, CUR = 21
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3528): !@Sync 16
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 233, CUR = 21
,I/MMD     ( 2874): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 233, CUR = 20,
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 232, CUR = 19
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3528): !@Sync 17
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 232, CUR = 19
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 232, CUR = 19
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 231, CUR = 17
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 3528): [PWL] Off : 455s ago
,E/Watchdog( 3528): !@Sync 18
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 231, CUR = 17
,I/MMD     ( 2874): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 231, CUR = 17
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 18
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 19
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 17
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 15
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 16
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0,
D/BatteryService( 3528): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 3528): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3528): TIMA: checkEvent, operation: 50000 subject: 10000,
,D/TimaService( 3528): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 3528): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 3528): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3528): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3528): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3528): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 16
,I/MMD     ( 2874): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3528): [PWL] Off : 525s ago
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 17
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ActivityManager( 3528): Killing 11515:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 15,
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 21
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 16
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 16,
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 17,
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 22
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 16
,I/MMD     ( 2874): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 15
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3528): [PWL] Off : 600s ago
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 15
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3528): !@Sync 23
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 15
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 15
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 24
,V/AlarmManager( 3528): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3694): handleTimeUpdate
,D/KeyguardEffectViewController( 3694): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3694): *** don't update sliding image ***
,D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 4615): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4615): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/art     (11356): Attempt to remove local handle scope entry from IRT, ignoring
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 503 for uid 10147
,V/GLSActivity( 4615): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4615): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/AclDataUtils(11356): Circle ID not found for type: 9
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 15
,I/MMD     ( 2874): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,V/AlarmManager( 3528): waitForAlarm result :8
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 14
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 13
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 25
,V/AlarmManager( 3528): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3694): handleTimeUpdate
,D/KeyguardEffectViewController( 3694): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3694): *** don't update sliding image ***
,D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 14
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3528): [PWL] Off : 680s ago
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 14
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 15
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-2
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3528): waitForAlarm result :4
,D/LightsService( 3528): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,I/Sensors ( 3528): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager( 3528): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,I/EventLogService( 6682): Aggregate from 1450237171743 (log), 1450237171743 (data)
,E/Watchdog( 3528): !@Sync 26
,I/Sensors ( 3528): #>LightSensor r=0 g=0 b=1 c=2 atime=238 again=64 lux=0.000000
,D/LightsService( 3528): [SvcLED]  onSensorChanged::light value = 0
I/Sensors ( 3528): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager( 3528): unregisterListener ::   
D/LightsService( 3528): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 13
,I/MMD     ( 2874): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,V/AlarmManager( 3528): waitForAlarm result :8
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-9
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-3
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 27
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 14
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 28
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 11
,I/MMD     ( 2874): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3528): [PWL] Off : 765s ago
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 29
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 11
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 12
,V/AlarmManager( 3528): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3694): handleTimeUpdate
,D/KeyguardEffectViewController( 3694): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3694): *** don't update sliding image ***
,D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,D/BatteryService( 3528): stay LED for fully charged
I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 13
,D/TimaService( 3528): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3528): TIMA: checkEvent, operation: 50000 subject: 10000,
,D/TimaService( 3528): TimaServiceHandler.handleMessage what =1
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 3528): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3528): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3528): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3528): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 12
,I/MMD     ( 2874): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,V/AlarmManager( 3528): waitForAlarm result :8
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 11
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 11
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 31
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 12
,I/PowerManagerService( 3528): [PWL] Off : 855s ago
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 11
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-5
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 32
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 10
,I/MMD     ( 2874): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 11
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3528): !@Sync 33
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-5
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 10,
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 11
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 34
,I/MMD     ( 2874): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 11
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3528): [PWL] Off : 950s ago,
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 35
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 11
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 10
,E/Watchdog( 3528): !@Sync 36
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2874): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 9
,E/Watchdog( 3528): !@Sync 37
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-3
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/BatteryService( 3528): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 9,
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3528): [PWL] Off : 1050s ago
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 7
,E/Watchdog( 3528): !@Sync 38
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2874): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 8
,E/Watchdog( 3528): !@Sync 39
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-2
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 9,
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 10
,D/TimaService( 3528): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3528): TIMA: checkEvent, operation: 50000 subject: 10000,
D/TimaService( 3528): TimaServiceHandler.handleMessage what =1,
,I/UsageStatsService( 3528): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 3528): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 3528): Updating Usage Statistics in DB @ 1450239412070
,I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory),' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/Sy,stem.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
,W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	,at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
,W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
,W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): ,	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
,W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
,W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
,W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
,W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
,W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
,W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
,W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage( 3528): Done Updating Usage Statistics in DB @ 1450239412118
,E/Watchdog( 3528): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 3528): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3528): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3528): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3528): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2874): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3528): stay LED for fully charged
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 9,
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 8
,E/Watchdog( 3528): !@Sync 41
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 8
,I/PowerManagerService( 3528): [PWL] Off : 1155s ago
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 7,
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 8
,E/Watchdog( 3528): !@Sync 42
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2874): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.,
,I/MotionRecognitionService( 3528): Plugged
I/MotionRecognitionService( 3528): setPowerConnected  = true
D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 9
,E/Watchdog( 3528): !@Sync 43
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 7,
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 8
,E/Watchdog( 3528): !@Sync 44
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2874): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 8,
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 8
,I/PowerManagerService( 3528): [PWL] Off : 1265s ago
,E/Watchdog( 3528): !@Sync 45
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 5
,I/art     ( 3528): Background sticky concurrent mark sweep GC freed 94383(9MB) AllocSpace objects, 373(5MB) LOS objects, 13% free, 49MB/57MB, paused 5.324ms total 99.699ms
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 5,
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-8
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 6
,E/Watchdog( 3528): !@Sync 46
,I/MMD     ( 2874): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-7
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 7
,E/Watchdog( 3528): !@Sync 47
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 5
,E/Watchdog( 3528): !@Sync 48
,I/MMD     ( 2874): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
I/MotionRecognitionService( 3528): setPowerConnected  = true
D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 7
,I/PowerManagerService( 3528): [PWL] Off : 1380s ago
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 6
,E/Watchdog( 3528): !@Sync 49
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 7
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/TimaService( 3528): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3528): TIMA: checkEvent, operation: 50000 subject: 10000,
,D/TimaService( 3528): TimaServiceHandler.handleMessage what =1,
,V/AlarmManager( 3528): waitForAlarm result :8
,D/LightsService( 3528): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3694): handleTimeUpdate
,D/KeyguardEffectViewController( 3694): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3694): *** don't update sliding image ***
,I/Sensors ( 3528): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager( 3528): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/Watchdog( 3528): !@Sync 50
,I/Sensors ( 3528): #>LightSensor r=0 g=0 b=1 c=2 atime=238 again=64 lux=0.000000
,D/LightsService( 3528): [SvcLED]  onSensorChanged::light value = 0
I/Sensors ( 3528): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager( 3528): unregisterListener ::   
D/LightsService( 3528): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/TLC_TIMA_PKM_measure_kernel( 3528): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3528): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3528): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3528): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/MMD     ( 2874): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3528): waitForAlarm result :8
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/BatteryService( 3528): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-9
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 51
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-9
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 52
,I/MMD     ( 2874): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 3528): [PWL] Off : 1500s ago
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3528): !@Sync 53
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 5,
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:4, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 4
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-5
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3528): !@Sync 54
,I/MMD     ( 2874): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-10
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 5,
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 55
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-7
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 5,
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 56
,I/MMD     ( 2874): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 5,
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:4, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,I/PowerManagerService( 3528): [PWL] Off : 1625s ago
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 57
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 4
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 4
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-2
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:4, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 58
,I/MMD     ( 2874): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 4
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-1
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 59
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
V/AlarmManager( 3528): waitForAlarm result :4
D/BatteryService( 3528): online:4, current avg:2, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-7
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/NetworkStatsFactory( 3528): UpdateStatsForKnox
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 3694): handleTimeUpdate
,D/KeyguardEffectViewController( 3694): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3694): *** don't update sliding image ***
,D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
I/GoogleURLConnFactory( 4615): Using platform SSLCertificateSocketFactory
,V/AlarmManager( 3528): OOI=Alarm{3b1b694b type 0 when 1450241800662 com.google.android.gms}
,D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/PhenotypeConfigurator( 4615): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,I/System.out( 4615): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 503 for uid 10014
,I/System.out( 4615): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 4615): Tagging socket 66 with tag 1000120300000000{268440067,0} uid -1, pid: 4615, getuid(): 10014
,I/qtaguid ( 4615): Tagging socket 70 with tag 1000120300000000{268440067,0} uid -1, pid: 4615, getuid(): 10014
,W/PhenotypeConfigurator( 4615): Server returned 404
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 2
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:4, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
D/BatteryService( 3528): stay LED for fully charged
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 3528): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3528): TIMA: checkEvent, operation: 50000 subject: 10000,
,D/TimaService( 3528): TimaServiceHandler.handleMessage what =1,
,E/Watchdog( 3528): !@Sync 60
,I/TLC_TIMA_PKM_measure_kernel( 3528): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3528): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3528): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3528): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/MMD     ( 2874): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 4
,V/AlarmManager( 3528): waitForAlarm result :8
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 6,
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 61
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 6
,I/PowerManagerService( 3528): [PWL] Off : 1755s ago
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:4, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 4
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:3, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,D/BatteryService( 3528): stay LED for fully charged
I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 3
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:4, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 62
,I/MMD     ( 2874): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 4
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:4, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 4
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:4, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-20
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 4
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 63
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:4, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 4
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:4, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 64
,I/MMD     ( 2874): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 4
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:3, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-13
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 3
,TIME-OUT KILL (timeout was 1800000ms),D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 3528): Plugged
I/MotionRecognitionService( 3528): setPowerConnected  = true
D/BatteryService( 3528): stay LED for fully charged
D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5626): Disconnected process message: 10
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AndroidRuntime(13850): 
D/AndroidRuntime(13850): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(13850): CheckJNI is OFF
D/AndroidRuntime(13850): readGMSProperty: start
D/AndroidRuntime(13850): readGMSProperty: already setted!!
D/AndroidRuntime(13850): readGMSProperty: end
D/AndroidRuntime(13850): addProductProperty: start
E/AffinityControl(13850): AffinityControl: registerfunction enter
D/AndroidRuntime(13850): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 3528): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 3528): START PACKAGE DELETE: observer{52980544}
D/PackageManager( 3528): pkg{<packageName>}
D/PackageManager( 3528): user{0}
D/PackageManager( 3528): caller{2000}
D/PackageManager( 3528): flags{3}
D/PersonaManagerService( 3528): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3528): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3528): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 3528): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3528): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 3528): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 3528): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 3528): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3528): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 3528): !@killApplicatoin: 10504, uninstall pkg
I/ActivityManager( 3528): Force stopping com.test.thalitest appid=10504 user=-1: uninstall pkg
I/ActivityManager( 3528): Killing 11750:com.test.thalitest/u0a504 (adj 0): stop com.test.thalitest
I/ActivityManager( 3528): Killing 11200:com.osp.app.signin/u0a45 (adj 13): empty for 1810s
I/ActivityManager( 3528): Killing 12073:com.policydm/1000 (adj 13): empty for 1810s
I/ActivityManager( 3528): Killing 12055:com.sec.android.soagent/u0a38 (adj 13): empty for 1810s
I/ActivityManager( 3528): Killing 12038:com.samsung.klmsagent/u0a21 (adj 13): empty for 1810s
I/ActivityManager( 3528): Killing 12012:com.sec.android.fotaclient/u0a12 (adj 13): empty for 1810s
I/ActivityManager( 3528): Killing 11994:com.sec.android.diagmonagent/1000 (adj 13): empty for 1810s
I/ActivityManager( 3528): Killing 11974:com.sec.android.cloudagent/u0a2 (adj 13): empty for 1810s
I/ActivityManager( 3528): Killing 11908:com.sec.pcw.device/1000 (adj 13): empty for 1810s
I/ActivityManager( 3528): Killing 11408:com.samsung.android.snote/u0a160 (adj 15): empty for 1810s
I/ActivityManager( 3528): Killing 8926:com.android.settings/1000 (adj 15): empty for 1810s
I/ActivityManager( 3528): Killing 12333:com.sec.android.provider.badge/u0a82 (adj 15): empty for 1811s
I/ActivityManager( 3528): Killing 11639:com.android.vending/u0a31 (adj 15): empty for 1839s
I/ActivityManager( 3528): Killing 10818:com.android.defcontainer/u0a5 (adj 15): empty for 1844s
I/ActivityManager( 3528): Killing 11496:com.sec.android.widgetapp.locationwidget/u0a22 (adj 15): empty for 1852s
I/ActivityManager( 3528): Killing 11531:com.android.calendar/u0a164 (adj 15): empty for 1852s
I/ActivityManager( 3528):   Force finishing activity ActivityRecord{2e4b8d41 u0 com.test.thalitest/.MainActivity t26}
W/ActivityManager( 3528): mDVFSHelper.acquire()
W/PackageSettings( 3528): Skipping PackageSetting{1ea739b7 com.example.hello/10500} due to missing metadata
I/WindowState( 3528): WIN DEATH: Window{2c875c0f u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 3528): Client connection lost with reason: 4
I/SurfaceFlinger( 2850): id=14 Removed NainActivit (5/8)
I/SurfaceFlinger( 2850): id=14 Removed NainActivit (-2/8)
D/WifiService( 3528): Client connection lost with reason: 4
D/PointerIcon( 3528): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3528): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3528): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3528): setHoveringSpenCustomIcon IconType is same.1
W/libprocessgroup( 3528): failed to open /acct/uid_10002/pid_11974/cgroup.procs: No such file or directory
W/libprocessgroup( 3528): failed to open /acct/uid_10005/pid_10818/cgroup.procs: No such file or directory
W/libprocessgroup( 3528): failed to open /acct/uid_10082/pid_12333/cgroup.procs: No such file or directory
W/libprocessgroup( 3528): failed to open /acct/uid_10160/pid_11408/cgroup.procs: No such file or directory
W/libprocessgroup( 3528): failed to open /acct/uid_1000/pid_8926/cgroup.procs: No such file or directory
W/libprocessgroup( 3528): failed to open /acct/uid_10012/pid_12012/cgroup.procs: No such file or directory
W/libprocessgroup( 3528): failed to open /acct/uid_1000/pid_11994/cgroup.procs: No such file or directory
I/ActivityManager( 3528): Force stopping com.test.thalitest appid=10504 user=0: pkg removed
I/ActivityManager( 3528):   Force finishing activity ActivityRecord{2e4b8d41 u0 com.test.thalitest/.MainActivity t26 f}
W/ActivityManager( 3528): Duplicate finish request for ActivityRecord{2e4b8d41 u0 com.test.thalitest/.MainActivity t26 f}
W/libprocessgroup( 3528): failed to open /acct/uid_10022/pid_11496/cgroup.procs: No such file or directory
W/libprocessgroup( 3528): failed to open /acct/uid_10031/pid_11639/cgroup.procs: No such file or directory
I/art     ( 3528): Background partial concurrent mark sweep GC freed 54007(5MB) AllocSpace objects, 179(2MB) LOS objects, 24% free, 49MB/65MB, paused 5.296ms total 210.726ms
I/art     ( 3528): WaitForGcToComplete blocked for 35.219ms for cause Explicit
I/art     ( 8978): Explicit concurrent mark sweep GC freed 29254(1641KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.165ms total 39.975ms
I/DBG_DM  ( 6269): [com.wssyncmldm.ui.XUIInstallConfirmActivity(456/onResume)] 
I/art     ( 4058): Explicit concurrent mark sweep GC freed 30949(1926KB) AllocSpace objects, 0(0B) LOS objects, 21% free, 28MB/36MB, paused 1.360ms total 66.484ms
I/art     ( 6682): Explicit concurrent mark sweep GC freed 4754(197KB) AllocSpace objects, 0(0B) LOS objects, 20% free, 31MB/39MB, paused 1.432ms total 68.173ms
W/libprocessgroup( 3528): failed to open /acct/uid_1000/pid_11908/cgroup.procs: No such file or directory
I/DBG_DM  ( 6269): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 8
I/ProcessStatsService( 3528): Prepared write state in 19ms
W/libprocessgroup( 3528): failed to open /acct/uid_10038/pid_12055/cgroup.procs: No such file or directory
W/libprocessgroup( 3528): failed to open /acct/uid_1000/pid_12073/cgroup.procs: No such file or directory
W/libprocessgroup( 3528): failed to open /acct/uid_10045/pid_11200/cgroup.procs: No such file or directory
W/libprocessgroup( 3528): failed to open /acct/uid_10021/pid_12038/cgroup.procs: No such file or directory
I/DBG_DM  ( 6269): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
I/DBG_DM  ( 6269): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 6269): [com.wssyncmldm.ui.XUIInstallConfirmActivity(466/onResume)] Postpone Count : 8
I/ProcessStatsService( 3528): Prepared write state in 13ms
W/libprocessgroup( 3528): failed to open /acct/uid_10164/pid_11531/cgroup.procs: No such file or directory
I/DBG_DM  ( 6269): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
I/ProcessStatsService( 3528): Prepared write state in 13ms
I/DBG_DM  ( 6269): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
I/ProcessStatsService( 3528): Prepared write state in 12ms
I/DBG_DM  ( 6269): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
I/ProcessStatsService( 3528): Prepared write state in 13ms
D/SecContentProvider2( 3528): uri = 14 selection = getSealedState
D/SecContentProvider2( 3528): mCursor = null
D/ApplicationPolicy( 3528): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3528): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
I/ProcessStatsService( 3528): Prepared write state in 15ms
I/DBG_DM  ( 6269): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 8
I/DBG_DM  ( 6269): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
I/ProcessStatsService( 3528): Prepared write state in 17ms
I/DBG_DM  ( 6269): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 6269): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
I/DBG_DM  ( 6269): [llIIlIIlIllIllIlllII(376/llIIllllIIlllIIIIlll)] 
I/DBG_DM  ( 6269): [IIlIIIlllllIIlIIIlII(339/llllIlIIIllllIIlIlll)] No need to check encryption status
I/DBG_DM  ( 6269): [llIIlIIlIllIllIlllII(405/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
I/ProcessStatsService( 3528): Prepared write state in 13ms
D/ActivityManager( 3528): post active user change for 0
D/KnoxTimeoutHandler( 3528): postActiveUserChange for user 0
I/DBG_DM  ( 6269): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
I/ProcessStatsService( 3528): Prepared write state in 17ms
I/art     ( 3528): Explicit concurrent mark sweep GC freed 8114(552KB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 48MB/64MB, paused 3.407ms total 180.719ms
I/art     ( 3528): WaitForGcToComplete blocked for 139.967ms for cause Explicit
I/ProcessStatsService( 3528): Prepared write state in 21ms
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
I/InputReader( 3528): Reconfiguring input devices.  changes=0x00000010
E/SamsungIME( 4467): mOCRHelper is null
W/BroadcastQueue( 3528): Skipping deliver [background] BroadcastRecord{e7493be u0 android.intent.action.PACKAGE_REMOVED} to ReceiverList{201ff247 11496 com.sec.android.widgetapp.locationwidget/10022/u0 remote:13c86986}: filter unregistered
W/GeofencerStateMachine( 4615): Ignoring removeGeofence because network location is disabled.
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/Zygote  (13869): MountEmulatedStorage()
E/Zygote  (13869): v2
I/libpersona(13869): KNOX_SDCARD checking this for 10063
I/libpersona(13869): KNOX_SDCARD not a persona
I/SELinux (13869): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
W/ResourceType( 5317): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5317): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
I/ActivityManager( 3528): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=13869 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (13869): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (13869): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ProcessStatsService( 3528): Prepared write state in 17ms
I/SurfaceFlinger( 2850): id=16 createSurf (1440x2560),2 flag=404, YUIInstallC
D/StatusBarManagerService( 3528): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService( 3528): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/ProcessStatsService( 3528): Prepared write state in 15ms
D/PointerIcon( 3528): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3528): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3528): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3528): setHoveringSpenCustomIcon IconType is same.1
I/ProcessStatsService( 3528): Prepared write state in 10ms
D/KnoxTimeoutHandler( 3528): handleActiveUserChange for user 0
D/TimaKeyStoreProvider(13869): TimaSignature is unavailable
D/ActivityThread(13869): Added TimaKeyStore provider
D/ResourcesManager( 3528): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/ProcessStatsService( 3528): Prepared write state in 7ms
I/ProcessStatsService( 3528): Prepared write state in 9ms
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /data/app/com.facebook.katana-1/base.apk
I/ProcessStatsService( 3528): Prepared write state in 16ms
D/InputMethodManagerService( 3528): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/SecContentProvider2( 3528): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3528): mCursor = null
W/InputMethodManagerService( 3528): Got RemoteException sending setActive(false) notification to pid 11750 uid 10504
I/ProcessStatsService( 3528): Prepared write state in 14ms
D/ResourcesManager(13869): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
V/ActivityThread( 6269): updateVisibility : ActivityRecord{fa12aef token=android.os.BinderProxy@11ad3750 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
I/Timeline( 6269): Timeline: Activity_idle id: android.os.BinderProxy@11ad3750 time:1953773
W/ActivityManager( 3528): mDVFSHelper.release()
I/Timeline( 3528): Timeline: Activity_windows_visible id: ActivityRecord{2233e662 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t24} time:1953778
D/RegisteredServicesCache( 3965): empty dynamic service
D/VRSetupWizardStub/PackageIntentReceiver(13869): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(13869): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(13869): packagename:com.test.thalitest
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
I/ProcessStatsService( 3528): Pruning old procstats: /data/system/procstats/state-2015-12-15-16-16-37.bin
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
I/art     ( 3528): Explicit concurrent mark sweep GC freed 5951(380KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 48MB/64MB, paused 5.981ms total 234.976ms
E/Zygote  (13888): MountEmulatedStorage()
I/libpersona(13888): KNOX_SDCARD checking this for 10021
E/Zygote  (13888): v2
I/libpersona(13888): KNOX_SDCARD not a persona
I/SELinux (13888): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (13888): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (13888): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3528): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=13888 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
I/ActivityManager( 3528): Killing 12136:com.samsung.android.scloud.backup/u0a67 (adj 15): empty for 1810s
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/TimaKeyStoreProvider(13888): TimaSignature is unavailable
D/ActivityThread(13888): Added TimaKeyStore provider
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
D/ResourcesManager(13888): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
I/KLMS-2.4.521: (13888): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Dec 16 05:29:14 GMT+01:00 2015
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
D/PackageManager( 3528): delete codoeFile: 
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
I/KLMS-2.4.521: (13888): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 3528): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3528): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
W/libprocessgroup( 3528): failed to open /acct/uid_10067/pid_12136/cgroup.procs: No such file or directory
I/AASAUninstall( 3528):  com.test.thalitest not target!
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/PackageManager( 3528): result of delete: 1{52980544}
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
I/KLMS-2.4.521: (13888): KLMSIntentService(): onCreate()
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/AndroidRuntime(13850): Shutting down VM
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/Books/Books.apk
I/KLMS-2.4.521: (13888): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
I/KLMS-2.4.521: (13888): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/talkback/talkback.apk
I/KLMS-2.4.521: (13888): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
I/KLMS-2.4.521: (13888): KLMSIntentService(): PACKAGE_REMOVED
I/KLMS-2.4.521: (13888): KLMSIntentService(): listeningToPackageRemoved().START
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
I/KLMS-2.4.521: (13888): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
E/Zygote  (13904): MountEmulatedStorage()
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/EnterpriseDeviceManagerService( 3528): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3528): Admin package name: com.google.android.gms
E/Zygote  (13904): v2
I/libpersona(13904): KNOX_SDCARD checking this for 10106
I/libpersona(13904): KNOX_SDCARD not a persona
I/SELinux (13904): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
I/SELinux (13904): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3528): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=13904 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
E/SELinux (13904): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
W/Resources( 3528): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
W/Resources( 3528): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/RCPManager(12165):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3528):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3528): queryAllProviders():  providerCallBack is not register for 0
E/Zygote  (13919): MountEmulatedStorage()
E/Zygote  (13919): v2
I/libpersona(13919): KNOX_SDCARD checking this for 10160
I/libpersona(13919): KNOX_SDCARD not a persona
I/SELinux (13919): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (13919): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3528): Start proc com.samsung.android.snote for broadcast com.samsung.android.snote/.library.plugin.PluginBroadcastReceiver: pid=13919 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
E/SELinux (13919): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider(13904): TimaSignature is unavailable
W/Resources( 3528): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ActivityThread(13904): Added TimaKeyStore provider
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider(13919): TimaSignature is unavailable
D/ActivityThread(13919): Added TimaKeyStore provider
E/Zygote  (13934): MountEmulatedStorage()
E/Zygote  (13934): v2
I/libpersona(13934): KNOX_SDCARD checking this for 10050
I/libpersona(13934): KNOX_SDCARD not a persona
I/SELinux (13934): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (13934): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3528): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=13934 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
E/SELinux (13934): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.4.521: (13888): KLMSIntentService(): listeningToPackageRemoved().END
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(13919): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/ResourcesManager(13904): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/TimaKeyStoreProvider(13934): TimaSignature is unavailable
D/ActivityThread(13934): Added TimaKeyStore provider
W/ResourcesManager(13919): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(13919): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13919): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
E/Zygote  (13949): MountEmulatedStorage()
E/Zygote  (13949): v2
I/libpersona(13949): KNOX_SDCARD checking this for 10101
I/libpersona(13949): KNOX_SDCARD not a persona
I/SELinux (13949): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager( 3528): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/elm:14491(13904): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
I/SELinux (13949): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/elm:14491(13904): ELMEngine.ELMEngine( context ).
D/elm:14491(13904): MDMBridge.setEnterpriseBridge()
I/ActivityManager( 3528): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=13949 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (13949): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/art     ( 2884): Explicit concurrent mark sweep GC freed 8735(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 414us total 16.097ms
I/KLMS-2.4.521: (13888): KLMSIntentService(): onDestroy()
D/elm:14491(13904): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14491(13904): ElmAgentService : onCreate()
D/TimaKeyStoreProvider(13949): TimaSignature is unavailable
D/elm:14491(13904): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
D/ActivityThread(13949): Added TimaKeyStore provider
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
D/elm:14491(13904): MainReceiver.listeningToPackageRemoved()
D/elm:14491(13904): MDMBridge.getInstance()
D/elm:14491(13904): MDMBridge.getAllLicenseInfoFromSDK()
D/ResourcesManager(13934): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
D/elm:14491(13904): MDMBridge.getAllLicenseInfoFromSDK()
I/art     ( 2884): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 554us total 11.689ms
W/ResourcesManager(13934): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(13934): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(13934): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(13934): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13934): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(13934): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(13934): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(13934): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/art     ( 2884): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 351us total 11.198ms
E/Zygote  (13966): MountEmulatedStorage()
E/Zygote  (13966): v2
I/libpersona(13966): KNOX_SDCARD checking this for 10019
I/libpersona(13966): KNOX_SDCARD not a persona
I/SELinux (13966): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (13966): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3528): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=13966 uid=10019 gids={50019, 9997} abi=armeabi-v7a
E/SELinux (13966): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/elm:14491(13904): ElmAgentService : onDestroy().

```
