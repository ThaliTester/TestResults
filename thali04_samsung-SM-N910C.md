#### Test 575312438097721_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:46
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 3523): Plugged
I/MotionRecognitionService( 3523): setPowerConnected  = true
D/BatteryService( 3523): stay LED for fully charged
--------- beginning of main
D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5636): Disconnected process message: 10
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/AlarmManager( 3523): waitForAlarm result :8
D/AndroidRuntime(12079): 
D/AndroidRuntime(12079): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(12079): CheckJNI is OFF
D/AndroidRuntime(12079): readGMSProperty: start
D/AndroidRuntime(12079): readGMSProperty: already setted!!
D/AndroidRuntime(12079): readGMSProperty: end
D/AndroidRuntime(12079): addProductProperty: start
E/AffinityControl(12079): AffinityControl: registerfunction enter
D/AndroidRuntime(12079): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3523): inState():  stateMachine is null !!
I/PersonaManagerService( 3523): PersonaId don't exist
I/ActivityManager( 3523): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3523): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3523): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3523): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager( 3523): mDVFSHelper.acquire()
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/Zygote  (12099): MountEmulatedStorage()
E/Zygote  (12099): v2
I/libpersona(12099): KNOX_SDCARD checking this for 10619
I/libpersona(12099): KNOX_SDCARD not a persona
I/SELinux (12099): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3523): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=12099 uid=10619 gids={50619, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux (12099): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12099): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(12079): Shutting down VM
D/PointerIcon( 3523): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3523): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3523): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3523): setHoveringSpenCustomIcon IconType is same.1
I/art     ( 2881): Explicit concurrent mark sweep GC freed 8743(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 895us total 25.031ms
D/TimaKeyStoreProvider(12099): TimaSignature is unavailable
D/ActivityThread(12099): Added TimaKeyStore provider
I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 807us total 18.646ms
I/SurfaceFlinger( 2850): id=11 Removed YUIInstallC (5/8)
I/SurfaceFlinger( 2850): id=11 Removed YUIInstallC (-2/8)
D/ResourcesManager(12099): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
V/ActivityThread( 6273): updateVisibility : ActivityRecord{13d94469 token=android.os.BinderProxy@31482d22 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 621us total 20.052ms
I/WebViewFactory(12099): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(12099): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(12099): Loading: webviewchromium
I/LibraryLoader(12099): Time to load native libraries: 6 ms (timestamps 6237-6243)
I/LibraryLoader(12099): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(12099): Binding Chromium to main looper Looper (main, tid 1) {3e96e780}
I/LibraryLoader(12099): Expected native library version number "",actual native library version number ""
I/chromium(12099): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController(12099): Initializing chromium process, renderers=0
W/art     (12099): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium(12099): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium(12099): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(12099): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
W/chromium(12099): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium(12099): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     (12099): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents(12099): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine(12099): CordovaWebView is running on device made by: samsung
W/art     (12099): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (12099): Attempt to remove local handle scope entry from IRT, ignoring
D/Activity(12099): performCreate Call secproduct feature valuefalse
D/Activity(12099): performCreate Call debug elastic valuetrue
D/OpenGLRenderer(12099): Render dirty regions requested: true
W/ActivityManager( 3523): Activity pause timeout for ActivityRecord{34a410b6 u0 com.test.thalitest/.MainActivity t26}
D/ActivityManager( 3523): post active user change for 0
D/KnoxTimeoutHandler( 3523): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3523): handleActiveUserChange for user 0
I/SurfaceFlinger( 2850): id=13 createSurf (1x1),1 flag=404, NainActivit
D/StatusBarManagerService( 3523): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService( 3523): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 3523): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3523): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3523): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3523): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer(12099): Initialized EGL, version 1.4
I/OpenGLRenderer(12099): HWUI protection enabled for context ,  &this =0xaf945060 ,&mEglDisplay = 1 , &mEglConfig = -1279807216 
D/OpenGLRenderer(12099): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(12099): Enabling debug mode 0
D/mali_winsys(12099): new_window_surface returns 0x3000,  [1440x2560]-format:1
V/ActivityThread(12099): updateVisibility : ActivityRecord{10f330b0 token=android.os.BinderProxy@3b6d4067 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
D/InputMethodManagerService( 3523): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ActivityManager( 3523): mDVFSHelper.release()
I/Timeline( 3523): Timeline: Activity_windows_visible id: ActivityRecord{34a410b6 u0 com.test.thalitest/.MainActivity t26} time:246743
W/IInputConnectionWrapper(12099): showStatusIcon on inactive InputConnection
I/Timeline(12099): Timeline: Activity_idle id: android.os.BinderProxy@3b6d4067 time:246755
D/JsMessageQueue(12099): Set native->JS mode to OnlineEventsBridgeMode
I/chromium(12099): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(12099): 
D/jxcore_app_log(12099): JniHelper::setJavaVM(0xb4d5c280), pthread_self() = -1362667776
I/chromium(12099): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/jxcore-log(12099): Initializing JXcore engine
W/jxcore-log(12099): JXcore engine is ready
,E/auditd  ( 4615): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3523): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3523): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(12099): Starting JXcore engine
,W/jxcore-log(12099): Platform android
W/jxcore-log(12099): 
W/jxcore-log(12099): Process ARCH arm
W/jxcore-log(12099): 
,I/jxcore-log(12099): JXcore Cordova bridge is ready!
I/jxcore-log(12099): 
W/jxcore-log(12099): JXcore engine is started
,I/jxcore-log(12099): Toggling radios to true
I/jxcore-log(12099): 
,D/BluetoothAdapter(12099): enable()
,D/BluetoothAdapter(12099): enable(): BT is already enabled..!
,D/WifiService( 3523): New client listening to asynchronous messages
,I/WifiManager(12099): packageName : com.test.thalitest
,D/SecContentProvider( 3523): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3523): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3523): mCursor = null
,D/WifiService( 3523): setWifiEnabled: true pid=12099, uid=10619
E/WifiService( 3523): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3523): Permission Denial: getCurrentUser() from pid=12099, uid=10619 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 3523): Failed getting userId using ActivityManagerNative
W/WifiService( 3523): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=12099, uid=10619 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3523): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3523): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3523): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3523): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3523): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider( 3523): name = wifi_on
I/WifiService( 3523): disconnect: pid=12099, uid=10619
,I/wpa_supplicant( 3832): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log(12099): Radios toggled
I/jxcore-log(12099): 
,I/jxcore-log(12099): My device name is: samsung-SM-N910C
I/jxcore-log(12099): 
,I/wpa_supplicant( 3832): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3832): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 3832): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3832): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine( 3523): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 3832): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3832): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3832): Disconnected - do not scan
I/wpa_supplicant( 3832): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine( 3523): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3523): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3523): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3523): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine( 3523): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3523): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/native  ( 3523): do suspend true
,D/WifiP2pService( 3523): InactiveState{ what=143375 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=143375 }
,D/CommandListener( 2846): Clearing all IP addresses on wlan0
,E/Netd    ( 2846): ifc_reset_connections failed on iface wlan0 for address 192.168.1.124/24 (Unknown error -1)
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,E/WifiStateMachine( 3523): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService( 3523): updateNetworkInfo()
,D/ConnectivityService( 3523): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/WifiConfigStore( 3523): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/ConnectivityService( 3523): updateNetworkInfo()
,D/ConnectivityService( 3523): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,I/WifiTrafficPoller( 3523): evaluateTrafficStatsPolling
,E/WifiStateMachine( 3523): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 3832): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3832): P2P: Current p2p state = IDLE
I/wpa_supplicant( 3832): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 3832): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3832): First Scan Start
,I/wpa_supplicant( 3832): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiStateMachine( 3523): ConnectModeState: Network connection lost 
,E/WifiStateMachine( 3523): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - processMessage - processMsg
,E/WifiStateMachine( 3523): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3523): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3523): do suspend true
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3692): applyOpen
,D/WifiP2pService( 3523): InactiveState{ what=143375 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=143375 }
I/Hs20UtilService( 4064): Starting #8
I/Hs20UtilService( 4064): Message received 5007
D/NearbySettings( 8880): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 8880): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings( 8880): MountReceiver.onReceive - Create mPrefHandler
,D/NearbySettings( 8880): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
,V/NearbySettings( 8880): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8880): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/WifiService( 3523): New client listening to asynchronous messages
,I/NearbySettings( 8880): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8880): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8880): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8880): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11654): NETWORK_STATE_CHANGED_ACTION
,D/CommandListener( 2846): Clearing all IP addresses on wlan0
,D/ConnectivityService( 3523): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/EntConnectivity( 3523): Not allowed due to - mEnabled false
,D/ConnectivityManager.CallbackHandler( 3692): CM callback handler got msg 524292
E/WifiStateMachine( 3523): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 3523): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiStateMachine( 3523): updateConfiguredNetworkExpiration - currTime: 1454429882551
D/WifiStateMachine( 3523): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
E/WifiStateMachine( 3523): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine( 3523): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
I/WifiTrafficPoller( 3523): evaluateTrafficStatsPolling
D/TelephonyNetworkFactory( 3982): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 6670): CM callback handler got msg 524292
E/WifiStateMachine( 3523): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3523): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent( 3523): NetworkAgent: NetworkAgent channel lost
,D/CSLegacyTypeTracker( 3523): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
E/WifiStateMachine( 3523): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
D/CSLegacyTypeTracker( 3523): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
E/WifiStateMachine( 3523): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
D/ConnectivityService( 3523): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine( 3523): setDetailed state send new extra info"NG700"
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
,D/SecContentProvider2( 3523): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3523): mCursor = null
,D/Tethering( 3523): MasterInitialState.processMessage what=3
,D/EntConnectivity( 3523): Not allowed due to - mEnabled false
D/SmartBondingService( 3523): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService( 3523): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,V/NetworkStats( 3523): updateIfacesLocked()
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
V/NetworkStats( 3523): performPollLocked(flags=0x1)
,D/SmartBondingService( 3523): getSBEnabled() enabled =false
,D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
,D/SecContentProvider2( 3523): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3523): mCursor = null
,D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3692): updateDataNetType()
D/StatusBar.NetworkController( 3692): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3692): updateLTEICONDataNetType:0
D/NetworkStatsFactory( 3523): UpdateStatsForKnox
,D/ConnectivityService( 3523): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/SmartBondingService( 3523): getNetworkEnabled : wifi : true mobile : false
,V/NetworkStats( 3523): performPollLocked() took 8ms
,D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
V/NetworkStats( 3523): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 3692): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3692): updateTelephonySignalStrength: hasService=false ss=null
,D/StatusBar.NetworkController( 3692): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,I/Hs20UtilService( 4064): Starting #9
,I/Hs20UtilService( 4064): Message received 5007
,D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
,D/NearbySettings( 8880): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8880): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8880): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8880): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8880): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8880): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 8880): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11654): NETWORK_STATE_CHANGED_ACTION
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
,D/ConnectivityService( 3523): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 3523): updateDataUsageMap
I/ApplicationPolicy( 3523): updateDataUsageMap  idList is null 
D/SmartBondingService( 3523): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3523): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/GpsLocationProvider( 3523): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3523): getNetworkEnabled : wifi : true mobile : false
W/SLocation( 3523): No Active Data Connection
I/DBG_DM  ( 6273): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
I/DBG_DM  ( 6273): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12189): MountEmulatedStorage()
E/Zygote  (12189): v2
I/libpersona(12189): KNOX_SDCARD checking this for 10110
I/libpersona(12189): KNOX_SDCARD not a persona
,I/SELinux (12189): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12189): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12189): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.iorg.vpn.cleanup.NetworkStateMonitor: pid=12189 uid=10110 gids={50110, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12189): TimaSignature is unavailable
,D/ActivityThread(12189): Added TimaKeyStore provider
,D/ResourcesManager(12189): creating new AssetManager and set to /data/app/com.facebook.appmanager-2/base.apk
,D/ACRA    (12189): ACRA is enabled for com.facebook.appmanager, intializing...
,I/DexLibLoader(12189): not using cross-dex optimization: ART in use
,I/art     (12189): Thread[1,tid=12189,WaitingForJniOnLoad,Thread*=0xb4d08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/app/com.facebook.appmanager-2/lib/arm/libfbjni.so"
,V/DexLibLoader(12189): about to lock: /data/data/com.facebook.appmanager/mdex_lock
V/DexLibLoader(12189): locking /data/data/com.facebook.appmanager/mdex_lock took 1 ms
,V/DexLibLoader(12189): Secondary program dex metadata: classes2.dex 29f80981f469a774a4884b3db2df17e0be227159 secondary.dex01.Canary
D/DexLibLoader(12189): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex" is valid
D/DexLibLoader(12189): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex_opt" is valid
,W/art     (12189): Attempt to remove local handle scope entry from IRT, ignoring
,D/DexLibLoader(12189): loading pre-built fallback odex files
V/MultiDexClassLoader(12189): installing MultiDexClassLoader before application classloader
D/DexLibLoader(12189): released odex store lock
D/DexLibLoader(12189): DexLibLoader.loadAll took 17 ms
,W/ca      (12189): Verify
,W/LightSharedPreferencesImpl(12189): Failed to load preference file from Disk!
W/LightSharedPreferencesImpl(12189): java.io.FileNotFoundException: /data/data/com.facebook.appmanager/app_light_prefs/com.facebook.appmanager/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(12189): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/LightSharedPreferencesImpl(12189): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/LightSharedPreferencesImpl(12189): 	at com.facebook.crudolib.b.k.a(LightSharedPreferencesStorage.java:56)
W/LightSharedPreferencesImpl(12189): 	at com.facebook.crudolib.b.g.run(LightSharedPreferencesImpl.java:61)
W/LightSharedPreferencesImpl(12189): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/LightSharedPreferencesImpl(12189): 	at com.facebook.common.executors.dj.run(WrappingExecutorService.java:77)
W/LightSharedPreferencesImpl(12189): 	at com.facebook.common.executors.u.run(DefaultConstrainedListeningExecutorService.java:327)
W/LightSharedPreferencesImpl(12189): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/LightSharedPreferencesImpl(12189): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/LightSharedPreferencesImpl(12189): 	at com.facebook.common.executors.cc.run(NamedThreadFactory.java:42)
W/LightSharedPreferencesImpl(12189): 	at java.lang.Thread.run(Thread.java:818)
W/LightSharedPreferencesImpl(12189): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(12189): 	at libcore.io.Posix.open(Native Method)
W/LightSharedPreferencesImpl(12189): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/LightSharedPreferencesImpl(12189): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/LightSharedPreferencesImpl(12189): 	... 10 more
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12214): MountEmulatedStorage()
I/libpersona(12214): KNOX_SDCARD checking this for 1000
E/Zygote  (12214): v2
I/libpersona(12214): KNOX_SDCARD not a persona
,I/SELinux (12214): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12214): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3523): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=12214 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (12214): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Killing 9976:com.sec.android.app.shealth/u0a36 (adj 15): bgCount ##31
,E/lowmemorykiller( 2829): Error writing /proc/9976/oom_score_adj; errno=22
,W/appmanager(:<default>):b(12189): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/appmanager(:<default>):b(12189): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/TimaKeyStoreProvider(12214): TimaSignature is unavailable
,D/ActivityThread(12214): Added TimaKeyStore provider
,D/ResourcesManager(12214): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,W/appmanager(:<default>):QuickExperimentControllerImpl(12189): Exposure of experiment com.facebook.common.network.l@13aacef6 occurred when no user was logged in
,I/PCWCLIENTTRACE_LOG(12214): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(12214): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(12214): new DMDBOpenHelper instance
,W/BroadcastQueue( 3523): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{289e5925 u0 ReceiverList{3082c91c 12189 com.facebook.appmanager/10110/u0 remote:be9b28f}}
,W/BroadcastQueue( 3523): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{289e5925 u0 ReceiverList{3082c91c 12189 com.facebook.appmanager/10110/u0 remote:be9b28f}}
,I/PCWCLIENTTRACE_PushUtil(12214): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(12214): sales region : global
I/PCWCLIENTTRACE_PushUtil(12214): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(12214): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
I/PCWCLIENTTRACE_SYSTEMReceiver(12214): noConnectivity : true
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12237): MountEmulatedStorage()
I/libpersona(12237): KNOX_SDCARD checking this for 10135
E/Zygote  (12237): v2
I/libpersona(12237): KNOX_SDCARD not a persona
,I/SELinux (12237): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12237): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3523): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=12237 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (12237): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Killing 11250:com.sec.android.app.samsungapps/u0a13 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12237): TimaSignature is unavailable
,D/ActivityThread(12237): Added TimaKeyStore provider
,D/ResourcesManager(12237): creating new AssetManager and set to /system/app/Music2/Music2.apk
,W/BroadcastQueue( 3523): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{b11c4d9 u0 ReceiverList{28fe8320 12189 com.facebook.appmanager/10110/u0 remote:d5fc223}}
,I/MusicStore(12237): Database version: 104
,D/ResourcesManager(12237): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(12237): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(12237): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (12237): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(12237): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (12237): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1c39ded4: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(12237): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(12237): GMSCore installation verified
,I/ConfigStore(12237): Config Database version: 1
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12237): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,I/wpa_supplicant( 3832): nl80211: Received scan results (5 BSSes)
I/wpa_supplicant( 3832): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3832): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3832): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 3832): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3523): [1,454,429,883,578 ms] noteScanEnd no scan source
,E/WifiStateMachine( 3523): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@191f2fd4 sup_state=SCANNING debouncing=false
,E/WifiStateMachine( 3523): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3523): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3523): setDetailed state send new extra info
,D/SecContentProvider2( 3523): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3523): mCursor = null
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12237): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
W/ContextImpl(12237): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,I/art     ( 3523): Explicit concurrent mark sweep GC freed 63764(3MB) AllocSpace objects, 50(800KB) LOS objects, 24% free, 49MB/65MB, paused 1.255ms total 80.193ms
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12189): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
W/ContextImpl(12189): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,I/wpa_supplicant( 3832): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 3832): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3523): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3523): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
I/wpa_supplicant( 3832): Associated with C0.AA.48
E/WifiStateMachine( 3523): setDetailed state send new extra info"NG700"
D/SecContentProvider2( 3523): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3523): mCursor = null
,D/WifiDisplayAdapter( 3523): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/wpa_supplicant( 3832): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 3832): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3523): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3523): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,D/SecContentProvider2( 3523): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3523): mCursor = null
,D/WifiDisplayAdapter( 3523): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3523): getStreamVolume 3 index 0
,I/MediaRouter(12237): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,W/appmanager(:<default>):QuickExperimentControllerImpl(12189): Exposure of experiment com.facebook.imagepipeline.a.g@2da8fa77 occurred when no user was logged in
I/wpa_supplicant( 3832): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,W/appmanager(:<default>):QuickExperimentControllerImpl(12189): Exposure of experiment com.facebook.imagepipeline.a.d@3736bd50 occurred when no user was logged in
,I/wpa_supplicant( 3832): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 3832): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3523): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3523): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,I/wpa_supplicant( 3832): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3832): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,I/wpa_supplicant( 3832): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 3832): Blacklist: Clear (temp) 
I/wpa_supplicant( 3832): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3523): Network connection established
,D/WifiNative-HAL( 3523): callSECApiVoid - ID [50]
,E/WifiStateMachine( 3523): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine( 3523): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService( 3523): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine( 3523): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3523): L2ConnectedState "NG700" nid=0
E/WifiConfigStore( 3523): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 3523): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 3523): updateNetworkInfo()
,D/ConnectivityService( 3523): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/WifiStateMachine( 3523): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine( 3523): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3523): ObtainingIpAddress "NG700" nid=0
I/art     (12189): Explicit concurrent mark sweep GC freed 42574(2MB) AllocSpace objects, 6(96KB) LOS objects, 22% free, 27MB/35MB, paused 544us total 22.700ms
E/WifiConfigStore( 3523): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/appmanager(:<default>):m(12189): No feature status reporters found; is this dead code?
,E/Zygote  (12273): MountEmulatedStorage()
I/libpersona(12273): KNOX_SDCARD checking this for 10002
E/Zygote  (12273): v2
I/libpersona(12273): KNOX_SDCARD not a persona
,I/SELinux (12273): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12273): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12273): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=12273 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/CommandListener( 2846): Setting iface cfg
E/WifiStateMachine( 3523): Start Dhcp Watchdog 2
,D/SecContentProvider2( 3523): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3523): mCursor = null
,D/WifiDisplayAdapter( 3523): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/TimaKeyStoreProvider(12273): TimaSignature is unavailable
,D/ActivityThread(12273): Added TimaKeyStore provider
,I/NetworkMonitor(12237): type=WIFI subType= reason=null isConnected=false
,I/ActivityManager( 3523): Killing 11268:com.policydm/1000 (adj 15): bgCount ##31
,D/ResourcesManager(12273): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager( 3523): Killing 11283:com.sec.android.provider.badge/u0a82 (adj 15): bgCount ##31
E/lowmemorykiller( 2829): Error writing /proc/11283/oom_score_adj; errno=22
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12296): MountEmulatedStorage()
I/libpersona(12296): KNOX_SDCARD checking this for 1000
E/Zygote  (12296): v2
I/libpersona(12296): KNOX_SDCARD not a persona
,I/SELinux (12296): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12296): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12296): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=12296 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12296): TimaSignature is unavailable
,D/ActivityThread(12296): Added TimaKeyStore provider
,E/WifiStateMachine( 3523): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3523): do suspend false
,D/WifiP2pService( 3523): InactiveState{ what=143375 }
D/WifiP2pService( 3523): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 3523): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3523): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
D/SecContentProvider2( 3523): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3523): mCursor = null
D/ResourcesManager(12296): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT(12296): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT(12296): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT(12296): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT(12296): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(12296): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12312): MountEmulatedStorage()
I/libpersona(12312): KNOX_SDCARD checking this for 10012
E/Zygote  (12312): v2
I/libpersona(12312): KNOX_SDCARD not a persona
,I/SELinux (12312): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12312): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12312): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=12312 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12312): TimaSignature is unavailable
,D/ActivityThread(12312): Added TimaKeyStore provider
,D/ResourcesManager(12312): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager( 3523): Killing 11304:com.sec.android.app.soundalive/u0a59 (adj 15): bgCount ##31
,I/FOTA_Client(12312): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(12312): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(12312): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/dhcpcd  (12328): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (12328): version 5.5.6 starting
,E/Zygote  (12329): MountEmulatedStorage()
I/libpersona(12329): KNOX_SDCARD checking this for 10021
E/Zygote  (12329): v2
I/libpersona(12329): KNOX_SDCARD not a persona
E/dhcpcd  (12328): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/SELinux (12329): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12329): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12329): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=12329 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
I/ActivityManager( 3523): Killing 11321:com.sec.spp.push/u0a39 (adj 15): bgCount ##31
,E/lowmemorykiller( 2829): Error writing /proc/11321/oom_score_adj; errno=22
,D/TimaKeyStoreProvider(12329): TimaSignature is unavailable
,D/ActivityThread(12329): Added TimaKeyStore provider
,D/ResourcesManager(12329): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/dhcpcd  (12328): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (12328): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (12328): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  (12328): bssid match
,I/dhcpcd  (12328): wlan0: rebinding lease of 192.168.1.124
,I/KLMS-2.4.521: (12329): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Feb 02 17:18:04 GMT+01:00 2016
,I/KLMS-2.4.521: (12329): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (12329): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12329): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
I/KLMS-2.4.521: (12329): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (12329): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12329): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (12329): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.521: (12329): StateImplV2(): networkChangeListener().END
,E/Zygote  (12352): MountEmulatedStorage()
E/Zygote  (12352): v2
I/libpersona(12352): KNOX_SDCARD checking this for 10038
I/libpersona(12352): KNOX_SDCARD not a persona
,I/SELinux (12352): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12352): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12352): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=12352 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/KLMS-2.4.521: (12329): KLMSIntentService(): onDestroy()
,I/ActivityManager( 3523): Killing 11135:com.google.android.apps.docs/u0a101 (adj 15): bgCount ##31
,E/lowmemorykiller( 2829): Error writing /proc/11135/oom_score_adj; errno=22
,D/TimaKeyStoreProvider(12352): TimaSignature is unavailable
,D/ActivityThread(12352): Added TimaKeyStore provider
,D/ResourcesManager(12352): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT(12352): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12367): MountEmulatedStorage()
I/libpersona(12367): KNOX_SDCARD checking this for 1000
E/Zygote  (12367): v2
I/libpersona(12367): KNOX_SDCARD not a persona
I/SELinux (12367): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12367): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12367): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=12367 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 11343:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12367): TimaSignature is unavailable
,D/ActivityThread(12367): Added TimaKeyStore provider
,D/ResourcesManager(12367): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12387): MountEmulatedStorage()
I/libpersona(12387): KNOX_SDCARD checking this for 10039
E/Zygote  (12387): v2
I/libpersona(12387): KNOX_SDCARD not a persona
I/SELinux (12387): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12387): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12387): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=12387 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 11399:com.wsomacp/u0a28 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12387): TimaSignature is unavailable
,D/ActivityThread(12387): Added TimaKeyStore provider
,D/ResourcesManager(12387): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService(12387): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(12387): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService(12387): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,D/SPPClientService(12387): PushLog.txt file is not deleted.
D/SPPClientService(12387): PushLog.txt file is not deleted.
D/SPPClientService(12387): ============PushLog. stop!
,I/SA      (11457): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
I/SA      (11457): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      (11457): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      (11457): [SLFUCHKMGR] constructor called
,E/SPPClientService(12387): [[SystemStateMonitorService]] No Active Internet
,I/SA      (11457): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11457): [OR] == isSIMCardReady false ==
,I/SA      (11457): [SCU] == networkStateCheck == false
I/SA      (11457): [OR] onReceive END
,V/DownloadManager( 5749): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager( 3523): Killing 11383:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
E/lowmemorykiller( 2829): Error writing /proc/11383/oom_score_adj; errno=22
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12407): MountEmulatedStorage()
I/libpersona(12407): KNOX_SDCARD checking this for 10067
E/Zygote  (12407): v2
I/libpersona(12407): KNOX_SDCARD not a persona
I/SELinux (12407): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12407): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12407): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=12407 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/art     ( 2881): Explicit concurrent mark sweep GC freed 8740(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 391us total 10.148ms
D/TimaKeyStoreProvider(12407): TimaSignature is unavailable
D/ActivityThread(12407): Added TimaKeyStore provider
I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 269us total 8.560ms
D/ResourcesManager(12407): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 261us total 8.487ms
,I/sCloudBackupApp(12407): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(12407): Other Intent
,I/ActivityManager( 3523): Killing 11419:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
,D/accuweather( 5100): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3776): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,D/accuweather( 5100): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5100): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5100): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5100): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
D/accuweather( 5100): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/accuweather( 5100): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12423): MountEmulatedStorage()
E/Zygote  (12423): v2
I/libpersona(12423): KNOX_SDCARD checking this for 1000
I/libpersona(12423): KNOX_SDCARD not a persona
,I/SELinux (12423): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12423): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12423): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=12423 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12423): TimaSignature is unavailable
,D/ActivityThread(12423): Added TimaKeyStore provider
,D/ResourcesManager(12423): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(12423): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro(12423): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro(12423): premStatus:2
,I/KnoxUsageLogPro(12423): isEulaShown : false
I/KnoxUsageLogPro(12423): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12438): MountEmulatedStorage()
I/libpersona(12438): KNOX_SDCARD checking this for 10090
E/Zygote  (12438): v2
I/libpersona(12438): KNOX_SDCARD not a persona
I/SELinux (12438): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12438): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12438): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=12438 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 11356:com.sec.android.automotive.drivelink/u0a102 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12438): TimaSignature is unavailable
,D/ActivityThread(12438): Added TimaKeyStore provider
,D/ResourcesManager(12438): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12454): MountEmulatedStorage()
E/Zygote  (12454): v2
I/libpersona(12454): KNOX_SDCARD checking this for 10127
I/libpersona(12454): KNOX_SDCARD not a persona
,I/SELinux (12454): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12454): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12454): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=12454 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 11513:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12454): TimaSignature is unavailable
,D/ActivityThread(12454): Added TimaKeyStore provider
,D/ResourcesManager(12454): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,D/KeyguardWallpaperUpdator(12454): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12454): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12454): stopCheckCategoryVersion
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12471): MountEmulatedStorage()
E/Zygote  (12471): v2
I/libpersona(12471): KNOX_SDCARD checking this for 10136
I/libpersona(12471): KNOX_SDCARD not a persona
,I/SELinux (12471): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12471): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12471): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=12471 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 11493:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12471): TimaSignature is unavailable
,D/ActivityThread(12471): Added TimaKeyStore provider
,D/ResourcesManager(12471): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12471): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
W/ContextImpl(12471): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12471): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl(12471): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,I/WebViewFactory(12471): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(12471): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(12471): Loading: webviewchromium
,I/LibraryLoader(12471): Time to load native libraries: 3 ms (timestamps 364-367)
I/LibraryLoader(12471): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(12471): Binding Chromium to main looper Looper (main, tid 1) {3cc01440}
,I/LibraryLoader(12471): Expected native library version number "",actual native library version number ""
,I/chromium(12471): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(12471): Initializing chromium process, renderers=0
,W/art     (12471): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(12471): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(12471): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium(12471): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
W/AudioManagerAndroid(12471): Requires BLUETOOTH permission
,I/NSApplication(12471): Starting up...
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,W/art     (11602): Suspending all threads took: 6.356ms
,E/Zygote  (12539): MountEmulatedStorage()
E/Zygote  (12539): v2
I/libpersona(12539): KNOX_SDCARD checking this for 10150
I/libpersona(12539): KNOX_SDCARD not a persona
,I/SELinux (12539): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12539): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3523): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=12539 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 11533:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,E/SELinux (12539): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12539): TimaSignature is unavailable
,D/ActivityThread(12539): Added TimaKeyStore provider
,D/ResourcesManager(12539): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(12539): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12539): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12539): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect(12539): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12539): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect(12539): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12554): MountEmulatedStorage()
I/libpersona(12554): KNOX_SDCARD checking this for 10178
E/Zygote  (12554): v2
I/libpersona(12554): KNOX_SDCARD not a persona
,I/SELinux (12554): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12554): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12554): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=12554 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
I/ActivityManager( 3523): Killing 11551:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12554): TimaSignature is unavailable
,D/ActivityThread(12554): Added TimaKeyStore provider
,D/ResourcesManager(12554): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(12554): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager(12554): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12554): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12554): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12554): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12554): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService( 3523): exchangeData() failure , invalid userId
,D/RCPManagerService( 3523): exchangeData() failure , invalid userId
,D/RCPManagerService( 3523): exchangeData() failure , invalid userId
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 3523): exchangeData() failure , invalid userId
,E/Zygote  (12577): MountEmulatedStorage()
I/libpersona(12577): KNOX_SDCARD checking this for 10082
E/Zygote  (12577): v2
I/libpersona(12577): KNOX_SDCARD not a persona
,I/SELinux (12577): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12577): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12577): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=12577 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,D/RCPManagerService( 3523): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider(12577): TimaSignature is unavailable
,D/ActivityThread(12577): Added TimaKeyStore provider
,D/RCPManagerService( 3523): exchangeData() failure , invalid userId
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(12577): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/BadgeProvider(12577): onCreate
D/BadgeProvider(12577): DatabaseHelper
,E/Zygote  (12593): MountEmulatedStorage()
E/Zygote  (12593): v2
I/libpersona(12593): KNOX_SDCARD checking this for 1000
I/libpersona(12593): KNOX_SDCARD not a persona
,I/SELinux (12593): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12593): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12593): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=12593 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 11677:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##31
,I/ActivityManager( 3523): Killing 11566:com.samsung.helphub/1000 (adj 13): bgCount ##32
,D/BadgeProvider(12577): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/TimaKeyStoreProvider(12593): TimaSignature is unavailable
,D/ActivityThread(12593): Added TimaKeyStore provider
,D/ResourcesManager(12593): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/BadgeProvider(12577): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider(12577): sendNotify, [notify] : null
D/BadgeProvider(12577): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12577): update, [BadgeCount] : badgecount=0
D/BadgeProvider(12577): update, [UpdateCount] : 1
D/Launcher.Model( 4002): reloadBadges entered.
,I/ActivityManager( 3523): Killing 11694:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
,W/ActivityManager( 3523): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/iu.Environment( 6670): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 6670): num queued entries: 0
,I/iu.UploadsManager( 6670): num updated entries: 0
I/iu.SyncManager( 6670): NEXT; no task
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12611): MountEmulatedStorage()
E/Zygote  (12611): v2
I/libpersona(12611): KNOX_SDCARD checking this for 10013
I/libpersona(12611): KNOX_SDCARD not a persona
,I/SELinux (12611): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12611): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12611): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=12611 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12611): TimaSignature is unavailable
,D/ActivityThread(12611): Added TimaKeyStore provider
,D/ResourcesManager(12611): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,I/dhcpcd  (12328): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
,I/ActivityManager( 3523): Killing 11712:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##31
,I/dhcpcd  (12328): wlan0: leased 192.168.1.124 for 86400 seconds
,E/WifiStateMachine( 3523): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine( 3523): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,I/Hs20UtilService( 4064): Starting #10
I/Hs20UtilService( 4064): Message received 5007
,D/NearbySettings( 8880): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8880): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8880): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 8880): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8880): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8880): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 8880): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11654): NETWORK_STATE_CHANGED_ACTION
,I/jxcore-log(12099): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log(12099): 
,E/WifiStateMachine( 3523): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine( 3523): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  ( 3523): do suspend true
,D/WifiP2pService( 3523): InactiveState{ what=143375 }
D/WifiP2pService( 3523): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 3523): WifiStateMachine DHCP successful
,E/WifiStateMachine( 3523): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3523): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine( 3523): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,D/WifiStateMachine( 3523): Not connected state, yet.
E/WifiStateMachine( 3523): VerifyingLinkState enter
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiStateMachine( 3523): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine( 3523): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3523): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3523): callSECApiInt - ID [210]
,E/WifiStateMachine( 3523): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService( 3523): updateNetworkInfo()
D/ConnectivityService( 3523): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 3523): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 3523): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 3523): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
D/WifiWatchdogStateMachine.DnsResolver( 3523): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 3523): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3523): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,I/Hs20UtilService( 4064): Starting #11
,I/Hs20UtilService( 4064): Message received 5007
,E/WifiStateMachine( 3523): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine( 3523): Now, connected state.
E/WifiStateMachine( 3523): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,D/NearbySettings( 8880): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8880): MountReceiver.onReceive - Keep current state
E/WifiStateMachine( 3523): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService( 3523): Adding Route [fe80::/64 -> :: wlan0] to network 503
I/WifiTrafficPoller( 3523): evaluateTrafficStatsPolling
,D/ConnectivityService( 3523): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
D/ConnectivityService( 3523): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService( 3523): Unexpected mtu value: 0, wlan0
V/        ( 2846): QcRouteController
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
,I/WifiTrafficPoller( 3523): evaluateTrafficStatsPolling
E/WifiStateMachine( 3523): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiNative-HAL( 3523): callSECApiVoid - ID [212]
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
,V/        ( 2846): QcRouteController
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,E/WifiStateMachine( 3523): ConnectedState Enter  mScreenOn=false scanperiod=20000
,I/WifiStateMachine( 3523): REQUEST_POWER_SAVE_ON
,V/        ( 2846): QcRouteController
,V/        ( 2846): QcRouteController
,I/SignOutReceiver(11654): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2846): QcRouteController
,I/Hs20UtilService( 4064): Starting #12
,I/Hs20UtilService( 4064): Message received 5007
V/        ( 2846): QcRouteController
,V/        ( 2846): QcRouteController
,D/NearbySettings( 8880): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8880): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8880): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8880): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8880): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8880): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8880): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11654): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2846): QcRouteController
,I/Hs20UtilService( 4064): Starting #13
,D/ConnectivityService( 3523): Setting Dns servers for network 503 to [/192.168.1.1]
,I/Hs20UtilService( 4064): Message received 5007
D/ConnectivityService( 3523): LTETest block dns file not exists
,D/NearbySettings( 8880): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8880): MountReceiver.onReceive - Keep current state
E/ConnectivityService( 3523): updateNetworkInfo()
D/ConnectivityService( 3523): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 3523): updateNetworkInfo()
D/ConnectivityService( 3523): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 3523): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 3523): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): Checking http://clients3.google.com/generate_204 on "NG700"
,I/System.out( 3523): (HTTPLog)-Static: isSBSettingEnabled false
,D/ConnectivityService( 3523):    accepting network in place of null
D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 503 for uid 1000
,E/CSLegacyTypeTracker( 3523): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 3523): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 3523): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): Validated
,D/TelephonyNetworkFactory( 3982): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService( 3523): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/EntConnectivity( 3523): Not allowed due to - mEnabled false
D/ConnectivityService( 3523): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 3692): CM callback handler got msg 524290
D/ConnectivityService( 3523): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3523): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3523): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityManager.CallbackHandler( 6670): CM callback handler got msg 524290
D/ConnectivityService( 3523): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 3523): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/Tethering( 3523): MasterInitialState.processMessage what=3
D/SmartBondingService( 3523): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService( 3523): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/ConnectivityManager.CallbackHandler( 3692): CM callback handler got msg 524290
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/ConnectivityManager.CallbackHandler( 6670): CM callback handler got msg 524290
D/NetworkStatsFactory( 3523): UpdateStatsForKnox
V/NetworkStats( 3523): updateIfacesLocked()
V/NetworkStats( 3523): performPollLocked(flags=0x1)
,D/SmartBondingService( 3523): getNetworkEnabled : wifi : true mobile : false
,V/NetworkStats( 3523): performPollLocked() took 2ms
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
I/WifiStateMachine( 3523): callSECApi what=220
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/WifiStateMachine( 3523): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
,V/NetworkStats( 3523): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3692): updateDataNetType()
D/StatusBar.NetworkController( 3692): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3692): updateLTEICONDataNetType:0
,I/SignOutReceiver(11654): NETWORK_STATE_CHANGED_ACTION
,D/StatusBar.NetworkController( 3692): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3692): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3692): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3692): updateDataNetType()
D/StatusBar.NetworkController( 3692): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3692): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3692): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3692): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3692): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,I/SurfaceFlinger( 2850): id=14 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 3523): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3523
,D/mali_winsys( 3692): new_window_surface returns 0x3000,  [1120x201]-format:1
,I/jxcore-log(12099): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log(12099): 
,I/jxcore-log(12099): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log(12099): 
,I/jxcore-log(12099): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log(12099): 
,I/jxcore-log(12099): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log(12099): 
,D/ConnectivityService( 3523): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3523): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3523): SmartBondingReceiver: wifi is connected
D/SmartBondingService( 3523): SmartBondingReceiver: wifi ap is not changed
D/SmartBondingService( 3523): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
,D/SmartBondingService( 3523): getNetworkEnabled : wifi : true mobile : false
,D/GpsLocationProvider( 3523): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 6273): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 6273): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,W/ResourceType( 5326): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5326): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,I/NetworkMonitor(12237): type=WIFI subType= reason=null isConnected=true
,I/PCWCLIENTTRACE_PushUtil(12214): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(12214): sales region : global
I/PCWCLIENTTRACE_PushUtil(12214): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(12214): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/SecContentProvider2( 3523): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3523): mCursor = null
,I/DIAGMON_AGENT(12296): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(12296): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/FOTA_Client(12312): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(12312): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(12312): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.521: (12329): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Feb 02 17:18:06 GMT+01:00 2016
,I/KLMS-2.4.521: (12329): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (12329): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12329): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (12329): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (12329): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12329): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
I/KLMS-2.4.521: (12329): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.521: (12329): StateImplV2(): networkChangeListener().START
I/KLMS-2.4.521: (12329): NetworkChangeOperations(): uploadRequestLog().START 
,I/SO_AGENT(12352): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,I/KLMS-2.4.521: (12329): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.4.521: (12329): StateImplV2(): networkChangeListener().END
,I/KLMS-2.4.521: (12329): KLMSIntentService(): onDestroy()
,E/SPPClientService(12387): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      (11457): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11457): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (11457): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (11457): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11457): [OR] == isSIMCardReady false ==
,I/SA      (11457): [SCU] == networkStateCheck == true
I/SA      (11457): [DM] getCountryCodeFromCSC : PL
I/SA      (11457): isChinaCountryCode : false
I/SA      (11457): [SCU] is ChinestModel Data Restricted   : false
I/SA      (11457): [OR] == networkStateCheck true ==
,I/SA      (11457): [OR] GetMyCountryZoneTask
I/SA      (11457): [OR] onReceive END
,I/SA      (11457): [SRS] prepareGetMyCountryZone
,I/SA      (11457): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (11457): [SSP] query invoked
,V/DownloadManager( 5749): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      (11457): [TPMU] GetMccFromDB : null
I/SA      (11457): [SCU] getMccFromPreferece mcc = 260
I/SA      (11457): [TPM] isNoProxy(default) : true
,I/SCloudBackupReceiver(12407): Other Intent
,D/accuweather( 5100): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3776): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,D/accuweather( 5100): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5100): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
,D/accuweather( 5100): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
,D/accuweather( 5100): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5100): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5100): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro(12423): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro(12423): premStatus:2
,I/KnoxUsageLogPro(12423): isEulaShown : false
I/KnoxUsageLogPro(12423): KnoxUsageReceiver onReceive : not Processible, just return
,D/KeyguardWallpaperUpdator(12454): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12454): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12454): stopCheckCategoryVersion
,D/QuickConnect(12539): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12539): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect(12539): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 3523): exchangeData() failure , invalid userId
,D/RCPManagerService( 3523): exchangeData() failure , invalid userId
,I/iu.Environment( 6670): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 6670): num queued entries: 0
,I/iu.UploadsManager( 6670): num updated entries: 0
I/iu.SyncManager( 6670): NEXT; no task
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 503 for uid 10014
,D/WaitQueueForNetworkActivate(12611): notifyNetworkActivated
,W/ContextImpl(12611): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3523): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/hcjo    (12611): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12611): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12611): exit::IDLE
D/InitializeManagerStateMachine(12611): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12611): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12611): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12611): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12611): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12611): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12611): entry::SUCCESS
D/hcjo    (12611): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    (12611): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12611): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine(12611): exit::SUCCESS
D/InitializeManagerStateMachine(12611): entry::IDLE
,I/SA      (11457): [RC New] Execute method=[GET] start
,I/SA      (11457): [RC New] Security=[true]
,I/System.out(11457): Thread-1570(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out(11457): Thread-1570(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11457): Thread-1570(ApacheHTTPLog):isShipBuild true
I/System.out(11457): Thread-1570(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 503 for uid 10045
,D/ConnectivityService( 3523): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,E/Watchdog( 3523): !@Sync 8
I/SA      (11457): [RC New] [v2liruge] api execute + 945
I/SA      (11457): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out(11457): AsyncTask #1 calls detatch()
I/SA      (11457): [TPMU] getNetworkMcc : 
I/SA      (11457): [SCU] saveMccToPreferece Start
I/SA      (11457): [SCU] RegionMCC : 260
I/SA      (11457): [SSP] query invoked
,I/art     ( 3523): Explicit concurrent mark sweep GC freed 52910(2MB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 48MB/64MB, paused 1.242ms total 73.284ms
,I/SA      (11457): [TPMU] GetMccFromDB : null
I/SA      (11457): [SCU] getMccFromPreferece mcc = 260
I/SA      (11457): [SCU] saveMccToPreferece End
,I/SA      (11457): [RC New] executeRequest [v2liruge] end. 1038
I/SA      (11457): [RC New] Execute end
I/SA      (11457): [OR] GetMyCountryZoneTask mcc = 260
I/SA      (11457): [OR] GetMyCountryZoneTask Success
,I/dhcpcd  (12328): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (12328): wlan0: sendmsg: Cannot assign requested address
,D/WearableService( 4644): callingUid 10014, callindPid: 4644
,D/ResourcesManager(12237): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(12237): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(12237): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory(12237): Using the GMSCore's GoogleHttpClient
,I/MusicLeanback(12237): Conditions not met for autocaching.
I/MusicLeanback(12237): Stop autocaching.
,D/WearableClient(12237): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(12237): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(12237): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(12237): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(12237): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils(12237): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/ActivityThread(12237): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@1b682d2c that was originally bound here
E/ActivityThread(12237): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@1b682d2c that was originally bound here
E/ActivityThread(12237): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(12237): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(12237): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(12237): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(12237): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(12237): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(12237): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(12237): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(12237): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(12237): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(12237): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(12237): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(12237): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(12237): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(12237): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(12237): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(12237): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(12237): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(12237): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(12237): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(12237): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(12237): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(12237): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(12237): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(12237): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/WifiStateMachine( 3523): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine( 3523): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,D/SSRM:n  ( 3523): SIOP:: AP = 280, PST = 246, CUR = 32
,I/jxcore-log(12099): Test app app.js loaded
I/jxcore-log(12099): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(12099): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(12099): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(12099): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(12099): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(12099): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(12099): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(12099): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(12099): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(12099): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(12099): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@363e4498 added. We now have 1 listener(s)
,I/jxcore-log(12099): BLE advertisement is supported
I/jxcore-log(12099): 
,I/chromium(12099): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/SurfaceFlinger( 2850): id=14 Removed Uoast (8/9)
I/SurfaceFlinger( 2850): id=14 Removed Uoast (-2/9)
,D/PowerManagerService( 3523): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3523) eventTime = 254689
,D/PowerManagerService( 3523): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3523 (0x0)
D/PowerManagerService( 3523): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3523, ws=WorkSource{10060}) (elapsedTime=3480)
,E/WifiStateMachine( 3523): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3523): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityService( 3523): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,V/        ( 2846): QcRouteController
,D/SmartBondingService( 3523): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
D/SmartBondingService( 3523): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
,V/        ( 2846): QcRouteController
,W/NetworkManagementService( 3523): route cmd failed: 
W/NetworkManagementService( 3523): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '76 route replace src v6 wlan0 fe80::92b6:86ff:fe43:731c 2 ::' failed with '400 76 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService( 3523): '
W/NetworkManagementService( 3523): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService( 3523): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService( 3523): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService( 3523): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService( 3523): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService( 3523): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5738)
W/NetworkManagementService( 3523): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5545)
W/NetworkManagementService( 3523): 	at com.android.server.ConnectivityService.access$2600(ConnectivityService.java:231)
W/NetworkManagementService( 3523): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2436)
W/NetworkManagementService( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ConnectivityService( 3523): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3692): CM callback handler got msg 524295
,D/ConnectivityService( 3523): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3692): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 6670): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 6670): CM callback handler got msg 524295
,I/GAV4    (12471): Thread[GAThread,5,main]: No campaign data found.
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:-253, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:61
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/PackageManager( 3523): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/PCWCLIENTTRACE_SYSTEMReceiver(12214): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil(12214): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE(12214): ================================================
,I/CSTORAGE(12214):  CSTORAGE_SKM_LIB v1.0.15
I/CSTORAGE(12214): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI(12214): [GetString-S]
E/art     (12214): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI(12214): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI(12214): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil(12214): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil(12214): sales region : global
I/PCWCLIENTTRACE_PushUtil(12214): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler(12214): [ensureRegistration] - No Samsung account
,I/dhcpcd  (12328): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  (12328): wlan0: sending IPv6 Router Solicitation,
,I/dhcpcd  (12328): wlan0: no IPv6 Routers available
,D/PreloadUpdateManagerStateMachine(12611): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(12611): exit::IDLE
D/PreloadUpdateManagerStateMachine(12611): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (12611): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    (12611): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine(12611): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine(12611): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine(12611): entry::IDLE
,D/SSRM:n  ( 3523): SIOP:: AP = 270, PST = 247, CUR = -253
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:-62, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:50
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ActivityManager( 3523): Waited long enough for: ServiceRecord{328c4796 u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 248, CUR = -62
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:53
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3523): !@Sync 9
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 249, CUR = 7
,I/art     ( 4644): Explicit concurrent mark sweep GC freed 78327(4MB) AllocSpace objects, 34(1479KB) LOS objects, 34% free, 30MB/46MB, paused 1.975ms total 68.285ms
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3523): [PWL] Off : 225s ago
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 250, CUR = 30
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:45
,D/BatteryService( 3523): stay LED for fully charged
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 250, CUR = 37
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService( 3523): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3523): TimaServiceHandler.handleMessage what =1
,D/TimaService( 3523): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize( 3523): initializing...
,I/TLC_TIMA_PKM_initialize( 3523): root = 0, root_strlen = 1
I/TLC_TIMA_PKM_initialize( 3523): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 3523): input max_sendmsg_size = 262196
,I/TZ: mc_tlc_communication( 3523): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 3523): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 3523): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 3523): aligned max_sendmsg_size = 262208
,I/TZ: mc_tlc_communication( 3523): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 3523): device_id = 0x0
I/TZ: mc_tlc_communication( 3523): tlc_open() was called
I/TZ: mc_tlc_communication( 3523): Opening MobiCore device
,I/TZ: mc_tlc_communication( 3523): Allocating WSM for TCI
,I/TZ: mc_tlc_communication( 3523): Opening the session
,I/TZ: mc_tlc_communication( 3523): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 3523): Trustlet response is completed
,E/Watchdog( 3523): !@Sync 10
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 251, CUR = 37
,I/TLC_TIMA_PKM_measure_kernel( 3523): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3523): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3523): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3523): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:38, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:52
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 251, CUR = 38
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:36, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 251, CUR = 36,
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3523): [PWL] Off : 275s ago
,E/Watchdog( 3523): !@Sync 11
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 251, CUR = 32
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:33, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:42
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 248, CUR = 33
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:34
D/BatteryService( 3523): stay LED for fully charged
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 246, CUR = 32
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3523): !@Sync 12
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 245, CUR = 30
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 245, CUR = 27
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3523): [PWL] Off : 330s ago
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 244, CUR = 27
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3523): !@Sync 13
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 243, CUR = 27
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3523): stay LED for fully charged
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 243, CUR = 27
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 242, CUR = 26
,V/AlarmManager( 3523): waitForAlarm result :8
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3523): !@Sync 14
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 242, CUR = 26
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 241, CUR = 26
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3523): [PWL] Off : 390s ago
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 240, CUR = 25
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3523): !@Sync 15
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 240, CUR = 24
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 240, CUR = 24
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 240, CUR = 24
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3523): !@Sync 16
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 240, CUR = 23,
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 240, CUR = 23
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 240, CUR = 22
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3523): [PWL] Off : 455s ago
,E/Watchdog( 3523): !@Sync 17
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 240, CUR = 20
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 240, CUR = 22
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 240, CUR = 21
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3523): !@Sync 18
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 240, CUR = 22
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 240, CUR = 21
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 240, CUR = 20
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3523): !@Sync 19
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 240, CUR = 20
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3523): [PWL] Off : 525s ago
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 240, CUR = 18
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 240, CUR = 18
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,D/BatteryService( 3523): stay LED for fully charged
I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 3523): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3523): TIMA: checkEvent, operation: 50000 subject: 10000,
,D/TimaService( 3523): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 3523): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 3523): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3523): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3523): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3523): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 240, CUR = 18,
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 240, CUR = 17
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ActivityManager( 3523): Killing 11747:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 240, CUR = 16
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3523): !@Sync 21,
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 240, CUR = 17
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 240, CUR = 17
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3523): [PWL] Off : 600s ago
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 240, CUR = 17
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3523): !@Sync 22
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 240, CUR = 18
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 240, CUR = 18,
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 240, CUR = 20
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3523): !@Sync 23
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 239, CUR = 20
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 239, CUR = 16
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
D/BatteryService( 3523): stay LED for fully charged
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged,
I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 239, CUR = 17,
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3523): !@Sync 24
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 238, CUR = 16
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3523): [PWL] Off : 680s ago
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 238, CUR = 18
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
I/MotionRecognitionService( 3523): setPowerConnected  = true
D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 238, CUR = 17,
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3523): !@Sync 25
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 237, CUR = 16
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 237, CUR = 16
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 237, CUR = 14
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3523): !@Sync 26
,V/AlarmManager( 3523): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3692): handleTimeUpdate
,D/KeyguardEffectViewController( 3692): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3692): *** don't update sliding image ***
,D/LightsService( 3523): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,I/Sensors ( 3523): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager( 3523): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 6670): Aggregate from 1454428451063 (log), 1454428451063 (data)
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/Sensors ( 3523): #>LightSensor r=0 g=0 b=1 c=2 atime=238 again=64 lux=0.000000
,D/LightsService( 3523): [SvcLED]  onSensorChanged::light value = 0
I/Sensors ( 3523): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager( 3523): unregisterListener ::   
D/LightsService( 3523): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 236, CUR = 15
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,W/ProcessCpuTracker( 3523): Skipping unknown process pid 13163
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4400, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 236, CUR = 15
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 236, CUR = 15
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3523): !@Sync 27
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 235, CUR = 15
,I/PowerManagerService( 3523): [PWL] Off : 765s ago
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 235, CUR = 13,
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3523): waitForAlarm result :8
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 235, CUR = 14
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!,
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3523): !@Sync 28
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 234, CUR = 13
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 234, CUR = 14
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 234, CUR = 14
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3523): !@Sync 29
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 233, CUR = 14
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-9
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 233, CUR = 12
,V/AlarmManager( 3523): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3692): handleTimeUpdate
,D/KeyguardEffectViewController( 3692): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 3692): *** don't update sliding image ***
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3523): waitForAlarm result :8
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 233, CUR = 13,
,D/TimaService( 3523): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3523): TIMA: checkEvent, operation: 50000 subject: 10000,
,D/TimaService( 3523): TimaServiceHandler.handleMessage what =1,
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3523): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 3523): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3523): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3523): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3523): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 232, CUR = 14
,I/PowerManagerService( 3523): [PWL] Off : 855s ago
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 232, CUR = 13
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 232, CUR = 12
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
I/MotionRecognitionService( 3523): setPowerConnected  = true
D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3523): !@Sync 31
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 231, CUR = 13
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 231, CUR = 13
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 231, CUR = 11
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3523): !@Sync 32
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3523): !@Sync 33
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 230, CUR = 14
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3523): [PWL] Off : 950s ago
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3523): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 230, CUR = 15
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3523): !@Sync 34
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 230, CUR = 13
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 230, CUR = 13,
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 230, CUR = 12
,E/Watchdog( 3523): !@Sync 35
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
I/MotionRecognitionService( 3523): setPowerConnected  = true
D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 230, CUR = 8
,E/Watchdog( 3523): !@Sync 36
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 3523): [PWL] Off : 1050s ago
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 230, CUR = 10
,E/Watchdog( 3523): !@Sync 37
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-10
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 230, CUR = 10
,E/Watchdog( 3523): !@Sync 38
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-1
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3523): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 230, CUR = 10,
,E/Watchdog( 3523): !@Sync 39
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
D/BatteryService( 3523): stay LED for fully charged
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 230, CUR = 10
,D/TimaService( 3523): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3523): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 3523): TimaServiceHandler.handleMessage what =1,
,I/UsageStatsService( 3523): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 3523): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 3523): Updating Usage Statistics in DB @ 1454430845756
,I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
,W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
,W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
,W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
,W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	,at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134),
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
,W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	,at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	,at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	,at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
,W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	,at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
,W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
,W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	,at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
,W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3523): ::getAppControlDB: Exception to create DB
W/System.err( 3523): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3523): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage( 3523): Done Updating Usage Statistics in DB @ 1454430845832
,E/Watchdog( 3523): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 3523): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3523): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3523): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3523): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-7
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
I/MotionRecognitionService( 3523): Plugged
I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 230, CUR = 9
,I/PowerManagerService( 3523): [PWL] Off : 1155s ago
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 230, CUR = 9
,E/Watchdog( 3523): !@Sync 41
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 230, CUR = 8,
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 230, CUR = 9
,E/Watchdog( 3523): !@Sync 42
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 230, CUR = 9
,E/Watchdog( 3523): !@Sync 43
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 230, CUR = 9,
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 230, CUR = 9
,I/PowerManagerService( 3523): [PWL] Off : 1265s ago
,E/Watchdog( 3523): !@Sync 44
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 230, CUR = 9
,E/Watchdog( 3523): !@Sync 45
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3523): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 230, CUR = 8
,E/Watchdog( 3523): !@Sync 46
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-9
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 230, CUR = 9
,E/Watchdog( 3523): !@Sync 47
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-5
,D/BatteryService( 3523): stay LED for fully charged
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 230, CUR = 9
,I/PowerManagerService( 3523): [PWL] Off : 1380s ago
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 230, CUR = 10
,E/Watchdog( 3523): !@Sync 48
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 230, CUR = 8,
,TIME-OUT KILL (timeout was 1200000ms)
```
