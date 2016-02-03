#### Test 58135655c662d33_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
,D/BatteryService( 3509): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3509): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3509): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:36
D/BatteryService( 3509): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 3509): Plugged
I/MotionRecognitionService( 3509): setPowerConnected  = true
--------- beginning of main
D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
D/BatteryService( 3509): stay LED for fully charged
D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5646): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5646): Disconnected process message: 10
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AndroidRuntime(12020): 
D/AndroidRuntime(12020): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(12020): CheckJNI is OFF
D/AndroidRuntime(12020): readGMSProperty: start
D/AndroidRuntime(12020): readGMSProperty: already setted!!
D/AndroidRuntime(12020): readGMSProperty: end
D/AndroidRuntime(12020): addProductProperty: start
E/AffinityControl(12020): AffinityControl: registerfunction enter
D/AndroidRuntime(12020): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3509): inState():  stateMachine is null !!
I/PersonaManagerService( 3509): PersonaId don't exist
I/ActivityManager( 3509): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3509): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3509): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3509): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager( 3509): mDVFSHelper.acquire()
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/Zygote  (12035): MountEmulatedStorage()
I/libpersona(12035): KNOX_SDCARD checking this for 10623
E/Zygote  (12035): v2
I/libpersona(12035): KNOX_SDCARD not a persona
I/SELinux (12035): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3509): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=12035 uid=10623 gids={50623, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux (12035): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/AndroidRuntime(12020): Shutting down VM
E/SELinux (12035): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon( 3509): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3509): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3509): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3509): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(12035): TimaSignature is unavailable
D/ActivityThread(12035): Added TimaKeyStore provider
I/SurfaceFlinger( 2848): id=11 Removed YUIInstallC (5/8)
I/SurfaceFlinger( 2848): id=11 Removed YUIInstallC (-2/8)
D/ResourcesManager(12035): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
V/ActivityThread( 6306): updateVisibility : ActivityRecord{3066c548 token=android.os.BinderProxy@1f3bcee5 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
,I/WebViewFactory(12035): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(12035): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(12035): Loading: webviewchromium
I/LibraryLoader(12035): Time to load native libraries: 7 ms (timestamps 5978-5985)
I/LibraryLoader(12035): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider(12035): Binding Chromium to main looper Looper (main, tid 1) {29f3d6bb}
I/LibraryLoader(12035): Expected native library version number "",actual native library version number ""
I/chromium(12035): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController(12035): Initializing chromium process, renderers=0
W/art     (12035): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium(12035): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium(12035): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(12035): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
W/chromium(12035): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium(12035): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     (12035): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents(12035): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine(12035): CordovaWebView is running on device made by: samsung
W/art     (12035): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (12035): Attempt to remove local handle scope entry from IRT, ignoring
D/Activity(12035): performCreate Call secproduct feature valuefalse
D/Activity(12035): performCreate Call debug elastic valuetrue
W/ActivityManager( 3509): Activity pause timeout for ActivityRecord{1e8cb90f u0 com.test.thalitest/.MainActivity t26}
D/OpenGLRenderer(12035): Render dirty regions requested: true
D/ActivityManager( 3509): post active user change for 0
D/KnoxTimeoutHandler( 3509): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3509): handleActiveUserChange for user 0
V/ActivityThread(12035): updateVisibility : ActivityRecord{10c3e4ab token=android.os.BinderProxy@358bd53e {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
I/SurfaceFlinger( 2848): id=13 createSurf (1x1),1 flag=404, NainActivit
D/StatusBarManagerService( 3509): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService( 3509): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 3509): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3509): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3509): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3509): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer(12035): Initialized EGL, version 1.4
I/OpenGLRenderer(12035): HWUI protection enabled for context ,  &this =0xafa45060 ,&mEglDisplay = 1 , &mEglConfig = -1278775024 
D/OpenGLRenderer(12035): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(12035): Enabling debug mode 0
D/mali_winsys(12035): new_window_surface returns 0x3000,  [1440x2560]-format:1
D/InputMethodManagerService( 3509): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl( 3509): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ContextImpl( 3509): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ActivityManager( 3509): mDVFSHelper.release()
I/Timeline( 3509): Timeline: Activity_windows_visible id: ActivityRecord{1e8cb90f u0 com.test.thalitest/.MainActivity t26} time:226399
W/IInputConnectionWrapper(12035): showStatusIcon on inactive InputConnection
I/Timeline(12035): Timeline: Activity_idle id: android.os.BinderProxy@358bd53e time:226405
I/chromium(12035): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(12035): 
D/JsMessageQueue(12035): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log(12035): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1361621120
I/chromium(12035): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/ContextImpl( 3509): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/jxcore-log(12035): Initializing JXcore engine
W/jxcore-log(12035): JXcore engine is ready
,E/auditd  ( 4619): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3509): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl( 3509): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3509): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(12035): Starting JXcore engine
,W/jxcore-log(12035): Platform android
W/jxcore-log(12035): 
W/jxcore-log(12035): Process ARCH arm
W/jxcore-log(12035): 
,I/jxcore-log(12035): JXcore Cordova bridge is ready!
I/jxcore-log(12035): 
W/jxcore-log(12035): JXcore engine is started
,I/jxcore-log(12035): Toggling radios to true
I/jxcore-log(12035): 
,D/BluetoothAdapter(12035): enable()
,D/BluetoothAdapter(12035): enable(): BT is already enabled..!
,D/WifiService( 3509): New client listening to asynchronous messages
,I/WifiManager(12035): packageName : com.test.thalitest
,D/SecContentProvider( 3509): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3509): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3509): mCursor = null
,D/WifiService( 3509): setWifiEnabled: true pid=12035, uid=10623
E/WifiService( 3509): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3509): Permission Denial: getCurrentUser() from pid=12035, uid=10623 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 3509): Failed getting userId using ActivityManagerNative
W/WifiService( 3509): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=12035, uid=10623 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3509): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3509): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3509): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3509): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3509): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider( 3509): name = wifi_on
,I/WifiService( 3509): disconnect: pid=12035, uid=10623
,I/wpa_supplicant( 3830): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log(12035): Radios toggled
I/jxcore-log(12035): 
,I/jxcore-log(12035): My device name is: samsung-SM-N910C
I/jxcore-log(12035): 
,I/wpa_supplicant( 3830): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3830): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 3830): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3830): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine( 3509): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 3830): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3830): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3830): Disconnected - do not scan
I/wpa_supplicant( 3830): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine( 3509): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3509): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3509): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3509): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine( 3509): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3509): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3509): do suspend true
,D/WifiP2pService( 3509): InactiveState{ what=143375 }
D/WifiP2pService( 3509): P2pEnabledState{ what=143375 }
,D/CommandListener( 2844): Clearing all IP addresses on wlan0
,E/Netd    ( 2844): ifc_reset_connections failed on iface wlan0 for address 192.168.1.124/24 (Unknown error -1)
,E/WifiStateMachine( 3509): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/ConnectivityService( 3509): updateNetworkInfo()
E/WifiConfigStore( 3509): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService( 3509): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3509): updateNetworkInfo()
,I/WifiTrafficPoller( 3509): evaluateTrafficStatsPolling
D/ConnectivityService( 3509): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
D/StatusBar.NetworkController( 3691): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
,I/Hs20UtilService( 4078): Starting #8
,I/Hs20UtilService( 4078): Message received 5007
,D/NearbySettings( 8890): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 8890): MountReceiver.onReceive - Start HandlerThread
,D/NearbySettings( 8890): MountReceiver.onReceive - Create mPrefHandler
,E/WifiStateMachine( 3509): Start Disconnecting Watchdog 1
I/wpa_supplicant( 3830): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3830): P2P: Current p2p state = IDLE
I/wpa_supplicant( 3830): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 3830): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3830): First Scan Start
E/WifiStateMachine( 3509): ConnectModeState: Network connection lost 
I/wpa_supplicant( 3830): Scan requested (ret=0) - scan timeout 30 seconds
E/WifiStateMachine( 3509): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - processMessage - processMsg
D/NearbySettings( 8890): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 3509): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine( 3509): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3509): do suspend true
V/NearbySettings( 8890): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8890): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/WifiP2pService( 3509): InactiveState{ what=143375 }
D/WifiP2pService( 3509): P2pEnabledState{ what=143375 }
,D/WifiService( 3509): New client listening to asynchronous messages
,I/NearbySettings( 8890): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8890): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8890): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8890): MountReceiver.mPrefHandler - 7002
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
,I/SignOutReceiver(11569): NETWORK_STATE_CHANGED_ACTION
,D/CommandListener( 2844): Clearing all IP addresses on wlan0
,D/ConnectivityService( 3509): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/EntConnectivity( 3509): Not allowed due to - mEnabled false
E/WifiStateMachine( 3509): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityService( 3509): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3509): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker( 3509): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/WifiStateMachine( 3509): updateConfiguredNetworkExpiration - currTime: 1454523326507
D/CSLegacyTypeTracker( 3509): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/WifiStateMachine( 3509): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
D/ConnectivityService( 3509): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine( 3509): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine( 3509): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityManager.CallbackHandler( 3691): CM callback handler got msg 524292
,D/TelephonyNetworkFactory( 3979): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine( 3509): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3509): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 3509): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3509): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent( 3509): NetworkAgent: NetworkAgent channel lost
D/ConnectivityManager.CallbackHandler( 4766): CM callback handler got msg 524292
I/WifiTrafficPoller( 3509): evaluateTrafficStatsPolling
,E/WifiStateMachine( 3509): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3509): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine( 3509): setDetailed state send new extra info"NG700"
,D/SecContentProvider2( 3509): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3509): mCursor = null
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
,D/EntConnectivity( 3509): Not allowed due to - mEnabled false
D/ConnectivityService( 3509): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/SecContentProvider2( 3509): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3509): mCursor = null
D/SmartBondingService( 3509): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering( 3509): MasterInitialState.processMessage what=3
V/NetworkStats( 3509): updateIfacesLocked()
D/NtpTrustedTime( 3509): currentTimeMillis() cache hit
V/NetworkStats( 3509): performPollLocked(flags=0x1)
D/SmartBondingService( 3509): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3509): getSBEnabled() enabled =false
D/SmartBondingService( 3509): getSBEnabled() enabled =false
D/SmartBondingService( 3509): getSBEnabled() enabled =false
D/NetworkStatsFactory( 3509): UpdateStatsForKnox
D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3691): updateDataNetType()
D/StatusBar.NetworkController( 3691): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3691): updateLTEICONDataNetType:0
D/SmartBondingService( 3509): getNetworkEnabled : wifi : true mobile : false
V/NetworkStats( 3509): performPollLocked() took 5ms
D/NtpTrustedTime( 3509): currentTimeMillis() cache hit
D/NtpTrustedTime( 3509): currentTimeMillis() cache hit
D/NtpTrustedTime( 3509): currentTimeMillis() cache hit
D/NtpTrustedTime( 3509): currentTimeMillis() cache hit
V/NetworkStats( 3509): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3509): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 3691): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
I/Hs20UtilService( 4078): Starting #9
I/Hs20UtilService( 4078): Message received 5007
,D/NtpTrustedTime( 3509): currentTimeMillis() cache hit
D/NtpTrustedTime( 3509): currentTimeMillis() cache hit
,D/NearbySettings( 8890): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8890): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8890): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8890): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8890): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8890): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8890): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11569): NETWORK_STATE_CHANGED_ACTION
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,D/ConnectivityService( 3509): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 3509): updateDataUsageMap
I/ApplicationPolicy( 3509): updateDataUsageMap  idList is null 
,D/SmartBondingService( 3509): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3509): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3509): getSBEnabled() enabled =false
D/SmartBondingService( 3509): getSBEnabled() enabled =false
D/SmartBondingService( 3509): getSBEnabled() enabled =false
,D/SmartBondingService( 3509): getNetworkEnabled : wifi : true mobile : false
D/GpsLocationProvider( 3509): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/SLocation( 3509): No Active Data Connection
,I/DBG_DM  ( 6306): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/DBG_DM  ( 6306): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12138): MountEmulatedStorage()
E/Zygote  (12138): v2
I/libpersona(12138): KNOX_SDCARD checking this for 10110
I/libpersona(12138): KNOX_SDCARD not a persona
,I/SELinux (12138): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12138): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12138): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3509): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.iorg.vpn.cleanup.NetworkStateMonitor: pid=12138 uid=10110 gids={50110, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12138): TimaSignature is unavailable
,D/ActivityThread(12138): Added TimaKeyStore provider
,D/ResourcesManager(12138): creating new AssetManager and set to /data/app/com.facebook.appmanager-2/base.apk
,D/ACRA    (12138): ACRA is enabled for com.facebook.appmanager, intializing...
,I/DexLibLoader(12138): not using cross-dex optimization: ART in use
,I/art     (12138): Thread[1,tid=12138,WaitingForJniOnLoad,Thread*=0xb4e08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/app/com.facebook.appmanager-2/lib/arm/libfbjni.so"
,V/DexLibLoader(12138): about to lock: /data/data/com.facebook.appmanager/mdex_lock
,V/DexLibLoader(12138): locking /data/data/com.facebook.appmanager/mdex_lock took 1 ms
V/DexLibLoader(12138): Secondary program dex metadata: classes2.dex 29f80981f469a774a4884b3db2df17e0be227159 secondary.dex01.Canary
,D/DexLibLoader(12138): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex" is valid
D/DexLibLoader(12138): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex_opt" is valid
,W/art     (12138): Attempt to remove local handle scope entry from IRT, ignoring
D/DexLibLoader(12138): loading pre-built fallback odex files
,V/MultiDexClassLoader(12138): installing MultiDexClassLoader before application classloader
,D/DexLibLoader(12138): released odex store lock
D/DexLibLoader(12138): DexLibLoader.loadAll took 18 ms
,W/ca      (12138): Verify
,W/LightSharedPreferencesImpl(12138): Failed to load preference file from Disk!
W/LightSharedPreferencesImpl(12138): java.io.FileNotFoundException: /data/data/com.facebook.appmanager/app_light_prefs/com.facebook.appmanager/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(12138): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/LightSharedPreferencesImpl(12138): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/LightSharedPreferencesImpl(12138): 	at com.facebook.crudolib.b.k.a(LightSharedPreferencesStorage.java:56)
W/LightSharedPreferencesImpl(12138): 	at com.facebook.crudolib.b.g.run(LightSharedPreferencesImpl.java:61)
W/LightSharedPreferencesImpl(12138): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/LightSharedPreferencesImpl(12138): 	at com.facebook.common.executors.dj.run(WrappingExecutorService.java:77)
W/LightSharedPreferencesImpl(12138): 	at com.facebook.common.executors.u.run(DefaultConstrainedListeningExecutorService.java:327)
W/LightSharedPreferencesImpl(12138): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/LightSharedPreferencesImpl(12138): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/LightSharedPreferencesImpl(12138): 	at com.facebook.common.executors.cc.run(NamedThreadFactory.java:42)
W/LightSharedPreferencesImpl(12138): 	at java.lang.Thread.run(Thread.java:818)
W/LightSharedPreferencesImpl(12138): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(12138): 	at libcore.io.Posix.open(Native Method)
W/LightSharedPreferencesImpl(12138): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/LightSharedPreferencesImpl(12138): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/LightSharedPreferencesImpl(12138): 	... 10 more
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12163): MountEmulatedStorage()
E/Zygote  (12163): v2
I/libpersona(12163): KNOX_SDCARD checking this for 1000
I/libpersona(12163): KNOX_SDCARD not a persona
,I/SELinux (12163): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12163): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12163): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3509): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=12163 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 3509): Killing 11083:com.android.mms/u0a52 (adj 15): bgCount ##31
,W/appmanager(:<default>):b(12138): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
W/appmanager(:<default>):b(12138): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/TimaKeyStoreProvider(12163): TimaSignature is unavailable
,D/ActivityThread(12163): Added TimaKeyStore provider
,D/ResourcesManager(12163): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,W/appmanager(:<default>):QuickExperimentControllerImpl(12138): Exposure of experiment com.facebook.common.network.l@202e1009 occurred when no user was logged in
,I/PCWCLIENTTRACE_LOG(12163): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(12163): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(12163): new DMDBOpenHelper instance
,D/CountryDetector( 3509): No listener is left
,W/BroadcastQueue( 3509): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{3c9c5732 u0 ReceiverList{2952f33d 12138 com.facebook.appmanager/10110/u0 remote:2c8f9c94}}
,W/BroadcastQueue( 3509): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{3c9c5732 u0 ReceiverList{2952f33d 12138 com.facebook.appmanager/10110/u0 remote:2c8f9c94}}
I/PCWCLIENTTRACE_PushUtil(12163): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(12163): sales region : global
I/PCWCLIENTTRACE_PushUtil(12163): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(12163): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver(12163): noConnectivity : true
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12188): MountEmulatedStorage()
I/libpersona(12188): KNOX_SDCARD checking this for 10135
E/Zygote  (12188): v2
I/libpersona(12188): KNOX_SDCARD not a persona
,I/SELinux (12188): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12188): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12188): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3509): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=12188 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3509): Killing 11169:com.sec.android.app.samsungapps/u0a13 (adj 15): bgCount ##31
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 8729(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 717us total 11.237ms
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 272us total 8.659ms
,D/TimaKeyStoreProvider(12188): TimaSignature is unavailable
,D/ActivityThread(12188): Added TimaKeyStore provider
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 453us total 8.739ms
,D/ResourcesManager(12188): creating new AssetManager and set to /system/app/Music2/Music2.apk
,W/BroadcastQueue( 3509): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{2e8d556 u0 ReceiverList{3d4fc371 12138 com.facebook.appmanager/10110/u0 remote:30017d18}}
,I/MusicStore(12188): Database version: 104
,D/ResourcesManager(12188): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(12188): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(12188): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (12188): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(12188): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (12188): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3864c35f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(12188): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(12188): GMSCore installation verified
,I/ConfigStore(12188): Config Database version: 1
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12188): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12188): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,I/wpa_supplicant( 3830): nl80211: Received scan results (4 BSSes)
I/wpa_supplicant( 3830): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3830): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
,I/wpa_supplicant( 3830): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 3830): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3509): [1,454,523,327,559 ms] noteScanEnd no scan source
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12188): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/WifiStateMachine( 3509): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@3a1b8fe sup_state=SCANNING debouncing=false
,E/WifiStateMachine( 3509): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3509): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3509): setDetailed state send new extra info
,D/SecContentProvider2( 3509): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3509): mCursor = null
,I/art     ( 3509): Explicit concurrent mark sweep GC freed 63518(3MB) AllocSpace objects, 44(704KB) LOS objects, 24% free, 49MB/65MB, paused 1.230ms total 80.984ms
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12138): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12138): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,D/WifiDisplayAdapter( 3509): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3509): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3509): getStreamVolume 3 index 0
,I/MediaRouter(12188): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/wpa_supplicant( 3830): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 3830): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 3830): Associated with C0.AA.48
E/WifiStateMachine( 3509): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3509): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3509): setDetailed state send new extra info"NG700"
,D/SecContentProvider2( 3509): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3509): mCursor = null
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,W/appmanager(:<default>):QuickExperimentControllerImpl(12138): Exposure of experiment com.facebook.imagepipeline.a.g@20d9578e occurred when no user was logged in
,W/appmanager(:<default>):QuickExperimentControllerImpl(12138): Exposure of experiment com.facebook.imagepipeline.a.d@2c6263cb occurred when no user was logged in
,E/Zygote  (12221): MountEmulatedStorage()
I/libpersona(12221): KNOX_SDCARD checking this for 10002
E/Zygote  (12221): v2
I/libpersona(12221): KNOX_SDCARD not a persona
,I/SELinux (12221): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12221): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12221): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3509): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=12221 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/wpa_supplicant( 3830): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 3830): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3509): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3509): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,I/wpa_supplicant( 3830): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/art     (12138): Explicit concurrent mark sweep GC freed 48917(2MB) AllocSpace objects, 6(96KB) LOS objects, 22% free, 27MB/35MB, paused 992us total 24.528ms
W/appmanager(:<default>):m(12138): No feature status reporters found; is this dead code?
,I/wpa_supplicant( 3830): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 3830): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 3830): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3830): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 3830): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 3830): Blacklist: Clear (temp) 
I/wpa_supplicant( 3830): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/WifiDisplayAdapter( 3509): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/WifiStateMachine( 3509): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3509): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,D/TimaKeyStoreProvider(12221): TimaSignature is unavailable
,D/ActivityThread(12221): Added TimaKeyStore provider
E/WifiStateMachine( 3509): Network connection established
,D/WifiNative-HAL( 3509): callSECApiVoid - ID [50]
E/WifiStateMachine( 3509): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/NetworkMonitor(12188): type=WIFI subType= reason=null isConnected=false
,E/WifiStateMachine( 3509): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService( 3509): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine( 3509): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService( 3509): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/WifiStateMachine( 3509): L2ConnectedState "NG700" nid=0
E/WifiConfigStore( 3509): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 3509): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 3509): updateNetworkInfo()
,E/WifiStateMachine( 3509): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine( 3509): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3509): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3509): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ResourcesManager(12221): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
,I/ActivityManager( 3509): Killing 11185:com.sec.android.app.myfiles/u0a53 (adj 15): bgCount ##31
,D/CommandListener( 2844): Setting iface cfg
,E/WifiStateMachine( 3509): Start Dhcp Watchdog 2
,D/SecContentProvider2( 3509): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3509): mCursor = null
,D/SecContentProvider2( 3509): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3509): mCursor = null
,E/WifiStateMachine( 3509): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3509): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/ActivityManager( 3509): Killing 11211:com.sec.android.provider.badge/u0a82 (adj 15): bgCount ##31
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12245): MountEmulatedStorage()
E/Zygote  (12245): v2
I/libpersona(12245): KNOX_SDCARD checking this for 1000
I/libpersona(12245): KNOX_SDCARD not a persona
,I/SELinux (12245): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12245): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12245): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3509): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=12245 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12245): TimaSignature is unavailable
,D/ActivityThread(12245): Added TimaKeyStore provider
,D/ResourcesManager(12245): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT(12245): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,E/WifiStateMachine( 3509): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3509): do suspend false
,D/SecContentProvider2( 3509): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3509): mCursor = null
,D/WifiP2pService( 3509): InactiveState{ what=143375 }
D/WifiP2pService( 3509): P2pEnabledState{ what=143375 }
,I/DIAGMON_AGENT(12245): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT(12245): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT(12245): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(12245): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12261): MountEmulatedStorage()
E/Zygote  (12261): v2
I/libpersona(12261): KNOX_SDCARD checking this for 10012
I/libpersona(12261): KNOX_SDCARD not a persona
,I/SELinux (12261): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12261): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12261): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3509): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=12261 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12261): TimaSignature is unavailable
,D/ActivityThread(12261): Added TimaKeyStore provider
,D/ResourcesManager(12261): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager( 3509): Killing 11052:com.google.android.apps.docs/u0a101 (adj 15): bgCount ##31
,I/FOTA_Client(12261): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(12261): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
E/lowmemorykiller( 2827): Error writing /proc/11052/oom_score_adj; errno=22
,I/FOTA_Client(12261): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12277): MountEmulatedStorage()
I/libpersona(12277): KNOX_SDCARD checking this for 10021
E/Zygote  (12277): v2
I/libpersona(12277): KNOX_SDCARD not a persona
,I/SELinux (12277): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12277): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3509): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=12277 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
E/SELinux (12277): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3509): Killing 11228:com.sec.spp.push/u0a39 (adj 15): bgCount ##31
,E/lowmemorykiller( 2827): Error writing /proc/11228/oom_score_adj; errno=22
D/TimaKeyStoreProvider(12277): TimaSignature is unavailable
D/ActivityThread(12277): Added TimaKeyStore provider
E/dhcpcd  (12292): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
D/ResourcesManager(12277): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
I/dhcpcd  (12292): version 5.5.6 starting
E/dhcpcd  (12292): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/KLMS-2.4.521: (12277): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Feb 03 19:15:28 GMT+01:00 2016
I/KLMS-2.4.521: (12277): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (12277): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12277): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
I/KLMS-2.4.521: (12277): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/KLMS-2.4.521: (12277): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/KLMS-2.4.521: (12277): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (12277): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
E/Zygote  (12299): MountEmulatedStorage()
I/libpersona(12299): KNOX_SDCARD checking this for 10038
E/Zygote  (12299): v2
I/libpersona(12299): KNOX_SDCARD not a persona
I/SELinux (12299): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/KLMS-2.4.521: (12277): StateImplV2(): networkChangeListener().END
,I/SELinux (12299): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12299): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3509): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=12299 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/dhcpcd  (12292): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (12292): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (12292): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  (12292): bssid match
I/dhcpcd  (12292): wlan0: rebinding lease of 192.168.1.124
,I/KLMS-2.4.521: (12277): KLMSIntentService(): onDestroy()
I/ActivityManager( 3509): Killing 11269:com.sec.android.app.soundalive/u0a59 (adj 15): bgCount ##31
,E/lowmemorykiller( 2827): Error writing /proc/11269/oom_score_adj; errno=22
,D/TimaKeyStoreProvider(12299): TimaSignature is unavailable
,D/ActivityThread(12299): Added TimaKeyStore provider
,D/ResourcesManager(12299): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT(12299): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12316): MountEmulatedStorage()
I/libpersona(12316): KNOX_SDCARD checking this for 1000
E/Zygote  (12316): v2
I/libpersona(12316): KNOX_SDCARD not a persona
I/SELinux (12316): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12316): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12316): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3509): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=12316 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3509): Killing 11338:com.wsomacp/u0a28 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12316): TimaSignature is unavailable
,D/ActivityThread(12316): Added TimaKeyStore provider
,D/ResourcesManager(12316): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12336): MountEmulatedStorage()
,E/Zygote  (12336): v2
I/libpersona(12336): KNOX_SDCARD checking this for 10039
I/libpersona(12336): KNOX_SDCARD not a persona
I/SELinux (12336): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3509): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=12336 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (12336): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12336): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3509): Killing 11323:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12336): TimaSignature is unavailable
,D/ActivityThread(12336): Added TimaKeyStore provider
,D/ResourcesManager(12336): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService(12336): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(12336): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService(12336): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,D/SPPClientService(12336): PushLog.txt file is not deleted.
D/SPPClientService(12336): PushLog.txt file is not deleted.
D/SPPClientService(12336): ============PushLog. stop!
,I/SA      (11384): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11384): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      (11384): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      (11384): [SLFUCHKMGR] constructor called
,E/SPPClientService(12336): [[SystemStateMonitorService]] No Active Internet
,I/SA      (11384): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11384): [OR] == isSIMCardReady false ==
,I/SA      (11384): [SCU] == networkStateCheck == false
I/SA      (11384): [OR] onReceive END
,I/ActivityManager( 3509): Killing 11307:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
,V/DownloadManager( 3714): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,E/lowmemorykiller( 2827): Error writing /proc/11307/oom_score_adj; errno=22
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/lowmemorykiller( 2827): Error writing /proc/11307/oom_score_adj; errno=22
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,E/lowmemorykiller( 2827): Error writing /proc/11307/oom_score_adj; errno=22
,E/Zygote  (12356): MountEmulatedStorage()
I/libpersona(12356): KNOX_SDCARD checking this for 10067
E/Zygote  (12356): v2
I/libpersona(12356): KNOX_SDCARD not a persona
,I/SELinux (12356): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12356): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12356): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3509): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=12356 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12356): TimaSignature is unavailable
,D/ActivityThread(12356): Added TimaKeyStore provider
,D/ResourcesManager(12356): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/sCloudBackupApp(12356): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(12356): Other Intent
,I/ActivityManager( 3509): Killing 11248:com.sec.android.automotive.drivelink/u0a102 (adj 13): bgCount ##31
,D/accuweather( 5214): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3770): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,D/accuweather( 5214): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5214): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5214): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5214): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5214): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5214): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12372): MountEmulatedStorage()
E/Zygote  (12372): v2
I/libpersona(12372): KNOX_SDCARD checking this for 1000
I/libpersona(12372): KNOX_SDCARD not a persona
,I/SELinux (12372): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12372): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12372): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3509): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=12372 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12372): TimaSignature is unavailable
,D/ActivityThread(12372): Added TimaKeyStore provider
,D/ResourcesManager(12372): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(12372): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro(12372): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro(12372): premStatus:2
,I/KnoxUsageLogPro(12372): isEulaShown : false
I/KnoxUsageLogPro(12372): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12387): MountEmulatedStorage()
I/libpersona(12387): KNOX_SDCARD checking this for 10090
E/Zygote  (12387): v2
I/libpersona(12387): KNOX_SDCARD not a persona
I/SELinux (12387): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12387): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12387): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3509): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=12387 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3509): Killing 11287:com.samsung.android.sdk.samsunglink/u0a42 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12387): TimaSignature is unavailable
,D/ActivityThread(12387): Added TimaKeyStore provider
,D/ResourcesManager(12387): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12403): MountEmulatedStorage()
I/libpersona(12403): KNOX_SDCARD checking this for 10127
E/Zygote  (12403): v2
I/libpersona(12403): KNOX_SDCARD not a persona
I/SELinux (12403): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12403): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12403): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3509): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=12403 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3509): Killing 11421:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 8749(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 285us total 9.752ms
,D/TimaKeyStoreProvider(12403): TimaSignature is unavailable
,D/ActivityThread(12403): Added TimaKeyStore provider
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 260us total 8.558ms
,D/ResourcesManager(12403): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 512us total 8.769ms
,D/KeyguardWallpaperUpdator(12403): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12403): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12403): stopCheckCategoryVersion
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12419): MountEmulatedStorage()
I/libpersona(12419): KNOX_SDCARD checking this for 10136
E/Zygote  (12419): v2
I/libpersona(12419): KNOX_SDCARD not a persona
,I/SELinux (12419): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12419): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12419): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3509): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=12419 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3509): Killing 11403:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12419): TimaSignature is unavailable
,D/ActivityThread(12419): Added TimaKeyStore provider
,D/ResourcesManager(12419): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12419): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12419): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12419): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12419): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory(12419): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(12419): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(12419): Loading: webviewchromium
,I/LibraryLoader(12419): Time to load native libraries: 3 ms (timestamps 38-41)
I/LibraryLoader(12419): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(12419): Binding Chromium to main looper Looper (main, tid 1) {383c367b}
,I/LibraryLoader(12419): Expected native library version number "",actual native library version number ""
,I/chromium(12419): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(12419): Initializing chromium process, renderers=0
,W/art     (12419): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(12419): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,W/AudioManagerAndroid(12419): Requires BLUETOOTH permission
I/chromium(12419): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium(12419): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,I/NSApplication(12419): Starting up...
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12487): MountEmulatedStorage()
I/libpersona(12487): KNOX_SDCARD checking this for 10150
E/Zygote  (12487): v2
I/libpersona(12487): KNOX_SDCARD not a persona
,I/SELinux (12487): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12487): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12487): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3509): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=12487 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager( 3509): Killing 11455:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12487): TimaSignature is unavailable
,D/ActivityThread(12487): Added TimaKeyStore provider
,D/ResourcesManager(12487): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(12487): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12487): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12487): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect(12487): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12487): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect(12487): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12502): MountEmulatedStorage()
I/libpersona(12502): KNOX_SDCARD checking this for 10178
E/Zygote  (12502): v2
I/libpersona(12502): KNOX_SDCARD not a persona
I/SELinux (12502): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12502): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12502): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3509): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=12502 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager( 3509): Killing 11471:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12502): TimaSignature is unavailable
,D/ActivityThread(12502): Added TimaKeyStore provider
,D/ResourcesManager(12502): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(12502): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager(12502): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12502): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12502): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12502): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12502): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService( 3509): exchangeData() failure , invalid userId
,D/RCPManagerService( 3509): exchangeData() failure , invalid userId
,D/RCPManagerService( 3509): exchangeData() failure , invalid userId
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 3509): exchangeData() failure , invalid userId
,E/Zygote  (12525): MountEmulatedStorage()
I/libpersona(12525): KNOX_SDCARD checking this for 10082
E/Zygote  (12525): v2
I/libpersona(12525): KNOX_SDCARD not a persona
I/SELinux (12525): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12525): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12525): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/RCPManagerService( 3509): exchangeData() failure , invalid userId
,I/ActivityManager( 3509): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=12525 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,D/RCPManagerService( 3509): exchangeData() failure , invalid userId
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(12525): TimaSignature is unavailable
,D/ActivityThread(12525): Added TimaKeyStore provider
,E/Zygote  (12541): MountEmulatedStorage()
E/Zygote  (12541): v2
I/libpersona(12541): KNOX_SDCARD checking this for 1000
I/libpersona(12541): KNOX_SDCARD not a persona
,I/SELinux (12541): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12541): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12541): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3509): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=12541 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3509): Killing 11487:com.samsung.helphub/1000 (adj 13): bgCount ##31
,I/ActivityManager( 3509): Killing 11592:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12541): TimaSignature is unavailable
,D/ActivityThread(12541): Added TimaKeyStore provider
,D/ResourcesManager(12525): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/ResourcesManager(12541): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/BadgeProvider(12525): onCreate
,D/BadgeProvider(12525): DatabaseHelper
,D/BadgeProvider(12525): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/ActivityManager( 3509): Killing 11609:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
,D/BadgeProvider(12525): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider(12525): sendNotify, [notify] : null
D/BadgeProvider(12525): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12525): update, [BadgeCount] : badgecount=0
D/BadgeProvider(12525): update, [UpdateCount] : 1
,D/Launcher.Model( 3999): reloadBadges entered.
,W/ActivityManager( 3509): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/iu.Environment( 4766): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 4766): num queued entries: 0
,I/iu.UploadsManager( 4766): num updated entries: 0
I/iu.SyncManager( 4766): NEXT; no task
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12560): MountEmulatedStorage()
E/Zygote  (12560): v2
I/libpersona(12560): KNOX_SDCARD checking this for 10013
I/libpersona(12560): KNOX_SDCARD not a persona
,I/SELinux (12560): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12560): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12560): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3509): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=12560 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12560): TimaSignature is unavailable
,D/ActivityThread(12560): Added TimaKeyStore provider
,D/ResourcesManager(12560): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,I/ActivityManager( 3509): Killing 11626:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##31
,I/Hs20UtilService( 4078): Starting #10
,I/Hs20UtilService( 4078): Message received 5007
,D/NearbySettings( 8890): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8890): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8890): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 8890): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8890): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8890): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8890): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11569): NETWORK_STATE_CHANGED_ACTION
,I/jxcore-log(12035): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log(12035): 
,I/dhcpcd  (12292): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
,I/dhcpcd  (12292): wlan0: leased 192.168.1.124 for 86400 seconds
,E/WifiStateMachine( 3509): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3509): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine( 3509): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine( 3509): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  ( 3509): do suspend true
,D/WifiP2pService( 3509): InactiveState{ what=143375 }
D/WifiP2pService( 3509): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 3509): WifiStateMachine DHCP successful
,E/WifiStateMachine( 3509): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3509): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine( 3509): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3509): Not connected state, yet.
E/WifiStateMachine( 3509): VerifyingLinkState enter
,D/WifiStateMachine( 3509): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine( 3509): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3509): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3509): callSECApiInt - ID [210]
,E/WifiStateMachine( 3509): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
E/ConnectivityService( 3509): updateNetworkInfo()
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
,D/ConnectivityService( 3509): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 3509): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 3509): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 3509): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 3509): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 3509): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3509): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
,I/Hs20UtilService( 4078): Starting #11
,D/NearbySettings( 8890): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/Hs20UtilService( 4078): Message received 5007
I/NearbySettings( 8890): MountReceiver.onReceive - Keep current state
,I/SignOutReceiver(11569): NETWORK_STATE_CHANGED_ACTION
,E/WifiStateMachine( 3509): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine( 3509): Now, connected state.
D/ConnectivityService( 3509): Adding Route [fe80::/64 -> :: wlan0] to network 503
E/WifiStateMachine( 3509): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,D/ConnectivityService( 3509): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService( 3509): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
E/ConnectivityService( 3509): Unexpected mtu value: 0, wlan0
,V/        ( 2844): QcRouteController
E/WifiStateMachine( 3509): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,E/WifiStateMachine( 3509): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/WifiTrafficPoller( 3509): evaluateTrafficStatsPolling
,E/WifiStateMachine( 3509): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
V/        ( 2844): QcRouteController
,I/WifiTrafficPoller( 3509): evaluateTrafficStatsPolling
,D/WifiNative-HAL( 3509): callSECApiVoid - ID [212]
,I/WifiStateMachine( 3509): REQUEST_POWER_SAVE_ON
,D/StatusBar.NetworkController( 3691): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
,V/        ( 2844): QcRouteController
,I/Hs20UtilService( 4078): Starting #12
,I/Hs20UtilService( 4078): Message received 5007
,D/NearbySettings( 8890): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8890): DMSUtil.isNetworkConnected - flag-null, state-null
,V/        ( 2844): QcRouteController
I/NearbySettings( 8890): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8890): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8890): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8890): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 8890): MountReceiver.mPrefHandler - 7002
,V/        ( 2844): QcRouteController
,I/SignOutReceiver(11569): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2844): QcRouteController
,V/        ( 2844): QcRouteController
,I/Hs20UtilService( 4078): Starting #13
,D/NearbySettings( 8890): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8890): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 4078): Message received 5007
,V/        ( 2844): QcRouteController
,I/WifiStateMachine( 3509): callSECApi what=220
D/WifiStateMachine( 3509): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/ConnectivityService( 3509): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService( 3509): LTETest block dns file not exists
,D/ConnectivityService( 3509): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 3509): updateNetworkInfo()
D/ConnectivityService( 3509): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3509): updateNetworkInfo()
D/ConnectivityService( 3509): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3509): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3509): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3509): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3509): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3509): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService( 3509):    accepting network in place of null
,E/CSLegacyTypeTracker( 3509): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 3509): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 3509): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/TelephonyNetworkFactory( 3979): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/System.out( 3509): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2844): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2844): getNetworkForDns: using netid 503 for uid 1000
,D/ConnectivityService( 3509): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/Tethering( 3509): MasterInitialState.processMessage what=3
D/SmartBondingService( 3509): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService( 3509): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/ConnectivityService( 3509): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/SmartBondingService( 3509): getSBEnabled() enabled =false
D/SmartBondingService( 3509): getSBEnabled() enabled =false
D/NtpTrustedTime( 3509): currentTimeMillis() cache hit
D/SmartBondingService( 3509): getSBEnabled() enabled =false
D/ConnectivityManager.CallbackHandler( 3691): CM callback handler got msg 524290
V/NetworkStats( 3509): updateIfacesLocked()
V/NetworkStats( 3509): performPollLocked(flags=0x1)
,D/ConnectivityManager.CallbackHandler( 4766): CM callback handler got msg 524290
,D/SmartBondingService( 3509): getNetworkEnabled : wifi : true mobile : false
,D/NetworkStatsFactory( 3509): UpdateStatsForKnox
,V/NetworkStats( 3509): performPollLocked() took 6ms
D/NtpTrustedTime( 3509): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3509): currentTimeMillis() cache hit
,I/SignOutReceiver(11569): NETWORK_STATE_CHANGED_ACTION
,D/NtpTrustedTime( 3509): currentTimeMillis() cache hit
D/NtpTrustedTime( 3509): currentTimeMillis() cache hit
V/NetworkStats( 3509): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3509): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3509): currentTimeMillis() cache hit
D/NtpTrustedTime( 3509): currentTimeMillis() cache hit
,I/SurfaceFlinger( 2848): id=14 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 3509): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3509
,D/mali_winsys( 3691): new_window_surface returns 0x3000,  [1120x201]-format:1
,D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3691): updateDataNetType()
D/StatusBar.NetworkController( 3691): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3691): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3691): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength: hasService=false ss=null
,D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3691): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
,I/System.out( 3509): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/jxcore-log(12035): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log(12035): 
,I/jxcore-log(12035): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log(12035): 
,I/jxcore-log(12035): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log(12035): 
,I/jxcore-log(12035): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log(12035): 
,I/jxcore-log(12035): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log(12035): 
,I/jxcore-log(12035): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log(12035): 
,I/jxcore-log(12035): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log(12035): 
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3509): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 03 Feb 2016 18:15:29 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454523330004], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454523329822]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3509): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3509): Validated
D/ConnectivityService( 3509): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3509): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3509): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 3509): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3691): CM callback handler got msg 524290
D/ConnectivityService( 3509): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 4766): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3691): updateDataNetType()
D/StatusBar.NetworkController( 3691): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3691): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3691): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength: hasService=false ss=null
,D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3691): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/ConnectivityService( 3509): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3509): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3509): SmartBondingReceiver: wifi is connected
D/SmartBondingService( 3509): SmartBondingReceiver: wifi ap is not changed
,D/SmartBondingService( 3509): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3509): getSBEnabled() enabled =false
D/SmartBondingService( 3509): getSBEnabled() enabled =false
D/SmartBondingService( 3509): getSBEnabled() enabled =false
,D/SmartBondingService( 3509): getNetworkEnabled : wifi : true mobile : false
,I/DBG_DM  ( 6306): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 6306): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/GpsLocationProvider( 3509): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/ResourceType( 5356): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5356): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,I/NetworkMonitor(12188): type=WIFI subType= reason=null isConnected=true
,I/PCWCLIENTTRACE_PushUtil(12163): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(12163): sales region : global
I/PCWCLIENTTRACE_PushUtil(12163): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(12163): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/SecContentProvider2( 3509): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3509): mCursor = null
,I/DIAGMON_AGENT(12245): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(12245): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/FOTA_Client(12261): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(12261): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(12261): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.521: (12277): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Feb 03 19:15:30 GMT+01:00 2016
,I/KLMS-2.4.521: (12277): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (12277): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12277): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (12277): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (12277): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12277): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/SO_AGENT(12299): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,I/KLMS-2.4.521: (12277): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.521: (12277): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.521: (12277): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.521: (12277): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.4.521: (12277): StateImplV2(): networkChangeListener().END
,I/KLMS-2.4.521: (12277): KLMSIntentService(): onDestroy()
,E/SPPClientService(12336): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      (11384): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11384): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (11384): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (11384): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11384): [OR] == isSIMCardReady false ==
I/SA      (11384): [SCU] == networkStateCheck == true
,I/SA      (11384): [DM] getCountryCodeFromCSC : PL
I/SA      (11384): isChinaCountryCode : false
I/SA      (11384): [SCU] is ChinestModel Data Restricted   : false
I/SA      (11384): [OR] == networkStateCheck true ==
I/SA      (11384): [OR] GetMyCountryZoneTask
I/SA      (11384): [OR] onReceive END
,I/SA      (11384): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 3714): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      (11384): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11384): [SSP] query invoked
,I/SA      (11384): [TPMU] GetMccFromDB : null
I/SA      (11384): [SCU] getMccFromPreferece mcc = 260
I/SA      (11384): [TPM] isNoProxy(default) : true
,I/SCloudBackupReceiver(12356): Other Intent
,D/accuweather( 5214): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3770): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 10
,D/accuweather( 5214): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5214): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5214): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5214): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5214): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5214): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro(12372): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro(12372): premStatus:2
,I/KnoxUsageLogPro(12372): isEulaShown : false
I/KnoxUsageLogPro(12372): KnoxUsageReceiver onReceive : not Processible, just return
,D/KeyguardWallpaperUpdator(12403): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12403): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12403): stopCheckCategoryVersion
,D/QuickConnect(12487): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12487): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect(12487): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 3509): exchangeData() failure , invalid userId
,D/RCPManagerService( 3509): exchangeData() failure , invalid userId
,I/iu.Environment( 4766): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 4766): num queued entries: 0
,I/iu.UploadsManager( 4766): num updated entries: 0
I/iu.SyncManager( 4766): NEXT; no task
,D/WaitQueueForNetworkActivate(12560): notifyNetworkActivated
,D/EnterpriseController( 2844): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2844): getNetworkForDns: using netid 503 for uid 10014
,W/ContextImpl(12560): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3509): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/hcjo    (12560): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12560): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12560): exit::IDLE
D/InitializeManagerStateMachine(12560): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12560): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12560): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12560): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12560): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12560): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12560): entry::SUCCESS
D/hcjo    (12560): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (12560): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12560): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine(12560): exit::SUCCESS
D/InitializeManagerStateMachine(12560): entry::IDLE
,I/SA      (11384): [RC New] Execute method=[GET] start
,I/SA      (11384): [RC New] Security=[true]
,I/System.out(11384): Thread-1555(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out(11384): Thread-1555(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11384): Thread-1555(ApacheHTTPLog):isShipBuild true
I/System.out(11384): Thread-1555(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2844): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2844): getNetworkForDns: using netid 503 for uid 10045
,D/ConnectivityService( 3509): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/SA      (11384): [RC New] [v2liruge] api execute + 662
I/SA      (11384): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out(11384): AsyncTask #1 calls detatch()
I/SA      (11384): [TPMU] getNetworkMcc : 
I/SA      (11384): [SCU] saveMccToPreferece Start
I/SA      (11384): [SCU] RegionMCC : 260
I/SA      (11384): [SSP] query invoked
I/art     ( 3509): Explicit concurrent mark sweep GC freed 51944(2MB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 48MB/64MB, paused 1.293ms total 72.776ms
I/SA      (11384): [TPMU] GetMccFromDB : null
I/SA      (11384): [SCU] getMccFromPreferece mcc = 260
I/SA      (11384): [SCU] saveMccToPreferece End
I/SA      (11384): [RC New] executeRequest [v2liruge] end. 757
I/SA      (11384): [RC New] Execute end
I/SA      (11384): [OR] GetMyCountryZoneTask mcc = 260
I/SA      (11384): [OR] GetMyCountryZoneTask Success
,I/dhcpcd  (12292): wlan0: sending IPv6 Router Solicitation
,E/dhcpcd  (12292): wlan0: sendmsg: Cannot assign requested address
,E/WifiStateMachine( 3509): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3509): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityService( 3509): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
V/        ( 2844): QcRouteController
D/SmartBondingService( 3509): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
D/SmartBondingService( 3509): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3509): getSBEnabled() enabled =false
D/SmartBondingService( 3509): getSBEnabled() enabled =false
D/SmartBondingService( 3509): getSBEnabled() enabled =false
,V/        ( 2844): QcRouteController
,W/NetworkManagementService( 3509): route cmd failed: 
W/NetworkManagementService( 3509): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '76 route replace src v6 wlan0 fe80::92b6:86ff:fe43:731c 2 ::' failed with '400 76 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService( 3509): '
W/NetworkManagementService( 3509): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService( 3509): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService( 3509): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService( 3509): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService( 3509): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService( 3509): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5738)
W/NetworkManagementService( 3509): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5545)
W/NetworkManagementService( 3509): 	at com.android.server.ConnectivityService.access$2600(ConnectivityService.java:231)
W/NetworkManagementService( 3509): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2436)
W/NetworkManagementService( 3509): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 3509): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService( 3509): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ConnectivityService( 3509): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3691): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 4766): CM callback handler got msg 524295
D/ConnectivityService( 3509): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 3691): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 4766): CM callback handler got msg 524295
,D/SSRM:n  ( 3509): SIOP:: AP = 280, PST = 248, CUR = 32
,D/WearableService( 4629): callingUid 10014, callindPid: 4629
,D/ResourcesManager(12188): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(12188): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(12188): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory(12188): Using the GMSCore's GoogleHttpClient
,I/MusicLeanback(12188): Conditions not met for autocaching.
I/MusicLeanback(12188): Stop autocaching.
,D/WearableClient(12188): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(12188): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(12188): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(12188): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(12188): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils(12188): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/ActivityThread(12188): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@28fe1b17 that was originally bound here
E/ActivityThread(12188): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@28fe1b17 that was originally bound here
E/ActivityThread(12188): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(12188): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(12188): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(12188): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(12188): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(12188): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(12188): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(12188): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(12188): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(12188): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(12188): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(12188): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(12188): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(12188): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(12188): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(12188): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(12188): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(12188): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(12188): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(12188): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(12188): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(12188): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(12188): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(12188): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(12188): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/WifiStateMachine( 3509): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine( 3509): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/jxcore-log(12035): Test app app.js loaded
I/jxcore-log(12035): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(12035): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(12035): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(12035): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(12035): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(12035): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(12035): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(12035): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(12035): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(12035): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(12035): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@107dab6d added. We now have 1 listener(s)
,I/jxcore-log(12035): BLE advertisement is supported
I/jxcore-log(12035): 
,I/chromium(12035): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log(12035): --= Surplus to requirements =--
I/jxcore-log(12035): 
I/jxcore-log(12035): ****TEST TOOK:  ms ****
I/jxcore-log(12035): 
I/jxcore-log(12035): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(12035): 
,I/SurfaceFlinger( 2848): id=14 Removed Uoast (8/9)
,I/SurfaceFlinger( 2848): id=14 Removed Uoast (-2/9)
,D/PowerManagerService( 3509): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3509) eventTime = 234593
,D/PowerManagerService( 3509): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3509 (0x0)
D/PowerManagerService( 3509): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3509, ws=WorkSource{10060}) (elapsedTime=3471)
,I/GAV4    (12419): Thread[GAThread,5,main]: No campaign data found.
,D/AndroidRuntime(12654): 
D/AndroidRuntime(12654): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(12654): CheckJNI is OFF
,D/AndroidRuntime(12654): readGMSProperty: start
D/AndroidRuntime(12654): readGMSProperty: already setted!!
,D/AndroidRuntime(12654): readGMSProperty: end
D/AndroidRuntime(12654): addProductProperty: start
,E/AffinityControl(12654): AffinityControl: registerfunction enter
,D/AndroidRuntime(12654): Calling main entry com.android.commands.pm.Pm
,D/PackageManager( 3509): START PACKAGE DELETE: observer{558642244}
D/PackageManager( 3509): pkg{<packageName>}
D/PackageManager( 3509): user{0}
D/PackageManager( 3509): caller{2000}
D/PackageManager( 3509): flags{3}
D/PersonaManagerService( 3509): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService( 3509): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3509): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3509): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3509): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3509): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 3509): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 3509): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 3509): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3509): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 3509): !@killApplicatoin: 10623, uninstall pkg
,I/ActivityManager( 3509): Force stopping com.test.thalitest appid=10623 user=-1: uninstall pkg
I/ActivityManager( 3509): Killing 12035:com.test.thalitest/u0a623 (adj 0): stop com.test.thalitest
,I/ActivityManager( 3509):   Force finishing activity ActivityRecord{1e8cb90f u0 com.test.thalitest/.MainActivity t26}
,W/ActivityManager( 3509): mDVFSHelper.acquire()
,D/BatteryService( 3509): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3509): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3509): online:4, current avg:-257, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:77
D/BatteryService( 3509): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3509): stay LED for fully charged
,W/PackageSettings( 3509): Skipping PackageSetting{9f8c2a2 com.example.hello/10563} due to missing metadata
,I/WindowState( 3509): WIN DEATH: Window{126c3ccd u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 3509): Client connection lost with reason: 4
,I/SurfaceFlinger( 2848): id=13 Removed NainActivit (5/8)
,I/SurfaceFlinger( 2848): id=13 Removed NainActivit (-2/8)
,D/PointerIcon( 3509): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3509): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3509): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3509): setHoveringSpenCustomIcon IconType is same.1
,I/ActivityManager( 3509): Force stopping com.test.thalitest appid=10623 user=0: pkg removed
,I/ActivityManager( 3509):   Force finishing activity ActivityRecord{1e8cb90f u0 com.test.thalitest/.MainActivity t26 f}
W/ActivityManager( 3509): Duplicate finish request for ActivityRecord{1e8cb90f u0 com.test.thalitest/.MainActivity t26 f}
,I/art     ( 9095): Explicit concurrent mark sweep GC freed 31661(1744KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.169ms total 44.371ms
,I/DBG_DM  ( 6306): [com.wssyncmldm.ui.XUIInstallConfirmActivity(456/onResume)] 
,I/art     ( 4766): Explicit concurrent mark sweep GC freed 25089(1441KB) AllocSpace objects, 3(48KB) LOS objects, 20% free, 31MB/39MB, paused 1.956ms total 66.330ms
,I/MotionRecognitionService( 3509): Plugged
I/MotionRecognitionService( 3509): setPowerConnected  = true
,I/art     ( 4039): Explicit concurrent mark sweep GC freed 36723(2MB) AllocSpace objects, 0(0B) LOS objects, 21% free, 28MB/36MB, paused 1.431ms total 45.600ms
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,I/DBG_DM  ( 6306): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 11
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5646): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5646): Disconnected process message: 10
,D/ResourcesManager( 3509): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/DBG_DM  ( 6306): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/DBG_DM  ( 6306): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6306): [com.wssyncmldm.ui.XUIInstallConfirmActivity(466/onResume)] Postpone Count : 11
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,I/InputReader( 3509): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,I/DBG_DM  ( 6306): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,E/SamsungIME( 4505): mOCRHelper is null
,I/DBG_DM  ( 6306): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,W/GeofencerStateMachine( 4629): Ignoring removeGeofence because network location is disabled.
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/LWLocationManager(11646): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(11646): getLastUiLocationId() : mLastUiLocationId = -100
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3509): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/talkback/talkback.apk
,E/Zygote  (12682): MountEmulatedStorage()
E/Zygote  (12682): v2
I/libpersona(12682): KNOX_SDCARD checking this for 10063
I/libpersona(12682): KNOX_SDCARD not a persona
,I/SELinux (12682): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12682): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3509): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=12682 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (12682): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourceType( 5356): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5356): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,I/DBG_DM  ( 6306): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/ResourcesManager(11646): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/TimaKeyStoreProvider(12682): TimaSignature is unavailable
,D/ActivityThread(12682): Added TimaKeyStore provider
,D/SecContentProvider2( 3509): uri = 14 selection = getSealedState
,D/SecContentProvider2( 3509): mCursor = null
,D/ApplicationPolicy( 3509): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3509): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,I/DBG_DM  ( 6306): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 11
,D/ResourcesManager(12682): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,I/DBG_DM  ( 6306): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,D/ResourcesManager(11646): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/VRSetupWizardStub/PackageIntentReceiver(12682): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(12682): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(12682): packagename:com.test.thalitest
D/ResourcesManager( 3509): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
I/DBG_DM  ( 6306): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,I/DBG_DM  ( 6306): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/Books/Books.apk
,I/DBG_DM  ( 6306): [llIIlIIlIllIllIlllII(376/llIIllllIIlllIIIIlll)] 
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/DBG_DM  ( 6306): [IIlIIIlllllIIlIIIlII(339/llllIlIIIllllIIlIlll)] No need to check encryption status
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/Drive/Drive.apk
,I/DBG_DM  ( 6306): [llIIlIIlIllIllIlllII(405/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
,D/ActivityManager( 3509): post active user change for 0
D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/KnoxTimeoutHandler( 3509): postActiveUserChange for user 0
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/Music2/Music2.apk
I/DBG_DM  ( 6306): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
,I/KLMS-2.4.521: (12277): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Feb 03 19:15:34 GMT+01:00 2016
,D/ResourcesManager(11646): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/EnterpriseDeviceManagerService( 3509): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3509): Admin package name: com.google.android.gms
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,I/SurfaceFlinger( 2848): id=15 createSurf (1440x2560),2 flag=404, YUIInstallC
,D/SecContentProvider2( 3509): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3509): mCursor = null
,D/StatusBarManagerService( 3509): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/StatusBarManagerService( 3509): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/PointerIcon( 3509): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,V/ActivityThread( 6306): updateVisibility : ActivityRecord{3066c548 token=android.os.BinderProxy@1f3bcee5 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
D/PointerIcon( 3509): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3509): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3509): setHoveringSpenCustomIcon IconType is same.1
,D/ResourcesManager(11646): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/RegisteredServicesCache( 3966): empty dynamic service
,W/Resources( 3509): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/KLMS-2.4.521: (12277): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 3509): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3509): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
I/art     ( 3509): Explicit concurrent mark sweep GC freed 28112(2MB) AllocSpace objects, 8(128KB) LOS objects, 24% free, 49MB/65MB, paused 5.909ms total 142.863ms
,D/ResourcesManager(11646): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (12277): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12277): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/Zygote  (12700): MountEmulatedStorage()
,E/Zygote  (12700): v2
I/libpersona(12700): KNOX_SDCARD checking this for 10106
,D/ResourcesManager(11646): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
I/libpersona(12700): KNOX_SDCARD not a persona
,I/SELinux (12700): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3509): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=12700 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,I/SELinux (12700): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12700): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/InputMethodManagerService( 3509): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/ResourcesManager(11646): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,I/KLMS-2.4.521: (12277): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,W/InputMethodManagerService( 3509): Got RemoteException sending setActive(false) notification to pid 12035 uid 10623
,I/KLMS-2.4.521: (12277): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,W/ContextImpl( 3509): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ResourcesManager(11646): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,I/KLMS-2.4.521: (12277): KLMSIntentService(): PACKAGE_REMOVED
,I/Timeline( 6306): Timeline: Activity_idle id: android.os.BinderProxy@1f3bcee5 time:235735
,I/KLMS-2.4.521: (12277): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.4.521: (12277): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,D/ResourcesManager(11646): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager( 3509): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/RCPManager(12372):  in createShortcut() for packageName: com.test.thalitest userId0
,D/RCPManagerService( 3509):  in createShortcut() for packageName: com.test.thalitest userId0
,D/RCPManagerService( 3509): queryAllProviders():  providerCallBack is not register for 0
,D/ResourcesManager(11646): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,D/TimaKeyStoreProvider(12700): TimaSignature is unavailable
,D/ActivityThread(12700): Added TimaKeyStore provider
,W/ResourcesManager(11646): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/RCPManagerService( 3509): PackageReceiver onReceive()
,I/HarmonyEASService( 3509): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,W/Resources( 3509): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/KnoxMUMContainerPolicy( 3509): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(11646): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/BackupManagerService( 3509): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 3509): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3509): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3509): uID is 10623
V/EnterpriseBillingPolicy( 3509): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3509): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 3509): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3509): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3509): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3509): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 3509): getBillingProfileForVpnEngine - end - null
,D/ResourcesManager(11646): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(12700): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11646): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(11646): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,E/Zygote  (12718): MountEmulatedStorage()
E/Zygote  (12718): v2
I/libpersona(12718): KNOX_SDCARD checking this for 10050
I/libpersona(12718): KNOX_SDCARD not a persona
,W/ResourcesManager(11646): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(11646): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11646): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11646): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
I/SELinux (12718): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3509): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=12718 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/SELinux (12718): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/PackageManager( 3509): delete codoeFile: 
E/SELinux (12718): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AASAUninstall( 3509):  com.test.thalitest not target!
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/PackageManager( 3509): result of delete: 1{558642244}
,D/KnoxTimeoutHandler( 3509): handleActiveUserChange for user 0
W/ActivityManager( 3509): mDVFSHelper.release()
I/Timeline( 3509): Timeline: Activity_windows_visible id: ActivityRecord{32156928 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t24} time:235824
,D/ResourcesManager(11646): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,W/Resources( 3509): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,D/AndroidRuntime(12654): Shutting down VM
D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/elm:14491(12700): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14491(12700): ELMEngine.ELMEngine( context ).
D/elm:14491(12700): MDMBridge.setEnterpriseBridge()
,D/ResourcesManager(11646): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,I/KLMS-2.4.521: (12277): KLMSIntentService(): listeningToPackageRemoved().END
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
,E/Zygote  (12733): MountEmulatedStorage()
,E/Zygote  (12733): v2
I/libpersona(12733): KNOX_SDCARD checking this for 10101
I/libpersona(12733): KNOX_SDCARD not a persona
,I/SELinux (12733): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12733): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12733): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3509): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=12733 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TaskPersister( 3509): removeObsoleteFile: deleting file=26_task.xml
,D/TaskPersister( 3509): removeObsoleteFile: deleting file=24_task.xml
,D/PackageManager( 3509): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/TimaKeyStoreProvider(12718): TimaSignature is unavailable
,D/ActivityThread(12718): Added TimaKeyStore provider
,D/ResourcesManager(11646): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/StatusBar( 3691): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 3691): isKioskContainerExistOnDevice
,D/PersonaManager( 3691): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3691): Icon Only
,I/StatusBar( 3691): Icon Only
,D/elm:14491(12700): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/PanelView( 3691): There is/are notification(s) 
,D/PanelView( 3691): There is/are notification(s) 
,I/KLMS-2.4.521: (12277): KLMSIntentService(): onDestroy()
D/elm:14491(12700): ElmAgentService : onCreate()
D/elm:14491(12700): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14491(12700): MainReceiver.listeningToPackageRemoved()
D/elm:14491(12700): MDMBridge.getInstance()
D/elm:14491(12700): MDMBridge.getAllLicenseInfoFromSDK()
,D/PersonaManager( 3691): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3691): Icon Only
,D/elm:14491(12700): MDMBridge.getAllLicenseInfoFromSDK()
,I/StatusBar( 3691): Icon Only
,D/PanelView( 3691): There is/are notification(s) 
,D/TimaKeyStoreProvider(12733): TimaSignature is unavailable
,D/ActivityThread(12733): Added TimaKeyStore provider
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(12718): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/ResourcesManager(12718): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(12718): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12718): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager(12718): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12718): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager(12718): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(12718): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12718): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Zygote  (12750): MountEmulatedStorage()
E/Zygote  (12750): v2
I/libpersona(12750): KNOX_SDCARD checking this for 10183
I/libpersona(12750): KNOX_SDCARD not a persona
,I/SELinux (12750): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12750): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12750): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(11646): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
I/ActivityManager( 3509): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=12750 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
,W/ResourceType( 3509): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3509): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources( 3509): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3509): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,W/Resources( 3509): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3509): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(11646): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/elm:14491(12700): ElmAgentService : onDestroy().
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources( 3509): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/TimaKeyStoreProvider(12750): TimaSignature is unavailable
,D/ResourcesManager(11646): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
W/Resources( 3509): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3509): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 8731(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.246ms total 28.169ms
D/PanelView( 3691): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,W/ResourcesManager( 3509): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3509): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3509): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ActivityThread(12750): Added TimaKeyStore provider
W/ResourcesManager( 3509): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
W/Resources( 3509): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3509): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(12733): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(11646): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 715us total 14.866ms
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources( 3509): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3509): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3509): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/Resources( 3509): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3509): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3509): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources( 3509): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3509): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 360us total 11.375ms
,W/Resources( 3509): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3509): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3509): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/ResourcesManager(11646): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,W/Resources( 3509): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3509): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/Resources( 3509): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/Zygote  (12766): MountEmulatedStorage()
E/Zygote  (12766): v2
I/libpersona(12766): KNOX_SDCARD checking this for 10019
I/libpersona(12766): KNOX_SDCARD not a persona
,I/SELinux (12766): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3509): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=12766 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,I/SELinux (12766): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12766): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3509): Killing 11663:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
,D/ResourcesManager(11646): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/TimaKeyStoreProvider(12766): TimaSignature is unavailable
,D/ActivityThread(12766): Added TimaKeyStore provider
,I/ActivityManager( 3509): Killing 11679:com.android.calendar/u0a164 (adj 13): bgCount ##31
,D/ResourcesManager(11646): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/UsbSettingsManager( 3509): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 3509): onPackageRemoved : com.test.thalitest
,D/ResourcesManager(11646): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
,D/ResourcesManager(12750): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
D/DocsApplication(12733): Installing DEX configuration.
,D/ResourcesManager(12766): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/DexInstaller(12733): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,I/PackageInfoHelper(12733): Provided clientMode=RELEASE, packageInfo=PackageInfo{10fe70c0 com.google.android.apps.docs}
,D/TAG     (12733): onCreate()
D/ResourcesManager(11646): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/PackageManager( 3509): findPreferredActivity: No PreferredActivities set
,D/CrossAppStateProvider(12733): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,D/com.sec.android.service.health.upgrade.UninstallReceiver(12766): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver(12766): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver(12766): onReceive() : package name is not s health. Return !!!
,D/LocationWidgetApplication(11646): getLastUiLocationId() : mLastUiLocationId = -100
,E/SQLiteLog(12750): (284) automatic index on shooting_modes(title_id)
,D/ResourcesManager(11646): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/NearbySource(12718): Nearby Source Create!
D/NearbyContext(12718): Nearby Context Create!
,D/ResourcesManager(11646): creating new AssetManager and set to /system/app/Books/Books.apk
,I/PCWCLIENTTRACE_PushUtil(12163): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(12163): sales region : global
I/PCWCLIENTTRACE_PushUtil(12163): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver(12163): [onReceive] - android.intent.action.PACKAGE_REMOVED
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12718): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource(12718): Samsung link source created
D/ResourcesManager(11646): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11646): creating new AssetManager and set to /system/app/Drive/Drive.apk
,E/Zygote  (12783): MountEmulatedStorage()
E/Zygote  (12783): v2
I/libpersona(12783): KNOX_SDCARD checking this for 10035
I/libpersona(12783): KNOX_SDCARD not a persona
,I/SELinux (12783): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager(11646): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,I/SELinux (12783): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3509): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=12783 uid=10035 gids={50035, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,E/SELinux (12783): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3509): Killing 10987:com.android.defcontainer/u0a5 (adj 13): bgCount ##31
,D/ResourcesManager(11646): creating new AssetManager and set to /system/app/FBInstagram_stub/FBInstagram_stub.apk
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11646): creating new AssetManager and set to /system/app/FBMessenger_stub/FBMessenger_stub.apk
,D/WifiDisplayAdapter( 3509): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ResourcesManager(11646): creating new AssetManager and set to /system/app/FBPagesManager_stub/FBPagesManager_stub.apk
,E/Zygote  (12799): MountEmulatedStorage()
E/Zygote  (12799): v2
I/libpersona(12799): KNOX_SDCARD checking this for 10190
I/libpersona(12799): KNOX_SDCARD not a persona
,I/ActivityManager( 3509): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=12799 uid=10190 gids={50190, 9997} abi=armeabi-v7a
,I/SELinux (12799): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12799): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12799): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(11646): creating new AssetManager and set to /system/app/Maps/Maps.apk
,D/TimaKeyStoreProvider(12783): TimaSignature is unavailable
,D/ActivityThread(12783): Added TimaKeyStore provider
,D/ResourcesManager(11646): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/TimaKeyStoreProvider(12799): TimaSignature is unavailable
,D/ActivityThread(12799): Added TimaKeyStore provider
,D/ContactProvider(12718): getAllContactInfoList Start
D/ResourcesManager(11646): creating new AssetManager and set to /system/app/PENUP/PENUP.apk
,I/ActivityManager( 3509): Killing 11804:com.android.vending/u0a31 (adj 13): bgCount ##31
,D/WifiDisplayAdapter( 3509): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ResourcesManager(12783): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/ResourcesManager(11646): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager(11646): creating new AssetManager and set to /system/app/SecCalculator2/SecCalculator2.apk
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11646): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
D/ResourcesManager(12799): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
,D/ResourcesManager(11646): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,E/Zygote  (12818): MountEmulatedStorage()
,E/Zygote  (12818): v2
I/libpersona(12818): KNOX_SDCARD checking this for 10052
I/libpersona(12818): KNOX_SDCARD not a persona
,I/ActivityManager( 3509): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=12818 uid=10052 gids={50052, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
D/UsbHostManager( 3509): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
D/UsbHostManager( 3509): displayNotification : [02h,02h,01h]
,D/UsbHostManager( 3509): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
D/UsbHostManager( 3509): displayNotification : [0ah,00h,00h]
,D/UsbHostManager( 3509): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
E/SharedPreferencesImpl(12718): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
D/UsbHostManager( 3509): displayNotification : [02h,0dh,00h]
,D/UsbHostManager( 3509): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3509): displayNotification : [0ah,00h,01h]
,D/ResourcesManager(11646): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,I/SELinux (12818): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/UsbHostManager( 3509): usbDeviceRemoved : /dev/bus/usb/001/003
E/UsbHostManager( 3509): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
,D/UsbSettingsManager( 3509): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
,D/UsbHostManager( 3509): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
D/UsbHostManager( 3509): displayNotification : [09h,00h,00h]
,I/SELinux (12818): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/MtpClient(12718): onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
D/MtpClient(12718): ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
I/TapandpayWidget:TanpandpayAppWidgetProvider(12799): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(12799): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
E/SELinux (12818): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3509): Killing 12525:com.sec.android.provider.badge/u0a82 (adj 13): bgCount ##31
,D/ResourcesManager(11646): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,I/TapandpayWidget:Utils(12799): Clear T&P info.
,D/TapandpayWidget:TanpandpayAppWidgetProvider(12799): Widget is not attached.
,I/ActivityManager( 3509): Killing 8890:com.android.settings/1000 (adj 13): bgCount ##31
,I/FeatureConfig(12783): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/ResourcesManager(12783): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
W/ResourcesManager(12783): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12783): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12783): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12783): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12783): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(12783): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/ResourcesManager(12783): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
D/PackageBroadcastService( 4766): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 4766): Clearing selected account for com.test.thalitest
,W/ResourcesManager(12783): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12783): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12783): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager(12783): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,D/TimaKeyStoreProvider(12818): TimaSignature is unavailable
,D/ActivityThread(12818): Added TimaKeyStore provider
,W/ResourcesManager(12783): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager(12783): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12783): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager(12783): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12783): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12783): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12783): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/UsbHostManager( 3509): usbDeviceRemoved : /dev/bus/usb/001/001
,E/UsbHostManager( 3509): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
,D/ResourcesManager(12783): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ContactProvider(12718): getAllContactInfoList End
,I/syncContacts(12718): thread: 1758, sync time = 215
,I/EventHub( 3509): Removing device '/dev/input/event10' due to inotify event
,D/ResourcesManager(12783): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,E/SQLiteLog( 4766): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 4766): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,W/ResourcesManager(12783): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12783): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12783): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12783): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,E/DriveAsyncService( 4766): disk I/O error (code 3850)
E/DriveAsyncService( 4766): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4766): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4766): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/DriveAsyncService( 4766): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4766): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4766): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/DriveAsyncService( 4766): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
E/DriveAsyncService( 4766): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 4766): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 4766): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 4766): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 4766): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 4766): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 4766): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 4766): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 4766): 	at java.lang.Thread.run(Thread.java:818)
,D/ResourcesManager(11646): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,D/ResourcesManager(12783): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,W/ResourcesManager(12783): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12783): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12783): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/WifiService( 3509): Client connection lost with reason: 4
,D/ResourcesManager(12783): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/ResourcesManager(12783): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12783): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12783): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12783): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12783): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(12783): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(12783): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12783): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/EventHub( 3509): Removing device '/dev/input/event7' due to inotify event
,D/ResourcesManager(12783): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
D/ResourcesManager(12818): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager(12783): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12783): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12783): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager(12818): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager(12818): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12818): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12818): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12818): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(12818): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/LocationSettingsChecker( 4766): Removing dialog suppression flag for package com.test.thalitest
,D/ResourcesManager(12783): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager(12783): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12783): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12783): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12783): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12783): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,I/EventHub( 3509): Removing device '/dev/input/event8' due to inotify event
,E/SQLiteLog( 4766): (28) failed to open "/data/data/com.google.android.gms/databases/metrics.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 4766): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 4766): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4766): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4766): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 4766): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 4766): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 4766): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 4766): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 4766): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 4766): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 4766): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 4766): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 4766): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 4766): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4766): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 4766): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 4766): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 4766): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 4766): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 4766): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4766): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4766): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 4766): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 4766): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 4766): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4766): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4766): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 4766): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 4766): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 4766): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 4766): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 4766): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 4766): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 4766): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 4766): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper( 4766): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 4766): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 4766): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 4766): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 4766): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 4766): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 4766): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 4766): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 4766): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4766): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 4766): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/SQLiteOpenHelper( 4766): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 4766): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 4766): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/ResourcesManager(12783): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ChimeraCfgMgr( 4766): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4766): Module APK com.google.android.play.games already loaded
,W/ResourcesManager(12783): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager(12783): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12783): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/SQLiteLog( 4766): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
,D/gH_CompatibleDatabase( 4766): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,E/AndroidRuntime( 4766): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 4766): Process: com.google.android.gms, PID: 4766
E/AndroidRuntime( 4766): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 4766): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4766): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
E/AndroidRuntime( 4766): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4766): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4766): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1623)
E/AndroidRuntime( 4766): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 4766): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 4766): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4766): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4766): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 4766): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/EventHub( 3509): Removing device '/dev/input/event9' due to inotify event
,D/ResourcesManager(12783): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,W/ResourcesManager(12783): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/ApplicationPolicy( 3509): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/Mms/MmsApp(12818): [start]    onCreate() consume time = 0.0
,D/ChimeraCfgMgr( 4766): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4766): Module APK com.google.android.play.games already loaded
,D/Mms/ArtClassLoader(12818): init before art
,D/Mms/ArtClassLoader(12818): init [DONE] art
,I/EventHub( 3509): Removing device '/dev/input/event11' due to inotify event
,E/SQLiteLog( 4766): (28) failed to open "/data/data/com.google.android.gms/databases/phenotype.db" with flag (131138) and mode_t (0) due to error (30)
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(12783): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,E/SQLiteDatabase( 4766): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 4766): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4766): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4766): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 4766): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 4766): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 4766): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 4766): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 4766): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 4766): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 4766): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 4766): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 4766): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 4766): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 4766): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4766): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4766): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 4766): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4766): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4766): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 4766): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/ResourcesManager(12783): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager(12783): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12783): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
E/SQLiteLog( 4766): (10) POSIX Error : 9 SQLite Error : 3850
W/ResourcesManager(12783): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/SQLiteLog( 4766): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/ResourcesManager(12783): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12783): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/Process ( 4766): Sending signal. PID: 4766 SIG: 9
,D/ResourcesManager(12783): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/PCWCLIENTTRACE_SYSTEMReceiver(12163): mConnectivityHandler : connected
,E/Zygote  (12851): MountEmulatedStorage()
E/Zygote  (12851): v2
,I/libpersona(12851): KNOX_SDCARD checking this for 10036
I/libpersona(12851): KNOX_SDCARD not a persona
,I/EventHub( 3509): Removing device '/dev/input/event12' due to inotify event
,I/ActivityManager( 3509): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=12851 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/SELinux (12851): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager(12783): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,I/ActivityManager( 3509): Killing 12138:com.facebook.appmanager/u0a110 (adj 13): bgCount ##31
,I/SELinux (12851): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,W/ResourcesManager(12783): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12783): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/SELinux (12851): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
W/ResourcesManager(12783): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,E/SQLiteLog(12733): (28) failed to open "/data/data/com.google.android.apps.docs/databases/ClientFlag.db" with flag (131138) and mode_t (0) due to error (30)
,D/Mms/TelephonyPermission(12818): start operation mode monitor
,E/SQLiteDatabase(12733): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase(12733): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12733): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12733): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12733): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12733): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12733): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12733): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12733): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12733): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12733): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12733): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12733): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12733): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12733): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(12733): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase(12733): 	at QF.provideClientFlag(ClientFlagsModule.java:71)
E/SQLiteDatabase(12733): 	at QH.a(GellyInjectorStore.java:215)
E/SQLiteDatabase(12733): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12733): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12733): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12733): 	at tQ.a(GellyInjectorStore.java:2039)
E/SQLiteDatabase(12733): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12733): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12733): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12733): 	at pG.a(GellyInjectorStore.java:478)
E/SQLiteDatabase(12733): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12733): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12733): 	at qD.a(GellyInjectorStore.java:118)
E/SQLiteDatabase(12733): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12733): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12733): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12733): 	at aEV.a(GellyInjectorStore.java:130)
E/SQLiteDatabase(12733): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12733): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12733): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12733): 	at aGH.a(GellyInjectorStore.java:227)
E/SQLiteDatabase(12733): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12733): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12733): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12733): 	at aGH.a(GellyInjectorStore.java:392)
E/SQLiteDatabase(12733): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12733): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12733): 	at aGH.a(GellyInjectorStore.java:369)
E/SQLiteDatabase(12733): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12733): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12733): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12733): 	at agN.a(GellyInjectorStore.java:799)
E/SQLiteDatabase(12733): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12733): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12733): 	at pG.a(GellyInjectorStore.java:146)
E/SQLiteDatabase(12733): 	at pG.a(GellyInjectorStore.java:392)
E/SQLiteDatabase(12733): 	at bsh.a(GellyMembersInjector.java:30)
E/SQLiteDatabase(12733): 	at brQ.a(GellyInjector.ja,va:119)
E/SQLiteDatabase(12733): 	at ajB.a(ScopedInjector.java:216)
E/SQLiteDatabase(12733): 	at com.google.android.apps.docs.DocsApplication.a(DocsApplication.java:235)
E/SQLiteDatabase(12733): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase(12733): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(12733): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(12733): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12733): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12733): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12733): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12733): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12733): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12733): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12733): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12733): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper(12733): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper(12733): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(12733): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(12733): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(12733): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(12733): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(12733): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(12733): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(12733): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(12733): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(12733): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(12733): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(12733): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(12733): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(12733): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(12733): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper(12733): 	at QF.provideClientFlag(ClientFlagsModule.java:71)
E/SQLiteOpenHelper(12733): 	at QH.a(GellyInjectorStore.java:215)
E/SQLiteOpenHelper(12733): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12733): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12733): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12733): 	at tQ.a(GellyInjectorStore.java:2039)
E/SQLiteOpenHelper(12733): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12733): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12733): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12733): 	at pG.a(GellyInjectorStore.java:478)
E/SQLiteOpenHelper(12733): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12733): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12733): 	at qD.a(GellyInjectorStore.java:118)
E/SQLiteOpenHelper(12733): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12733): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12733): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12733): 	at aEV.a(GellyInjectorStore.java:130)
E/SQLiteOpenHelper(12733): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12733): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12733): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12733): 	at aGH.a(GellyInjectorStore.java:227)
E/SQLiteOpenHelper(12733): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12733): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12733): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12733): 	at aGH.a(GellyInjectorStore.java:392)
E/SQLiteOpenHelper(12733): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12733): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12733): 	at aGH.a(GellyInjectorStore.java:369)
E/SQLiteOpenHelper(12733): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12733): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12733): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12733): 	at agN.a(GellyInjectorStore.java:799)
E/SQLiteOpenHelper(12733): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12733): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12733): 	at pG.a(GellyInjectorStore.java:146)
E/SQLiteOpenHelper(12733): 	at pG.a(GellyInjectorStore.java:392)
E/SQLiteOpenHelper(12733): 	at bsh.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper(12733): 	at brQ.a(GellyInjector.java:119)
E/SQLiteOpenHelper(12733): 	at ajB.a(ScopedInjector.java:216)
E/SQLiteOpenHelper(12733): 	at com.google.android.apps.docs.DocsApplication.a(DocsApplication.java:235)
E/SQLiteOpenHelper(12733): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper(12733): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(12733): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(12733): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(12733): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(12733): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(12733): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(12733): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(12733): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(12733): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(12733): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(12733): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper(12733): Opened ClientFlag.db in read-only mode
I/EventHub( 3509): Removing device '/dev/input/event13' due to inotify event
W/PCWCLIENTTRACE_AccountUtil(12163): [hasSamungAccount] - No Samsung Account
D/ResourcesManager(12783): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
E/SQLiteLog( 4629): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 4629): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,D/AndroidRuntime( 4629): Shutting down VM
E/AndroidRuntime( 4629): FATAL EXCEPTION: main
E/AndroidRuntime( 4629): Process: com.google.android.gms.persistent, PID: 4629
E/AndroidRuntime( 4629): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4629): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3001)
E/AndroidRuntime( 4629): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
E/AndroidRuntime( 4629): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
E/AndroidRuntime( 4629): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4629): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 4629): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime( 4629): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4629): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4629): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 4629): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime( 4629): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4629): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4629): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
E/AndroidRuntime( 4629): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4629): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4629): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1623)
E/AndroidRuntime( 4629): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 4629): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 4629): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 4629): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
E/AndroidRuntime( 4629): 	... 9 more
W/ResourcesManager(12783): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12783): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
I/EventHub( 3509): Removing device '/dev/input/event14' due to inotify event
E/lowmemorykiller( 2827): Error writing /proc/4766/oom_score_adj; errno=22
W/ResourcesManager(12783): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12783): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12783): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/SQLiteLog(12733): (28) failed to open "/data/data/com.google.android.apps.docs/databases/DocList.db" with flag (131138) and mode_t (0) due to error (30)
W/ResourcesManager(12783): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
E/SQLiteDatabase(12733): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase(12733): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12733): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12733): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12733): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12733): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12733): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12733): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12733): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12733): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12733): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12733): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12733): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12733): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12733): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12733): 	at aFu.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase(12733): 	at aFo.a(AbstractDatabaseInstance.java:457)
E/SQLiteDatabase(12733): 	at aFo.a(AbstractDatabaseInstance.java:453)
E/SQLiteDatabase(12733): 	at bjx.a(Suppliers.java:125)
E/SQLiteDatabase(12733): 	at aFp.run(AbstractDatabaseInstance.java:471)
E/AndroidRuntime(12733): FATAL EXCEPTION: Open database in background
E/AndroidRuntime(12733): Process: com.google.android.apps.docs, PID: 12733
E/AndroidRuntime(12733): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12733): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12733): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(12733): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(12733): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12733): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12733): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12733): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(12733): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(12733): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(12733): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(12733): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12733): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(12733): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(12733): 	at aFu.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime(12733): 	at aFo.a(AbstractDatabaseInstance.java:457)
E/AndroidRuntime(12733): 	at aFo.a(AbstractDatabaseInstance.java:453)
E/AndroidRuntime(12733): 	at bjx.a(Suppliers.java:125)
E/AndroidRuntime(12733): 	at aFp.run(AbstractDatabaseInstance.java:471)
E/DropBoxManagerService( 3509): Can't write: system_app_crash
E/DropBoxManagerService( 3509): java.io.FileNotFoundException: /data/system/dropbox/drop196.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3509): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3509): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3509): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3509): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3509): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3509): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3509): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3509): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3509): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3509): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3509): 	... 5 more
D/ConnectivityService( 3509): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@5d31f60)
D/ConnectivityService( 3509): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/ActivityManager( 3509): Process com.google.android.gms (pid 4766)(adj 5) has died(264,1190)
,D/TimaKeyStoreProvider(12851): TimaSignature is unavailable
D/ActivityThread(12851): Added TimaKeyStore provider
D/ResourcesManager(12818): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
E/ConnectivityService( 3509): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/ActivityManager( 3509): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 1000ms
W/ActivityManager( 3509): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 1000ms
W/ActivityManager( 3509): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
W/ResourcesManager(12818): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ActivityManager( 3509): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 1000ms
W/ActivityManager( 3509): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 11000ms
W/ActivityManager( 3509): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 10999ms
D/ResourcesManager(12783): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
W/ResourcesManager(12783): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager(12783): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
V/ApplicationPolicy( 3509): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.docs
V/ApplicationPolicy( 3509): isApplicationStateBlocked userId 0 pkgname com.google.android.gms.persistent
I/CSTORAGE(12163): ================================================
I/CSTORAGE(12163):  CSTORAGE_SKM_LIB v1.0.15
I/CSTORAGE(12163): ================================================
I/PCWCLIENTTRACE_SecurePreferencesJNI(12163): [GetString-S]
E/art     (12163): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
W/PCWCLIENTTRACE_SecurePreferencesJNI(12163): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI(12163): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil(12163): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(12163): sales region : global
I/PCWCLIENTTRACE_PushUtil(12163): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler(12163): [ensureRegistration] - No Samsung account
,E/SQLiteLog(12733): (28) failed to open "/data/data/com.google.android.apps.docs/databases/ClientFlag.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(12733): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase(12733): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12733): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12733): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12733): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12733): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12733): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12733): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12733): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12733): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12733): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12733): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12733): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12733): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12733): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(12733): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase(12733): 	at com.google.android.apps.docs.DocsApplication.i(DocsApplication.java:349)
E/SQLiteDatabase(12733): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:229)
E/SQLiteDatabase(12733): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(12733): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(12733): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12733): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12733): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12733): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12733): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12733): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12733): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12733): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12733): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper(12733): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper(12733): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(12733): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(12733): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(12733): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(12733): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(12733): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(12733): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(12733): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(12733): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(12733): 	at android.database.sql,ite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(12733): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(12733): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(12733): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(12733): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(12733): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper(12733): 	at com.google.android.apps.docs.DocsApplication.i(DocsApplication.java:349)
E/SQLiteOpenHelper(12733): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:229)
E/SQLiteOpenHelper(12733): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(12733): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(12733): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(12733): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(12733): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(12733): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(12733): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(12733): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(12733): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(12733): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(12733): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper(12733): Opened ClientFlag.db in read-only mode
W/GalaxyFinderApplication(12783): system/finder_cp/cpdata.xml file not found
,D/Mms/TelephonyPermission(12818): DefaultSmsApp is com.android.mms
E/DropBoxManagerService( 3509): Can't write: system_app_crash
E/DropBoxManagerService( 3509): java.io.FileNotFoundException: /data/system/dropbox/drop197.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3509): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3509): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3509): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3509): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3509): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3509): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3509): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3509): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3509): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3509): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3509): 	... 5 more
D/Mms/TelephonyPermission(12818): isDefault true
,E/DropBoxManagerService( 3509): Can't write: system_app_crash
E/DropBoxManagerService( 3509): java.io.FileNotFoundException: /data/system/dropbox/drop198.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3509): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3509): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3509): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3509): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3509): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3509): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3509): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3509): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3509): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3509): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3509): 	... 5 more
,D/Mms/MmsApp(12818): onCreate() com.android.mms
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(12851): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk

```
