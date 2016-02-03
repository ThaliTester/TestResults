#### Test 5813565532fb33b_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
D/BatteryService( 3509): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3509): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3509): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
D/BatteryService( 3509): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3509): stay LED for fully charged
I/MotionRecognitionService( 3509): Plugged
I/MotionRecognitionService( 3509): setPowerConnected  = true
--------- beginning of main
D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5646): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5646): Disconnected process message: 10
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AndroidRuntime(11875): 
D/AndroidRuntime(11875): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11875): CheckJNI is OFF
D/AndroidRuntime(11875): readGMSProperty: start
D/AndroidRuntime(11875): readGMSProperty: already setted!!
D/AndroidRuntime(11875): readGMSProperty: end
D/AndroidRuntime(11875): addProductProperty: start
E/AffinityControl(11875): AffinityControl: registerfunction enter
D/AndroidRuntime(11875): Calling main entry com.android.commands.am.Am
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
E/Zygote  (11895): MountEmulatedStorage()
E/Zygote  (11895): v2
I/libpersona(11895): KNOX_SDCARD checking this for 10624
I/libpersona(11895): KNOX_SDCARD not a persona
I/SELinux (11895): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11895): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3509): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=11895 uid=10624 gids={50624, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/SELinux (11895): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(11875): Shutting down VM
D/PointerIcon( 3509): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3509): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3509): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3509): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(11895): TimaSignature is unavailable
D/ActivityThread(11895): Added TimaKeyStore provider
I/SurfaceFlinger( 2848): id=11 Removed YUIInstallC (5/8)
I/SurfaceFlinger( 2848): id=11 Removed YUIInstallC (-2/8)
D/ResourcesManager(11895): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
V/ActivityThread( 6325): updateVisibility : ActivityRecord{1c5c6122 token=android.os.BinderProxy@15905997 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
I/WebViewFactory(11895): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(11895): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(11895): Loading: webviewchromium
I/LibraryLoader(11895): Time to load native libraries: 4 ms (timestamps 6239-6243)
I/LibraryLoader(11895): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(11895): Binding Chromium to main looper Looper (main, tid 1) {365bd73d}
,I/LibraryLoader(11895): Expected native library version number "",actual native library version number ""
I/chromium(11895): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(11895): Initializing chromium process, renderers=0
,W/art     (11895): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(11895): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(11895): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(11895): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,W/chromium(11895): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium(11895): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     (11895): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents(11895): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine(11895): CordovaWebView is running on device made by: samsung
W/art     (11895): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11895): Attempt to remove local handle scope entry from IRT, ignoring
D/Activity(11895): performCreate Call secproduct feature valuefalse
D/Activity(11895): performCreate Call debug elastic valuetrue
D/OpenGLRenderer(11895): Render dirty regions requested: true
D/ActivityManager( 3509): post active user change for 0
D/KnoxTimeoutHandler( 3509): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3509): handleActiveUserChange for user 0
I/SurfaceFlinger( 2848): id=13 createSurf (1x1),1 flag=404, NainActivit
D/StatusBarManagerService( 3509): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService( 3509): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 3509): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3509): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3509): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3509): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer(11895): Initialized EGL, version 1.4
I/OpenGLRenderer(11895): HWUI protection enabled for context ,  &this =0xaf6ad1a0 ,&mEglDisplay = 1 , &mEglConfig = -1278770928 
D/OpenGLRenderer(11895): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(11895): Enabling debug mode 0
D/mali_winsys(11895): new_window_surface returns 0x3000,  [1440x2560]-format:1
V/ActivityThread(11895): updateVisibility : ActivityRecord{5609ad token=android.os.BinderProxy@196a7de8 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
D/InputMethodManagerService( 3509): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl( 3509): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ActivityManager( 3509): mDVFSHelper.release()
I/Timeline( 3509): Timeline: Activity_windows_visible id: ActivityRecord{3c217dd6 u0 com.test.thalitest/.MainActivity t26} time:246708
W/IInputConnectionWrapper(11895): showStatusIcon on inactive InputConnection
I/Timeline(11895): Timeline: Activity_idle id: android.os.BinderProxy@196a7de8 time:246719
I/chromium(11895): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11895): 
D/JsMessageQueue(11895): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log(11895): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1357424896
I/chromium(11895): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log(11895): Initializing JXcore engine
W/jxcore-log(11895): JXcore engine is ready
,E/auditd  ( 4619): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3509): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl( 3509): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3509): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(11895): Starting JXcore engine
,W/jxcore-log(11895): Platform android
W/jxcore-log(11895): 
W/jxcore-log(11895): Process ARCH arm
W/jxcore-log(11895): 
,I/jxcore-log(11895): JXcore Cordova bridge is ready!
I/jxcore-log(11895): 
W/jxcore-log(11895): JXcore engine is started
,I/jxcore-log(11895): Toggling radios to true
I/jxcore-log(11895): 
,W/ContextImpl( 3509): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BluetoothAdapter(11895): enable()
,D/BluetoothAdapter(11895): enable(): BT is already enabled..!
,D/WifiService( 3509): New client listening to asynchronous messages
,I/WifiManager(11895): packageName : com.test.thalitest
,D/SecContentProvider( 3509): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3509): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3509): mCursor = null
,D/WifiService( 3509): setWifiEnabled: true pid=11895, uid=10624
E/WifiService( 3509): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3509): Permission Denial: getCurrentUser() from pid=11895, uid=10624 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 3509): Failed getting userId using ActivityManagerNative
W/WifiService( 3509): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=11895, uid=10624 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3509): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3509): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3509): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3509): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3509): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider( 3509): name = wifi_on
,I/WifiService( 3509): disconnect: pid=11895, uid=10624
,I/wpa_supplicant( 3824): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/wpa_supplicant( 3824): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3824): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 3824): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3824): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine( 3509): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 3824): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3824): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3824): Disconnected - do not scan
I/wpa_supplicant( 3824): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine( 3509): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3509): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3509): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3509): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/jxcore-log(11895): Radios toggled
I/jxcore-log(11895): 
,I/jxcore-log(11895): My device name is: samsung-SM-N910C
I/jxcore-log(11895): 
,E/WifiStateMachine( 3509): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3509): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3509): do suspend true
,D/WifiP2pService( 3509): InactiveState{ what=143375 }
,D/WifiP2pService( 3509): P2pEnabledState{ what=143375 }
,D/CommandListener( 2844): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,E/Netd    ( 2844): ifc_reset_connections failed on iface wlan0 for address 192.168.1.124/24 (Unknown error -1)
,E/WifiStateMachine( 3509): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/WifiConfigStore( 3509): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/ConnectivityService( 3509): updateNetworkInfo()
,D/ConnectivityService( 3509): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3509): updateNetworkInfo()
I/WifiTrafficPoller( 3509): evaluateTrafficStatsPolling
D/ConnectivityService( 3509): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,I/Hs20UtilService( 4110): Starting #8
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
I/Hs20UtilService( 4110): Message received 5007
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/NearbySettings( 8852): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 8852): MountReceiver.onReceive - Start HandlerThread
,D/NearbySettings( 8852): MountReceiver.onReceive - Create mPrefHandler
,D/NearbySettings( 8852): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8852): DMSUtil.isNetworkConnected - flag-null, state-null
,E/WifiStateMachine( 3509): Start Disconnecting Watchdog 1
I/NearbySettings( 8852): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
E/WifiStateMachine( 3509): ConnectModeState: Network connection lost 
E/WifiStateMachine( 3509): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - processMessage - processMsg
E/WifiStateMachine( 3509): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine( 3509): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3509): do suspend true
,D/WifiP2pService( 3509): InactiveState{ what=143375 }
D/WifiP2pService( 3509): P2pEnabledState{ what=143375 }
,I/NearbySettings( 8852): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8852): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8852): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 8852): MountReceiver.mPrefHandler - 7002
D/WifiService( 3509): New client listening to asynchronous messages
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
,I/SignOutReceiver(11499): NETWORK_STATE_CHANGED_ACTION
,D/CommandListener( 2844): Clearing all IP addresses on wlan0
,D/ConnectivityService( 3509): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/EntConnectivity( 3509): Not allowed due to - mEnabled false
D/ConnectivityManager.CallbackHandler( 3692): CM callback handler got msg 524292
E/WifiStateMachine( 3509): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityService( 3509): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/CSLegacyTypeTracker( 3509): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 3509): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 3509): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory( 3982): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3509): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 6828): CM callback handler got msg 524292
,D/WifiStateMachine( 3509): updateConfiguredNetworkExpiration - currTime: 1454527995293
D/WifiStateMachine( 3509): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
E/WifiStateMachine( 3509): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine( 3509): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/wpa_supplicant( 3824): wlan0: Setting scan request: 0 sec 0 usec
D/ConnectivityService( 3509): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
I/wpa_supplicant( 3824): P2P: Current p2p state = IDLE
I/wpa_supplicant( 3824): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 3824): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3824): First Scan Start
D/EntConnectivity( 3509): Not allowed due to - mEnabled false
,E/WifiStateMachine( 3509): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3509): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent( 3509): NetworkAgent: NetworkAgent channel lost
I/WifiTrafficPoller( 3509): evaluateTrafficStatsPolling
I/wpa_supplicant( 3824): Scan requested (ret=0) - scan timeout 30 seconds
,D/SecContentProvider2( 3509): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3509): mCursor = null
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/SmartBondingService( 3509): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
,D/Tethering( 3509): MasterInitialState.processMessage what=3
D/SmartBondingService( 3509): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3509): getSBEnabled() enabled =false
D/SmartBondingService( 3509): getSBEnabled() enabled =false
D/SmartBondingService( 3509): getSBEnabled() enabled =false
V/NetworkStats( 3509): updateIfacesLocked()
D/NtpTrustedTime( 3509): currentTimeMillis() cache hit
V/NetworkStats( 3509): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 3509): UpdateStatsForKnox
D/SmartBondingService( 3509): getNetworkEnabled : wifi : true mobile : false
D/NtpTrustedTime( 3509): currentTimeMillis() cache hit
V/NetworkStats( 3509): performPollLocked() took 4ms
D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3692): updateDataNetType()
V/NetworkStats( 3509): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/StatusBar.NetworkController( 3692): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3692): updateLTEICONDataNetType:0
D/NtpTrustedTime( 3509): currentTimeMillis() cache hit
D/NtpTrustedTime( 3509): currentTimeMillis() cache hit
D/NtpTrustedTime( 3509): currentTimeMillis() cache hit
D/NtpTrustedTime( 3509): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 3692): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3692): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3692): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
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
,E/WifiStateMachine( 3509): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3509): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine( 3509): setDetailed state send new extra info"NG700"
I/Hs20UtilService( 4110): Starting #9
I/Hs20UtilService( 4110): Message received 5007
D/SecContentProvider2( 3509): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3509): mCursor = null
,D/NtpTrustedTime( 3509): currentTimeMillis() cache hit
D/NtpTrustedTime( 3509): currentTimeMillis() cache hit
,D/NearbySettings( 8852): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8852): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8852): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8852): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8852): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8852): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8852): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11499): NETWORK_STATE_CHANGED_ACTION
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/ConnectivityService( 3509): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 3509): updateDataUsageMap
I/ApplicationPolicy( 3509): updateDataUsageMap  idList is null 
,D/SmartBondingService( 3509): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3509): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3509): getSBEnabled() enabled =false
D/SmartBondingService( 3509): getSBEnabled() enabled =false
D/SmartBondingService( 3509): getSBEnabled() enabled =false
D/GpsLocationProvider( 3509): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/SLocation( 3509): No Active Data Connection
D/SmartBondingService( 3509): getNetworkEnabled : wifi : true mobile : false
,I/DBG_DM  ( 6325): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/DBG_DM  ( 6325): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11999): MountEmulatedStorage()
E/Zygote  (11999): v2
I/libpersona(11999): KNOX_SDCARD checking this for 10110
I/libpersona(11999): KNOX_SDCARD not a persona
,I/SELinux (11999): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11999): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11999): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3509): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.iorg.vpn.cleanup.NetworkStateMonitor: pid=11999 uid=10110 gids={50110, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11999): TimaSignature is unavailable
,D/ActivityThread(11999): Added TimaKeyStore provider
,D/ResourcesManager(11999): creating new AssetManager and set to /data/app/com.facebook.appmanager-2/base.apk
,D/ACRA    (11999): ACRA is enabled for com.facebook.appmanager, intializing...
,I/DexLibLoader(11999): not using cross-dex optimization: ART in use
,I/art     (11999): Thread[1,tid=11999,WaitingForJniOnLoad,Thread*=0xb4e08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/app/com.facebook.appmanager-2/lib/arm/libfbjni.so"
,V/DexLibLoader(11999): about to lock: /data/data/com.facebook.appmanager/mdex_lock
,V/DexLibLoader(11999): locking /data/data/com.facebook.appmanager/mdex_lock took 0 ms
V/DexLibLoader(11999): Secondary program dex metadata: classes2.dex 29f80981f469a774a4884b3db2df17e0be227159 secondary.dex01.Canary
,D/DexLibLoader(11999): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex" is valid
D/DexLibLoader(11999): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex_opt" is valid
,W/art     (11999): Attempt to remove local handle scope entry from IRT, ignoring
,D/DexLibLoader(11999): loading pre-built fallback odex files
V/MultiDexClassLoader(11999): installing MultiDexClassLoader before application classloader
D/DexLibLoader(11999): released odex store lock
D/DexLibLoader(11999): DexLibLoader.loadAll took 17 ms
,W/ca      (11999): Verify
,W/LightSharedPreferencesImpl(11999): Failed to load preference file from Disk!
W/LightSharedPreferencesImpl(11999): java.io.FileNotFoundException: /data/data/com.facebook.appmanager/app_light_prefs/com.facebook.appmanager/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11999): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/LightSharedPreferencesImpl(11999): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/LightSharedPreferencesImpl(11999): 	at com.facebook.crudolib.b.k.a(LightSharedPreferencesStorage.java:56)
W/LightSharedPreferencesImpl(11999): 	at com.facebook.crudolib.b.g.run(LightSharedPreferencesImpl.java:61)
W/LightSharedPreferencesImpl(11999): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/LightSharedPreferencesImpl(11999): 	at com.facebook.common.executors.dj.run(WrappingExecutorService.java:77)
W/LightSharedPreferencesImpl(11999): 	at com.facebook.common.executors.u.run(DefaultConstrainedListeningExecutorService.java:327)
W/LightSharedPreferencesImpl(11999): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/LightSharedPreferencesImpl(11999): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/LightSharedPreferencesImpl(11999): 	at com.facebook.common.executors.cc.run(NamedThreadFactory.java:42)
W/LightSharedPreferencesImpl(11999): 	at java.lang.Thread.run(Thread.java:818)
W/LightSharedPreferencesImpl(11999): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11999): 	at libcore.io.Posix.open(Native Method)
W/LightSharedPreferencesImpl(11999): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/LightSharedPreferencesImpl(11999): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/LightSharedPreferencesImpl(11999): 	... 10 more
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/Zygote  (12024): MountEmulatedStorage()
E/Zygote  (12024): v2
I/libpersona(12024): KNOX_SDCARD checking this for 1000
I/libpersona(12024): KNOX_SDCARD not a persona
I/SELinux (12024): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12024): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3509): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=12024 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (12024): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3509): Killing 11017:com.android.mms/u0a52 (adj 15): bgCount ##31
W/appmanager(:<default>):b(11999): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
W/appmanager(:<default>):b(11999): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/TimaKeyStoreProvider(12024): TimaSignature is unavailable
,D/ActivityThread(12024): Added TimaKeyStore provider
,D/ResourcesManager(12024): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,W/appmanager(:<default>):QuickExperimentControllerImpl(11999): Exposure of experiment com.facebook.common.network.l@2358249b occurred when no user was logged in
,W/BroadcastQueue( 3509): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{154fa4c5 u0 ReceiverList{39817f3c 11999 com.facebook.appmanager/10110/u0 remote:6b6ed2f}}
,W/BroadcastQueue( 3509): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{154fa4c5 u0 ReceiverList{39817f3c 11999 com.facebook.appmanager/10110/u0 remote:6b6ed2f}}
I/PCWCLIENTTRACE_LOG(12024): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(12024): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(12024): new DMDBOpenHelper instance
,D/CountryDetector( 3509): No listener is left
,I/PCWCLIENTTRACE_PushUtil(12024): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(12024): sales region : global
I/PCWCLIENTTRACE_PushUtil(12024): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(12024): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver(12024): noConnectivity : true
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12054): MountEmulatedStorage()
I/libpersona(12054): KNOX_SDCARD checking this for 10135
E/Zygote  (12054): v2
I/libpersona(12054): KNOX_SDCARD not a persona
,I/SELinux (12054): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12054): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3509): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=12054 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (12054): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3509): Killing 11101:com.policydm/1000 (adj 15): bgCount ##31
,W/BroadcastQueue( 3509): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{280f3e79 u0 ReceiverList{2c455f40 11999 com.facebook.appmanager/10110/u0 remote:3785fac3}}
,D/TimaKeyStoreProvider(12054): TimaSignature is unavailable
,D/ActivityThread(12054): Added TimaKeyStore provider
,D/ResourcesManager(12054): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/MusicStore(12054): Database version: 104
,D/ResourcesManager(12054): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(12054): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(12054): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (12054): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(12054): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (12054): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@143691c1: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(12054): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(12054): GMSCore installation verified
,E/Vold    ( 2827): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2827): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11999): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
I/ConfigStore(12054): Config Database version: 1
,E/Vold    ( 2827): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/ContextImpl(11999): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
W/Vold    ( 2827): Returning OperationFailed - no handler for errno 0
,W/appmanager(:<default>):QuickExperimentControllerImpl(11999): Exposure of experiment com.facebook.imagepipeline.a.g@6bd09b8 occurred when no user was logged in
,W/appmanager(:<default>):QuickExperimentControllerImpl(11999): Exposure of experiment com.facebook.imagepipeline.a.d@1829a7cd occurred when no user was logged in
,E/Vold    ( 2827): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/ContextImpl(12054): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
W/Vold    ( 2827): Returning OperationFailed - no handler for errno 0
,I/art     (11999): Explicit concurrent mark sweep GC freed 47374(2MB) AllocSpace objects, 6(96KB) LOS objects, 22% free, 27MB/35MB, paused 723us total 22.211ms
,W/appmanager(:<default>):m(11999): No feature status reporters found; is this dead code?
,E/Vold    ( 2827): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2827): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12054): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2827): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2827): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12054): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter( 3509): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3509): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3509): getStreamVolume 3 index 0
,I/MediaRouter(12054): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12084): MountEmulatedStorage()
I/libpersona(12084): KNOX_SDCARD checking this for 10002
E/Zygote  (12084): v2
I/libpersona(12084): KNOX_SDCARD not a persona
,I/SELinux (12084): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12084): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12084): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3509): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=12084 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/WifiDisplayAdapter( 3509): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/wpa_supplicant( 3824): nl80211: Received scan results (4 BSSes)
,I/wpa_supplicant( 3824): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3824): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3824): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 3824): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
E/WifiStateMachine( 3509): [1,454,527,996,382 ms] noteScanEnd no scan source
,I/NetworkMonitor(12054): type=WIFI subType= reason=null isConnected=false
,D/TimaKeyStoreProvider(12084): TimaSignature is unavailable
D/ActivityThread(12084): Added TimaKeyStore provider
,E/WifiStateMachine( 3509): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@1487ec sup_state=SCANNING debouncing=false
,E/WifiStateMachine( 3509): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3509): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3509): setDetailed state send new extra info
,I/ActivityManager( 3509): Killing 11118:com.sec.android.app.myfiles/u0a53 (adj 15): bgCount ##31
,D/SecContentProvider2( 3509): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3509): mCursor = null
,E/lowmemorykiller( 2825): Error writing /proc/11118/oom_score_adj; errno=22
,D/ResourcesManager(12084): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager( 3509): Killing 11135:com.sec.android.provider.badge/u0a82 (adj 13): bgCount ##31
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12102): MountEmulatedStorage()
I/libpersona(12102): KNOX_SDCARD checking this for 1000
E/Zygote  (12102): v2
I/libpersona(12102): KNOX_SDCARD not a persona
I/SELinux (12102): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12102): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12102): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3509): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=12102 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/art     ( 2876): Explicit concurrent mark sweep GC freed 8736(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 553us total 10.890ms
,I/wpa_supplicant( 3824): wlan0: State: ASSOCIATING -> ASSOCIATED
,I/wpa_supplicant( 3824): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/art     ( 2876): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 277us total 9.036ms
,I/wpa_supplicant( 3824): Associated with C0.AA.48
,E/WifiStateMachine( 3509): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3509): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3509): setDetailed state send new extra info"NG700"
,I/art     ( 2876): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 334us total 7.604ms
D/SecContentProvider2( 3509): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3509): mCursor = null
,D/TimaKeyStoreProvider(12102): TimaSignature is unavailable
,D/ActivityThread(12102): Added TimaKeyStore provider
,I/wpa_supplicant( 3824): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 3824): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3509): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3509): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,D/SecContentProvider2( 3509): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3509): mCursor = null
,I/art     ( 3509): Explicit concurrent mark sweep GC freed 59651(3MB) AllocSpace objects, 48(768KB) LOS objects, 24% free, 49MB/65MB, paused 5.323ms total 91.875ms
,D/ResourcesManager(12102): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/wpa_supplicant( 3824): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 3824): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 3824): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3509): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3509): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,I/wpa_supplicant( 3824): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3824): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 3824): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 3824): Blacklist: Clear (temp) 
I/wpa_supplicant( 3824): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,I/DIAGMON_AGENT(12102): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
E/WifiStateMachine( 3509): Network connection established
,D/WifiNative-HAL( 3509): callSECApiVoid - ID [50]
,E/WifiStateMachine( 3509): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
E/WifiStateMachine( 3509): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService( 3509): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine( 3509): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3509): L2ConnectedState "NG700" nid=0
E/WifiConfigStore( 3509): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService( 3509): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 3509): updateNetworkInfo()
D/ConnectivityService( 3509): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3509): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine( 3509): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3509): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3509): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener( 2844): Setting iface cfg
,E/WifiStateMachine( 3509): Start Dhcp Watchdog 2
,D/SecContentProvider2( 3509): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3509): mCursor = null
,E/WifiStateMachine( 3509): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3509): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/DIAGMON_AGENT(12102): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT(12102): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT(12102): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(12102): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,E/WifiStateMachine( 3509): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3509): do suspend false
,D/SecContentProvider2( 3509): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3509): mCursor = null
E/Zygote  (12120): MountEmulatedStorage()
I/libpersona(12120): KNOX_SDCARD checking this for 10012
E/Zygote  (12120): v2
I/libpersona(12120): KNOX_SDCARD not a persona
I/SELinux (12120): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/WifiP2pService( 3509): InactiveState{ what=143375 }
D/WifiP2pService( 3509): P2pEnabledState{ what=143375 }
,I/SELinux (12120): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12120): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3509): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=12120 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12120): TimaSignature is unavailable
,D/ActivityThread(12120): Added TimaKeyStore provider
,D/ResourcesManager(12120): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager( 3509): Killing 10984:com.google.android.apps.docs/u0a101 (adj 15): bgCount ##31
,I/FOTA_Client(12120): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(12120): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(12120): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12136): MountEmulatedStorage()
I/libpersona(12136): KNOX_SDCARD checking this for 10021
E/Zygote  (12136): v2
I/libpersona(12136): KNOX_SDCARD not a persona
,I/SELinux (12136): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12136): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12136): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3509): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=12136 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
I/ActivityManager( 3509): Killing 11182:com.sec.spp.push/u0a39 (adj 15): bgCount ##31
,E/lowmemorykiller( 2825): Error writing /proc/11182/oom_score_adj; errno=22
,D/TimaKeyStoreProvider(12136): TimaSignature is unavailable
,D/ActivityThread(12136): Added TimaKeyStore provider
,D/ResourcesManager(12136): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.521: (12136): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Feb 03 20:33:16 GMT+01:00 2016
,I/KLMS-2.4.521: (12136): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (12136): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12136): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (12136): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (12136): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12136): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (12136): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.521: (12136): StateImplV2(): networkChangeListener().END
,E/Zygote  (12153): MountEmulatedStorage()
I/libpersona(12153): KNOX_SDCARD checking this for 10038
E/Zygote  (12153): v2
I/libpersona(12153): KNOX_SDCARD not a persona
,I/SELinux (12153): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12153): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12153): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3509): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=12153 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/KLMS-2.4.521: (12136): KLMSIntentService(): onDestroy()
,I/ActivityManager( 3509): Killing 11199:com.sec.android.app.soundalive/u0a59 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12153): TimaSignature is unavailable
,D/ActivityThread(12153): Added TimaKeyStore provider
,D/ResourcesManager(12153): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT(12153): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12168): MountEmulatedStorage()
E/Zygote  (12168): v2
I/libpersona(12168): KNOX_SDCARD checking this for 1000
I/libpersona(12168): KNOX_SDCARD not a persona
,I/SELinux (12168): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12168): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12168): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3509): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=12168 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 3509): Killing 11215:com.wsomacp/u0a28 (adj 15): bgCount ##31
,E/dhcpcd  (12175): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (12175): version 5.5.6 starting
,E/dhcpcd  (12175): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,D/TimaKeyStoreProvider(12168): TimaSignature is unavailable
,D/ActivityThread(12168): Added TimaKeyStore provider
,D/ResourcesManager(12168): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,I/dhcpcd  (12175): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (12175): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (12175): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  (12175): bssid match
I/dhcpcd  (12175): wlan0: rebinding lease of 192.168.1.124
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12195): MountEmulatedStorage()
,E/Zygote  (12195): v2
I/libpersona(12195): KNOX_SDCARD checking this for 10039
I/libpersona(12195): KNOX_SDCARD not a persona
I/SELinux (12195): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12195): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3509): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=12195 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (12195): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3509): Killing 11268:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12195): TimaSignature is unavailable
,D/ActivityThread(12195): Added TimaKeyStore provider
,D/ResourcesManager(12195): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService(12195): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(12195): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService(12195): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,D/SPPClientService(12195): PushLog.txt file is not deleted.
D/SPPClientService(12195): PushLog.txt file is not deleted.
D/SPPClientService(12195): ============PushLog. stop!
,I/SA      (11346): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11346): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      (11346): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (11346): [SLFUCHKMGR] constructor called
,E/SPPClientService(12195): [[SystemStateMonitorService]] No Active Internet
,I/SA      (11346): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11346): [OR] == isSIMCardReady false ==
,I/SA      (11346): [SCU] == networkStateCheck == false
I/SA      (11346): [OR] onReceive END
,I/ActivityManager( 3509): Killing 11237:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
,V/DownloadManager( 5507): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12215): MountEmulatedStorage()
I/libpersona(12215): KNOX_SDCARD checking this for 10067
E/Zygote  (12215): v2
I/libpersona(12215): KNOX_SDCARD not a persona
,I/SELinux (12215): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12215): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12215): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3509): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=12215 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12215): TimaSignature is unavailable
,D/ActivityThread(12215): Added TimaKeyStore provider
,D/ResourcesManager(12215): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/sCloudBackupApp(12215): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(12215): Other Intent
,I/ActivityManager( 3509): Killing 11167:com.sec.android.automotive.drivelink/u0a102 (adj 13): bgCount ##31
,D/accuweather( 5118): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3775): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,D/accuweather( 5118): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5118): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
,D/accuweather( 5118): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5118): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5118): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5118): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12231): MountEmulatedStorage()
I/libpersona(12231): KNOX_SDCARD checking this for 1000
E/Zygote  (12231): v2
I/libpersona(12231): KNOX_SDCARD not a persona
,I/SELinux (12231): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12231): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12231): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3509): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=12231 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12231): TimaSignature is unavailable
,D/ActivityThread(12231): Added TimaKeyStore provider
,D/ResourcesManager(12231): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(12231): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro(12231): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro(12231): premStatus:2
,I/KnoxUsageLogPro(12231): isEulaShown : false
I/KnoxUsageLogPro(12231): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12246): MountEmulatedStorage()
I/libpersona(12246): KNOX_SDCARD checking this for 10090
E/Zygote  (12246): v2
I/libpersona(12246): KNOX_SDCARD not a persona
I/SELinux (12246): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12246): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12246): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3509): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=12246 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3509): Killing 11252:com.samsung.android.sdk.samsunglink/u0a42 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12246): TimaSignature is unavailable
,D/ActivityThread(12246): Added TimaKeyStore provider
,D/ResourcesManager(12246): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12262): MountEmulatedStorage()
I/libpersona(12262): KNOX_SDCARD checking this for 10127
E/Zygote  (12262): v2
I/libpersona(12262): KNOX_SDCARD not a persona
,I/SELinux (12262): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12262): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12262): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3509): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=12262 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3509): Killing 11329:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12262): TimaSignature is unavailable
D/ActivityThread(12262): Added TimaKeyStore provider
D/ResourcesManager(12262): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
D/KeyguardWallpaperUpdator(12262): cancelUpdateWallpaper
D/KeyguardWallpaperUpdator(12262): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12262): stopCheckCategoryVersion
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12278): MountEmulatedStorage()
I/libpersona(12278): KNOX_SDCARD checking this for 10136
E/Zygote  (12278): v2
I/libpersona(12278): KNOX_SDCARD not a persona
I/SELinux (12278): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12278): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12278): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3509): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=12278 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3509): Killing 11364:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12278): TimaSignature is unavailable
,D/ActivityThread(12278): Added TimaKeyStore provider
,D/ResourcesManager(12278): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Vold    ( 2827): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2827): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12278): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2827): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2827): Returning OperationFailed - no handler for errno 0
W/ContextImpl(12278): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    ( 2827): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2827): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12278): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2827): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl(12278): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    ( 2827): Returning OperationFailed - no handler for errno 0
,I/WebViewFactory(12278): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(12278): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(12278): Loading: webviewchromium
,I/LibraryLoader(12278): Time to load native libraries: 3 ms (timestamps 245-248)
I/LibraryLoader(12278): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(12278): Binding Chromium to main looper Looper (main, tid 1) {18d988fd}
,I/LibraryLoader(12278): Expected native library version number "",actual native library version number ""
,I/chromium(12278): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(12278): Initializing chromium process, renderers=0
,W/art     (12278): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(12278): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(12278): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium(12278): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,W/AudioManagerAndroid(12278): Requires BLUETOOTH permission
,I/NSApplication(12278): Starting up...
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12346): MountEmulatedStorage()
I/libpersona(12346): KNOX_SDCARD checking this for 10150
E/Zygote  (12346): v2
I/libpersona(12346): KNOX_SDCARD not a persona
,I/SELinux (12346): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12346): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12346): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3509): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=12346 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager( 3509): Killing 11312:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
,I/art     ( 2876): Explicit concurrent mark sweep GC freed 8753(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 379us total 10.321ms
,D/TimaKeyStoreProvider(12346): TimaSignature is unavailable
,D/ActivityThread(12346): Added TimaKeyStore provider
,I/art     ( 2876): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 671us total 8.700ms
,D/ResourcesManager(12346): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(12346): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12346): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager(12346): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/art     ( 2876): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 259us total 8.058ms
,D/QuickConnect(12346): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12346): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect(12346): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12361): MountEmulatedStorage()
E/Zygote  (12361): v2
I/libpersona(12361): KNOX_SDCARD checking this for 10178
I/libpersona(12361): KNOX_SDCARD not a persona
,I/SELinux (12361): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12361): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12361): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3509): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=12361 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager( 3509): Killing 11382:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12361): TimaSignature is unavailable
,D/ActivityThread(12361): Added TimaKeyStore provider
,D/ResourcesManager(12361): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(12361): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager(12361): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12361): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12361): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12361): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12361): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService( 3509): exchangeData() failure , invalid userId
,D/RCPManagerService( 3509): exchangeData() failure , invalid userId
,D/RCPManagerService( 3509): exchangeData() failure , invalid userId
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 3509): exchangeData() failure , invalid userId
,D/RCPManagerService( 3509): exchangeData() failure , invalid userId
E/Zygote  (12384): MountEmulatedStorage()
I/libpersona(12384): KNOX_SDCARD checking this for 10082
E/Zygote  (12384): v2
I/libpersona(12384): KNOX_SDCARD not a persona
I/SELinux (12384): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12384): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12384): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3509): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=12384 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12384): TimaSignature is unavailable
,D/ActivityThread(12384): Added TimaKeyStore provider
,D/RCPManagerService( 3509): exchangeData() failure , invalid userId
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(12384): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,E/Zygote  (12400): MountEmulatedStorage()
E/Zygote  (12400): v2
I/libpersona(12400): KNOX_SDCARD checking this for 1000
I/libpersona(12400): KNOX_SDCARD not a persona
,I/SELinux (12400): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12400): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12400): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3509): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=12400 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/BadgeProvider(12384): onCreate
D/BadgeProvider(12384): DatabaseHelper
,I/ActivityManager( 3509): Killing 11522:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##31
,I/ActivityManager( 3509): Killing 11398:com.samsung.helphub/1000 (adj 13): bgCount ##32
,D/BadgeProvider(12384): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/TimaKeyStoreProvider(12400): TimaSignature is unavailable
,D/ActivityThread(12400): Added TimaKeyStore provider
,D/BadgeProvider(12384): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12384): sendNotify, [notify] : null
D/BadgeProvider(12384): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12384): update, [BadgeCount] : badgecount=0
D/BadgeProvider(12384): update, [UpdateCount] : 1
,D/Launcher.Model( 4001): reloadBadges entered.
,D/ResourcesManager(12400): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,I/ActivityManager( 3509): Killing 11540:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
,W/ActivityManager( 3509): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/iu.Environment( 6828): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 6828): num queued entries: 0
,I/iu.UploadsManager( 6828): num updated entries: 0
I/iu.SyncManager( 6828): NEXT; no task
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12418): MountEmulatedStorage()
I/libpersona(12418): KNOX_SDCARD checking this for 10013
E/Zygote  (12418): v2
I/libpersona(12418): KNOX_SDCARD not a persona
,I/SELinux (12418): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12418): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3509): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=12418 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux (12418): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12418): TimaSignature is unavailable
,D/ActivityThread(12418): Added TimaKeyStore provider
,D/ResourcesManager(12418): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,I/ActivityManager( 3509): Killing 11559:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##31
,I/Hs20UtilService( 4110): Starting #10
,I/Hs20UtilService( 4110): Message received 5007
,D/NearbySettings( 8852): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8852): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8852): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 8852): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8852): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8852): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8852): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11499): NETWORK_STATE_CHANGED_ACTION
,I/dhcpcd  (12175): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
,I/dhcpcd  (12175): wlan0: leased 192.168.1.124 for 86400 seconds
,E/WifiStateMachine( 3509): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3509): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,I/jxcore-log(11895): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log(11895): 
,E/WifiStateMachine( 3509): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine( 3509): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  ( 3509): do suspend true
,D/WifiP2pService( 3509): InactiveState{ what=143375 }
,D/WifiP2pService( 3509): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 3509): WifiStateMachine DHCP successful
,E/WifiStateMachine( 3509): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3509): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine( 3509): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3509): Not connected state, yet.
E/WifiStateMachine( 3509): VerifyingLinkState enter
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiStateMachine( 3509): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine( 3509): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3509): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3509): callSECApiInt - ID [210]
E/WifiStateMachine( 3509): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
E/ConnectivityService( 3509): updateNetworkInfo()
,D/ConnectivityService( 3509): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 3509): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 3509): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 3509): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 3509): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 3509): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3509): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
,I/Hs20UtilService( 4110): Starting #11
,I/Hs20UtilService( 4110): Message received 5007
,D/NearbySettings( 8852): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,D/ConnectivityService( 3509): Adding Route [fe80::/64 -> :: wlan0] to network 503
D/ConnectivityService( 3509): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
I/NearbySettings( 8852): MountReceiver.onReceive - Keep current state
,D/ConnectivityService( 3509): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService( 3509): Unexpected mtu value: 0, wlan0
,V/        ( 2844): QcRouteController
,I/SignOutReceiver(11499): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2844): QcRouteController
,E/WifiStateMachine( 3509): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine( 3509): Now, connected state.
E/WifiStateMachine( 3509): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/WifiStateMachine( 3509): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/WifiTrafficPoller( 3509): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
,V/        ( 2844): QcRouteController
,I/Hs20UtilService( 4110): Starting #12
I/Hs20UtilService( 4110): Message received 5007
,I/WifiTrafficPoller( 3509): evaluateTrafficStatsPolling
,D/WifiNative-HAL( 3509): callSECApiVoid - ID [212]
E/WifiStateMachine( 3509): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,V/        ( 2844): QcRouteController
,E/WifiStateMachine( 3509): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
I/WifiStateMachine( 3509): REQUEST_POWER_SAVE_ON
,D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/NearbySettings( 8852): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8852): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8852): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
V/        ( 2844): QcRouteController
I/NearbySettings( 8852): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8852): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8852): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8852): MountReceiver.mPrefHandler - 7002
,V/        ( 2844): QcRouteController
,V/        ( 2844): QcRouteController
,I/SignOutReceiver(11499): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2844): QcRouteController,
I/Hs20UtilService( 4110): Starting #13
,I/Hs20UtilService( 4110): Message received 5007
,D/NearbySettings( 8852): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8852): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine( 3509): callSECApi what=220
D/WifiStateMachine( 3509): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/SignOutReceiver(11499): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService( 3509): Setting Dns servers for network 503 to [/192.168.1.1]
,D/ConnectivityService( 3509): LTETest block dns file not exists
,D/ConnectivityService( 3509): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,E/ConnectivityService( 3509): updateNetworkInfo()
D/ConnectivityService( 3509): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3509): updateNetworkInfo()
D/ConnectivityService( 3509): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3509): rematching NetworkAgentInfo [WIFI () - 503]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3509): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3509): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3509): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3509): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService( 3509):    accepting network in place of null
,D/TelephonyNetworkFactory( 3982): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker( 3509): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 3509): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 3509): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService( 3509): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/Tethering( 3509): MasterInitialState.processMessage what=3
,D/ConnectivityService( 3509): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
I/System.out( 3509): (HTTPLog)-Static: isSBSettingEnabled false
D/ConnectivityManager.CallbackHandler( 6828): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 3692): CM callback handler got msg 524290
D/SmartBondingService( 3509): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService( 3509): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3509): getSBEnabled() enabled =false
D/SmartBondingService( 3509): getSBEnabled() enabled =false
D/EnterpriseController( 2844): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2844): getNetworkForDns: using netid 503 for uid 1000
D/SmartBondingService( 3509): getSBEnabled() enabled =false
,V/NetworkStats( 3509): updateIfacesLocked()
D/NtpTrustedTime( 3509): currentTimeMillis() cache hit
V/NetworkStats( 3509): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 3509): UpdateStatsForKnox
,D/SmartBondingService( 3509): getNetworkEnabled : wifi : true mobile : false
,D/NtpTrustedTime( 3509): currentTimeMillis() cache hit
,I/SurfaceFlinger( 2848): id=14 createSurf (1x1),1 flag=4, Uoast
D/NtpTrustedTime( 3509): currentTimeMillis() cache hit
D/NtpTrustedTime( 3509): currentTimeMillis() cache hit
D/NtpTrustedTime( 3509): currentTimeMillis() cache hit
V/NetworkStats( 3509): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 3509): currentTimeMillis() cache hit
V/NetworkStats( 3509): performPollLocked() took 5ms
,D/NtpTrustedTime( 3509): currentTimeMillis() cache hit
D/NtpTrustedTime( 3509): currentTimeMillis() cache hit
,D/PowerManagerService( 3509): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3509
,D/mali_winsys( 3692): new_window_surface returns 0x3000,  [1120x201]-format:1
,D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3692): updateDataNetType()
D/StatusBar.NetworkController( 3692): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3692): updateLTEICONDataNetType:0
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
I/System.out( 3509): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3509): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 03 Feb 2016 19:33:18 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454527998625], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454527998610]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3509): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3509): Validated
,D/ConnectivityService( 3509): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3509): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3509): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 3509): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3509): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 3692): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 6828): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3692): updateDataNetType()
D/StatusBar.NetworkController( 3692): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3692): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3692): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3692): updateTelephonySignalStrength: hasService=false ss=null
,D/StatusBar.NetworkController( 3692): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,I/jxcore-log(11895): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log(11895): 
,I/jxcore-log(11895): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log(11895): 
,I/jxcore-log(11895): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log(11895): 
,I/jxcore-log(11895): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log(11895): 
,I/jxcore-log(11895): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log(11895): 
I/jxcore-log(11895): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log(11895): 
I/jxcore-log(11895): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log(11895): 
,E/WifiStateMachine( 3509): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3509): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService( 3509): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
V/        ( 2844): QcRouteController
D/SmartBondingService( 3509): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
D/SmartBondingService( 3509): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3509): getSBEnabled() enabled =false
D/SmartBondingService( 3509): getSBEnabled() enabled =false
D/SmartBondingService( 3509): getSBEnabled() enabled =false
V/        ( 2844): QcRouteController
W/NetworkManagementService( 3509): route cmd failed: 
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
D/ConnectivityManager.CallbackHandler( 3692): CM callback handler got msg 524295
D/ConnectivityService( 3509): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 3692): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 6828): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 6828): CM callback handler got msg 524295
D/ConnectivityService( 3509): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3509): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3509): SmartBondingReceiver: wifi is connected
D/SmartBondingService( 3509): SmartBondingReceiver: wifi ap is not changed
D/SmartBondingService( 3509): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3509): getSBEnabled() enabled =false
D/SmartBondingService( 3509): getSBEnabled() enabled =false
D/SmartBondingService( 3509): getSBEnabled() enabled =false
D/GpsLocationProvider( 3509): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3509): getNetworkEnabled : wifi : true mobile : false
I/DBG_DM  ( 6325): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 6325): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
I/NetworkMonitor(12054): type=WIFI subType= reason=null isConnected=true
W/ResourceType( 5399): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5399): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
I/PCWCLIENTTRACE_PushUtil(12024): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(12024): sales region : global
I/PCWCLIENTTRACE_PushUtil(12024): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(12024): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(12102): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(12102): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
D/SecContentProvider2( 3509): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3509): mCursor = null
I/FOTA_Client(12120): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
I/FOTA_Client(12120): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
I/FOTA_Client(12120): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
I/KLMS-2.4.521: (12136): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Feb 03 20:33:19 GMT+01:00 2016
I/KLMS-2.4.521: (12136): KLMSAbstractReciever(): onReceive().END.
I/KLMS-2.4.521: (12136): KLMSIntentService(): onCreate()
I/KLMS-2.4.521: (12136): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.4.521: (12136): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/KLMS-2.4.521: (12136): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/KLMS-2.4.521: (12136): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
I/KLMS-2.4.521: (12136): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
I/SO_AGENT(12153): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
I/KLMS-2.4.521: (12136): StateImplV2(): networkChangeListener().START
I/KLMS-2.4.521: (12136): NetworkChangeOperations(): uploadRequestLog().START 
I/KLMS-2.4.521: (12136): NetworkChangeOperations(): uploadRequestLog().END 
I/KLMS-2.4.521: (12136): StateImplV2(): networkChangeListener().END
I/KLMS-2.4.521: (12136): KLMSIntentService(): onDestroy()
E/SPPClientService(12195): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
I/SA      (11346): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
I/SA      (11346): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (11346): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      (11346): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11346): [OR] == isSIMCardReady false ==
I/SA      (11346): [SCU] == networkStateCheck == true
I/SA      (11346): [DM] getCountryCodeFromCSC : PL
I/SA      (11346): isChinaCountryCode : false
I/SA      (11346): [SCU] is ChinestModel Data Restricted   : false
I/SA      (11346): [OR] == networkStateCheck true ==
I/SA      (11346): [OR] GetMyCountryZoneTask
I/SA      (11346): [OR] onReceive END
I/SA      (11346): [SRS] prepareGetMyCountryZone
I/SA      (11346): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11346): [SSP] query invoked
V/DownloadManager( 5507): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
I/SA      (11346): [TPMU] GetMccFromDB : null
I/SA      (11346): [SCU] getMccFromPreferece mcc = 260
I/SA      (11346): [TPM] isNoProxy(default) : true
I/SCloudBackupReceiver(12215): Other Intent
D/accuweather( 5118): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/daemonapp( 3775): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 6
D/accuweather( 5118): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5118): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5118): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5118): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
D/accuweather( 5118): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/accuweather( 5118): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
I/KnoxUsageLogPro(12231): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro(12231): premStatus:2
I/KnoxUsageLogPro(12231): isEulaShown : false
I/KnoxUsageLogPro(12231): KnoxUsageReceiver onReceive : not Processible, just return
D/KeyguardWallpaperUpdator(12262): cancelUpdateWallpaper
D/KeyguardWallpaperUpdator(12262): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12262): stopCheckCategoryVersion
D/QuickConnect(12346): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect(12346): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect(12346): PeriphStartReceiver.onReceive - no need to start
D/RCPManagerService( 3509): exchangeData() failure , invalid userId
D/RCPManagerService( 3509): exchangeData() failure , invalid userId
I/iu.Environment( 6828): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 6828): num queued entries: 0
I/iu.UploadsManager( 6828): num updated entries: 0
I/iu.SyncManager( 6828): NEXT; no task
D/WaitQueueForNetworkActivate(12418): notifyNetworkActivated
D/EnterpriseController( 2844): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2844): getNetworkForDns: using netid 503 for uid 10014
W/ContextImpl(12418): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
W/ActivityManager( 3509): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
D/hcjo    (12418): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine(12418): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12418): exit::IDLE
D/InitializeManagerStateMachine(12418): entry::NETWORK_CHECK
D/InitializeManagerStateMachine(12418): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12418): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12418): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12418): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12418): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12418): entry::SUCCESS
D/hcjo    (12418): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    (12418): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12418): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine(12418): exit::SUCCESS
D/InitializeManagerStateMachine(12418): entry::IDLE
I/SA      (11346): [RC New] Execute method=[GET] start
I/SA      (11346): [RC New] Security=[true]
I/System.out(11346): Thread-1555(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out(11346): Thread-1555(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11346): Thread-1555(ApacheHTTPLog):isShipBuild true
I/System.out(11346): Thread-1555(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/EnterpriseController( 2844): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2844): getNetworkForDns: using netid 503 for uid 10045
,I/PhenotypeConfigurator( 4647): Scheduling Phenotype for one-off execution 7729 seconds from now (1454527999549)
,D/ConnectivityService( 3509): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/GetConfigurationSnapshotOperation( 4647): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 4647): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 4647): Using platform SSLCertificateSocketFactory
,D/LocationManagerService( 3509): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 4647): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4647): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 4647): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 4647): (HTTPLog)-Static: isShipBuild true
I/System.out( 4647): (HTTPLog)-Thread-331-172251030: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 4647): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2844): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2844): getNetworkForDns: using netid 503 for uid 10014
,I/System.out( 4647): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 4647): Tagging socket 77 with tag 1000120100000000{268440065,0} uid -1, pid: 4647, getuid(): 10014
,I/qtaguid ( 4647): Tagging socket 81 with tag 1000120100000000{268440065,0} uid -1, pid: 4647, getuid(): 10014
,D/LocationManagerService( 3509): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 4647): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4647): Tagging socket 77 with tag 1000120100000000{268440065,0} uid -1, pid: 4647, getuid(): 10014
,D/LocationManagerService( 3509): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 4647): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 4647): Tagging socket 77 with tag 1000120100000000{268440065,0} uid -1, pid: 4647, getuid(): 10014
,D/LocationManagerService( 3509): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 4647): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4647): Tagging socket 77 with tag 1000120100000000{268440065,0} uid -1, pid: 4647, getuid(): 10014
,I/SA      (11346): [RC New] [v2liruge] api execute + 564
I/SA      (11346): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out(11346): AsyncTask #1 calls detatch()
,I/SA      (11346): [TPMU] getNetworkMcc : 
,I/SA      (11346): [SCU] saveMccToPreferece Start
I/SA      (11346): [SCU] RegionMCC : 260
I/SA      (11346): [SSP] query invoked
,E/Watchdog( 3509): !@Sync 8
,I/art     ( 3509): Explicit concurrent mark sweep GC freed 58776(3MB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 49MB/65MB, paused 1.318ms total 77.538ms
,I/SA      (11346): [TPMU] GetMccFromDB : null
I/SA      (11346): [SCU] getMccFromPreferece mcc = 260
I/SA      (11346): [SCU] saveMccToPreferece End
,I/SA      (11346): [RC New] executeRequest [v2liruge] end. 666
I/SA      (11346): [RC New] Execute end
,I/SA      (11346): [OR] GetMyCountryZoneTask mcc = 260
I/SA      (11346): [OR] GetMyCountryZoneTask Success
,D/LocationManagerService( 3509): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 4647): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 4647): Tagging socket 77 with tag 1000120100000000{268440065,0} uid -1, pid: 4647, getuid(): 10014
,D/LocationManagerService( 3509): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 4647): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 4647): Tagging socket 77 with tag 1000120100000000{268440065,0} uid -1, pid: 4647, getuid(): 10014
,I/dhcpcd  (12175): wlan0: sending IPv6 Router Solicitation
,D/WearableService( 4647): callingUid 10014, callindPid: 4647
,D/ResourcesManager(12054): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(12054): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(12054): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory(12054): Using the GMSCore's GoogleHttpClient
,D/WearableClient(12054): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(12054): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(12054): WearableClientImpl.onPostInitHandler: done
,I/MusicLeanback(12054): Conditions not met for autocaching.
I/MusicLeanback(12054): Stop autocaching.
,D/WearableClient(12054): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(12054): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils(12054): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/ActivityThread(12054): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@86585b9 that was originally bound here
E/ActivityThread(12054): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@86585b9 that was originally bound here
E/ActivityThread(12054): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(12054): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(12054): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(12054): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(12054): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(12054): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(12054): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(12054): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(12054): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(12054): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(12054): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(12054): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(12054): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(12054): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(12054): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(12054): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(12054): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(12054): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(12054): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(12054): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(12054): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(12054): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(12054): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(12054): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(12054): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/SSRM:n  ( 3509): SIOP:: AP = 280, PST = 245, CUR = 28
,I/WifiStateMachine( 3509): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine( 3509): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/jxcore-log(11895): Test app app.js loaded
I/jxcore-log(11895): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11895): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11895): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11895): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11895): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11895): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11895): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11895): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11895): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11895): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11895): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1671a7df added. We now have 1 listener(s)
,I/jxcore-log(11895): BLE advertisement is supported
I/jxcore-log(11895): 
,I/chromium(11895): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log(11895): --= Surplus to requirements =--
I/jxcore-log(11895): 
I/jxcore-log(11895): ****TEST TOOK:  ms ****
I/jxcore-log(11895): 
I/jxcore-log(11895): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(11895): 
,I/SurfaceFlinger( 2848): id=14 Removed Uoast (8/9)
,I/SurfaceFlinger( 2848): id=14 Removed Uoast (-2/9)
D/PowerManagerService( 3509): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3509) eventTime = 254888
D/PowerManagerService( 3509): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3509 (0x0)
D/PowerManagerService( 3509): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3509, ws=WorkSource{10060}) (elapsedTime=3463)
,I/GAV4    (12278): Thread[GAThread,5,main]: No campaign data found.
,D/AndroidRuntime(12522): 
D/AndroidRuntime(12522): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(12522): CheckJNI is OFF
,D/AndroidRuntime(12522): readGMSProperty: start
D/AndroidRuntime(12522): readGMSProperty: already setted!!
,D/AndroidRuntime(12522): readGMSProperty: end
D/AndroidRuntime(12522): addProductProperty: start
,E/AffinityControl(12522): AffinityControl: registerfunction enter
,D/AndroidRuntime(12522): Calling main entry com.android.commands.pm.Pm
,D/PersonaManagerService( 3509): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 3509): START PACKAGE DELETE: observer{1031232805}
D/PackageManager( 3509): pkg{<packageName>}
D/PackageManager( 3509): user{0}
D/PackageManager( 3509): caller{2000}
D/PackageManager( 3509): flags{3}
D/PersonaManagerService( 3509): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3509): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3509): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 3509): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3509): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 3509): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 3509): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 3509): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3509): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 3509): !@killApplicatoin: 10624, uninstall pkg,
I/ActivityManager( 3509): Force stopping com.test.thalitest appid=10624 user=-1: uninstall pkg
I/ActivityManager( 3509): Killing 11895:com.test.thalitest/u0a624 (adj 0): stop com.test.thalitest
,I/ActivityManager( 3509):   Force finishing activity ActivityRecord{3c217dd6 u0 com.test.thalitest/.MainActivity t26}
,W/ActivityManager( 3509): mDVFSHelper.acquire()
,W/PackageSettings( 3509): Skipping PackageSetting{1aa5e030 com.example.hello/10563} due to missing metadata
,D/BatteryService( 3509): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3509): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3509): online:4, current avg:-307, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:107
D/BatteryService( 3509): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3509): stay LED for fully charged
,I/ActivityManager( 3509): Force stopping com.test.thalitest appid=10624 user=0: pkg removed
,E/JavaBinder( 3509): !!! FAILED BINDER TRANSACTION !!!
,I/ActivityManager( 3509):   Force finishing activity ActivityRecord{3c217dd6 u0 com.test.thalitest/.MainActivity t26 f}
W/ActivityManager( 3509): Duplicate finish request for ActivityRecord{3c217dd6 u0 com.test.thalitest/.MainActivity t26 f}
,D/PointerIcon( 3509): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3509): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3509): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3509): setHoveringSpenCustomIcon IconType is same.1
,I/DBG_DM  ( 6325): [com.wssyncmldm.ui.XUIInstallConfirmActivity(456/onResume)] 
,I/WindowState( 3509): WIN DEATH: Window{e333b0c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger( 2848): id=13 Removed NainActivit (5/8)
,I/SurfaceFlinger( 2848): id=13 Removed NainActivit (-2/8)
,D/WifiService( 3509): Client connection lost with reason: 4
,I/MotionRecognitionService( 3509): Plugged
I/MotionRecognitionService( 3509): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,I/DBG_DM  ( 6325): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 11
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5646): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5646): Disconnected process message: 10
,D/ResourcesManager( 3509): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/art     ( 6828): Explicit concurrent mark sweep GC freed 25633(1470KB) AllocSpace objects, 3(48KB) LOS objects, 20% free, 31MB/39MB, paused 1.621ms total 80.226ms
,I/DBG_DM  ( 6325): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/art     ( 4056): Explicit concurrent mark sweep GC freed 30942(1916KB) AllocSpace objects, 0(0B) LOS objects, 21% free, 28MB/36MB, paused 1.183ms total 64.732ms
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/DBG_DM  ( 6325): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6325): [com.wssyncmldm.ui.XUIInstallConfirmActivity(466/onResume)] Postpone Count : 11
,I/art     ( 8893): Explicit concurrent mark sweep GC freed 26875(1540KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.405ms total 77.464ms
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/DBG_DM  ( 6325): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,I/DBG_DM  ( 6325): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/InputReader( 3509): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,E/SamsungIME( 4501): mOCRHelper is null
,W/GeofencerStateMachine( 4647): Ignoring removeGeofence because network location is disabled.
,D/LWLocationManager(11577): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(11577): getLastUiLocationId() : mLastUiLocationId = -100
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,E/Zygote  (12537): MountEmulatedStorage()
E/Zygote  (12537): v2
I/libpersona(12537): KNOX_SDCARD checking this for 10063
I/libpersona(12537): KNOX_SDCARD not a persona
,I/SELinux (12537): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12537): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3509): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=12537 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,E/SELinux (12537): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,W/ResourceType( 5399): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5399): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,I/DBG_DM  ( 6325): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/EnterpriseDeviceManagerService( 3509): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3509): Admin package name: com.google.android.gms
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3509): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,I/art     ( 3509): Explicit concurrent mark sweep GC freed 21976(1701KB) AllocSpace objects, 8(128KB) LOS objects, 24% free, 49MB/65MB, paused 2.675ms total 177.107ms
,D/TimaKeyStoreProvider(12537): TimaSignature is unavailable
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/SecContentProvider2( 3509): uri = 14 selection = getSealedState
D/SecContentProvider2( 3509): mCursor = null
D/ActivityThread(12537): Added TimaKeyStore provider
,D/ApplicationPolicy( 3509): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3509): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,I/DBG_DM  ( 6325): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 11
,D/ResourcesManager(12537): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,I/DBG_DM  ( 6325): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,D/ResourcesManager(11577): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,I/DBG_DM  ( 6325): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6325): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 6325): [llIIlIIlIllIllIlllII(376/llIIllllIIlllIIIIlll)] 
,I/DBG_DM  ( 6325): [IIlIIIlllllIIlIIIlII(339/llllIlIIIllllIIlIlll)] No need to check encryption status
,D/VRSetupWizardStub/PackageIntentReceiver(12537): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(12537): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(12537): packagename:com.test.thalitest
I/DBG_DM  ( 6325): [llIIlIIlIllIllIlllII(405/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
,D/SecContentProvider2( 3509): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 3509): mCursor = null
,D/ActivityManager( 3509): post active user change for 0
D/KnoxTimeoutHandler( 3509): postActiveUserChange for user 0
I/KLMS-2.4.521: (12136): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Feb 03 20:33:22 GMT+01:00 2016
,D/ResourcesManager(11577): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
I/DBG_DM  ( 6325): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
,I/SurfaceFlinger( 2848): id=15 createSurf (1440x2560),2 flag=404, YUIInstallC
,D/RegisteredServicesCache( 3967): empty dynamic service
,I/KLMS-2.4.521: (12136): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 3509): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3509): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,D/StatusBarManagerService( 3509): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,D/StatusBarManagerService( 3509): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/KLMS-2.4.521: (12136): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12136): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/PointerIcon( 3509): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3509): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3509): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3509): setHoveringSpenCustomIcon IconType is same.1
D/ResourcesManager(11577): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
V/ActivityThread( 6325): updateVisibility : ActivityRecord{1c5c6122 token=android.os.BinderProxy@15905997 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,E/Zygote  (12555): MountEmulatedStorage()
E/Zygote  (12555): v2
I/libpersona(12555): KNOX_SDCARD checking this for 10106
I/libpersona(12555): KNOX_SDCARD not a persona
,I/SELinux (12555): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12555): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/ResourcesManager(11577): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/ActivityManager( 3509): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=12555 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,E/SELinux (12555): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.4.521: (12136): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,I/KLMS-2.4.521: (12136): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12136): KLMSIntentService(): PACKAGE_REMOVED
,I/KLMS-2.4.521: (12136): KLMSIntentService(): listeningToPackageRemoved().START
,D/ResourcesManager(11577): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,D/InputMethodManagerService( 3509): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/KLMS-2.4.521: (12136): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,D/ResourcesManager(11577): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/ContextImpl( 3509): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/InputMethodManagerService( 3509): Got RemoteException sending setActive(false) notification to pid 11895 uid 10624
,D/ResourcesManager(11577): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/RCPManager(12231):  in createShortcut() for packageName: com.test.thalitest userId0
,I/Timeline( 6325): Timeline: Activity_idle id: android.os.BinderProxy@15905997 time:255868
,D/RCPManagerService( 3509):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3509): queryAllProviders():  providerCallBack is not register for 0
D/TimaKeyStoreProvider(12555): TimaSignature is unavailable
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,D/ActivityThread(12555): Added TimaKeyStore provider
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/PackageManager( 3509): delete codoeFile: 
,I/AASAUninstall( 3509):  com.test.thalitest not target!
,D/PackageManager( 3509): result of delete: 1{1031232805}
,D/AndroidRuntime(12522): Shutting down VM
D/ResourcesManager(11577): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,E/Zygote  (12573): MountEmulatedStorage()
I/libpersona(12573): KNOX_SDCARD checking this for 10050
E/Zygote  (12573): v2
I/libpersona(12573): KNOX_SDCARD not a persona
,I/SELinux (12573): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
I/ActivityManager( 3509): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=12573 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
D/ResourcesManager(11577): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/SELinux (12573): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12573): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,W/ActivityManager( 3509): mDVFSHelper.release()
I/Timeline( 3509): Timeline: Activity_windows_visible id: ActivityRecord{30e92574 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t24} time:255909
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(11577): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(11577): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,W/Resources( 3509): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/Books/Books.apk
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/Resources( 3509): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(11577): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,E/Zygote  (12588): MountEmulatedStorage()
E/Zygote  (12588): v2
I/libpersona(12588): KNOX_SDCARD checking this for 10183
I/libpersona(12588): KNOX_SDCARD not a persona
,I/SELinux (12588): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,W/Resources( 3509): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/Videos/Videos.apk
I/SELinux (12588): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/ResourcesManager(12555): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,E/SELinux (12588): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3509): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=12588 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12573): TimaSignature is unavailable
,D/ResourcesManager(11577): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/ActivityThread(12573): Added TimaKeyStore provider
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(11577): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/elm:14491(12555): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14491(12555): ELMEngine.ELMEngine( context ).
,D/elm:14491(12555): MDMBridge.setEnterpriseBridge()
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (12136): KLMSIntentService(): listeningToPackageRemoved().END
,D/ResourcesManager(11577): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
D/ResourcesManager(12573): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/ResourcesManager(11577): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(11577): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11577): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11577): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,W/ResourcesManager(12573): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(12573): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12573): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,E/Zygote  (12603): MountEmulatedStorage()
E/Zygote  (12603): v2
I/libpersona(12603): KNOX_SDCARD checking this for 10101
I/libpersona(12603): KNOX_SDCARD not a persona
,I/SELinux (12603): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/TimaKeyStoreProvider(12588): TimaSignature is unavailable
,I/SELinux (12603): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3509): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=12603 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ActivityThread(12588): Added TimaKeyStore provider
E/SELinux (12603): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/ResourcesManager(11577): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,W/ResourcesManager(12573): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(12573): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(12573): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(12573): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12573): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/PackageManager( 3509): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/ResourcesManager(11577): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/TimaKeyStoreProvider(12603): TimaSignature is unavailable
,D/ActivityThread(12603): Added TimaKeyStore provider
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/elm:14491(12555): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,I/KLMS-2.4.521: (12136): KLMSIntentService(): onDestroy()
,D/ResourcesManager(11577): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/elm:14491(12555): ElmAgentService : onCreate()
,D/elm:14491(12555): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:14491(12555): MainReceiver.listeningToPackageRemoved()
D/elm:14491(12555): MDMBridge.getInstance()
D/elm:14491(12555): MDMBridge.getAllLicenseInfoFromSDK()
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,D/elm:14491(12555): MDMBridge.getAllLicenseInfoFromSDK()
,D/ResourcesManager(12603): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(12588): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,W/ResourceType( 3509): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3509): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/Resources( 3509): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3509): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3509): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,E/Zygote  (12619): MountEmulatedStorage()
E/Zygote  (12619): v2
I/libpersona(12619): KNOX_SDCARD checking this for 10019
I/libpersona(12619): KNOX_SDCARD not a persona
,I/SELinux (12619): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,W/Resources( 3509): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,I/SELinux (12619): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
E/SELinux (12619): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3509): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=12619 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,W/Resources( 3509): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3509): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,W/ResourcesManager( 3509): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3509): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3509): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3509): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,I/ActivityManager( 3509): Killing 11594:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
,W/Resources( 3509): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/ResourcesManager( 3509): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager( 3509): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(11577): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/PackageManager( 3509): findPreferredActivity: No PreferredActivities set
,D/ResourcesManager( 3509): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
D/TimaKeyStoreProvider(12619): TimaSignature is unavailable
,D/ActivityThread(12619): Added TimaKeyStore provider
,E/SQLiteLog(12588): (284) automatic index on shooting_modes(title_id)
,D/elm:14491(12555): ElmAgentService : onDestroy().
D/ResourcesManager( 3509): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/ActivityManager( 3509): Killing 11609:com.android.calendar/u0a164 (adj 13): bgCount ##31
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/ResourcesManager(11577): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/RCPManagerService( 3509): PackageReceiver onReceive()
I/HarmonyEASService( 3509): onReceive : android.intent.action.PACKAGE_REMOVED for 0
W/Resources( 3509): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3509): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/KnoxMUMContainerPolicy( 3509): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
W/Resources( 3509): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3509): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3509): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
D/BackupManagerService( 3509): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 3509): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3509): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3509): uID is 10624
V/EnterpriseBillingPolicy( 3509): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3509): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 3509): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3509): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3509): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3509): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 3509): getBillingProfileForVpnEngine - end - null
,W/Resources( 3509): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3509): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources( 3509): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3509): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3509): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/KnoxTimeoutHandler( 3509): handleActiveUserChange for user 0
,W/Resources( 3509): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3509): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 3509): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(11577): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,D/UsbSettingsManager( 3509): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 3509): onPackageRemoved : com.test.thalitest
,D/TaskPersister( 3509): removeObsoleteFile: deleting file=26_task.xml
D/TaskPersister( 3509): removeObsoleteFile: deleting file=24_task.xml
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,D/NearbySource(12573): Nearby Source Create!
D/NearbyContext(12573): Nearby Context Create!
,D/ResourcesManager(11577): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,D/ResourcesManager(12619): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/StatusBar( 3692): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/Vold    ( 2827): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2827): Returning OperationFailed - no handler for errno 0
,D/ResourcesManager(11577): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
W/ContextImpl(12573): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource(12573): Samsung link source created
,D/PersonaManager( 3692): isKioskContainerExistOnDevice
D/PersonaManager( 3692): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3692): Icon Only
I/StatusBar( 3692): Icon Only
,D/PanelView( 3692): There is/are notification(s) 
D/PanelView( 3692): There is/are notification(s) 
D/PersonaManager( 3692): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3692): Icon Only
I/StatusBar( 3692): Icon Only
,D/PanelView( 3692): There is/are notification(s) 
,D/ResourcesManager(11577): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager(11577): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
E/Zygote  (12642): MountEmulatedStorage()
E/Zygote  (12642): v2
I/libpersona(12642): KNOX_SDCARD checking this for 10190
I/libpersona(12642): KNOX_SDCARD not a persona
,I/SELinux (12642): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager(11577): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
,I/SELinux (12642): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12642): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3509): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=12642 uid=10190 gids={50190, 9997} abi=armeabi-v7a
,D/ResourcesManager(11577): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/DocsApplication(12603): Installing DEX configuration.
,D/com.sec.android.service.health.upgrade.UninstallReceiver(12619): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver(12619): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver(12619): onReceive() : package name is not s health. Return !!!
I/ActivityManager( 3509): Killing 11577:com.sec.android.widgetapp.locationwidget/u0a22 (adj 13): bgCount ##31
I/art     ( 2876): Explicit concurrent mark sweep GC freed 8725(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 632us total 21.213ms
,I/ActivityManager( 3509): Killing 10919:com.android.defcontainer/u0a5 (adj 13): bgCount ##31
,I/art     ( 2876): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 522us total 11.624ms
,D/TimaKeyStoreProvider(12642): TimaSignature is unavailable
,D/PanelView( 3692): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
D/ActivityThread(12642): Added TimaKeyStore provider
,E/SQLiteLog(12573): (28) failed to open "/data/data/com.sec.android.gallery3d/databases/local.db" with flag (131138) and mode_t (0) due to error (30)
,I/art     ( 2876): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 370us total 11.422ms
,D/DexInstaller(12603): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,E/SQLiteDatabase(12573): Failed to open database '/data/data/com.sec.android.gallery3d/databases/local.db'.
E/SQLiteDatabase(12573): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12573): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12573): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12573): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12573): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12573): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12573): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12573): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12573): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12573): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12573): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12573): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12573): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12573): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(12573): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteDatabase(12573): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteDatabase(12573): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteDatabase(12573): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:202)
E/SQLiteDatabase(12573): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:194)
E/SQLiteDatabase(12573): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(12573): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(12573): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12573): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12573): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12573): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12573): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12573): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12573): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12573): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12573): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/SQLiteOpenHelper(12573): Couldn't open local.db for writing (will try read-only):
E/SQLiteOpenHelper(12573): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(12573): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(12573): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(12573): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(12573): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(12573): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(12573): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(12573): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(12573): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(12573): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(12573): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(12573): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(12573): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(12573): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(12573): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteOpenHelper(12573): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteOpenHelper(12573): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteOpenHelper(12573): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:202)
E/SQLiteOpenHelper(12573): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:194)
E/SQLiteOpenHelper(12573): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(12573): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(12573): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(12573): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(12573): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(12573): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(12573): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(12573): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(12573): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(12573): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(12573): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
I/PackageInfoHelper(12603): Provided clientMode=RELEASE, packageInfo=PackageInfo{109e5ada com.google.android.apps.docs}
W/SQLiteOpenHelper(12573): Opened local.db in read-only mode
D/TAG     (12603): onCreate()
D/ResourcesManager(12642): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
D/WifiDisplayAdapter( 3509): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/CrossAppStateProvider(12603): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
I/PCWCLIENTTRACE_PushUtil(12024): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(12024): sales region : global
I/PCWCLIENTTRACE_PushUtil(12024): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(12024): [onReceive] - android.intent.action.PACKAGE_REMOVED
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
D/UsbHostManager( 3509): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
D/UsbHostManager( 3509): displayNotification : [02h,02h,01h]
D/UsbHostManager( 3509): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
D/UsbHostManager( 3509): displayNotification : [0ah,00h,00h]
D/UsbHostManager( 3509): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3509): displayNotification : [02h,0dh,00h]
D/UsbHostManager( 3509): usbDeviceRemoved : /dev/bus/usb/001/003
E/UsbHostManager( 3509): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
D/UsbSettingsManager( 3509): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
E/Zygote  (12664): MountEmulatedStorage()
E/Zygote  (12664): v2
I/libpersona(12664): KNOX_SDCARD checking this for 10035
I/libpersona(12664): KNOX_SDCARD not a persona
I/TapandpayWidget:TanpandpayAppWidgetProvider(12642): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(12642): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
I/SELinux (12664): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/TapandpayWidget:Utils(12642): Clear T&P info.
I/ActivityManager( 3509): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=12664 uid=10035 gids={50035, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/SELinux (12664): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12664): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/UsbHostManager( 3509): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3509): displayNotification : [0ah,00h,01h]
D/UsbHostManager( 3509): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
D/UsbHostManager( 3509): displayNotification : [09h,00h,00h]
D/ContactProvider(12573): getAllContactInfoList Start
,D/WifiDisplayAdapter( 3509): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/TapandpayWidget:TanpandpayAppWidgetProvider(12642): Widget is not attached.
,I/ActivityManager( 3509): Killing 11733:com.android.vending/u0a31 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12664): TimaSignature is unavailable
,D/ActivityThread(12664): Added TimaKeyStore provider
,D/UsbHostManager( 3509): usbDeviceRemoved : /dev/bus/usb/001/001
E/UsbHostManager( 3509): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
,D/MtpClient(12573): onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
,D/MtpClient(12573): ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
,I/EventHub( 3509): Removing device '/dev/input/event10' due to inotify event
,E/SharedPreferencesImpl(12573): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3509): checkUser: useridlist=null, currentuser=0
,D/PackageBroadcastService( 6828): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 6828): Clearing selected account for com.test.thalitest
,I/EventHub( 3509): Removing device '/dev/input/event7' due to inotify event
,D/ResourcesManager(12664): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,E/Zygote  (12683): MountEmulatedStorage()
E/Zygote  (12683): v2
I/libpersona(12683): KNOX_SDCARD checking this for 10052
I/libpersona(12683): KNOX_SDCARD not a persona
,I/SELinux (12683): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/EventHub( 3509): Removing device '/dev/input/event8' due to inotify event
,I/SELinux (12683): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3509): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=12683 uid=10052 gids={50052, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,E/SELinux (12683): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/FeatureConfig(12664): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,I/EventHub( 3509): Removing device '/dev/input/event9' due to inotify event
,D/ResourcesManager(12664): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager(12664): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12664): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12664): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12664): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12664): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(12664): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/EventHub( 3509): Removing device '/dev/input/event11' due to inotify event
,D/ResourcesManager(12664): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,E/SQLiteLog( 6828): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6828): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/ResourcesManager(12664): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12664): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12664): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/DriveAsyncService( 6828): disk I/O error (code 3850)
E/DriveAsyncService( 6828): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 6828): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 6828): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/DriveAsyncService( 6828): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 6828): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 6828): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/DriveAsyncService( 6828): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
E/DriveAsyncService( 6828): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 6828): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 6828): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 6828): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 6828): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 6828): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 6828): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 6828): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 6828): 	at java.lang.Thread.run(Thread.java:818)
,D/ResourcesManager(12664): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,I/EventHub( 3509): Removing device '/dev/input/event12' due to inotify event
,D/TimaKeyStoreProvider(12683): TimaSignature is unavailable
,D/ActivityThread(12683): Added TimaKeyStore provider
I/LocationSettingsChecker( 6828): Removing dialog suppression flag for package com.test.thalitest
,W/ResourcesManager(12664): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager(12664): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12664): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager(12664): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12664): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12664): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12664): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/ActivityManager( 3509): Killing 12384:com.sec.android.provider.badge/u0a82 (adj 13): bgCount ##31
,D/ResourcesManager(12664): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,I/EventHub( 3509): Removing device '/dev/input/event13' due to inotify event
,E/SQLiteLog( 6828): (28) failed to open "/data/data/com.google.android.gms/databases/metrics.db" with flag (131138) and mode_t (0) due to error (30)
,D/ResourcesManager(12664): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(12664): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
E/SQLiteDatabase( 6828): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 6828): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6828): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6828): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6828): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6828): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6828): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6828): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6828): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 6828): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 6828): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6828): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 6828): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6828): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6828): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 6828): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 6828): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 6828): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 6828): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 6828): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6828): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6828): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6828): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ResourcesManager(12664): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12664): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12664): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
E/SQLiteOpenHelper( 6828): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 6828): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 6828): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 6828): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 6828): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 6828): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 6828): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 6828): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 6828): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 6828): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 6828): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 68,28): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper( 6828): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 6828): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 6828): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 6828): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 6828): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 6828): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 6828): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 6828): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 6828): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 6828): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 6828): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/SQLiteOpenHelper( 6828): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 6828): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 6828): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,E/SQLiteLog( 6828): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/gH_CompatibleDatabase( 6828): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,E/AndroidRuntime( 6828): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 6828): Process: com.google.android.gms, PID: 6828
E/AndroidRuntime( 6828): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 6828): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 6828): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
E/AndroidRuntime( 6828): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 6828): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 6828): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1623)
E/AndroidRuntime( 6828): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 6828): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 6828): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6828): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6828): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6828): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/EventHub( 3509): Removing device '/dev/input/event14' due to inotify event
,D/ResourcesManager(12664): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,W/ResourcesManager(12664): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12664): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12664): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager(12664): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/ResourcesManager(12664): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12664): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12664): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12664): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12664): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(12664): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(12664): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12664): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,V/ApplicationPolicy( 3509): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/SQLiteLog( 6828): (28) failed to open "/data/data/com.google.android.gms/databases/phenotype.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteLog( 6828): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6828): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDatabase( 6828): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 6828): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6828): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6828): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6828): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6828): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6828): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6828): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6828): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 6828): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 6828): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6828): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 6828): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6828): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6828): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6828): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6828): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 6828): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6828): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6828): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6828): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/PhenotypeInitializer( 6828): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 6828): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 6828): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 6828): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/PhenotypeInitializer( 6828): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/PhenotypeInitializer( 6828): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/PhenotypeInitializer( 6828): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/PhenotypeInitializer( 6828): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/PhenotypeInitializer( 6828): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/PhenotypeInitializer( 6828): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/PhenotypeInitializer( 6828): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/PhenotypeInitializer( 6828): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/PhenotypeInitializer( 6828): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/PhenotypeInitializer( 6828): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/PhenotypeInitializer( 6828): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/PhenotypeInitializer( 6828): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/PhenotypeInitializer( 6828): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 6828): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 6828): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 6828): 	at android.os.Looper.loop(Looper.java:145)
E/PhenotypeInitializer( 6828): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ResourcesManager(12683): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager(12664): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager(12683): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12683): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12683): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12683): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12683): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(12683): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager(12664): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12664): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12664): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/ClearPendingStateOp( 6828): Runtime exception while performing operation
E/ClearPendingStateOp( 6828): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearPendingStateOp( 6828): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearPendingStateOp( 6828): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/ClearPendingStateOp( 6828): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearPendingStateOp( 6828): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearPendingStateOp( 6828): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/ClearPendingStateOp( 6828): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:474)
E/ClearPendingStateOp( 6828): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
E/ClearPendingStateOp( 6828): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
E/ClearPendingStateOp( 6828): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:318)
E/ClearPendingStateOp( 6828): 	at android.content.ContentResolver.delete(ContentResolver.java:1309)
E/ClearPendingStateOp( 6828): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 6828): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 6828): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/ClearPendingStateOp( 6828): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 6828): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 6828): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 6828): 	at java.lang.Thread.run(Thread.java:818)
,F/ClearPendingStateOp( 6828): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 6828): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
F/ClearPendingStateOp( 6828): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
F/ClearPendingStateOp( 6828): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
F/ClearPendingStateOp( 6828): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
F/ClearPendingStateOp( 6828): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
F/ClearPendingStateOp( 6828): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
F/ClearPendingStateOp( 6828): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:474)
F/ClearPendingStateOp( 6828): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
F/ClearPendingStateOp( 6828): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
F/ClearPendingStateOp( 6828): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:318)
F/ClearPendingStateOp( 6828): 	at android.content.ContentResolver.delete(ContentResolver.java:1309)
F/ClearPendingStateOp( 6828): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 6828): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 6828): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
F/ClearPendingStateOp( 6828): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 6828): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 6828): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
F/ClearPendingStateOp( 6828): 	at java.lang.Thread.run(Thread.java:818)
,E/DropBoxManagerService( 3509): Can't write: system_app_crash
E/DropBoxManagerService( 3509): java.io.FileNotFoundException: /data/system/dropbox/drop195.tmp: open failed: EROFS (Read-only file system)
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
D/ContactProvider(12573): getAllContactInfoList End
,I/syncContacts(12573): thread: 1748, sync time = 540
,E/SQLiteLog( 6828): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6828): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/GMPM-SVC( 6828): Task exception on worker thread: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.b(SourceFile:321)
,D/ChimeraCfgMgr( 6828): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6828): Module APK com.google.android.play.games already loaded
,E/SharedPreferencesImpl( 6828): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak

```
