#### Test 58380500306a2c5_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
D/BatteryService( 3505): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3505): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3505): online:4, current avg:47, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
D/BatteryService( 3505): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3505): stay LED for fully charged
--------- beginning of main
D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
I/MotionRecognitionService( 3505): Plugged
I/MotionRecognitionService( 3505): setPowerConnected  = true
D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 5644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5644): Disconnected process message: 10
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AndroidRuntime(11926): 
D/AndroidRuntime(11926): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11926): CheckJNI is OFF
D/AndroidRuntime(11926): readGMSProperty: start
D/AndroidRuntime(11926): readGMSProperty: already setted!!
D/AndroidRuntime(11926): readGMSProperty: end
D/AndroidRuntime(11926): addProductProperty: start
E/AffinityControl(11926): AffinityControl: registerfunction enter
D/AndroidRuntime(11926): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3505): inState():  stateMachine is null !!
I/PersonaManagerService( 3505): PersonaId don't exist
I/ActivityManager( 3505): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3505): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3505): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3505): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager( 3505): mDVFSHelper.acquire()
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/Zygote  (11944): MountEmulatedStorage()
I/libpersona(11944): KNOX_SDCARD checking this for 10651
E/Zygote  (11944): v2
I/libpersona(11944): KNOX_SDCARD not a persona
I/SELinux (11944): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3505): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=11944 uid=10651 gids={50651, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux (11944): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/AndroidRuntime(11926): Shutting down VM
E/SELinux (11944): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon( 3505): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3505): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3505): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3505): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(11944): TimaSignature is unavailable
D/ActivityThread(11944): Added TimaKeyStore provider
I/SurfaceFlinger( 2853): id=11 Removed YUIInstallC (5/8)
I/SurfaceFlinger( 2853): id=11 Removed YUIInstallC (-2/8)
D/ResourcesManager(11944): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
V/ActivityThread( 6235): updateVisibility : ActivityRecord{26bc16d8 token=android.os.BinderProxy@2731c435 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
I/WebViewFactory(11944): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(11944): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(11944): Loading: webviewchromium
I/LibraryLoader(11944): Time to load native libraries: 3 ms (timestamps 6137-6140)
I/LibraryLoader(11944): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider(11944): Binding Chromium to main looper Looper (main, tid 1) {2e4b308b}
I/LibraryLoader(11944): Expected native library version number "",actual native library version number ""
I/chromium(11944): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(11944): Initializing chromium process, renderers=0
,W/art     (11944): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(11944): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(11944): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(11944): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,W/chromium(11944): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(11944): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (11944): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(11944): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(11944): CordovaWebView is running on device made by: samsung
,W/art     (11944): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11944): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity(11944): performCreate Call secproduct feature valuefalse
D/Activity(11944): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(11944): Render dirty regions requested: true
,D/ActivityManager( 3505): post active user change for 0
D/KnoxTimeoutHandler( 3505): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3505): handleActiveUserChange for user 0
,I/SurfaceFlinger( 2853): id=14 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService( 3505): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3505): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3505): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3505): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3505): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3505): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer(11944): Initialized EGL, version 1.4
,I/OpenGLRenderer(11944): HWUI protection enabled for context ,  &this =0xaf645060 ,&mEglDisplay = 1 , &mEglConfig = -1278775024 
,D/OpenGLRenderer(11944): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(11944): Enabling debug mode 0
,D/mali_winsys(11944): new_window_surface returns 0x3000,  [1440x2560]-format:1
,V/ActivityThread(11944): updateVisibility : ActivityRecord{28cd527b token=android.os.BinderProxy@3c91634e {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/InputMethodManagerService( 3505): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3505): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 3505): mDVFSHelper.release()
,I/Timeline( 3505): Timeline: Activity_windows_visible id: ActivityRecord{35af1cd0 u0 com.test.thalitest/.MainActivity t26} time:236592
,W/IInputConnectionWrapper(11944): showStatusIcon on inactive InputConnection
,I/Timeline(11944): Timeline: Activity_idle id: android.os.BinderProxy@3c91634e time:236604
,I/chromium(11944): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11944): 
,D/JsMessageQueue(11944): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log(11944): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1259353344
,I/chromium(11944): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log(11944): Initializing JXcore engine
W/jxcore-log(11944): JXcore engine is ready
E/auditd  ( 4615): In denial and Property audit_ondenial is set to 1 
D/SecurityLogAgent:SEDenialService( 3505): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl( 3505): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
D/SecurityLogAgent:SEDenialService( 3505): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
W/jxcore-log(11944): Starting JXcore engine
W/jxcore-log(11944): Platform android
W/jxcore-log(11944): 
W/jxcore-log(11944): Process ARCH arm
W/jxcore-log(11944): 
I/jxcore-log(11944): JXcore Cordova bridge is ready!
I/jxcore-log(11944): 
W/jxcore-log(11944): JXcore engine is started
I/jxcore-log(11944): Toggling radios to true
I/jxcore-log(11944): 
D/BluetoothAdapter(11944): enable()
D/BluetoothAdapter(11944): enable(): BT is already enabled..!
D/WifiService( 3505): New client listening to asynchronous messages
I/WifiManager(11944): packageName : com.test.thalitest
D/SecContentProvider( 3505): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3505): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3505): mCursor = null
D/WifiService( 3505): setWifiEnabled: true pid=11944, uid=10651
E/WifiService( 3505): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3505): Permission Denial: getCurrentUser() from pid=11944, uid=10651 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3505): Failed getting userId using ActivityManagerNative
W/WifiService( 3505): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=11944, uid=10651 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3505): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3505): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3505): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3505): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3505): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider( 3505): name = wifi_on
I/WifiService( 3505): disconnect: pid=11944, uid=10651
I/wpa_supplicant( 3834): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log(11944): Radios toggled
I/jxcore-log(11944): 
I/jxcore-log(11944): My device name is: samsung-SM-N910C
I/jxcore-log(11944): 
I/wpa_supplicant( 3834): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant( 3834): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 3834): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3834): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine( 3505): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 3834): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3834): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3834): Disconnected - do not scan
I/wpa_supplicant( 3834): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine( 3505): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3505): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3505): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3505): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiStateMachine( 3505): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine( 3505): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3505): do suspend true
D/WifiP2pService( 3505): InactiveState{ what=143375 }
D/WifiP2pService( 3505): P2pEnabledState{ what=143375 }
D/CommandListener( 2847): Clearing all IP addresses on wlan0
E/Netd    ( 2847): ifc_reset_connections failed on iface wlan0 for address 192.168.1.124/24 (Unknown error -1)
D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
E/WifiStateMachine( 3505): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiConfigStore( 3505): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/ConnectivityService( 3505): updateNetworkInfo()
D/ConnectivityService( 3505): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3505): updateNetworkInfo()
D/ConnectivityService( 3505): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
I/WifiTrafficPoller( 3505): evaluateTrafficStatsPolling
D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
I/Hs20UtilService( 4056): Starting #8
I/Hs20UtilService( 4056): Message received 5007
E/WifiStateMachine( 3505): Start Disconnecting Watchdog 1
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
I/wpa_supplicant( 3834): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3834): P2P: Current p2p state = IDLE
I/wpa_supplicant( 3834): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 3834): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3834): First Scan Start
E/WifiStateMachine( 3505): ConnectModeState: Network connection lost 
E/WifiStateMachine( 3505): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - processMessage - processMsg
E/WifiStateMachine( 3505): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine( 3505): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3505): do suspend true
I/wpa_supplicant( 3834): Scan requested (ret=0) - scan timeout 30 seconds
D/WifiP2pService( 3505): InactiveState{ what=143375 }
D/WifiP2pService( 3505): P2pEnabledState{ what=143375 }
E/Zygote  (12036): MountEmulatedStorage()
E/Zygote  (12036): v2
I/libpersona(12036): KNOX_SDCARD checking this for 1000
I/libpersona(12036): KNOX_SDCARD not a persona
I/ActivityManager( 3505): Start proc com.android.settings for broadcast com.android.settings/.nearby.MountReceiver: pid=12036 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux (12036): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12036): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12036): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
D/TimaKeyStoreProvider(12036): TimaSignature is unavailable
D/ActivityThread(12036): Added TimaKeyStore provider
D/CommandListener( 2847): Clearing all IP addresses on wlan0
D/ConnectivityService( 3505): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/EntConnectivity( 3505): Not allowed due to - mEnabled false
E/WifiStateMachine( 3505): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityManager.CallbackHandler( 3693): CM callback handler got msg 524292
D/WifiStateMachine( 3505): updateConfiguredNetworkExpiration - currTime: 1455058391460
D/ConnectivityService( 3505): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiStateMachine( 3505): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
E/WifiStateMachine( 3505): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine( 3505): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/CSLegacyTypeTracker( 3505): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3505): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker( 3505): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityManager.CallbackHandler( 6758): CM callback handler got msg 524292
D/ConnectivityService( 3505): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine( 3505): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3505): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent( 3505): NetworkAgent: NetworkAgent channel lost
I/WifiTrafficPoller( 3505): evaluateTrafficStatsPolling
D/TelephonyNetworkFactory( 3979): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine( 3505): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3505): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine( 3505): setDetailed state send new extra info"NG700"
D/SecContentProvider2( 3505): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3505): mCursor = null
D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
D/EntConnectivity( 3505): Not allowed due to - mEnabled false
D/ConnectivityService( 3505): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/SecContentProvider2( 3505): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3505): mCursor = null
D/Tethering( 3505): MasterInitialState.processMessage what=3
D/SmartBondingService( 3505): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService( 3505): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
V/NetworkStats( 3505): updateIfacesLocked()
D/NtpTrustedTime( 3505): currentTimeMillis() cache hit
V/NetworkStats( 3505): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 3505): UpdateStatsForKnox
D/SmartBondingService( 3505): getSBEnabled() enabled =false
D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3693): updateDataNetType()
D/StatusBar.NetworkController( 3693): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3693): updateLTEICONDataNetType:0
D/NtpTrustedTime( 3505): currentTimeMillis() cache hit
D/NtpTrustedTime( 3505): currentTimeMillis() cache hit
D/NtpTrustedTime( 3505): currentTimeMillis() cache hit
D/ResourcesManager(12036): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
V/NetworkStats( 3505): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3505): currentTimeMillis() cache hit
D/SmartBondingService( 3505): getSBEnabled() enabled =false
D/SmartBondingService( 3505): getSBEnabled() enabled =false
W/ResourcesManager(12036): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager(12036): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12036): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager(12036): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12036): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12036): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12036): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
V/NetworkStats( 3505): performPollLocked() took 11ms
D/NtpTrustedTime( 3505): currentTimeMillis() cache hit
D/SmartBondingService( 3505): getNetworkEnabled : wifi : true mobile : false
D/StatusBar.NetworkController( 3693): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/NtpTrustedTime( 3505): currentTimeMillis() cache hit
D/NtpTrustedTime( 3505): currentTimeMillis() cache hit
D/MySettingsProvider(12036): DatabaseHelper(Context context):DATABASE_VERSION=1
E/SQLiteLog(12036): (283) recovered 10 frames from WAL file /data/data/com.android.settings/databases/mysettings.db-wal
D/MySettingsProvider(12036): onCreate():(mDB == null)? false:true  =true
D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
D/NearbySettings(12036): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings(12036): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings(12036): MountReceiver.onReceive - Create mPrefHandler
D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
D/NearbySettings(12036): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
V/NearbySettings(12036): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings(12036): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/WifiService( 3505): New client listening to asynchronous messages
I/NearbySettings(12036): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings(12036): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings(12036): MountReceiver.onReceive - Set preference state off
V/NearbySettings(12036): MountReceiver.mPrefHandler - 7002
I/ActivityManager( 3505): Killing 11084:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
I/SignOutReceiver(11225): NETWORK_STATE_CHANGED_ACTION
I/Hs20UtilService( 4056): Starting #9
I/Hs20UtilService( 4056): Message received 5007
D/NearbySettings(12036): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings(12036): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings(12036): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings(12036): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings(12036): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings(12036): MountReceiver.onReceive - Set preference state off
V/NearbySettings(12036): MountReceiver.mPrefHandler - 7002
I/SignOutReceiver(11225): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService( 3505): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 3505): updateDataUsageMap
I/ApplicationPolicy( 3505): updateDataUsageMap  idList is null 
,D/SmartBondingService( 3505): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3505): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3505): getSBEnabled() enabled =false
D/SmartBondingService( 3505): getSBEnabled() enabled =false
D/SmartBondingService( 3505): getSBEnabled() enabled =false
,D/GpsLocationProvider( 3505): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3505): getNetworkEnabled : wifi : true mobile : false
,W/SLocation( 3505): No Active Data Connection
,I/DBG_DM  ( 6235): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/DBG_DM  ( 6235): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12071): MountEmulatedStorage()
E/Zygote  (12071): v2
I/libpersona(12071): KNOX_SDCARD checking this for 10110
I/libpersona(12071): KNOX_SDCARD not a persona
,I/SELinux (12071): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12071): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12071): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3505): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.iorg.vpn.cleanup.NetworkStateMonitor: pid=12071 uid=10110 gids={50110, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 8736(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 293us total 10.183ms
,D/TimaKeyStoreProvider(12071): TimaSignature is unavailable
,D/ActivityThread(12071): Added TimaKeyStore provider
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 277us total 8.412ms
,D/ResourcesManager(12071): creating new AssetManager and set to /data/app/com.facebook.appmanager-2/base.apk
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 504us total 8.280ms
,D/ACRA    (12071): ACRA is enabled for com.facebook.appmanager, intializing...
,I/DexLibLoader(12071): not using cross-dex optimization: ART in use
,I/art     (12071): Thread[1,tid=12071,WaitingForJniOnLoad,Thread*=0xb4e08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/app/com.facebook.appmanager-2/lib/arm/libfbjni.so"
,V/DexLibLoader(12071): about to lock: /data/data/com.facebook.appmanager/mdex_lock
,V/DexLibLoader(12071): locking /data/data/com.facebook.appmanager/mdex_lock took 1 ms
V/DexLibLoader(12071): Secondary program dex metadata: classes2.dex 29f80981f469a774a4884b3db2df17e0be227159 secondary.dex01.Canary
,D/DexLibLoader(12071): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex" is valid
D/DexLibLoader(12071): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex_opt" is valid
,W/art     (12071): Attempt to remove local handle scope entry from IRT, ignoring
,D/DexLibLoader(12071): loading pre-built fallback odex files
V/MultiDexClassLoader(12071): installing MultiDexClassLoader before application classloader
D/DexLibLoader(12071): released odex store lock
D/DexLibLoader(12071): DexLibLoader.loadAll took 16 ms
,W/ca      (12071): Verify
,W/LightSharedPreferencesImpl(12071): Failed to load preference file from Disk!
W/LightSharedPreferencesImpl(12071): java.io.FileNotFoundException: /data/data/com.facebook.appmanager/app_light_prefs/com.facebook.appmanager/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(12071): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/LightSharedPreferencesImpl(12071): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/LightSharedPreferencesImpl(12071): 	at com.facebook.crudolib.b.k.a(LightSharedPreferencesStorage.java:56)
W/LightSharedPreferencesImpl(12071): 	at com.facebook.crudolib.b.g.run(LightSharedPreferencesImpl.java:61)
W/LightSharedPreferencesImpl(12071): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/LightSharedPreferencesImpl(12071): 	at com.facebook.common.executors.dj.run(WrappingExecutorService.java:77)
W/LightSharedPreferencesImpl(12071): 	at com.facebook.common.executors.u.run(DefaultConstrainedListeningExecutorService.java:327)
W/LightSharedPreferencesImpl(12071): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/LightSharedPreferencesImpl(12071): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/LightSharedPreferencesImpl(12071): 	at com.facebook.common.executors.cc.run(NamedThreadFactory.java:42)
W/LightSharedPreferencesImpl(12071): 	at java.lang.Thread.run(Thread.java:818)
W/LightSharedPreferencesImpl(12071): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(12071): 	at libcore.io.Posix.open(Native Method)
W/LightSharedPreferencesImpl(12071): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/LightSharedPreferencesImpl(12071): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/LightSharedPreferencesImpl(12071): 	... 10 more
,E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12096): MountEmulatedStorage()
I/libpersona(12096): KNOX_SDCARD checking this for 1000
E/Zygote  (12096): v2
I/libpersona(12096): KNOX_SDCARD not a persona
,I/SELinux (12096): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12096): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12096): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3505): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=12096 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3505): Killing 11103:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,W/appmanager(:<default>):b(12071): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/appmanager(:<default>):b(12071): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/TimaKeyStoreProvider(12096): TimaSignature is unavailable
,D/ActivityThread(12096): Added TimaKeyStore provider
,D/ResourcesManager(12096): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/PCWCLIENTTRACE_LOG(12096): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(12096): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(12096): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil(12096): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(12096): sales region : global
I/PCWCLIENTTRACE_PushUtil(12096): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(12096): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver(12096): noConnectivity : true
,E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
,W/appmanager(:<default>):QuickExperimentControllerImpl(12071): Exposure of experiment com.facebook.common.network.l@83eb859 occurred when no user was logged in
,E/Zygote  (12118): MountEmulatedStorage()
I/libpersona(12118): KNOX_SDCARD checking this for 10135
E/Zygote  (12118): v2
I/libpersona(12118): KNOX_SDCARD not a persona
,I/SELinux (12118): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12118): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12118): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3505): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=12118 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3505): Killing 11121:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
,W/BroadcastQueue( 3505): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{3ebe292 u0 ReceiverList{906101d 12071 com.facebook.appmanager/10110/u0 remote:379ba0f4}}
,W/BroadcastQueue( 3505): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{3ebe292 u0 ReceiverList{906101d 12071 com.facebook.appmanager/10110/u0 remote:379ba0f4}}
,D/TimaKeyStoreProvider(12118): TimaSignature is unavailable
,D/ActivityThread(12118): Added TimaKeyStore provider
,D/ResourcesManager(12118): creating new AssetManager and set to /system/app/Music2/Music2.apk
,W/BroadcastQueue( 3505): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{2d405378 u0 ReceiverList{52fbcdb 12071 com.facebook.appmanager/10110/u0 remote:2eed31ea}}
,I/MusicStore(12118): Database version: 104
,D/ResourcesManager(12118): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(12118): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(12118): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (12118): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(12118): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (12118): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@137c702f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(12118): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(12118): GMSCore installation verified
,I/ConfigStore(12118): Config Database version: 1
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12118): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
W/ContextImpl(12071): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
W/ContextImpl(12071): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12118): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12118): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/appmanager(:<default>):QuickExperimentControllerImpl(12071): Exposure of experiment com.facebook.imagepipeline.a.g@246a819e occurred when no user was logged in
,W/appmanager(:<default>):QuickExperimentControllerImpl(12071): Exposure of experiment com.facebook.imagepipeline.a.d@3ddde99b occurred when no user was logged in
,D/WifiDisplayAdapter( 3505): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3505): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/wpa_supplicant( 3834): nl80211: Received scan results (4 BSSes)
,I/wpa_supplicant( 3834): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3834): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3834): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 3834): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3505): [1,455,058,392,506 ms] noteScanEnd no scan source
I/AudioService( 3505): getStreamVolume 3 index 0
I/MediaRouter(12118): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
E/WifiStateMachine( 3505): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@17eb161a sup_state=SCANNING debouncing=false
,E/WifiStateMachine( 3505): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3505): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3505): setDetailed state send new extra info
D/SecContentProvider2( 3505): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3505): mCursor = null
,E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
,I/art     (12071): Explicit concurrent mark sweep GC freed 50604(2MB) AllocSpace objects, 6(96KB) LOS objects, 22% free, 27MB/35MB, paused 798us total 24.458ms
W/appmanager(:<default>):m(12071): No feature status reporters found; is this dead code?
,E/Zygote  (12154): MountEmulatedStorage()
I/libpersona(12154): KNOX_SDCARD checking this for 10002
E/Zygote  (12154): v2
I/libpersona(12154): KNOX_SDCARD not a persona
I/SELinux (12154): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12154): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12154): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3505): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=12154 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/WifiDisplayAdapter( 3505): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/NetworkMonitor(12118): type=WIFI subType= reason=null isConnected=false
,D/TimaKeyStoreProvider(12154): TimaSignature is unavailable
,D/ActivityThread(12154): Added TimaKeyStore provider
,I/ActivityManager( 3505): Killing 11136:com.samsung.helphub/1000 (adj 13): bgCount ##31
,D/ResourcesManager(12154): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/wpa_supplicant( 3834): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 3834): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3505): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3505): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3505): setDetailed state send new extra info"NG700"
I/wpa_supplicant( 3834): Associated with C0.AA.48
,D/SecContentProvider2( 3505): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3505): mCursor = null
,I/ActivityManager( 3505): Killing 11171:com.google.android.apps.plus/u0a147 (adj 13): bgCount ##31
,E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
,I/wpa_supplicant( 3834): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 3834): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3505): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3505): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,I/wpa_supplicant( 3834): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 3834): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,I/wpa_supplicant( 3834): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 3834): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/SecContentProvider2( 3505): uri = 20 selection = getPromptCredentialsEnabled
I/libpersona(12174): KNOX_SDCARD checking this for 1000
D/SecContentProvider2( 3505): mCursor = null
I/libpersona(12174): KNOX_SDCARD not a persona
E/Zygote  (12174): MountEmulatedStorage()
E/Zygote  (12174): v2
I/wpa_supplicant( 3834): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 3834): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/SELinux (12174): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/wpa_supplicant( 3834): Blacklist: Clear (temp) 
I/wpa_supplicant( 3834): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
I/SELinux (12174): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12174): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3505): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=12174 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/WifiStateMachine( 3505): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3505): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine( 3505): Network connection established
,D/WifiNative-HAL( 3505): callSECApiVoid - ID [50]
,E/WifiStateMachine( 3505): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine( 3505): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService( 3505): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine( 3505): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3505): L2ConnectedState "NG700" nid=0
E/WifiConfigStore( 3505): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService( 3505): hsengiv:checkWhatTypeOfNetwork and the value is false
D/TimaKeyStoreProvider(12174): TimaSignature is unavailable
D/ActivityThread(12174): Added TimaKeyStore provider
E/ConnectivityService( 3505): updateNetworkInfo()
,D/ConnectivityService( 3505): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3505): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine( 3505): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3505): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3505): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ResourcesManager(12174): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
I/art     ( 3505): Explicit concurrent mark sweep GC freed 66639(4MB) AllocSpace objects, 54(3MB) LOS objects, 24% free, 49MB/65MB, paused 3.210ms total 96.258ms
,D/CommandListener( 2847): Setting iface cfg
,E/WifiStateMachine( 3505): Start Dhcp Watchdog 2
,D/SecContentProvider2( 3505): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3505): mCursor = null
,E/WifiStateMachine( 3505): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3505): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/DIAGMON_AGENT(12174): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT(12174): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT(12174): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,E/WifiStateMachine( 3505): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3505): do suspend false
,I/DIAGMON_AGENT(12174): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(12174): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/SecContentProvider2( 3505): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3505): mCursor = null
,D/WifiP2pService( 3505): InactiveState{ what=143375 }
D/WifiP2pService( 3505): P2pEnabledState{ what=143375 }
,I/FOTA_Client(11437): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(11437): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(11437): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.521: (11470): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Feb 09 23:53:12 GMT+01:00 2016
,I/KLMS-2.4.521: (11470): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (11470): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11470): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (11470): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/SO_AGENT(11671): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,I/KLMS-2.4.521: (11470): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
I/KLMS-2.4.521: (11470): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (11470): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.521: (11470): StateImplV2(): networkChangeListener().END
,E/Zygote  (12195): MountEmulatedStorage()
E/Zygote  (12195): v2
I/libpersona(12195): KNOX_SDCARD checking this for 1000
I/libpersona(12195): KNOX_SDCARD not a persona
,I/SELinux (12195): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12195): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12195): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3505): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=12195 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/KLMS-2.4.521: (11470): KLMSIntentService(): onDestroy()
,I/ActivityManager( 3505): Killing 11245:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12195): TimaSignature is unavailable
,D/ActivityThread(12195): Added TimaKeyStore provider
,D/ResourcesManager(12195): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12215): MountEmulatedStorage()
I/libpersona(12215): KNOX_SDCARD checking this for 10039
E/Zygote  (12215): v2
I/libpersona(12215): KNOX_SDCARD not a persona
I/SELinux (12215): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12215): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12215): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3505): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=12215 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3505): Killing 11262:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12215): TimaSignature is unavailable
,D/ActivityThread(12215): Added TimaKeyStore provider
,D/ResourcesManager(12215): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/dhcpcd  (12230): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (12230): version 5.5.6 starting
,E/dhcpcd  (12230): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,E/SPPClientService(12215): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(12215): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService(12215): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,D/SPPClientService(12215): PushLog.txt file is not deleted.
D/SPPClientService(12215): PushLog.txt file is not deleted.
D/SPPClientService(12215): ============PushLog. stop!
,I/SA      (11015): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11015): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      (11015): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      (11015): [SLFUCHKMGR] constructor called
,E/SPPClientService(12215): [[SystemStateMonitorService]] No Active Internet
,I/SA      (11015): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11015): [OR] == isSIMCardReady false ==
,I/SA      (11015): [SCU] == networkStateCheck == false
I/SA      (11015): [OR] onReceive END
,I/ActivityManager( 3505): Killing 11281:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##31
,V/DownloadManager( 3717): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,E/lowmemorykiller( 2828): Error writing /proc/11281/oom_score_adj; errno=22
,I/dhcpcd  (12230): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (12230): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (12230): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  (12230): bssid match
I/dhcpcd  (12230): wlan0: rebinding lease of 192.168.1.124
,E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12242): MountEmulatedStorage()
I/libpersona(12242): KNOX_SDCARD checking this for 10067
E/Zygote  (12242): v2
I/libpersona(12242): KNOX_SDCARD not a persona
,I/SELinux (12242): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12242): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3505): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=12242 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux (12242): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12242): TimaSignature is unavailable
,D/ActivityThread(12242): Added TimaKeyStore provider
,D/ResourcesManager(12242): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/sCloudBackupApp(12242): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(12242): Other Intent
,I/ActivityManager( 3505): Killing 11299:com.sec.android.widgetapp.locationwidget/u0a22 (adj 13): bgCount ##31
,D/accuweather( 5206): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3778): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,D/accuweather( 5206): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5206): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5206): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
,D/accuweather( 5206): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5206): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5206): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12258): MountEmulatedStorage()
E/Zygote  (12258): v2
I/libpersona(12258): KNOX_SDCARD checking this for 1000
I/libpersona(12258): KNOX_SDCARD not a persona
,I/SELinux (12258): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12258): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12258): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3505): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=12258 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12258): TimaSignature is unavailable
,D/ActivityThread(12258): Added TimaKeyStore provider
,D/ResourcesManager(12258): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(12258): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro(12258): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro(12258): premStatus:2
,I/KnoxUsageLogPro(12258): isEulaShown : false
I/KnoxUsageLogPro(12258): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12273): MountEmulatedStorage()
,E/Zygote  (12273): v2
I/libpersona(12273): KNOX_SDCARD checking this for 10090
I/libpersona(12273): KNOX_SDCARD not a persona
I/SELinux (12273): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12273): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12273): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3505): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=12273 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3505): Killing 10635:com.android.defcontainer/u0a5 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12273): TimaSignature is unavailable
,D/ActivityThread(12273): Added TimaKeyStore provider
,D/ResourcesManager(12273): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12289): MountEmulatedStorage()
I/libpersona(12289): KNOX_SDCARD checking this for 10127
E/Zygote  (12289): v2
I/libpersona(12289): KNOX_SDCARD not a persona
,I/SELinux (12289): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12289): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12289): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3505): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=12289 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3505): Killing 11376:com.android.vending/u0a31 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12289): TimaSignature is unavailable
,D/ActivityThread(12289): Added TimaKeyStore provider
,D/ResourcesManager(12289): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,D/KeyguardWallpaperUpdator(12289): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12289): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12289): stopCheckCategoryVersion
,E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12305): MountEmulatedStorage()
I/libpersona(12305): KNOX_SDCARD checking this for 10136
E/Zygote  (12305): v2
I/libpersona(12305): KNOX_SDCARD not a persona
,I/SELinux (12305): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12305): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12305): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3505): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=12305 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3505): Killing 11457:com.android.mms/u0a52 (adj 13): bgCount ##31
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 8767(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 545us total 11.240ms
,D/TimaKeyStoreProvider(12305): TimaSignature is unavailable
,D/ActivityThread(12305): Added TimaKeyStore provider
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 533us total 8.387ms
,D/ResourcesManager(12305): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 256us total 8.329ms
,D/CountryDetector( 3505): No listener is left
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12305): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12305): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12305): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl(12305): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,I/WebViewFactory(12305): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(12305): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(12305): Loading: webviewchromium
,I/LibraryLoader(12305): Time to load native libraries: 3 ms (timestamps 19-22)
I/LibraryLoader(12305): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(12305): Binding Chromium to main looper Looper (main, tid 1) {3069e04b}
,I/LibraryLoader(12305): Expected native library version number "",actual native library version number ""
I/chromium(12305): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(12305): Initializing chromium process, renderers=0
,W/art     (12305): Attempt to remove local handle scope entry from IRT, ignoring
,W/AudioManagerAndroid(12305): Requires BLUETOOTH permission
W/chromium(12305): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(12305): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium(12305): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,I/NSApplication(12305): Starting up...
,E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12372): MountEmulatedStorage()
E/Zygote  (12372): v2
I/libpersona(12372): KNOX_SDCARD checking this for 10147
I/libpersona(12372): KNOX_SDCARD not a persona
,I/SELinux (12372): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12372): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12372): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3505): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=12372 uid=10147 gids={50147, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3505): Killing 11332:com.android.calendar/u0a164 (adj 15): bgCount ##31
,E/lowmemorykiller( 2828): Error writing /proc/11332/oom_score_adj; errno=22
,D/TimaKeyStoreProvider(12372): TimaSignature is unavailable
,D/ActivityThread(12372): Added TimaKeyStore provider
,D/ResourcesManager(12372): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/ResourcesManager(12372): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/Zygote  (12400): MountEmulatedStorage()
I/libpersona(12400): KNOX_SDCARD checking this for 10150
E/Zygote  (12400): v2
I/libpersona(12400): KNOX_SDCARD not a persona
I/SELinux (12400): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12400): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12400): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3505): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=12400 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
V/GLSActivity( 4640): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 4640): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/TimaKeyStoreProvider(12400): TimaSignature is unavailable
D/ActivityThread(12400): Added TimaKeyStore provider
,D/ResourcesManager(12400): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(12400): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(12400): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12400): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect(12400): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12400): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect(12400): PeriphStartReceiver.onReceive - no need to start
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12418): MountEmulatedStorage()
I/libpersona(12418): KNOX_SDCARD checking this for 10178
E/Zygote  (12418): v2
I/libpersona(12418): KNOX_SDCARD not a persona
,I/SELinux (12418): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12418): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12418): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3505): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=12418 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager( 3505): Killing 11489:com.samsung.android.securitylogagent/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12418): TimaSignature is unavailable
,D/ActivityThread(12418): Added TimaKeyStore provider
,D/ResourcesManager(12418): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(12418): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager(12418): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12418): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12418): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12418): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12418): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService( 3505): exchangeData() failure , invalid userId
,D/RCPManagerService( 3505): exchangeData() failure , invalid userId
,D/RCPManagerService( 3505): exchangeData() failure , invalid userId
,D/RCPManagerService( 3505): exchangeData() failure , invalid userId
,D/BadgeProvider(11585): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
D/RCPManagerService( 3505): exchangeData() failure , invalid userId
,D/BadgeProvider(11585): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider(11585): sendNotify, [notify] : null
D/BadgeProvider(11585): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(11585): update, [BadgeCount] : badgecount=0
D/BadgeProvider(11585): update, [UpdateCount] : 1
D/Launcher.Model( 4002): reloadBadges entered.
,D/RCPManagerService( 3505): exchangeData() failure , invalid userId
,E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12444): MountEmulatedStorage()
I/libpersona(12444): KNOX_SDCARD checking this for 1000
E/Zygote  (12444): v2
I/libpersona(12444): KNOX_SDCARD not a persona
,I/SELinux (12444): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12444): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12444): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3505): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=12444 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3505): Killing 11526:com.sec.android.app.taskmanager/u0a191 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12444): TimaSignature is unavailable
,D/ActivityThread(12444): Added TimaKeyStore provider
,D/ResourcesManager(12444): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,I/ActivityManager( 3505): Killing 11546:com.samsung.android.scloud.sync/u0a69 (adj 13): bgCount ##31
,I/iu.Environment( 6758): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 6758): num queued entries: 0
,I/iu.UploadsManager( 6758): num updated entries: 0
I/iu.SyncManager( 6758): NEXT; no task
,W/ActivityManager( 3505): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12462): MountEmulatedStorage()
E/Zygote  (12462): v2
I/libpersona(12462): KNOX_SDCARD checking this for 10013
I/libpersona(12462): KNOX_SDCARD not a persona
,I/SELinux (12462): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12462): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12462): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3505): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=12462 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12462): TimaSignature is unavailable
,D/ActivityThread(12462): Added TimaKeyStore provider
,D/ResourcesManager(12462): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,I/ActivityManager( 3505): Killing 11601:com.sec.android.app.clockpackage/u0a94 (adj 13): bgCount ##31
,I/Hs20UtilService( 4056): Starting #10
,I/Hs20UtilService( 4056): Message received 5007
,D/NearbySettings(12036): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings(12036): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings(12036): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings(12036): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings(12036): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings(12036): MountReceiver.onReceive - Set preference state off
V/NearbySettings(12036): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11225): NETWORK_STATE_CHANGED_ACTION
,I/dhcpcd  (12230): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
,I/dhcpcd  (12230): wlan0: leased 192.168.1.124 for 86400 seconds
,E/WifiStateMachine( 3505): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3505): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine( 3505): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine( 3505): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  ( 3505): do suspend true
,D/WifiP2pService( 3505): InactiveState{ what=143375 }
D/WifiP2pService( 3505): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 3505): WifiStateMachine DHCP successful
,E/WifiStateMachine( 3505): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3505): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine( 3505): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3505): Not connected state, yet.
E/WifiStateMachine( 3505): VerifyingLinkState enter
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiStateMachine( 3505): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine( 3505): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3505): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3505): callSECApiInt - ID [210]
E/WifiStateMachine( 3505): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService( 3505): updateNetworkInfo()
D/ConnectivityService( 3505): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 3505): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 3505): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 3505): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.DnsResolver( 3505): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker( 3505): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3505): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3505): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine( 3505): Now, connected state.
E/WifiStateMachine( 3505): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/WifiStateMachine( 3505): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/Hs20UtilService( 4056): Starting #11
,D/ConnectivityService( 3505): Adding Route [fe80::/64 -> :: wlan0] to network 503
,I/WifiTrafficPoller( 3505): evaluateTrafficStatsPolling
D/ConnectivityService( 3505): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,I/Hs20UtilService( 4056): Message received 5007
,D/ConnectivityService( 3505): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService( 3505): Unexpected mtu value: 0, wlan0
,V/        ( 2847): QcRouteController
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,I/WifiTrafficPoller( 3505): evaluateTrafficStatsPolling
,D/WifiNative-HAL( 3505): callSECApiVoid - ID [212]
,E/WifiStateMachine( 3505): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/WifiStateMachine( 3505): ConnectedState Enter  mScreenOn=false scanperiod=20000
,I/jxcore-log(11944): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log(11944): 
I/WifiStateMachine( 3505): REQUEST_POWER_SAVE_ON
,D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
V/        ( 2847): QcRouteController
,D/NearbySettings(12036): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings(12036): MountReceiver.onReceive - Keep current state
,V/        ( 2847): QcRouteController
,V/        ( 2847): QcRouteController
,I/SignOutReceiver(11225): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2847): QcRouteController,
I/Hs20UtilService( 4056): Starting #12
,I/Hs20UtilService( 4056): Message received 5007
,D/NearbySettings(12036): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings(12036): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings(12036): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings(12036): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings(12036): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings(12036): MountReceiver.onReceive - Set preference state off
,V/NearbySettings(12036): MountReceiver.mPrefHandler - 7002
V/        ( 2847): QcRouteController
V/        ( 2847): QcRouteController
,I/SignOutReceiver(11225): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2847): QcRouteController
,I/Hs20UtilService( 4056): Starting #13
,I/Hs20UtilService( 4056): Message received 5007
,D/ConnectivityService( 3505): Setting Dns servers for network 503 to [/192.168.1.1]
D/NearbySettings(12036): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 3505): LTETest block dns file not exists
I/NearbySettings(12036): MountReceiver.onReceive - Keep current state
,D/ConnectivityService( 3505): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 3505): updateNetworkInfo()
D/ConnectivityService( 3505): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3505): updateNetworkInfo()
D/ConnectivityService( 3505): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3505): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 3505): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3505): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3505): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3505): Checking http://clients3.google.com/generate_204 on "NG700"
I/WifiStateMachine( 3505): callSECApi what=220
D/WifiStateMachine( 3505): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/ConnectivityService( 3505):    accepting network in place of null
,D/TelephonyNetworkFactory( 3979): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker( 3505): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 3505): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
I/System.out( 3505): (HTTPLog)-Static: isSBSettingEnabled false
D/ConnectivityService( 3505): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 503 for uid 1000
D/ConnectivityService( 3505): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/Tethering( 3505): MasterInitialState.processMessage what=3
,D/ConnectivityService( 3505): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/EntConnectivity( 3505): Not allowed due to - mEnabled false
D/SmartBondingService( 3505): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService( 3505): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3505): getSBEnabled() enabled =false
D/ConnectivityManager.CallbackHandler( 3693): CM callback handler got msg 524290
D/SmartBondingService( 3505): getSBEnabled() enabled =false
D/NtpTrustedTime( 3505): currentTimeMillis() cache hit
D/SmartBondingService( 3505): getSBEnabled() enabled =false
V/NetworkStats( 3505): updateIfacesLocked()
V/NetworkStats( 3505): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 3505): UpdateStatsForKnox
D/SmartBondingService( 3505): getNetworkEnabled : wifi : true mobile : false
,D/NtpTrustedTime( 3505): currentTimeMillis() cache hit
D/NtpTrustedTime( 3505): currentTimeMillis() cache hit
D/NtpTrustedTime( 3505): currentTimeMillis() cache hit
V/NetworkStats( 3505): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3505): currentTimeMillis() cache hit
V/NetworkStats( 3505): performPollLocked() took 6ms
D/NtpTrustedTime( 3505): currentTimeMillis() cache hit
,D/ConnectivityManager.CallbackHandler( 6758): CM callback handler got msg 524290
,D/NtpTrustedTime( 3505): currentTimeMillis() cache hit
D/NtpTrustedTime( 3505): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3693): updateDataNetType()
D/StatusBar.NetworkController( 3693): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3693): updateLTEICONDataNetType:0
,I/SignOutReceiver(11225): NETWORK_STATE_CHANGED_ACTION
D/StatusBar.NetworkController( 3693): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,I/SurfaceFlinger( 2853): id=15 createSurf (1x1),1 flag=4, Uoast
D/PowerManagerService( 3505): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3505
D/mali_winsys( 3693): new_window_surface returns 0x3000,  [1120x201]-format:1
,I/System.out( 3505): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3505): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Feb 2016 22:53:14 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455058394651], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455058394628]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3505): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3505): Validated
D/ConnectivityService( 3505): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3505): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3505): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 3505): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3693): CM callback handler got msg 524290
D/ConnectivityService( 3505): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 6758): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3693): updateDataNetType()
D/StatusBar.NetworkController( 3693): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3693): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3693): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,E/WifiStateMachine( 3505): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3505): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityService( 3505): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
V/        ( 2847): QcRouteController
D/SmartBondingService( 3505): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/SmartBondingService( 3505): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3505): getSBEnabled() enabled =false
D/SmartBondingService( 3505): getSBEnabled() enabled =false
D/SmartBondingService( 3505): getSBEnabled() enabled =false
,V/        ( 2847): QcRouteController
,W/NetworkManagementService( 3505): route cmd failed: 
W/NetworkManagementService( 3505): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '76 route replace src v6 wlan0 fe80::92b6:86ff:fe43:731c 2 ::' failed with '400 76 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService( 3505): '
W/NetworkManagementService( 3505): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService( 3505): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService( 3505): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService( 3505): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService( 3505): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService( 3505): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5738)
W/NetworkManagementService( 3505): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5545)
W/NetworkManagementService( 3505): 	at com.android.server.ConnectivityService.access$2600(ConnectivityService.java:231)
W/NetworkManagementService( 3505): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2436)
W/NetworkManagementService( 3505): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 3505): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService( 3505): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ConnectivityService( 3505): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3693): CM callback handler got msg 524295
D/ConnectivityService( 3505): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 3693): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 6758): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 6758): CM callback handler got msg 524295
,I/jxcore-log(11944): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log(11944): 
,I/jxcore-log(11944): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log(11944): 
,I/jxcore-log(11944): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log(11944): 
,I/jxcore-log(11944): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log(11944): 
,I/jxcore-log(11944): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log(11944): 
,D/ConnectivityService( 3505): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3505): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3505): SmartBondingReceiver: wifi is connected
D/SmartBondingService( 3505): SmartBondingReceiver: wifi ap is not changed
,D/SmartBondingService( 3505): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3505): getSBEnabled() enabled =false
D/SmartBondingService( 3505): getSBEnabled() enabled =false
D/SmartBondingService( 3505): getSBEnabled() enabled =false
,D/SmartBondingService( 3505): getNetworkEnabled : wifi : true mobile : false
,D/GpsLocationProvider( 3505): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkMonitor(12118): type=WIFI subType= reason=null isConnected=true
,I/DBG_DM  ( 6235): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 6235): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,W/ResourceType( 5367): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5367): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,I/PCWCLIENTTRACE_PushUtil(12096): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil(12096): sales region : global
I/PCWCLIENTTRACE_PushUtil(12096): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(12096): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(12174): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(12174): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/SecContentProvider2( 3505): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3505): mCursor = null
,I/FOTA_Client(11437): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(11437): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(11437): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.521: (11470): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Feb 09 23:53:15 GMT+01:00 2016
,I/KLMS-2.4.521: (11470): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (11470): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11470): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/SO_AGENT(11671): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,I/KLMS-2.4.521: (11470): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (11470): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (11470): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (11470): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.521: (11470): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.521: (11470): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.521: (11470): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.4.521: (11470): StateImplV2(): networkChangeListener().END
,I/KLMS-2.4.521: (11470): KLMSIntentService(): onDestroy()
,E/SPPClientService(12215): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      (11015): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
I/SA      (11015): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (11015): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (11015): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11015): [OR] == isSIMCardReady false ==
,I/SA      (11015): [SCU] == networkStateCheck == true
I/SA      (11015): [DM] getCountryCodeFromCSC : PL
I/SA      (11015): isChinaCountryCode : false
I/SA      (11015): [SCU] is ChinestModel Data Restricted   : false
I/SA      (11015): [OR] == networkStateCheck true ==
,I/SA      (11015): [OR] GetMyCountryZoneTask
I/SA      (11015): [OR] onReceive END
,I/SA      (11015): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 3717): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SCloudBackupReceiver(12242): Other Intent
,I/SA      (11015): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (11015): [SSP] query invoked
,D/accuweather( 5206): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/SA      (11015): [TPMU] GetMccFromDB : null
I/SA      (11015): [SCU] getMccFromPreferece mcc = 260
I/SA      (11015): [TPM] isNoProxy(default) : true
,D/daemonapp( 3778): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 10
,D/accuweather( 5206): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5206): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
,D/accuweather( 5206): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
,D/accuweather( 5206): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5206): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5206): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro(12258): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro(12258): premStatus:2
,I/KnoxUsageLogPro(12258): isEulaShown : false
I/KnoxUsageLogPro(12258): KnoxUsageReceiver onReceive : not Processible, just return
,D/KeyguardWallpaperUpdator(12289): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12289): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12289): stopCheckCategoryVersion
,I/art     ( 3505): Explicit concurrent mark sweep GC freed 47545(2MB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 48MB/64MB, paused 1.316ms total 79.531ms
,D/QuickConnect(12400): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12400): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect(12400): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 3505): exchangeData() failure , invalid userId
,D/RCPManagerService( 3505): exchangeData() failure , invalid userId
,I/iu.Environment( 6758): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 6758): num queued entries: 0
I/iu.UploadsManager( 6758): num updated entries: 0
,I/iu.SyncManager( 6758): NEXT; no task
,D/WaitQueueForNetworkActivate(12462): notifyNetworkActivated
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 503 for uid 10014
,W/ContextImpl(12462): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3505): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/hcjo    (12462): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12462): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12462): exit::IDLE
D/InitializeManagerStateMachine(12462): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12462): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12462): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12462): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12462): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12462): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12462): entry::SUCCESS
D/hcjo    (12462): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    (12462): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12462): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine(12462): exit::SUCCESS
D/InitializeManagerStateMachine(12462): entry::IDLE
,I/SA      (11015): [RC New] Execute method=[GET] start
I/SA      (11015): [RC New] Security=[true]
I/System.out(11015): Thread-1501(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out(11015): Thread-1501(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11015): Thread-1501(ApacheHTTPLog):isShipBuild true
I/System.out(11015): Thread-1501(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 503 for uid 10045
D/ConnectivityService( 3505): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
I/SA      (11015): [RC New] [v2liruge] api execute + 605
I/SA      (11015): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out(11015): AsyncTask #1 calls detatch()
I/SA      (11015): [TPMU] getNetworkMcc : 
I/SA      (11015): [SCU] saveMccToPreferece Start
I/SA      (11015): [SCU] RegionMCC : 260
I/SA      (11015): [SSP] query invoked
I/SA      (11015): [TPMU] GetMccFromDB : null
I/SA      (11015): [SCU] getMccFromPreferece mcc = 260
I/SA      (11015): [SCU] saveMccToPreferece End
I/SA      (11015): [RC New] executeRequest [v2liruge] end. 626
I/SA      (11015): [RC New] Execute end
I/SA      (11015): [OR] GetMyCountryZoneTask mcc = 260
I/SA      (11015): [OR] GetMyCountryZoneTask Success
,I/dhcpcd  (12230): wlan0: sending IPv6 Router Solicitation
,D/WearableService( 4640): callingUid 10014, callindPid: 4640
,D/ResourcesManager(12118): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(12118): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(12118): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory(12118): Using the GMSCore's GoogleHttpClient
,D/WearableClient(12118): WearableClientImpl.onPostInitHandler: done
,I/MusicLeanback(12118): Conditions not met for autocaching.
I/MusicLeanback(12118): Stop autocaching.
,D/WearableClient(12118): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(12118): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(12118): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(12118): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils(12118): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/ActivityThread(12118): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@15e78901 that was originally bound here
E/ActivityThread(12118): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@15e78901 that was originally bound here
E/ActivityThread(12118): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(12118): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(12118): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(12118): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(12118): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(12118): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(12118): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(12118): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(12118): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(12118): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(12118): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(12118): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(12118): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(12118): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(12118): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(12118): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(12118): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(12118): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(12118): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(12118): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(12118): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(12118): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(12118): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(12118): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(12118): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/WifiStateMachine( 3505): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine( 3505): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,D/SSRM:n  ( 3505): SIOP:: AP = 290, PST = 256, CUR = 47
,I/jxcore-log(11944): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log(11944): 
,I/jxcore-log(11944): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log(11944): 
,I/jxcore-log(11944): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log(11944): 
,I/jxcore-log(11944): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log(11944): 
,I/SurfaceFlinger( 2853): id=15 Removed Uoast (8/9)
,I/SurfaceFlinger( 2853): id=15 Removed Uoast (-2/9)
,D/PowerManagerService( 3505): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3505) eventTime = 244586
D/PowerManagerService( 3505): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3505 (0x0)
D/PowerManagerService( 3505): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3505, ws=WorkSource{10060}) (elapsedTime=3480)
,I/jxcore-log(11944): Test app app.js loaded
I/jxcore-log(11944): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11944): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11944): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11944): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11944): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11944): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11944): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11944): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11944): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11944): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11944): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ff520a3 added. We now have 1 listener(s)
,I/jxcore-log(11944): BLE advertisement is supported
I/jxcore-log(11944): 
,I/chromium(11944): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/GAV4    (12305): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log(11944): --= Surplus to requirements =--
I/jxcore-log(11944): 
I/jxcore-log(11944): ****TEST TOOK:  ms ****
I/jxcore-log(11944): 
I/jxcore-log(11944): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(11944): 
,I/GAV2    (12372): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 3505): Killing 11620:com.sec.esdk.elm/u0a106 (adj 15): bgCount ##31
,D/BatteryService( 3505): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3505): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3505): online:4, current avg:-269, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:122
D/BatteryService( 3505): stay LED for fully charged
D/BatteryService( 3505): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3505): Plugged
I/MotionRecognitionService( 3505): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5644): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AndroidRuntime(12563): 
D/AndroidRuntime(12563): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(12563): CheckJNI is OFF
,D/AndroidRuntime(12563): readGMSProperty: start
D/AndroidRuntime(12563): readGMSProperty: already setted!!
,D/AndroidRuntime(12563): readGMSProperty: end
D/AndroidRuntime(12563): addProductProperty: start
,E/AffinityControl(12563): AffinityControl: registerfunction enter
,D/AndroidRuntime(12563): Calling main entry com.android.commands.pm.Pm
,D/PersonaManagerService( 3505): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 3505): START PACKAGE DELETE: observer{547283397}
D/PackageManager( 3505): pkg{<packageName>}
D/PackageManager( 3505): user{0}
D/PackageManager( 3505): caller{2000}
D/PackageManager( 3505): flags{3}
D/PersonaManagerService( 3505): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3505): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3505): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3505): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 3505): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 3505): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 3505): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 3505): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3505): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 3505): !@killApplicatoin: 10651, uninstall pkg
,I/ActivityManager( 3505): Force stopping com.test.thalitest appid=10651 user=-1: uninstall pkg
,I/ActivityManager( 3505): Killing 11944:com.test.thalitest/u0a651 (adj 0): stop com.test.thalitest
,I/ActivityManager( 3505):   Force finishing activity ActivityRecord{35af1cd0 u0 com.test.thalitest/.MainActivity t26}
,W/ActivityManager( 3505): mDVFSHelper.acquire()
,W/PackageSettings( 3505): Skipping PackageSetting{3ec558fe com.example.hello/10563} due to missing metadata
,D/WifiService( 3505): Client connection lost with reason: 4
,I/WindowState( 3505): WIN DEATH: Window{1659a156 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger( 2853): id=14 Removed NainActivit (5/8)
,I/SurfaceFlinger( 2853): id=14 Removed NainActivit (-2/8)
,I/SurfaceFlinger( 2853): id=14 Removed NainActivit (-2/8)
,I/DBG_DM  ( 6235): [com.wssyncmldm.ui.XUIInstallConfirmActivity(456/onResume)] 
,D/PointerIcon( 3505): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 3505): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3505): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3505): setHoveringSpenCustomIcon IconType is same.1
,I/ActivityManager( 3505): Force stopping com.test.thalitest appid=10651 user=0: pkg removed
,I/DBG_DM  ( 6235): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 13
,I/DBG_DM  ( 6235): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/ResourcesManager( 3505): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager( 3505): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/DBG_DM  ( 6235): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6235): [com.wssyncmldm.ui.XUIInstallConfirmActivity(466/onResume)] Postpone Count : 13
,I/DBG_DM  ( 6235): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,I/DBG_DM  ( 6235): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,D/ResourcesManager( 3979): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/GeofencerStateMachine( 4640): Ignoring removeGeofence because network location is disabled.
,I/art     ( 8019): Explicit concurrent mark sweep GC freed 23756(1408KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.777ms total 49.658ms
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3979): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,I/art     ( 4070): Explicit concurrent mark sweep GC freed 33307(2042KB) AllocSpace objects, 1(39KB) LOS objects, 21% free, 28MB/36MB, paused 7.260ms total 71.757ms
,D/ResourcesManager( 3505): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,D/ResourcesManager( 3505): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
W/ResourcesManager( 3979): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/SamsungIME( 4503): mOCRHelper is null
,D/ResourcesManager( 3505): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,I/InputReader( 3505): Reconfiguring input devices.  changes=0x00000010
,E/Zygote  (12577): MountEmulatedStorage()
E/Zygote  (12577): v2
I/libpersona(12577): KNOX_SDCARD checking this for 10063
I/libpersona(12577): KNOX_SDCARD not a persona
,I/SELinux (12577): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3505): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=12577 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (12577): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12577): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourceType( 5367): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5367): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/ResourcesManager( 3505): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/art     ( 6758): Explicit concurrent mark sweep GC freed 25508(1492KB) AllocSpace objects, 3(48KB) LOS objects, 20% free, 31MB/39MB, paused 1.408ms total 104.815ms
,D/ResourcesManager( 3505): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager( 3505): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,I/DBG_DM  ( 6235): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
D/ResourcesManager( 3505): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/ResourcesManager( 3505): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/SecContentProvider2( 3505): uri = 14 selection = getSealedState
D/SecContentProvider2( 3505): mCursor = null
,D/ResourcesManager( 3505): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/EnterpriseDeviceManagerService( 3505): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3505): Admin package name: com.google.android.gms
,D/ResourcesManager( 3505): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager( 3505): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/ResourcesManager( 3505): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,W/Resources( 3505): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3505): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager( 3505): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,W/Resources( 3505): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3505): creating new AssetManager and set to /system/app/Books/Books.apk
,D/TimaKeyStoreProvider(12577): TimaSignature is unavailable
,D/ApplicationPolicy( 3505): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy( 3505): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/ActivityThread(12577): Added TimaKeyStore provider
,I/DBG_DM  ( 6235): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 13
,I/DBG_DM  ( 6235): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,D/ResourcesManager(12577): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,I/DBG_DM  ( 6235): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,D/SecContentProvider2( 3505): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3505): mCursor = null
,I/DBG_DM  ( 6235): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 6235): [llIIlIIlIllIllIlllII(376/llIIllllIIlllIIIIlll)] 
,I/DBG_DM  ( 6235): [IIlIIIlllllIIlIIIlII(339/llllIlIIIllllIIlIlll)] No need to check encryption status
,I/DBG_DM  ( 6235): [llIIlIIlIllIllIlllII(405/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
,D/ActivityManager( 3505): post active user change for 0
D/KnoxTimeoutHandler( 3505): postActiveUserChange for user 0
,I/DBG_DM  ( 6235): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
,I/SurfaceFlinger( 2853): id=16 createSurf (1440x2560),2 flag=404, YUIInstallC
,D/VRSetupWizardStub/PackageIntentReceiver(12577): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(12577): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(12577): packagename:com.test.thalitest
,D/StatusBarManagerService( 3505): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/RegisteredServicesCache( 3969): empty dynamic service
,D/StatusBarManagerService( 3505): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/art     ( 3505): Explicit concurrent mark sweep GC freed 24632(1903KB) AllocSpace objects, 8(128KB) LOS objects, 24% free, 49MB/65MB, paused 1.731ms total 123.268ms
,D/PointerIcon( 3505): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3505): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3505): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3505): setHoveringSpenCustomIcon IconType is same.1
V/ActivityThread( 6235): updateVisibility : ActivityRecord{26bc16d8 token=android.os.BinderProxy@2731c435 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,I/KLMS-2.4.521: (11470): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Feb 09 23:53:19 GMT+01:00 2016
,I/KLMS-2.4.521: (11470): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 3505): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
,I/splitIntent( 3505): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,D/ResourcesManager( 3505): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager( 3505): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,I/KLMS-2.4.521: (11470): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11470): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/ResourcesManager( 3505): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/RCPManager(12258):  in createShortcut() for packageName: com.test.thalitest userId0
,D/RCPManagerService( 3505):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3505): queryAllProviders():  providerCallBack is not register for 0
,E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3505): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,I/KLMS-2.4.521: (11470): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (11470): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,D/PackageManager( 3505): delete codoeFile: 
I/KLMS-2.4.521: (11470): KLMSIntentService(): PACKAGE_REMOVED
,I/AASAUninstall( 3505):  com.test.thalitest not target!
,D/PackageManager( 3505): result of delete: 1{547283397}
D/ResourcesManager( 3505): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,I/KLMS-2.4.521: (11470): KLMSIntentService(): listeningToPackageRemoved().START
D/AndroidRuntime(12563): Shutting down VM
,D/ResourcesManager( 3505): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager( 3505): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
I/KLMS-2.4.521: (11470): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,D/ResourcesManager( 3505): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,E/Zygote  (12594): MountEmulatedStorage()
E/Zygote  (12594): v2
I/libpersona(12594): KNOX_SDCARD checking this for 10106
I/libpersona(12594): KNOX_SDCARD not a persona
,I/SELinux (12594): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/InputMethodManagerService( 3505): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/SELinux (12594): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3505): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=12594 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,E/SELinux (12594): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 3505): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,W/InputMethodManagerService( 3505): Got RemoteException sending setActive(false) notification to pid 11944 uid 10651
,D/ResourcesManager( 3505): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,W/ContextImpl( 3505): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ResourcesManager( 3505): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/TimaKeyStoreProvider(12594): TimaSignature is unavailable
D/ResourcesManager( 3505): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/Timeline( 6235): Timeline: Activity_idle id: android.os.BinderProxy@2731c435 time:246012
,D/ActivityThread(12594): Added TimaKeyStore provider
,D/ResourcesManager( 3505): creating new AssetManager and set to /system/app/Drive/Drive.apk
,W/Resources( 3505): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3505): creating new AssetManager and set to /system/app/Videos/Videos.apk
,E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3505): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/PackageManager( 3505): [MSG] WRITE_PACKAGE_RESTRICTIONS
,E/Zygote  (12611): MountEmulatedStorage()
E/Zygote  (12611): v2
I/libpersona(12611): KNOX_SDCARD checking this for 10050
I/libpersona(12611): KNOX_SDCARD not a persona
,I/SELinux (12611): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12611): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12611): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3505): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=12611 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,W/ActivityManager( 3505): mDVFSHelper.release()
,I/Timeline( 3505): Timeline: Activity_windows_visible id: ActivityRecord{2f6af136 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t24} time:246062
,D/ResourcesManager( 3505): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(12611): TimaSignature is unavailable
,D/ActivityThread(12611): Added TimaKeyStore provider
D/ResourcesManager( 3505): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3505): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
,D/ResourcesManager( 3505): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,E/Zygote  (12626): MountEmulatedStorage()
E/Zygote  (12626): v2
I/libpersona(12626): KNOX_SDCARD checking this for 10101
I/libpersona(12626): KNOX_SDCARD not a persona
,I/SELinux (12626): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12626): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12626): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(12594): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,I/ActivityManager( 3505): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=12626 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/KLMS-2.4.521: (11470): KLMSIntentService(): listeningToPackageRemoved().END
,E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
,D/elm:14491(12594): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14491(12594): ELMEngine.ELMEngine( context ).
D/elm:14491(12594): MDMBridge.setEnterpriseBridge()
D/TimaKeyStoreProvider(12626): TimaSignature is unavailable
D/ResourcesManager(12611): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
D/ActivityThread(12626): Added TimaKeyStore provider
W/ResourcesManager(12611): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12611): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(12611): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12611): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12611): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager(12611): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(12611): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12611): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Zygote  (12641): MountEmulatedStorage()
E/Zygote  (12641): v2
I/libpersona(12641): KNOX_SDCARD checking this for 10183
I/libpersona(12641): KNOX_SDCARD not a persona
,I/SELinux (12641): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12641): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12641): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3505): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=12641 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
,D/elm:14491(12594): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:14491(12594): ElmAgentService : onCreate()
,D/elm:14491(12594): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14491(12594): MainReceiver.listeningToPackageRemoved()
D/elm:14491(12594): MDMBridge.getInstance()
D/elm:14491(12594): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14491(12594): MDMBridge.getAllLicenseInfoFromSDK()
,I/KLMS-2.4.521: (11470): KLMSIntentService(): onDestroy()
,D/com.sec.android.service.health.upgrade.UninstallReceiver(11569): onReceive()
,I/com.sec.android.service.health.upgrade.UninstallReceiver(11569): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver(11569): onReceive() : package name is not s health. Return !!!
,W/ResourceType( 3505): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/elm:14491(12594): ElmAgentService : onDestroy().
D/ResourcesManager( 3505): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
W/Resources( 3505): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3505): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3505): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TimaKeyStoreProvider(12641): TimaSignature is unavailable
,D/ResourcesManager( 3505): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ActivityThread(12641): Added TimaKeyStore provider
,D/ResourcesManager( 3505): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources( 3505): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3505): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager( 3505): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(12626): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager( 3505): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager( 3505): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/Resources( 3505): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3505): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3505): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,E/Zygote  (12658): MountEmulatedStorage()
,E/Zygote  (12658): v2
I/ActivityManager( 3505): Start proc com.sec.android.widgetapp.locationwidget for broadcast com.sec.android.widgetapp.locationwidget/.cocktail.LocationWidgetCocktailProvider: pid=12658 uid=10022 gids={50022, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
I/libpersona(12658): KNOX_SDCARD checking this for 10022
I/libpersona(12658): KNOX_SDCARD not a persona
,W/ResourcesManager( 3505): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3505): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3505): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3505): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,W/Resources( 3505): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3505): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,I/SELinux (12658): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3505): Killing 11316:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
,D/ResourcesManager( 3505): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager( 3505): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/SELinux (12658): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12658): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 3505): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/ResourcesManager( 3505): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 3505): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 8740(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 950us total 29.883ms
,D/ResourcesManager( 3505): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager( 3505): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,I/ActivityManager( 3505): Killing 11509:com.sec.android.app.shealth/u0a36 (adj 13): bgCount ##31
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 770us total 12.613ms
W/Resources( 3505): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3505): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
D/TimaKeyStoreProvider(12658): TimaSignature is unavailable
,D/ActivityThread(12658): Added TimaKeyStore provider
,W/Resources( 3505): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3505): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3505): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3505): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/ResourcesManager(12641): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,W/Resources( 3505): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3505): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 609us total 11.933ms
,W/Resources( 3505): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3505): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3505): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
D/RCPManagerService( 3505): PackageReceiver onReceive()
I/HarmonyEASService( 3505): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 3505): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,W/Resources( 3505): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3505): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/BackupManagerService( 3505): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/EnterpriseBillingPolicy( 3505): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
D/JobSchedulerService( 3505): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3505): uID is 10651
V/EnterpriseBillingPolicy( 3505): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3505): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 3505): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3505): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3505): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3505): getBillingProfileForVpnEngine - start - com.test.thalitest
W/Resources( 3505): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
V/EnterpriseBillingPolicyStorage( 3505): getBillingProfileForVpnEngine - end - null
D/UsbSettingsManager( 3505): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 3505): onPackageRemoved : com.test.thalitest
D/DocsApplication(12626): Installing DEX configuration.
,D/KnoxTimeoutHandler( 3505): handleActiveUserChange for user 0
,D/DexInstaller(12626): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,I/PackageInfoHelper(12626): Provided clientMode=RELEASE, packageInfo=PackageInfo{2f232c50 com.google.android.apps.docs}
,D/TAG     (12626): onCreate()
,D/CrossAppStateProvider(12626): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,D/ResourcesManager(12658): creating new AssetManager and set to /system/priv-app/LocationWidget/LocationWidget.apk
,D/TaskPersister( 3505): removeObsoleteFile: deleting file=26_task.xml
,D/TaskPersister( 3505): removeObsoleteFile: deleting file=24_task.xml
,W/ResourcesManager(12658): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(12658): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12658): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/PackageManager( 3505): findPreferredActivity: No PreferredActivities set
,E/SQLiteLog(12641): (284) automatic index on shooting_modes(title_id)
,D/NearbySource(12611): Nearby Source Create!
D/NearbyContext(12611): Nearby Context Create!
,D/StatusBar( 3693): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 3693): isKioskContainerExistOnDevice
D/PersonaManager( 3693): isKioskContainerExistOnDevice
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
I/PhoneStatusBar( 3693): Icon Only
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
I/StatusBar( 3693): Icon Only
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
I/LocationWidgetApplication(12658): onCreate() : start
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
D/PanelView( 3693): There is/are notification(s) 
D/PanelView( 3693): There is/are notification(s) 
,D/LocationWidgetApplication(12658): countryCode = POLAND
,D/PersonaManager( 3693): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 3693): Icon Only
I/StatusBar( 3693): Icon Only
,D/PanelView( 3693): There is/are notification(s) 
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12611): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource(12611): Samsung link source created
,E/Zygote  (12677): MountEmulatedStorage()
I/libpersona(12677): KNOX_SDCARD checking this for 10190
E/Zygote  (12677): v2
I/libpersona(12677): KNOX_SDCARD not a persona
,I/SELinux (12677): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3505): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=12677 uid=10190 gids={50190, 9997} abi=armeabi-v7a
,I/SELinux (12677): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12677): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3505): Killing 11069:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
,E/SQLiteLog(12611): (28) failed to open "/data/data/com.sec.android.gallery3d/databases/local.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(12611): Failed to open database '/data/data/com.sec.android.gallery3d/databases/local.db'.
E/SQLiteDatabase(12611): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12611): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12611): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12611): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12611): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12611): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12611): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12611): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12611): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12611): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12611): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12611): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12611): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12611): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(12611): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteDatabase(12611): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteDatabase(12611): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteDatabase(12611): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:202)
E/SQLiteDatabase(12611): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:194)
E/SQLiteDatabase(12611): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(12611): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(12611): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12611): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12611): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12611): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12611): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12611): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12611): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12611): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12611): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper(12611): Couldn't open local.db for writing (will try read-only):
E/SQLiteOpenHelper(12611): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(12611): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(12611): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(12611): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(12611): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(12611): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(12611): 	at android.database.sqlite.SQLiteConne,ctionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(12611): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(12611): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(12611): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(12611): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(12611): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(12611): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(12611): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(12611): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteOpenHelper(12611): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteOpenHelper(12611): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteOpenHelper(12611): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:202)
E/SQLiteOpenHelper(12611): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:194)
E/SQLiteOpenHelper(12611): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(12611): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(12611): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(12611): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(12611): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(12611): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(12611): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(12611): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(12611): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(12611): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(12611): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper(12611): Opened local.db in read-only mode
D/WifiDisplayAdapter( 3505): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/ContactProvider(12611): getAllContactInfoList Start
D/LocationManagerService( 3505): getProviders()=[]
D/LocationManagerService( 3505): getProviders()=[passive]
D/LocationManagerService( 3505): getBestProvider(Criteria[power=LOW acc=LOW], true)=passive
D/LWLocationManager(12658): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(12658): getLastUiLocationId() : mLastUiLocationId = -100
D/WifiDisplayAdapter( 3505): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
E/SQLiteLog(12658): (28) failed to open "/data/data/com.sec.android.widgetapp.locationwidget/databases/LBHWidget.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase(12658): Failed to open database '/data/data/com.sec.android.widgetapp.locationwidget/databases/LBHWidget.db'.
E/SQLiteDatabase(12658): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12658): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12658): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12658): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12658): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12658): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12658): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12658): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12658): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12658): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12658): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12658): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12658): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12658): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12658): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12658): 	at com.sec.android.widgetapp.locationwidget.db.LocationWidgetDBControll.<init>(LocationWidgetDBControll.java:52)
E/SQLiteDatabase(12658): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getDBList(LocationWidgetFuctionData.java:690)
E/SQLiteDatabase(12658): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.configPlaceListItems(LocationWidgetFuctionData.java:548)
E/SQLiteDatabase(12658): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getPlaceListItems(LocationWidgetFuctionData.java:55)
E/SQLiteDatabase(12658): 	at com.sec.android.widgetapp.locationwidget.cocktail.LocationWidgetCocktailProvider.onReceive(LocationWidgetCocktailProvider.java:277)
E/SQLiteDatabase(12658): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
E/SQLiteDatabase(12658): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
E/SQLiteDatabase(12658): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
E/SQLiteDatabase(12658): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12658): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12658): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12658): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12658): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12658): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12658): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime(12658): Shutting down VM
E/AndroidRuntime(12658): FATAL EXCEPTION: main
E/AndroidRuntime(12658): Process: com.sec.android.widgetapp.locationwidget, PID: 12658
E/AndroidRuntime(12658): java.lang.RuntimeException: Unable to start receiver com.sec.android.widgetapp.locationwidget.cocktail.LocationWidgetCocktailProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12658): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3001)
E/AndroidRuntime(12658): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
E/AndroidRuntime(12658): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
E/AndroidRuntime(12658): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(12658): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(12658): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(12658): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(12658): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(12658): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(12658): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(12658): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12658): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12658): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(12658): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(12658): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12658): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12658): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12658): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(12658): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(12658): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(12658): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(12658): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12658): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12658): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(12658): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(12658): 	at com.sec.android.widgetapp.locationwidget.db.LocationWidgetDBControll.<init>(LocationWidgetDBControll.java:52)
E/AndroidRuntime(12658): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getDBList(LocationWidgetFuctionData.java:690)
E/AndroidRuntime(12658): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.configPlaceListItems(LocationWidgetFuctionData.java:548)
E/AndroidRuntime(12658): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getPlaceListItems(LocationWidgetFuctionData.java:55)
E/AndroidRuntime(12658): 	at com.sec.android.widgetapp.locationwidget.cocktail.LocationWidgetCocktailProvider.onReceive(LocationWidgetCocktailProvider.java:277)
E/AndroidRuntime(12658): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
E/AndroidRuntime(12658): 	... 9 more
D/TimaKeyStoreProvider(12677): TimaSignature is unavailable
D/ActivityThread(12677): Added TimaKeyStore provider
I/PCWCLIENTTRACE_PushUtil(12096): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(12096): sales region : global
I/PCWCLIENTTRACE_PushUtil(12096): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(12096): [onReceive] - android.intent.action.PACKAGE_REMOVED
D/UsbHostManager( 3505): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
D/UsbHostManager( 3505): displayNotification : [02h,02h,01h]
D/UsbHostManager( 3505): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
D/UsbHostManager( 3505): displayNotification : [0ah,00h,00h]
D/UsbHostManager( 3505): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3505): displayNotification : [02h,0dh,00h]
D/PanelView( 3693): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
D/UsbHostManager( 3505): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3505): displayNotification : [0ah,00h,01h]
,D/UsbHostManager( 3505): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
D/UsbHostManager( 3505): displayNotification : [09h,00h,00h]
D/UsbHostManager( 3505): usbDeviceRemoved : /dev/bus/usb/001/003
E/UsbHostManager( 3505): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
D/UsbSettingsManager( 3505): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
V/ApplicationPolicy( 3505): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.locationwidget
E/SharedPreferencesImpl(12611): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
D/MtpClient(12611): onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
D/MtpClient(12611): ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(12677): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
E/Zygote  (12702): MountEmulatedStorage()
E/Zygote  (12702): v2
I/libpersona(12702): KNOX_SDCARD checking this for 10035
I/libpersona(12702): KNOX_SDCARD not a persona
I/SELinux (12702): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
E/DropBoxManagerService( 3505): Can't write: system_app_crash
E/DropBoxManagerService( 3505): java.io.FileNotFoundException: /data/system/dropbox/drop196.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3505): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3505): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3505): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3505): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3505): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3505): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3505): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3505): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3505): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3505): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3505): 	... 5 more
I/SELinux (12702): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3505): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=12702 uid=10035 gids={50035, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
E/SELinux (12702): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/UsbHostManager( 3505): usbDeviceRemoved : /dev/bus/usb/001/001
E/UsbHostManager( 3505): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
,I/ActivityManager( 3505): Killing 11585:com.sec.android.provider.badge/u0a82 (adj 13): bgCount ##31
,E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
I/TapandpayWidget:TanpandpayAppWidgetProvider(12677): onReceive()
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
D/TapandpayWidget:TanpandpayAppWidgetProvider(12677): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,I/EventHub( 3505): Removing device '/dev/input/event10' due to inotify event
,I/TapandpayWidget:Utils(12677): Clear T&P info.
,D/TapandpayWidget:TanpandpayAppWidgetProvider(12677): Widget is not attached.
,D/TimaKeyStoreProvider(12702): TimaSignature is unavailable
,D/ActivityThread(12702): Added TimaKeyStore provider
I/EventHub( 3505): Removing device '/dev/input/event7' due to inotify event
,E/Zygote  (12719): MountEmulatedStorage()
I/libpersona(12719): KNOX_SDCARD checking this for 10052
E/Zygote  (12719): v2
I/libpersona(12719): KNOX_SDCARD not a persona
I/SELinux (12719): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12719): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12719): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3505): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=12719 uid=10052 gids={50052, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,I/ActivityManager( 3505): Killing 12036:com.android.settings/1000 (adj 13): bgCount ##31
,I/EventHub( 3505): Removing device '/dev/input/event8' due to inotify event
,I/EventHub( 3505): Removing device '/dev/input/event9' due to inotify event
I/PCWCLIENTTRACE_SYSTEMReceiver(12096): mConnectivityHandler : connected
,D/TimaKeyStoreProvider(12719): TimaSignature is unavailable
,D/ActivityThread(12719): Added TimaKeyStore provider
,D/ResourcesManager(12702): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/PCWCLIENTTRACE_AccountUtil(12096): [hasSamungAccount] - No Samsung Account
,D/WifiService( 3505): Client connection lost with reason: 4
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3505): checkUser: useridlist=null, currentuser=0
,D/PackageBroadcastService( 6758): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 6758): Clearing selected account for com.test.thalitest
,I/EventHub( 3505): Removing device '/dev/input/event11' due to inotify event
,E/Zygote  (12736): MountEmulatedStorage()
E/Zygote  (12736): v2
I/libpersona(12736): KNOX_SDCARD checking this for 10031
I/libpersona(12736): KNOX_SDCARD not a persona
,I/SELinux (12736): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12736): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12736): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3505): Start proc com.android.vending for preferred application com.android.vending: pid=12736 uid=10031 gids={50031, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/CSTORAGE(12096): ================================================
I/CSTORAGE(12096):  CSTORAGE_SKM_LIB v1.0.15
I/CSTORAGE(12096): ================================================
I/PCWCLIENTTRACE_SecurePreferencesJNI(12096): [GetString-S]
E/art     (12096): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
W/PCWCLIENTTRACE_SecurePreferencesJNI(12096): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI(12096): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil(12096): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(12096): sales region : global
I/PCWCLIENTTRACE_PushUtil(12096): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler(12096): [ensureRegistration] - No Samsung account
,I/EventHub( 3505): Removing device '/dev/input/event12' due to inotify event
,I/EventHub( 3505): Removing device '/dev/input/event13' due to inotify event
,D/TimaKeyStoreProvider(12736): TimaSignature is unavailable
,D/ActivityThread(12736): Added TimaKeyStore provider
,I/Process (12658): Sending signal. PID: 12658 SIG: 9
,D/ResourcesManager(12719): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/EventHub( 3505): Removing device '/dev/input/event14' due to inotify event
,W/ResourcesManager(12719): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12719): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12719): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12719): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12719): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(12719): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/SQLiteLog( 6758): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6758): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/DriveAsyncService( 6758): disk I/O error (code 3850)
E/DriveAsyncService( 6758): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 6758): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 6758): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/DriveAsyncService( 6758): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 6758): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 6758): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/DriveAsyncService( 6758): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
E/DriveAsyncService( 6758): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 6758): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 6758): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 6758): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 6758): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 6758): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 6758): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 6758): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 6758): 	at java.lang.Thread.run(Thread.java:818)
,I/LocationSettingsChecker( 6758): Removing dialog suppression flag for package com.test.thalitest
,I/ActivityManager( 3505): Killing 12071:com.facebook.appmanager/u0a110 (adj 13): bgCount ##31
,E/SQLiteLog(12626): (28) failed to open "/data/data/com.google.android.apps.docs/databases/ClientFlag.db" with flag (131138) and mode_t (0) due to error (30)
,I/FeatureConfig(12702): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,E/SQLiteDatabase(12626): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase(12626): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12626): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12626): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12626): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12626): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12626): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12626): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12626): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12626): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12626): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12626): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12626): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12626): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12626): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(12626): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase(12626): 	at QF.provideClientFlag(ClientFlagsModule.java:71)
E/SQLiteDatabase(12626): 	at QH.a(GellyInjectorStore.java:215)
E/SQLiteDatabase(12626): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12626): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12626): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12626): 	at tQ.a(GellyInjectorStore.java:2039)
E/SQLiteDatabase(12626): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12626): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12626): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12626): 	at pG.a(GellyInjectorStore.java:478)
E/SQLiteDatabase(12626): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12626): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12626): 	at qD.a(GellyInjectorStore.java:118)
E/SQLiteDatabase(12626): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12626): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12626): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12626): 	at aEV.a(GellyInjectorStore.java:130)
E/SQLiteDatabase(12626): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12626): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12626): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12626): 	at aGH.a(GellyInjectorStore.java:227)
E/SQLiteDatabase(12626): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12626): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12626): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12626): 	at aGH.a(GellyInjectorStore.java:392)
E/SQLiteDatabase(12626): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12626): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12626): 	at aGH.a(GellyInjectorStore.java:369)
E/SQLiteDatabase(12626): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12626): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12626): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12626): 	at agN.a(GellyInjectorStore.java:799)
E/SQLiteDatabase(12626): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12626): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12626): 	at pG.a(GellyInjectorStore.java:146)
E/SQLiteDatabase(12626): 	at pG.a(GellyInjectorStore.java:392)
E/SQLiteDatabase(12626): 	at bsh.a(GellyMembersInjector.java:30)
E/SQLiteDatabase(12626): 	at brQ.a(GellyInjector.ja,va:119)
E/SQLiteDatabase(12626): 	at ajB.a(ScopedInjector.java:216)
E/SQLiteDatabase(12626): 	at com.google.android.apps.docs.DocsApplication.a(DocsApplication.java:235)
E/SQLiteDatabase(12626): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase(12626): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(12626): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(12626): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12626): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12626): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12626): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12626): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12626): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12626): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12626): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12626): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper(12626): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper(12626): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(12626): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(12626): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(12626): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(12626): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(12626): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(12626): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(12626): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(12626): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(12626): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(12626): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(12626): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(12626): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(12626): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(12626): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper(12626): 	at QF.provideClientFlag(ClientFlagsModule.java:71)
E/SQLiteOpenHelper(12626): 	at QH.a(GellyInjectorStore.java:215)
E/SQLiteOpenHelper(12626): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12626): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12626): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12626): 	at tQ.a(GellyInjectorStore.java:2039)
E/SQLiteOpenHelper(12626): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12626): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12626): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12626): 	at pG.a(GellyInjectorStore.java:478)
E/SQLiteOpenHelper(12626): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12626): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12626): 	at qD.a(GellyInjectorStore.java:118)
E/SQLiteOpenHelper(12626): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12626): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12626): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12626): 	at aEV.a(Gelly,InjectorStore.java:130)
E/SQLiteOpenHelper(12626): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12626): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12626): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12626): 	at aGH.a(GellyInjectorStore.java:227)
E/SQLiteOpenHelper(12626): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12626): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12626): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12626): 	at aGH.a(GellyInjectorStore.java:392)
E/SQLiteOpenHelper(12626): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12626): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12626): 	at aGH.a(GellyInjectorStore.java:369)
E/SQLiteOpenHelper(12626): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12626): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12626): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12626): 	at agN.a(GellyInjectorStore.java:799)
E/SQLiteOpenHelper(12626): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12626): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12626): 	at pG.a(GellyInjectorStore.java:146)
E/SQLiteOpenHelper(12626): 	at pG.a(GellyInjectorStore.java:392)
E/SQLiteOpenHelper(12626): 	at bsh.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper(12626): 	at brQ.a(GellyInjector.java:119)
E/SQLiteOpenHelper(12626): 	at ajB.a(ScopedInjector.java:216)
E/SQLiteOpenHelper(12626): 	at com.google.android.apps.docs.DocsApplication.a(DocsApplication.java:235)
E/SQLiteOpenHelper(12626): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper(12626): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(12626): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(12626): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(12626): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(12626): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(12626): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(12626): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(12626): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(12626): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(12626): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(12626): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper(12626): Opened ClientFlag.db in read-only mode
E/SQLiteLog( 6758): (28) failed to open "/data/data/com.google.android.gms/databases/metrics.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 6758): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 6758): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6758): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6758): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6758): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6758): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6758): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6758): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6758): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 6758): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 6758): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6758): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 6758): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6758): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6758): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 6758): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 6758): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 6758): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 6758): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 6758): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6758): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 6758): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 6758): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 6758): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 6758): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 6758): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 6758): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 6758): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 6758): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 6758): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 6758): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 6758): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 6758): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper( 6758): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 6758): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 6758): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 6758): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 6758): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 6758): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 6758): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 6758): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 6758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 6758): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 6758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteLog(12626): (28) failed to open "/data/data/com.google.android.apps.docs/databases/DocList.db" with flag (131138) and mode_t (0) due to error (30)
,W/SQLiteOpenHelper( 6758): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 6758): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
E/SQLiteDatabase(12626): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase(12626): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12626): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12626): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12626): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12626): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12626): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12626): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12626): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12626): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12626): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12626): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12626): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12626): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12626): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12626): 	at aFu.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase(12626): 	at aFo.a(AbstractDatabaseInstance.java:457)
E/SQLiteDatabase(12626): 	at aFo.a(AbstractDatabaseInstance.java:453)
E/SQLiteDatabase(12626): 	at bjx.a(Suppliers.java:125)
E/SQLiteDatabase(12626): 	at aFp.run(AbstractDatabaseInstance.java:471)
D/gH_CompatibleDatabase( 6758): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/AndroidRuntime(12626): FATAL EXCEPTION: Open database in background
E/AndroidRuntime(12626): Process: com.google.android.apps.docs, PID: 12626
E/AndroidRuntime(12626): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12626): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12626): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(12626): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(12626): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12626): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12626): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12626): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(12626): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(12626): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(12626): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(12626): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12626): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(12626): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(12626): 	at aFu.getWritableDatabase(DatabaseHelper.java:236)
E/And,roidRuntime(12626): 	at aFo.a(AbstractDatabaseInstance.java:457)
E/AndroidRuntime(12626): 	at aFo.a(AbstractDatabaseInstance.java:453)
E/AndroidRuntime(12626): 	at bjx.a(Suppliers.java:125)
E/AndroidRuntime(12626): 	at aFp.run(AbstractDatabaseInstance.java:471)
D/ResourcesManager(12702): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
E/SQLiteLog( 6758): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/gH_CompatibleDatabase( 6758): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
E/AndroidRuntime( 6758): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 6758): Process: com.google.android.gms, PID: 6758
E/AndroidRuntime( 6758): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 6758): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 6758): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
E/AndroidRuntime( 6758): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 6758): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 6758): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1623)
E/AndroidRuntime( 6758): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 6758): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 6758): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6758): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ChimeraCfgMgr( 6758): Loading module com.google.android.gms.games from APK com.google.android.play.games

```
