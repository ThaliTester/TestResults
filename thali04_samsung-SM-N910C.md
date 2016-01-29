#### Test 5761781115ba656_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
D/SSRM:n  ( 3522): SIOP:: AP = 260, PST = 288, CUR = 62
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:62, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:86
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
D/BatteryService( 3522): stay LED for fully charged
--------- beginning of main
D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
V/HeadsetService( 5624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5624): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AndroidRuntime(11555): 
D/AndroidRuntime(11555): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11555): CheckJNI is OFF
D/AndroidRuntime(11555): readGMSProperty: start
D/AndroidRuntime(11555): readGMSProperty: already setted!!
D/AndroidRuntime(11555): readGMSProperty: end
D/AndroidRuntime(11555): addProductProperty: start
E/AffinityControl(11555): AffinityControl: registerfunction enter
D/AndroidRuntime(11555): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3522): inState():  stateMachine is null !!
I/PersonaManagerService( 3522): PersonaId don't exist
I/ActivityManager( 3522): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3522): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3522): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3522): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager( 3522): mDVFSHelper.acquire()
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/Zygote  (11573): MountEmulatedStorage()
I/libpersona(11573): KNOX_SDCARD checking this for 10607
E/Zygote  (11573): v2
I/libpersona(11573): KNOX_SDCARD not a persona
I/SELinux (11573): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3522): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=11573 uid=10607 gids={50607, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux (11573): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11573): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(11555): Shutting down VM
D/PointerIcon( 3522): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3522): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3522): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3522): setHoveringSpenCustomIcon IconType is same.1
I/art     ( 2881): Explicit concurrent mark sweep GC freed 8756(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.003ms total 28.514ms
D/TimaKeyStoreProvider(11573): TimaSignature is unavailable
D/ActivityThread(11573): Added TimaKeyStore provider
I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 757us total 18.982ms
I/SurfaceFlinger( 2853): id=11 Removed YUIInstallC (5/8)
I/SurfaceFlinger( 2853): id=11 Removed YUIInstallC (-2/8)
D/ResourcesManager(11573): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.803ms total 20.374ms
V/ActivityThread( 6230): updateVisibility : ActivityRecord{22e9d3c7 token=android.os.BinderProxy@1ab6abc8 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
I/WebViewFactory(11573): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(11573): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(11573): Loading: webviewchromium
I/LibraryLoader(11573): Time to load native libraries: 4 ms (timestamps 4835-4839)
I/LibraryLoader(11573): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(11573): Binding Chromium to main looper Looper (main, tid 1) {3125de16}
,I/LibraryLoader(11573): Expected native library version number "",actual native library version number ""
I/chromium(11573): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(11573): Initializing chromium process, renderers=0
,W/art     (11573): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(11573): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(11573): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(11573): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,W/chromium(11573): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(11573): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (11573): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(11573): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(11573): CordovaWebView is running on device made by: samsung
,W/art     (11573): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11573): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity(11573): performCreate Call secproduct feature valuefalse
D/Activity(11573): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(11573): Render dirty regions requested: true
,W/ActivityManager( 3522): Activity pause timeout for ActivityRecord{15fc12d1 u0 com.test.thalitest/.MainActivity t26}
,D/ActivityManager( 3522): post active user change for 0
D/KnoxTimeoutHandler( 3522): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3522): handleActiveUserChange for user 0
,I/SurfaceFlinger( 2853): id=14 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService( 3522): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3522): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3522): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3522): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3522): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3522): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer(11573): Initialized EGL, version 1.4
I/OpenGLRenderer(11573): HWUI protection enabled for context ,  &this =0xaf645060 ,&mEglDisplay = 1 , &mEglConfig = -1278840560 
,D/OpenGLRenderer(11573): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(11573): Enabling debug mode 0
,D/mali_winsys(11573): new_window_surface returns 0x3000,  [1440x2560]-format:1
,V/ActivityThread(11573): updateVisibility : ActivityRecord{266ff8c6 token=android.os.BinderProxy@217f44b5 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/InputMethodManagerService( 3522): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 3522): mDVFSHelper.release()
I/Timeline( 3522): Timeline: Activity_windows_visible id: ActivityRecord{15fc12d1 u0 com.test.thalitest/.MainActivity t26} time:115337
,W/IInputConnectionWrapper(11573): showStatusIcon on inactive InputConnection
,I/Timeline(11573): Timeline: Activity_idle id: android.os.BinderProxy@217f44b5 time:115349
,D/JsMessageQueue(11573): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium(11573): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11573): 
,D/jxcore_app_log(11573): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1358473472
,I/chromium(11573): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log(11573): Initializing JXcore engine
W/jxcore-log(11573): JXcore engine is ready
,E/auditd  ( 4619): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3522): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3522): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(11573): Starting JXcore engine
,W/jxcore-log(11573): Platform android
W/jxcore-log(11573): 
W/jxcore-log(11573): Process ARCH arm
W/jxcore-log(11573): 
,I/jxcore-log(11573): JXcore Cordova bridge is ready!
I/jxcore-log(11573): 
W/jxcore-log(11573): JXcore engine is started
,I/jxcore-log(11573): Toggling radios to true
I/jxcore-log(11573): 
,D/BluetoothAdapter(11573): enable()
,D/BluetoothAdapter(11573): enable(): BT is already enabled..!
,D/WifiService( 3522): New client listening to asynchronous messages
,I/WifiManager(11573): packageName : com.test.thalitest
,D/SecContentProvider( 3522): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3522): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3522): mCursor = null
,D/WifiService( 3522): setWifiEnabled: true pid=11573, uid=10607
E/WifiService( 3522): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3522): Permission Denial: getCurrentUser() from pid=11573, uid=10607 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 3522): Failed getting userId using ActivityManagerNative
W/WifiService( 3522): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=11573, uid=10607 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3522): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3522): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3522): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3522): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3522): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider( 3522): name = wifi_on
,I/WifiService( 3522): disconnect: pid=11573, uid=10607
,I/wpa_supplicant( 3825): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log(11573): Radios toggled
I/jxcore-log(11573): 
,I/jxcore-log(11573): My device name is: samsung-SM-N910C
I/jxcore-log(11573): 
,I/wpa_supplicant( 3825): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3825): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 3825): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3825): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine( 3522): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 3825): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3825): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3825): Disconnected - do not scan
I/wpa_supplicant( 3825): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine( 3522): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3522): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3522): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3522): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine( 3522): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3522): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3522): do suspend true
,D/WifiP2pService( 3522): InactiveState{ what=143375 }
,D/WifiP2pService( 3522): P2pEnabledState{ what=143375 }
,D/CommandListener( 2846): Clearing all IP addresses on wlan0
,E/Netd    ( 2846): ifc_reset_connections failed on iface wlan0 for address 192.168.1.124/24 (Unknown error -1)
,E/WifiStateMachine( 3522): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/ConnectivityService( 3522): updateNetworkInfo()
,D/ConnectivityService( 3522): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3522): updateNetworkInfo()
D/ConnectivityService( 3522): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
D/StatusBar.NetworkController( 3689): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3689): onWifiSignalChanged enabled=true enabledDesc:"NG700"
E/WifiConfigStore( 3522): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/WifiTrafficPoller( 3522): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 3689): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3689): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
E/WifiStateMachine( 3522): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 3825): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3825): P2P: Current p2p state = IDLE
I/wpa_supplicant( 3825): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 3825): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3825): First Scan Start
,I/wpa_supplicant( 3825): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiStateMachine( 3522): ConnectModeState: Network connection lost 
E/WifiStateMachine( 3522): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - processMessage - processMsg
E/WifiStateMachine( 3522): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3522): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3522): do suspend true
,I/Hs20UtilService( 4110): Starting #8
,I/Hs20UtilService( 4110): Message received 5007
,D/NearbySettings( 8739): MountReceiver.onReceive - Create HandlerThread
,D/NearbySettings( 8739): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings( 8739): MountReceiver.onReceive - Create mPrefHandler
,D/NearbySettings( 8739): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8739): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8739): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/WifiP2pService( 3522): InactiveState{ what=143375 }
,D/WifiP2pService( 3522): P2pEnabledState{ what=143375 }
,D/WifiService( 3522): New client listening to asynchronous messages
,I/NearbySettings( 8739): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8739): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8739): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8739): MountReceiver.mPrefHandler - 7002
,D/StatusBar.NetworkController( 3689): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3689): onWifiSignalChanged enabled=true enabledDesc:null
,D/CommandListener( 2846): Clearing all IP addresses on wlan0
,I/SignOutReceiver(11336): NETWORK_STATE_CHANGED_ACTION
D/ConnectivityService( 3522): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/EntConnectivity( 3522): Not allowed due to - mEnabled false
,D/ConnectivityManager.CallbackHandler( 3689): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3522): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 3522): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/WifiStateMachine( 3522): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/CSLegacyTypeTracker( 3522): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 3522): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 3522): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory( 3978): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 4757): CM callback handler got msg 524292
,D/WifiStateMachine( 3522): updateConfiguredNetworkExpiration - currTime: 1454056199401
D/WifiStateMachine( 3522): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
E/WifiStateMachine( 3522): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine( 3522): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine( 3522): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3522): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/EntConnectivity( 3522): Not allowed due to - mEnabled false
E/WifiStateMachine( 3522): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3522): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent( 3522): NetworkAgent: NetworkAgent channel lost
D/ConnectivityService( 3522): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
E/WifiStateMachine( 3522): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3522): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine( 3522): setDetailed state send new extra info"NG700"
D/SecContentProvider2( 3522): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3522): mCursor = null
,I/WifiTrafficPoller( 3522): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 3689): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3689): onWifiSignalChanged enabled=true enabledDesc:null
,D/Tethering( 3522): MasterInitialState.processMessage what=3
D/SmartBondingService( 3522): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService( 3522): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService( 3522): getSBEnabled() enabled =false
D/SmartBondingService( 3522): getSBEnabled() enabled =false
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
D/SmartBondingService( 3522): getSBEnabled() enabled =false
V/NetworkStats( 3522): updateIfacesLocked()
V/NetworkStats( 3522): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 3522): UpdateStatsForKnox
,D/StatusBar.NetworkController( 3689): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3689): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3689): updateDataNetType()
D/StatusBar.NetworkController( 3689): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3689): updateLTEICONDataNetType:0
,D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
D/SmartBondingService( 3522): getNetworkEnabled : wifi : true mobile : false
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
V/NetworkStats( 3522): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
,V/NetworkStats( 3522): performPollLocked() took 6ms
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 3689): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3689): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3689): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3689): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3689): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
D/SecContentProvider2( 3522): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3522): mCursor = null
,I/Hs20UtilService( 4110): Starting #9
I/Hs20UtilService( 4110): Message received 5007
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
D/NearbySettings( 8739): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8739): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8739): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 8739): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8739): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8739): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8739): MountReceiver.mPrefHandler - 7002
I/SignOutReceiver(11336): NETWORK_STATE_CHANGED_ACTION
,D/FileWriteThread_Telephony( 3978): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3978): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3978): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3978): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3978): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3978): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3978): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3978): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3978): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3978): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3978): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3978): FileWriteThread : threadType = 3
,D/ConnectivityService( 3522): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 3522): updateDataUsageMap
I/ApplicationPolicy( 3522): updateDataUsageMap  idList is null 
,D/SmartBondingService( 3522): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3522): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3522): getSBEnabled() enabled =false
D/SmartBondingService( 3522): getSBEnabled() enabled =false
D/SmartBondingService( 3522): getSBEnabled() enabled =false
D/GpsLocationProvider( 3522): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3522): getNetworkEnabled : wifi : true mobile : false
W/SLocation( 3522): No Active Data Connection
,I/DBG_DM  ( 6230): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/DBG_DM  ( 6230): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11662): MountEmulatedStorage()
E/Zygote  (11662): v2
I/libpersona(11662): KNOX_SDCARD checking this for 10110
I/libpersona(11662): KNOX_SDCARD not a persona
,I/SELinux (11662): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3522): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.iorg.vpn.cleanup.NetworkStateMonitor: pid=11662 uid=10110 gids={50110, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux (11662): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11662): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11662): TimaSignature is unavailable
,D/ActivityThread(11662): Added TimaKeyStore provider
,D/ResourcesManager(11662): creating new AssetManager and set to /data/app/com.facebook.appmanager-2/base.apk
,V/AlarmManager( 3522): waitForAlarm result :8
,D/ACRA    (11662): ACRA is enabled for com.facebook.appmanager, intializing...
,I/DexLibLoader(11662): not using cross-dex optimization: ART in use
,I/art     (11662): Thread[1,tid=11662,WaitingForJniOnLoad,Thread*=0xb4e08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/app/com.facebook.appmanager-2/lib/arm/libfbjni.so"
,V/DexLibLoader(11662): about to lock: /data/data/com.facebook.appmanager/mdex_lock
,V/DexLibLoader(11662): locking /data/data/com.facebook.appmanager/mdex_lock took 0 ms
V/DexLibLoader(11662): Secondary program dex metadata: classes2.dex 29f80981f469a774a4884b3db2df17e0be227159 secondary.dex01.Canary
,D/DexLibLoader(11662): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex" is valid
D/DexLibLoader(11662): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex_opt" is valid
,W/art     (11662): Attempt to remove local handle scope entry from IRT, ignoring
,D/DexLibLoader(11662): loading pre-built fallback odex files
V/MultiDexClassLoader(11662): installing MultiDexClassLoader before application classloader
,D/DexLibLoader(11662): released odex store lock
D/DexLibLoader(11662): DexLibLoader.loadAll took 18 ms
,W/ca      (11662): Verify
,W/LightSharedPreferencesImpl(11662): Failed to load preference file from Disk!
W/LightSharedPreferencesImpl(11662): java.io.FileNotFoundException: /data/data/com.facebook.appmanager/app_light_prefs/com.facebook.appmanager/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11662): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/LightSharedPreferencesImpl(11662): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/LightSharedPreferencesImpl(11662): 	at com.facebook.crudolib.b.k.a(LightSharedPreferencesStorage.java:56)
W/LightSharedPreferencesImpl(11662): 	at com.facebook.crudolib.b.g.run(LightSharedPreferencesImpl.java:61)
W/LightSharedPreferencesImpl(11662): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/LightSharedPreferencesImpl(11662): 	at com.facebook.common.executors.dj.run(WrappingExecutorService.java:77)
W/LightSharedPreferencesImpl(11662): 	at com.facebook.common.executors.u.run(DefaultConstrainedListeningExecutorService.java:327)
W/LightSharedPreferencesImpl(11662): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/LightSharedPreferencesImpl(11662): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/LightSharedPreferencesImpl(11662): 	at com.facebook.common.executors.cc.run(NamedThreadFactory.java:42)
W/LightSharedPreferencesImpl(11662): 	at java.lang.Thread.run(Thread.java:818)
W/LightSharedPreferencesImpl(11662): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11662): 	at libcore.io.Posix.open(Native Method)
W/LightSharedPreferencesImpl(11662): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/LightSharedPreferencesImpl(11662): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/LightSharedPreferencesImpl(11662): 	... 10 more
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11687): MountEmulatedStorage()
I/libpersona(11687): KNOX_SDCARD checking this for 1000
E/Zygote  (11687): v2
I/libpersona(11687): KNOX_SDCARD not a persona
,I/SELinux (11687): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11687): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11687): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=11687 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3522): Killing 10870:com.android.mms/u0a52 (adj 15): bgCount ##31
W/appmanager(:<default>):b(11662): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
E/lowmemorykiller( 2828): Error writing /proc/10870/oom_score_adj; errno=22
,W/appmanager(:<default>):b(11662): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/TimaKeyStoreProvider(11687): TimaSignature is unavailable
,D/ActivityThread(11687): Added TimaKeyStore provider
,D/ResourcesManager(11687): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/PCWCLIENTTRACE_LOG(11687): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(11687): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(11687): new DMDBOpenHelper instance
,D/CountryDetector( 3522): No listener is left
,W/appmanager(:<default>):QuickExperimentControllerImpl(11662): Exposure of experiment com.facebook.common.network.l@25b9642f occurred when no user was logged in
,W/BroadcastQueue( 3522): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{18fe9d9c u0 ReceiverList{156090f 11662 com.facebook.appmanager/10110/u0 remote:3b90fe6e}}
I/PCWCLIENTTRACE_PushUtil(11687): SPPPushClient is installed : true
W/BroadcastQueue( 3522): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{18fe9d9c u0 ReceiverList{156090f 11662 com.facebook.appmanager/10110/u0 remote:3b90fe6e}}
I/PCWCLIENTTRACE_PushUtil(11687): sales region : global
I/PCWCLIENTTRACE_PushUtil(11687): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11687): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver(11687): noConnectivity : true
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11711): MountEmulatedStorage()
E/Zygote  (11711): v2
I/libpersona(11711): KNOX_SDCARD checking this for 10135
I/libpersona(11711): KNOX_SDCARD not a persona
,I/SELinux (11711): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11711): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11711): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=11711 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3522): Killing 10937:com.sec.android.app.samsungapps/u0a13 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(11711): TimaSignature is unavailable
,D/ActivityThread(11711): Added TimaKeyStore provider
,D/ResourcesManager(11711): creating new AssetManager and set to /system/app/Music2/Music2.apk
,W/BroadcastQueue( 3522): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{360a2fa0 u0 ReceiverList{12d450a3 11662 com.facebook.appmanager/10110/u0 remote:200c17d2}}
,I/MusicStore(11711): Database version: 104
,D/ResourcesManager(11711): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11711): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11711): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (11711): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(11711): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  (11711): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3b609e0a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller(11711): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(11711): GMSCore installation verified
,I/ConfigStore(11711): Config Database version: 1
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11662): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11662): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11711): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/appmanager(:<default>):QuickExperimentControllerImpl(11662): Exposure of experiment com.facebook.imagepipeline.a.g@1f3b2745 occurred when no user was logged in
,W/appmanager(:<default>):QuickExperimentControllerImpl(11662): Exposure of experiment com.facebook.imagepipeline.a.d@2b335a66 occurred when no user was logged in
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/ContextImpl(11711): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
W/ContextImpl(11711): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter( 3522): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/wpa_supplicant( 3825): nl80211: Received scan results (4 BSSes)
,I/wpa_supplicant( 3825): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3825): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3825): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 3825): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3522): [1,454,056,200,458 ms] noteScanEnd no scan source
,I/art     (11662): Explicit concurrent mark sweep GC freed 42577(2MB) AllocSpace objects, 6(96KB) LOS objects, 22% free, 27MB/35MB, paused 796us total 24.082ms
,W/appmanager(:<default>):m(11662): No feature status reporters found; is this dead code?
,E/WifiStateMachine( 3522): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@36359cb9 sup_state=SCANNING debouncing=false
,E/WifiStateMachine( 3522): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3522): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3522): setDetailed state send new extra info
,D/WifiDisplayAdapter( 3522): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/SecContentProvider2( 3522): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3522): mCursor = null
,I/AudioService( 3522): getStreamVolume 3 index 0
,I/MediaRouter(11711): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11747): MountEmulatedStorage()
I/libpersona(11747): KNOX_SDCARD checking this for 10002
E/Zygote  (11747): v2
I/libpersona(11747): KNOX_SDCARD not a persona
I/SELinux (11747): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11747): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11747): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=11747 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/WifiDisplayAdapter( 3522): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/NetworkMonitor(11711): type=WIFI subType= reason=null isConnected=false
,I/ActivityManager( 3522): Killing 10190:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(11747): TimaSignature is unavailable
,D/ActivityThread(11747): Added TimaKeyStore provider
,D/ResourcesManager(11747): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager( 3522): Killing 9784:com.sec.android.app.shealth/u0a36 (adj 15): bgCount ##31
,E/lowmemorykiller( 2828): Error writing /proc/9784/oom_score_adj; errno=22
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11766): MountEmulatedStorage()
I/libpersona(11766): KNOX_SDCARD checking this for 1000
E/Zygote  (11766): v2
I/libpersona(11766): KNOX_SDCARD not a persona
,I/SELinux (11766): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11766): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11766): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=11766 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11766): TimaSignature is unavailable
,D/ActivityThread(11766): Added TimaKeyStore provider
,D/ResourcesManager(11766): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT(11766): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/wpa_supplicant( 3825): wlan0: State: ASSOCIATING -> ASSOCIATED
,I/wpa_supplicant( 3825): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
E/WifiStateMachine( 3522): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3522): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3522): setDetailed state send new extra info"NG700"
I/wpa_supplicant( 3825): Associated with C0.AA.48
,I/wpa_supplicant( 3825): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 3825): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,D/SecContentProvider2( 3522): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3522): mCursor = null
,E/WifiStateMachine( 3522): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3522): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,D/SecContentProvider2( 3522): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3522): mCursor = null
,I/wpa_supplicant( 3825): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 3825): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 3825): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3522): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3522): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,I/wpa_supplicant( 3825): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3825): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 3825): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 3825): Blacklist: Clear (temp) 
I/wpa_supplicant( 3825): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3522): Network connection established
,D/WifiNative-HAL( 3522): callSECApiVoid - ID [50]
,E/WifiStateMachine( 3522): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine( 3522): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService( 3522): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine( 3522): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3522): L2ConnectedState "NG700" nid=0
E/WifiConfigStore( 3522): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService( 3522): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 3522): updateNetworkInfo()
D/ConnectivityService( 3522): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/StatusBar.NetworkController( 3689): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3689): onWifiSignalChanged enabled=true enabledDesc:null
,I/DIAGMON_AGENT(11766): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,E/WifiStateMachine( 3522): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine( 3522): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3522): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3522): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/DIAGMON_AGENT(11766): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT(11766): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(11766): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/CommandListener( 2846): Setting iface cfg
E/WifiStateMachine( 3522): Start Dhcp Watchdog 2
,D/SecContentProvider2( 3522): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3522): mCursor = null
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11783): MountEmulatedStorage()
E/Zygote  (11783): v2
I/libpersona(11783): KNOX_SDCARD checking this for 10012
I/libpersona(11783): KNOX_SDCARD not a persona
,I/SELinux (11783): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11783): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11783): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=11783 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11783): TimaSignature is unavailable
,D/ActivityThread(11783): Added TimaKeyStore provider
,D/ResourcesManager(11783): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,E/WifiStateMachine( 3522): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3522): do suspend false
,D/WifiP2pService( 3522): InactiveState{ what=143375 }
D/WifiP2pService( 3522): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 3522): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine( 3522): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
D/SecContentProvider2( 3522): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3522): mCursor = null
,I/ActivityManager( 3522): Killing 10953:com.sec.android.app.myfiles/u0a53 (adj 15): bgCount ##31
,I/FOTA_Client(11783): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(11783): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(11783): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11799): MountEmulatedStorage()
I/libpersona(11799): KNOX_SDCARD checking this for 10021
E/Zygote  (11799): v2
I/libpersona(11799): KNOX_SDCARD not a persona
,I/SELinux (11799): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11799): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11799): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=11799 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
I/ActivityManager( 3522): Killing 10971:com.policydm/1000 (adj 15): bgCount ##31
,E/lowmemorykiller( 2828): Error writing /proc/10971/oom_score_adj; errno=22
,D/TimaKeyStoreProvider(11799): TimaSignature is unavailable
,D/ActivityThread(11799): Added TimaKeyStore provider
,D/ResourcesManager(11799): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.521: (11799): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jan 29 09:30:00 GMT+01:00 2016
,I/KLMS-2.4.521: (11799): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (11799): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11799): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
I/KLMS-2.4.521: (11799): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (11799): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (11799): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (11799): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,E/Zygote  (11815): MountEmulatedStorage()
I/libpersona(11815): KNOX_SDCARD checking this for 10038
E/Zygote  (11815): v2
I/libpersona(11815): KNOX_SDCARD not a persona
,I/KLMS-2.4.521: (11799): StateImplV2(): networkChangeListener().END
I/SELinux (11815): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11815): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11815): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=11815 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
I/KLMS-2.4.521: (11799): KLMSIntentService(): onDestroy()
,D/TimaKeyStoreProvider(11815): TimaSignature is unavailable
,D/ActivityThread(11815): Added TimaKeyStore provider
I/ActivityManager( 3522): Killing 10986:com.sec.android.provider.badge/u0a82 (adj 15): bgCount ##31
E/lowmemorykiller( 2828): Error writing /proc/10986/oom_score_adj; errno=22
,D/ResourcesManager(11815): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT(11815): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11830): MountEmulatedStorage()
I/libpersona(11830): KNOX_SDCARD checking this for 1000
E/Zygote  (11830): v2
I/libpersona(11830): KNOX_SDCARD not a persona
,I/SELinux (11830): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11830): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11830): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=11830 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3522): Killing 10836:com.google.android.apps.docs/u0a101 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(11830): TimaSignature is unavailable
,D/ActivityThread(11830): Added TimaKeyStore provider
,D/ResourcesManager(11830): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,E/dhcpcd  (11849): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (11849): version 5.5.6 starting
,E/dhcpcd  (11849): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,E/SPPClientService(11049): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,E/SPPClientService(11049): [[SystemStateMonitorService]] No Active Internet
,I/SA      (11167): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11167): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      (11167): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (11167): [SLFUCHKMGR] constructor called
,I/SA      (11167): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11167): [OR] == isSIMCardReady false ==
,I/SA      (11167): [SCU] == networkStateCheck == false
I/SA      (11167): [OR] onReceive END
,I/dhcpcd  (11849): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (11849): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (11849): if(wlan0) info get Success. (MAC : C0.AA.48)
I/ActivityManager( 3522): Killing 11032:com.sec.android.app.soundalive/u0a59 (adj 15): bgCount ##31
I/dhcpcd  (11849): bssid match
I/dhcpcd  (11849): wlan0: rebinding lease of 192.168.1.124
,V/DownloadManager( 3714): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11860): MountEmulatedStorage()
I/libpersona(11860): KNOX_SDCARD checking this for 10067
E/Zygote  (11860): v2
I/libpersona(11860): KNOX_SDCARD not a persona
,I/SELinux (11860): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11860): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11860): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=11860 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11860): TimaSignature is unavailable
,D/ActivityThread(11860): Added TimaKeyStore provider
,D/ResourcesManager(11860): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/sCloudBackupApp(11860): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(11860): Other Intent
,I/ActivityManager( 3522): Killing 11064:com.wsomacp/u0a28 (adj 15): bgCount ##31
,D/accuweather( 5192): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3774): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,D/accuweather( 5192): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5192): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5192): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
,D/accuweather( 5192): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5192): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5192): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11876): MountEmulatedStorage()
E/Zygote  (11876): v2
I/libpersona(11876): KNOX_SDCARD checking this for 1000
I/libpersona(11876): KNOX_SDCARD not a persona
,I/SELinux (11876): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11876): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11876): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=11876 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 8755(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 604us total 11.845ms
,D/TimaKeyStoreProvider(11876): TimaSignature is unavailable
,D/ActivityThread(11876): Added TimaKeyStore provider
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 601us total 8.640ms
,D/ResourcesManager(11876): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(11876): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 364us total 8.527ms
,I/KnoxUsageLogPro(11876): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro(11876): premStatus:2
,I/KnoxUsageLogPro(11876): isEulaShown : false
I/KnoxUsageLogPro(11876): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11891): MountEmulatedStorage()
E/Zygote  (11891): v2
I/libpersona(11891): KNOX_SDCARD checking this for 10090
I/libpersona(11891): KNOX_SDCARD not a persona
,I/SELinux (11891): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11891): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3522): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=11891 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (11891): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Killing 11086:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(11891): TimaSignature is unavailable
,D/ActivityThread(11891): Added TimaKeyStore provider
,D/ResourcesManager(11891): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11907): MountEmulatedStorage()
I/libpersona(11907): KNOX_SDCARD checking this for 10127
E/Zygote  (11907): v2
I/libpersona(11907): KNOX_SDCARD not a persona
I/SELinux (11907): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11907): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11907): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=11907 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3522): Killing 11105:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
,E/lowmemorykiller( 2828): Error writing /proc/11105/oom_score_adj; errno=22
,D/TimaKeyStoreProvider(11907): TimaSignature is unavailable
,D/ActivityThread(11907): Added TimaKeyStore provider
,D/ResourcesManager(11907): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,D/KeyguardWallpaperUpdator(11907): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(11907): cancelUpdateCategory
D/KeyguardWallpaperUpdator(11907): stopCheckCategoryVersion
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11924): MountEmulatedStorage()
I/libpersona(11924): KNOX_SDCARD checking this for 10136
E/Zygote  (11924): v2
I/libpersona(11924): KNOX_SDCARD not a persona
,I/SELinux (11924): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11924): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11924): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=11924 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3522): Killing 11014:com.sec.android.automotive.drivelink/u0a102 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(11924): TimaSignature is unavailable
,D/ActivityThread(11924): Added TimaKeyStore provider
,D/ResourcesManager(11924): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/dhcpcd  (11849): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11924): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl(11924): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11924): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11924): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/dhcpcd  (11849): wlan0: leased 192.168.1.124 for 86400 seconds
,E/WifiStateMachine( 3522): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3522): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,I/WebViewFactory(11924): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(11924): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(11924): Loading: webviewchromium
,I/LibraryLoader(11924): Time to load native libraries: 3 ms (timestamps 8727-8730)
I/LibraryLoader(11924): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(11924): Binding Chromium to main looper Looper (main, tid 1) {367290d6}
,I/LibraryLoader(11924): Expected native library version number "",actual native library version number ""
,I/chromium(11924): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(11924): Initializing chromium process, renderers=0
,W/art     (11924): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(11924): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(11924): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium(11924): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,W/AudioManagerAndroid(11924): Requires BLUETOOTH permission
,I/NSApplication(11924): Starting up...
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/WifiStateMachine( 3522): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine( 3522): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  ( 3522): do suspend true
E/Zygote  (12013): MountEmulatedStorage()
I/libpersona(12013): KNOX_SDCARD checking this for 10150
E/Zygote  (12013): v2
I/libpersona(12013): KNOX_SDCARD not a persona
,I/SELinux (12013): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12013): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12013): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=12013 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager( 3522): Killing 11122:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
,E/lowmemorykiller( 2828): Error writing /proc/11122/oom_score_adj; errno=22
,D/WifiP2pService( 3522): InactiveState{ what=143375 }
D/WifiP2pService( 3522): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 3522): WifiStateMachine DHCP successful
,E/WifiStateMachine( 3522): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3522): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine( 3522): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3522): Not connected state, yet.
E/WifiStateMachine( 3522): VerifyingLinkState enter
,D/StatusBar.NetworkController( 3689): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3689): onWifiSignalChanged enabled=true enabledDesc:null
D/WifiStateMachine( 3522): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
,D/WifiStateMachine( 3522): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3522): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3522): callSECApiInt - ID [210]
E/WifiStateMachine( 3522): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService( 3522): updateNetworkInfo()
,D/ConnectivityService( 3522): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 3522): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 3522): updateDnsLinkProperty: enter
D/WifiWatchdogStateMachine.DnsPinger( 3522): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 3522): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 3522): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3522): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/TimaKeyStoreProvider(12013): TimaSignature is unavailable
,D/ActivityThread(12013): Added TimaKeyStore provider
,D/StatusBar.NetworkController( 3689): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3689): onWifiSignalChanged enabled=true enabledDesc:null
,D/ResourcesManager(12013): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,D/ConnectivityService( 3522): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService( 3522): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
W/ResourcesManager(12013): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12013): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12013): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ConnectivityService( 3522): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
E/WifiStateMachine( 3522): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine( 3522): Now, connected state.
E/WifiStateMachine( 3522): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/WifiStateMachine( 3522): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
E/ConnectivityService( 3522): Unexpected mtu value: 0, wlan0
,I/WifiTrafficPoller( 3522): evaluateTrafficStatsPolling
,V/        ( 2846): QcRouteController
,D/StatusBar.NetworkController( 3689): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3689): onWifiSignalChanged enabled=true enabledDesc:null
V/        ( 2846): QcRouteController
,E/WifiStateMachine( 3522): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/WifiStateMachine( 3522): ConnectedState Enter  mScreenOn=false scanperiod=20000
,I/WifiTrafficPoller( 3522): evaluateTrafficStatsPolling
,D/WifiNative-HAL( 3522): callSECApiVoid - ID [212]
D/QuickConnect(12013): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/WifiStateMachine( 3522): REQUEST_POWER_SAVE_ON
,D/StatusBar.NetworkController( 3689): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3689): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
,V/        ( 2846): QcRouteController
,D/StatusBar.NetworkController( 3689): applyOpen
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
,I/QuickConnect(12013): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect(12013): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,V/        ( 2846): QcRouteController
,E/Zygote  (12039): MountEmulatedStorage()
I/libpersona(12039): KNOX_SDCARD checking this for 10178
E/Zygote  (12039): v2
I/libpersona(12039): KNOX_SDCARD not a persona
,I/SELinux (12039): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
V/        ( 2846): QcRouteController
,I/SELinux (12039): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12039): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=12039 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
I/ActivityManager( 3522): Killing 10128:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
,V/        ( 2846): QcRouteController
,V/        ( 2846): QcRouteController
,V/        ( 2846): QcRouteController
,D/TimaKeyStoreProvider(12039): TimaSignature is unavailable
,D/ActivityThread(12039): Added TimaKeyStore provider
,D/ConnectivityService( 3522): Setting Dns servers for network 503 to [/192.168.1.1]
,D/ConnectivityService( 3522): LTETest block dns file not exists
,D/ConnectivityService( 3522): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 3522): updateNetworkInfo()
D/ConnectivityService( 3522): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3522): updateNetworkInfo()
D/ConnectivityService( 3522): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3522): rematching NetworkAgentInfo [WIFI () - 503]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3522): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3522): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3522): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3522): Checking http://clients3.google.com/generate_204 on "NG700"
D/ResourcesManager(12039): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(12039): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager(12039): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12039): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12039): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12039): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12039): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/JavaBinder( 3522): !!! FAILED BINDER TRANSACTION !!!
I/System.out( 3522): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 503 for uid 1000
,D/ConnectivityService( 3522):    accepting network in place of null
,D/TelephonyNetworkFactory( 3978): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker( 3522): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 3522): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 3522): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,W/ActivityManager( 3522): Failed to clear dns cache for: com.android.providers.calendar
,D/ConnectivityService( 3522): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService( 3522): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/Tethering( 3522): MasterInitialState.processMessage what=3
D/ConnectivityManager.CallbackHandler( 3689): CM callback handler got msg 524290
D/SmartBondingService( 3522): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService( 3522): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3522): getSBEnabled() enabled =false
D/SmartBondingService( 3522): getSBEnabled() enabled =false
D/SmartBondingService( 3522): getSBEnabled() enabled =false
D/ConnectivityManager.CallbackHandler( 4757): CM callback handler got msg 524290
,D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
V/NetworkStats( 3522): updateIfacesLocked()
V/NetworkStats( 3522): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 3522): UpdateStatsForKnox
,D/StatusBar.NetworkController( 3689): getUpdateDataNetType(): 0
D/SmartBondingService( 3522): getNetworkEnabled : wifi : true mobile : false
D/StatusBar.NetworkController( 3689): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3689): updateDataNetType()
D/StatusBar.NetworkController( 3689): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3689): updateLTEICONDataNetType:0
,D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
V/NetworkStats( 3522): performPollLocked() took 3ms
,D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
V/NetworkStats( 3522): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 3689): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3689): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3689): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 3689): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3689): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
,D/RCPManagerService( 3522): exchangeData() failure , invalid userId
,D/RCPManagerService( 3522): exchangeData() failure , invalid userId
,D/RCPManagerService( 3522): exchangeData() failure , invalid userId
,D/RCPManagerService( 3522): exchangeData() failure , invalid userId
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 3522): exchangeData() failure , invalid userId
,E/Zygote  (12070): MountEmulatedStorage()
I/libpersona(12070): KNOX_SDCARD checking this for 10082
E/Zygote  (12070): v2
I/libpersona(12070): KNOX_SDCARD not a persona
I/SELinux (12070): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/RCPManagerService( 3522): exchangeData() failure , invalid userId
I/SELinux (12070): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12070): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=12070 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12083): MountEmulatedStorage()
E/Zygote  (12083): v2
I/libpersona(12083): KNOX_SDCARD checking this for 1000
I/libpersona(12083): KNOX_SDCARD not a persona
,I/SELinux (12083): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12083): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/TimaKeyStoreProvider(12070): TimaSignature is unavailable
E/SELinux (12083): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=12083 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/ActivityThread(12070): Added TimaKeyStore provider
,I/ActivityManager( 3522): Killing 11183:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
,I/ActivityManager( 3522): Killing 11201:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12083): TimaSignature is unavailable
,D/ActivityThread(12083): Added TimaKeyStore provider
,I/art     ( 3522): Explicit concurrent mark sweep GC freed 77831(4MB) AllocSpace objects, 9(144KB) LOS objects, 24% free, 49MB/65MB, paused 1.243ms total 88.118ms
,D/ResourcesManager(12070): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/ResourcesManager(12083): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
W/ActivityManager( 3522): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/BadgeProvider(12070): onCreate
,D/BadgeProvider(12070): DatabaseHelper
,I/ActivityManager( 3522): Killing 11236:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,D/BadgeProvider(12070): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider(12070): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12070): sendNotify, [notify] : null
D/BadgeProvider(12070): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12070): update, [BadgeCount] : badgecount=0
D/BadgeProvider(12070): update, [UpdateCount] : 1
,D/Launcher.Model( 3998): reloadBadges entered.
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12103): MountEmulatedStorage()
E/Zygote  (12103): v2
I/libpersona(12103): KNOX_SDCARD checking this for 10013
I/libpersona(12103): KNOX_SDCARD not a persona
,I/SELinux (12103): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12103): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12103): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=12103 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12103): TimaSignature is unavailable
,D/ActivityThread(12103): Added TimaKeyStore provider
,D/ResourcesManager(12103): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,D/WaitQueueForNetworkActivate(12103): notifyNetworkActivated
,W/ContextImpl(12103): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3522): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/hcjo    (12103): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12103): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12103): exit::IDLE
D/InitializeManagerStateMachine(12103): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12103): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12103): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12103): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12103): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12103): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12103): entry::SUCCESS
D/hcjo    (12103): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (12103): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12103): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine(12103): exit::SUCCESS
D/InitializeManagerStateMachine(12103): entry::IDLE
,I/ActivityManager( 3522): Killing 11251:com.samsung.helphub/1000 (adj 13): bgCount ##31
,I/Hs20UtilService( 4110): Starting #10
,I/Hs20UtilService( 4110): Message received 5007
,D/NearbySettings( 8739): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8739): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8739): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 8739): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8739): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8739): MountReceiver.onReceive - Keep current state
,I/SignOutReceiver(11336): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4110): Starting #11
,I/Hs20UtilService( 4110): Message received 5007
,D/NearbySettings( 8739): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8739): MountReceiver.onReceive - Keep current state
,I/SignOutReceiver(11336): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4110): Starting #12
,I/Hs20UtilService( 4110): Message received 5007
,D/NearbySettings( 8739): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8739): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8739): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 8739): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8739): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8739): MountReceiver.onReceive - Keep current state
,I/SignOutReceiver(11336): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4110): Starting #13
,I/Hs20UtilService( 4110): Message received 5007
,D/NearbySettings( 8739): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 8739): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine( 3522): callSECApi what=220
D/WifiStateMachine( 3522): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/SignOutReceiver(11336): NETWORK_STATE_CHANGED_ACTION
,I/SurfaceFlinger( 2853): id=15 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 3522): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3522
,D/mali_winsys( 3689): new_window_surface returns 0x3000,  [1120x201]-format:1
,D/ConnectivityService( 3522): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3522): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3522): SmartBondingReceiver: wifi is connected
D/SmartBondingService( 3522): SmartBondingReceiver: wifi ap is not changed
,D/SmartBondingService( 3522): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3522): getSBEnabled() enabled =false
D/SmartBondingService( 3522): getSBEnabled() enabled =false
D/SmartBondingService( 3522): getSBEnabled() enabled =false
,I/DBG_DM  ( 6230): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,D/SmartBondingService( 3522): getNetworkEnabled : wifi : true mobile : false
,I/DBG_DM  ( 6230): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/GpsLocationProvider( 3522): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/ResourceType( 5345): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5345): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,I/NetworkMonitor(11711): type=WIFI subType= reason=null isConnected=true
,I/PCWCLIENTTRACE_PushUtil(11687): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11687): sales region : global
I/PCWCLIENTTRACE_PushUtil(11687): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11687): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(11766): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(11766): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/SecContentProvider2( 3522): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3522): mCursor = null
,I/FOTA_Client(11783): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(11783): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(11783): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.521: (11799): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jan 29 09:30:02 GMT+01:00 2016
,I/KLMS-2.4.521: (11799): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (11799): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11799): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (11799): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (11799): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (11799): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (11799): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/SO_AGENT(11815): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,I/KLMS-2.4.521: (11799): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.521: (11799): NetworkChangeOperations(): uploadRequestLog().START 
,E/WifiStateMachine( 3522): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3522): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService( 3522): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
V/        ( 2846): QcRouteController
D/SmartBondingService( 3522): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
I/KLMS-2.4.521: (11799): NetworkChangeOperations(): uploadRequestLog().END 
D/SmartBondingService( 3522): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3522): getSBEnabled() enabled =false
D/SmartBondingService( 3522): getSBEnabled() enabled =false
D/SmartBondingService( 3522): getSBEnabled() enabled =false
,I/KLMS-2.4.521: (11799): StateImplV2(): networkChangeListener().END
,V/        ( 2846): QcRouteController
,I/KLMS-2.4.521: (11799): KLMSIntentService(): onDestroy()
W/NetworkManagementService( 3522): route cmd failed: 
W/NetworkManagementService( 3522): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '76 route replace src v6 wlan0 fe80::92b6:86ff:fe43:731c 2 ::' failed with '400 76 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService( 3522): '
W/NetworkManagementService( 3522): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService( 3522): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService( 3522): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService( 3522): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService( 3522): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService( 3522): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5738)
W/NetworkManagementService( 3522): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5545)
W/NetworkManagementService( 3522): 	at com.android.server.ConnectivityService.access$2600(ConnectivityService.java:231)
W/NetworkManagementService( 3522): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2436)
W/NetworkManagementService( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ConnectivityService( 3522): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 3522): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3689): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 4757): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 3689): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 4757): CM callback handler got msg 524295
,E/SPPClientService(11049): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      (11167): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11167): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (11167): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (11167): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11167): [OR] == isSIMCardReady false ==
,I/SA      (11167): [SCU] == networkStateCheck == true
I/SA      (11167): [DM] getCountryCodeFromCSC : PL
I/SA      (11167): isChinaCountryCode : false
I/SA      (11167): [SCU] is ChinestModel Data Restricted   : false
I/SA      (11167): [OR] == networkStateCheck true ==
,I/SA      (11167): [OR] GetMyCountryZoneTask
I/SA      (11167): [OR] onReceive END
,I/SA      (11167): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 3714): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      (11167): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (11167): [SSP] query invoked
,I/System.out( 3522): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/SCloudBackupReceiver(11860): Other Intent
,I/SA      (11167): [TPMU] GetMccFromDB : null
,I/SA      (11167): [SCU] getMccFromPreferece mcc = 260
I/SA      (11167): [TPM] isNoProxy(default) : true
,D/accuweather( 5192): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3774): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,D/accuweather( 5192): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5192): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5192): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5192): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5192): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5192): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro(11876): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro(11876): premStatus:2
,I/KnoxUsageLogPro(11876): isEulaShown : false
I/KnoxUsageLogPro(11876): KnoxUsageReceiver onReceive : not Processible, just return
,D/KeyguardWallpaperUpdator(11907): cancelUpdateWallpaper
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3522): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 29 Jan 2016 08:30:02 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454056202415], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454056202394]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3522): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3522): Validated
,D/KeyguardWallpaperUpdator(11907): cancelUpdateCategory
D/KeyguardWallpaperUpdator(11907): stopCheckCategoryVersion
D/ConnectivityService( 3522): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3522): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3522): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 3522): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3689): CM callback handler got msg 524290
,I/jxcore-log(11573): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log(11573): 
,D/ConnectivityService( 3522): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 4757): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 3689): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3689): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3689): updateDataNetType()
D/StatusBar.NetworkController( 3689): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3689): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3689): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3689): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3689): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3689): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3689): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/QuickConnect(12013): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12013): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect(12013): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 3522): exchangeData() failure , invalid userId
,D/RCPManagerService( 3522): exchangeData() failure , invalid userId
,D/hcjo    (12103): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12103): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12103): exit::IDLE
D/InitializeManagerStateMachine(12103): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12103): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12103): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12103): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12103): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12103): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12103): entry::SUCCESS
D/hcjo    (12103): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    (12103): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12103): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine(12103): exit::SUCCESS
D/InitializeManagerStateMachine(12103): entry::IDLE
,I/SA      (11167): [RC New] Execute method=[GET] start
,I/SA      (11167): [RC New] Security=[true]
,I/System.out(11167): Thread-1540(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out(11167): Thread-1540(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11167): Thread-1540(ApacheHTTPLog):isShipBuild true
I/System.out(11167): Thread-1540(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 503 for uid 10045
,D/ConnectivityService( 3522): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/jxcore-log(11573): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log(11573): 
,I/jxcore-log(11573): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log(11573): 
,I/jxcore-log(11573): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log(11573): 
,I/jxcore-log(11573): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log(11573): 
,I/jxcore-log(11573): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log(11573): 
,I/jxcore-log(11573): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log(11573): 
,I/jxcore-log(11573): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log(11573): 
,I/SA      (11167): [RC New] [v2liruge] api execute + 673
I/SA      (11167): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out(11167): AsyncTask #1 calls detatch()
,I/SA      (11167): [TPMU] getNetworkMcc : 
,I/SA      (11167): [SCU] saveMccToPreferece Start
I/SA      (11167): [SCU] RegionMCC : 260
I/SA      (11167): [SSP] query invoked
,I/SA      (11167): [TPMU] GetMccFromDB : null
I/SA      (11167): [SCU] getMccFromPreferece mcc = 260
I/SA      (11167): [SCU] saveMccToPreferece End
,I/SA      (11167): [RC New] executeRequest [v2liruge] end. 694
I/SA      (11167): [RC New] Execute end
I/SA      (11167): [OR] GetMyCountryZoneTask mcc = 260
I/SA      (11167): [OR] GetMyCountryZoneTask Success
,I/WifiStateMachine( 3522): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine( 3522): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/dhcpcd  (11849): wlan0: sending IPv6 Router Solicitation
,D/WearableService( 4630): callingUid 10014, callindPid: 4630
,D/ResourcesManager(11711): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11711): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11711): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory(11711): Using the GMSCore's GoogleHttpClient
,I/MusicLeanback(11711): Conditions not met for autocaching.
I/MusicLeanback(11711): Stop autocaching.
,D/WearableClient(11711): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11711): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11711): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11711): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(11711): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils(11711): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/ActivityThread(11711): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@13c0c322 that was originally bound here
E/ActivityThread(11711): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@13c0c322 that was originally bound here
E/ActivityThread(11711): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(11711): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(11711): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(11711): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(11711): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(11711): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(11711): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11711): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11711): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11711): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(11711): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(11711): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(11711): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(11711): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(11711): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(11711): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(11711): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(11711): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(11711): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(11711): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(11711): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(11711): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(11711): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(11711): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(11711): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/SurfaceFlinger( 2853): id=15 Removed Uoast (8/9)
,I/SurfaceFlinger( 2853): id=15 Removed Uoast (-2/9)
,D/PowerManagerService( 3522): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3522) eventTime = 122915
D/PowerManagerService( 3522): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3522 (0x0)
D/PowerManagerService( 3522): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3522, ws=WorkSource{10060}) (elapsedTime=3477)
,I/jxcore-log(11573): Test app app.js loaded
I/jxcore-log(11573): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11573): setDiscoveryMode: Mode set to BLE
,I/jxcore-log(11573): BLE advertisement is supported
I/jxcore-log(11573): 
,I/chromium(11573): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/GAV4    (11924): Thread[GAThread,5,main]: No campaign data found.
,V/AlarmManager( 3522): waitForAlarm result :4
,V/AlarmManager( 3522): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager( 3522): <AppSync3 Whitelist>
V/AlarmManager( 3522): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 3689): handleTimeUpdate
,D/KeyguardEffectViewController( 3689): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 3689): *** don't update sliding image ***
,D/DateView( 3689): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3689): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 3522): SIOP:: AP = 300, PST = 285, CUR = 62
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:-223, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:147
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5624): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3522): [PWL] Off : 30s ago
,I/PCWCLIENTTRACE_SYSTEMReceiver(11687): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil(11687): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE(11687): ================================================
,I/CSTORAGE(11687):  CSTORAGE_SKM_LIB v1.0.15
I/CSTORAGE(11687): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI(11687): [GetString-S]
,E/art     (11687): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI(11687): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,I/PCWCLIENTTRACE_SecurePreferencesJNI(11687): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil(11687): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil(11687): sales region : global
I/PCWCLIENTTRACE_PushUtil(11687): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler(11687): [ensureRegistration] - No Samsung account
,D/PackageManager( 3522): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/dhcpcd  (11849): wlan0: sending IPv6 Router Solicitation
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ProcessCpuTracker( 3522): Skipping unknown process pid 12193
,D/PreloadUpdateManagerStateMachine(12103): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(12103): exit::IDLE
,D/PreloadUpdateManagerStateMachine(12103): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (12103): AutoUpdateTriggerManager:REQUEST2:requestInterval
,I/Volley  (12103): RestApi Request Add : 2307
,I/System.out(12103): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out(12103): (HTTPLog)-Static: isShipBuild true
I/System.out(12103): (HTTPLog)-Thread-1700-362409349: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out(12103): (HTTPLog)-Static: isSBSettingEnabled false
,D/PreloadUpdateManagerStateMachine(12103): execute::CHECK_TIMEOUT_FOR_UPDATE:EXECUTE
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 503 for uid 10013
,I/System.out(12103): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid (12103): Tagging socket 26 with tag 79a327ee00000000{2040735726,0} uid -1, pid: 12103, getuid(): 10013
,I/qtaguid (12103): Untagging socket 26
,D/hcjo    (12103): AutoUpdateTriggerManager:REQUEST2:setInterval:86400000
,D/hcjo    (12103): AutoUpdateTriggerManager:REQUEST2:notifyTimedOutAndWriteUpdateCheckedTime
,D/PreloadUpdateManagerStateMachine(12103): execute::CHECK_TIMEOUT_FOR_UPDATE:TIMED_OUT
D/PreloadUpdateManagerStateMachine(12103): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine(12103): entry::REQ_UPDATE_CHECK
,I/Volley  (12103): RestApi Request Add : 2315
,I/System.out(12103): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out(12103): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid (12103): Tagging socket 28 with tag 79a327ee00000000{2040735726,0} uid -1, pid: 12103, getuid(): 10013
,I/dhcpcd  (11849): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  (11849): wlan0: no IPv6 Routers available
,I/qtaguid (12103): Untagging socket -1
,I/qtaguid (12103): Failed write_ctrl(u -1) res=-1 errno=9
,I/qtaguid (12103): Untagging socket -1 failed errno=-9
,W/NetworkManagementSocketTagger(12103): untagSocket(-1) failed with errno -9
,D/PreloadUpdateManagerStateMachine(12103): execute::REQ_UPDATE_CHECK:REQUEST_SUCCESS
,D/PreloadUpdateManagerStateMachine(12103): exit::REQ_UPDATE_CHECK
,D/PreloadUpdateManagerStateMachine(12103): entry::NOTIFY_NOTIFICATION
D/PreloadUpdateManagerStateMachine(12103): exit::NOTIFY_NOTIFICATION
,D/PreloadUpdateManagerStateMachine(12103): entry::FINISH
,D/PreloadUpdateManagerStateMachine(12103): exit::FINISH
,D/PreloadUpdateManagerStateMachine(12103): entry::IDLE
,E/Watchdog( 3522): !@Sync 4
,D/SSRM:n  ( 3522): SIOP:: AP = 280, PST = 280, CUR = -223
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:-25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:106
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5624): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2874): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 260, PST = 278, CUR = -25,
,I/PowerManagerService( 3522): [PWL] Off : 50s ago
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:44, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:90
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged,
I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5624): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3522): SIOP:: AP = 260, PST = 273, CUR = 44,
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:59, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:95
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5624): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ProcessCpuTracker( 3522): Skipping unknown process pid 12296
,E/Watchdog( 3522): !@Sync 5
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 271, CUR = 59
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:66, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:61
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5624): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3522): [PWL] Off : 75s ago
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 270, CUR = 66
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:65, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:64
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5624): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3522): waitForAlarm result :8
,I/ClearcutLoggerApiImpl( 4630): disconnect managed GoogleApiClient
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 268, CUR = 65
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:62, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:53
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5624): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3522): !@Sync 6
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 264, CUR = 62
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:58, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:38
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5624): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2874): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3522): [PWL] Off : 105s ago
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 263, CUR = 58
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:54, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:40
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5624): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3522): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3689): handleTimeUpdate
,D/KeyguardEffectViewController( 3689): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3689): *** don't update sliding image ***
,D/DateView( 3689): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3689): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 262, CUR = 54,
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:50, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:41
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5624): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 7
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 259, CUR = 50
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:49, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:57
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5624): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3522): [PWL] Off : 140s ago
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 255, CUR = 49
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:46, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:42
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5624): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3522): waitForAlarm result :8
,I/jxcore-log(11573): --= Surplus to requirements =--
I/jxcore-log(11573): 
,I/jxcore-log(11573): ****TEST TOOK:  ms ****
I/jxcore-log(11573): 
,I/jxcore-log(11573): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(11573): 
,D/AndroidRuntime(12411): 
D/AndroidRuntime(12411): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(12411): CheckJNI is OFF
,D/AndroidRuntime(12411): readGMSProperty: start
D/AndroidRuntime(12411): readGMSProperty: already setted!!
,D/AndroidRuntime(12411): readGMSProperty: end
D/AndroidRuntime(12411): addProductProperty: start
,E/AffinityControl(12411): AffinityControl: registerfunction enter
,D/AndroidRuntime(12411): Calling main entry com.android.commands.pm.Pm
,D/PersonaManagerService( 3522): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
,D/PackageManager( 3522): START PACKAGE DELETE: observer{213402714}
D/PackageManager( 3522): pkg{<packageName>}
D/PackageManager( 3522): user{0}
D/PackageManager( 3522): caller{2000}
D/PackageManager( 3522): flags{3}
D/PersonaManagerService( 3522): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 3522): [MSG] DELETE_PACKAGE_AS_USER
,D/PersonaManagerService( 3522): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3522): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3522): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3522): !@killApplicatoin: 10607, uninstall pkg
,D/PackageManagerService( 3522): deletePackage- pkg:com.test.thalitest, edmuserId:0
I/ActivityManager( 3522): Force stopping com.test.thalitest appid=10607 user=-1: uninstall pkg
D/PackageManagerService( 3522): deletePackage- pkg:com.test.thalitest, edmuserId:-1
I/ActivityManager( 3522): Killing 11573:com.test.thalitest/u0a607 (adj 0): stop com.test.thalitest
,D/ApplicationPolicy( 3522): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3522): getApplicationUninstallationEnabled :  enabled true
,I/ActivityManager( 3522):   Force finishing activity ActivityRecord{15fc12d1 u0 com.test.thalitest/.MainActivity t26}
W/ActivityManager( 3522): mDVFSHelper.acquire()
,W/PackageSettings( 3522): Skipping PackageSetting{4c0f66d com.example.hello/10563} due to missing metadata
,I/DBG_DM  ( 6230): [com.wssyncmldm.ui.XUIInstallConfirmActivity(456/onResume)] 
,D/WifiService( 3522): Client connection lost with reason: 4
,D/PointerIcon( 3522): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,I/WindowState( 3522): WIN DEATH: Window{85c5a1f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger( 2853): id=14 Removed NainActivit (5/8)
,I/SurfaceFlinger( 2853): id=14 Removed NainActivit (-2/8)
,D/PointerIcon( 3522): setMouseCustomIcon IconType is same.101
,D/PointerIcon( 3522): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 3522): setHoveringSpenCustomIcon IconType is same.1
,I/ActivityManager( 3522): Force stopping com.test.thalitest appid=10607 user=0: pkg removed
,I/DBG_DM  ( 6230): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 10
,I/DBG_DM  ( 6230): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,I/DBG_DM  ( 6230): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6230): [com.wssyncmldm.ui.XUIInstallConfirmActivity(466/onResume)] Postpone Count : 10
,I/DBG_DM  ( 6230): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,I/art     ( 8723): Explicit concurrent mark sweep GC freed 28463(1608KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.150ms total 54.619ms
,I/DBG_DM  ( 6230): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/art     ( 4055): Explicit concurrent mark sweep GC freed 30736(1896KB) AllocSpace objects, 0(0B) LOS objects, 21% free, 28MB/36MB, paused 1.328ms total 33.744ms
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/InputReader( 3522): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 4498): mOCRHelper is null
,W/GeofencerStateMachine( 4630): Ignoring removeGeofence because network location is disabled.
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,I/art     ( 4757): Explicit concurrent mark sweep GC freed 27664(1563KB) AllocSpace objects, 3(48KB) LOS objects, 20% free, 31MB/39MB, paused 2.036ms total 122.946ms
,E/Zygote  (12443): MountEmulatedStorage()
E/Zygote  (12443): v2
I/libpersona(12443): KNOX_SDCARD checking this for 10063
I/libpersona(12443): KNOX_SDCARD not a persona
,I/SELinux (12443): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3522): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=12443 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (12443): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12443): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/talkback/talkback.apk
,I/DBG_DM  ( 6230): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/EnterpriseDeviceManagerService( 3522): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3522): Admin package name: com.google.android.gms
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
W/ResourceType( 5345): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5345): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/SecContentProvider2( 3522): uri = 14 selection = getSealedState
D/SecContentProvider2( 3522): mCursor = null
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/TimaKeyStoreProvider(12443): TimaSignature is unavailable
,D/ActivityThread(12443): Added TimaKeyStore provider
D/ApplicationPolicy( 3522): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3522): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,I/DBG_DM  ( 6230): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 10
,I/DBG_DM  ( 6230): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/DBG_DM  ( 6230): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6230): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 6230): [llIIlIIlIllIllIlllII(376/llIIllllIIlllIIIIlll)] 
,I/DBG_DM  ( 6230): [IIlIIIlllllIIlIIIlII(339/llllIlIIIllllIIlIlll)] No need to check encryption status
I/DBG_DM  ( 6230): [llIIlIIlIllIllIlllII(405/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
,D/ActivityManager( 3522): post active user change for 0
D/KnoxTimeoutHandler( 3522): postActiveUserChange for user 0
,I/DBG_DM  ( 6230): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
,I/SurfaceFlinger( 2853): id=16 createSurf (1440x2560),2 flag=404, YUIInstallC
,D/StatusBarManagerService( 3522): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3522): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3522): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3522): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3522): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3522): setHoveringSpenCustomIcon IconType is same.1
V/ActivityThread( 6230): updateVisibility : ActivityRecord{22e9d3c7 token=android.os.BinderProxy@1ab6abc8 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/ResourcesManager(12443): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,I/art     ( 3522): Explicit concurrent mark sweep GC freed 49831(3MB) AllocSpace objects, 43(688KB) LOS objects, 24% free, 49MB/65MB, paused 2.390ms total 185.494ms
,D/ResourcesManager( 3522): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/art     ( 3522): WaitForGcToComplete blocked for 182.016ms for cause Explicit
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,D/VRSetupWizardStub/PackageIntentReceiver(12443): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(12443): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(12443): packagename:com.test.thalitest
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,I/KLMS-2.4.521: (11799): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jan 29 09:32:05 GMT+01:00 2016
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,I/KLMS-2.4.521: (11799): KLMSAbstractReciever(): onReceive().END.
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/splitIntent( 3522): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3522): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (11799): KLMSIntentService(): onCreate()
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,I/KLMS-2.4.521: (11799): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,I/KLMS-2.4.521: (11799): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/InputMethodManagerService( 3522): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/SecContentProvider2( 3522): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3522): mCursor = null
,E/Zygote  (12462): MountEmulatedStorage()
E/Zygote  (12462): v2
I/libpersona(12462): KNOX_SDCARD checking this for 10106
I/libpersona(12462): KNOX_SDCARD not a persona
,I/SELinux (12462): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12462): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3522): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=12462 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,E/SELinux (12462): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/InputMethodManagerService( 3522): Got RemoteException sending setActive(false) notification to pid 11573 uid 10607
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/KLMS-2.4.521: (11799): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (11799): KLMSIntentService(): PACKAGE_REMOVED
,I/Timeline( 6230): Timeline: Activity_idle id: android.os.BinderProxy@1ab6abc8 time:242324
,I/KLMS-2.4.521: (11799): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.4.521: (11799): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,D/RCPManager(11876):  in createShortcut() for packageName: com.test.thalitest userId0
,D/TimaKeyStoreProvider(12462): TimaSignature is unavailable
D/ActivityThread(12462): Added TimaKeyStore provider
,D/RCPManagerService( 3522):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3522): queryAllProviders():  providerCallBack is not register for 0
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,D/RegisteredServicesCache( 3960): empty dynamic service
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
,E/Zygote  (12479): MountEmulatedStorage()
E/Zygote  (12479): v2
I/libpersona(12479): KNOX_SDCARD checking this for 10050
I/libpersona(12479): KNOX_SDCARD not a persona
,I/SELinux (12479): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12479): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3522): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=12479 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,E/SELinux (12479): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 8730(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 578us total 14.121ms
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (11799): KLMSIntentService(): listeningToPackageRemoved().END
,D/ResourcesManager(12462): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/TimaKeyStoreProvider(12479): TimaSignature is unavailable
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 491us total 9.809ms
D/ActivityThread(12479): Added TimaKeyStore provider
,I/art     ( 3522): Explicit concurrent mark sweep GC freed 6241(318KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 49MB/65MB, paused 2.186ms total 152.025ms
I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 549us total 9.911ms
,D/elm:14491(12462): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14491(12462): ELMEngine.ELMEngine( context ).
D/elm:14491(12462): MDMBridge.setEnterpriseBridge()
,E/Zygote  (12494): MountEmulatedStorage()
E/Zygote  (12494): v2
I/libpersona(12494): KNOX_SDCARD checking this for 10101
I/libpersona(12494): KNOX_SDCARD not a persona
,I/SELinux (12494): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12494): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3522): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=12494 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (12494): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,W/ActivityManager( 3522): mDVFSHelper.release()
I/Timeline( 3522): Timeline: Activity_windows_visible id: ActivityRecord{2f58b774 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t24} time:242424
,I/KLMS-2.4.521: (11799): KLMSIntentService(): onDestroy()
,D/TimaKeyStoreProvider(12494): TimaSignature is unavailable
,D/ActivityThread(12494): Added TimaKeyStore provider
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/elm:14491(12462): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/PackageManager( 3522): delete codoeFile: 
,D/elm:14491(12462): ElmAgentService : onCreate()
D/elm:14491(12462): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,I/AASAUninstall( 3522):  com.test.thalitest not target!
,D/PackageManager( 3522): result of delete: 1{213402714}
D/elm:14491(12462): MainReceiver.listeningToPackageRemoved()
D/elm:14491(12462): MDMBridge.getInstance()
D/elm:14491(12462): MDMBridge.getAllLicenseInfoFromSDK()
,D/AndroidRuntime(12411): Shutting down VM
D/elm:14491(12462): MDMBridge.getAllLicenseInfoFromSDK()
,I/TapandpayWidget:TanpandpayAppWidgetProvider(11392): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(11392): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
I/TapandpayWidget:Utils(11392): Clear T&P info.
,D/TapandpayWidget:TanpandpayAppWidgetProvider(11392): Widget is not attached.
,D/elm:14491(12462): ElmAgentService : onDestroy().
D/ResourcesManager(12479): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/ResourcesManager(12479): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12479): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12479): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12479): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12479): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(12479): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(12479): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12479): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(12494): creating new AssetManager and set to /system/app/Drive/Drive.apk
,E/Zygote  (12512): MountEmulatedStorage()
E/Zygote  (12512): v2
I/libpersona(12512): KNOX_SDCARD checking this for 10019
I/libpersona(12512): KNOX_SDCARD not a persona
,I/SELinux (12512): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3522): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=12512 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,I/SELinux (12512): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
W/ResourceType( 3522): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,E/SELinux (12512): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/TimaKeyStoreProvider(12512): TimaSignature is unavailable
,D/ActivityThread(12512): Added TimaKeyStore provider
,I/ActivityManager( 3522): Killing 11358:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##31
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 3522): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
W/ResourcesManager( 3522): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3522): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 3522): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/DocsApplication(12494): Installing DEX configuration.
,D/PackageBroadcastService( 4757): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 4757): Clearing selected account for com.test.thalitest
,I/ActivityManager( 3522): Killing 10772:com.android.defcontainer/u0a5 (adj 13): bgCount ##31
,D/DexInstaller(12494): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,I/PackageInfoHelper(12494): Provided clientMode=RELEASE, packageInfo=PackageInfo{c6c2f9f com.google.android.apps.docs}
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/TAG     (12494): onCreate()
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
D/ResourcesManager(12512): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/CrossAppStateProvider(12494): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/PackageManager( 3522): findPreferredActivity: No PreferredActivities set
,I/LocationSettingsChecker( 4757): Removing dialog suppression flag for package com.test.thalitest
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/ChimeraCfgMgr( 4757): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4757): Module APK com.google.android.play.games already loaded
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Music2/Music2.apk
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/gH_CompatibleDatabase( 4757): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 4757): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 4757): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 4757): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/gH_CompatibleDatabase( 4757): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 4757): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 4757): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/gH_CompatibleDatabase( 4757): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 4757): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 4757): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 4757): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 4757): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/ChimeraCfgMgr( 4757): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4757): Module APK com.google.android.play.games already loaded
D/RCPManagerService( 3522): PackageReceiver onReceive()
I/HarmonyEASService( 3522): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/gH_CompatibleDatabase( 4757): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,D/KnoxMUMContainerPolicy( 3522): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService( 3522): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 3522): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3522): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3522): uID is 10607
V/EnterpriseBillingPolicy( 3522): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3522): getProfileForApplication - enter
D/com.sec.android.service.health.upgrade.UninstallReceiver(12512): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver(12512): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver(12512): onReceive() : package name is not s health. Return !!!
V/EnterpriseBillingPolicyStorage( 3522): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3522): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3522): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3522): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 3522): getBillingProfileForVpnEngine - end - null
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12533): MountEmulatedStorage()
,E/Zygote  (12533): v2
I/libpersona(12533): KNOX_SDCARD checking this for 10022
I/libpersona(12533): KNOX_SDCARD not a persona
,I/SELinux (12533): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12533): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12533): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.sec.android.widgetapp.locationwidget for broadcast com.sec.android.widgetapp.locationwidget/.cocktail.LocationWidgetCocktailProvider: pid=12533 uid=10022 gids={50022, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3522): Killing 10347:com.android.vending/u0a31 (adj 13): bgCount ##31
,D/UsbSettingsManager( 3522): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 3522): onPackageRemoved : com.test.thalitest
,D/TaskPersister( 3522): removeObsoleteFile: deleting file=26_task.xml
,D/TaskPersister( 3522): removeObsoleteFile: deleting file=24_task.xml
,D/KnoxTimeoutHandler( 3522): handleActiveUserChange for user 0
,E/NetworkScheduler.SchedulerReceiver( 4630): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 4630): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/TimaKeyStoreProvider(12533): TimaSignature is unavailable
,D/ActivityThread(12533): Added TimaKeyStore provider
,D/StatusBar( 3689): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 3689): isKioskContainerExistOnDevice
D/PersonaManager( 3689): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 3689): Icon Only
I/StatusBar( 3689): Icon Only
D/PanelView( 3689): There is/are notification(s) 
D/PanelView( 3689): There is/are notification(s) 
,D/PersonaManager( 3689): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3689): Icon Only
I/StatusBar( 3689): Icon Only
,D/PanelView( 3689): There is/are notification(s) 
,D/ResourcesManager(12533): creating new AssetManager and set to /system/priv-app/LocationWidget/LocationWidget.apk
,W/ResourcesManager(12533): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/ActivityThread(11662): Failed to find provider info for com.facebook.appmanager.installrecord
,W/ResourcesManager(12533): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12533): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,I/Icing   ( 4757): doRemovePackageData com.test.thalitest
,D/NearbySource(12479): Nearby Source Create!
D/NearbyContext(12479): Nearby Context Create!
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12479): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource(12479): Samsung link source created
,I/LocationWidgetApplication(12533): onCreate() : start
,D/LocationWidgetApplication(12533): countryCode = POLAND
,D/PanelView( 3689): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,D/WifiDisplayAdapter( 3522): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3522): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/ContactProvider(12479): getAllContactInfoList Start
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/LocationManagerService( 3522): getProviders()=[]
D/LocationManagerService( 3522): getProviders()=[passive]
D/LocationManagerService( 3522): getBestProvider(Criteria[power=LOW acc=LOW], true)=passive
D/LWLocationManager(12533): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(12533): getLastUiLocationId() : mLastUiLocationId = -100
E/SharedPreferencesImpl(12479): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
,E/SQLiteLog(12533): (28) failed to open "/data/data/com.sec.android.widgetapp.locationwidget/databases/LBHWidget.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(12533): Failed to open database '/data/data/com.sec.android.widgetapp.locationwidget/databases/LBHWidget.db'.
E/SQLiteDatabase(12533): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12533): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12533): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12533): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12533): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12533): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12533): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12533): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12533): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12533): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12533): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12533): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12533): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12533): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12533): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12533): 	at com.sec.android.widgetapp.locationwidget.db.LocationWidgetDBControll.<init>(LocationWidgetDBControll.java:52)
E/SQLiteDatabase(12533): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getDBList(LocationWidgetFuctionData.java:690)
E/SQLiteDatabase(12533): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.configPlaceListItems(LocationWidgetFuctionData.java:548)
E/SQLiteDatabase(12533): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getPlaceListItems(LocationWidgetFuctionData.java:55)
E/SQLiteDatabase(12533): 	at com.sec.android.widgetapp.locationwidget.cocktail.LocationWidgetCocktailProvider.onReceive(LocationWidgetCocktailProvider.java:277)
E/SQLiteDatabase(12533): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
E/SQLiteDatabase(12533): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
E/SQLiteDatabase(12533): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
E/SQLiteDatabase(12533): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12533): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12533): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12533): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12533): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12533): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12533): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime(12533): Shutting down VM
E/AndroidRuntime(12533): FATAL EXCEPTION: main
E/AndroidRuntime(12533): Process: com.sec.android.widgetapp.locationwidget, PID: 12533
E/AndroidRuntime(12533): java.lang.RuntimeException: Unable to start receiver com.sec.android.widgetapp.locationwidget.cocktail.LocationWidgetCocktailProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12533): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3001)
E/AndroidRuntime(12533): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
E/AndroidRuntime(12533),: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
E/AndroidRuntime(12533): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(12533): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(12533): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(12533): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(12533): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(12533): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(12533): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(12533): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12533): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12533): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(12533): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(12533): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12533): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12533): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12533): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(12533): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(12533): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(12533): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(12533): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12533): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12533): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(12533): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(12533): 	at com.sec.android.widgetapp.locationwidget.db.LocationWidgetDBControll.<init>(LocationWidgetDBControll.java:52)
E/AndroidRuntime(12533): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getDBList(LocationWidgetFuctionData.java:690)
E/AndroidRuntime(12533): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.configPlaceListItems(LocationWidgetFuctionData.java:548)
E/AndroidRuntime(12533): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getPlaceListItems(LocationWidgetFuctionData.java:55)
E/AndroidRuntime(12533): 	at com.sec.android.widgetapp.locationwidget.cocktail.LocationWidgetCocktailProvider.onReceive(LocationWidgetCocktailProvider.java:277)
E/AndroidRuntime(12533): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
E/AndroidRuntime(12533): 	... 9 more
E/Zygote  (12561): MountEmulatedStorage()
E/Zygote  (12561): v2
I/libpersona(12561): KNOX_SDCARD checking this for 10052
I/libpersona(12561): KNOX_SDCARD not a persona
I/SELinux (12561): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3522): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=12561 uid=10052 gids={50052, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
V/ApplicationPolicy( 3522): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.locationwidget
I/SELinux (12561): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12561): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/PCWCLIENTTRACE_PushUtil(11687): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11687): sales region : global
I/PCWCLIENTTRACE_PushUtil(11687): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11687): [onReceive] - android.intent.action.PACKAGE_REMOVED
,I/ActivityManager( 3522): Killing 12070:com.sec.android.provider.badge/u0a82 (adj 13): bgCount ##31
D/UsbHostManager( 3522): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
D/UsbHostManager( 3522): displayNotification : [02h,02h,01h]
D/UsbHostManager( 3522): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
D/UsbHostManager( 3522): displayNotification : [0ah,00h,00h]
D/UsbHostManager( 3522): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3522): displayNotification : [02h,0dh,00h]
E/DropBoxManagerService( 3522): Can't write: system_app_crash
E/DropBoxManagerService( 3522): java.io.FileNotFoundException: /data/system/dropbox/drop194.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3522): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3522): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3522): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3522): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3522): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3522): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3522): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3522): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3522): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3522): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3522): 	... 5 more
D/UsbHostManager( 3522): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3522): displayNotification : [0ah,00h,01h]
D/UsbHostManager( 3522): usbDeviceRemoved : /dev/bus/usb/001/003
E/UsbHostManager( 3522): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
D/UsbSettingsManager( 3522): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider(12561): TimaSignature is unavailable
D/ActivityThread(12561): Added TimaKeyStore provider
E/Zygote  (12583): MountEmulatedStorage()
E/Zygote  (12583): v2
I/libpersona(12583): KNOX_SDCARD checking this for 10035
I/libpersona(12583): KNOX_SDCARD not a persona
I/SELinux (12583): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3522): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=12583 uid=10035 gids={50035, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/SELinux (12583): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12583): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Killing 8739:com.android.settings/1000 (adj 13): bgCount ##31
,D/UsbHostManager( 3522): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
D/UsbHostManager( 3522): displayNotification : [09h,00h,00h]
,I/art     ( 4630): Explicit concurrent mark sweep GC freed 74968(4MB) AllocSpace objects, 45(2MB) LOS objects, 34% free, 30MB/46MB, paused 946us total 48.233ms
,I/Process (12533): Sending signal. PID: 12533 SIG: 9
,D/ResourcesManager(12561): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/MtpClient(12479): onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
D/MtpClient(12479): ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
,W/ResourcesManager(12561): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager(12561): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12561): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider(12583): TimaSignature is unavailable
W/ResourcesManager(12561): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12561): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager(12561): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/ActivityThread(12583): Added TimaKeyStore provider
,D/UsbHostManager( 3522): usbDeviceRemoved : /dev/bus/usb/001/001
E/UsbHostManager( 3522): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
,E/SQLiteLog(12494): (28) failed to open "/data/data/com.google.android.apps.docs/databases/ClientFlag.db" with flag (131138) and mode_t (0) due to error (30)
D/ResourcesManager(12583): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,E/SQLiteDatabase(12494): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase(12494): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12494): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12494): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12494): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12494): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12494): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12494): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12494): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12494): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12494): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12494): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12494): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12494): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12494): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(12494): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase(12494): 	at QF.provideClientFlag(ClientFlagsModule.java:71)
E/SQLiteDatabase(12494): 	at QH.a(GellyInjectorStore.java:215)
E/SQLiteDatabase(12494): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12494): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12494): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12494): 	at tQ.a(GellyInjectorStore.java:2039)
E/SQLiteDatabase(12494): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12494): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12494): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12494): 	at pG.a(GellyInjectorStore.java:478)
E/SQLiteDatabase(12494): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12494): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12494): 	at qD.a(GellyInjectorStore.java:118)
E/SQLiteDatabase(12494): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12494): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12494): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12494): 	at aEV.a(GellyInjectorStore.java:130)
E/SQLiteDatabase(12494): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12494): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12494): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12494): 	at aGH.a(GellyInjectorStore.java:227)
E/SQLiteDatabase(12494): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12494): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12494): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12494): 	at aGH.a(GellyInjectorStore.java:392)
E/SQLiteDatabase(12494): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12494): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12494): 	at aGH.a(GellyInjectorStore.java:369)
E/SQLiteDatabase(12494): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12494): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12494): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12494): 	at agN.a(GellyInjectorStore.java:799)
E/SQLiteDatabase(12494): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12494): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12494): 	at pG.a(GellyInjectorStore.java:146)
E/SQLiteDatabase(12494): 	at pG.a(GellyInjectorStore.java:392)
E/SQLiteDatabase(12494): 	at bsh.a(GellyMembersInjector.java:30)
E/SQLiteDatabase(12494): 	at brQ.a(GellyInjector.ja,va:119)
E/SQLiteDatabase(12494): 	at ajB.a(ScopedInjector.java:216)
E/SQLiteDatabase(12494): 	at com.google.android.apps.docs.DocsApplication.a(DocsApplication.java:235)
E/SQLiteDatabase(12494): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase(12494): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(12494): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(12494): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12494): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12494): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12494): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12494): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12494): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12494): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12494): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12494): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper(12494): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper(12494): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(12494): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(12494): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(12494): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(12494): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(12494): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(12494): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(12494): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(12494): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(12494): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(12494): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(12494): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(12494): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(12494): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(12494): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper(12494): 	at QF.provideClientFlag(ClientFlagsModule.java:71)
E/SQLiteOpenHelper(12494): 	at QH.a(GellyInjectorStore.java:215)
E/SQLiteOpenHelper(12494): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12494): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12494): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12494): 	at tQ.a(GellyInjectorStore.java:2039)
E/SQLiteOpenHelper(12494): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12494): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12494): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12494): 	at pG.a(GellyInjectorStore.java:478)
E/SQLiteOpenHelper(12494): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12494): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12494): 	at qD.a(GellyInjectorStore.java:118)
E/SQLiteOpenHelper(12494): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12494): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12494): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12494): 	at aEV.a(Gelly,InjectorStore.java:130)
E/SQLiteOpenHelper(12494): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12494): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12494): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12494): 	at aGH.a(GellyInjectorStore.java:227)
E/SQLiteOpenHelper(12494): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12494): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12494): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12494): 	at aGH.a(GellyInjectorStore.java:392)
E/SQLiteOpenHelper(12494): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12494): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12494): 	at aGH.a(GellyInjectorStore.java:369)
E/SQLiteOpenHelper(12494): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12494): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12494): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12494): 	at agN.a(GellyInjectorStore.java:799)
E/SQLiteOpenHelper(12494): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12494): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12494): 	at pG.a(GellyInjectorStore.java:146)
E/SQLiteOpenHelper(12494): 	at pG.a(GellyInjectorStore.java:392)
E/SQLiteOpenHelper(12494): 	at bsh.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper(12494): 	at brQ.a(GellyInjector.java:119)
E/SQLiteOpenHelper(12494): 	at ajB.a(ScopedInjector.java:216)
E/SQLiteOpenHelper(12494): 	at com.google.android.apps.docs.DocsApplication.a(DocsApplication.java:235)
E/SQLiteOpenHelper(12494): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper(12494): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(12494): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(12494): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(12494): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(12494): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(12494): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(12494): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(12494): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(12494): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(12494): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(12494): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
I/EventHub( 3522): Removing device '/dev/input/event10' due to inotify event
D/ContactProvider(12479): getAllContactInfoList End
I/syncContacts(12479): thread: 1713, sync time = 174
W/SQLiteOpenHelper(12494): Opened ClientFlag.db in read-only mode
D/WifiService( 3522): Client connection lost with reason: 4
,I/EventHub( 3522): Removing device '/dev/input/event7' due to inotify event
,I/ActivityManager( 3522): Process com.sec.android.widgetapp.locationwidget (pid 12533)(adj 9) has died(220,1195)
,I/FeatureConfig(12583): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,E/SQLiteLog(12494): (28) failed to open "/data/data/com.google.android.apps.docs/databases/DocList.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(12494): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase(12494): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12494): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12494): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12494): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12494): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12494): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12494): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12494): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12494): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12494): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12494): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12494): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12494): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12494): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12494): 	at aFu.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase(12494): 	at aFo.a(AbstractDatabaseInstance.java:457)
E/SQLiteDatabase(12494): 	at aFo.a(AbstractDatabaseInstance.java:453)
E/SQLiteDatabase(12494): 	at bjx.a(Suppliers.java:125)
E/SQLiteDatabase(12494): 	at aFp.run(AbstractDatabaseInstance.java:471)
,E/AndroidRuntime(12494): FATAL EXCEPTION: Open database in background
E/AndroidRuntime(12494): Process: com.google.android.apps.docs, PID: 12494
E/AndroidRuntime(12494): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12494): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12494): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(12494): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(12494): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12494): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12494): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12494): 	,at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(12494): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(12494): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(12494): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(12494): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12494): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(12494): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(12494): 	at aFu.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime(12494): 	at aFo.a(AbstractDatabaseInstance.java:457)
E/AndroidRuntime(12494): 	at aFo.a(AbstractDatabaseInstance.java:453)
E/AndroidRuntime(12494): 	at bjx.a(Suppliers.java:125)
E/AndroidRuntime(12494): 	at aFp.run(AbstractDatabaseInstance.java:471)
,V/ApplicationPolicy( 3522): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.docs,
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/DropBoxManagerService( 3522): Can't write: system_app_crash
E/DropBoxManagerService( 3522): java.io.FileNotFoundException: /data/system/dropbox/drop196.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3522): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3522): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3522): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3522): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3522): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3522): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3522): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3522): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3522): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3522): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3522): 	... 5 more
,D/ResourcesManager(12583): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager(12583): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager(12583): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12583): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12583): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12583): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(12583): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/EventHub( 3522): Removing device '/dev/input/event8' due to inotify event
,E/SQLiteLog(12494): (28) failed to open "/data/data/com.google.android.apps.docs/databases/ClientFlag.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(12494): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase(12494): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12494): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12494): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12494): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12494): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12494): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12494): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12494): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12494): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12494): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12494): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12494): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12494): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12494): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(12494): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase(12494): 	at com.google.android.apps.docs.DocsApplication.i(DocsApplication.java:349)
E/SQLiteDatabase(12494): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:229)
E/SQLiteDatabase(12494): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(12494): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(12494): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12494): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12494): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12494): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12494): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12494): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12494): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12494): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12494): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper(12494): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper(12494): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(12494): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(12494): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(12494): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(12494): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(12494): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(12494): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(12494): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(12494): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(12494): 	at android.database.sql,ite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(12494): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(12494): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(12494): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(12494): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(12494): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper(12494): 	at com.google.android.apps.docs.DocsApplication.i(DocsApplication.java:349)
E/SQLiteOpenHelper(12494): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:229)
E/SQLiteOpenHelper(12494): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(12494): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(12494): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(12494): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(12494): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(12494): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(12494): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(12494): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(12494): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(12494): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(12494): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/ResourcesManager(12583): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
W/SQLiteOpenHelper(12494): Opened ClientFlag.db in read-only mode
W/ResourcesManager(12583): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12583): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12583): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
E/Zygote  (12607): MountEmulatedStorage()
E/Zygote  (12607): v2
I/libpersona(12607): KNOX_SDCARD checking this for 1000
I/libpersona(12607): KNOX_SDCARD not a persona
I/SELinux (12607): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager(12583): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
I/SELinux (12607): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12607): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ResourcesManager(12583): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager(12583): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12583): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager(12583): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12583): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12583): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12583): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/ActivityManager( 3522): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=12607 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/Process (12494): Sending signal. PID: 12494 SIG: 9
,D/Mms/MmsApp(12561): [start]    onCreate() consume time = 0.0
,I/EventHub( 3522): Removing device '/dev/input/event9' due to inotify event
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/Mms/ArtClassLoader(12561): init before art
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(12583): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/Mms/ArtClassLoader(12561): init [DONE] art
,D/ResourcesManager(12583): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,E/Zygote  (12622): MountEmulatedStorage()
E/Zygote  (12622): v2
I/libpersona(12622): KNOX_SDCARD checking this for 10036
I/libpersona(12622): KNOX_SDCARD not a persona
,I/SELinux (12622): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/EventHub( 3522): Removing device '/dev/input/event11' due to inotify event
,I/SELinux (12622): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12622): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=12622 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,W/ResourcesManager(12583): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(12583): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/lowmemorykiller( 2828): Error writing /proc/12494/oom_score_adj; errno=22
W/ResourcesManager(12583): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(12583): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
E/JavaBinder( 3522): !!! FAILED BINDER TRANSACTION !!!
,I/ActivityManager( 3522): Killing 11747:com.sec.android.cloudagent/u0a2 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12607): TimaSignature is unavailable
,D/ActivityThread(12607): Added TimaKeyStore provider
,D/ResourcesManager(12583): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,W/ResourcesManager(12583): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12583): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12583): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/EventHub( 3522): Removing device '/dev/input/event12' due to inotify event
,D/ResourcesManager(12583): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/Mms/TelephonyPermission(12561): start operation mode monitor
,W/ResourcesManager(12583): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12583): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12583): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12583): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12583): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(12583): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(12583): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12583): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager(12583): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager(12583): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12583): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12583): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager(12561): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,I/EventHub( 3522): Removing device '/dev/input/event13' due to inotify event
,W/ResourcesManager(12561): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/ActivityManager( 3522): Process com.google.android.apps.docs (pid 12494)(adj 9) has died(246,1195)
,D/ResourcesManager(12583): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager(12583): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12583): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12583): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12583): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12583): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider(12622): TimaSignature is unavailable
,D/ActivityThread(12622): Added TimaKeyStore provider
,D/ResourcesManager(12583): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager(12583): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager(12583): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12583): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/BroadcastQueue( 3522): Skipping deliver [background] BroadcastRecord{f0126bf u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{2c4c9c19 12494 com.google.android.apps.docs/10101/u0 remote:160d2f60}: filter unregistered
,I/EventHub( 3522): Removing device '/dev/input/event14' due to inotify event
,D/ResourcesManager(12607): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk
,D/Mms/TelephonyPermission(12561): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission(12561): isDefault true
,D/ResourcesManager(12583): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/Mms/MmsApp(12561): onCreate() com.android.mms
,W/ResourcesManager(12583): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager(12622): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/Mms/MmsApp(12561): [start]    initCountryIso consume time = 238.669708
,D/CountryDetector( 3522): The first listener is added
,W/ContextImpl(12607): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2994 
,D/ResourcesManager(12583): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/Mms/MmsApp(12561): [end]    initCountryIso consume time = 23.15825
D/Mms/MmsConfig(12561): [start]    MmsConfig.init() consume time = 0.297
,W/ResourcesManager(12583): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager(12583): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(12583): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12583): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12583): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12583): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/Mms/MmsConfig(12561): before partial update
,D/ResourcesManager(12583): creating new AssetManager and set to /system/app/Chrome/Chrome.apk

```
