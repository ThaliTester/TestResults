#### Test 54312298af2c956_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
,D/SSRM:n  ( 3508): SIOP:: AP = 260, PST = 283, CUR = 60
I/PowerManagerService( 3508): [PWL] Off : 50s ago
D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3508): online:4, current avg:67, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:82
D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3508): stay LED for fully charged
I/MotionRecognitionService( 3508): Plugged
I/MotionRecognitionService( 3508): setPowerConnected  = true
--------- beginning of main
D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5622): Disconnected process message: 10
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AndroidRuntime(11614): 
D/AndroidRuntime(11614): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11614): CheckJNI is OFF
D/AndroidRuntime(11614): readGMSProperty: start
D/AndroidRuntime(11614): readGMSProperty: already setted!!
D/AndroidRuntime(11614): readGMSProperty: end
D/AndroidRuntime(11614): addProductProperty: start
E/AffinityControl(11614): AffinityControl: registerfunction enter
D/AndroidRuntime(11614): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3508): inState():  stateMachine is null !!
I/PersonaManagerService( 3508): PersonaId don't exist
I/ActivityManager( 3508): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3508): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3508): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3508): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager( 3508): mDVFSHelper.acquire()
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/Zygote  (11631): MountEmulatedStorage()
I/libpersona(11631): KNOX_SDCARD checking this for 10527
E/Zygote  (11631): v2
I/libpersona(11631): KNOX_SDCARD not a persona
I/SELinux (11631): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11631): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3508): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=11631 uid=10527 gids={50527, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/SELinux (11631): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(11614): Shutting down VM
D/PointerIcon( 3508): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3508): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3508): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3508): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(11631): TimaSignature is unavailable
D/ActivityThread(11631): Added TimaKeyStore provider
I/SurfaceFlinger( 2849): id=11 Removed YUIInstallC (5/8)
I/SurfaceFlinger( 2849): id=11 Removed YUIInstallC (-2/8)
D/ResourcesManager(11631): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
V/ActivityThread( 6243): updateVisibility : ActivityRecord{251a47e2 token=android.os.BinderProxy@3a361d57 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
I/WebViewFactory(11631): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(11631): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(11631): Loading: webviewchromium
I/LibraryLoader(11631): Time to load native libraries: 4 ms (timestamps 5046-5050)
I/LibraryLoader(11631): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(11631): Binding Chromium to main looper Looper (main, tid 1) {3f40f0fd}
,I/LibraryLoader(11631): Expected native library version number "",actual native library version number ""
,I/chromium(11631): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(11631): Initializing chromium process, renderers=0
,W/art     (11631): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(11631): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(11631): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(11631): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,W/chromium(11631): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(11631): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (11631): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(11631): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(11631): CordovaWebView is running on device made by: samsung
,W/art     (11631): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11631): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity(11631): performCreate Call secproduct feature valuefalse
D/Activity(11631): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(11631): Render dirty regions requested: true
,D/ActivityManager( 3508): post active user change for 0
D/KnoxTimeoutHandler( 3508): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3508): handleActiveUserChange for user 0
,I/SurfaceFlinger( 2849): id=14 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService( 3508): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3508): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3508): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 3508): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3508): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3508): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer(11631): Initialized EGL, version 1.4
,I/OpenGLRenderer(11631): HWUI protection enabled for context ,  &this =0xaf645060 ,&mEglDisplay = 1 , &mEglConfig = -1278652144 
,D/OpenGLRenderer(11631): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(11631): Enabling debug mode 0
,D/mali_winsys(11631): new_window_surface returns 0x3000,  [1440x2560]-format:1
,V/ActivityThread(11631): updateVisibility : ActivityRecord{495136d token=android.os.BinderProxy@11d7daa8 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/InputMethodManagerService( 3508): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3508): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ContextImpl( 3508): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 3508): mDVFSHelper.release()
I/Timeline( 3508): Timeline: Activity_windows_visible id: ActivityRecord{2cd9877b u0 com.test.thalitest/.MainActivity t26} time:145396
,W/IInputConnectionWrapper(11631): showStatusIcon on inactive InputConnection
,I/Timeline(11631): Timeline: Activity_idle id: android.os.BinderProxy@11d7daa8 time:145405
,D/JsMessageQueue(11631): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium(11631): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11631): 
,D/jxcore_app_log(11631): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1357424896
,D/JX-Cordova(11631): jxcore cordova android initializing
,W/jxcore-log(11631): Initializing JXcore engine
W/jxcore-log(11631): JXcore engine is ready
,W/jxcore-log(11631): Starting JXcore engine
,E/auditd  ( 4632): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3508): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl( 3508): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3508): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(11631): Platform android
W/jxcore-log(11631): 
W/jxcore-log(11631): Process ARCH arm
W/jxcore-log(11631): 
,I/jxcore-log(11631): JXcore Cordova bridge is ready!
I/jxcore-log(11631): 
W/jxcore-log(11631): JXcore engine is started
,W/ContextImpl( 3508): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log(11631): Toggling radios to true
I/jxcore-log(11631): 
,D/BluetoothAdapter(11631): enable()
,D/BluetoothAdapter(11631): enable(): BT is already enabled..!
,D/WifiService( 3508): New client listening to asynchronous messages
,I/WifiManager(11631): packageName : com.test.thalitest
,D/SecContentProvider( 3508): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3508): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3508): mCursor = null
D/WifiService( 3508): setWifiEnabled: true pid=11631, uid=10527
E/WifiService( 3508): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3508): Permission Denial: getCurrentUser() from pid=11631, uid=10527 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 3508): Failed getting userId using ActivityManagerNative
W/WifiService( 3508): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=11631, uid=10527 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3508): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3508): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3508): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3508): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3508): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider( 3508): name = wifi_on
,I/WifiService( 3508): disconnect: pid=11631, uid=10527
,I/wpa_supplicant( 3830): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/wpa_supplicant( 3830): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3830): wlan0: State: COMPLETED -> DISCONNECTED
I/jxcore-log(11631): Radios toggled
I/jxcore-log(11631): 
I/wpa_supplicant( 3830): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3830): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine( 3508): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 3830): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3830): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3830): Disconnected - do not scan
I/wpa_supplicant( 3830): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine( 3508): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3508): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3508): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3508): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/jxcore-log(11631): Got Device Bluetooth address: E0:DB:10:14:E2:C0
I/jxcore-log(11631): 
,I/jxcore-log(11631): Perf Test app loaded loaded
I/jxcore-log(11631): 
,I/jxcore-log(11631): check test folder
I/jxcore-log(11631): 
,I/jxcore-log(11631): found test : ./testFindPeers.js
I/jxcore-log(11631): 
,E/WifiStateMachine( 3508): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3508): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3508): do suspend true
,D/WifiP2pService( 3508): InactiveState{ what=143375 }
D/WifiP2pService( 3508): P2pEnabledState{ what=143375 }
,D/CommandListener( 2845): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 3694): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:"NG700"
E/Netd    ( 2845): ifc_reset_connections failed on iface wlan0 for address 192.168.1.124/24 (Unknown error -1)
,I/jxcore-log(11631): found test : ./testSendData.js
I/jxcore-log(11631): 
,E/WifiStateMachine( 3508): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService( 3508): updateNetworkInfo()
E/WifiConfigStore( 3508): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/WifiTrafficPoller( 3508): evaluateTrafficStatsPolling
E/ConnectivityService( 3508): updateNetworkInfo()
D/ConnectivityService( 3508): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 3508): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
,D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
,E/WifiStateMachine( 3508): Start Disconnecting Watchdog 1
,E/WifiStateMachine( 3508): ConnectModeState: Network connection lost 
,E/WifiStateMachine( 3508): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - processMessage - processMsg
E/WifiStateMachine( 3508): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3508): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3508): do suspend true
I/Hs20UtilService( 4082): Starting #8
,I/Hs20UtilService( 4082): Message received 5007
,I/jxcore-log(11631): found test : ./testSendData2.js
I/jxcore-log(11631): 
,D/NearbySettings( 8784): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 8784): MountReceiver.onReceive - Start HandlerThread
,D/NearbySettings( 8784): MountReceiver.onReceive - Create mPrefHandler
,D/WifiP2pService( 3508): InactiveState{ what=143375 }
D/NearbySettings( 8784): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,D/WifiP2pService( 3508): P2pEnabledState{ what=143375 }
,V/NearbySettings( 8784): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8784): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiService( 3508): New client listening to asynchronous messages
I/NearbySettings( 8784): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8784): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8784): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 8784): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11356): NETWORK_STATE_CHANGED_ACTION
,D/CommandListener( 2845): Clearing all IP addresses on wlan0
D/ConnectivityService( 3508): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/EntConnectivity( 3508): Not allowed due to - mEnabled false
,D/ConnectivityManager.CallbackHandler( 3694): CM callback handler got msg 524292
E/WifiStateMachine( 3508): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3508): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 3508): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiStateMachine( 3508): updateConfiguredNetworkExpiration - currTime: 1450836566578
D/WifiStateMachine( 3508): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
,I/wpa_supplicant( 3830): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3830): P2P: Current p2p state = IDLE
I/wpa_supplicant( 3830): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 3830): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3830): First Scan Start
D/TelephonyNetworkFactory( 3983): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/WifiStateMachine( 3508): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
D/CSLegacyTypeTracker( 3508): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
E/WifiStateMachine( 3508): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/CSLegacyTypeTracker( 3508): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 3508): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/wpa_supplicant( 3830): Scan requested (ret=0) - scan timeout 30 seconds
,D/ConnectivityManager.CallbackHandler( 6720): CM callback handler got msg 524292
E/WifiStateMachine( 3508): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3508): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine( 3508): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3508): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent( 3508): NetworkAgent: NetworkAgent channel lost
,I/WifiTrafficPoller( 3508): evaluateTrafficStatsPolling
,E/WifiStateMachine( 3508): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3508): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine( 3508): setDetailed state send new extra info"NG700"
D/SecContentProvider2( 3508): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3508): mCursor = null
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,D/Tethering( 3508): MasterInitialState.processMessage what=3
D/EntConnectivity( 3508): Not allowed due to - mEnabled false
,D/SmartBondingService( 3508): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 3508): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/SmartBondingService( 3508): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3508): getSBEnabled() enabled =false
D/NtpTrustedTime( 3508): currentTimeMillis() cache hit
D/SmartBondingService( 3508): getSBEnabled() enabled =false
D/SmartBondingService( 3508): getSBEnabled() enabled =false
V/NetworkStats( 3508): updateIfacesLocked()
V/NetworkStats( 3508): performPollLocked(flags=0x1)
,D/NtpTrustedTime( 3508): currentTimeMillis() cache hit
D/SmartBondingService( 3508): getNetworkEnabled : wifi : true mobile : false
D/NtpTrustedTime( 3508): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): 0
V/NetworkStats( 3508): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3508): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3694): updateDataNetType()
D/StatusBar.NetworkController( 3694): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3694): updateLTEICONDataNetType:0
D/NtpTrustedTime( 3508): currentTimeMillis() cache hit
D/NetworkStatsFactory( 3508): UpdateStatsForKnox
,I/Choreographer(11631): Skipped 47 frames!  The application may be doing too much work on its main thread.
D/StatusBar.NetworkController( 3694): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
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
,V/NetworkStats( 3508): performPollLocked() took 9ms
,D/NtpTrustedTime( 3508): currentTimeMillis() cache hit
,I/Hs20UtilService( 4082): Starting #9
D/SecContentProvider2( 3508): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3508): mCursor = null
I/Hs20UtilService( 4082): Message received 5007
,I/chromium(11631): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/NtpTrustedTime( 3508): currentTimeMillis() cache hit
D/NtpTrustedTime( 3508): currentTimeMillis() cache hit
D/NearbySettings( 8784): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8784): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8784): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8784): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8784): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8784): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8784): MountReceiver.mPrefHandler - 7002
,I/chromium(11631): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/SignOutReceiver(11356): NETWORK_STATE_CHANGED_ACTION
,D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
,D/ConnectivityService( 3508): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 3508): updateDataUsageMap
,I/ApplicationPolicy( 3508): updateDataUsageMap  idList is null 
,D/SmartBondingService( 3508): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3508): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService( 3508): getSBEnabled() enabled =false
D/SmartBondingService( 3508): getSBEnabled() enabled =false
,D/SmartBondingService( 3508): getSBEnabled() enabled =false
,D/SmartBondingService( 3508): getNetworkEnabled : wifi : true mobile : false
,D/GpsLocationProvider( 3508): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,W/SLocation( 3508): No Active Data Connection
,I/DBG_DM  ( 6243): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,E/Zygote  (11731): MountEmulatedStorage()
I/libpersona(11731): KNOX_SDCARD checking this for 10110
E/Zygote  (11731): v2
I/libpersona(11731): KNOX_SDCARD not a persona
,I/SELinux (11731): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/DBG_DM  ( 6243): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,I/ActivityManager( 3508): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.iorg.vpn.cleanup.NetworkStateMonitor: pid=11731 uid=10110 gids={50110, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/SELinux (11731): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11731): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11731): TimaSignature is unavailable
,D/ActivityThread(11731): Added TimaKeyStore provider
,D/ResourcesManager(11731): creating new AssetManager and set to /data/app/com.facebook.appmanager-2/base.apk
,D/ACRA    (11731): ACRA is enabled for com.facebook.appmanager, intializing...
,I/DexLibLoader(11731): not using cross-dex optimization: ART in use
,I/art     (11731): Thread[1,tid=11731,WaitingForJniOnLoad,Thread*=0xb4e08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/app/com.facebook.appmanager-2/lib/arm/libfbjni.so"
,V/DexLibLoader(11731): about to lock: /data/data/com.facebook.appmanager/mdex_lock
V/DexLibLoader(11731): locking /data/data/com.facebook.appmanager/mdex_lock took 0 ms
,V/DexLibLoader(11731): Secondary program dex metadata: classes2.dex 29f80981f469a774a4884b3db2df17e0be227159 secondary.dex01.Canary
D/DexLibLoader(11731): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex" is valid
D/DexLibLoader(11731): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex_opt" is valid
,W/art     (11731): Attempt to remove local handle scope entry from IRT, ignoring
D/DexLibLoader(11731): loading pre-built fallback odex files
V/MultiDexClassLoader(11731): installing MultiDexClassLoader before application classloader
,D/DexLibLoader(11731): released odex store lock
D/DexLibLoader(11731): DexLibLoader.loadAll took 45 ms
,W/ca      (11731): Verify
,W/LightSharedPreferencesImpl(11731): Failed to load preference file from Disk!
W/LightSharedPreferencesImpl(11731): java.io.FileNotFoundException: /data/data/com.facebook.appmanager/app_light_prefs/com.facebook.appmanager/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11731): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/LightSharedPreferencesImpl(11731): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/LightSharedPreferencesImpl(11731): 	at com.facebook.crudolib.b.k.a(LightSharedPreferencesStorage.java:56)
W/LightSharedPreferencesImpl(11731): 	at com.facebook.crudolib.b.g.run(LightSharedPreferencesImpl.java:61)
W/LightSharedPreferencesImpl(11731): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/LightSharedPreferencesImpl(11731): 	at com.facebook.common.executors.dj.run(WrappingExecutorService.java:77)
W/LightSharedPreferencesImpl(11731): 	at com.facebook.common.executors.u.run(DefaultConstrainedListeningExecutorService.java:327)
W/LightSharedPreferencesImpl(11731): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/LightSharedPreferencesImpl(11731): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/LightSharedPreferencesImpl(11731): 	at com.facebook.common.executors.cc.run(NamedThreadFactory.java:42)
W/LightSharedPreferencesImpl(11731): 	at java.lang.Thread.run(Thread.java:818)
W/LightSharedPreferencesImpl(11731): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11731): 	at libcore.io.Posix.open(Native Method)
W/LightSharedPreferencesImpl(11731): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/LightSharedPreferencesImpl(11731): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/LightSharedPreferencesImpl(11731): 	... 10 more
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11765): MountEmulatedStorage()
E/Zygote  (11765): v2
I/libpersona(11765): KNOX_SDCARD checking this for 1000
I/libpersona(11765): KNOX_SDCARD not a persona
,I/SELinux (11765): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3508): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=11765 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux (11765): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,W/appmanager(:<default>):b(11731): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,E/SELinux (11765): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3508): Killing 10973:com.sec.android.app.myfiles/u0a53 (adj 15): bgCount ##31
,I/wpa_supplicant( 3830): nl80211: Received scan results (10 BSSes)
,I/wpa_supplicant( 3830): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 3830): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3830): wlan0: State: SCANNING -> ASSOCIATING
,E/WifiStateMachine( 3508): [1,450,836,567,665 ms] noteScanEnd no scan source
,I/wpa_supplicant( 3830): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3508): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@148f764e sup_state=SCANNING debouncing=false
,E/WifiStateMachine( 3508): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
,E/WifiStateMachine( 3508): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3508): setDetailed state send new extra info
,D/SecContentProvider2( 3508): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3508): mCursor = null
,D/TimaKeyStoreProvider(11765): TimaSignature is unavailable
,W/appmanager(:<default>):b(11731): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/ActivityThread(11765): Added TimaKeyStore provider
,D/ResourcesManager(11765): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/PCWCLIENTTRACE_LOG(11765): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(11765): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(11765): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil(11765): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11765): sales region : global
I/PCWCLIENTTRACE_PushUtil(11765): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11765): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver(11765): noConnectivity : true
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,I/wpa_supplicant( 3830): wlan0: State: ASSOCIATING -> ASSOCIATED
,I/wpa_supplicant( 3830): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3508): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3508): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
I/wpa_supplicant( 3830): Associated with C0.AA.48
,E/WifiStateMachine( 3508): setDetailed state send new extra info"NG700"
,D/SecContentProvider2( 3508): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3508): mCursor = null
,E/Zygote  (11789): MountEmulatedStorage()
E/Zygote  (11789): v2
I/libpersona(11789): KNOX_SDCARD checking this for 10135
I/libpersona(11789): KNOX_SDCARD not a persona
,I/SELinux (11789): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11789): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3508): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=11789 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (11789): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/wpa_supplicant( 3830): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 3830): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3508): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
,E/WifiStateMachine( 3508): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,I/wpa_supplicant( 3830): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 3830): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 3830): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 3830): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/ActivityManager( 3508): Killing 10990:com.sec.android.provider.badge/u0a82 (adj 15): bgCount ##31
I/wpa_supplicant( 3830): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 3830): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 3830): Blacklist: Clear (temp) 
I/wpa_supplicant( 3830): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3508): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3508): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine( 3508): Network connection established
,D/WifiNative-HAL( 3508): callSECApiVoid - ID [50]
,E/WifiStateMachine( 3508): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine( 3508): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService( 3508): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,E/WifiStateMachine( 3508): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3508): L2ConnectedState "NG700" nid=0
E/WifiConfigStore( 3508): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 3508): hsengiv:checkWhatTypeOfNetwork and the value is false
,E/ConnectivityService( 3508): updateNetworkInfo()
,D/ConnectivityService( 3508): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3508): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine( 3508): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3508): ObtainingIpAddress "NG700" nid=0
,E/WifiConfigStore( 3508): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,W/appmanager(:<default>):QuickExperimentControllerImpl(11731): Exposure of experiment com.facebook.common.network.l@35b0f6a occurred when no user was logged in
,D/TimaKeyStoreProvider(11789): TimaSignature is unavailable
,D/ActivityThread(11789): Added TimaKeyStore provider
,D/CommandListener( 2845): Setting iface cfg
,E/WifiStateMachine( 3508): Start Dhcp Watchdog 2
,D/SecContentProvider2( 3508): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3508): mCursor = null
,W/BroadcastQueue( 3508): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{3fe481d4 u0 ReceiverList{1f007b27 11731 com.facebook.appmanager/10110/u0 remote:29e409e6}}
,W/BroadcastQueue( 3508): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{3fe481d4 u0 ReceiverList{1f007b27 11731 com.facebook.appmanager/10110/u0 remote:29e409e6}}
,D/SecContentProvider2( 3508): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3508): mCursor = null
,D/ResourcesManager(11789): creating new AssetManager and set to /system/app/Music2/Music2.apk
,E/WifiStateMachine( 3508): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine( 3508): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,W/BroadcastQueue( 3508): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{39fd5e58 u0 ReceiverList{30a0a73b 11731 com.facebook.appmanager/10110/u0 remote:18ffc9ca}}
,E/WifiStateMachine( 3508): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3508): do suspend false
,D/SecContentProvider2( 3508): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3508): mCursor = null
D/WifiP2pService( 3508): InactiveState{ what=143375 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=143375 }
,I/MusicStore(11789): Database version: 104
,D/ResourcesManager(11789): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11789): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11789): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (11789): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(11789): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (11789): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@339d4f81: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(11789): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(11789): GMSCore installation verified
,I/ConfigStore(11789): Config Database version: 1
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11789): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/dhcpcd  (11828): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (11828): version 5.5.6 starting
,E/dhcpcd  (11828): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
W/ContextImpl(11789): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11789): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter( 3508): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3508): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3508): getStreamVolume 3 index 0
,I/MediaRouter(11789): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/dhcpcd  (11828): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (11828): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (11828): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  (11828): bssid match
I/dhcpcd  (11828): wlan0: rebinding lease of 192.168.1.124
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11835): MountEmulatedStorage()
E/Zygote  (11835): v2
I/libpersona(11835): KNOX_SDCARD checking this for 10002
I/libpersona(11835): KNOX_SDCARD not a persona
,I/SELinux (11835): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3508): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=11835 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (11835): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11835): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11731): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,D/WifiDisplayAdapter( 3508): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11731): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,I/NetworkMonitor(11789): type=WIFI subType= reason=null isConnected=false
,D/TimaKeyStoreProvider(11835): TimaSignature is unavailable
,D/ActivityThread(11835): Added TimaKeyStore provider
,I/ActivityManager( 3508): Killing 9743:com.sec.android.app.shealth/u0a36 (adj 15): bgCount ##31
,D/ResourcesManager(11835): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,W/appmanager(:<default>):QuickExperimentControllerImpl(11731): Exposure of experiment com.facebook.imagepipeline.a.g@3e30b678 occurred when no user was logged in
,W/appmanager(:<default>):QuickExperimentControllerImpl(11731): Exposure of experiment com.facebook.imagepipeline.a.d@3c0fd18d occurred when no user was logged in
,I/ActivityManager( 3508): Killing 11005:com.sec.android.app.samsungapps/u0a13 (adj 15): bgCount ##31
,I/art     (11731): Explicit concurrent mark sweep GC freed 43519(2MB) AllocSpace objects, 6(96KB) LOS objects, 22% free, 27MB/35MB, paused 1.559ms total 48.363ms
,W/appmanager(:<default>):m(11731): No feature status reporters found; is this dead code?
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11855): MountEmulatedStorage()
E/Zygote  (11855): v2
I/libpersona(11855): KNOX_SDCARD checking this for 1000
I/libpersona(11855): KNOX_SDCARD not a persona
,I/SELinux (11855): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11855): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11855): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3508): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=11855 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11855): TimaSignature is unavailable
,D/ActivityThread(11855): Added TimaKeyStore provider
,D/ResourcesManager(11855): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT(11855): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/dhcpcd  (11828): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
,I/DIAGMON_AGENT(11855): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT(11855): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT(11855): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(11855): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/dhcpcd  (11828): wlan0: leased 192.168.1.124 for 86400 seconds
,E/WifiStateMachine( 3508): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine( 3508): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11881): MountEmulatedStorage()
,E/Zygote  (11881): v2
I/libpersona(11881): KNOX_SDCARD checking this for 10012
I/libpersona(11881): KNOX_SDCARD not a persona
,I/SELinux (11881): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3508): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=11881 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (11881): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11881): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11881): TimaSignature is unavailable
,D/ActivityThread(11881): Added TimaKeyStore provider
,D/ResourcesManager(11881): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager( 3508): Killing 11024:com.policydm/1000 (adj 15): bgCount ##31
,I/FOTA_Client(11881): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(11881): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(11881): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11911): MountEmulatedStorage()
E/Zygote  (11911): v2
I/libpersona(11911): KNOX_SDCARD checking this for 10021
I/libpersona(11911): KNOX_SDCARD not a persona
,I/SELinux (11911): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11911): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3508): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=11911 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
E/SELinux (11911): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3508): Killing 10862:com.google.android.apps.docs/u0a101 (adj 15): bgCount ##31
,E/WifiStateMachine( 3508): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine( 3508): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
D/TimaKeyStoreProvider(11911): TimaSignature is unavailable
E/native  ( 3508): do suspend true
,D/ActivityThread(11911): Added TimaKeyStore provider
,D/WifiP2pService( 3508): InactiveState{ what=143375 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 3508): WifiStateMachine DHCP successful
,E/WifiStateMachine( 3508): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine( 3508): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine( 3508): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3508): Not connected state, yet.
E/WifiStateMachine( 3508): VerifyingLinkState enter
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiStateMachine( 3508): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
,D/WifiStateMachine( 3508): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3508): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3508): callSECApiInt - ID [210]
,E/WifiStateMachine( 3508): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
D/ResourcesManager(11911): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,E/ConnectivityService( 3508): updateNetworkInfo()
,D/ConnectivityService( 3508): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 3508): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 3508): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 3508): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.DnsResolver( 3508): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker( 3508): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3508): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,E/WifiStateMachine( 3508): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine( 3508): Now, connected state.
E/WifiStateMachine( 3508): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3508): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/WifiTrafficPoller( 3508): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,I/WifiTrafficPoller( 3508): evaluateTrafficStatsPolling
,D/WifiNative-HAL( 3508): callSECApiVoid - ID [212]
,E/WifiStateMachine( 3508): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/KLMS-2.4.521: (11911): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Dec 23 03:09:28 GMT+01:00 2015
,D/StatusBar.NetworkController( 3694): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
,E/WifiStateMachine( 3508): ConnectedState Enter  mScreenOn=false scanperiod=20000
,I/WifiStateMachine( 3508): REQUEST_POWER_SAVE_ON
D/ConnectivityService( 3508): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/ConnectivityService( 3508): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService( 3508): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,I/KLMS-2.4.521: (11911): KLMSAbstractReciever(): onReceive().END.
E/ConnectivityService( 3508): Unexpected mtu value: 0, wlan0
,V/        ( 2845): QcRouteController
,I/KLMS-2.4.521: (11911): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11911): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (11911): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (11911): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (11911): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2845): QcRouteController
,E/Zygote  (11933): MountEmulatedStorage()
,E/Zygote  (11933): v2
I/libpersona(11933): KNOX_SDCARD checking this for 10038
I/libpersona(11933): KNOX_SDCARD not a persona
,I/SELinux (11933): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/KLMS-2.4.521: (11911): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager( 3508): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=11933 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/SELinux (11933): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/KLMS-2.4.521: (11911): StateImplV2(): networkChangeListener().END
,E/SELinux (11933): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.4.521: (11911): KLMSIntentService(): onDestroy()
,I/ActivityManager( 3508): Killing 11042:com.sec.android.app.soundalive/u0a59 (adj 15): bgCount ##31
,V/        ( 2845): QcRouteController
,V/        ( 2845): QcRouteController
,D/TimaKeyStoreProvider(11933): TimaSignature is unavailable
,D/ActivityThread(11933): Added TimaKeyStore provider
,V/        ( 2845): QcRouteController
,D/ResourcesManager(11933): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,V/        ( 2845): QcRouteController
,V/        ( 2845): QcRouteController
,V/        ( 2845): QcRouteController
,I/SO_AGENT(11933): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService( 3508): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService( 3508): LTETest block dns file not exists
,E/Zygote  (11959): MountEmulatedStorage()
E/Zygote  (11959): v2
I/libpersona(11959): KNOX_SDCARD checking this for 1000
I/libpersona(11959): KNOX_SDCARD not a persona
,I/SELinux (11959): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11959): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3508): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=11959 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux (11959): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3508): Killing 11089:com.sec.spp.push/u0a39 (adj 15): bgCount ##31
,D/ConnectivityService( 3508): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,E/ConnectivityService( 3508): updateNetworkInfo()
,E/ConnectivityService( 3508): updateNetworkInfo()
,D/ConnectivityService( 3508): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService( 3508): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 3508): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3508): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3508): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3508): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3508): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService( 3508):    accepting network in place of null
,D/TelephonyNetworkFactory( 3983): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker( 3508): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,D/CSLegacyTypeTracker( 3508): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 3508): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService( 3508): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/Tethering( 3508): MasterInitialState.processMessage what=3
D/SmartBondingService( 3508): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService( 3508): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
I/System.out( 3508): (HTTPLog)-Static: isSBSettingEnabled false
D/SmartBondingService( 3508): getSBEnabled() enabled =false
D/SmartBondingService( 3508): getSBEnabled() enabled =false
D/SmartBondingService( 3508): getSBEnabled() enabled =false
,V/NetworkStats( 3508): updateIfacesLocked()
D/NtpTrustedTime( 3508): currentTimeMillis() cache hit
V/NetworkStats( 3508): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 3508): UpdateStatsForKnox
D/SmartBondingService( 3508): getNetworkEnabled : wifi : true mobile : false
,D/ConnectivityService( 3508): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/EntConnectivity( 3508): Not allowed due to - mEnabled false
,D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3694): updateDataNetType()
D/StatusBar.NetworkController( 3694): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3694): updateLTEICONDataNetType:0
,D/NtpTrustedTime( 3508): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 3694): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength: hasService=false ss=null
D/NtpTrustedTime( 3508): currentTimeMillis() cache hit
D/NtpTrustedTime( 3508): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
V/NetworkStats( 3508): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3508): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 3694): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
,V/NetworkStats( 3508): performPollLocked() took 14ms
,D/NtpTrustedTime( 3508): currentTimeMillis() cache hit
D/ConnectivityManager.CallbackHandler( 3694): CM callback handler got msg 524290
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 1000
,D/ConnectivityManager.CallbackHandler( 6720): CM callback handler got msg 524290
,D/NtpTrustedTime( 3508): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3508): currentTimeMillis() cache hit
,D/TimaKeyStoreProvider(11959): TimaSignature is unavailable
,D/ActivityThread(11959): Added TimaKeyStore provider
,D/ResourcesManager(11959): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,I/System.out( 3508): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3508): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 23 Dec 2015 02:09:29 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450836569296], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450836569280]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3508): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3508): Validated
D/ConnectivityService( 3508): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3508): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3508): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 3508): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 3508): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 6720): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 3694): CM callback handler got msg 524290
,E/Zygote  (11981): MountEmulatedStorage()
I/libpersona(11981): KNOX_SDCARD checking this for 10039
E/Zygote  (11981): v2
I/libpersona(11981): KNOX_SDCARD not a persona
,I/SELinux (11981): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11981): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3508): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=11981 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (11981): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3508): Killing 11128:com.wsomacp/u0a28 (adj 15): bgCount ##31
,D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): 0
,D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): mDataTypeBrand = LTE
,D/StatusBar.NetworkController( 3694): updateDataNetType()
D/StatusBar.NetworkController( 3694): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3694): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3694): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength: hasService=false ss=null
,D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3694): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 8745(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 881us total 23.838ms
,D/TimaKeyStoreProvider(11981): TimaSignature is unavailable
,D/ActivityThread(11981): Added TimaKeyStore provider
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 843us total 18.515ms
,D/ResourcesManager(11981): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.027ms total 16.078ms
,E/SPPClientService(11981): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(11981): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService(11981): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,D/SPPClientService(11981): PushLog.txt file is not deleted.
D/SPPClientService(11981): PushLog.txt file is not deleted.
D/SPPClientService(11981): ============PushLog. stop!
,I/SA      (11204): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
I/SA      (11204): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      (11204): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (11204): [SLFUCHKMGR] constructor called
,E/SPPClientService(11981): [[SystemStateMonitorService]] No Active Internet
,I/SA      (11204): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11204): [OR] == isSIMCardReady false ==
,I/SA      (11204): [SCU] == networkStateCheck == true
,I/SA      (11204): [DM] getCountryCodeFromCSC : PL
I/SA      (11204): isChinaCountryCode : false
I/SA      (11204): [SCU] is ChinestModel Data Restricted   : false
I/SA      (11204): [OR] == networkStateCheck true ==
,I/SA      (11204): [OR] GetMyCountryZoneTask
I/SA      (11204): [OR] onReceive END
,I/SA      (11204): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 3719): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager( 3508): Killing 11108:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##31
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,I/SA      (11204): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (11204): [SSP] query invoked
,E/Zygote  (12005): MountEmulatedStorage()
,E/Zygote  (12005): v2
,I/libpersona(12005): KNOX_SDCARD checking this for 10067
I/libpersona(12005): KNOX_SDCARD not a persona
,I/SELinux (12005): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SA      (11204): [TPMU] GetMccFromDB : null
I/ActivityManager( 3508): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=12005 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/SA      (11204): [SCU] getMccFromPreferece mcc = 260
I/SA      (11204): [TPM] isNoProxy(default) : true
,I/SELinux (12005): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12005): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12005): TimaSignature is unavailable
,D/ActivityThread(12005): Added TimaKeyStore provider
,D/ResourcesManager(12005): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/sCloudBackupApp(12005): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(12005): Other Intent
,I/ActivityManager( 3508): Killing 11143:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
E/lowmemorykiller( 2827): Error writing /proc/11143/oom_score_adj; errno=22
,D/accuweather( 5211): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3776): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 6
,D/accuweather( 5211): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5211): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5211): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5211): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5211): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5211): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12021): MountEmulatedStorage()
E/Zygote  (12021): v2
I/libpersona(12021): KNOX_SDCARD checking this for 1000
I/libpersona(12021): KNOX_SDCARD not a persona
,I/SELinux (12021): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3508): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=12021 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux (12021): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12021): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12021): TimaSignature is unavailable
,D/ActivityThread(12021): Added TimaKeyStore provider
,D/ConnectivityService( 3508): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3508): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3508): SmartBondingReceiver: wifi is connected
D/SmartBondingService( 3508): SmartBondingReceiver: wifi ap is not changed
,D/SmartBondingService( 3508): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService( 3508): getSBEnabled() enabled =false
D/SmartBondingService( 3508): getSBEnabled() enabled =false
D/SmartBondingService( 3508): getSBEnabled() enabled =false
,D/SmartBondingService( 3508): getNetworkEnabled : wifi : true mobile : false
,I/DBG_DM  ( 6243): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 6243): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/GpsLocationProvider( 3508): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/ResourceType( 5344): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5344): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,I/NetworkMonitor(11789): type=WIFI subType= reason=null isConnected=true
,D/ResourcesManager(12021): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(12021): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro(12021): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro(12021): premStatus:2
,I/KnoxUsageLogPro(12021): isEulaShown : false
I/KnoxUsageLogPro(12021): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12037): MountEmulatedStorage()
E/Zygote  (12037): v2
I/libpersona(12037): KNOX_SDCARD checking this for 10090
I/libpersona(12037): KNOX_SDCARD not a persona
,I/SELinux (12037): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12037): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12037): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3508): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=12037 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3508): Killing 11062:com.sec.android.automotive.drivelink/u0a102 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12037): TimaSignature is unavailable
,D/ActivityThread(12037): Added TimaKeyStore provider
,I/SA      (11204): [RC New] Execute method=[GET] start
,I/SA      (11204): [RC New] Security=[true]
,I/System.out(11204): Thread-1545(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out(11204): Thread-1545(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11204): Thread-1545(ApacheHTTPLog):isShipBuild true
I/System.out(11204): Thread-1545(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 10045
,I/art     ( 3508): Explicit concurrent mark sweep GC freed 80926(4MB) AllocSpace objects, 18(288KB) LOS objects, 24% free, 49MB/65MB, paused 5.285ms total 126.226ms
D/SecContentProvider2( 3508): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3508): mCursor = null
,D/ResourcesManager(12037): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12054): MountEmulatedStorage()
E/Zygote  (12054): v2
I/libpersona(12054): KNOX_SDCARD checking this for 10127
I/libpersona(12054): KNOX_SDCARD not a persona
,I/SELinux (12054): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3508): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=12054 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (12054): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12054): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3508): Killing 11157:com.samsung.android.sdk.samsunglink/u0a42 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12054): TimaSignature is unavailable
,D/ActivityThread(12054): Added TimaKeyStore provider
,D/ResourcesManager(12054): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,D/KeyguardWallpaperUpdator(12054): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12054): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12054): stopCheckCategoryVersion
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12070): MountEmulatedStorage()
E/Zygote  (12070): v2
I/libpersona(12070): KNOX_SDCARD checking this for 10136
I/libpersona(12070): KNOX_SDCARD not a persona
,I/SELinux (12070): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12070): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12070): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3508): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=12070 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3508): Killing 9960:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
,D/ConnectivityService( 3508): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/TimaKeyStoreProvider(12070): TimaSignature is unavailable
,D/ActivityThread(12070): Added TimaKeyStore provider
,D/ResourcesManager(12070): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12070): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12070): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12070): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
,W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
W/ContextImpl(12070): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/SA      (11204): [RC New] [v2liruge] api execute + 641
I/SA      (11204): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out(11204): AsyncTask #1 calls detatch()
,I/SA      (11204): [TPMU] getNetworkMcc : 
,I/SA      (11204): [SCU] saveMccToPreferece Start
I/SA      (11204): [SCU] RegionMCC : 260
,I/SA      (11204): [SSP] query invoked
,I/SA      (11204): [TPMU] GetMccFromDB : null
I/SA      (11204): [SCU] getMccFromPreferece mcc = 260
I/SA      (11204): [SCU] saveMccToPreferece End
,I/SA      (11204): [RC New] executeRequest [v2liruge] end. 679
I/SA      (11204): [RC New] Execute end
I/SA      (11204): [OR] GetMyCountryZoneTask mcc = 260
I/SA      (11204): [OR] GetMyCountryZoneTask Success
,I/WebViewFactory(12070): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(12070): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(12070): Loading: webviewchromium
,I/LibraryLoader(12070): Time to load native libraries: 5 ms (timestamps 1602-1607)
I/LibraryLoader(12070): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(12070): Binding Chromium to main looper Looper (main, tid 1) {12024803}
,I/LibraryLoader(12070): Expected native library version number "",actual native library version number ""
,I/chromium(12070): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(12070): Initializing chromium process, renderers=0
,W/art     (12070): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(12070): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
W/AudioManagerAndroid(12070): Requires BLUETOOTH permission
I/chromium(12070): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium(12070): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,I/NSApplication(12070): Starting up...
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12137): MountEmulatedStorage()
E/Zygote  (12137): v2
I/libpersona(12137): KNOX_SDCARD checking this for 10150
I/libpersona(12137): KNOX_SDCARD not a persona
,I/SELinux (12137): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3508): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=12137 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux (12137): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3508): Killing 11223:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##31
E/SELinux (12137): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12137): TimaSignature is unavailable
,D/ActivityThread(12137): Added TimaKeyStore provider
,D/ResourcesManager(12137): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(12137): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12137): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager(12137): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect(12137): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12137): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect(12137): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12152): MountEmulatedStorage()
E/Zygote  (12152): v2
I/libpersona(12152): KNOX_SDCARD checking this for 10178
I/libpersona(12152): KNOX_SDCARD not a persona
,I/SELinux (12152): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12152): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3508): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=12152 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
E/SELinux (12152): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3508): Killing 11238:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12152): TimaSignature is unavailable
,D/ActivityThread(12152): Added TimaKeyStore provider
,D/ResourcesManager(12152): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(12152): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager(12152): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12152): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12152): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12152): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,W/ResourcesManager(12152): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService( 3508): exchangeData() failure , invalid userId
,D/RCPManagerService( 3508): exchangeData() failure , invalid userId
,D/RCPManagerService( 3508): exchangeData() failure , invalid userId
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 3508): exchangeData() failure , invalid userId
,D/RCPManagerService( 3508): exchangeData() failure , invalid userId
,E/Zygote  (12179): MountEmulatedStorage()
E/Zygote  (12179): v2
I/libpersona(12179): KNOX_SDCARD checking this for 10082
I/libpersona(12179): KNOX_SDCARD not a persona
,I/SELinux (12179): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3508): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=12179 uid=10082 gids={50082, 9997} abi=armeabi-v7a
D/RCPManagerService( 3508): exchangeData() failure , invalid userId
I/SELinux (12179): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12179): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12194): MountEmulatedStorage()
E/Zygote  (12194): v2
I/libpersona(12194): KNOX_SDCARD checking this for 1000
I/libpersona(12194): KNOX_SDCARD not a persona
,I/SELinux (12194): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12194): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12194): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3508): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=12194 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3508): Killing 11273:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12179): TimaSignature is unavailable
,D/ActivityThread(12179): Added TimaKeyStore provider
,I/ActivityManager( 3508): Killing 11288:com.samsung.helphub/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12194): TimaSignature is unavailable
,D/ActivityThread(12194): Added TimaKeyStore provider
,D/ResourcesManager(12179): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/ResourcesManager(12194): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/BadgeProvider(12179): onCreate
D/BadgeProvider(12179): DatabaseHelper
,I/ActivityManager( 3508): Killing 11382:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##31
,D/BadgeProvider(12179): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider(12179): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12179): sendNotify, [notify] : null
D/BadgeProvider(12179): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12179): update, [BadgeCount] : badgecount=0
D/BadgeProvider(12179): update, [UpdateCount] : 1
,D/Launcher.Model( 4002): reloadBadges entered.
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12216): MountEmulatedStorage()
E/Zygote  (12216): v2
I/libpersona(12216): KNOX_SDCARD checking this for 10013
I/libpersona(12216): KNOX_SDCARD not a persona
,I/SELinux (12216): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12216): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3508): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=12216 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,E/SELinux (12216): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 3508): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/TimaKeyStoreProvider(12216): TimaSignature is unavailable
,D/ActivityThread(12216): Added TimaKeyStore provider
,D/ResourcesManager(12216): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,D/WaitQueueForNetworkActivate(12216): notifyNetworkActivated
,W/ContextImpl(12216): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3508): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): setDiscoveryMode: Mode set to BLE
,I/jxcore-log(11631): BLE supported!!
I/jxcore-log(11631): 
,D/hcjo    (12216): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12216): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12216): exit::IDLE
D/InitializeManagerStateMachine(12216): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12216): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12216): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12216): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12216): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12216): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12216): entry::SUCCESS
D/hcjo    (12216): AutoUpdateManager:INITCHECK:onInitializeSuccess
,E/WifiStateMachine( 3508): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine( 3508): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService( 3508): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/hcjo    (12216): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12216): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,V/        ( 2845): QcRouteController
,I/Hs20UtilService( 4082): Starting #10
,D/SmartBondingService( 3508): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/SmartBondingService( 3508): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService( 3508): getSBEnabled() enabled =false
D/SmartBondingService( 3508): getSBEnabled() enabled =false
D/SmartBondingService( 3508): getSBEnabled() enabled =false
,D/InitializeManagerStateMachine(12216): exit::SUCCESS
D/InitializeManagerStateMachine(12216): entry::IDLE
,D/NearbySettings( 8784): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8784): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8784): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 8784): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 8784): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/Hs20UtilService( 4082): Message received 5007
I/NearbySettings( 8784): MountReceiver.onReceive - Keep current state
,I/ActivityManager( 3508): Killing 11400:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
,V/        ( 2845): QcRouteController
,W/NetworkManagementService( 3508): route cmd failed: 
W/NetworkManagementService( 3508): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '76 route replace src v6 wlan0 fe80::92b6:86ff:fe43:731c 2 ::' failed with '400 76 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService( 3508): '
W/NetworkManagementService( 3508): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService( 3508): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService( 3508): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService( 3508): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService( 3508): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService( 3508): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5738)
W/NetworkManagementService( 3508): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5545)
W/NetworkManagementService( 3508): 	at com.android.server.ConnectivityService.access$2600(ConnectivityService.java:231)
W/NetworkManagementService( 3508): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2436)
W/NetworkManagementService( 3508): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 3508): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService( 3508): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ConnectivityService( 3508): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3694): CM callback handler got msg 524295
,D/ConnectivityService( 3508): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 6720): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 3694): CM callback handler got msg 524295
,I/SignOutReceiver(11356): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityManager.CallbackHandler( 6720): CM callback handler got msg 524295
,I/Hs20UtilService( 4082): Starting #11
,I/Hs20UtilService( 4082): Message received 5007
,D/NearbySettings( 8784): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8784): MountReceiver.onReceive - Keep current state
,I/SignOutReceiver(11356): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4082): Starting #12
,I/Hs20UtilService( 4082): Message received 5007
,D/NearbySettings( 8784): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8784): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8784): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 8784): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8784): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8784): MountReceiver.onReceive - Keep current state
,I/SignOutReceiver(11356): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4082): Starting #13
,I/Hs20UtilService( 4082): Message received 5007
,D/NearbySettings( 8784): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8784): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine( 3508): callSECApi what=220
D/WifiStateMachine( 3508): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/SignOutReceiver(11356): NETWORK_STATE_CHANGED_ACTION
,I/PCWCLIENTTRACE_PushUtil(11765): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11765): sales region : global
I/PCWCLIENTTRACE_PushUtil(11765): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11765): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/SurfaceFlinger( 2849): id=15 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 3508): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3508
,I/DIAGMON_AGENT(11855): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(11855): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/mali_winsys( 3694): new_window_surface returns 0x3000,  [1120x201]-format:1
,I/FOTA_Client(11881): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(11881): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(11881): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.521: (11911): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Dec 23 03:09:31 GMT+01:00 2015
,I/KLMS-2.4.521: (11911): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (11911): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11911): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (11911): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (11911): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (11911): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (11911): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.521: (11911): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.521: (11911): NetworkChangeOperations(): uploadRequestLog().START 
,I/SO_AGENT(11933): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,I/KLMS-2.4.521: (11911): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.4.521: (11911): StateImplV2(): networkChangeListener().END
,I/KLMS-2.4.521: (11911): KLMSIntentService(): onDestroy()
,E/SPPClientService(11981): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      (11204): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11204): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (11204): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (11204): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11204): [OR] == isSIMCardReady false ==
,I/SA      (11204): [SCU] == networkStateCheck == true
I/SA      (11204): [DM] getCountryCodeFromCSC : PL
I/SA      (11204): isChinaCountryCode : false
I/SA      (11204): [SCU] is ChinestModel Data Restricted   : false
I/SA      (11204): [OR] == networkStateCheck true ==
I/SA      (11204): [OR] GetMyCountryZoneTask
,I/SA      (11204): [OR] onReceive END
,I/SA      (11204): [SRS] prepareGetMyCountryZone
,I/SA      (11204): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (11204): [SSP] query invoked
,V/DownloadManager( 3719): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      (11204): [TPMU] GetMccFromDB : null
I/SA      (11204): [SCU] getMccFromPreferece mcc = 260
I/SA      (11204): [TPM] isNoProxy(default) : true
I/SA      (11204): [RC New] Execute method=[GET] start
,I/SCloudBackupReceiver(12005): Other Intent
,D/accuweather( 5211): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3776): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 7
,D/accuweather( 5211): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5211): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5211): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5211): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5211): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5211): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/SA      (11204): [RC New] Security=[true]
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 10045
,I/KnoxUsageLogPro(12021): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro(12021): premStatus:2
,I/KnoxUsageLogPro(12021): isEulaShown : false
I/KnoxUsageLogPro(12021): KnoxUsageReceiver onReceive : not Processible, just return
,D/KeyguardWallpaperUpdator(12054): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12054): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12054): stopCheckCategoryVersion
,D/QuickConnect(12137): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12137): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect(12137): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 3508): exchangeData() failure , invalid userId
,D/RCPManagerService( 3508): exchangeData() failure , invalid userId
,D/hcjo    (12216): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12216): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12216): exit::IDLE
D/InitializeManagerStateMachine(12216): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12216): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12216): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12216): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12216): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12216): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12216): entry::SUCCESS
D/hcjo    (12216): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (12216): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12216): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine(12216): exit::SUCCESS
D/InitializeManagerStateMachine(12216): entry::IDLE
,I/WifiStateMachine( 3508): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine( 3508): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/dhcpcd  (11828): wlan0: sending IPv6 Router Solicitation
,I/SA      (11204): [RC New] [v2liruge] api execute + 613
,I/SA      (11204): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out(11204): AsyncTask #2 calls detatch()
,I/SA      (11204): [TPMU] getNetworkMcc : 
,I/SA      (11204): [SCU] saveMccToPreferece Start
,I/SA      (11204): [SCU] RegionMCC : 260
,I/SA      (11204): [SSP] query invoked
,I/SA      (11204): [TPMU] GetMccFromDB : null
,I/SA      (11204): [SCU] getMccFromPreferece mcc = 260
,I/SA      (11204): [SCU] saveMccToPreferece End
,I/SA      (11204): [RC New] executeRequest [v2liruge] end. 687
,I/SA      (11204): [RC New] Execute end
,I/SA      (11204): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      (11204): [OR] GetMyCountryZoneTask Success
,D/SSRM:n  ( 3508): SIOP:: AP = 280, PST = 282, CUR = 67
,D/WearableService( 4641): callingUid 10014, callindPid: 4641
,D/ResourcesManager(11789): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3508): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:66
D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3508): stay LED for fully charged
,W/ResourcesManager(11789): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11789): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MotionRecognitionService( 3508): Plugged
I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5622): Disconnected process message: 10
,I/GHttpClientFactory(11789): Using the GMSCore's GoogleHttpClient
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MusicLeanback(11789): Conditions not met for autocaching.
I/MusicLeanback(11789): Stop autocaching.
,D/WearableClient(11789): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11789): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11789): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11789): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(11789): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils(11789): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/ActivityThread(11789): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@3539fb79 that was originally bound here
E/ActivityThread(11789): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@3539fb79 that was originally bound here
E/ActivityThread(11789): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(11789): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(11789): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(11789): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(11789): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(11789): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(11789): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11789): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11789): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11789): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(11789): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(11789): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(11789): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(11789): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(11789): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(11789): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(11789): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(11789): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(11789): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(11789): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(11789): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(11789): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(11789): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(11789): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(11789): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/PackageManager( 3508): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/SurfaceFlinger( 2849): id=15 Removed Uoast (8/9)
,I/SurfaceFlinger( 2849): id=15 Removed Uoast (-2/9)
,D/PowerManagerService( 3508): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3508) eventTime = 156313
,D/PowerManagerService( 3508): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3508 (0x0)
D/PowerManagerService( 3508): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3508, ws=WorkSource{10060}) (elapsedTime=3474)
,I/GAV4    (12070): Thread[GAThread,5,main]: No campaign data found.
,I/dhcpcd  (11828): wlan0: sending IPv6 Router Solicitation
,I/PCWCLIENTTRACE_SYSTEMReceiver(11765): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil(11765): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE(11765): ================================================
I/CSTORAGE(11765):  CSTORAGE_SKM_LIB v1.0.15
I/CSTORAGE(11765): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI(11765): [GetString-S]
E/art     (11765): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
W/PCWCLIENTTRACE_SecurePreferencesJNI(11765): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI(11765): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil(11765): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11765): sales region : global
I/PCWCLIENTTRACE_PushUtil(11765): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler(11765): [ensureRegistration] - No Samsung account
,I/dhcpcd  (11828): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  (11828): wlan0: no IPv6 Routers available
,D/PreloadUpdateManagerStateMachine(12216): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(12216): exit::IDLE
,D/PreloadUpdateManagerStateMachine(12216): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (12216): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    (12216): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine(12216): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine(12216): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine(12216): entry::IDLE
,E/Watchdog( 3508): !@Sync 5
,D/PreloadUpdateManagerStateMachine(12216): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(12216): exit::IDLE
D/PreloadUpdateManagerStateMachine(12216): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (12216): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine(12216): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine(12216): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine(12216): entry::IDLE
,D/SSRM:n  ( 3508): SIOP:: AP = 270, PST = 280, CUR = 28
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3508): online:4, current avg:53, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:71
,D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/BatteryService( 3508): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5622): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3508): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 3508): Waited long enough for: ServiceRecord{39e3dbea u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,I/PowerManagerService( 3508): [PWL] Off : 75s ago
,D/SSRM:n  ( 3508): SIOP:: AP = 260, PST = 280, CUR = 53
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3508): online:4, current avg:59, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:60
,D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3508): stay LED for fully charged
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5622): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3508): waitForAlarm result :8,
,I/ClearcutLoggerApiImpl( 4641): disconnect managed GoogleApiClient
,D/SSRM:n  ( 3508): SIOP:: AP = 260, PST = 275, CUR = 59
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3508): online:4, current avg:59, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:49
D/BatteryService( 3508): stay LED for fully charged
D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5622): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3508): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,W/ProcessCpuTracker( 3508): Skipping unknown process pid 12396
,E/Watchdog( 3508): !@Sync 6
,D/SSRM:n  ( 3508): SIOP:: AP = 260, PST = 271, CUR = 59,
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3508): online:4, current avg:57, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:63
D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3508): stay LED for fully charged
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5622): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3508): [PWL] Off : 105s ago
,D/SSRM:n  ( 3508): SIOP:: AP = 260, PST = 268, CUR = 57
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3508): online:4, current avg:53, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
,D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/BatteryService( 3508): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5622): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3508): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3508): SIOP:: AP = 250, PST = 266, CUR = 53
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3508): online:4, current avg:50, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:41
,D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3508): stay LED for fully charged
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5622): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3508): !@Sync 7
,V/AlarmManager( 3508): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3694): handleTimeUpdate
,D/KeyguardEffectViewController( 3694): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3694): *** don't update sliding image ***
,D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 3508): SIOP:: AP = 250, PST = 264, CUR = 50
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3508): online:4, current avg:49, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3508): stay LED for fully charged
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5622): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3508): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3508): [PWL] Off : 140s ago
,D/SSRM:n  ( 3508): SIOP:: AP = 250, PST = 262, CUR = 49
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3508): online:4, current avg:46, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
,D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/BatteryService( 3508): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5622): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3508): waitForAlarm result :8
,D/SSRM:n  ( 3508): SIOP:: AP = 250, PST = 258, CUR = 46
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3508): online:4, current avg:46, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
,D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3508): stay LED for fully charged
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5622): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3508): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3508): !@Sync 8
,D/SSRM:n  ( 3508): SIOP:: AP = 250, PST = 257, CUR = 46
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3508): online:4, current avg:44, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3508): Plugged
I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/BatteryService( 3508): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5622): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3508): SIOP:: AP = 250, PST = 256, CUR = 44
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3508): online:4, current avg:43, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:55
,D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/BatteryService( 3508): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5622): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3508): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3508): [PWL] Off : 180s ago
,D/SSRM:n  ( 3508): SIOP:: AP = 250, PST = 255, CUR = 43
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3508): online:4, current avg:43, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:59
,D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3508): stay LED for fully charged
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5622): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3508): !@Sync 9
,D/SSRM:n  ( 3508): SIOP:: AP = 250, PST = 253, CUR = 43
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3508): online:4, current avg:42, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:42
,D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/BatteryService( 3508): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5622): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3508): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3508): SIOP:: AP = 250, PST = 252, CUR = 42
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3508): online:4, current avg:40, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/BatteryService( 3508): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5622): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11631): Connected to the server!
I/jxcore-log(11631): 
,I/chromium(11631): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/SSRM:n  ( 3508): SIOP:: AP = 250, PST = 252, CUR = 40
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3508): online:4, current avg:38, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3508): stay LED for fully charged
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5622): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3508): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService( 3508): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3508): TimaServiceHandler.handleMessage what =1
,D/TimaService( 3508): TIMA: checkEvent, operation: 50000 subject: 10000,
,I/TLC_TIMA_PKM_initialize( 3508): initializing...
I/TLC_TIMA_PKM_initialize( 3508): root = 0, root_strlen = 1
I/TLC_TIMA_PKM_initialize( 3508): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 3508): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 3508): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 3508): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 3508): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 3508): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 3508): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 3508): device_id = 0x0
I/TZ: mc_tlc_communication( 3508): tlc_open() was called
I/TZ: mc_tlc_communication( 3508): Opening MobiCore device
,I/TZ: mc_tlc_communication( 3508): Allocating WSM for TCI,
,I/TZ: mc_tlc_communication( 3508): Opening the session
,I/TZ: mc_tlc_communication( 3508): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 3508): Trustlet response is completed
,E/Watchdog( 3508): !@Sync 10
,D/SSRM:n  ( 3508): SIOP:: AP = 250, PST = 251, CUR = 38
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3508): online:4, current avg:38, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:51
D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3508): stay LED for fully charged
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,I/TLC_TIMA_PKM_measure_kernel( 3508): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 3508): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5622): Disconnected process message: 10
,D/TimaService( 3508): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3508): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3508): [PWL] Off : 225s ago
,D/SSRM:n  ( 3508): SIOP:: AP = 250, PST = 251, CUR = 38
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3508): online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:41
,D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/BatteryService( 3508): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5622): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3508): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3508): SIOP:: AP = 250, PST = 250, CUR = 37
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3508): online:4, current avg:36, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:34
,D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3508): stay LED for fully charged
,I/MotionRecognitionService( 3508): Plugged
I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5622): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3508): !@Sync 11
,D/SSRM:n  ( 3508): SIOP:: AP = 250, PST = 250, CUR = 36
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3508): online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
,D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/BatteryService( 3508): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5622): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3508): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3508): SIOP:: AP = 240, PST = 249, CUR = 35
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3508): online:4, current avg:36, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/BatteryService( 3508): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5622): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3508): SIOP:: AP = 240, PST = 248, CUR = 36
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3508): online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/BatteryService( 3508): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5622): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3508): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3508): [PWL] Off : 275s ago
,E/Watchdog( 3508): !@Sync 12
,D/SSRM:n  ( 3508): SIOP:: AP = 240, PST = 247, CUR = 35
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3508): online:4, current avg:36, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:49
,D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/BatteryService( 3508): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5622): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3508): SIOP:: AP = 240, PST = 247, CUR = 36
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3508): online:4, current avg:36, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:38
,D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/BatteryService( 3508): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5622): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3508): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3508): SIOP:: AP = 240, PST = 246, CUR = 36
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3508): online:4, current avg:34, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:49
,D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/BatteryService( 3508): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5622): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3508): !@Sync 13
,D/SSRM:n  ( 3508): SIOP:: AP = 240, PST = 245, CUR = 34,
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3508): online:4, current avg:33, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:44
D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3508): stay LED for fully charged
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5622): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3508): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3508): SIOP:: AP = 240, PST = 245, CUR = 33,
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,I/jxcore-log(11631): --- start :testFindPeers.js---
I/jxcore-log(11631): 
,I/jxcore-log(11631): testFindPeers created [object Object]
I/jxcore-log(11631): 
,I/jxcore-log(11631): serverPort is 8876
I/jxcore-log(11631): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): setDiscoveryMode: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11631): start: Peer ID: E0:DB:10:14:E2:C0, peer name: samsung-SM-N910C_PT1003
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11631): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11631): initialize: My bluetooth address is E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(11631): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1003","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11631): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11631): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11631): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter(11631): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(11631): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[115]}
,D/BluetoothSocket(11631): bindListen(), new LocalSocket 
D/BluetoothSocket(11631): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(11631): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2b8384cc
,D/BluetoothSocket(11631): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11631): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11631): start: OK
I/io.jxcore.node.ConnectionHelper(11631): start: Using peer discovery mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): start: Peer ID: E0:DB:10:14:E2:C0, peer name: samsung-SM-N910C_PT1003
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(11631): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1003","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(11631): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11631): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): start: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1003","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11631): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1003","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 3508): InactiveState{ what=139292 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11631): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11631): start: Starting P2P device discovery...
D/WifiP2pService( 3508): P2pEnabledState{ what=139292 }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): startWifiPeerDiscovery: Wi-Fi Direct OK
D/WifiP2pService( 3508): P2pEnabledState add service
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): setState: RUNNING
I/io.jxcore.node.ConnectionHelper(11631): start: OK
,I/jxcore-log(11631): StartBroadcasting started ok
I/jxcore-log(11631): 
D/WifiP2pService( 3508): add a new client
,I/io.jxcore.node.ConnectionHelper(11631): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onWifiStateChanged: State changed to 2
I/io.jxcore.node.ConnectionHelper(11631): onDiscoveryManagerStateChanged: RUNNING
,I/chromium(11631): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
,D/WifiP2pService( 3508): InactiveState{ what=139265 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11631): Local service added successfully
D/WifiP2pService( 3508): P2pEnabledState{ what=139265 }
,D/WifiService( 3508): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/WifiStateMachine( 3508): callSECApi what=74
D/WifiStateMachine( 3508): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3508): callSECApiBoolean - ID [13]
I/wpa_supplicant( 3830): USE_NETWORK : USE_NETWORK OFF
,D/WifiP2pService( 3508): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11631): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11631): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11631): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 3830): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3830): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0,
,D/WifiP2pService( 3508): InactiveState{ what=147477 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3508): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/WifiDisplayController( 3508): Received list of peers.
,D/WifiDisplayController( 3508):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/WifiP2pService( 3508): InactiveState{ what=147477 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onP2pDeviceListChanged: 1 device(s) discovered
D/WifiP2pService( 3508): P2pEnabledState{ what=147477 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 1: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pService( 3508): InactiveState{ what=139301 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139301 }
D/WifiP2pService( 3508): P2pEnabledState add service request
D/WifiDisplayController( 3508): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
D/WifiP2pManager(11631): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): Service request added successfully
D/WifiP2pService( 3508): DefaultState{ what=139283 }
D/WifiDisplayController( 3508): Received list of peers.
,D/WifiDisplayController( 3508):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3508): InactiveState{ what=139283 }
D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,V/AlarmManager( 3508): waitForAlarm result :8
,D/WifiP2pService( 3508): InactiveState{ what=139310 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3508): P2pEnabledState discover services
,D/WifiService( 3508): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3508): callSECApi what=74
,D/WifiStateMachine( 3508): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3508): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3830): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): Service discovery started successfully
,D/WifiP2pService( 3508): InactiveState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6438","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
,I/io.jxcore.node.ConnectionHelper(11631): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], Bluetooth address: F8:95:C7:87:85:54, device name: , device address: a2:39:f7:70:12:80
,D/io.jxcore.node.ConnectionHelper(11631): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438] is available
,I/jxcore-log(11631): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"LGE-LG-D722_PT6438","peerAvailable":true}]
I/jxcore-log(11631): 
,I/jxcore-log(11631): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log(11631): 
,I/jxcore-log(11631): weAreDoneNow
I/jxcore-log(11631): 
,I/jxcore-log(11631): done, now sending data to server
I/jxcore-log(11631): 
,I/PowerManagerService( 3508): [PWL] Off : 330s ago
,D/SSRM:n  ( 3508): SIOP:: AP = 240, PST = 245, CUR = 33
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3508): online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:51
D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3508): stay LED for fully charged
,I/MotionRecognitionService( 3508): Plugged
I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5622): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3508): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/wpa_supplicant( 3830): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3830): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3508): InactiveState{ what=147477 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3508): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/WifiDisplayController( 3508): Received list of peers.
,D/WifiDisplayController( 3508):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onP2pDeviceListChanged: 3 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pService( 3508): InactiveState{ what=147477 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3508): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3508): InactiveState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6068","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
I/io.jxcore.node.ConnectionHelper(11631): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper(11631): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068] is available
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/WifiDisplayController( 3508): Received list of peers.
D/WifiDisplayController( 3508):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3508): InactiveState{ what=139283 }
D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onP2pDeviceListChanged: 4 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,E/Watchdog( 3508): !@Sync 14
,D/SSRM:n  ( 3508): SIOP:: AP = 240, PST = 244, CUR = 31,
,I/wpa_supplicant( 3830): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3508): InactiveState{ what=147477 },
,D/WifiP2pService( 3508): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3508): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/WifiDisplayController( 3508): Received list of peers.
,D/WifiDisplayController( 3508):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onP2pDeviceListChanged: 5 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): restart: Restarting...
,D/WifiP2pService( 3508): InactiveState{ what=139307 }
D/WifiP2pService( 3508): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3508): P2pEnabledState clear service request
,D/WifiP2pService( 3508): InactiveState{ what=139301 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139301 }
D/WifiP2pService( 3508): P2pEnabledState add service request
,D/WifiP2pManager(11631): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): Service request added successfully
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/WifiP2pService( 3508): InactiveState{ what=139310 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3508): P2pEnabledState discover services
,D/WifiService( 3508): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3508): callSECApi what=74
,D/WifiStateMachine( 3508): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3508): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3830): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): Service discovery started successfully
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3508): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/BatteryService( 3508): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5622): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/wpa_supplicant( 3830): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3508): InactiveState{ what=147477 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3508): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/WifiDisplayController( 3508): Received list of peers.
D/WifiDisplayController( 3508):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,D/SSRM:n  ( 3508): SIOP:: AP = 240, PST = 243, CUR = 32
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3508): online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/BatteryService( 3508): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5622): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3508): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/wpa_supplicant( 3830): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3508): InactiveState{ what=147477 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3508): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3508): InactiveState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3911","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
,I/io.jxcore.node.ConnectionHelper(11631): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
,D/io.jxcore.node.ConnectionHelper(11631): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3911] is available
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/WifiDisplayController( 3508): Received list of peers.
,D/WifiDisplayController( 3508):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onP2pDeviceListChanged: 6 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): restart: Restarting...
,D/WifiP2pService( 3508): InactiveState{ what=139307 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3508): P2pEnabledState clear service request
,D/WifiP2pService( 3508): InactiveState{ what=139301 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139301 }
D/WifiP2pService( 3508): P2pEnabledState add service request
,D/WifiP2pManager(11631): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): Service request added successfully
,I/wpa_supplicant( 3830): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3508): InactiveState{ what=147477 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3508): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/WifiDisplayController( 3508): Received list of peers.
,D/WifiDisplayController( 3508):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onP2pDeviceListChanged: 7 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
,D/SSRM:n  ( 3508): SIOP:: AP = 240, PST = 243, CUR = 31,
,D/WifiP2pService( 3508): InactiveState{ what=139310 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3508): P2pEnabledState discover services
,D/WifiService( 3508): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3508): callSECApi what=74
,D/WifiStateMachine( 3508): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3508): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3830): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): Service discovery started successfully
,D/WifiP2pService( 3508): InactiveState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147494 }
D/WifiP2pService( 3508): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3911","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
I/io.jxcore.node.ConnectionHelper(11631): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper(11631): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3911] already in the list, will not add again
,D/WifiP2pService( 3508): InactiveState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7855","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
I/io.jxcore.node.ConnectionHelper(11631): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper(11631): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855] is available
,D/WifiP2pService( 3508): InactiveState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6068","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
I/io.jxcore.node.ConnectionHelper(11631): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper(11631): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068] already in the list, will not add again
,D/WifiP2pService( 3508): InactiveState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT1715","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
,I/io.jxcore.node.ConnectionHelper(11631): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
D/io.jxcore.node.ConnectionHelper(11631): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715] is available
,D/WifiP2pService( 3508): InactiveState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT4270","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
I/io.jxcore.node.ConnectionHelper(11631): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper(11631): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270] is available
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3508): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/BatteryService( 3508): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5622): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/wpa_supplicant( 3830): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3508): InactiveState{ what=147477 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3508): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/WifiDisplayController( 3508): Received list of peers.
,D/WifiDisplayController( 3508):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onP2pDeviceListChanged: 8 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068],
,D/WifiP2pService( 3508): InactiveState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6545","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
,I/io.jxcore.node.ConnectionHelper(11631): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
,D/io.jxcore.node.ConnectionHelper(11631): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545] is available
,E/Watchdog( 3508): !@Sync 15
,I/wpa_supplicant( 3830): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3508): InactiveState{ what=147477 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3508): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/WifiDisplayController( 3508): Received list of peers.
,D/WifiDisplayController( 3508):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onP2pDeviceListChanged: 8 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3911],
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
,I/wpa_supplicant( 3830): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3508): InactiveState{ what=147477 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3508): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/WifiDisplayController( 3508): Received list of peers.
,D/WifiDisplayController( 3508):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiDisplayController( 3508):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 3508):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onP2pDeviceListChanged: 9 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 3508): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 3508): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): restart: Restarting...
D/WifiP2pService( 3508): P2pEnabledState clear service request
,D/WifiP2pService( 3508): InactiveState{ what=139301 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139301 }
D/WifiP2pService( 3508): P2pEnabledState add service request
,D/WifiP2pManager(11631): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): Service request added successfully
,D/SSRM:n  ( 3508): SIOP:: AP = 240, PST = 243, CUR = 32,
,D/WifiP2pService( 3508): InactiveState{ what=139310 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3508): P2pEnabledState discover services
,D/WifiService( 3508): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3508): callSECApi what=74
,D/WifiStateMachine( 3508): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3508): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3830): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): Service discovery started successfully
,W/ContextImpl( 3508): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3508): online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3508): stay LED for fully charged
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5622): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/wpa_supplicant( 3830): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3830): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3508): InactiveState{ what=147477 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3508): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3508): InactiveState{ what=139283 },
D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
D/WifiDisplayController( 3508): Received list of peers.
,D/WifiDisplayController( 3508):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3508): InactiveState{ what=147477 }
D/WifiP2pService( 3508): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 3508): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onP2pDeviceListChanged: 9 device(s) discovered
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 3508): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 3508):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], add/update: true
D/WifiDisplayController( 3508):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
D/WifiDisplayController( 3508):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
,D/WifiDisplayController( 3508):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 3508):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 3508):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
,D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/WifiDisplayController( 3508):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 3508): InactiveState{ what=139283 }
D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onP2pDeviceListChanged: 9 device(s) discovered
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
,D/SSRM:n  ( 3508): SIOP:: AP = 240, PST = 242, CUR = 31
,I/wpa_supplicant( 3830): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3830): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3508): InactiveState{ what=147477 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3508): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/WifiDisplayController( 3508): Received list of peers.
,D/WifiDisplayController( 3508):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3508): InactiveState{ what=147477 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3508): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): restart: Restarting...
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/WifiDisplayController( 3508): Received list of peers.
,D/WifiDisplayController( 3508):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 3508): InactiveState{ what=139307 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3508): P2pEnabledState clear service request
,D/WifiP2pService( 3508): InactiveState{ what=139301 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139301 }
D/WifiP2pService( 3508): P2pEnabledState add service request
,D/WifiP2pManager(11631): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): Service request added successfully
,I/wpa_supplicant( 3830): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3508): InactiveState{ what=147477 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3508): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/WifiDisplayController( 3508): Received list of peers.
,D/WifiDisplayController( 3508):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3508): InactiveState{ what=139310 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3508): P2pEnabledState discover services
,D/WifiService( 3508): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3508): callSECApi what=74
,D/WifiStateMachine( 3508): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3508): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3830): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): Service discovery started successfully
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3508): online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
D/BatteryService( 3508): stay LED for fully charged
D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5622): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/WifiP2pService( 3508): InactiveState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3911","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
,I/io.jxcore.node.ConnectionHelper(11631): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper(11631): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3911] already in the list, will not add again
,D/WifiP2pService( 3508): InactiveState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7855","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
I/io.jxcore.node.ConnectionHelper(11631): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
,W/io.jxcore.node.ConnectionHelper(11631): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855] already in the list, will not add again
,I/PowerManagerService( 3508): [PWL] Off : 390s ago
,D/SSRM:n  ( 3508): SIOP:: AP = 240, PST = 242, CUR = 30
,W/ContextImpl( 3508): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3508): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
,D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3508): stay LED for fully charged
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5622): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3508): !@Sync 16
,D/SSRM:n  ( 3508): SIOP:: AP = 240, PST = 241, CUR = 29
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3508): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/BatteryService( 3508): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5622): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3508): SIOP:: AP = 240, PST = 241, CUR = 28
,W/ContextImpl( 3508): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11631): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11631): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11631): setState: RESTARTING
,D/WifiP2pService( 3508): InactiveState{ what=139268 }
,I/wpa_supplicant( 3830): P2P-FIND-STOPPED 
,D/WifiP2pService( 3508): InactiveState{ what=147493 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3508): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11631): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3508): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3508): Plugged,
I/MotionRecognitionService( 3508): setPowerConnected  = true
D/BatteryService( 3508): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5622): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11631): Start timer timeout, starting now...
,D/WifiP2pService( 3508): InactiveState{ what=139265 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139265 }
,D/WifiService( 3508): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3508): callSECApi what=74
,D/WifiStateMachine( 3508): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3508): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3830): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11631): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11631): setState: STARTED
,D/WifiP2pService( 3508): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11631): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 3830): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3508): InactiveState{ what=147477 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3508): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/WifiDisplayController( 3508): Received list of peers.
,D/WifiDisplayController( 3508):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onP2pDeviceListChanged: 11 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): restart: Restarting...
,D/WifiP2pService( 3508): InactiveState{ what=139307 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3508): P2pEnabledState clear service request
,D/WifiP2pService( 3508): InactiveState{ what=139301 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 3508): P2pEnabledState add service request
,D/WifiP2pManager(11631): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): Service request added successfully
,D/WifiP2pService( 3508): InactiveState{ what=139310 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3508): P2pEnabledState discover services
,D/WifiService( 3508): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3508): callSECApi what=74
,D/WifiStateMachine( 3508): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3508): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3830): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): Service discovery started successfully
,D/SSRM:n  ( 3508): SIOP:: AP = 240, PST = 241, CUR = 28
,D/WifiP2pService( 3508): InactiveState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6438","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
I/io.jxcore.node.ConnectionHelper(11631): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
,W/io.jxcore.node.ConnectionHelper(11631): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438] already in the list, will not add again
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3508): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
,D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/BatteryService( 3508): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5622): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/wpa_supplicant( 3830): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3508): InactiveState{ what=147477 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 3508): InactiveState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147494 }
D/WifiDisplayController( 3508): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3508): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT1715","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
D/WifiP2pService( 3508): InactiveState{ what=139283 }
I/io.jxcore.node.ConnectionHelper(11631): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper(11631): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715] already in the list, will not add again
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
D/WifiDisplayController( 3508): Received list of peers.
,D/WifiDisplayController( 3508):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3508): InactiveState{ what=139283 }
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 3508):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onP2pDeviceListChanged: 11 device(s) discovered
D/WifiDisplayController( 3508):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/WifiDisplayController( 3508):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 3508): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
,I/wpa_supplicant( 3830): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,D/WifiP2pService( 3508): InactiveState{ what=147477 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3508): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/WifiDisplayController( 3508): Received list of peers.
,D/WifiDisplayController( 3508):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 3508): InactiveState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7855","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
,I/io.jxcore.node.ConnectionHelper(11631): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
,W/io.jxcore.node.ConnectionHelper(11631): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855] already in the list, will not add again
,E/Watchdog( 3508): !@Sync 17
,D/WifiP2pService( 3508): InactiveState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4998","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onServiceDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Adding new peer: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
,I/io.jxcore.node.ConnectionHelper(11631): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998], Bluetooth address: 44:80:EB:7B:5A:05, device name: , device address: 44:80:eb:7b:5a:07
D/io.jxcore.node.ConnectionHelper(11631): notifyPeerAvailability: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4998] is available
,D/SSRM:n  ( 3508): SIOP:: AP = 240, PST = 240, CUR = 27
,I/wpa_supplicant( 3830): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/WifiP2pService( 3508): InactiveState{ what=147477 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147477 }
,W/ContextImpl( 3508): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/WifiDisplayController( 3508): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/WifiDisplayController( 3508): Received list of peers.
,D/WifiDisplayController( 3508):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 3508):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): restart: Restarting...
,D/WifiP2pService( 3508): InactiveState{ what=139307 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3508): P2pEnabledState clear service request
,D/WifiP2pService( 3508): InactiveState{ what=139301 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 3508): P2pEnabledState add service request
,D/WifiP2pManager(11631): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): Service request added successfully
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3508): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3508): stay LED for fully charged
,I/MotionRecognitionService( 3508): Plugged,
I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5622): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/WifiP2pService( 3508): InactiveState{ what=139310 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3508): P2pEnabledState discover services
,D/WifiService( 3508): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3508): callSECApi what=74
,D/WifiStateMachine( 3508): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3508): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3830): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): Service discovery started successfully
,D/WifiP2pService( 3508): InactiveState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4998","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onServiceDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
,I/io.jxcore.node.ConnectionHelper(11631): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998], Bluetooth address: 44:80:EB:7B:5A:05, device name: XT1072_23d5, device address: 44:80:eb:7b:5a:07
,W/io.jxcore.node.ConnectionHelper(11631): modifyListOfDiscoveredPeers: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4998] already in the list, will not add again
,D/SSRM:n  ( 3508): SIOP:: AP = 240, PST = 240, CUR = 28
,I/wpa_supplicant( 3830): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3508): InactiveState{ what=147477 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3508): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/WifiDisplayController( 3508): Received list of peers.
,D/WifiDisplayController( 3508):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): restart: Restarting...
,D/WifiP2pService( 3508): InactiveState{ what=139307 }
D/WifiP2pService( 3508): P2pEnabledState{ what=139307 }
D/WifiP2pService( 3508): P2pEnabledState clear service request
D/WifiP2pService( 3508): InactiveState{ what=139301 }
D/WifiP2pService( 3508): P2pEnabledState{ what=139301 }
D/WifiP2pService( 3508): P2pEnabledState add service request
D/WifiP2pManager(11631): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): Service request added successfully
,I/jxcore-log(11631): teardown
I/jxcore-log(11631): 
,I/jxcore-log(11631): testFindPeers stopped
I/jxcore-log(11631): 
,I/io.jxcore.node.ConnectionHelper(11631): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11631): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11631): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11631): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11631): shutdown
,D/BluetoothSocket(11631): close() in, this: android.bluetooth.BluetoothSocket@3dca21b8, channel: 6, state: LISTENING
D/BluetoothSocket(11631): close() this: android.bluetooth.BluetoothSocket@3dca21b8, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2b8384cc, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@31a69b91mSocket: android.net.LocalSocket@a7c9af6 impl:android.net.LocalSocketImpl@3e891ef7 fd:FileDescriptor[115]
D/BluetoothSocket(11631): Closing mSocket: android.net.LocalSocket@a7c9af6 impl:android.net.LocalSocketImpl@3e891ef7 fd:FileDescriptor[115]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11631): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11631): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11631): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11631): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): stop: Stopping services
,D/WifiP2pService( 3508): InactiveState{ what=139298 }
D/WifiP2pService( 3508): P2pEnabledState{ what=139298 }
,D/WifiP2pService( 3508): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11631): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11631): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(11631): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11631): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11631): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): setState: NOT_STARTED
,I/jxcore-log(11631): StopBroadcasting went ok
I/jxcore-log(11631): 
D/WifiP2pService( 3508): InactiveState{ what=139268 }
I/wpa_supplicant( 3830): P2P-FIND-STOPPED 
,I/io.jxcore.node.ConnectionHelper(11631): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper(11631): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11631): Local services cleared successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11631): P2P device discovery stopped successfully
D/WifiP2pService( 3508): InactiveState{ what=139307 }
I/chromium(11631): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
D/WifiP2pService( 3508): P2pEnabledState{ what=139307 }
D/WifiP2pService( 3508): P2pEnabledState clear service request
,D/WifiP2pService( 3508): remove channel information from framework
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): Service requests cleared successfully
,I/jxcore-log(11631): --- start :testSendData.js---
I/jxcore-log(11631): 
,D/WifiP2pService( 3508): InactiveState{ what=147493 }
D/WifiP2pService( 3508): P2pEnabledState{ what=147493 }
D/WifiP2pService( 3508): discovery change broadcast false
,I/jxcore-log(11631): testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":14}bt-address length : 0
I/jxcore-log(11631): 
,I/jxcore-log(11631): check server
I/jxcore-log(11631): 
,I/jxcore-log(11631): serverPort is 54681
I/jxcore-log(11631): 
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): setDiscoveryMode: Mode set to BLE
D/BatteryService( 3508): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): setDiscoveryMode: Mode set to WIFI
D/BatteryService( 3508): stay LED for fully charged
D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3508): Plugged
I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5622): Disconnected process message: 10
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11631): start: Peer ID: E0:DB:10:14:E2:C0, peer name: samsung-SM-N910C_PT1003
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11631): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11631): initialize: My bluetooth address is E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(11631): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1003","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11631): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11631): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11631): startListeningForIncomingConnections: Starting...
W/BluetoothAdapter(11631): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothSocket(11631): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[116]}
D/BluetoothSocket(11631): bindListen(), new LocalSocket 
D/BluetoothSocket(11631): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(11631): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3d085fcd
D/BluetoothSocket(11631): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11631): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11631): start: OK
I/io.jxcore.node.ConnectionHelper(11631): start: Using peer discovery mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11631): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): start: Peer ID: E0:DB:10:14:E2:C0, peer name: samsung-SM-N910C_PT1003
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(11631): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1003","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(11631): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): start: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1003","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11631): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1003","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/WifiP2pService( 3508): InactiveState{ what=139292 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139292 }
D/WifiP2pService( 3508): P2pEnabledState add service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11631): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11631): start: Starting P2P device discovery...
D/WifiP2pService( 3508): add a new client
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): setState: RUNNING
I/io.jxcore.node.ConnectionHelper(11631): start: OK
,I/jxcore-log(11631): StartBroadcasting started ok
I/jxcore-log(11631): 
D/WifiP2pService( 3508): InactiveState{ what=139265 }
D/WifiP2pService( 3508): P2pEnabledState{ what=139265 }
I/WifiStateMachine( 3508): callSECApi what=74
D/WifiService( 3508): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 3508): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3508): callSECApiBoolean - ID [13]
I/wpa_supplicant( 3830): USE_NETWORK : USE_NETWORK OFF
I/jxcore-log(11631): null
I/jxcore-log(11631): 
,D/WifiP2pService( 3508): discovery change broadcast true
,I/jxcore-log(11631): 2015-12-23T02:15:57.062Z SendDataTCPServer.js: TCP/IP server is bound to port: 54681
I/jxcore-log(11631): 
,I/io.jxcore.node.ConnectionHelper(11631): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onWifiStateChanged: State changed to 2
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11631): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11631): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11631): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper(11631): onDiscoveryManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11631): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11631): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11631): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11631): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/WifiP2pService( 3508): InactiveState{ what=139268 }
I/wpa_supplicant( 3830): P2P-FIND-STOPPED 
,I/chromium(11631): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
D/WifiP2pService( 3508): InactiveState{ what=147493 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11631): P2P device discovery stopped successfully
D/WifiP2pService( 3508): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3508): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11631): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11631): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11631): setState: RESTARTING
,D/WifiP2pService( 3508): InactiveState{ what=139268 }
,D/WifiP2pService( 3508): InactiveState{ what=139310 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3508): P2pEnabledState discover services
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): Failed to start the service discovery, got error code: 3
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11631): Start timer timeout, starting now...
,D/WifiP2pService( 3508): InactiveState{ what=139265 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139265 }
,D/WifiService( 3508): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3508): callSECApi what=74
,D/WifiStateMachine( 3508): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3508): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3830): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11631): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11631): setState: STARTED
,D/WifiP2pService( 3508): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11631): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/SSRM:n  ( 3508): SIOP:: AP = 240, PST = 240, CUR = 28
,I/wpa_supplicant( 3830): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3508): InactiveState{ what=147477 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147477 },
,D/WifiDisplayController( 3508): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/WifiDisplayController( 3508): Received list of peers.
,D/WifiDisplayController( 3508):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 3508): InactiveState{ what=139301 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 3508): P2pEnabledState add service request
,D/WifiP2pManager(11631): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): Service request added successfully
,D/WifiP2pService( 3508): InactiveState{ what=139310 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3508): P2pEnabledState discover services
,D/WifiService( 3508): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3508): callSECApi what=74
D/WifiStateMachine( 3508): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3508): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3830): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): Service discovery started successfully
,W/ContextImpl( 3508): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3508): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3508): stay LED for fully charged
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5622): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/wpa_supplicant( 3830): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3830): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3830): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3508): InactiveState{ what=147477 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 3508): InactiveState{ what=147477 },
D/WifiDisplayController( 3508): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 3508): P2pEnabledState{ what=147477 },
,D/WifiDisplayController( 3508): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3508): InactiveState{ what=147477 }
D/WifiP2pService( 3508): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiDisplayController( 3508): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3508): DefaultState{ what=139283 }
D/WifiDisplayController( 3508): Received list of peers.
,D/WifiDisplayController( 3508):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiDisplayController( 3508):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 3508): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 3508):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 3508):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 3508):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 3508):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 3508):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiDisplayController( 3508):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 3508):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 3508):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 3508): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/WifiDisplayController( 3508): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 3508): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 3508):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 3508):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 3508):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/WifiDisplayController( 3508):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 3508): InactiveState{ what=147494 },
,D/WifiP2pService( 3508): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6438","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
,I/io.jxcore.node.ConnectionHelper(11631): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper(11631): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438] already in the list, will not add again
,I/PowerManagerService( 3508): [PWL] Off : 455s ago
,E/Watchdog( 3508): !@Sync 18
,D/IOP_DB_BT( 5622): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 5622): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 5622): db_query_add_key: key KEY_LMP_VER, value 7:24841,
,D/IOP_DB_BT( 5622): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 5622): db_query_execute: result 1
,D/IOP_DB_BT( 5622): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 5622): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 5622): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 5622): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 5622): db_query_execute: result 1
,W/bt-btif ( 5622): info:x10
,D/        ( 5622): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 5622): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 8784): Received android.bluetooth.device.action.NAME_CHANGED
,D/SSRM:n  ( 3508): SIOP:: AP = 240, PST = 240, CUR = 29
,I/BluetoothBondStateMachine( 5622): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
,V/BluetoothEventManager( 8784): Received android.bluetooth.device.action.NAME_CHANGED
,D/SecContentProvider( 3508): uri = 4 selection = bluetoothLogForRemote
,E/bt-btif ( 5622): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 5622): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11,
D/BtConfig.SecureMode( 5622): isSecureModeOn:false
I/BluetoothBondStateMachine( 5622): Entering PendingCommandState State
,D/BluetoothTile( 3694):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 3694):  handleUpdatestate:false name:null
,V/BluetoothEventManager( 8784): Received android.bluetooth.device.action.CLASS_CHANGED
,V/BluetoothEventManager( 8784): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothNotiBroadcastReceiver( 8784): onReceive
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 3508): Start proc com.sec.android.automotive.drivelink for broadcast com.sec.android.automotive.drivelink/.common.receiver.AutoLaunchReceiver: pid=12807 uid=10102 gids={50102, 9997, 3002, 1028, 1015, 3001, 3003} abi=armeabi-v7a
,E/Zygote  (12807): MountEmulatedStorage()
I/libpersona(12807): KNOX_SDCARD checking this for 10102
E/Zygote  (12807): v2
I/libpersona(12807): KNOX_SDCARD not a persona
,I/SELinux (12807): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/art     ( 2877): WaitForGcToComplete blocked for 10.927ms for cause Explicit
,I/SELinux (12807): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12807): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/btif_config_util( 5622): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 5622): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 5622): Failed to remove device: F8:95:C7:87:3C:51
,D/SecContentProvider( 3508): uri = 4 selection = bluetoothLogForRemote
,I/BluetoothBondStateMachine( 5622): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
D/BtConfig.SecureMode( 5622): isSecureModeOn:false
,V/BluetoothEventManager( 8784): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 8762(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 928us total 26.383ms
,D/BluetoothTile( 3694):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 3694):  handleUpdatestate:false name:null
,D/TimaKeyStoreProvider(12807): TimaSignature is unavailable
,D/ActivityThread(12807): Added TimaKeyStore provider
,W/bt-btif ( 5622): new conn_srvc id:26, app_id:255
W/bt-btif ( 5622): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 5622): bta_dm_pm_ssr:2, lat:1200
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.221ms total 22.663ms
,D/BluetoothSocket(11631): socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@3b636fd0
,E/BluetoothRemoteDevices( 5622): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11631): Incoming connection accepted
,D/HidService( 5622): getHidService(): returning com.android.bluetooth.hid.HidService@3d9d1a14
,D/SettingsProvider( 3508): name = bluetooth_input_device_priority_F8:95:C7:87:3C:51
D/SettingsProvider( 3508): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3508): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3508): selectionArgs: false
D/SettingsProvider( 3508): selectionArgs: 1002
D/SecContentProvider( 3508): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3508): ret = -1
,D/HidService( 5622): Saved priority F8:95:C7:87:3C:51 = -1
,D/SettingsProvider( 3508): name = bluetooth_a2dp_sink_priority_F8:95:C7:87:3C:51
,D/SettingsProvider( 3508): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 3508): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 3508): selectionArgs: false
D/SettingsProvider( 3508): selectionArgs: 1002
D/SecContentProvider( 3508): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 3508): ret = -1
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11631): Incoming connection initialized (thread ID: 1629)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11631): Waiting for incoming connections...
,D/SettingsProvider( 3508): name = bluetooth_headset_priority_F8:95:C7:87:3C:51
D/SettingsProvider( 3508): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3508): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3508): selectionArgs: false
D/SettingsProvider( 3508): selectionArgs: 1002
D/SecContentProvider( 3508): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3508): ret = -1
,I/BluetoothBondStateMachine( 5622): StableState(): Entering Off State
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread(11631): Entering thread (ID: 1629)
D/ResourcesManager(12807): creating new AssetManager and set to /system/app/DriveLink/DriveLink.apk
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11631): onBytesRead: Read 77 bytes successfully (thread ID: 1629)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11631): Got valid identity from [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11631): onBytesWritten: 82 bytes successfully written (thread ID: 1629)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11631): removeThreadFromList: Removing thread with ID 1629
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11631): Handshake thread disposed (thread ID: 1629)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11631): onIncomingConnectionConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread(11631): Exiting thread (ID: 1629)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11631): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
I/io.jxcore.node.ConnectionHelper(11631): onConnected: Incoming connection to peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
D/io.jxcore.node.ConnectionHelper(11631): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
W/io.jxcore.node.ConnectionHelper(11631): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855] already in the list, will not add again
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 836us total 24.066ms
,W/ResourcesManager(12807): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/io.jxcore.node.ConnectionHelper(11631): onConnected: Incoming socket thread, for peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], created successfully
D/io.jxcore.node.ConnectionHelper(11631): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread(11631): Entering thread (ID: 1630)
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 10527
,I/io.jxcore.node.IncomingSocketThread(11631): Local host address: localhost/127.0.0.1, port: 54681
,D/io.jxcore.node.IncomingSocketThread(11631): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread(11631): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread(11631): setBufferSize: Setting buffer size to 8192 bytes
I/jxcore-log(11631): 2015-12-23T02:16:14.432Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log(11631): 
,D/io.jxcore.node.StreamCopyingThread(11631): Entering thread (ID: 1631, name: Sender)
I/io.jxcore.node.IncomingSocketThread(11631): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread(11631): Exiting thread (ID: 1630)
,D/io.jxcore.node.StreamCopyingThread(11631): Entering thread (ID: 1632, name: Receiver)
,E/[CarMode](12807): [DLApplication]-onCreate: Applicatino Started!
,D/SampleAppCoreManager(12807): SampleAppCoreManager VACVersion '2.2.0.11867'
D/SampleAppCoreManager(12807): mContext is not null
,I/VlingoAndroidCore(12807): AppName: SamsungCCTproject, Core: 2.2.0.11867, SDK: 2.0.1017, EDM:11867
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12839): MountEmulatedStorage()
I/libpersona(12839): KNOX_SDCARD checking this for 10034
E/Zygote  (12839): v2
I/libpersona(12839): KNOX_SDCARD not a persona
,I/SELinux (12839): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12839): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3508): Start proc com.vlingo.midas for content provider com.vlingo.midas/.provider.VlingoConfigProvider: pid=12839 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,E/SELinux (12839): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12839): TimaSignature is unavailable
,D/ActivityThread(12839): Added TimaKeyStore provider
,D/ResourcesManager(12839): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,I/System.out(12839): Inside WakeupProvider
,E/DatabaseUtils(12839): Writing exception to parcel
E/DatabaseUtils(12839): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils(12839): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils(12839): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils(12839): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1535)
E/DatabaseUtils(12839): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils(12839): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils(12839): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils(12839): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/DatabaseUtils(12839): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/DatabaseUtils(12839): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils(12839): 	at android.os.Binder.execTransact(Binder.java:446)
W/System.err(12807): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
,W/System.err(12807): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err(12807): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err(12807): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err(12807): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err(12807): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err(12807): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err(12807): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err(12807): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err(12807): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err(12807): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err(12807): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err(12807): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err(12807): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterLanguage(InternalMdsoUtils.java:134)
W/System.err(12807): 	at com.vlingo.core.internal.lmtt.event.LmttEventHandler.onCoreInitialization(LmttEventHandler.java:176)
W/System.err(12807): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:625)
W/System.err(12807): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:118)
W/System.err(12807): 	at com.vlingo.core.facade.CoreManager.initCore(CoreManager.java:70)
W/System.err(12807): 	at com.nuance.sample.coreaccess.SampleAppCoreManager.initCore(SampleAppCoreManager.java:131)
W/System.err(12807): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:197)
W/System.err(12807): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:126)
W/System.err(12807): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err(12807): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
W/System.err(12807): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
,W/System.err(12807): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
W/System.err(12807): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(12807): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(12807): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
W/System.err(12807): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err(12807): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err(12807): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err(12807): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/DatabaseUtils(12839): Writing exception to parcel
E/DatabaseUtils(12839): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils(12839): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils(12839): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils(12839): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1535)
E/DatabaseUtils(12839): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils(12839): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils(12839): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils(12839): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/DatabaseUtils(12839): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/DatabaseUtils(12839): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils(12839): 	at android.os.Binder.execTransact(Binder.java:446)
W/System.err(12807): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
W/System.err(12807): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err(12807): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err(12807): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err(12807): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err(12807): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err(12807): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err(12807): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err(12807): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err(12807): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err(12807): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err(12807): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err(12807): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err(12807): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.otherMasterExists(InternalMdsoUtils.java:98)
W/System.err(12807): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.isSlave(InternalMdsoUtils.java:32)
W/System.err(12807): 	at com.vlingo.core.facade.lmtt.MdsoUtils.isSlave(MdsoUtils.java:13)
W/System.err(12807): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:242)
W/System.err(12807): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:126)
W/System.err(12807): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err(12807): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
W/System.err(12807): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
W/System.err(12807): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
W/System.err(12807): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(12807): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(12807): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
W/System.err(12807): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err(12807): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err(12807): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err(12807): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/[CarMode](12807): [DLApplication]-Init Called!:false
W/[CarMode](12807): [CommonUtil]-=========================================
W/[CarMode](12807): [CommonUtil]-CarMode Version:1.10.38.19768
W/[CarMode](12807): [CommonUtil]-=========================================
E/[CarMode](12807): [DLApplication]-Init Started!:true
I/[CarModeFW](12807): DriveLinkServiceInterfaceImp-drivelink framework initialize start
I/[CarModeFW](12807): ### com.sec.android.app.automotive.carmode.framework.DriveLinkServiceInterfaceImp::initialize(132)
I/[CarModeFW](12807): ### com.sec.android.automotive.drivelink.DLApplication::init(211)
I/[CarModeFW](12807): ### com.sec.android.automotive.drivelink.DLApplication::onCreate(135)
I/[CarModeFW](12807): ### android.app.Instrumentation::callApplicationOnCreate(1020)
I/[CarModeFW](12807): ### android.app.ActivityThread::handleBindApplication(5115)
I/[CarModeFW](12807): ### android.app.ActivityThread::access$1600(178)
I/[CarModeFW](12807): ### android.app.ActivityThread$H::handleMessage(1510)
I/[CarModeFW](12807): ### android.os.Handler::dispatchMessage(102)
I/[CarModeFW](12807): ### android.os.Looper::loop(145)
I/[CarModeFW](12807): ### android.app.ActivityThread::main(5944)
I/[CarModeFW](12807): ### java.lang.reflect.Method::invoke(372)
I/[CarModeFW](12807): ### com.android.internal.os.ZygoteInit$MethodAndArgsCaller::run(1399)
I/[CarModeFW](12807): ### com.android.internal.os.ZygoteInit::main(1194)
I/VlingoApplication(12839): VlingoApplication appVersion ='11.7.0.1.39589', coreVersion = '2.5.2.15201', ro.csc.sales_code=XEO
I/MessageDataHandler(12807): initialize
D/[CarModeFW](12807): CDH-initiazlieCaches : before sync
D/[CarModeFW](12807): CDH-initiazlieCaches : after sync
,I/VlingoAndroidCore(12839): AppName: SamsungTproject, Core: 2.5.2.15201, SDK: 2.0.1657, EDM:15201
D/[CarModeFW](12807): CDH-buildContactCacheWireFrame : cur len =0
D/[CarModeFW](12807): CDH-ContactDataHandler initiazlieCaches time : 21
D/[CarModeFW](12807): CDH-initiazlieCaches : end sync
D/[CarModeFW](12807): DrivingManager-initialize...
I/SensorService( 3508): Skipped sensor HRMLED IR because it requires permission com.samsung.permission.SSENSOR_HRM_RAW_PPG
I/SensorService( 3508): Skipped sensor HRMLED RED because it requires permission com.samsung.permission.SSENSOR_HRM_RAW_PPG
I/SensorService( 3508): Skipped sensor MAX86902 because it requires permission 
I/SensorService( 3508): Skipped sensor HRM Sensor because it requires permission 
I/SensorService( 3508): Skipped sensor HeartRate Sensor because it requires permission android.permission.BODY_SENSORS
,D/VlingoApplication(12839): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,D/VlingoApplication(12839): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,D/DialogFlow(12839): initQueue()
,I/MediaPlayer(12807): Need to enable context aware info
V/MediaPlayer-JNI(12807): native_setup
V/MediaPlayer(12807): constructor
,V/MediaPlayer(12807): setListener
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/art     ( 3508): Explicit concurrent mark sweep GC freed 76602(6MB) AllocSpace objects, 126(2017KB) LOS objects, 24% free, 49MB/65MB, paused 1.822ms total 132.850ms
,D/[CarModeFW](12807): MY_TAG-[YANG] MusicButtonReceiver construct MusicButtonReceiver() 
,I/[CarModeFW](12807): DriveLinkServiceInterfaceImp-drivelink framework initialize end
,D/[CarMode](12807): [DLServiceManager]-getOnDLLocationSuggestionListener..........
,D/[CarModeFW](12807): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestCallLogList => start time : 1450836975014
,D/[CarModeFW](12807): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => start time : 1450836975014
,D/[CarModeFW](12807): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestInboxList => start time : 1450836975020
,D/[CarModeFW](12807): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestUnreadMessageCount => start time : 1450836975022
,D/[CarMode](12807): [DLServiceManager]-updateLocationList
D/[CarMode](12807): [DLServiceManager]-requestRecommendedLocationList
,D/TP/SmsProvider( 3983): query,matched:2, calling pid = 12807
D/[CarModeFW](12807): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForCall => start time : 1450836975032
,D/[CarModeFW](12807): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedLocationList => start time : 1450836975033
,D/[CarModeFW](12807): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => start time : 1450836975034
D/[CarModeFW](12807): insertNavigationAvailable-sql: select distinct nav_package from tb_location_navigation_available
,D/TP/SmsProvider( 3983): match 2:Elapsed time : 3.613 ms
,D/[CarModeFW](12807): ContactDataHandler-getFavoriteContactList : cur len = 0
F/DLApplication(12807): DLApplication mListNavitationAvailable: [com.skt.skaf.l001mtm091, com.google.android.apps.maps, kt.navi, com.mnsoft.lgunavi, com.autonavi.xmgd.navigator.samsung, com.here.app.maps]
,D/[CarModeFW](12807): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => execute time : 23
,D/TP/SmsProvider( 3983): query,matched:2, calling pid = 12807
,I/[CarMode](12807): [LogNotNull]-Package name is: com.here.app.maps
,D/[CarModeFW](12807): ContactDataHandler-getFavoriteContactList : cur len = 0
,D/TP/SmsProvider( 3983): match 2:Elapsed time : 7.095 ms
,D/[CarModeFW](12807): CalllogDataHandler-getCalllogList : cur len = 0
,E/[CarMode](12807): [DLApplication]-Init End!:true
D/[CarModeFW](12807): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForCall => execute time : 18
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,D/[CarMode](12807): [TAG]-phone sound mode is: 0
V/[CarMode](12807): [DLApplication]-savePreviousGpsState
,D/[CarModeFW](12807): ContactDataHandler-getFavoriteContactList : cur len = 0
,D/[CarModeFW](12807): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => execute time : 29
,E/Zygote  (12873): MountEmulatedStorage()
E/Zygote  (12873): v2
I/libpersona(12873): KNOX_SDCARD checking this for 10047
I/libpersona(12873): KNOX_SDCARD not a persona
,I/SELinux (12873): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12873): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3508): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=12873 uid=10047 gids={50047, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (12873): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/[CarModeFW](12807): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestCallLogList => execute time : 63
,D/MessageDataHandler(12807):  getInboxList smsCursor : 57
,V/[CarMode](12807): [DLApplication]-savePreviousGpsState: Previous state = 0
,D/TP/MmsProvider( 3983): Query uri=content://mms/inbox, match=2, calling pid = 12807
,D/TP/MmsProvider( 3983): Query uri=content://mms, match=0, calling pid = 12807
,D/MessageDataHandler(12807):  getInboxList mmsCursor : 13
,I/MessageDataHandler(12807): getUnreadMessageCount :0
D/[CarModeFW](12807): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestUnreadMessageCount => execute time : 70
,D/MessageDataHandler(12807):  getInboxList mms,sms cursor join : 4
,D/[CarMode](12807): [DLApplication]-GooglePlayServices SUCCESS.
,E/[CarMode](12807): [DLApplication]-PREF_CAR_APP_RUNNING is set to false
D/TP/MmsSmsProvider( 3983): query,matched:0, calling pid = 12807
V/TP/MmsSmsProvider( 3983): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 3983): match 0:Elapsed time : 2.128 ms
,I/[CarMode](12807): [[DLUncaughtExceptionHandler]]-setDLUncaughtExceptionHandler
,E/[CarMode](12807): [[DLUncaughtExceptionHandler]]-DLUncaughtExceptionHandler is created!
,D/[CarMode](12807): [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,D/TP/MmsSmsProvider( 3983): query,matched:13, calling pid = 12807
,D/[CarMode](12807): [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED G4-1 state is 11
D/TP/MmsSmsProvider( 3983): match 13:Elapsed time : 2.065 ms
,D/TimaKeyStoreProvider(12873): TimaSignature is unavailable
D/DialogFlow(12807): initQueue()
,D/ActivityThread(12873): Added TimaKeyStore provider
,I/ActivityManager( 3508): Killing 11418:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##31
,I/jxcore-log(11631): 2015-12-23T02:16:15.125Z SendDataTCPServer.js: TCP/IP server has received 2024 bytes of data
I/jxcore-log(11631): 
,D/MessageDataHandler(12807):  getInboxList address cursor : 29
,D/TP/MmsSmsProvider( 3983): query,matched:0, calling pid = 12807
V/TP/MmsSmsProvider( 3983): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 3983): match 0:Elapsed time : 1.122 ms
,D/ResourcesManager(12873): creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
,W/ResourcesManager(12873): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/MessageDataHandler(12807):  getInboxList thread cursor : 6
,D/MessageDataHandler(12807):  thread, addr result: 6
I/[CarModeFW](12807): ContentManager-com.sec.android.app.automotive.carmode.framework.manager.content.ContentManager end getInboxList() : 131
I/[CarModeFW](12807): ContentManager-com.sec.android.app.automotive.carmode.framework.manager.content.ContentManager end getInboxListWithContactData() : 0
D/[CarModeFW](12807): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestInboxList => execute time : 132
,V/[CarModeFW](12807): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,I/jxcore-log(11631): 2015-12-23T02:16:15.158Z SendDataTCPServer.js: TCP/IP server has received 4048 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:15.165Z SendDataTCPServer.js: TCP/IP server has received 6072 bytes of data
I/jxcore-log(11631): 
,I/CalendarProvider2(12873): CalendarProvider2.onCreate() called
,I/jxcore-log(11631): 2015-12-23T02:16:15.174Z SendDataTCPServer.js: TCP/IP server has received 8096 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:15.177Z SendDataTCPServer.js: TCP/IP server has received 10120 bytes of data
I/jxcore-log(11631): 
,I/System.out(12839): INFO:Resource not found:/Common.properties Using default values
I/jxcore-log(11631): 2015-12-23T02:16:15.181Z SendDataTCPServer.js: TCP/IP server has received 12144 bytes of data
I/jxcore-log(11631): 
,E/Zygote  (12891): MountEmulatedStorage()
E/Zygote  (12891): v2
I/libpersona(12891): KNOX_SDCARD checking this for 10121
I/libpersona(12891): KNOX_SDCARD not a persona
,I/SELinux (12891): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3508): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/.GMHFPReceiver: pid=12891 uid=10121 gids={50121, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/SELinux (12891): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12891): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/[CarModeFW](12807): ConnectivityManager-handleMessage PAIRING_DEVICES
,I/ActivityManager( 3508): Killing 10736:com.android.defcontainer/u0a5 (adj 13): bgCount ##31
,I/ActivityManager( 3508): Killing 10765:com.google.android.gms.unstable/u0a14 (adj 15): bgCount ##32
,D/TimaKeyStoreProvider(12891): TimaSignature is unavailable
,D/ActivityThread(12891): Added TimaKeyStore provider
,I/jxcore-log(11631): 2015-12-23T02:16:15.232Z SendDataTCPServer.js: TCP/IP server has received 14168 bytes of data
I/jxcore-log(11631): 
,D/ResourcesManager(12891): creating new AssetManager and set to /system/app/GearManagerStub/GearManagerStub.apk
,I/jxcore-log(11631): 2015-12-23T02:16:15.241Z SendDataTCPServer.js: TCP/IP server has received 16192 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:15.246Z SendDataTCPServer.js: TCP/IP server has received 18216 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:15.249Z SendDataTCPServer.js: TCP/IP server has received 20240 bytes of data
I/jxcore-log(11631): 
,D/[CarModeFW](12807): LocationDataHandler-No schedules found.
,E/BluetoothHeadset(12891): BTStateChangeCB is registed
,D/[CarModeFW](12807): MyPlaceProvider-Provider uri: content://com.samsung.android.internal.intelligence.useranalysis/place
,I/jxcore-log(11631): 2015-12-23T02:16:15.268Z SendDataTCPServer.js: TCP/IP server has received 22264 bytes of data
I/jxcore-log(11631): 
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12909): MountEmulatedStorage()
I/libpersona(12909): KNOX_SDCARD checking this for 10003
E/Zygote  (12909): v2
I/libpersona(12909): KNOX_SDCARD not a persona
,I/SELinux (12909): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12909): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3508): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=12909 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 3006, 1007, 3001} abi=armeabi-v7a
,E/SELinux (12909): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/BluetoothHeadset(12891): BluetoothHeadset service is binded
D/GMFPReceiver(12891): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver(12891): jangil::setProperties()
,D/GMFPReceiver(12891): jangil::printBTStatus()
,D/SettingsProvider( 3508): name = Wearable0001
D/SettingsProvider( 3508): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3508): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3508): selectionArgs: false
D/SettingsProvider( 3508): selectionArgs: 10121
D/SecContentProvider( 3508): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 3508): ret = -1
,W/BackupManagerService( 3508): dataChanged but no participant pkg='com.android.providers.settings' uid=10121
,D/GMFPReceiver(12891): ::::::::Wearable0001::false
,D/SettingsProvider( 3508): name = Wearable0002
D/SettingsProvider( 3508): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3508): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3508): selectionArgs: false
D/SettingsProvider( 3508): selectionArgs: 10121
I/jxcore-log(11631): 2015-12-23T02:16:15.306Z SendDataTCPServer.js: TCP/IP server has received 26312 bytes of data
I/jxcore-log(11631): 
D/SecContentProvider( 3508): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3508): ret = -1
,I/jxcore-log(11631): 2015-12-23T02:16:15.309Z SendDataTCPServer.js: TCP/IP server has received 28336 bytes of data
I/jxcore-log(11631): 
,D/TimaKeyStoreProvider(12909): TimaSignature is unavailable
,W/BackupManagerService( 3508): dataChanged but no participant pkg='com.android.providers.settings' uid=10121
,D/ActivityThread(12909): Added TimaKeyStore provider
,D/GMFPReceiver(12891): ::::::::Wearable0002::false
D/GMFPReceiver(12891): onServiceConnected() : 1
D/GMFPReceiver(12891): mBluetoothHeadset = true
,I/jxcore-log(11631): 2015-12-23T02:16:15.320Z SendDataTCPServer.js: TCP/IP server has received 30360 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:15.324Z SendDataTCPServer.js: TCP/IP server has received 32384 bytes of data
I/jxcore-log(11631): 
,I/ActivityManager( 3508): Killing 11507:com.android.vending/u0a31 (adj 15): bgCount ##31
,D/BluetoothNotiBroadcastReceiver( 8784): onReceive
,D/[CarMode](12807): [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,D/[CarMode](12807): [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED G4-1 state is 10
,D/ResourcesManager(12909): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
,I/jxcore-log(11631): 2015-12-23T02:16:15.360Z SendDataTCPServer.js: TCP/IP server has received 50600 bytes of data
I/jxcore-log(11631): 
,E/BluetoothHeadset(12891): BTStateChangeCB is registed
,V/[CarModeFW](12807): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,E/BluetoothHeadset(12891): BluetoothHeadset service is binded
D/GMFPReceiver(12891): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver(12891): jangil::setProperties()
,D/GMFPReceiver(12891): jangil::printBTStatus()
,D/SettingsProvider( 3508): name = Wearable0001
D/SettingsProvider( 3508): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3508): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3508): selectionArgs: false
D/SettingsProvider( 3508): selectionArgs: 10121
D/SecContentProvider( 3508): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3508): ret = -1
D/UserAnalysis.PlaceProvider(12909): PlaceProvider onCreate()
D/GMFPReceiver(12891): ::::::::Wearable0001::false
,D/SettingsProvider( 3508): name = Wearable0002
D/SettingsProvider( 3508): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3508): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3508): selectionArgs: false
D/SettingsProvider( 3508): selectionArgs: 10121
D/SecContentProvider( 3508): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3508): ret = -1
D/GMFPReceiver(12891): ::::::::Wearable0002::false
,D/GMFPReceiver(12891): onServiceConnected() : 1
D/GMFPReceiver(12891): mBluetoothHeadset = true
,D/BootupListener( 3983): ACTION_DRIVELINK
,D/SettingsProvider( 3508): name = drivelink_navigation
D/SettingsProvider( 3508): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3508): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3508): selectionArgs: false
D/SettingsProvider( 3508): selectionArgs: 1001
D/SecContentProvider( 3508): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3508): ret = -1
D/BootupListener( 3983): NAVI : com.here.app.maps
D/SettingsProvider( 3508): name = internet_call_settings_visibility
D/SettingsProvider( 3508): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3508): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3508): selectionArgs: false
D/SettingsProvider( 3508): selectionArgs: 1001
D/SecContentProvider( 3508): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3508): ret = -1
,D/BootupListener( 3983): intent.getAction() = com.sec.android.automotive.drivelink.NAVIGATION_PACKAGE_NAME
,D/UserAnalysis.SecureDbManager(12909): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper(12909): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider(12909): Create SecureDbHelper
,D/IntelligenceServiceApplication(12909): onCreate()
,I/jxcore-log(11631): 2015-12-23T02:16:15.413Z SendDataTCPServer.js: TCP/IP server has received 52624 bytes of data
I/jxcore-log(11631): 
,D/[CarModeFW](12807): MyPlaceProvider-+++Begin print all data in content provider+++
D/[CarModeFW](12807): MyPlaceProvider-=============
D/[CarModeFW](12807): MyPlaceProvider-=============
D/[CarModeFW](12807): MyPlaceProvider-=============
D/[CarModeFW](12807): MyPlaceProvider-=============
D/[CarModeFW](12807): MyPlaceProvider-=============
D/[CarModeFW](12807): MyPlaceProvider-=============
D/[CarModeFW](12807): MyPlaceProvider----End print all data in content provider---
D/[CarModeFW](12807): MyPlaceProvider-==============
D/[CarModeFW](12807): MyPlaceProvider-==============
D/[CarModeFW](12807): MyPlaceProvider-==============
D/[CarModeFW](12807): MyPlaceProvider-==============
D/[CarModeFW](12807): MyPlaceProvider-==============
,D/[CarModeFW](12807): DestinationAvailableTableHandler-sql: select dest_name from tb_destination_list_available where ((1450836975420 - dest_date ) / 360000 ) <= 24 ORDER BY dest_date DESC LIMIT 100
,E/[CarModeFW](12807): DestinationAvailableTableHandler-insert FAIL!
E/DestinationList(12807): loadLocationDestinationList is null
D/[CarModeFW](12807): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedLocationList => execute time : 388
,I/jxcore-log(11631): 2015-12-23T02:16:15.449Z SendDataTCPServer.js: TCP/IP server has received 64768 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:15.487Z SendDataTCPServer.js: TCP/IP server has received 66792 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:15.530Z SendDataTCPServer.js: TCP/IP server has received 74888 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:15.579Z SendDataTCPServer.js: TCP/IP server has received 76912 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:15.616Z SendDataTCPServer.js: TCP/IP server has received 97152 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:15.628Z SendDataTCPServer.js: TCP/IP server has received 99176 bytes of data
I/jxcore-log(11631): 
,W/bt-btif ( 5622): invalid rfc slot id: 5
,I/jxcore-log(11631): 2015-12-23T02:16:15.666Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log(11631): 
W/io.jxcore.node.StreamCopyingThread(11631): Either failed to read from the output stream or write to the input stream (thread ID: 1632, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread(11631): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper(11631): onDisconnected: Incoming connection, peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper(11631): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1630
,D/io.jxcore.node.IncomingSocketThread(11631): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread(11631): doStop: Thread ID: 1632
D/io.jxcore.node.IncomingSocketThread(11631): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread(11631): doStop: Thread ID: 1631
D/io.jxcore.node.IncomingSocketThread(11631): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread(11631): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread(11631): closeLocalSocketAndStreams: Closing the local output stream...
W/io.jxcore.node.StreamCopyingThread(11631): Either failed to read from the output stream or write to the input stream (thread ID: 1631, thread name: Sender): Socket closed
,E/io.jxcore.node.IncomingSocketThread(11631): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper(11631): onDisconnected: Incoming connection, peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.IncomingSocketThread(11631): closeLocalSocketAndStreams: Closing the localhost socket...
,W/bt-rfcomm( 5622): rfc_find_lcid_mcb LCID reused LCID:0x41 current:0x0
W/bt-rfcomm( 5622): RFCOMM_DisconnectInd LCID:0x41
,I/io.jxcore.node.IncomingSocketThread(11631): closeBluetoothSocketAndStreams
,D/BluetoothSocket(11631): close() in, this: android.bluetooth.BluetoothSocket@20482bc9, channel: 6, state: CONNECTED
D/BluetoothSocket(11631): close() this: android.bluetooth.BluetoothSocket@20482bc9, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@228812ce, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2fef5efmSocket: android.net.LocalSocket@1b57b8fc impl:android.net.LocalSocketImpl@2d9ebb85 fd:FileDescriptor[115]
,D/BluetoothSocket(11631): Closing mSocket: android.net.LocalSocket@1b57b8fc impl:android.net.LocalSocketImpl@2d9ebb85 fd:FileDescriptor[115]
D/BluetoothSocket(11631): close() in, this: android.bluetooth.BluetoothSocket@20482bc9, channel: 6, state: CLOSED
D/BluetoothSocket(11631): close() in, this: android.bluetooth.BluetoothSocket@20482bc9, channel: 6, state: CLOSED
D/io.jxcore.node.ConnectionHelper(11631): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.ConnectionHelper(11631): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.StreamCopyingThread(11631): Exiting thread (ID: 1631, name: Sender)
,D/io.jxcore.node.StreamCopyingThread(11631): Exiting thread (ID: 1632, name: Receiver),
,I/jxcore-log(11631): 2015-12-23T02:16:15.688Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log(11631): 
,I/CalendarProvider2(12873): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12935): MountEmulatedStorage()
E/Zygote  (12935): v2
I/libpersona(12935): KNOX_SDCARD checking this for 10022
I/libpersona(12935): KNOX_SDCARD not a persona
,I/SELinux (12935): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12935): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3508): Start proc com.sec.android.widgetapp.locationwidget for broadcast com.sec.android.widgetapp.locationwidget/.cocktail.LocationWidgetCocktailProvider: pid=12935 uid=10022 gids={50022, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,E/SELinux (12935): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3508): Killing 12179:com.sec.android.provider.badge/u0a82 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12935): TimaSignature is unavailable
,D/ActivityThread(12935): Added TimaKeyStore provider
,D/ResourcesManager(12935): creating new AssetManager and set to /system/priv-app/LocationWidget/LocationWidget.apk
,W/ResourcesManager(12935): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12935): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(12935): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,I/LocationWidgetApplication(12935): onCreate() : start
,D/LocationWidgetApplication(12935): countryCode = POLAND
,D/LocationWidgetUtils(12935): getUpcommingInstances() start: 1450836976427, end: 1451429999999
D/LocationWidgetUtils(12935): getUpcommingInstances() DB begin time >= start:1450836976427, DB begin time <= end:1451429999999
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12953): MountEmulatedStorage()
E/Zygote  (12953): v2
I/libpersona(12953): KNOX_SDCARD checking this for 10163
I/libpersona(12953): KNOX_SDCARD not a persona
,I/SELinux (12953): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12953): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3508): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=12953 uid=10163 gids={50163, 9997} abi=armeabi-v7a
,E/SELinux (12953): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3508): Killing 11356:com.samsung.android.snote/u0a160 (adj 15): bgCount ##31
,E/lowmemorykiller( 2827): Error writing /proc/11356/oom_score_adj; errno=22
,D/TimaKeyStoreProvider(12953): TimaSignature is unavailable
,D/ActivityThread(12953): Added TimaKeyStore provider
,D/ResourcesManager(12953): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG_Transparent/SPlannerWidget_OS_UPG_Transparent.apk
,W/ResourcesManager(12953): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12953): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12972): MountEmulatedStorage()
E/Zygote  (12972): v2
I/libpersona(12972): KNOX_SDCARD checking this for 10164
I/libpersona(12972): KNOX_SDCARD not a persona
,I/SELinux (12972): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12972): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3508): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=12972 uid=10164 gids={50164, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,E/SELinux (12972): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3508): Killing 11765:com.sec.pcw.device/1000 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12972): TimaSignature is unavailable
,D/ActivityThread(12972): Added TimaKeyStore provider
,D/ResourcesManager(12972): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(12972): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(12972): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12972): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12972): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/daemonapp( 3776): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/LocationManagerService( 3508): getProviders()=[]
D/LocationManagerService( 3508): getProviders()=[passive]
D/LocationManagerService( 3508): getBestProvider(Criteria[power=LOW acc=LOW], true)=passive
,D/LWLocationManager(12935): mPrivacy is null
,W/ContextImpl(12935): Implicit intents with startService are not safe: Intent { act=com.samsung.android.providers.context.privacy.IPrivacyManager } android.content.ContextWrapper.bindService:559 com.samsung.android.providers.context.privacy.PrivacyManager.bindService:394 com.sec.android.widgetapp.locationwidget.data.LWLocationManager.bindPrivacyService:150 
,I/ActivityManager( 3508): Killing 11835:com.sec.android.cloudagent/u0a2 (adj 15): bgCount ##31
,D/ContextFramework:PrivacyManager(12935): Service for PrivacyManager is connected
,D/LWLocationManager(12935): Privacy service : STATUS_PLACE
D/LWLocationManager(12935): updateLocationStatus()
,I/LocationWidgetFuctionData(12935): readDB
,I/LocationWidgetFuctionData(12935): selectedAppSize: 3
I/LocationWidgetFuctionData(12935): configPlaceList aroundMeItems
,I/LocationWidgetFuctionData(12935): selectedAppSize: 3
,I/LocationWidgetFuctionData(12935): selectedAppSize: 3
,I/LocationWidgetFuctionData(12935): selectedAppSize: 3
,I/LocationWidgetFuctionData(12935): selectedAppSize: 3
,E/LWLocationManager(12935): findLocationType() : cursor_location.moveToFirst() return false!!
,D/LWLocationManager(12935): Intent broadcast sent with action: com.sec.android.widgetapp.locationwidget.LOCATION_SOURCES_UPDATED
D/LWLocationManager(12935): setShouldUpdateLocationId
D/LWLocationManager(12935): setShouldUpdateLocationId return false
D/LWLocationManager(12935): setShouldUpdateLocationId
D/LWLocationManager(12935): setShouldUpdateLocationId return false
D/LWLocationManager(12935): setShouldUpdateLocationId
D/LWLocationManager(12935): setShouldUpdateLocationId return false
D/LWLocationManager(12935): updateDeviceLocation() : lastDeviceLocationId = -100 mDeviceLocationId: -100 cocktailId: -1
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3508): online:4, current avg:1, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/BatteryService( 3508): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5622): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ProcessCpuTracker( 3508): Skipping unknown process pid 13003
,E/bt-btm  ( 5622): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 5622): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 3694): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService( 5622): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f40f0fd
,D/BtConfig.SecureMode( 5622): isSecureModeOn:false
,D/SecContentProvider( 3508): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,I/BluetoothPbapService( 5622): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,D/KeyguardViewMediator( 3694): isGear1: device is not B1!
,V/BluetoothEventManager( 8784): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 8784): ACTION_ACL_DISCONNECTED
,I/BTConnectionReceiver( 4055): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4055): Bluetooth Device Name: G4-1
,V/[CarModeFW](12807): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_DISCONNECTED State = -2147483648 Previous = -2147483648
,D/[CarModeFW](12807): ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED
,D/[CarModeFW](12807): ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED onNotifyBluetoothDeviceDisconnected
,D/[CarModeFW](12807): ConnectivityManager-Paired Devices list is empty
,E/[CarMode](12807): [BluetoothConnectivityListener]-onNotifyBluetoothProfileDisconnected: Unexpected error: Invalid device
,D/IOP_DB_BT( 5622): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
,D/IOP_DB_BT( 5622): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 5622): db_query_add_key: key KEY_LMP_VER, value 7:2003
D/IOP_DB_BT( 5622): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 5622): db_query_execute: result 1
,D/IOP_DB_BT( 5622): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
,D/IOP_DB_BT( 5622): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 5622): db_query_add_key: key KEY_LMP_VER, value 7:2003
D/IOP_DB_BT( 5622): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 5622): db_query_execute: result 1
,W/bt-btif ( 5622): info:x10
D/        ( 5622): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 5622): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 8784): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothBondStateMachine( 5622): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
,D/SecContentProvider( 3508): uri = 4 selection = bluetoothLogForRemote
,E/bt-btif ( 5622): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 5622): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 10 NewState: 11
,D/BtConfig.SecureMode( 5622): isSecureModeOn:false
I/BluetoothBondStateMachine( 5622): Entering PendingCommandState State
,V/BluetoothEventManager( 8784): Received android.bluetooth.device.action.NAME_CHANGED
,D/BluetoothTile( 3694):  onBluetoothPairedDevicesChanged:
,V/BluetoothEventManager( 8784): Received android.bluetooth.device.action.CLASS_CHANGED
,D/BluetoothTile( 3694):  handleUpdatestate:false name:null
,V/BluetoothEventManager( 8784): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothNotiBroadcastReceiver( 8784): onReceive
,D/btif_config_util( 5622): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,V/[CarModeFW](12807): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,D/[CarMode](12807): [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,D/[CarMode](12807): [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED A5-1 state is 11
,I/BluetoothBondStateMachine( 5622): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
D/[CarModeFW](12807): ConnectivityManager-handleMessage PAIRING_DEVICES
D/BluetoothAdapterProperties( 5622): Failed to remove device: 7C:F9:0E:37:96:AB
,D/SecContentProvider( 3508): uri = 4 selection = bluetoothLogForRemote
,E/BluetoothHeadset(12891): BTStateChangeCB is registed
,V/[CarModeFW](12807): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,I/BluetoothBondStateMachine( 5622): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
D/BtConfig.SecureMode( 5622): isSecureModeOn:false
D/[CarModeFW](12807): ConnectivityManager-handleMessage PAIRING_DEVICES
,D/HidService( 5622): getHidService(): returning com.android.bluetooth.hid.HidService@3d9d1a14
,V/BluetoothEventManager( 8784): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothTile( 3694):  onBluetoothPairedDevicesChanged:
D/SettingsProvider( 3508): name = bluetooth_input_device_priority_7C:F9:0E:37:96:AB
D/SettingsProvider( 3508): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3508): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3508): selectionArgs: false
D/SettingsProvider( 3508): selectionArgs: 1002
D/SecContentProvider( 3508): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3508): ret = -1
,D/HidService( 5622): Saved priority 7C:F9:0E:37:96:AB = -1
,D/SettingsProvider( 3508): name = bluetooth_a2dp_sink_priority_7C:F9:0E:37:96:AB
D/SettingsProvider( 3508): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3508): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3508): selectionArgs: false
D/SettingsProvider( 3508): selectionArgs: 1002
,D/SecContentProvider( 3508): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3508): ret = -1
D/BluetoothTile( 3694):  handleUpdatestate:false name:null
,D/SettingsProvider( 3508): name = bluetooth_headset_priority_7C:F9:0E:37:96:AB
D/SettingsProvider( 3508): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3508): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3508): selectionArgs: false
D/SettingsProvider( 3508): selectionArgs: 1002
D/SecContentProvider( 3508): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3508): ret = -1
,E/BluetoothHeadset(12891): BluetoothHeadset service is binded
D/GMFPReceiver(12891): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver(12891): jangil::setProperties()
,I/BluetoothBondStateMachine( 5622): StableState(): Entering Off State
,D/GMFPReceiver(12891): jangil::printBTStatus()
,D/SettingsProvider( 3508): name = Wearable0001
D/SettingsProvider( 3508): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3508): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3508): selectionArgs: false
D/SettingsProvider( 3508): selectionArgs: 10121
D/SecContentProvider( 3508): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3508): ret = -1
D/GMFPReceiver(12891): ::::::::Wearable0001::false
,D/SettingsProvider( 3508): name = Wearable0002
D/SettingsProvider( 3508): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3508): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3508): selectionArgs: false
D/SettingsProvider( 3508): selectionArgs: 10121
D/SecContentProvider( 3508): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3508): ret = -1
D/GMFPReceiver(12891): ::::::::Wearable0002::false
,V/[CarModeFW](12807): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
D/GMFPReceiver(12891): onServiceConnected() : 1
D/GMFPReceiver(12891): mBluetoothHeadset = true
,D/BluetoothNotiBroadcastReceiver( 8784): onReceive
,D/[CarMode](12807): [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,D/[CarMode](12807): [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED A5-1 state is 10
,V/[CarModeFW](12807): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,W/bt-btif ( 5622): new conn_srvc id:26, app_id:255
W/bt-btif ( 5622): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 5622): bta_dm_pm_ssr:2, lat:1200
,D/BluetoothSocket(11631): socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@17968dda
,E/BluetoothRemoteDevices( 5622): setRfcommConnected true
E/BluetoothHeadset(12891): BTStateChangeCB is registed
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11631): Incoming connection accepted
,E/BluetoothHeadset(12891): BluetoothHeadset service is binded
D/GMFPReceiver(12891): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver(12891): jangil::setProperties()
,D/GMFPReceiver(12891): jangil::printBTStatus()
,D/SettingsProvider( 3508): name = Wearable0001
D/SettingsProvider( 3508): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3508): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3508): selectionArgs: false
D/SettingsProvider( 3508): selectionArgs: 10121
D/SecContentProvider( 3508): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3508): ret = -1
D/GMFPReceiver(12891): ::::::::Wearable0001::false
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11631): Incoming connection initialized (thread ID: 1633)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11631): Waiting for incoming connections...
D/SettingsProvider( 3508): name = Wearable0002
D/SettingsProvider( 3508): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3508): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3508): selectionArgs: false
D/SettingsProvider( 3508): selectionArgs: 10121
D/SecContentProvider( 3508): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3508): ret = -1
D/GMFPReceiver(12891): ::::::::Wearable0002::false
,D/GMFPReceiver(12891): onServiceConnected() : 1
D/GMFPReceiver(12891): mBluetoothHeadset = true
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread(11631): Entering thread (ID: 1633)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11631): onBytesRead: Read 83 bytes successfully (thread ID: 1633)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11631): Got valid identity from [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11631): onBytesWritten: 82 bytes successfully written (thread ID: 1633)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11631): removeThreadFromList: Removing thread with ID 1633
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11631): Handshake thread disposed (thread ID: 1633)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11631): onIncomingConnectionConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11631): onConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
I/io.jxcore.node.ConnectionHelper(11631): onConnected: Incoming connection to peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/io.jxcore.node.ConnectionHelper(11631): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper(11631): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430] is available
,I/jxcore-log(11631): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"samsung-SM-A500FU_PT6430","peerAvailable":true}]
I/jxcore-log(11631): 
,I/jxcore-log(11631): Found peer : samsung-SM-A500FU_PT6430, Available: true
I/jxcore-log(11631): 
I/jxcore-log(11631): startWithNextDevice
I/jxcore-log(11631): 
,I/jxcore-log(11631): device[1]: 7C:F9:0E:37:96:AB
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:20.710Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB
I/jxcore-log(11631): 
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread(11631): Exiting thread (ID: 1633)
,I/jxcore-log(11631): 2015-12-23T02:16:20.712Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log(11631): 
I/jxcore-log(11631): 2015-12-23T02:16:20.712Z SendDataConnector.js: do connect now
I/jxcore-log(11631): 
,I/io.jxcore.node.ConnectionHelper(11631): connect: Trying to connect to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper(11631): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11631): connect: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11631): connect: Trying to start connecting to A5-1 in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11631): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11631): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11631): onConnecting: A5-1 7C:F9:0E:37:96:AB
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11631): connect: Started connecting to A5-1 in address 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper(11631): connect: Connection process successfully started (peer ID: 7C:F9:0E:37:96:AB)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11631): Trying to connect to peer with address 7C:F9:0E:37:96:AB (thread ID: 1634)
,I/io.jxcore.node.ConnectionHelper(11631): onConnected: Incoming socket thread, for peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], created successfully
D/io.jxcore.node.ConnectionHelper(11631): onConnected: The total number of connections is now 1
,D/BluetoothUtils(11631): isSocketAllowedBySecurityPolicy start : device null
D/io.jxcore.node.IncomingSocketThread(11631): Entering thread (ID: 1635)
W/BluetoothAdapter(11631): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 5622): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket(11631): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[119]}
D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 10527
,I/io.jxcore.node.IncomingSocketThread(11631): Local host address: localhost/127.0.0.1, port: 54681
D/io.jxcore.node.IncomingSocketThread(11631): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread(11631): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread(11631): setBufferSize: Setting buffer size to 8192 bytes
,I/jxcore-log(11631): 2015-12-23T02:16:20.726Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log(11631): 
D/io.jxcore.node.StreamCopyingThread(11631): Entering thread (ID: 1636, name: Sender)
I/io.jxcore.node.IncomingSocketThread(11631): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread(11631): Exiting thread (ID: 1635)
,D/io.jxcore.node.StreamCopyingThread(11631): Entering thread (ID: 1637, name: Receiver)
,W/bt-sdp  ( 5622): process_service_search_attr_rsp
,W/bt-btif ( 5622): new conn_srvc id:26, app_id:1
,W/bt-btif ( 5622): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 5622): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 5622): bta_dm_pm_ssr:2, lat:1200
,E/BluetoothRemoteDevices( 5622): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11631): onSocketConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11631): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1634)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11631): onBytesWritten: 82 bytes successfully written (thread ID: 1638)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11631): Outgoing connection initialized (*handshake* thread ID: 1638)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11631): Exiting thread (thread ID: 1634)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread(11631): Entering thread (ID: 1638)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11631): onBytesRead: Read 83 bytes successfully (thread ID: 1638)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11631): Handshake succeeded with [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11631): onHandshakeSucceeded: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11631): onConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
I/io.jxcore.node.ConnectionHelper(11631): onConnected: Outgoing connection to peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
,D/io.jxcore.node.ConnectionHelper(11631): hasConnection: We have an incoming connection with peer with ID 7C:F9:0E:37:96:AB
W/io.jxcore.node.ConnectionHelper(11631): onConnected: Already connected with peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], continuing anyway...
W/io.jxcore.node.ConnectionHelper(11631): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430] already in the list, will not add again
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread(11631): Exiting thread (ID: 1638)
,I/io.jxcore.node.ConnectionHelper(11631): onConnected: Outgoing socket thread, for peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], created successfully
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11631): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper(11631): onConnected: The total number of connections is now 2
,D/io.jxcore.node.OutgoingSocketThread(11631): Entering thread (ID: 1639)
,D/io.jxcore.node.OutgoingSocketThread(11631): Server socket local port: 51058
,I/io.jxcore.node.OutgoingSocketThread(11631): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper(11631): onListeningForIncomingConnections: Outgoing connection is using port 51058 (peer ID: 7C:F9:0E:37:96:AB)
,I/jxcore-log(11631): 2015-12-23T02:16:21.191Z SendDataConnector.js: CLIENT connected to 51058, error: null
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:21.195Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log(11631): 
,I/io.jxcore.node.OutgoingSocketThread(11631): Incoming data from address: /127.0.0.1, port: 51058
,D/io.jxcore.node.OutgoingSocketThread(11631): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread(11631): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread(11631): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.OutgoingSocketThread(11631): startStreamCopyingThreads: OK
,D/io.jxcore.node.OutgoingSocketThread(11631): Exiting thread (ID: 1639)
,D/io.jxcore.node.StreamCopyingThread(11631): Entering thread (ID: 1641, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread(11631): Entering thread (ID: 1640, name: Sender)
,I/jxcore-log(11631): 2015-12-23T02:16:21.232Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log(11631): 
,D/        ( 5622): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:3324
,I/jxcore-log(11631): 2015-12-23T02:16:21.592Z SendDataTCPServer.js: TCP/IP server has received 20240 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:21.620Z SendDataTCPServer.js: TCP/IP server has received 22264 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:21.656Z SendDataTCPServer.js: TCP/IP server has received 26312 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:21.785Z SendDataTCPServer.js: TCP/IP server has received 28336 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:21.810Z SendDataTCPServer.js: TCP/IP server has received 30360 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:21.857Z SendDataTCPServer.js: TCP/IP server has received 32384 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:21.902Z SendDataTCPServer.js: TCP/IP server has received 40480 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:21.908Z SendDataTCPServer.js: TCP/IP server has received 42504 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:21.912Z SendDataTCPServer.js: TCP/IP server has received 44528 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:21.951Z SendDataTCPServer.js: TCP/IP server has received 54648 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:21.955Z SendDataTCPServer.js: TCP/IP server has received 56672 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:21.991Z SendDataTCPServer.js: TCP/IP server has received 60720 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:22.023Z SendDataTCPServer.js: TCP/IP server has received 62744 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:22.115Z SendDataTCPServer.js: TCP/IP server has received 66792 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:22.162Z SendDataTCPServer.js: TCP/IP server has received 78936 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:22.177Z SendDataConnector.js: CLIENT is data received : 10000,
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:22.184Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:22.194Z SendDataTCPServer.js: TCP/IP server has received 93104 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:22.226Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log(11631): 
,D/        ( 5622): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:18628
,I/jxcore-log(11631): 2015-12-23T02:16:22.245Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:22.259Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log(11631): 
,W/bt-btif ( 5622): invalid rfc slot id: 6
,D/        ( 5622): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:7496
,W/io.jxcore.node.StreamCopyingThread(11631): Either failed to read from the output stream or write to the input stream (thread ID: 1637, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread(11631): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper(11631): onDisconnected: Incoming connection, peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper(11631): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1635
D/io.jxcore.node.OutgoingSocketThread(11631): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread(11631): doStop: Thread ID: 1637
D/io.jxcore.node.OutgoingSocketThread(11631): close: Stopping sending thread...
,I/io.jxcore.node.StreamCopyingThread(11631): doStop: Thread ID: 1636
D/io.jxcore.node.OutgoingSocketThread(11631): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread(11631): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread(11631): Either failed to read from the output stream or write to the input stream (thread ID: 1636, thread name: Sender): Socket closed
,E/io.jxcore.node.OutgoingSocketThread(11631): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper(11631): onDisconnected: Incoming connection, peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread(11631): closeLocalSocketAndStreams: Closing the local output stream...
,D/io.jxcore.node.OutgoingSocketThread(11631): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread(11631): closeBluetoothSocketAndStreams
,D/BluetoothSocket(11631): close() in, this: android.bluetooth.BluetoothSocket@3aef020b, channel: 6, state: CONNECTED
,D/BluetoothSocket(11631): close() this: android.bluetooth.BluetoothSocket@3aef020b, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@9e568e8, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@28148b01mSocket: android.net.LocalSocket@16dfada6 impl:android.net.LocalSocketImpl@1889b3e7 fd:FileDescriptor[115]
,D/BluetoothSocket(11631): Closing mSocket: android.net.LocalSocket@16dfada6 impl:android.net.LocalSocketImpl@1889b3e7 fd:FileDescriptor[115]
,D/BluetoothSocket(11631): close() in, this: android.bluetooth.BluetoothSocket@3aef020b, channel: 6, state: CLOSED
,D/BluetoothSocket(11631): close() in, this: android.bluetooth.BluetoothSocket@3aef020b, channel: 6, state: CLOSED
,D/io.jxcore.node.ConnectionHelper(11631): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper(11631): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread(11631): Exiting thread (ID: 1636, name: Sender)
,D/io.jxcore.node.StreamCopyingThread(11631): Exiting thread (ID: 1637, name: Receiver)
,I/jxcore-log(11631): 2015-12-23T02:16:22.900Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:23.617Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log(11631): 
,D/SSRM:n  ( 3508): SIOP:: AP = 250, PST = 240, CUR = 1
,I/jxcore-log(11631): 2015-12-23T02:16:24.248Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:24.958Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:25.598Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log(11631): 
,W/ContextImpl( 3508): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log(11631): 2015-12-23T02:16:26.274Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:26.952Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:26.957Z SendDataConnector.js: got all data for this round
I/jxcore-log(11631): 
,I/jxcore-log(11631): oneRoundDownNow
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:26.971Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:26.972Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log(11631): 
,D/io.jxcore.node.ConnectionHelper(11631): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:37:96:AB
,I/io.jxcore.node.ConnectionHelper(11631): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:37:96:AB
I/io.jxcore.node.OutgoingSocketThread(11631): close
D/io.jxcore.node.OutgoingSocketThread(11631): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread(11631): doStop: Thread ID: 1641
D/io.jxcore.node.OutgoingSocketThread(11631): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread(11631): doStop: Thread ID: 1640
D/io.jxcore.node.OutgoingSocketThread(11631): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread(11631): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread(11631): Either failed to read from the output stream or write to the input stream (thread ID: 1640, thread name: Sender): Socket closed
,E/io.jxcore.node.OutgoingSocketThread(11631): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper(11631): onDisconnected: Outgoing connection, peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread(11631): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread(11631): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread(11631): closeBluetoothSocketAndStreams
,D/BluetoothSocket(11631): close() in, this: android.bluetooth.BluetoothSocket@331c2b94, channel: 6, state: CONNECTED
D/BluetoothSocket(11631): close() this: android.bluetooth.BluetoothSocket@331c2b94, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@20bdd63d, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3848fe32mSocket: android.net.LocalSocket@133a783 impl:android.net.LocalSocketImpl@125a6d00 fd:FileDescriptor[119]
,D/BluetoothSocket(11631): Closing mSocket: android.net.LocalSocket@133a783 impl:android.net.LocalSocketImpl@125a6d00 fd:FileDescriptor[119]
W/io.jxcore.node.StreamCopyingThread(11631): Either failed to read from the output stream or write to the input stream (thread ID: 1641, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread(11631): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper(11631): onDisconnected: Outgoing connection, peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/BluetoothSocket(11631): close() in, this: android.bluetooth.BluetoothSocket@331c2b94, channel: 6, state: CLOSED
,D/BluetoothSocket(11631): close() in, this: android.bluetooth.BluetoothSocket@331c2b94, channel: 6, state: CLOSED
,D/io.jxcore.node.ConnectionHelper(11631): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper(11631): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:37:96:AB
E/io.jxcore.node.ConnectionHelper(11631): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
,D/io.jxcore.node.ConnectionHelper(11631): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread(11631): Exiting thread (ID: 1640, name: Sender)
E/io.jxcore.node.ConnectionHelper(11631): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper(11631): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread(11631): Exiting thread (ID: 1641, name: Receiver)
,I/jxcore-log(11631): 2015-12-23T02:16:26.996Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log(11631): 
,I/jxcore-log(11631): ---- round done--------
I/jxcore-log(11631): 
,I/jxcore-log(11631): startWithNextDevice
I/jxcore-log(11631): 
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3508): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3508): stay LED for fully charged
,I/MotionRecognitionService( 3508): Plugged
I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5622): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/bt-btif ( 5622): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,I/wpa_supplicant( 3830): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3508): InactiveState{ what=147477 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3508): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/WifiDisplayController( 3508): Received list of peers.
,D/WifiDisplayController( 3508):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 3508): InactiveState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 3508): P2pEnabledState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/WifiP2pService( 3508): P2pEnabledState receive service response
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 3508): InactiveState{ what=139307 },
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiP2pService( 3508): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 3508): P2pEnabledState clear service request
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7855","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], add/update: true
D/WifiP2pService( 3508): InactiveState{ what=139301 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
I/io.jxcore.node.ConnectionHelper(11631): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
D/WifiP2pService( 3508): P2pEnabledState{ what=139301 }
W/io.jxcore.node.ConnectionHelper(11631): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855] already in the list, will not add again
D/WifiP2pService( 3508): P2pEnabledState add service request
,D/WifiP2pManager(11631): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): Service request added successfully
,I/wpa_supplicant( 3830): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3508): InactiveState{ what=147477 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3508): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/WifiDisplayController( 3508): Received list of peers.
,D/WifiDisplayController( 3508):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 3508): InactiveState{ what=139310 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3508): P2pEnabledState discover services
,D/WifiService( 3508): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3508): callSECApi what=74
D/WifiStateMachine( 3508): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3508): callSECApiBoolean - ID [13]
I/wpa_supplicant( 3830): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): Service discovery started successfully
,E/bt-btm  ( 5622): Reset sec_bd_name and name flag. (BR/EDR link),
E/bt-btm  ( 5622): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 3694): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 8784): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 8784): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 3694): isGear1: device is not B1!
,D/BluetoothAdapterService( 5622): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f40f0fd
,D/BtConfig.SecureMode( 5622): isSecureModeOn:false
,D/SecContentProvider( 3508): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,I/BluetoothPbapService( 5622): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,V/[CarModeFW](12807): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_DISCONNECTED State = -2147483648 Previous = -2147483648
,I/BTConnectionReceiver( 4055): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,D/[CarModeFW](12807): ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED
D/[CarModeFW](12807): ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED onNotifyBluetoothDeviceDisconnected
,I/BluetoothClassifier( 4055): Bluetooth Device Name: A5-1
,D/[CarModeFW](12807): ConnectivityManager-Paired Devices list is empty
,E/[CarMode](12807): [BluetoothConnectivityListener]-onNotifyBluetoothProfileDisconnected: Unexpected error: Invalid device
,D/IOP_DB_BT( 5622): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:3f:54:73:64:c0
,D/IOP_DB_BT( 5622): db_query_add_key: key KEY_LMP_MFCT, value 15,
,D/IOP_DB_BT( 5622): db_query_add_key: key KEY_LMP_VER, value 6:16653
,D/IOP_DB_BT( 5622): db_query_add_key: key KEY_DIR_ALL, value *,
,D/IOP_DB_BT( 5622): db_query_execute: result 1,
,D/IOP_DB_BT( 5622): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:3f:54:73:64:c0
,D/IOP_DB_BT( 5622): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 5622): db_query_add_key: key KEY_LMP_VER, value 6:2003
D/IOP_DB_BT( 5622): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 5622): db_query_execute: result 1
,W/bt-btif ( 5622): info:x10
,D/        ( 5622): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 5622): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 8784): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothBondStateMachine( 5622): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 1
,V/BluetoothEventManager( 8784): Received android.bluetooth.device.action.NAME_CHANGED
,V/BluetoothEventManager( 8784): Received android.bluetooth.device.action.CLASS_CHANGED
,D/SecContentProvider( 3508): uri = 4 selection = bluetoothLogForRemote
,E/bt-btif ( 5622): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 5622): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 10 NewState: 11
D/BtConfig.SecureMode( 5622): isSecureModeOn:false
I/BluetoothBondStateMachine( 5622): Entering PendingCommandState State
,D/BluetoothTile( 3694):  onBluetoothPairedDevicesChanged:
,V/BluetoothEventManager( 8784): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothTile( 3694):  handleUpdatestate:false name:null
,D/BluetoothNotiBroadcastReceiver( 8784): onReceive
,V/[CarModeFW](12807): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,D/[CarModeFW](12807): ConnectivityManager-handleMessage PAIRING_DEVICES
,D/btif_config_util( 5622): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/[CarMode](12807): [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,D/[CarMode](12807): [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED G3-1 state is 11
,I/BluetoothBondStateMachine( 5622): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 0
,D/BluetoothAdapterProperties( 5622): Failed to remove device: 58:3F:54:73:64:C0
,D/SecContentProvider( 3508): uri = 4 selection = bluetoothLogForRemote
,V/[CarModeFW](12807): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
D/[CarModeFW](12807): ConnectivityManager-handleMessage PAIRING_DEVICES
,E/BluetoothHeadset(12891): BTStateChangeCB is registed
,I/BluetoothBondStateMachine( 5622): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 11 NewState: 10
,D/BtConfig.SecureMode( 5622): isSecureModeOn:false
E/BluetoothHeadset(12891): BluetoothHeadset service is binded
D/GMFPReceiver(12891): android.bluetooth.device.action.BOND_STATE_CHANGED
,D/HidService( 5622): getHidService(): returning com.android.bluetooth.hid.HidService@3d9d1a14
D/GMFPReceiver(12891): jangil::setProperties()
,V/BluetoothEventManager( 8784): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothTile( 3694):  onBluetoothPairedDevicesChanged:
,D/SettingsProvider( 3508): name = bluetooth_input_device_priority_58:3F:54:73:64:C0
D/SettingsProvider( 3508): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 3508): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3508): selectionArgs: false
D/SettingsProvider( 3508): selectionArgs: 1002
D/SecContentProvider( 3508): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3508): ret = -1
,D/HidService( 5622): Saved priority 58:3F:54:73:64:C0 = -1
,D/SettingsProvider( 3508): name = bluetooth_a2dp_sink_priority_58:3F:54:73:64:C0
D/GMFPReceiver(12891): jangil::printBTStatus()
,D/SettingsProvider( 3508): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3508): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3508): selectionArgs: false
D/SettingsProvider( 3508): selectionArgs: 1002
D/SettingsProvider( 3508): name = Wearable0001
D/SettingsProvider( 3508): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3508): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3508): selectionArgs: false
,D/SecContentProvider( 3508): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3508): selectionArgs: 10121
D/SecContentProvider( 3508): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3508): ret = -1
,D/SettingsProvider( 3508): ret = -1
,D/SettingsProvider( 3508): name = bluetooth_headset_priority_58:3F:54:73:64:C0
D/SettingsProvider( 3508): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3508): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3508): selectionArgs: false
D/SettingsProvider( 3508): selectionArgs: 1002
D/SecContentProvider( 3508): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3508): ret = -1
I/BluetoothBondStateMachine( 5622): StableState(): Entering Off State
,W/bt-btif ( 5622): new conn_srvc id:26, app_id:255
W/bt-btif ( 5622): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 5622): bta_dm_pm_ssr:2, lat:1200
,D/BluetoothSocket(11631): socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@2bb69939
,E/BluetoothRemoteDevices( 5622): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11631): Incoming connection accepted
D/BluetoothTile( 3694):  handleUpdatestate:false name:null
,D/GMFPReceiver(12891): ::::::::Wearable0001::false
,D/SettingsProvider( 3508): name = Wearable0002
D/SettingsProvider( 3508): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3508): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3508): selectionArgs: false
D/SettingsProvider( 3508): selectionArgs: 10121
D/SecContentProvider( 3508): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3508): ret = -1
,D/GMFPReceiver(12891): ::::::::Wearable0002::false
V/[CarModeFW](12807): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,D/GMFPReceiver(12891): onServiceConnected() : 1
D/GMFPReceiver(12891): mBluetoothHeadset = true
,D/BluetoothNotiBroadcastReceiver( 8784): onReceive
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11631): Incoming connection initialized (thread ID: 1642)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11631): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread(11631): Entering thread (ID: 1642)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11631): onBytesRead: Read 77 bytes successfully (thread ID: 1642)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11631): Got valid identity from [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11631): onBytesWritten: 82 bytes successfully written (thread ID: 1642)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11631): removeThreadFromList: Removing thread with ID 1642
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11631): Handshake thread disposed (thread ID: 1642)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11631): onIncomingConnectionConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread(11631): Exiting thread (ID: 1642)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11631): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
I/io.jxcore.node.ConnectionHelper(11631): onConnected: Incoming connection to peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
D/io.jxcore.node.ConnectionHelper(11631): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
W/io.jxcore.node.ConnectionHelper(11631): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3911] already in the list, will not add again
,D/[CarMode](12807): [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,D/[CarMode](12807): [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED G3-1 state is 10
,I/io.jxcore.node.ConnectionHelper(11631): onConnected: Incoming socket thread, for peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3911], created successfully
,D/io.jxcore.node.ConnectionHelper(11631): onConnected: The total number of connections is now 1
D/io.jxcore.node.IncomingSocketThread(11631): Entering thread (ID: 1643)
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 10527
,I/io.jxcore.node.IncomingSocketThread(11631): Local host address: localhost/127.0.0.1, port: 54681
D/io.jxcore.node.IncomingSocketThread(11631): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread(11631): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread(11631): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread(11631): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread(11631): Exiting thread (ID: 1643)
,I/jxcore-log(11631): 2015-12-23T02:16:32.106Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log(11631): 
,D/io.jxcore.node.StreamCopyingThread(11631): Entering thread (ID: 1645, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread(11631): Entering thread (ID: 1644, name: Sender)
,V/[CarModeFW](12807): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,E/BluetoothHeadset(12891): BTStateChangeCB is registed
,E/BluetoothHeadset(12891): BluetoothHeadset service is binded
D/GMFPReceiver(12891): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver(12891): jangil::setProperties()
,D/GMFPReceiver(12891): jangil::printBTStatus()
,D/SettingsProvider( 3508): name = Wearable0001
D/SettingsProvider( 3508): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3508): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3508): selectionArgs: false
D/SettingsProvider( 3508): selectionArgs: 10121
D/SecContentProvider( 3508): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3508): ret = -1
,D/GMFPReceiver(12891): ::::::::Wearable0001::false
D/SettingsProvider( 3508): name = Wearable0002
D/SettingsProvider( 3508): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3508): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3508): selectionArgs: false
D/SettingsProvider( 3508): selectionArgs: 10121
D/SecContentProvider( 3508): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3508): ret = -1
D/GMFPReceiver(12891): ::::::::Wearable0002::false
,D/GMFPReceiver(12891): onServiceConnected() : 1
D/GMFPReceiver(12891): mBluetoothHeadset = true
,I/jxcore-log(11631): 2015-12-23T02:16:33.173Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:33.186Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:33.213Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:33.226Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:33.247Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:33.287Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:33.307Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:33.311Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:33.350Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:33.361Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:33.401Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:33.405Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:33.437Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:33.475Z SendDataTCPServer.js: TCP/IP server has received 87316 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:33.480Z SendDataTCPServer.js: TCP/IP server has received 91276 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:33.524Z SendDataTCPServer.js: TCP/IP server has received 97216 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:16:33.555Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log(11631): 
,W/bt-btif ( 5622): invalid rfc slot id: 7
,W/io.jxcore.node.StreamCopyingThread(11631): Either failed to read from the output stream or write to the input stream (thread ID: 1645, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread(11631): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper(11631): onDisconnected: Incoming connection, peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3911] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper(11631): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1643
,D/io.jxcore.node.IncomingSocketThread(11631): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread(11631): doStop: Thread ID: 1645
D/io.jxcore.node.IncomingSocketThread(11631): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread(11631): doStop: Thread ID: 1644
,D/io.jxcore.node.IncomingSocketThread(11631): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread(11631): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread(11631): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread(11631): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.IncomingSocketThread(11631): closeBluetoothSocketAndStreams
D/BluetoothSocket(11631): close() in, this: android.bluetooth.BluetoothSocket@3a84cb7e, channel: 6, state: CONNECTED
D/BluetoothSocket(11631): close() this: android.bluetooth.BluetoothSocket@3a84cb7e, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1ff38df, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3879592cmSocket: android.net.LocalSocket@28de8ff5 impl:android.net.LocalSocketImpl@31e218a fd:FileDescriptor[115]
D/BluetoothSocket(11631): Closing mSocket: android.net.LocalSocket@28de8ff5 impl:android.net.LocalSocketImpl@31e218a fd:FileDescriptor[115]
,W/io.jxcore.node.StreamCopyingThread(11631): Either failed to read from the output stream or write to the input stream (thread ID: 1644, thread name: Sender): Socket closed
D/BluetoothSocket(11631): close() in, this: android.bluetooth.BluetoothSocket@3a84cb7e, channel: 6, state: CLOSED
D/BluetoothSocket(11631): close() in, this: android.bluetooth.BluetoothSocket@3a84cb7e, channel: 6, state: CLOSED
E/io.jxcore.node.IncomingSocketThread(11631): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.ConnectionHelper(11631): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
W/io.jxcore.node.ConnectionHelper(11631): onDisconnected: Incoming connection, peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3911] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.StreamCopyingThread(11631): Exiting thread (ID: 1645, name: Receiver)
D/io.jxcore.node.ConnectionHelper(11631): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread(11631): Exiting thread (ID: 1644, name: Sender)
,I/jxcore-log(11631): 2015-12-23T02:16:33.633Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log(11631): 
,W/bt-rfcomm( 5622): rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0
,W/bt-rfcomm( 5622): RFCOMM_DisconnectInd LCID:0x46
,D/SSRM:n  ( 3508): SIOP:: AP = 240, PST = 240, CUR = 20
,E/bt-btm  ( 5622): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 5622): btm_sec_disconnected - Clearing Pending flag,
,D/KeyguardViewMediator( 3694): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 8784): Received android.bluetooth.device.action.ACL_DISCONNECTED
E/BluetoothEventManager( 8784): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 3694): isGear1: device is not B1!
,V/[CarModeFW](12807): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_DISCONNECTED State = -2147483648 Previous = -2147483648
,D/BluetoothAdapterService( 5622): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f40f0fd
D/BtConfig.SecureMode( 5622): isSecureModeOn:false
,D/SecContentProvider( 3508): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,D/[CarModeFW](12807): ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED
D/[CarModeFW](12807): ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED onNotifyBluetoothDeviceDisconnected
,I/BluetoothPbapService( 5622): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,D/[CarModeFW](12807): ConnectivityManager-Paired Devices list is empty
E/[CarMode](12807): [BluetoothConnectivityListener]-onNotifyBluetoothProfileDisconnected: Unexpected error: Invalid device
,I/BTConnectionReceiver( 4055): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4055): Bluetooth Device Name: G3-1
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3508): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
,D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3508): stay LED for fully charged
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5622): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3508): !@Sync 19
,D/SSRM:n  ( 3508): SIOP:: AP = 240, PST = 240, CUR = 23
,W/ContextImpl( 3508): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3508): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3508): stay LED for fully charged
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5622): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3508): SIOP:: AP = 240, PST = 240, CUR = 25,
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11631): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11631): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11631): setState: RESTARTING
,D/WifiP2pService( 3508): InactiveState{ what=139268 }
,I/wpa_supplicant( 3830): P2P-FIND-STOPPED ,
,D/WifiP2pService( 3508): InactiveState{ what=147493 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3508): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11631): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11631): Start timer timeout, starting now...
,D/WifiP2pService( 3508): InactiveState{ what=139265 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139265 }
,D/WifiService( 3508): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3508): callSECApi what=74
,D/WifiStateMachine( 3508): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3508): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3830): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11631): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11631): setState: STARTED
,D/WifiP2pService( 3508): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11631): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/SSRM:n  ( 3508): SIOP:: AP = 240, PST = 240, CUR = 25
,I/wpa_supplicant( 3830): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3508): InactiveState{ what=147477 }
D/WifiP2pService( 3508): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3508): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/WifiDisplayController( 3508): Received list of peers.
,D/WifiDisplayController( 3508):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): restart: Restarting...
,D/WifiP2pService( 3508): InactiveState{ what=139307 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3508): P2pEnabledState clear service request
,D/WifiP2pService( 3508): InactiveState{ what=139301 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 3508): P2pEnabledState add service request
,D/WifiP2pManager(11631): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): Service request added successfully
,I/wpa_supplicant( 3830): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3508): InactiveState{ what=147477 },
,D/WifiP2pService( 3508): P2pEnabledState{ what=147477 },
,D/WifiDisplayController( 3508): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3508): InactiveState{ what=139283 },
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/WifiDisplayController( 3508): Received list of peers.
,D/WifiDisplayController( 3508):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3508): InactiveState{ what=139283 }
D/WifiDisplayController( 3508):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 3508): InactiveState{ what=139310 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139310 }
D/WifiP2pService( 3508): P2pEnabledState discover services
,D/WifiService( 3508): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/WifiStateMachine( 3508): callSECApi what=74
,D/WifiStateMachine( 3508): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3508): callSECApiBoolean - ID [13]
I/wpa_supplicant( 3830): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): Service discovery started successfully
,W/ContextImpl( 3508): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/wpa_supplicant( 3830): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3508): InactiveState{ what=147477 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3508): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/WifiDisplayController( 3508): Received list of peers.
,D/WifiDisplayController( 3508):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 3508): InactiveState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6545","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
,I/io.jxcore.node.ConnectionHelper(11631): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper(11631): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545] already in the list, will not add again
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3508): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3508): stay LED for fully charged
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5622): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 3508): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3508): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 3508): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 3508): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 3508): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3508): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3508): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3508): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/wpa_supplicant( 3830): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3508): InactiveState{ what=147477 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3508): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/WifiDisplayController( 3508): Received list of peers.
,D/WifiDisplayController( 3508):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 3508): InactiveState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6438","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
,I/io.jxcore.node.ConnectionHelper(11631): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
,W/io.jxcore.node.ConnectionHelper(11631): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438] already in the list, will not add again
,D/SSRM:n  ( 3508): SIOP:: AP = 240, PST = 240, CUR = 26
,I/wpa_supplicant( 3830): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3508): InactiveState{ what=147477 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3508): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/WifiDisplayController( 3508): Received list of peers.
,D/WifiDisplayController( 3508):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/wpa_supplicant( 3830): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3508): InactiveState{ what=147477 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3508): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3508): InactiveState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6430","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
,I/io.jxcore.node.ConnectionHelper(11631): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
,W/io.jxcore.node.ConnectionHelper(11631): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430] already in the list, will not add again
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/WifiDisplayController( 3508): Received list of peers.
,D/WifiDisplayController( 3508):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): restart: Restarting...
,D/WifiP2pService( 3508): InactiveState{ what=139307 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3508): P2pEnabledState clear service request
,D/WifiP2pService( 3508): InactiveState{ what=139301 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 3508): P2pEnabledState add service request
,D/WifiP2pManager(11631): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): Service request added successfully
,I/wpa_supplicant( 3830): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3508): InactiveState{ what=147477 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3508): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/WifiDisplayController( 3508): Received list of peers.
,D/WifiDisplayController( 3508):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b,
,D/WifiP2pService( 3508): InactiveState{ what=139310 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3508): P2pEnabledState discover services
,D/WifiService( 3508): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3508): callSECApi what=74
,D/WifiStateMachine( 3508): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3508): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3830): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): Service discovery started successfully
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3508): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/BatteryService( 3508): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5622): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3508): [PWL] Off : 525s ago
,D/WifiP2pService( 3508): InactiveState{ what=147494 },
,D/WifiP2pService( 3508): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6430","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
,I/io.jxcore.node.ConnectionHelper(11631): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
,W/io.jxcore.node.ConnectionHelper(11631): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430] already in the list, will not add again
,D/WifiP2pService( 3508): InactiveState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6545","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
,I/io.jxcore.node.ConnectionHelper(11631): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
,W/io.jxcore.node.ConnectionHelper(11631): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545] already in the list, will not add again
,D/SSRM:n  ( 3508): SIOP:: AP = 240, PST = 240, CUR = 27
,I/wpa_supplicant( 3830): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3508): InactiveState{ what=147477 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3508): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/WifiDisplayController( 3508): Received list of peers.
,D/WifiDisplayController( 3508):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,I/wpa_supplicant( 3830): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3830): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3508): InactiveState{ what=147477 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3508): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3508): InactiveState{ what=147477 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3508): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/WifiDisplayController( 3508): Received list of peers.
,D/WifiDisplayController( 3508):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): restart: Restarting...
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/WifiDisplayController( 3508): Received list of peers.
,D/WifiDisplayController( 3508):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 3508): InactiveState{ what=139307 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139307 }
D/WifiP2pService( 3508): P2pEnabledState clear service request
,D/WifiP2pService( 3508): InactiveState{ what=139301 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139301 }
D/WifiP2pService( 3508): P2pEnabledState add service request
,D/WifiP2pManager(11631): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): Service request added successfully
,W/ContextImpl( 3508): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/wpa_supplicant( 3830): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3508): InactiveState{ what=147477 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3508): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
D/WifiDisplayController( 3508): Received list of peers.
D/WifiDisplayController( 3508):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 3508): InactiveState{ what=139310 },
,D/WifiP2pService( 3508): P2pEnabledState{ what=139310 }
D/WifiP2pService( 3508): P2pEnabledState discover services
,D/WifiService( 3508): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/WifiStateMachine( 3508): callSECApi what=74
,D/WifiStateMachine( 3508): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3508): callSECApiBoolean - ID [13]
I/wpa_supplicant( 3830): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): Service discovery started successfully
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3508): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/BatteryService( 3508): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5622): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/IOP_DB_BT( 5622): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
,D/IOP_DB_BT( 5622): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 5622): db_query_add_key: key KEY_LMP_VER, value 7:24844,
,D/IOP_DB_BT( 5622): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 5622): db_query_execute: result 1,
,D/IOP_DB_BT( 5622): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
,D/IOP_DB_BT( 5622): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 5622): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 5622): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 5622): db_query_execute: result 1
,W/bt-btif ( 5622): info:x10
,D/        ( 5622): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 5622): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 8784): Received android.bluetooth.device.action.NAME_CHANGED
,D/WifiP2pService( 3508): InactiveState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6430","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
,I/io.jxcore.node.ConnectionHelper(11631): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
,W/io.jxcore.node.ConnectionHelper(11631): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430] already in the list, will not add again
,D/WifiP2pService( 3508): InactiveState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6438","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
,I/io.jxcore.node.ConnectionHelper(11631): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
,W/io.jxcore.node.ConnectionHelper(11631): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438] already in the list, will not add again
,D/WifiP2pService( 3508): InactiveState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147494 },
D/WifiP2pService( 3508): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7855","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local.",
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855],
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
,D/WifiP2pService( 3508): InactiveState{ what=147494 }
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], add/update: true,
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
,I/io.jxcore.node.ConnectionHelper(11631): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
,D/WifiP2pService( 3508): P2pEnabledState{ what=147494 }
,W/io.jxcore.node.ConnectionHelper(11631): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855] already in the list, will not add again
,D/WifiP2pService( 3508): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6545","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
,I/io.jxcore.node.ConnectionHelper(11631): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
,W/io.jxcore.node.ConnectionHelper(11631): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545] already in the list, will not add again
,I/BluetoothBondStateMachine( 5622): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
,D/SecContentProvider( 3508): uri = 4 selection = bluetoothLogForRemote
,E/bt-btif ( 5622): check_cod: remote_cod = 0x5a020c
,V/BluetoothEventManager( 8784): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothBondStateMachine( 5622): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
,D/BtConfig.SecureMode( 5622): isSecureModeOn:false
,I/BluetoothBondStateMachine( 5622): Entering PendingCommandState State
,D/BluetoothTile( 3694):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 3694):  handleUpdatestate:false name:null
,V/BluetoothEventManager( 8784): Received android.bluetooth.device.action.CLASS_CHANGED
,V/BluetoothEventManager( 8784): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/btif_config_util( 5622): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 5622): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,D/BluetoothAdapterProperties( 5622): Failed to remove device: 7C:F9:0E:34:8A:A0
,D/SecContentProvider( 3508): uri = 4 selection = bluetoothLogForRemote
,D/BluetoothTile( 3694):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 3694):  handleUpdatestate:false name:null
,I/BluetoothBondStateMachine( 5622): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,D/BtConfig.SecureMode( 5622): isSecureModeOn:false
,D/HidService( 5622): getHidService(): returning com.android.bluetooth.hid.HidService@3d9d1a14
,D/SettingsProvider( 3508): name = bluetooth_input_device_priority_7C:F9:0E:34:8A:A0
,D/SettingsProvider( 3508): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/BluetoothSocket(11631): socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@3cc883fb
,W/bt-btif ( 5622): new conn_srvc id:26, app_id:255
,W/bt-btif ( 5622): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 5622): bta_dm_pm_ssr:2, lat:1200
,E/BluetoothRemoteDevices( 5622): setRfcommConnected true
,D/SettingsProvider( 3508): projectionArgs: isSettingsChangesAllowed
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11631): Incoming connection accepted
D/SettingsProvider( 3508): selectionArgs: false
,D/SettingsProvider( 3508): selectionArgs: 1002
,D/SecContentProvider( 3508): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 3508): ret = -1
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11631): Incoming connection initialized (thread ID: 1646)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11631): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread(11631): Entering thread (ID: 1646)
,D/HidService( 5622): Saved priority 7C:F9:0E:34:8A:A0 = -1
,D/BluetoothNotiBroadcastReceiver( 8784): onReceive
,V/BluetoothEventManager( 8784): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/SettingsProvider( 3508): name = bluetooth_a2dp_sink_priority_7C:F9:0E:34:8A:A0
,V/[CarModeFW](12807): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
D/SettingsProvider( 3508): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3508): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3508): selectionArgs: false
D/SettingsProvider( 3508): selectionArgs: 1002
D/SecContentProvider( 3508): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3508): ret = -1
,D/SettingsProvider( 3508): name = bluetooth_headset_priority_7C:F9:0E:34:8A:A0
D/SettingsProvider( 3508): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3508): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3508): selectionArgs: false
D/SettingsProvider( 3508): selectionArgs: 1002
,D/SecContentProvider( 3508): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3508): ret = -1
I/BluetoothBondStateMachine( 5622): StableState(): Entering Off State
,D/[CarModeFW](12807): ConnectivityManager-handleMessage PAIRING_DEVICES
,D/[CarMode](12807): [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,D/[CarMode](12807): [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED S5-1 state is 11
,V/[CarModeFW](12807): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,V/[CarModeFW](12807): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,D/[CarModeFW](12807): ConnectivityManager-handleMessage PAIRING_DEVICES
E/BluetoothHeadset(12891): BTStateChangeCB is registed
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11631): onBytesRead: Read 82 bytes successfully (thread ID: 1646)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11631): Got valid identity from [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11631): onBytesWritten: 82 bytes successfully written (thread ID: 1646)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11631): removeThreadFromList: Removing thread with ID 1646
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11631): Handshake thread disposed (thread ID: 1646)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11631): onIncomingConnectionConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread(11631): Exiting thread (ID: 1646)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11631): onConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
,I/io.jxcore.node.ConnectionHelper(11631): onConnected: Incoming connection to peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
D/io.jxcore.node.ConnectionHelper(11631): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
W/io.jxcore.node.ConnectionHelper(11631): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545] already in the list, will not add again
,E/BluetoothHeadset(12891): BluetoothHeadset service is binded
D/GMFPReceiver(12891): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver(12891): jangil::setProperties()
,D/GMFPReceiver(12891): jangil::printBTStatus()
,I/io.jxcore.node.ConnectionHelper(11631): onConnected: Incoming socket thread, for peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], created successfully
D/io.jxcore.node.ConnectionHelper(11631): onConnected: The total number of connections is now 1
D/SettingsProvider( 3508): name = Wearable0001
D/SettingsProvider( 3508): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3508): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3508): selectionArgs: false
D/SettingsProvider( 3508): selectionArgs: 10121
D/SecContentProvider( 3508): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3508): ret = -1
D/GMFPReceiver(12891): ::::::::Wearable0001::false
D/io.jxcore.node.IncomingSocketThread(11631): Entering thread (ID: 1647)
,D/SettingsProvider( 3508): name = Wearable0002
D/SettingsProvider( 3508): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3508): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3508): selectionArgs: false
D/SettingsProvider( 3508): selectionArgs: 10121
D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 10527
D/SecContentProvider( 3508): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3508): ret = -1
D/GMFPReceiver(12891): ::::::::Wearable0002::false
,I/io.jxcore.node.IncomingSocketThread(11631): Local host address: localhost/127.0.0.1, port: 54681
D/io.jxcore.node.IncomingSocketThread(11631): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread(11631): setBufferSize: Setting buffer size to 8192 bytes
D/GMFPReceiver(12891): onServiceConnected() : 1
D/GMFPReceiver(12891): mBluetoothHeadset = true
I/io.jxcore.node.StreamCopyingThread(11631): setBufferSize: Setting buffer size to 8192 bytes
,D/io.jxcore.node.StreamCopyingThread(11631): Entering thread (ID: 1648, name: Sender)
I/io.jxcore.node.IncomingSocketThread(11631): startStreamCopyingThreads: OK
,I/jxcore-log(11631): 2015-12-23T02:17:29.308Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log(11631): 
D/io.jxcore.node.IncomingSocketThread(11631): Exiting thread (ID: 1647)
,D/io.jxcore.node.StreamCopyingThread(11631): Entering thread (ID: 1649, name: Receiver)
,D/BluetoothNotiBroadcastReceiver( 8784): onReceive
,D/[CarMode](12807): [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,D/[CarMode](12807): [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED S5-1 state is 10
,V/[CarModeFW](12807): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,E/BluetoothHeadset(12891): BTStateChangeCB is registed
,E/BluetoothHeadset(12891): BluetoothHeadset service is binded
D/GMFPReceiver(12891): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver(12891): jangil::setProperties()
,D/GMFPReceiver(12891): jangil::printBTStatus()
,D/SettingsProvider( 3508): name = Wearable0001
D/SettingsProvider( 3508): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3508): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3508): selectionArgs: false
D/SettingsProvider( 3508): selectionArgs: 10121
D/SecContentProvider( 3508): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3508): ret = -1
D/GMFPReceiver(12891): ::::::::Wearable0001::false
,D/SettingsProvider( 3508): name = Wearable0002
D/SettingsProvider( 3508): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3508): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3508): selectionArgs: false
D/SettingsProvider( 3508): selectionArgs: 10121
D/SecContentProvider( 3508): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3508): ret = -1
D/GMFPReceiver(12891): ::::::::Wearable0002::false
,D/GMFPReceiver(12891): onServiceConnected() : 1
D/GMFPReceiver(12891): mBluetoothHeadset = true
,I/jxcore-log(11631): 2015-12-23T02:17:30.324Z SendDataTCPServer.js: TCP/IP server has received 6072 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:17:30.327Z SendDataTCPServer.js: TCP/IP server has received 20432 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:17:30.335Z SendDataTCPServer.js: TCP/IP server has received 24480 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:17:30.375Z SendDataTCPServer.js: TCP/IP server has received 44720 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:17:30.377Z SendDataTCPServer.js: TCP/IP server has received 46744 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:17:30.409Z SendDataTCPServer.js: TCP/IP server has received 48768 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:17:30.415Z SendDataTCPServer.js: TCP/IP server has received 50792 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:17:30.424Z SendDataTCPServer.js: TCP/IP server has received 52816 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:17:30.465Z SendDataTCPServer.js: TCP/IP server has received 77104 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:17:30.475Z SendDataTCPServer.js: TCP/IP server has received 79128 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:17:30.478Z SendDataTCPServer.js: TCP/IP server has received 81152 bytes of data
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:17:30.516Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log(11631): 
,W/bt-btif ( 5622): invalid rfc slot id: 9
,W/io.jxcore.node.StreamCopyingThread(11631): Either failed to read from the output stream or write to the input stream (thread ID: 1649, thread name: Receiver): bt socket closed, read return: -1,
E/io.jxcore.node.IncomingSocketThread(11631): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected,
W/io.jxcore.node.ConnectionHelper(11631): onDisconnected: Incoming connection, peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper(11631): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1647
,D/io.jxcore.node.IncomingSocketThread(11631): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread(11631): doStop: Thread ID: 1649
D/io.jxcore.node.IncomingSocketThread(11631): close: Stopping sending thread...
,I/io.jxcore.node.StreamCopyingThread(11631): doStop: Thread ID: 1648
,D/io.jxcore.node.IncomingSocketThread(11631): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread(11631): closeLocalSocketAndStreams: Closing the local input stream...
,W/bt-rfcomm( 5622): rfc_find_lcid_mcb LCID reused LCID:0x48 current:0x0
,W/bt-rfcomm( 5622): RFCOMM_DisconnectInd LCID:0x48
,W/io.jxcore.node.StreamCopyingThread(11631): Either failed to read from the output stream or write to the input stream (thread ID: 1648, thread name: Sender): Socket closed
,E/io.jxcore.node.IncomingSocketThread(11631): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper(11631): onDisconnected: Incoming connection, peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread(11631): closeLocalSocketAndStreams: Closing the local output stream...
,D/io.jxcore.node.IncomingSocketThread(11631): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.IncomingSocketThread(11631): closeBluetoothSocketAndStreams
,D/BluetoothSocket(11631): close() in, this: android.bluetooth.BluetoothSocket@8b8dc18, channel: 6, state: CONNECTED
,D/BluetoothSocket(11631): close() this: android.bluetooth.BluetoothSocket@8b8dc18, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1c553671, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1344cc56mSocket: android.net.LocalSocket@b1164d7 impl:android.net.LocalSocketImpl@186ba1c4 fd:FileDescriptor[115]
,D/BluetoothSocket(11631): Closing mSocket: android.net.LocalSocket@b1164d7 impl:android.net.LocalSocketImpl@186ba1c4 fd:FileDescriptor[115]
,D/BluetoothSocket(11631): close() in, this: android.bluetooth.BluetoothSocket@8b8dc18, channel: 6, state: CLOSED
,D/BluetoothSocket(11631): close() in, this: android.bluetooth.BluetoothSocket@8b8dc18, channel: 6, state: CLOSED
,D/io.jxcore.node.ConnectionHelper(11631): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper(11631): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread(11631): Exiting thread (ID: 1648, name: Sender)
,D/io.jxcore.node.StreamCopyingThread(11631): Exiting thread (ID: 1649, name: Receiver)
,I/jxcore-log(11631): 2015-12-23T02:17:30.683Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log(11631): 
,E/bt-btm  ( 5622): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 5622): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 3694): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/SSRM:n  ( 3508): SIOP:: AP = 240, PST = 240, CUR = 26
,V/BluetoothEventManager( 8784): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 8784): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 3694): isGear1: device is not B1!
,D/BluetoothAdapterService( 5622): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f40f0fd
,D/BtConfig.SecureMode( 5622): isSecureModeOn:false
,V/[CarModeFW](12807): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_DISCONNECTED State = -2147483648 Previous = -2147483648
,D/SecContentProvider( 3508): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,D/[CarModeFW](12807): ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED
,D/[CarModeFW](12807): ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED onNotifyBluetoothDeviceDisconnected
,D/[CarModeFW](12807): ConnectivityManager-Paired Devices list is empty
E/[CarMode](12807): [BluetoothConnectivityListener]-onNotifyBluetoothProfileDisconnected: Unexpected error: Invalid device
,I/BluetoothPbapService( 5622): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,I/BTConnectionReceiver( 4055): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4055): Bluetooth Device Name: S5-1
,I/jxcore-log(11631): timeout now
I/jxcore-log(11631): 
,I/jxcore-log(11631): weAreDoneNow, resultArray.length: 1
I/jxcore-log(11631): 
,I/jxcore-log(11631): sendReportNow
I/jxcore-log(11631): 
,I/jxcore-log(11631): done, now sending data to server
I/jxcore-log(11631): 
,I/jxcore-log(11631): 2015-12-23T02:17:37.097Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log(11631): 
,D/WifiP2pService( 3508): InactiveState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4998","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onServiceDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998],
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Adding new peer: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998],
,I/io.jxcore.node.ConnectionHelper(11631): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998], Bluetooth address: 44:80:EB:7B:5A:05, device name: XT1072_23d5, device address: 44:80:eb:7b:5a:07,
W/io.jxcore.node.ConnectionHelper(11631): modifyListOfDiscoveredPeers: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4998] already in the list, will not add again,
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3508): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
,D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/BatteryService( 3508): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5622): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/wpa_supplicant( 3830): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3508): InactiveState{ what=147477 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3508): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/WifiDisplayController( 3508): Received list of peers.
,D/WifiDisplayController( 3508):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): restart: Restarting...,
,D/WifiP2pService( 3508): InactiveState{ what=139307 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3508): P2pEnabledState clear service request
,D/WifiP2pService( 3508): InactiveState{ what=139301 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139301 }
D/WifiP2pService( 3508): P2pEnabledState add service request
,D/WifiP2pManager(11631): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): Service request added successfully
,I/wpa_supplicant( 3830): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3508): InactiveState{ what=147477 }
D/WifiP2pService( 3508): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3508): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 3508): InactiveState{ what=139283 }
D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
D/WifiDisplayController( 3508): Received list of peers.
D/WifiDisplayController( 3508):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3508): InactiveState{ what=139283 }
D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 3508): InactiveState{ what=139310 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139310 }
D/WifiP2pService( 3508): P2pEnabledState discover services
,D/WifiService( 3508): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/WifiStateMachine( 3508): callSECApi what=74
D/WifiStateMachine( 3508): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3508): callSECApiBoolean - ID [13]
I/wpa_supplicant( 3830): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): Service discovery started successfully
,D/WifiP2pService( 3508): InactiveState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4998","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onServiceDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Adding new peer: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
,I/io.jxcore.node.ConnectionHelper(11631): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998], Bluetooth address: 44:80:EB:7B:5A:05, device name: XT1072_23d5, device address: 44:80:eb:7b:5a:07
,W/io.jxcore.node.ConnectionHelper(11631): modifyListOfDiscoveredPeers: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4998] already in the list, will not add again
,D/WifiP2pService( 3508): InactiveState{ what=147494 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147494 },
D/WifiP2pService( 3508): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6430","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
I/io.jxcore.node.ConnectionHelper(11631): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper(11631): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430] already in the list, will not add again
,D/WifiP2pService( 3508): InactiveState{ what=147494 },
,D/WifiP2pService( 3508): P2pEnabledState{ what=147494 },
,D/WifiP2pService( 3508): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6545","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
,I/io.jxcore.node.ConnectionHelper(11631): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
,W/io.jxcore.node.ConnectionHelper(11631): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545] already in the list, will not add again
,E/Watchdog( 3508): !@Sync 21
,D/SSRM:n  ( 3508): SIOP:: AP = 240, PST = 240, CUR = 25
,I/wpa_supplicant( 3830): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3508): InactiveState{ what=147477 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3508): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
D/WifiDisplayController( 3508): Received list of peers.
D/WifiDisplayController( 3508):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3508): InactiveState{ what=139283 }
D/WifiDisplayController( 3508):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 3508):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,I/wpa_supplicant( 3830): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3508): InactiveState{ what=147477 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3508): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/WifiDisplayController( 3508): Received list of peers.
,D/WifiDisplayController( 3508):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3508):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3508):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3508): InactiveState{ what=139283 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3508): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3508): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3508): Plugged
,I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/BatteryService( 3508): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5622): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3508): SIOP:: AP = 240, PST = 240, CUR = 27
,I/jxcore-log(11631): teardown
I/jxcore-log(11631): 
,I/jxcore-log(11631): testSendData stopped
I/jxcore-log(11631): 
,I/io.jxcore.node.ConnectionHelper(11631): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11631): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11631): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11631): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11631): shutdown
D/BluetoothSocket(11631): close() in, this: android.bluetooth.BluetoothSocket@12b5c8ad, channel: 6, state: LISTENING
D/BluetoothSocket(11631): close() this: android.bluetooth.BluetoothSocket@12b5c8ad, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3d085fcd, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3d5957e2mSocket: android.net.LocalSocket@329d7773 impl:android.net.LocalSocketImpl@1d631630 fd:FileDescriptor[116]
,D/BluetoothSocket(11631): Closing mSocket: android.net.LocalSocket@329d7773 impl:android.net.LocalSocketImpl@1d631630 fd:FileDescriptor[116]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11631): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11631): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11631): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11631): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11631): stop: Stopping services
,D/WifiP2pService( 3508): InactiveState{ what=139298 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139298 }
D/WifiP2pService( 3508): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11631): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11631): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): onIsWifiPeerDiscoveryStartedChanged: false
,D/WifiP2pService( 3508): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(11631): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11631): release: The given listener does not exist in the list
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11631): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11631): setState: NOT_STARTED
,I/wpa_supplicant( 3830): P2P-FIND-STOPPED 
,I/jxcore-log(11631): StopBroadcasting went ok
I/jxcore-log(11631): 
,D/WifiP2pService( 3508): InactiveState{ what=139307 }
,D/WifiP2pService( 3508): P2pEnabledState{ what=139307 }
D/WifiP2pService( 3508): P2pEnabledState clear service request
D/WifiP2pService( 3508): remove channel information from framework
D/WifiP2pService( 3508): InactiveState{ what=147493 }
I/jxcore-log(11631): 2015-12-23T02:17:57.131Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log(11631): 
D/WifiP2pService( 3508): P2pEnabledState{ what=147493 }
D/WifiP2pService( 3508): discovery change broadcast false
I/io.jxcore.node.ConnectionHelper(11631): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11631): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper(11631): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11631): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11631): Service requests cleared successfully
I/chromium(11631): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log(11631): ****TEST TOOK:  ms ****
I/jxcore-log(11631): 
I/jxcore-log(11631): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(11631): 
,D/AndroidRuntime(13349): 
D/AndroidRuntime(13349): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(13349): CheckJNI is OFF
,D/AndroidRuntime(13349): readGMSProperty: start
D/AndroidRuntime(13349): readGMSProperty: already setted!!
,D/AndroidRuntime(13349): readGMSProperty: end
D/AndroidRuntime(13349): addProductProperty: start
,E/AffinityControl(13349): AffinityControl: registerfunction enter
,D/AndroidRuntime(13349): Calling main entry com.android.commands.pm.Pm
,D/PersonaManagerService( 3508): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
,D/PackageManager( 3508): START PACKAGE DELETE: observer{426301493}
D/PackageManager( 3508): pkg{<packageName>}
D/PackageManager( 3508): user{0}
D/PackageManager( 3508): caller{2000}
D/PackageManager( 3508): flags{3}
D/PersonaManagerService( 3508): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 3508): [MSG] DELETE_PACKAGE_AS_USER
,D/PersonaManagerService( 3508): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3508): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3508): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 3508): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 3508): deletePackage- pkg:com.test.thalitest, edmuserId:-1
,D/PackageManager( 3508): !@killApplicatoin: 10527, uninstall pkg
D/ApplicationPolicy( 3508): getApplicationUninstallationEnabled
I/ActivityManager( 3508): Force stopping com.test.thalitest appid=10527 user=-1: uninstall pkg
D/ApplicationPolicy( 3508): getApplicationUninstallationEnabled :  enabled true
,I/ActivityManager( 3508): Killing 11631:com.test.thalitest/u0a527 (adj 0): stop com.test.thalitest
,I/ActivityManager( 3508):   Force finishing activity ActivityRecord{2cd9877b u0 com.test.thalitest/.MainActivity t26}
,W/ActivityManager( 3508): mDVFSHelper.acquire()
,W/PackageSettings( 3508): Skipping PackageSetting{62f2ef2 com.example.hello/10500} due to missing metadata
,D/WifiService( 3508): Client connection lost with reason: 4
,I/WindowState( 3508): WIN DEATH: Window{1b3fe799 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger( 2849): id=14 Removed NainActivit (5/8)
,I/SurfaceFlinger( 2849): id=14 Removed NainActivit (-2/8)
,I/SurfaceFlinger( 2849): id=14 Removed NainActivit (-2/8)
,I/ActivityManager( 3508): Force stopping com.test.thalitest appid=10527 user=0: pkg removed
,I/ActivityManager( 3508):   Force finishing activity ActivityRecord{2cd9877b u0 com.test.thalitest/.MainActivity t26 f}
W/ActivityManager( 3508): Duplicate finish request for ActivityRecord{2cd9877b u0 com.test.thalitest/.MainActivity t26 f}
,D/PointerIcon( 3508): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 3508): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3508): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3508): setHoveringSpenCustomIcon IconType is same.1
,I/DBG_DM  ( 6243): [com.wssyncmldm.ui.XUIInstallConfirmActivity(456/onResume)] 
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/InputReader( 3508): Reconfiguring input devices.  changes=0x00000010
,I/DBG_DM  ( 6243): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 8
,E/SamsungIME( 4484): mOCRHelper is null
,I/art     ( 8854): Explicit concurrent mark sweep GC freed 26078(1506KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 2.916ms total 67.806ms
,I/art     ( 6720): Explicit concurrent mark sweep GC freed 6647(296KB) AllocSpace objects, 0(0B) LOS objects, 20% free, 31MB/39MB, paused 1.415ms total 79.173ms
,D/LWLocationManager(12935): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(12935): getLastUiLocationId() : mLastUiLocationId = -100
,I/DBG_DM  ( 6243): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,I/art     ( 4055): Explicit concurrent mark sweep GC freed 17747(717KB) AllocSpace objects, 4(64KB) LOS objects, 21% free, 28MB/36MB, paused 712us total 86.434ms
,I/DBG_DM  ( 6243): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/DBG_DM  ( 6243): [com.wssyncmldm.ui.XUIInstallConfirmActivity(466/onResume)] Postpone Count : 8
,W/GeofencerStateMachine( 4641): Ignoring removeGeofence because network location is disabled.
,I/DBG_DM  ( 6243): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/DBG_DM  ( 6243): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,W/ResourceType( 5344): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5344): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/talkback/talkback.apk
,E/Zygote  (13371): MountEmulatedStorage()
E/Zygote  (13371): v2
I/libpersona(13371): KNOX_SDCARD checking this for 10063
I/libpersona(13371): KNOX_SDCARD not a persona
,I/ActivityManager( 3508): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=13371 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (13371): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (13371): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (13371): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 6243): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/EnterpriseDeviceManagerService( 3508): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3508): Admin package name: com.google.android.gms
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/SecContentProvider2( 3508): uri = 14 selection = getSealedState
D/SecContentProvider2( 3508): mCursor = null
D/TimaKeyStoreProvider(13371): TimaSignature is unavailable
,D/ActivityThread(13371): Added TimaKeyStore provider
,D/ApplicationPolicy( 3508): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3508): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/ResourcesManager( 3508): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,I/DBG_DM  ( 6243): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 8
,I/art     ( 3508): Explicit concurrent mark sweep GC freed 50695(4MB) AllocSpace objects, 34(544KB) LOS objects, 24% free, 49MB/65MB, paused 2.171ms total 173.455ms
I/art     ( 3508): WaitForGcToComplete blocked for 150.345ms for cause Explicit
,D/ResourcesManager( 3508): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/DBG_DM  ( 6243): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
D/ResourcesManager(12935): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,I/DBG_DM  ( 6243): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6243): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
,W/Resources( 3508): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3508): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/DBG_DM  ( 6243): [llIIlIIlIllIllIlllII(376/llIIllllIIlllIIIIlll)] 
,I/DBG_DM  ( 6243): [IIlIIIlllllIIlIIIlII(339/llllIlIIIllllIIlIlll)] No need to check encryption status
,I/DBG_DM  ( 6243): [llIIlIIlIllIllIlllII(405/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
,D/ActivityManager( 3508): post active user change for 0
D/KnoxTimeoutHandler( 3508): postActiveUserChange for user 0
,I/DBG_DM  ( 6243): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
,I/SurfaceFlinger( 2849): id=16 createSurf (1440x2560),2 flag=404, YUIInstallC
,D/StatusBarManagerService( 3508): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/StatusBarManagerService( 3508): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/ResourcesManager(13371): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,D/ResourcesManager(12935): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/BatteryService( 3508): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3508): level:100, scale:100, status:5, health:2, present:true, voltage: 4394, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3508): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-7
D/BatteryService( 3508): stay LED for fully charged
,D/VRSetupWizardStub/PackageIntentReceiver(13371): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(13371): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(13371): packagename:com.test.thalitest
,D/ResourcesManager(12935): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,I/KLMS-2.4.521: (11911): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Dec 23 03:17:58 GMT+01:00 2015
,W/Resources( 3508): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/Books/Books.apk
,D/SecContentProvider2( 3508): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3508): mCursor = null
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,I/KLMS-2.4.521: (11911): KLMSAbstractReciever(): onReceive().END.
,D/ResourcesManager(12935): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
I/splitIntent( 3508): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3508): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (11911): KLMSIntentService(): onCreate()
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/KLMS-2.4.521: (11911): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(12935): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,I/KLMS-2.4.521: (11911): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,E/Zygote  (13390): MountEmulatedStorage()
E/Zygote  (13390): v2
I/libpersona(13390): KNOX_SDCARD checking this for 10106
I/libpersona(13390): KNOX_SDCARD not a persona
,I/SELinux (13390): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3508): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=13390 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,I/SELinux (13390): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (13390): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,I/KLMS-2.4.521: (11911): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,W/Resources( 3508): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,I/KLMS-2.4.521: (11911): KLMSIntentService(): PACKAGE_REMOVED
,D/ResourcesManager(12935): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,D/RegisteredServicesCache( 3968): empty dynamic service
,D/RCPManager(12021):  in createShortcut() for packageName: com.test.thalitest userId0
,D/RCPManagerService( 3508):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3508): queryAllProviders():  providerCallBack is not register for 0
,I/KLMS-2.4.521: (11911): KLMSIntentService(): listeningToPackageRemoved().START
,D/ResourcesManager(12935): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,I/KLMS-2.4.521: (11911): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,D/TimaKeyStoreProvider(13390): TimaSignature is unavailable
,E/Zygote  (13405): MountEmulatedStorage()
E/Zygote  (13405): v2
I/libpersona(13405): KNOX_SDCARD checking this for 10160
,I/libpersona(13405): KNOX_SDCARD not a persona
D/ActivityThread(13390): Added TimaKeyStore provider
,I/ActivityManager( 3508): Start proc com.samsung.android.snote for broadcast com.samsung.android.snote/.library.plugin.PluginBroadcastReceiver: pid=13405 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
I/SELinux (13405): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (13405): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (13405): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
,D/ResourcesManager( 3508): creating new AssetManager and set to /data/app/com.facebook.katana-1/base.apk
,D/ResourcesManager(12935): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,E/Zygote  (13420): MountEmulatedStorage()
I/libpersona(13420): KNOX_SDCARD checking this for 10050
E/Zygote  (13420): v2
I/libpersona(13420): KNOX_SDCARD not a persona
I/SELinux (13420): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (13420): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/ResourcesManager(12935): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
E/SELinux (13420): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3508): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=13420 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,D/TimaKeyStoreProvider(13405): TimaSignature is unavailable
,D/ActivityThread(13405): Added TimaKeyStore provider
,I/art     ( 3508): Explicit concurrent mark sweep GC freed 9215(451KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 49MB/65MB, paused 2.710ms total 190.063ms
,D/ResourcesManager(12935): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(12935): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ResourcesManager(12935): creating new AssetManager and set to /system/app/Music2/Music2.apk
I/art     ( 2877): Explicit concurrent mark sweep GC freed 8724(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 914us total 24.898ms
,D/ResourcesManager(12935): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 574us total 10.763ms
,D/TimaKeyStoreProvider(13420): TimaSignature is unavailable
D/ResourcesManager(12935): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
D/ActivityThread(13420): Added TimaKeyStore provider
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(13390): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 514us total 10.313ms
,D/ResourcesManager(12935): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourceType( 3508): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3508): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/ResourcesManager(12935): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12935): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12935): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12935): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,E/Zygote  (13436): MountEmulatedStorage()
E/Zygote  (13436): v2
I/libpersona(13436): KNOX_SDCARD checking this for 10101
I/libpersona(13436): KNOX_SDCARD not a persona
,I/SELinux (13436): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (13436): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3508): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=13436 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (13436): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(13405): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,W/ResourcesManager(13405): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(13405): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13405): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/elm:14491(13390): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/ResourcesManager(12935): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,D/elm:14491(13390): ELMEngine.ELMEngine( context ).
,D/elm:14491(13390): MDMBridge.setEnterpriseBridge()
I/KLMS-2.4.521: (11911): KLMSIntentService(): listeningToPackageRemoved().END
,D/TimaKeyStoreProvider(13436): TimaSignature is unavailable
,D/ActivityThread(13436): Added TimaKeyStore provider
,D/elm:14491(13390): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/ResourcesManager(12935): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/elm:14491(13390): ElmAgentService : onCreate()
,D/elm:14491(13390): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,I/KLMS-2.4.521: (11911): KLMSIntentService(): onDestroy()
D/elm:14491(13390): MainReceiver.listeningToPackageRemoved()
D/elm:14491(13390): MDMBridge.getInstance()
D/elm:14491(13390): MDMBridge.getAllLicenseInfoFromSDK()
,D/ResourcesManager(13420): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/elm:14491(13390): MDMBridge.getAllLicenseInfoFromSDK()
,D/ResourcesManager(12935): creating new AssetManager and set to /system/app/Videos/Videos.apk
,W/ResourcesManager(13420): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(13420): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(13420): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(13420): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(13420): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager(13420): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(13420): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager(13420): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager(13436): creating new AssetManager and set to /system/app/Drive/Drive.apk
,E/Zygote  (13453): MountEmulatedStorage()
I/libpersona(13453): KNOX_SDCARD checking this for 10019
E/Zygote  (13453): v2
I/libpersona(13453): KNOX_SDCARD not a persona
,I/SELinux (13453): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (13453): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3508): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=13453 uid=10019 gids={50019, 9997} abi=armeabi-v7a
E/SELinux (13453): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3508): Killing 11855:com.sec.android.diagmonagent/1000 (adj 15): bgCount ##31
,D/elm:14491(13390): ElmAgentService : onDestroy().
,I/ActivityManager( 3508): Killing 11881:com.sec.android.fotaclient/u0a12 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(13453): TimaSignature is unavailable
,D/ActivityThread(13453): Added TimaKeyStore provider
,D/ResourcesManager(12935): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,V/Common  (13405): getScreenSize 1440 2560
D/ResourcesManager(13453): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,W/Resources( 3508): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3508): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,I/JAM     (13405): Load The ApaService JNI
,I/JAM     (13405): version: ProfessionalAudio_v1.0.b5
I/JAM     (13405): Try v1.0.b3 ...
D/Spen    (13405): SpenSdk version level = 55
D/Spen    (13405): SpenSdk jar version = 3.0.243
D/ResourcesManager( 3508): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,D/Spen    (13405): SpenSdk apk version = 3.0.235
D/Spen    (13405): Server UPDATE Check
,W/linker  (13405): libSPenBase.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
D/PackageManager( 3508): delete codoeFile: 
,W/Resources( 3508): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/SPenError(13405): JNI_OnLoad
,D/JNI_Bitmap(13405): Init .. Done
D/SPenSpiDecoder(13405): JNI_OnLoad .. Done
D/SPenError(13405): JNI_OnLoad Success
,W/Resources( 3508): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/PluginManager(13405): Registering com/samsung/android/sdk/pen/plugin/framework/JniPluginManager natives
D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/PluginManager(13405): Registering com/samsung/android/sdk/pen/plugin/framework/SpenPluginManager$PluginListener natives
,I/AASAUninstall( 3508):  com.test.thalitest not target!
D/PackageManager( 3508): result of delete: 1{426301493}
D/Init_SPenSdk_Jni(13405): JNI_OnLoad
,D/Init_SPenSdk_Jni(13405): AndroidSDK: 21
D/Init_SPenSdk_Jni(13405): JNI_OnLoad .. Done
D/ResourcesManager( 3508): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager(12935): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/Model_ObjectBase_Jni(13405): JNI_OnLoad .. Done
D/Model_ObjectStroke_Jni(13405): JNI_OnLoad .. Done
D/Model_ObjectImage_Jni(13405): JNI_OnLoad .. Done
,D/Model_ObjectText_Jni(13405): JNI_OnLoad .. Done
D/Model_ObjectContainer_Jni(13405): JNI_OnLoad .. Done
D/Model_PageDoc_Jni(13405): JNI_OnLoad .. Done
D/AndroidRuntime(13349): Shutting down VM
D/ResourcesManager( 3508): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/Model_NoteDoc_Jni(13405): check build type eng[0]
,D/Model_NoteDoc_Jni(13405): JNI_OnLoad .. Done
D/Model_NoteFile_Jni(13405): JNI_OnLoad .. Done
D/Model_ObjectUtil_Jni(13405): JNI_OnLoad .. Done
D/Model   (13405): OnLoad class Done
D/ResourcesManager( 3508): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager( 3508): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,E/Zygote  (13471): MountEmulatedStorage()
E/Zygote  (13471): v2
I/libpersona(13471): KNOX_SDCARD checking this for 10160
D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/Books/Books.apk
I/libpersona(13471): KNOX_SDCARD not a persona
,I/SELinux (13471): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/spe_log (13405): SPen::GLRenderThreadImpl::GLRenderThreadImpl() Initialize: 0
,D/SPen_Library(13405): Draw Engine JNI_OnLoad enter!!
D/SPen_Library(13405): Canvas JNI_OnLoad enter!!
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/SPen_Library(13405): Canvas JNI_OnLoad Success
D/SPen_Library(13405): TextView JNI_OnLoad enter!!
D/SPen_Library(13405): TextView JNI_OnLoad Success
D/SPen_Library(13405): Text JNI_OnLoad enter!!
D/SPen_Library(13405): Text JNI_OnLoad Success
D/SPen_Library(13405): FontManager JNI_OnLoad enter!!
D/SPen_Library(13405): FontManager JNI_OnLoad Success
D/SPen_Library(13405): CapturePage JNI_OnLoad enter!!
D/SPen_Library(13405): CapturePage JNI_OnLoad Success
D/SPen_Library(13405): Multi JNI_OnLoad enter!!
,D/SPen_Library(13405): Multi JNI_OnLoad Success
D/SPen_Library(13405): Draw Engine JNI_OnLoad Success
I/SELinux (13471): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/SPen_Library(13405): Brush JNI_OnLoad enter!!
E/SELinux (13471): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/SPen_Library(13405): Brush JNI_OnLoad Success
,I/ActivityManager( 3508): Start proc com.samsung.android.snote:provider for content provider com.samsung.android.snote/.model.provider.SNoteProvider: pid=13471 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
D/SPen_Library(13405): ChineseBrush JNI_OnLoad enter!!
,D/SPen_Library(13405): ChineseBrush JNI_OnLoad Success
D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/SPen_Library(13405): InkPen JNI_OnLoad enter!!
D/SPen_Library(13405): InkPen JNI_OnLoad Success
,D/DocsApplication(13436): Installing DEX configuration.
D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/SPen_Library(13405): Marker JNI_OnLoad enter!!
D/SPen_Library(13405): Marker JNI_OnLoad Success
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/SPen_Library(13405): Pencil JNI_OnLoad enter!!
D/SPen_Library(13405): Pencil JNI_OnLoad Success
D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/DexInstaller(13436): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,D/com.sec.android.service.health.upgrade.UninstallReceiver(13453): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver(13453): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/SPen_Library(13405): NativePen JNI_OnLoad enter!!
D/com.sec.android.service.health.upgrade.UninstallReceiver(13453): onReceive() : package name is not s health. Return !!!
D/SPen_Library(13405): NativePen JNI_OnLoad Success
,D/SPen_Library(13405): MontblancFountainPen JNI_OnLoad enter!!
,D/SPen_Library(13405): MontblancFountainPen JNI_OnLoad Success
,D/SPen_Library(13405): MontblancCalligraphyPen JNI_OnLoad enter!!
,D/SPen_Library(13405): MontblancCalligraphyPen JNI_OnLoad Success
,I/PackageInfoHelper(13436): Provided clientMode=RELEASE, packageInfo=PackageInfo{2d4db99a com.google.android.apps.docs}
D/SPen_Library(13405): MagicPen JNI_OnLoad enter!!
,D/SPen_Library(13405): MagicPen JNI_OnLoad Success
D/TAG     (13436): onCreate()
D/ResourcesManager(12935): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,D/SPen_Library(13405): ObliquePen JNI_OnLoad enter!!
D/SPen_Library(13405): ObliquePen JNI_OnLoad Success
D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/CrossAppStateProvider(13436): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
D/SPen_Library(13405): FountainPen JNI_OnLoad enter!!
D/SPen_Library(13405): FountainPen JNI_OnLoad Success
D/Spen    (13405): SpenSdk Libraries are loaded.
D/Init_SPenSdk_Jni(13405): SPenSdk_init2
D/Init_SPenSdk(13405): Init - screen_width = 1440, screen_height = 2560, maxCacheSize = 100 M
D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/Init_SPenSdk(13405): Total S Pen SDK Directory Size = 0
D/Spen    (13405): initialize complete
W/linker  (13405): libSPenImageFilterLibs.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/LocationWidgetApplication(12935): getLastUiLocationId() : mLastUiLocationId = -100
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(12935): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,D/TimaKeyStoreProvider(13471): TimaSignature is unavailable
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/Resources( 3508): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ActivityThread(13471): Added TimaKeyStore provider
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/ResourcesManager(12935): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/Resources( 3508): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3508): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,W/ResourcesManager( 3508): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3508): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3508): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3508): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,W/Resources( 3508): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(12935): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager(12935): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/ResourcesManager(12935): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
,D/ResourcesManager(12935): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/PackageManager( 3508): findPreferredActivity: No PreferredActivities set
,D/ResourcesManager( 3508): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager( 3508): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/RCPManagerService( 3508): PackageReceiver onReceive()
I/HarmonyEASService( 3508): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 3508): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService( 3508): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 3508): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3508): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3508): uID is 10527
V/EnterpriseBillingPolicy( 3508): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3508): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 3508): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3508): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3508): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3508): getBillingProfileForVpnEngine - start - com.test.thalitest
D/ResourcesManager( 3508): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,V/EnterpriseBillingPolicyStorage( 3508): getBillingProfileForVpnEngine - end - null
,D/ResourcesManager( 3508): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources( 3508): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3508): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(12935): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
W/Resources( 3508): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3508): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3508): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources( 3508): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3508): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources( 3508): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3508): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3508): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,W/Resources( 3508): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3508): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 3508): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(12935): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(12935): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
,D/ResourcesManager(12935): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(12935): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(12935): creating new AssetManager and set to /system/app/FBInstagram_stub/FBInstagram_stub.apk
,D/ResourcesManager(12935): creating new AssetManager and set to /system/app/FBMessenger_stub/FBMessenger_stub.apk
,D/ResourcesManager(12935): creating new AssetManager and set to /system/app/FBPagesManager_stub/FBPagesManager_stub.apk
,D/ResourcesManager(12935): creating new AssetManager and set to /system/app/Maps/Maps.apk
,D/ResourcesManager(12935): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/PointerIcon( 3508): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 3508): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3508): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
V/ActivityThread( 6243): updateVisibility : ActivityRecord{251a47e2 token=android.os.BinderProxy@3a361d57 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
D/PointerIcon( 3508): setHoveringSpenCustomIcon IconType is same.1
,D/ResourcesManager(12935): creating new AssetManager and set to /system/app/PENUP/PENUP.apk
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(12935): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,E/Zygote  (13491): MountEmulatedStorage()
E/Zygote  (13491): v2
,I/libpersona(13491): KNOX_SDCARD checking this for 1000
I/libpersona(13491): KNOX_SDCARD not a persona
,I/SELinux (13491): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3508): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=13491 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ResourcesManager(12935): creating new AssetManager and set to /system/app/SecCalculator2/SecCalculator2.apk
,I/SELinux (13491): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3508): Killing 11933:com.sec.android.soagent/u0a38 (adj 15): bgCount ##31
,E/SELinux (13491): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/CrashAnrDetector( 3508): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager( 3508): clearDefaults: com.test.thalitest
,D/ResourcesManager(12935): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/ResourcesManager(12935): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,D/InputMethodManagerService( 3508): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3508): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ResourcesManager(12935): creating new AssetManager and set to /data/app/com.facebook.katana-1/base.apk
W/InputMethodManagerService( 3508): Got RemoteException sending setActive(false) notification to pid 11631 uid 10527
,E/Zygote  (13507): MountEmulatedStorage()
E/Zygote  (13507): v2
,I/libpersona(13507): KNOX_SDCARD checking this for 10183
I/libpersona(13507): KNOX_SDCARD not a persona
,I/ActivityManager( 3508): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=13507 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
I/SELinux (13507): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3508): Killing 11204:com.osp.app.signin/u0a45 (adj 15): bgCount ##31
,I/ActivityManager( 3508): Killing 11959:com.policydm/1000 (adj 15): bgCount ##32
,I/SELinux (13507): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (13507): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(13491): TimaSignature is unavailable
,D/ActivityThread(13491): Added TimaKeyStore provider
,I/Timeline( 6243): Timeline: Activity_idle id: android.os.BinderProxy@3a361d57 time:659765
,D/TaskPersister( 3508): removeObsoleteFile: deleting file=26_task.xml
D/TaskPersister( 3508): removeObsoleteFile: deleting file=24_task.xml
,D/ResourcesManager(13471): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/KnoxTimeoutHandler( 3508): handleActiveUserChange for user 0
,W/ResourcesManager(13471): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(13471): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13471): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/BatteryService( 3508): Sending ACTION_BATTERY_CHANGED.
,W/ActivityManager( 3508): mDVFSHelper.release()
,D/TimaKeyStoreProvider(13507): TimaSignature is unavailable
I/Timeline( 3508): Timeline: Activity_windows_visible id: ActivityRecord{3331b705 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t24} time:659804
,D/ActivityThread(13507): Added TimaKeyStore provider
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/ResourcesManager(13491): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/MotionRecognitionService( 3508): Plugged
I/MotionRecognitionService( 3508): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5622): Disconnected process message: 10
,I/PCWCLIENTTRACE_LOG(13491): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(13491): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(13491): new DMDBOpenHelper instance
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/StatusBar( 3694): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/NearbySource(13420): Nearby Source Create!
D/NearbyContext(13420): Nearby Context Create!
,E/SQLiteLog(13491): (28) failed to open "/data/data/com.sec.pcw.device/databases/value.db" with flag (131138) and mode_t (0) due to error (30)
D/PersonaManager( 3694): isKioskContainerExistOnDevice
D/PersonaManager( 3694): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3694): Icon Only
I/StatusBar( 3694): Icon Only
D/PanelView( 3694): There is/are notification(s) 
,D/PanelView( 3694): There is/are notification(s) 
E/SQLiteDatabase(13491): Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
E/SQLiteDatabase(13491): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(13491): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(13491): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(13491): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(13491): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(13491): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(13491): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(13491): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(13491): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(13491): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(13491): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(13491): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(13491): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(13491): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(13491): 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
E/SQLiteDatabase(13491): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/SQLiteDatabase(13491): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/SQLiteDatabase(13491): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/SQLiteDatabase(13491): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/SQLiteDatabase(13491): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/SQLiteDatabase(13491): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(13491): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(13491): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(13491): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(13491): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(13491): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(13491): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(13491): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(13491): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime(13491): Shutting down VM
D/PersonaManager( 3694): isKioskContainerExistOnDevice
E/AndroidRuntime(13491): FATAL EXCEPTION: main
E/AndroidRuntime(13491): Process: com.sec.pcw.device, PID: 13491
E/AndroidRuntime(13491): java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.DMProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(13491): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5564)
E/AndroidRuntime(13491): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/AndroidRuntime(13491): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/AndroidRuntime(13491): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/AndroidRuntime(13491): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/AndroidRuntime(13491): 	at android.os.Ha,ndler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(13491): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(13491): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(13491): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(13491): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(13491): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(13491): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(13491): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(13491): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(13491): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(13491): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(13491): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(13491): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(13491): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(13491): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(13491): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(13491): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(13491): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(13491): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(13491): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(13491): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(13491): 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
E/AndroidRuntime(13491): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/AndroidRuntime(13491): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/AndroidRuntime(13491): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/AndroidRuntime(13491): 	... 11 more
I/PhoneStatusBar( 3694): Icon Only
I/StatusBar( 3694): Icon Only
D/PanelView( 3694): There is/are notification(s) 
D/ResourcesManager(12935): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
D/ResourcesManager(13507): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,D/SNoteProvider(13471): onCreate enableSnoteSync = true
,V/ApplicationPolicy( 3508): isApplicationStateBlocked userId 0 pkgname com.sec.pcw.device
,D/SNoteProvider(13471): ===query=== 
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
W/ContextImpl(13420): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource(13420): Samsung link source created
,D/ResourcesManager(12935): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,E/SQLiteLog(13471): (28) failed to open "/data/user/0/com.samsung.android.snote/databases/Snote.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteLog(13507): (28) failed to open "/data/data/com.samsung.android.provider.shootingmodeprovider/databases/shootingmodemanager.db" with flag (131138) and mode_t (0) due to error (30)
,E/DropBoxManagerService( 3508): Can't write: system_app_crash
E/DropBoxManagerService( 3508): java.io.FileNotFoundException: /data/system/dropbox/drop196.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3508): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3508): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3508): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3508): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3508): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3508): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3508): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3508): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3508): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3508): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3508): 	... 5 more
,E/SQLiteDatabase(13507): Failed to open database '/data/data/com.samsung.android.provider.shootingmodeprovider/databases/shootingmodemanager.db'.
E/SQLiteDatabase(13507): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(13507): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(13507): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(13507): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(13507): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(13507): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(13507): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(13507): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(13507): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(13507): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(13507): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(13507): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(13507): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(13507): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(13507): 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.initializeSQLiteStatements(ShootingModeProvider.java:269)
E/SQLiteDatabase(13507): 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.onCreate(ShootingModeProvider.java:232)
E/SQLiteDatabase(13507): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/SQLiteDatabase(13507): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/SQLiteDatabase(13507): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/SQLiteDatabase(13507): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/SQLiteDatabase(13507): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/SQLiteDatabase(13507): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(13507): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(13507): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(13507): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(13507): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(13507): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(13507): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(13507): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(13507): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/Zygote  (13527): MountEmulatedStorage()
E/Zygote  (13527): v2
I/libpersona(13527): KNOX_SDCARD checking this for 10035
I/libpersona(13527): KNOX_SDCARD not a persona
D/AndroidRuntime(13507): Shutting down VM
,E/AndroidRuntime(13507): FATAL EXCEPTION: main
E/AndroidRuntime(13507): Process: com.samsung.android.provider.shootingmodeprovider, PID: 13507
E/AndroidRuntime(13507): java.lang.RuntimeException: Unable to get provider com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(13507): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5564)
E/AndroidRuntime(13507): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/AndroidRuntime(13507): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/AndroidRuntime(13507): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/AndroidRuntime(13507): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/AndroidRuntime(13507): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(13507): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(13507): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(13507): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(13507): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(13507): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(13507): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(13507): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(13507): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(13507): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(13507): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(13507): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(13507): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(13507): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(13507): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(13507): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(13507): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(13507): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(13507): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(13507): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(13507): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(13507): 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.initializeSQLiteStatements(ShootingModeProvider.java:269)
E/AndroidRuntime(13507): 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.onCreate(ShootingModeProvider.java:232)
E/AndroidRuntime(13507): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/AndroidRuntime(13507): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/AndroidRuntime(13507): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/AndroidRuntime(13507): 	... 11 more
,I/ActivityManager( 3508): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=13527 uid=10035 gids={50035, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
E/SQLiteDatabase(13471): Failed to open database '/data/user/0/com.samsung.android.snote/databases/Snote.db'.
E/SQLiteDatabase(13471): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(13471): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(13471): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(13471): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(13471): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(13471): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(13471): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(13471): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(13471): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(13471): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(13471): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(13471): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(13471): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(13471): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(13471): 	at com.samsung.android.snote.model.provider.SNoteProvider.a(SourceFile:156)
E/SQLiteDatabase(13471): 	at com.samsung.android.snote.model.provider.SNoteProvider.a(SourceFile:2285)
E/SQLiteDatabase(13471): 	at com.samsung.android.snote.model.provider.SNoteProvider.query(SourceFile:751)
E/SQLiteDatabase(13471): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/SQLiteDatabase(13471): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/SQLiteDatabase(13471): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteDatabase(13471): 	at android.os.Binder.execTransact(Binder.java:446)
I/SELinux (13527): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
W/System.err(13471): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err(13471): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err(13471): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
W/System.err(13471): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
W/System.err(13471): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err(13471): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err(13471): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err(13471): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
W/System.err(13471): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
W/System.err(13471): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
,V/ApplicationPolicy( 3508): isApplicationStateBlocked userId 0 pkgname com.samsung.android.provider.shootingmodeprovider
W/System.err(13471): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
W/System.err(13471): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err(13471): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err(13471): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err(13471): 	at com.samsung.android.snote.model.provider.SNoteProvider.a(SourceFile:156)
W/System.err(13471): 	at com.samsung.android.snote.model.provider.SNoteProvider.a(SourceFile:2285)
W/System.err(13471): 	at com.samsung.android.snote.model.provider.SNoteProvider.query(SourceFile:751)
W/System.err(13471): 	at android.content.ContentProvider.query(ContentProvider.java:987)
W/System.err(13471): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
W/System.err(13471): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
W/System.err(13471): 	at android.os.Binder.execTransact(Binder.java:446)
D/SNoteProvider(13471): message = not an error (code 0): Could not open the database in read/write mode.
,I/ActivityManager( 3508): Killing 12005:com.samsung.android.scloud.backup/u0a67 (adj 15): bgCount ##31
,I/SELinux (13527): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (13527): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/Common  (13471): getScreenSize 1440 2560
,D/UsbHostManager( 3508): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
,I/Process (13491): Sending signal. PID: 13491 SIG: 9
D/UsbHostManager( 3508): displayNotification : [02h,02h,01h]
D/UsbHostManager( 3508): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
D/UsbHostManager( 3508): displayNotification : [0ah,00h,00h]
,E/SQLiteLog(13420): (28) failed to open "/data/data/com.sec.android.gallery3d/databases/local.db" with flag (131138) and mode_t (0) due to error (30)
D/UsbHostManager( 3508): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3508): displayNotification : [02h,0dh,00h]
,I/ActivityManager( 3508): Killing 12037:com.android.chrome/u0a90 (adj 13): bgCount ##31
,E/DropBoxManagerService( 3508): Can't write: system_app_crash
E/DropBoxManagerService( 3508): java.io.FileNotFoundException: /data/system/dropbox/drop197.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3508): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3508): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3508): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3508): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3508): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3508): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3508): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3508): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3508): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3508): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3508): 	... 5 more
D/UsbHostManager( 3508): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3508): displayNotification : [0ah,00h,01h]
,E/SQLiteDatabase(13420): Failed to open database '/data/data/com.sec.android.gallery3d/databases/local.db'.
E/SQLiteDatabase(13420): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(13420): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(13420): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(13420): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(13420): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(13420): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(13420): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(13420): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(13420): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(13420): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(13420): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(13420): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(13420): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(13420): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(13420): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteDatabase(13420): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteDatabase(13420): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteDatabase(13420): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:202)
E/SQLiteDatabase(13420): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:194)
E/SQLiteDatabase(13420): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(13420): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(13420): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(13420): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(13420): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(13420): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(13420): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(13420): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(13420): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(13420): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(13420): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper(13420): Couldn't open local.db for writing (will try read-only):
E/SQLiteOpenHelper(13420): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(13420): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(13420): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(13420): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(13420): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(13420): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(13420): 	at android.database.sqlite.SQLiteConne,ctionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(13420): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(13420): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(13420): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(13420): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(13420): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(13420): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(13420): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(13420): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteOpenHelper(13420): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteOpenHelper(13420): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteOpenHelper(13420): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:202)
E/SQLiteOpenHelper(13420): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:194)
E/SQLiteOpenHelper(13420): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(13420): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(13420): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(13420): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(13420): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(13420): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(13420): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(13420): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(13420): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(13420): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(13420): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/UsbHostManager( 3508): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
W/SQLiteOpenHelper(13420): Opened local.db in read-only mode
D/UsbHostManager( 3508): displayNotification : [09h,00h,00h]
D/UsbHostManager( 3508): usbDeviceRemoved : /dev/bus/usb/001/003
E/UsbHostManager( 3508): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
D/UsbSettingsManager( 3508): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,D/WifiDisplayAdapter( 3508): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/PanelView( 3694): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,E/Zygote  (13550): MountEmulatedStorage()
E/Zygote  (13550): v2
I/libpersona(13550): KNOX_SDCARD checking this for 10190
I/libpersona(13550): KNOX_SDCARD not a persona
,I/SELinux (13550): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (13550): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (13550): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3508): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=13550 uid=10190 gids={50190, 9997} abi=armeabi-v7a
,D/TimaKeyStoreProvider(13527): TimaSignature is unavailable
,I/Process (13507): Sending signal. PID: 13507 SIG: 9
,D/ActivityThread(13527): Added TimaKeyStore provider
,D/SNoteProvider(13471): ===query=== 
,E/SQLiteLog(13471): (28) failed to open "/data/user/0/com.samsung.android.snote/databases/Snote.db" with flag (131138) and mode_t (0) due to error (30)
,D/WifiDisplayAdapter( 3508): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/SQLiteDatabase(13471): Failed to open database '/data/user/0/com.samsung.android.snote/databases/Snote.db'.
E/SQLiteDatabase(13471): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(13471): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(13471): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(13471): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(13471): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(13471): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(13471): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(13471): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(13471): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(13471): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(13471): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(13471): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(13471): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(13471): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(13471): 	at com.samsung.android.snote.model.provider.SNoteProvider.a(SourceFile:156)
E/SQLiteDatabase(13471): 	at com.samsung.android.snote.model.provider.SNoteProvider.a(SourceFile:2285)
E/SQLiteDatabase(13471): 	at com.samsung.android.snote.model.provider.SNoteProvider.query(SourceFile:751)
E/SQLiteDatabase(13471): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/SQLiteDatabase(13471): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/SQLiteDatabase(13471): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteDatabase(13471): 	at android.os.Binder.execTransact(Binder.java:446)
W/System.err(13471): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err(13471): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err(13471): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
W/System.err(13471): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
W/System.err(13471): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err(13471): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err(13471): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err(13471): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
W/System.err(13471): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
W/System.err(13471): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
W/System.err(13471): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
W/System.err(13471): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err(13471): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err(13471): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err(13471): 	at com.samsung.android.snote.model.provider.SNoteProvider.a(SourceFile:156)
W/System.err(13471): 	at com.samsung.android.snote.model.provider.SNoteProvider.a(SourceFile:2285)
W/System.err(13471): 	at com.samsung.android.snote.model.provid,er.SNoteProvider.query(SourceFile:751)
W/System.err(13471): 	at android.content.ContentProvider.query(ContentProvider.java:987)
W/System.err(13471): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
W/System.err(13471): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
W/System.err(13471): 	at android.os.Binder.execTransact(Binder.java:446)
D/SNoteProvider(13471): message = not an error (code 0): Could not open the database in read/write mode.
,I/ActivityManager( 3508): Process com.samsung.android.provider.shootingmodeprovider (pid 13507)(adj 9) has died(213,1164)
,D/ContactProvider(13420): getAllContactInfoList Start
,D/UsbHostManager( 3508): usbDeviceRemoved : /dev/bus/usb/001/001
E/UsbHostManager( 3508): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
,D/TimaKeyStoreProvider(13550): TimaSignature is unavailable
,D/ActivityThread(13550): Added TimaKeyStore provider
,D/ResourcesManager(13527): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,I/EventHub( 3508): Removing device '/dev/input/event10' due to inotify event
D/MtpClient(13420): onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
D/MtpClient(13420): ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
,I/EventHub( 3508): Removing device '/dev/input/event7' due to inotify event
,E/SharedPreferencesImpl(13420): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
,I/ActivityManager( 3508): Process com.sec.pcw.device (pid 13491)(adj 9) has died(209,1165)
,D/ResourcesManager(13550): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,I/TapandpayWidget:TanpandpayAppWidgetProvider(13550): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(13550): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,I/TapandpayWidget:Utils(13550): Clear T&P info.
,E/Zygote  (13568): MountEmulatedStorage()
E/Zygote  (13568): v2
I/libpersona(13568): KNOX_SDCARD checking this for 10052
I/libpersona(13568): KNOX_SDCARD not a persona
,I/SELinux (13568): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/EventHub( 3508): Removing device '/dev/input/event8' due to inotify event
D/TapandpayWidget:TanpandpayAppWidgetProvider(13550): Widget is not attached.
,I/SELinux (13568): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027,
,I/ActivityManager( 3508): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=13568 uid=10052 gids={50052, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,E/SELinux (13568): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/FeatureConfig(13527): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,I/EventHub( 3508): Removing device '/dev/input/event9' due to inotify event
,I/EventHub( 3508): Removing device '/dev/input/event11' due to inotify event
,D/PackageBroadcastService( 6720): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 6720): Clearing selected account for com.test.thalitest
,D/TimaKeyStoreProvider(13568): TimaSignature is unavailable
I/EventHub( 3508): Removing device '/dev/input/event12' due to inotify event
,D/ActivityThread(13568): Added TimaKeyStore provider
,D/ResourcesManager(13527): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager(13527): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(13527): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(13527): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(13527): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13527): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(13527): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager(13527): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,E/SQLiteLog( 6720): (10) POSIX Error : 9 SQLite Error : 3850
W/ResourcesManager(13527): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/SQLiteLog( 6720): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/ResourcesManager(13527): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(13527): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/DriveAsyncService( 6720): disk I/O error (code 3850)
E/DriveAsyncService( 6720): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 6720): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 6720): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/DriveAsyncService( 6720): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 6720): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 6720): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/DriveAsyncService( 6720): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
E/DriveAsyncService( 6720): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 6720): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 6720): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 6720): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 6720): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 6720): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 6720): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 6720): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 6720): 	at java.lang.Thread.run(Thread.java:818)
,I/EventHub( 3508): Removing device '/dev/input/event13' due to inotify event
,D/ResourcesManager(13527): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
W/ResourcesManager(13527): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager(13527): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(13527): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager(13527): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(13527): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(13527): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13527): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager(13527): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ChimeraCfgMgr( 6720): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6720): Module APK com.google.android.play.games already loaded
,D/ResourcesManager(13527): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
W/ResourcesManager(13527): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
I/EventHub( 3508): Removing device '/dev/input/event14' due to inotify event
W/ResourcesManager(13527): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(13527): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13527): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(13568): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager(13568): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager(13568): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(13568): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(13568): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(13568): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager(13568): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager(13527): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,W/ResourcesManager(13527): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(13527): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13527): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/Zygote  (13587): MountEmulatedStorage()
E/Zygote  (13587): v2
I/libpersona(13587): KNOX_SDCARD checking this for 10031
I/libpersona(13587): KNOX_SDCARD not a persona
,I/SELinux (13587): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (13587): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/ResourcesManager(13527): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,E/SELinux (13587): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3508): Start proc com.android.vending for preferred application com.android.vending: pid=13587 uid=10031 gids={50031, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager(13527): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(13527): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(13527): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(13527): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13527): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager(13527): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager(13527): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(13527): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/LocationSettingsChecker( 6720): Removing dialog suppression flag for package com.test.thalitest
,E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3508): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(13527): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/ChimeraCfgMgr( 6720): Loading module com.google.android.gms.games from APK com.google.android.play.games
W/ResourcesManager(13527): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ChimeraModuleLdr( 6720): Module APK com.google.android.play.games already loaded
W/ResourcesManager(13527): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(13527): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.

```
