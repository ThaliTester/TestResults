#### Test 5644966031ce140_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 273, CUR = 40
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:65, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:62
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3523): stay LED for fully charged
I/MotionRecognitionService( 3523): Plugged
I/MotionRecognitionService( 3523): setPowerConnected  = true
--------- beginning of main
D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5650): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5650): Disconnected process message: 10
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AndroidRuntime(11729): 
D/AndroidRuntime(11729): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11729): CheckJNI is OFF
D/AndroidRuntime(11729): readGMSProperty: start
D/AndroidRuntime(11729): readGMSProperty: already setted!!
D/AndroidRuntime(11729): readGMSProperty: end
D/AndroidRuntime(11729): addProductProperty: start
E/AffinityControl(11729): AffinityControl: registerfunction enter
D/AndroidRuntime(11729): Calling main entry com.android.commands.am.Am
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
E/Zygote  (11750): MountEmulatedStorage()
E/Zygote  (11750): v2
I/libpersona(11750): KNOX_SDCARD checking this for 10589
I/libpersona(11750): KNOX_SDCARD not a persona
I/SELinux (11750): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11750): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3523): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=11750 uid=10589 gids={50589, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/SELinux (11750): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(11729): Shutting down VM
D/PointerIcon( 3523): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3523): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3523): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3523): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(11750): TimaSignature is unavailable
D/ActivityThread(11750): Added TimaKeyStore provider
I/SurfaceFlinger( 2849): id=11 Removed YUIInstallC (5/8)
I/SurfaceFlinger( 2849): id=11 Removed YUIInstallC (-2/8)
D/ResourcesManager(11750): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
V/ActivityThread( 6239): updateVisibility : ActivityRecord{3b0e6dfe token=android.os.BinderProxy@c224083 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
I/WebViewFactory(11750): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(11750): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(11750): Loading: webviewchromium
I/LibraryLoader(11750): Time to load native libraries: 3 ms (timestamps 4846-4849)
I/LibraryLoader(11750): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(11750): Binding Chromium to main looper Looper (main, tid 1) {3bec4f09}
,I/LibraryLoader(11750): Expected native library version number "",actual native library version number ""
I/chromium(11750): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(11750): Initializing chromium process, renderers=0
,W/art     (11750): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(11750): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(11750): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(11750): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,W/chromium(11750): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(11750): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (11750): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(11750): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(11750): CordovaWebView is running on device made by: samsung
,W/art     (11750): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11750): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity(11750): performCreate Call secproduct feature valuefalse
D/Activity(11750): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(11750): Render dirty regions requested: true
,D/ActivityManager( 3523): post active user change for 0
D/KnoxTimeoutHandler( 3523): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3523): handleActiveUserChange for user 0
,I/SurfaceFlinger( 2849): id=14 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService( 3523): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3523): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3523): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 3523): setMouseCustomIcon IconType is same.101
I/OpenGLRenderer(11750): Initialized EGL, version 1.4
D/PointerIcon( 3523): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3523): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer(11750): HWUI protection enabled for context ,  &this =0xafa45060 ,&mEglDisplay = 1 , &mEglConfig = -1278643952 
,D/OpenGLRenderer(11750): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(11750): Enabling debug mode 0
,D/mali_winsys(11750): new_window_surface returns 0x3000,  [1440x2560]-format:1
,V/ActivityThread(11750): updateVisibility : ActivityRecord{34a0c79 token=android.os.BinderProxy@2cc345a4 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/InputMethodManagerService( 3523): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 3523): mDVFSHelper.release()
I/Timeline( 3523): Timeline: Activity_windows_visible id: ActivityRecord{2f3513e2 u0 com.test.thalitest/.MainActivity t26} time:135208
,W/IInputConnectionWrapper(11750): showStatusIcon on inactive InputConnection
,I/Timeline(11750): Timeline: Activity_idle id: android.os.BinderProxy@2cc345a4 time:135217
,I/chromium(11750): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11750): 
,D/JsMessageQueue(11750): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log(11750): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1361619200
,I/chromium(11750): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,W/jxcore-log(11750): Initializing JXcore engine
W/jxcore-log(11750): JXcore engine is ready
,E/auditd  ( 4616): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3523): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
D/SecurityLogAgent:SEDenialService( 3523): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(11750): Starting JXcore engine
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
,D/BluetoothAdapter(11750): enable(): BT is already enabled..!
,D/WifiService( 3523): New client listening to asynchronous messages
,I/WifiManager(11750): packageName : com.test.thalitest
,D/SecContentProvider( 3523): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3523): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3523): mCursor = null
,D/WifiService( 3523): setWifiEnabled: true pid=11750, uid=10589
E/WifiService( 3523): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3523): Permission Denial: getCurrentUser() from pid=11750, uid=10589 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 3523): Failed getting userId using ActivityManagerNative
W/WifiService( 3523): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=11750, uid=10589 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3523): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3523): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3523): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3523): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3523): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider( 3523): name = wifi_on
,I/WifiService( 3523): disconnect: pid=11750, uid=10589
,I/wpa_supplicant( 3834): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/wpa_supplicant( 3834): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3834): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 3834): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3834): wlan0: State: DISCONNECTED -> DISCONNECTED
I/jxcore-log(11750): Radios toggled
I/jxcore-log(11750): 
E/WifiStateMachine( 3523): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 3834): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3834): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3834): Disconnected - do not scan
I/wpa_supplicant( 3834): wlan0: State: DISCONNECTED -> DISCONNECTED
I/jxcore-log(11750): My device name is: samsung-SM-N910C
I/jxcore-log(11750): 
E/WifiStateMachine( 3523): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3523): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3523): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3523): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine( 3523): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3523): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3523): do suspend true
,D/WifiP2pService( 3523): InactiveState{ what=143375 }
D/WifiP2pService( 3523): P2pEnabledState{ what=143375 }
,D/CommandListener( 2845): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,E/Netd    ( 2845): ifc_reset_connections failed on iface wlan0 for address 192.168.1.124/24 (Unknown error -1)
,E/WifiStateMachine( 3523): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService( 3523): updateNetworkInfo()
E/WifiConfigStore( 3523): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/WifiTrafficPoller( 3523): evaluateTrafficStatsPolling
,D/ConnectivityService( 3523): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3523): updateNetworkInfo()
,D/ConnectivityService( 3523): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,I/Hs20UtilService( 4112): Starting #8
,I/Hs20UtilService( 4112): Message received 5007
,E/WifiStateMachine( 3523): Start Disconnecting Watchdog 1
D/NearbySettings( 8752): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 8752): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings( 8752): MountReceiver.onReceive - Create mPrefHandler
,E/WifiStateMachine( 3523): ConnectModeState: Network connection lost 
E/WifiStateMachine( 3523): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - processMessage - processMsg
E/WifiStateMachine( 3523): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
D/NearbySettings( 8752): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 3523): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3523): do suspend true
V/NearbySettings( 8752): DMSUtil.isNetworkConnected - flag-null, state-null
,D/WifiP2pService( 3523): InactiveState{ what=143375 }
D/WifiP2pService( 3523): P2pEnabledState{ what=143375 }
,I/NearbySettings( 8752): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiService( 3523): New client listening to asynchronous messages
,I/NearbySettings( 8752): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8752): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8752): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 8752): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11363): NETWORK_STATE_CHANGED_ACTION
,D/CommandListener( 2845): Clearing all IP addresses on wlan0
,D/ConnectivityService( 3523): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/EntConnectivity( 3523): Not allowed due to - mEnabled false
D/ConnectivityManager.CallbackHandler( 3692): CM callback handler got msg 524292
,D/ConnectivityService( 3523): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CSLegacyTypeTracker( 3523): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
E/WifiStateMachine( 3523): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/CSLegacyTypeTracker( 3523): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 3523): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WifiStateMachine( 3523): updateConfiguredNetworkExpiration - currTime: 1453205064425
D/WifiStateMachine( 3523): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 3834): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3834): P2P: Current p2p state = IDLE
I/wpa_supplicant( 3834): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 3834): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3834): First Scan Start
I/WifiTrafficPoller( 3523): evaluateTrafficStatsPolling
,D/TelephonyNetworkFactory( 3977): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine( 3523): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine( 3523): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityManager.CallbackHandler( 4760): CM callback handler got msg 524292
I/wpa_supplicant( 3834): Scan requested (ret=0) - scan timeout 30 seconds
E/WifiStateMachine( 3523): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3523): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine( 3523): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3523): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent( 3523): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 3523): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
,E/WifiStateMachine( 3523): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine( 3523): setDetailed state send new extra info"NG700"
D/SecContentProvider2( 3523): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3523): mCursor = null
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
,D/EntConnectivity( 3523): Not allowed due to - mEnabled false
D/ConnectivityService( 3523): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/Tethering( 3523): MasterInitialState.processMessage what=3
,D/SmartBondingService( 3523): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService( 3523): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
,V/NetworkStats( 3523): updateIfacesLocked()
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
V/NetworkStats( 3523): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 3523): UpdateStatsForKnox
D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3692): updateDataNetType()
D/StatusBar.NetworkController( 3692): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3692): updateLTEICONDataNetType:0
,V/NetworkStats( 3523): performPollLocked() took 3ms
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/SmartBondingService( 3523): getNetworkEnabled : wifi : true mobile : false
,D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
V/NetworkStats( 3523): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 3692): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3692): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3692): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
I/Hs20UtilService( 4112): Starting #9
I/Hs20UtilService( 4112): Message received 5007
D/NearbySettings( 8752): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8752): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8752): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/SecContentProvider2( 3523): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3523): mCursor = null
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
I/NearbySettings( 8752): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8752): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8752): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8752): MountReceiver.mPrefHandler - 7002
I/SignOutReceiver(11363): NETWORK_STATE_CHANGED_ACTION
,D/FileWriteThread_Telephony( 3977): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3977): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3977): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3977): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3977): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3977): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3977): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3977): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3977): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3977): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3977): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3977): FileWriteThread : threadType = 3
,D/ConnectivityService( 3523): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 3523): updateDataUsageMap
I/ApplicationPolicy( 3523): updateDataUsageMap  idList is null 
,D/GpsLocationProvider( 3523): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3523): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3523): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
,W/SLocation( 3523): No Active Data Connection
,D/SmartBondingService( 3523): getNetworkEnabled : wifi : true mobile : false
,I/DBG_DM  ( 6239): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/DBG_DM  ( 6239): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11854): MountEmulatedStorage()
E/Zygote  (11854): v2
I/libpersona(11854): KNOX_SDCARD checking this for 10110
I/libpersona(11854): KNOX_SDCARD not a persona
,I/SELinux (11854): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11854): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11854): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.iorg.vpn.cleanup.NetworkStateMonitor: pid=11854 uid=10110 gids={50110, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11854): TimaSignature is unavailable
,D/ActivityThread(11854): Added TimaKeyStore provider
,D/ResourcesManager(11854): creating new AssetManager and set to /data/app/com.facebook.appmanager-2/base.apk
,D/ACRA    (11854): ACRA is enabled for com.facebook.appmanager, intializing...
,I/DexLibLoader(11854): not using cross-dex optimization: ART in use
,I/art     (11854): Thread[1,tid=11854,WaitingForJniOnLoad,Thread*=0xb4e08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/app/com.facebook.appmanager-2/lib/arm/libfbjni.so"
,V/DexLibLoader(11854): about to lock: /data/data/com.facebook.appmanager/mdex_lock
,V/DexLibLoader(11854): locking /data/data/com.facebook.appmanager/mdex_lock took 0 ms
V/DexLibLoader(11854): Secondary program dex metadata: classes2.dex 29f80981f469a774a4884b3db2df17e0be227159 secondary.dex01.Canary
,D/DexLibLoader(11854): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex" is valid
D/DexLibLoader(11854): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex_opt" is valid
,W/art     (11854): Attempt to remove local handle scope entry from IRT, ignoring
,D/DexLibLoader(11854): loading pre-built fallback odex files
V/MultiDexClassLoader(11854): installing MultiDexClassLoader before application classloader
,D/DexLibLoader(11854): released odex store lock
D/DexLibLoader(11854): DexLibLoader.loadAll took 16 ms
,W/ca      (11854): Verify
,W/LightSharedPreferencesImpl(11854): Failed to load preference file from Disk!
W/LightSharedPreferencesImpl(11854): java.io.FileNotFoundException: /data/data/com.facebook.appmanager/app_light_prefs/com.facebook.appmanager/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11854): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/LightSharedPreferencesImpl(11854): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/LightSharedPreferencesImpl(11854): 	at com.facebook.crudolib.b.k.a(LightSharedPreferencesStorage.java:56)
W/LightSharedPreferencesImpl(11854): 	at com.facebook.crudolib.b.g.run(LightSharedPreferencesImpl.java:61)
W/LightSharedPreferencesImpl(11854): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/LightSharedPreferencesImpl(11854): 	at com.facebook.common.executors.dj.run(WrappingExecutorService.java:77)
W/LightSharedPreferencesImpl(11854): 	at com.facebook.common.executors.u.run(DefaultConstrainedListeningExecutorService.java:327)
W/LightSharedPreferencesImpl(11854): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/LightSharedPreferencesImpl(11854): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/LightSharedPreferencesImpl(11854): 	at com.facebook.common.executors.cc.run(NamedThreadFactory.java:42)
W/LightSharedPreferencesImpl(11854): 	at java.lang.Thread.run(Thread.java:818)
W/LightSharedPreferencesImpl(11854): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11854): 	at libcore.io.Posix.open(Native Method)
W/LightSharedPreferencesImpl(11854): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/LightSharedPreferencesImpl(11854): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/LightSharedPreferencesImpl(11854): 	... 10 more
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11879): MountEmulatedStorage()
I/libpersona(11879): KNOX_SDCARD checking this for 1000
E/Zygote  (11879): v2
I/libpersona(11879): KNOX_SDCARD not a persona
,I/SELinux (11879): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11879): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11879): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=11879 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 3523): Killing 9805:com.sec.android.app.shealth/u0a36 (adj 15): bgCount ##31
,W/appmanager(:<default>):b(11854): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,E/lowmemorykiller( 2828): Error writing /proc/9805/oom_score_adj; errno=22
,W/appmanager(:<default>):b(11854): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/TimaKeyStoreProvider(11879): TimaSignature is unavailable
,D/ActivityThread(11879): Added TimaKeyStore provider
,D/ResourcesManager(11879): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,W/appmanager(:<default>):QuickExperimentControllerImpl(11854): Exposure of experiment com.facebook.common.network.l@272858f4 occurred when no user was logged in
I/PCWCLIENTTRACE_LOG(11879): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(11879): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(11879): new DMDBOpenHelper instance
,W/BroadcastQueue( 3523): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{df10cc1 u0 ReceiverList{28bfd9a8 11854 com.facebook.appmanager/10110/u0 remote:275dbdcb}}
,W/BroadcastQueue( 3523): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{df10cc1 u0 ReceiverList{28bfd9a8 11854 com.facebook.appmanager/10110/u0 remote:275dbdcb}}
,I/PCWCLIENTTRACE_PushUtil(11879): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11879): sales region : global
I/PCWCLIENTTRACE_PushUtil(11879): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11879): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver(11879): noConnectivity : true
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11906): MountEmulatedStorage()
E/Zygote  (11906): v2
I/libpersona(11906): KNOX_SDCARD checking this for 10135
I/libpersona(11906): KNOX_SDCARD not a persona
,I/SELinux (11906): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11906): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11906): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=11906 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 10959:com.sec.android.app.samsungapps/u0a13 (adj 15): bgCount ##31
,W/BroadcastQueue( 3523): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{c41a44a u0 ReceiverList{19a765b5 11854 com.facebook.appmanager/10110/u0 remote:bacedec}}
,D/TimaKeyStoreProvider(11906): TimaSignature is unavailable
,D/ActivityThread(11906): Added TimaKeyStore provider
,D/ResourcesManager(11906): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/MusicStore(11906): Database version: 104
,D/ResourcesManager(11906): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11906): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11906): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (11906): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11854): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11854): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,W/ActivityThread(11906): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  (11906): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@f56d0cd: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller(11906): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(11906): GMSCore installation verified
,I/ConfigStore(11906): Config Database version: 1
,W/appmanager(:<default>):QuickExperimentControllerImpl(11854): Exposure of experiment com.facebook.imagepipeline.a.g@89b4b9d occurred when no user was logged in
,W/appmanager(:<default>):QuickExperimentControllerImpl(11854): Exposure of experiment com.facebook.imagepipeline.a.d@34acc35e occurred when no user was logged in
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11906): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,I/art     (11854): Explicit concurrent mark sweep GC freed 45565(2MB) AllocSpace objects, 6(96KB) LOS objects, 22% free, 27MB/35MB, paused 839us total 22.960ms
,W/appmanager(:<default>):m(11854): No feature status reporters found; is this dead code?
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11906): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11906): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter( 3523): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3523): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3523): getStreamVolume 3 index 0
,I/MediaRouter(11906): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11940): MountEmulatedStorage()
E/Zygote  (11940): v2
I/libpersona(11940): KNOX_SDCARD checking this for 10002
I/libpersona(11940): KNOX_SDCARD not a persona
,I/SELinux (11940): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11940): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11940): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=11940 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/wpa_supplicant( 3834): nl80211: Received scan results (6 BSSes)
,I/wpa_supplicant( 3834): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 3834): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3834): wlan0: State: SCANNING -> ASSOCIATING
E/WifiStateMachine( 3523): [1,453,205,065,513 ms] noteScanEnd no scan source
I/wpa_supplicant( 3834): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,D/WifiDisplayAdapter( 3523): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/NetworkMonitor(11906): type=WIFI subType= reason=null isConnected=false
,E/WifiStateMachine( 3523): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@3f4d4764 sup_state=SCANNING debouncing=false
E/WifiStateMachine( 3523): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3523): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3523): setDetailed state send new extra info
D/SecContentProvider2( 3523): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3523): mCursor = null
D/TimaKeyStoreProvider(11940): TimaSignature is unavailable
,D/ActivityThread(11940): Added TimaKeyStore provider
,I/ActivityManager( 3523): Killing 10974:com.policydm/1000 (adj 15): bgCount ##31
,D/ResourcesManager(11940): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager( 3523): Killing 10989:com.sec.android.provider.badge/u0a82 (adj 13): bgCount ##31
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11958): MountEmulatedStorage()
I/libpersona(11958): KNOX_SDCARD checking this for 1000
E/Zygote  (11958): v2
I/libpersona(11958): KNOX_SDCARD not a persona
I/SELinux (11958): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11958): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/wpa_supplicant( 3834): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 3834): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,E/SELinux (11958): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/wpa_supplicant( 3834): Associated with C0.AA.48
,E/WifiStateMachine( 3523): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
,I/ActivityManager( 3523): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=11958 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/WifiStateMachine( 3523): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3523): setDetailed state send new extra info"NG700"
,D/SecContentProvider2( 3523): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3523): mCursor = null
,D/TimaKeyStoreProvider(11958): TimaSignature is unavailable
,D/ActivityThread(11958): Added TimaKeyStore provider
,I/wpa_supplicant( 3834): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 3834): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3523): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3523): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,D/SecContentProvider2( 3523): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3523): mCursor = null
,I/art     ( 3523): Explicit concurrent mark sweep GC freed 62667(3MB) AllocSpace objects, 15(263KB) LOS objects, 24% free, 49MB/65MB, paused 1.740ms total 87.691ms
,I/wpa_supplicant( 3834): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 3834): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,I/wpa_supplicant( 3834): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,D/ResourcesManager(11958): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,E/WifiStateMachine( 3523): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3523): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
I/wpa_supplicant( 3834): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3834): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 3834): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 3834): Blacklist: Clear (temp) 
I/wpa_supplicant( 3834): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3523): Network connection established
D/WifiNative-HAL( 3523): callSECApiVoid - ID [50]
,E/WifiStateMachine( 3523): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
E/WifiStateMachine( 3523): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService( 3523): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine( 3523): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3523): L2ConnectedState "NG700" nid=0
E/WifiConfigStore( 3523): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 3523): hsengiv:checkWhatTypeOfNetwork and the value is false
,E/ConnectivityService( 3523): updateNetworkInfo()
D/ConnectivityService( 3523): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,E/WifiStateMachine( 3523): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine( 3523): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3523): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3523): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
,D/CommandListener( 2845): Setting iface cfg
,E/WifiStateMachine( 3523): Start Dhcp Watchdog 2
D/SecContentProvider2( 3523): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3523): mCursor = null
,I/DIAGMON_AGENT(11958): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,E/WifiStateMachine( 3523): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3523): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/DIAGMON_AGENT(11958): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT(11958): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT(11958): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(11958): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/WifiStateMachine( 3523): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3523): do suspend false
,D/SecContentProvider2( 3523): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3523): mCursor = null
D/WifiP2pService( 3523): InactiveState{ what=143375 }
D/WifiP2pService( 3523): P2pEnabledState{ what=143375 }
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11977): MountEmulatedStorage()
E/Zygote  (11977): v2
I/libpersona(11977): KNOX_SDCARD checking this for 10012
I/libpersona(11977): KNOX_SDCARD not a persona
,I/SELinux (11977): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11977): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3523): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=11977 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (11977): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11977): TimaSignature is unavailable
,D/ActivityThread(11977): Added TimaKeyStore provider
,D/ResourcesManager(11977): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager( 3523): Killing 11010:com.sec.spp.push/u0a39 (adj 15): bgCount ##31
,I/FOTA_Client(11977): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(11977): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(11977): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11993): MountEmulatedStorage()
E/Zygote  (11993): v2
I/libpersona(11993): KNOX_SDCARD checking this for 10021
I/libpersona(11993): KNOX_SDCARD not a persona
,I/SELinux (11993): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11993): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11993): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=11993 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
I/ActivityManager( 3523): Killing 11044:com.wsomacp/u0a28 (adj 15): bgCount ##31
,E/lowmemorykiller( 2828): Error writing /proc/11044/oom_score_adj; errno=22
,I/art     ( 2884): Explicit concurrent mark sweep GC freed 8726(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 297us total 10.252ms
,D/TimaKeyStoreProvider(11993): TimaSignature is unavailable
,D/ActivityThread(11993): Added TimaKeyStore provider
I/art     ( 2884): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 578us total 8.771ms
,D/ResourcesManager(11993): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/art     ( 2884): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 671us total 8.930ms
,I/KLMS-2.4.521: (11993): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Jan 19 13:04:25 GMT+01:00 2016
,I/KLMS-2.4.521: (11993): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (11993): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11993): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (11993): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (11993): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (11993): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (11993): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.521: (11993): StateImplV2(): networkChangeListener().END
,E/Zygote  (12010): MountEmulatedStorage()
I/libpersona(12010): KNOX_SDCARD checking this for 10038
E/Zygote  (12010): v2
I/libpersona(12010): KNOX_SDCARD not a persona
I/SELinux (12010): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12010): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12010): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=12010 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/KLMS-2.4.521: (11993): KLMSIntentService(): onDestroy()
,I/ActivityManager( 3523): Killing 10823:com.google.android.apps.docs/u0a101 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12010): TimaSignature is unavailable
,D/ActivityThread(12010): Added TimaKeyStore provider
,E/lowmemorykiller( 2828): Error writing /proc/10823/oom_score_adj; errno=22
,D/ResourcesManager(12010): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,E/dhcpcd  (12025): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (12025): version 5.5.6 starting
,E/dhcpcd  (12025): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/SO_AGENT(12010): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12030): MountEmulatedStorage()
I/libpersona(12030): KNOX_SDCARD checking this for 1000
E/Zygote  (12030): v2
I/libpersona(12030): KNOX_SDCARD not a persona
,I/SELinux (12030): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3523): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=12030 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux (12030): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12030): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Killing 11020:com.sec.android.app.soundalive/u0a59 (adj 15): bgCount ##31
,I/dhcpcd  (12025): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (12025): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (12025): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  (12025): bssid match
I/dhcpcd  (12025): wlan0: rebinding lease of 192.168.1.124
,D/TimaKeyStoreProvider(12030): TimaSignature is unavailable
,D/ActivityThread(12030): Added TimaKeyStore provider
,D/ResourcesManager(12030): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12052): MountEmulatedStorage()
E/Zygote  (12052): v2
I/libpersona(12052): KNOX_SDCARD checking this for 10039
I/libpersona(12052): KNOX_SDCARD not a persona
I/SELinux (12052): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12052): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12052): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=12052 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 11102:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12052): TimaSignature is unavailable
,D/ActivityThread(12052): Added TimaKeyStore provider
,D/ResourcesManager(12052): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService(12052): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(12052): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService(12052): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,D/SPPClientService(12052): PushLog.txt file is not deleted.
D/SPPClientService(12052): PushLog.txt file is not deleted.
D/SPPClientService(12052): ============PushLog. stop!
,I/SA      (11152): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11152): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      (11152): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      (11152): [SLFUCHKMGR] constructor called
,E/SPPClientService(12052): [[SystemStateMonitorService]] No Active Internet
,I/SA      (11152): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11152): [OR] == isSIMCardReady false ==
,I/SA      (11152): [SCU] == networkStateCheck == false
I/SA      (11152): [OR] onReceive END
,I/ActivityManager( 3523): Killing 11084:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
,V/DownloadManager( 3716): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
E/lowmemorykiller( 2828): Error writing /proc/11084/oom_score_adj; errno=22
,E/lowmemorykiller( 2828): Error writing /proc/11084/oom_score_adj; errno=22
E/lowmemorykiller( 2828): Error writing /proc/11084/oom_score_adj; errno=22
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12072): MountEmulatedStorage()
I/libpersona(12072): KNOX_SDCARD checking this for 10067
E/Zygote  (12072): v2
I/libpersona(12072): KNOX_SDCARD not a persona
,I/SELinux (12072): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12072): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3523): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=12072 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux (12072): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12072): TimaSignature is unavailable
,D/ActivityThread(12072): Added TimaKeyStore provider
,D/ResourcesManager(12072): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/sCloudBackupApp(12072): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(12072): Other Intent
,I/ActivityManager( 3523): Killing 11129:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
,D/accuweather( 5106): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3775): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,D/accuweather( 5106): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5106): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5106): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5106): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5106): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5106): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12088): MountEmulatedStorage()
I/libpersona(12088): KNOX_SDCARD checking this for 1000
E/Zygote  (12088): v2
I/libpersona(12088): KNOX_SDCARD not a persona
,I/SELinux (12088): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12088): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12088): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=12088 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12088): TimaSignature is unavailable
,D/ActivityThread(12088): Added TimaKeyStore provider
,D/ResourcesManager(12088): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(12088): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro(12088): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro(12088): premStatus:2
,I/KnoxUsageLogPro(12088): isEulaShown : false
I/KnoxUsageLogPro(12088): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12103): MountEmulatedStorage()
E/Zygote  (12103): v2
I/libpersona(12103): KNOX_SDCARD checking this for 10090
I/libpersona(12103): KNOX_SDCARD not a persona
,I/SELinux (12103): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12103): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12103): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=12103 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3523): Killing 11063:com.sec.android.automotive.drivelink/u0a102 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12103): TimaSignature is unavailable
,D/ActivityThread(12103): Added TimaKeyStore provider
,D/ResourcesManager(12103): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12119): MountEmulatedStorage()
E/Zygote  (12119): v2
I/libpersona(12119): KNOX_SDCARD checking this for 10127
I/libpersona(12119): KNOX_SDCARD not a persona
,I/SELinux (12119): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12119): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12119): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=12119 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3523): Killing 11219:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12119): TimaSignature is unavailable
,D/ActivityThread(12119): Added TimaKeyStore provider
,D/ResourcesManager(12119): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,D/KeyguardWallpaperUpdator(12119): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12119): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12119): stopCheckCategoryVersion
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12135): MountEmulatedStorage()
E/Zygote  (12135): v2
I/libpersona(12135): KNOX_SDCARD checking this for 10136
I/libpersona(12135): KNOX_SDCARD not a persona
,I/SELinux (12135): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12135): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12135): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=12135 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 11238:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12135): TimaSignature is unavailable
,D/ActivityThread(12135): Added TimaKeyStore provider
,D/ResourcesManager(12135): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/dhcpcd  (12025): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
,I/dhcpcd  (12025): wlan0: leased 192.168.1.124 for 86400 seconds
,E/WifiStateMachine( 3523): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3523): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12135): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12135): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12135): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12135): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory(12135): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(12135): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(12135): Loading: webviewchromium
,I/LibraryLoader(12135): Time to load native libraries: 2 ms (timestamps 9109-9111)
I/LibraryLoader(12135): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(12135): Binding Chromium to main looper Looper (main, tid 1) {278cacc9}
,I/LibraryLoader(12135): Expected native library version number "",actual native library version number ""
,I/chromium(12135): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(12135): Initializing chromium process, renderers=0
,W/art     (12135): Attempt to remove local handle scope entry from IRT, ignoring
,W/AudioManagerAndroid(12135): Requires BLUETOOTH permission
,W/chromium(12135): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(12135): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium(12135): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,I/NSApplication(12135): Starting up...
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12224): MountEmulatedStorage()
E/Zygote  (12224): v2
I/libpersona(12224): KNOX_SDCARD checking this for 10150
I/libpersona(12224): KNOX_SDCARD not a persona
,I/SELinux (12224): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12224): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12224): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=12224 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager( 3523): Killing 11204:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12224): TimaSignature is unavailable
,D/ActivityThread(12224): Added TimaKeyStore provider
,D/ResourcesManager(12224): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(12224): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12224): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12224): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect(12224): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12224): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect(12224): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12239): MountEmulatedStorage()
I/libpersona(12239): KNOX_SDCARD checking this for 10178
E/Zygote  (12239): v2
I/libpersona(12239): KNOX_SDCARD not a persona
I/SELinux (12239): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12239): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12239): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=12239 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 11257:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12239): TimaSignature is unavailable
,D/ActivityThread(12239): Added TimaKeyStore provider
,E/WifiStateMachine( 3523): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine( 3523): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  ( 3523): do suspend true
,D/WifiP2pService( 3523): InactiveState{ what=143375 }
,D/ResourcesManager(12239): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/WifiP2pService( 3523): P2pEnabledState{ what=143375 }
,W/ResourcesManager(12239): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager(12239): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12239): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12239): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12239): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12239): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/WifiStateMachine( 3523): WifiStateMachine DHCP successful
,E/WifiStateMachine( 3523): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3523): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine( 3523): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3523): Not connected state, yet.
E/WifiStateMachine( 3523): VerifyingLinkState enter
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiStateMachine( 3523): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine( 3523): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3523): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3523): callSECApiInt - ID [210]
,E/WifiStateMachine( 3523): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
E/ConnectivityService( 3523): updateNetworkInfo()
,D/ConnectivityService( 3523): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 3523): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 3523): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 3523): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.DnsResolver( 3523): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 3523): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3523): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
,D/ConnectivityService( 3523): Adding Route [fe80::/64 -> :: wlan0] to network 503
,E/WifiStateMachine( 3523): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/ConnectivityService( 3523): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
D/WifiStateMachine( 3523): Now, connected state.
E/WifiStateMachine( 3523): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/WifiStateMachine( 3523): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService( 3523): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
I/WifiTrafficPoller( 3523): evaluateTrafficStatsPolling
E/ConnectivityService( 3523): Unexpected mtu value: 0, wlan0
,V/        ( 2845): QcRouteController
,E/WifiStateMachine( 3523): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller( 3523): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3523): ConnectedState Enter  mScreenOn=false scanperiod=20000
V/        ( 2845): QcRouteController
D/WifiNative-HAL( 3523): callSECApiVoid - ID [212]
,I/WifiStateMachine( 3523): REQUEST_POWER_SAVE_ON
,V/        ( 2845): QcRouteController
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/RCPManagerService( 3523): exchangeData() failure , invalid userId
,V/        ( 2845): QcRouteController
,D/RCPManagerService( 3523): exchangeData() failure , invalid userId
,D/RCPManagerService( 3523): exchangeData() failure , invalid userId
,V/        ( 2845): QcRouteController
,V/        ( 2845): QcRouteController
,V/        ( 2845): QcRouteController
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
D/RCPManagerService( 3523): exchangeData() failure , invalid userId
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,V/        ( 2845): QcRouteController
,D/RCPManagerService( 3523): exchangeData() failure , invalid userId
,E/Zygote  (12279): MountEmulatedStorage()
E/Zygote  (12279): v2
I/libpersona(12279): KNOX_SDCARD checking this for 10082
I/libpersona(12279): KNOX_SDCARD not a persona
,I/ActivityManager( 3523): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=12279 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,I/SELinux (12279): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/RCPManagerService( 3523): exchangeData() failure , invalid userId
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/SELinux (12279): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12279): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ConnectivityService( 3523): Setting Dns servers for network 503 to [/192.168.1.1]
,D/ConnectivityService( 3523): LTETest block dns file not exists
,I/art     ( 2884): Explicit concurrent mark sweep GC freed 8751(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 670us total 18.144ms
,I/art     ( 2884): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 374us total 8.592ms
,D/TimaKeyStoreProvider(12279): TimaSignature is unavailable
D/ActivityThread(12279): Added TimaKeyStore provider
,I/art     ( 2884): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 251us total 7.496ms
,E/Zygote  (12295): MountEmulatedStorage()
E/Zygote  (12295): v2
I/libpersona(12295): KNOX_SDCARD checking this for 1000
I/libpersona(12295): KNOX_SDCARD not a persona
,I/SELinux (12295): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12295): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12295): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=12295 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 11272:com.samsung.helphub/1000 (adj 13): bgCount ##31
,I/ActivityManager( 3523): Killing 11383:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##31
,D/ConnectivityService( 3523): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,E/ConnectivityService( 3523): updateNetworkInfo()
E/ConnectivityService( 3523): updateNetworkInfo()
,D/ConnectivityService( 3523): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 3523): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3523): rematching NetworkAgentInfo [WIFI () - 503]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService( 3523):    accepting network in place of null
,D/TelephonyNetworkFactory( 3977): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TimaKeyStoreProvider(12295): TimaSignature is unavailable
,D/ActivityThread(12295): Added TimaKeyStore provider
E/CSLegacyTypeTracker( 3523): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 3523): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 3523): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ResourcesManager(12279): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,I/System.out( 3523): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 1000
,D/Tethering( 3523): MasterInitialState.processMessage what=3
D/ConnectivityService( 3523): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/SmartBondingService( 3523): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService( 3523): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
,D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
V/NetworkStats( 3523): updateIfacesLocked()
D/EntConnectivity( 3523): Not allowed due to - mEnabled false
V/NetworkStats( 3523): performPollLocked(flags=0x1)
D/ConnectivityService( 3523): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/NetworkStatsFactory( 3523): UpdateStatsForKnox
,D/ConnectivityManager.CallbackHandler( 3692): CM callback handler got msg 524290
,D/SmartBondingService( 3523): getNetworkEnabled : wifi : true mobile : false
D/ConnectivityManager.CallbackHandler( 4760): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3692): updateDataNetType()
D/StatusBar.NetworkController( 3692): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3692): updateLTEICONDataNetType:0
,D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
V/NetworkStats( 3523): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/BadgeProvider(12279): onCreate
,D/BadgeProvider(12279): DatabaseHelper
,V/NetworkStats( 3523): performPollLocked() took 11ms
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
,E/WifiStateMachine( 3523): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3523): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService( 3523): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ResourcesManager(12295): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
V/        ( 2845): QcRouteController
,D/StatusBar.NetworkController( 3692): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3692): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3692): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/SmartBondingService( 3523): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
D/SmartBondingService( 3523): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/BadgeProvider(12279): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
V/        ( 2845): QcRouteController
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
W/NetworkManagementService( 3523): route cmd failed: 
W/NetworkManagementService( 3523): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '75 route replace src v6 wlan0 fe80::92b6:86ff:fe43:731c 2 ::' failed with '400 75 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
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
I/ActivityManager( 3523): Killing 11401:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
D/ConnectivityManager.CallbackHandler( 3692): CM callback handler got msg 524295
D/ConnectivityService( 3523): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 4760): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 3692): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 4760): CM callback handler got msg 524295
D/BadgeProvider(12279): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12279): sendNotify, [notify] : null
D/BadgeProvider(12279): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12279): update, [BadgeCount] : badgecount=0
D/BadgeProvider(12279): update, [UpdateCount] : 1
,D/Launcher.Model( 4002): reloadBadges entered.
W/ActivityManager( 3523): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/Zygote  (12317): MountEmulatedStorage()
E/Zygote  (12317): v2
I/libpersona(12317): KNOX_SDCARD checking this for 10013
I/libpersona(12317): KNOX_SDCARD not a persona
I/SELinux (12317): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3523): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=12317 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/SELinux (12317): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12317): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/System.out( 3523): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/TimaKeyStoreProvider(12317): TimaSignature is unavailable
,D/ActivityThread(12317): Added TimaKeyStore provider
,D/ResourcesManager(12317): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 19 Jan 2016 12:04:27 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453205067089], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453205067057]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): Validated
,D/ConnectivityService( 3523): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3523): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3523): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 3523): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3523): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 3692): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 4760): CM callback handler got msg 524290
,D/WaitQueueForNetworkActivate(12317): notifyNetworkActivated
D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3692): updateDataNetType()
D/StatusBar.NetworkController( 3692): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3692): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3692): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3692): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3692): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,W/ContextImpl(12317): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3523): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/jxcore-log(11750): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log(11750): 
,D/hcjo    (12317): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12317): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12317): exit::IDLE
D/InitializeManagerStateMachine(12317): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12317): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12317): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12317): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12317): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12317): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12317): entry::SUCCESS
D/hcjo    (12317): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (12317): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12317): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine(12317): exit::SUCCESS
D/InitializeManagerStateMachine(12317): entry::IDLE
,I/Hs20UtilService( 4112): Starting #10
,I/Hs20UtilService( 4112): Message received 5007
,D/NearbySettings( 8752): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8752): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8752): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 8752): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8752): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8752): MountReceiver.onReceive - Keep current state
,I/ActivityManager( 3523): Killing 11419:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##31
,I/SignOutReceiver(11363): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4112): Starting #11
,I/Hs20UtilService( 4112): Message received 5007
,D/NearbySettings( 8752): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8752): MountReceiver.onReceive - Keep current state
,I/SignOutReceiver(11363): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4112): Starting #12
,I/Hs20UtilService( 4112): Message received 5007
,D/NearbySettings( 8752): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8752): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8752): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 8752): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8752): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8752): MountReceiver.onReceive - Keep current state
,I/SignOutReceiver(11363): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4112): Starting #13
,I/Hs20UtilService( 4112): Message received 5007
,D/NearbySettings( 8752): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8752): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine( 3523): callSECApi what=220
D/WifiStateMachine( 3523): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/SignOutReceiver(11363): NETWORK_STATE_CHANGED_ACTION
,I/SurfaceFlinger( 2849): id=15 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 3523): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3523
,D/mali_winsys( 3692): new_window_surface returns 0x3000,  [1120x201]-format:1
,D/ConnectivityService( 3523): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3523): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3523): SmartBondingReceiver: wifi is connected
D/SmartBondingService( 3523): SmartBondingReceiver: wifi ap is not changed
,D/SmartBondingService( 3523): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
,D/SmartBondingService( 3523): getNetworkEnabled : wifi : true mobile : false
,D/GpsLocationProvider( 3523): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 6239): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 6239): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/NetworkMonitor(11906): type=WIFI subType= reason=null isConnected=true
,W/ResourceType( 5364): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5364): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,I/PCWCLIENTTRACE_PushUtil(11879): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11879): sales region : global
I/PCWCLIENTTRACE_PushUtil(11879): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11879): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/SecContentProvider2( 3523): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3523): mCursor = null
,I/DIAGMON_AGENT(11958): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(11958): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/FOTA_Client(11977): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(11977): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(11977): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.521: (11993): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Jan 19 13:04:27 GMT+01:00 2016
,I/KLMS-2.4.521: (11993): KLMSAbstractReciever(): onReceive().END.
,I/jxcore-log(11750): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log(11750): 
,I/KLMS-2.4.521: (11993): KLMSIntentService(): onCreate()
,I/jxcore-log(11750): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log(11750): 
,I/KLMS-2.4.521: (11993): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (11993): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/SO_AGENT(12010): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,I/KLMS-2.4.521: (11993): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (11993): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (11993): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.521: (11993): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.521: (11993): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.521: (11993): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.4.521: (11993): StateImplV2(): networkChangeListener().END
,E/SPPClientService(12052): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/KLMS-2.4.521: (11993): KLMSIntentService(): onDestroy()
,I/SA      (11152): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11152): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (11152): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (11152): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11152): [OR] == isSIMCardReady false ==
,I/SA      (11152): [SCU] == networkStateCheck == true
I/SA      (11152): [DM] getCountryCodeFromCSC : PL
I/SA      (11152): isChinaCountryCode : false
I/SA      (11152): [SCU] is ChinestModel Data Restricted   : false
I/SA      (11152): [OR] == networkStateCheck true ==
I/SA      (11152): [OR] GetMyCountryZoneTask
,I/SA      (11152): [OR] onReceive END
I/SA      (11152): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 3716): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      (11152): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (11152): [SSP] query invoked
I/jxcore-log(11750): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log(11750): 
,I/SCloudBackupReceiver(12072): Other Intent
,I/SA      (11152): [TPMU] GetMccFromDB : null
I/SA      (11152): [SCU] getMccFromPreferece mcc = 260
I/SA      (11152): [TPM] isNoProxy(default) : true
,D/accuweather( 5106): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3775): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,I/jxcore-log(11750): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log(11750): 
D/accuweather( 5106): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5106): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
,D/accuweather( 5106): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5106): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,I/jxcore-log(11750): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log(11750): 
,I/jxcore-log(11750): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log(11750): 
,D/accuweather( 5106): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5106): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro(12088): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro(12088): premStatus:2
,I/KnoxUsageLogPro(12088): isEulaShown : false
I/KnoxUsageLogPro(12088): KnoxUsageReceiver onReceive : not Processible, just return
,D/KeyguardWallpaperUpdator(12119): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12119): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12119): stopCheckCategoryVersion
,D/QuickConnect(12224): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12224): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect(12224): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 3523): exchangeData() failure , invalid userId
,D/RCPManagerService( 3523): exchangeData() failure , invalid userId
,D/hcjo    (12317): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12317): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12317): exit::IDLE
D/InitializeManagerStateMachine(12317): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12317): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12317): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12317): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12317): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12317): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12317): entry::SUCCESS
D/hcjo    (12317): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (12317): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12317): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine(12317): exit::SUCCESS
D/InitializeManagerStateMachine(12317): entry::IDLE
,I/SA      (11152): [RC New] Execute method=[GET] start
I/SA      (11152): [RC New] Security=[true]
I/System.out(11152): Thread-1535(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out(11152): Thread-1535(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11152): Thread-1535(ApacheHTTPLog):isShipBuild true
I/System.out(11152): Thread-1535(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 10045
D/ConnectivityService( 3523): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
I/SA      (11152): [RC New] [v2liruge] api execute + 599
I/SA      (11152): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out(11152): AsyncTask #1 calls detatch()
I/SA      (11152): [TPMU] getNetworkMcc : 
I/SA      (11152): [SCU] saveMccToPreferece Start
I/SA      (11152): [SCU] RegionMCC : 260
I/SA      (11152): [SSP] query invoked
I/SA      (11152): [TPMU] GetMccFromDB : null
I/SA      (11152): [SCU] getMccFromPreferece mcc = 260
I/SA      (11152): [SCU] saveMccToPreferece End
I/SA      (11152): [RC New] executeRequest [v2liruge] end. 619
I/SA      (11152): [RC New] Execute end
I/SA      (11152): [OR] GetMyCountryZoneTask mcc = 260
I/SA      (11152): [OR] GetMyCountryZoneTask Success
,I/jxcore-log(11750): Test app app.js loaded
I/jxcore-log(11750): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setDiscoveryMode: Mode set to BLE
,I/jxcore-log(11750): BLE advertisement is supported
I/jxcore-log(11750): 
,I/chromium(11750): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/dhcpcd  (12025): wlan0: sending IPv6 Router Solicitation,
,I/WifiStateMachine( 3523): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine( 3523): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,D/WearableService( 4626): callingUid 10014, callindPid: 4626
,D/ResourcesManager(11906): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11906): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11906): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory(11906): Using the GMSCore's GoogleHttpClient
,I/MusicLeanback(11906): Conditions not met for autocaching.
I/MusicLeanback(11906): Stop autocaching.
,D/WearableClient(11906): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11906): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11906): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11906): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(11906): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils(11906): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/ActivityThread(11906): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@d5792af that was originally bound here
E/ActivityThread(11906): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@d5792af that was originally bound here
E/ActivityThread(11906): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(11906): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(11906): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(11906): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(11906): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(11906): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(11906): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11906): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11906): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11906): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(11906): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(11906): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(11906): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(11906): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(11906): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(11906): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(11906): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(11906): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(11906): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(11906): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(11906): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(11906): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(11906): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(11906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(11906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/SurfaceFlinger( 2849): id=15 Removed Uoast (8/9)
,I/SurfaceFlinger( 2849): id=15 Removed Uoast (-2/9)
,D/PowerManagerService( 3523): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3523) eventTime = 143252
,D/PowerManagerService( 3523): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3523 (0x0)
D/PowerManagerService( 3523): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3523, ws=WorkSource{10060}) (elapsedTime=3488)
,I/art     ( 3523): Explicit concurrent mark sweep GC freed 56691(3MB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 49MB/65MB, paused 2.170ms total 150.128ms
,D/SSRM:n  ( 3523): SIOP:: AP = 300, PST = 273, CUR = 65
,I/GAV4    (12135): Thread[GAThread,5,main]: No campaign data found.
,I/PowerManagerService( 3523): [PWL] Off : 50s ago
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:-153, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:122
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5650): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5650): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/PackageManager( 3523): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/PCWCLIENTTRACE_SYSTEMReceiver(11879): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil(11879): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE(11879): ================================================
,I/CSTORAGE(11879):  CSTORAGE_SKM_LIB v1.0.15
I/CSTORAGE(11879): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI(11879): [GetString-S]
,E/art     (11879): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI(11879): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,I/PCWCLIENTTRACE_SecurePreferencesJNI(11879): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil(11879): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil(11879): sales region : global
I/PCWCLIENTTRACE_PushUtil(11879): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler(11879): [ensureRegistration] - No Samsung account
,I/dhcpcd  (12025): wlan0: sending IPv6 Router Solicitation
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ProcessCpuTracker( 3523): Skipping unknown process pid 12439
,D/PreloadUpdateManagerStateMachine(12317): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(12317): exit::IDLE
,D/PreloadUpdateManagerStateMachine(12317): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (12317): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    (12317): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/PreloadUpdateManagerStateMachine(12317): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine(12317): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine(12317): entry::IDLE
,D/PreloadUpdateManagerStateMachine(12317): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(12317): exit::IDLE
,D/PreloadUpdateManagerStateMachine(12317): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (12317): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine(12317): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine(12317): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine(12317): entry::IDLE
,I/dhcpcd  (12025): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  (12025): wlan0: no IPv6 Routers available
,D/SSRM:n  ( 3523): SIOP:: AP = 270, PST = 273, CUR = -153
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:-2, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:93
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5650): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5650): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3523): !@Sync 5
,D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 268, CUR = -2,
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:47, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:82
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5650): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5650): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 3523): [PWL] Off : 75s ago
,V/AlarmManager( 3523): waitForAlarm result :8
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 266, CUR = 47,
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:60, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:66
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 5650): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5650): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ClearcutLoggerApiImpl( 4626): disconnect managed GoogleApiClient
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 265, CUR = 60
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:62, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:56
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,V/HeadsetService( 5650): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5650): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3523): !@Sync 6
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 265, CUR = 62
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:60, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:56
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5650): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5650): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3523): [PWL] Off : 105s ago
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 262, CUR = 60
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:57, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:49
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5650): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5650): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 261, CUR = 57
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:54, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:43
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5650): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5650): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3523): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3692): handleTimeUpdate
,D/KeyguardEffectViewController( 3692): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3692): *** don't update sliding image ***
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/Watchdog( 3523): !@Sync 7
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 260, CUR = 54
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:50, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:59
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5650): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5650): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 3523): waitForAlarm result :8
,I/PowerManagerService( 3523): [PWL] Off : 140s ago
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 259, CUR = 50
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:48, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:49
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5650): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5650): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 254, CUR = 48
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:47, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5650): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5650): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3523): !@Sync 8
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 253, CUR = 47
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:45, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
D/BatteryService( 3523): stay LED for fully charged
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5650): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5650): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 ,
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 251, CUR = 45
,I/jxcore-log(11750): TAP version 13
I/jxcore-log(11750): 
,I/jxcore-log(11750): # setup
I/jxcore-log(11750): 
,I/jxcore-log(11750): # multiplex can send data
I/jxcore-log(11750): 
,I/jxcore-log(11750): # teardown
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 1 String should be length:200
I/jxcore-log(11750): 
,I/jxcore-log(11750): # setup
I/jxcore-log(11750): 
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,I/jxcore-log(11750): # basic
I/jxcore-log(11750): 
D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:43, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:42
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5650): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5650): Disconnected process message: 10
,I/jxcore-log(11750): # teardown
I/jxcore-log(11750): 
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11750): ok 2 sane
I/jxcore-log(11750): 
,I/jxcore-log(11750): # setup
I/jxcore-log(11750): 
,I/jxcore-log(11750): # another
I/jxcore-log(11750): 
,I/jxcore-log(11750): # teardown
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 3 sane
I/jxcore-log(11750): 
,I/jxcore-log(11750): # setup
I/jxcore-log(11750): 
,I/jxcore-log(11750): # successfully create a new pkcs12 file and return hash value
I/jxcore-log(11750): 
,I/jxcore-log(11750): # teardown
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 4 should be equal
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 5 null
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 6 (unnamed assert)
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 7 should be equal
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 8 should not throw
I/jxcore-log(11750): 
,I/jxcore-log(11750): # setup
I/jxcore-log(11750): 
,I/jxcore-log(11750): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log(11750): 
,I/jxcore-log(11750): # teardown
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 9 (unnamed assert)
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 10 (unnamed assert)
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 11 should not throw
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 12 should be equal
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 13 should be equal
I/jxcore-log(11750): 
,I/jxcore-log(11750): # setup
I/jxcore-log(11750): 
,I/jxcore-log(11750): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log(11750): 
,I/jxcore-log(11750): # teardown
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 14 should be equal
I/jxcore-log(11750): 
,I/jxcore-log(11750): # setup
I/jxcore-log(11750): 
,I/jxcore-log(11750): # failed to get mobile documents path
I/jxcore-log(11750): 
,I/jxcore-log(11750): # teardown
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 15 should be equal
I/jxcore-log(11750): 
,I/jxcore-log(11750): # setup
I/jxcore-log(11750): 
,I/jxcore-log(11750): # #init should register the peerAvailabilityChanged event
I/jxcore-log(11750): 
,I/jxcore-log(11750): # teardown
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 16 should be equal
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 17 should be equal
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 18 should be equal
I/jxcore-log(11750): 
,I/jxcore-log(11750): # setup
I/jxcore-log(11750): 
,I/jxcore-log(11750): # #init should register the networkChanged event
I/jxcore-log(11750): 
,I/jxcore-log(11750): # teardown
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 19 should be equal
I/jxcore-log(11750): 
,I/jxcore-log(11750): # setup
I/jxcore-log(11750): 
,I/jxcore-log(11750): # #startBroadcasting should throw on null device name
I/jxcore-log(11750): 
,I/jxcore-log(11750): # teardown
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 20 should throw
I/jxcore-log(11750): 
,I/jxcore-log(11750): # setup
I/jxcore-log(11750): 
,I/jxcore-log(11750): # #startBroadcasting should throw on empty string device name
I/jxcore-log(11750): 
,I/jxcore-log(11750): # teardown
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 21 should throw
I/jxcore-log(11750): 
,I/jxcore-log(11750): # setup
I/jxcore-log(11750): 
,I/jxcore-log(11750): # #startBroadcasting should throw on non-number port
I/jxcore-log(11750): 
,I/jxcore-log(11750): # teardown
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 22 should throw
I/jxcore-log(11750): 
,I/jxcore-log(11750): # setup
I/jxcore-log(11750): 
,I/jxcore-log(11750): # #startBroadcasting should throw on NaN port
I/jxcore-log(11750): 
,I/jxcore-log(11750): # teardown
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 23 should throw
I/jxcore-log(11750): 
,I/jxcore-log(11750): # setup
I/jxcore-log(11750): 
,I/jxcore-log(11750): # #startBroadcasting should throw on negative port
I/jxcore-log(11750): 
,I/jxcore-log(11750): # teardown
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 24 should throw
I/jxcore-log(11750): 
,I/jxcore-log(11750): # setup
I/jxcore-log(11750): 
,I/jxcore-log(11750): # #startBroadcasting should throw on too large port
I/jxcore-log(11750): 
,I/jxcore-log(11750): # teardown
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 25 should throw
I/jxcore-log(11750): 
,I/jxcore-log(11750): # setup
I/jxcore-log(11750): 
,I/jxcore-log(11750): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log(11750): 
,I/jxcore-log(11750): # teardown
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 26 should be equal
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 27 should be equal
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 28 should be equal
I/jxcore-log(11750): 
,I/jxcore-log(11750): # setup
I/jxcore-log(11750): 
,I/jxcore-log(11750): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log(11750): 
,I/jxcore-log(11750): # teardown
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 29 should be equal
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 30 should be equal
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 31 should be equal,
I/jxcore-log(11750): 
,I/jxcore-log(11750): # setup
I/jxcore-log(11750): 
,I/jxcore-log(11750): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log(11750): 
,I/jxcore-log(11750): # teardown
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 32 should be equal
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 33 should be equal
I/jxcore-log(11750): 
,I/jxcore-log(11750): # setup
I/jxcore-log(11750): 
,I/jxcore-log(11750): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log(11750): 
,I/jxcore-log(11750): # teardown
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 34 should be equal
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 35 should be equal
I/jxcore-log(11750): 
,I/jxcore-log(11750): # setup
I/jxcore-log(11750): 
,I/jxcore-log(11750): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log(11750): 
,I/jxcore-log(11750): # teardown
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 36 should be equal
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 37 should be equal
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 38 should be equal
I/jxcore-log(11750): 
,I/jxcore-log(11750): # setup
I/jxcore-log(11750): 
,I/jxcore-log(11750): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log(11750): 
,I/jxcore-log(11750): # teardown,
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 39 should be equal
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 40 should be equal
I/jxcore-log(11750): 
,I/jxcore-log(11750): # setup
I/jxcore-log(11750): 
,I/jxcore-log(11750): # should call Mobile("Disconnect") without an error
I/jxcore-log(11750): 
,I/jxcore-log(11750): # teardown
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 41 should be equal
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 42 should be equal
I/jxcore-log(11750): 
,I/jxcore-log(11750): # setup
I/jxcore-log(11750): 
,I/jxcore-log(11750): # should call Mobile("Disconnect") and handle an error
I/jxcore-log(11750): 
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log(11750): # teardown
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 43 should be equal
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 44 should be equal
I/jxcore-log(11750): 
,I/jxcore-log(11750): # setup
I/jxcore-log(11750): 
,I/jxcore-log(11750): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log(11750): 
,I/jxcore-log(11750): # teardown
I/jxcore-log(11750): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setDiscoveryMode: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453205195205.11750
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): initialize: My bluetooth address is E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(11750): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453205195205.11750","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter(11750): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(11750): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
,D/BluetoothSocket(11750): bindListen(), new LocalSocket 
D/BluetoothSocket(11750): bindListen(), new LocalSocket.getInputStream() 
,D/BluetoothSocket(11750): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1e5a2ec
,D/BluetoothSocket(11750): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper(11750): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): start: OK
I/io.jxcore.node.ConnectionHelper(11750): start: Using peer discovery mode: BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453205195205.11750
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(11750): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11750): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(11750): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(11750): createAdvertiseData: From: 1453205195205.11750 b6a44ad1-d319-4b3a-815d-8b805a47fb51 E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(11750): E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(11750): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -32, -37, 16, 20, -30, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner(11750): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 5650): registerClient() - UUID=8b46b57f-582d-4839-a566-ecd7c8592d07
,D/BtGatt.GattService( 5650): onClientRegistered() - UUID=8b46b57f-582d-4839-a566-ecd7c8592d07, clientIf=6
,D/BluetoothLeAdvertiser(11750): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 5650): message : 0
,D/BtGatt.AdvertiseManager( 5650): number of adv instance running0
D/BtGatt.AdvertiseManager( 5650): size of list is =0
,D/BtGatt.AdvertiseManager( 5650): starting advertising
D/BtGatt.AdvertiseManager( 5650): isDualWavefalse
,D/BtGatt.GattService( 5650): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 5650): starting multi advertising
,D/BtGatt.GattService( 5650): onAdvertiseDataSet() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 5650): logClientsSet() - status: 0
D/BtGatt.AdvertiseManager( 5650): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService( 5650): registerClient() - UUID=aefe87bf-0523-4607-bea2-ffc85bcad77e
,D/BtGatt.GattService( 5650): onClientRegistered() - UUID=aefe87bf-0523-4607-bea2-ffc85bcad77e, clientIf=7
,D/BluetoothLeScanner(11750): onClientRegistered() - status=0 clientIf=7
,D/BtGatt.GattService( 5650): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startBlePeerDiscovery: OK
,D/BtGatt.ScanManager( 5650): handling starting scan
,D/BluetoothAdapterService( 5650): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bec4f09
,D/BtGatt.GattService( 5650): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,D/BtGatt.ScanManager( 5650): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager( 5650): allow scan with filters
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(11750): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453205195205.11750","ra":"E0:DB:10:14:E2:C0"}
D/BtGatt.ScanManager( 5650): client filter size is = 1available filters are = 13
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11750): start: {"pi":"E0:DB:10:14:E2:C0","pn":"1453205195205.11750","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11750): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"1453205195205.11750","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
D/BtGatt.ScanManager( 5650): set filter index= 3 for clientIf= 7
D/BtGatt.GattService( 5650): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 5650): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager( 5650): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 5650): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/BtGatt.ScanManager( 5650): :scan window =2000 Scan interval = 5000
,D/WifiP2pService( 3523): InactiveState{ what=139292 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=139292 }
,D/WifiP2pService( 3523): P2pEnabledState add service
,D/WifiP2pService( 3523): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setState: RUNNING_BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453205195205.11750
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startBlePeerDiscovery: Already running
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(11750): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): onIsAdvertiserStartedChanged: true
I/io.jxcore.node.ConnectionHelper(11750): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/io.jxcore.node.ConnectionHelper(11750): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11750): Local service added successfully
,D/WifiP2pService( 3523): InactiveState{ what=139265 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=139265 }
,D/WifiService( 3523): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/jxcore-log(11750): ok 45 Should be able to call startBroadcasting without error
I/jxcore-log(11750): 
,I/WifiStateMachine( 3523): callSECApi what=74
D/WifiStateMachine( 3523): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3523): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3834): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: STARTED
,D/WifiP2pService( 3523): discovery change broadcast true
,I/io.jxcore.node.ConnectionHelper(11750): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11750): shutdown
D/BluetoothSocket(11750): close() in, this: android.bluetooth.BluetoothSocket@31a0c931, channel: 6, state: LISTENING
,D/BluetoothSocket(11750): close() this: android.bluetooth.BluetoothSocket@31a0c931, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1e5a2ec, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2ba8c816mSocket: android.net.LocalSocket@1ad81597 impl:android.net.LocalSocketImpl@e5f6384 fd:FileDescriptor[118]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/BluetoothSocket(11750): Closing mSocket: android.net.LocalSocket@1ad81597 impl:android.net.LocalSocketImpl@e5f6384 fd:FileDescriptor[118]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11750): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper(11750): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): stop: Stopping peer discovery...
,D/BtGatt.AdvertiseManager( 5650): message : 1
,D/BtGatt.AdvertiseManager( 5650): stop advertise for client 6
D/BtGatt.AdvertiseManager( 5650):  dualWaveClientIf = 0client.clientIf6
,D/BtGatt.AdvertiseManager( 5650): logClientsSet() - status: -1
,D/BtGatt.GattService( 5650): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 5650): Client app is not null!
,D/BtGatt.GattService( 5650): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 5650): stopScan() - queue size =1
,D/BtGatt.ScanManager( 5650): filter size is 1
D/BtGatt.ScanManager( 5650): delete FilterIndex - 3
D/BtGatt.GattService( 5650): unregisterClient() - clientIf=7
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11750): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(11750): release: No more listeners, de-initializing...
,D/WifiP2pService( 3523): InactiveState{ what=139298 }
W/bt-smp  ( 5650): Key(LSB ~ MSB) = 30 7e 01 64 39 c4 92 6c 13 df 24 1d 72 e8 19 7f 
W/bt-smp  ( 5650): Plain text(LSB ~ MSB) = b8 63 4d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5650): Encrypted text(LSB ~ MSB) = 06 a4 b0 a6 93 c3 50 1e fb 44 9a cf e6 74 cf 08 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): release: No more listeners, de-initializing...
D/WifiP2pService( 3523): P2pEnabledState{ what=139298 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setState: NOT_STARTED
D/WifiP2pService( 3523): P2pEnabledState clear service
,I/io.jxcore.node.ConnectionHelper(11750): onDiscoveryManagerStateChanged: NOT_STARTED
,D/BtGatt.GattService( 5650): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
,D/BtGatt.ScanManager( 5650): callback done for clientIf - 7 status - 0
D/WifiP2pService( 3523): remove client information from framework
I/jxcore-log(11750): ok 46 Should be able to call stopBroadcasting without error
I/jxcore-log(11750): 
D/BtGatt.ScanManager( 5650): stop scan
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11750): Local services cleared successfully
D/BtGatt.ScanManager( 5650): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 5650): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 5650): configureRegularScanParams() - queue emtpy, scan stopped
D/WifiP2pService( 3523): InactiveState{ what=139268 }
I/wpa_supplicant( 3834): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setDiscoveryMode: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453205195515.11750,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): bind: Binding a new listener
D/WifiP2pService( 3523): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): P2P device discovery stopped successfully
D/WifiP2pService( 3523): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3523): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11750): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): initialize: My bluetooth address is E0:DB:10:14:E2:C0
,D/WifiP2pService( 3523): InactiveState{ what=147493 }
D/WifiP2pService( 3523): P2pEnabledState{ what=147493 }
D/WifiP2pService( 3523): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(11750): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453205195515.11750","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter(11750): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(11750): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
D/BluetoothSocket(11750): bindListen(), new LocalSocket 
D/BluetoothSocket(11750): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(11750): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1c614fa2
D/BluetoothSocket(11750): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): start: OK
I/io.jxcore.node.ConnectionHelper(11750): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper(11750): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11750): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453205195515.11750
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(11750): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(11750): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(11750): createAdvertiseData: From: 1453205195515.11750 b6a44ad1-d319-4b3a-815d-8b805a47fb51 E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(11750): E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(11750): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -32, -37, 16, 20, -30, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner(11750): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 5650): registerClient() - UUID=8a69e2dd-0a6c-4b4c-b957-5d4f6e064487
,D/BtGatt.GattService( 5650): onClientRegistered() - UUID=8a69e2dd-0a6c-4b4c-b957-5d4f6e064487, clientIf=6
,D/BluetoothLeAdvertiser(11750): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 5650): message : 0
,D/BtGatt.AdvertiseManager( 5650): number of adv instance running0
,D/BtGatt.AdvertiseManager( 5650): size of list is =0
,D/BtGatt.AdvertiseManager( 5650): starting advertising
,D/BtGatt.AdvertiseManager( 5650): isDualWavefalse
,D/BtGatt.GattService( 5650): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 5650): starting multi advertising
,D/BtGatt.GattService( 5650): onAdvertiseDataSet() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 5650): logClientsSet() - status: 0
D/BtGatt.AdvertiseManager( 5650): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService( 5650): registerClient() - UUID=63a33f54-f5e7-4f17-938d-cd3d9d91b392
,D/BtGatt.GattService( 5650): onClientRegistered() - UUID=63a33f54-f5e7-4f17-938d-cd3d9d91b392, clientIf=7
,D/BluetoothLeScanner(11750): onClientRegistered() - status=0 clientIf=7
,D/BtGatt.GattService( 5650): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startBlePeerDiscovery: OK
,D/BtGatt.ScanManager( 5650): handling starting scan
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(11750): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453205195515.11750","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11750): start: {"pi":"E0:DB:10:14:E2:C0","pn":"1453205195515.11750","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11750): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"1453205195515.11750","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/BtGatt.GattService( 5650): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
D/BtGatt.ScanManager( 5650): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager( 5650): allow scan with filters
D/BtGatt.ScanManager( 5650): client filter size is = 1available filters are = 13
D/BtGatt.ScanManager( 5650): set filter index= 4 for clientIf= 7
,D/BtGatt.GattService( 5650): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 5650): callback done for clientIf - 7 status - 0
,D/WifiP2pService( 3523): InactiveState{ what=139292 }
D/BtGatt.ScanManager( 5650): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 5650): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/BtGatt.ScanManager( 5650): :scan window =2000 Scan interval = 5000
,D/WifiP2pService( 3523): P2pEnabledState{ what=139292 }
,D/WifiP2pService( 3523): P2pEnabledState add service
,D/WifiP2pService( 3523): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453205195515.11750
,I/io.jxcore.node.ConnectionHelper(11750): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startBlePeerDiscovery: Already running
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startBlePeerDiscovery: OK
,D/WifiP2pService( 3523): InactiveState{ what=139265 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startWifiPeerDiscovery: Wi-Fi Direct OK
D/WifiP2pService( 3523): P2pEnabledState{ what=139265 }
I/WifiStateMachine( 3523): callSECApi what=74
D/WifiService( 3523): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 3523): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3523): callSECApiBoolean - ID [13]
I/jxcore-log(11750): ok 47 Should be able to call startBroadcasting without error
I/jxcore-log(11750): 
I/wpa_supplicant( 3834): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: OK
I/wpa_supplicant( 3834): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(11750): onStartSuccess
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): onIsAdvertiserStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): restart: Restarting...
D/WifiP2pService( 3523): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper(11750): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11750): shutdown
D/BluetoothSocket(11750): close() in, this: android.bluetooth.BluetoothSocket@3a22208f, channel: 6, state: LISTENING
D/BluetoothSocket(11750): close() this: android.bluetooth.BluetoothSocket@3a22208f, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1c614fa2, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@240d9f1cmSocket: android.net.LocalSocket@2bef7725 impl:android.net.LocalSocketImpl@36e130fa fd:FileDescriptor[118]
D/BluetoothSocket(11750): Closing mSocket: android.net.LocalSocket@2bef7725 impl:android.net.LocalSocketImpl@36e130fa fd:FileDescriptor[118]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11750): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): onServerStopped
,I/io.jxcore.node.ConnectionHelper(11750): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11750): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: STARTED
,D/BtGatt.AdvertiseManager( 5650): message : 1
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper(11750): onConnectionManagerStateChanged: NOT_STARTED
D/BtGatt.AdvertiseManager( 5650): stop advertise for client 6
D/BtGatt.AdvertiseManager( 5650):  dualWaveClientIf = 0client.clientIf6
,D/WifiP2pService( 3523): InactiveState{ what=139268 }
I/wpa_supplicant( 3834): P2P-FIND-STOPPED 
,D/BtGatt.AdvertiseManager( 5650): logClientsSet() - status: -1
D/BtGatt.GattService( 5650): onAdvertiseInstanceDisabled() - clientIf=6, status=0
,D/BtGatt.GattService( 5650): Client app is not null!
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): P2P device discovery stopped successfully
,D/WifiP2pService( 3523): InactiveState{ what=147493 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=147493 }
D/WifiP2pService( 3523): discovery change broadcast false
,D/BtGatt.GattService( 5650): unregisterClient() - clientIf=6
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): restart: Restarting...,
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): onIsAdvertiserStartedChanged: false
D/WifiP2pService( 3523): InactiveState{ what=139268 }
W/bt-smp  ( 5650): Key(LSB ~ MSB) = 30 7e 01 64 39 c4 92 6c 13 df 24 1d 72 e8 19 7f 
W/bt-smp  ( 5650): Plain text(LSB ~ MSB) = 7c 25 6b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5650): Encrypted text(LSB ~ MSB) = e2 ed 1e 33 15 16 06 d6 74 fb d0 10 9e e5 14 93 
,D/BtGatt.GattService( 5650): stopScan() - queue size =1
,D/BtGatt.ScanManager( 5650): filter size is 1
D/BtGatt.GattService( 5650): unregisterClient() - clientIf=7
,D/BtGatt.ScanManager( 5650): delete FilterIndex - 4
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11750): stop: Stopping services
D/BtGatt.GattService( 5650): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 5650): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager( 5650): stop scan
D/BtGatt.ScanManager( 5650): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 5650): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 5650): configureRegularScanParams() - queue emtpy, scan stopped
,D/WifiP2pService( 3523): InactiveState{ what=139298 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(11750): release: No more listeners, de-initializing...
D/WifiP2pService( 3523): P2pEnabledState{ what=139298 }
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): release: No more listeners, de-initializing...
,D/WifiP2pService( 3523): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper(11750): onDiscoveryManagerStateChanged: NOT_STARTED
,D/WifiP2pService( 3523): remove client information from framework
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11750): Local services cleared successfully
I/jxcore-log(11750): ok 48 Should be able to call stopBroadcasting without error
I/jxcore-log(11750): 
D/WifiP2pService( 3523): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): P2P device discovery stopped successfully
,D/WifiP2pService( 3523): InactiveState{ what=139307 }
D/WifiP2pService( 3523): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3523): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11750): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453205195736.11750
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): initialize: My bluetooth address is E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(11750): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453205195736.11750","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter(11750): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(11750): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
D/BluetoothSocket(11750): bindListen(), new LocalSocket 
D/BluetoothSocket(11750): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(11750): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3fe39108
D/BluetoothSocket(11750): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): start: OK
I/io.jxcore.node.ConnectionHelper(11750): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper(11750): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11750): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453205195736.11750
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(11750): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(11750): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(11750): createAdvertiseData: From: 1453205195736.11750 b6a44ad1-d319-4b3a-815d-8b805a47fb51 E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(11750): E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(11750): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -32, -37, 16, 20, -30, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner(11750): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 5650): registerClient() - UUID=4ea8450d-1978-4e20-ad5e-1cc879a57b47
,D/BtGatt.GattService( 5650): onClientRegistered() - UUID=4ea8450d-1978-4e20-ad5e-1cc879a57b47, clientIf=6
,D/BluetoothLeAdvertiser(11750): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 5650): message : 0
,D/BtGatt.AdvertiseManager( 5650): number of adv instance running0
D/BtGatt.AdvertiseManager( 5650): size of list is =0
,D/BtGatt.AdvertiseManager( 5650): starting advertising
D/BtGatt.AdvertiseManager( 5650): isDualWavefalse
,D/BtGatt.GattService( 5650): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 5650): starting multi advertising
,D/BtGatt.GattService( 5650): onAdvertiseDataSet() - clientIf=6, status=0
D/BtGatt.AdvertiseManager( 5650): logClientsSet() - status: 0
D/BtGatt.AdvertiseManager( 5650): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService( 5650): registerClient() - UUID=afdec68b-303b-4d13-91a3-276740467712
,D/BtGatt.GattService( 5650): onClientRegistered() - UUID=afdec68b-303b-4d13-91a3-276740467712, clientIf=7
,D/BluetoothLeScanner(11750): onClientRegistered() - status=0 clientIf=7
,D/BtGatt.GattService( 5650): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startBlePeerDiscovery: OK
,D/BtGatt.ScanManager( 5650): handling starting scan
,D/BtGatt.GattService( 5650): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
D/BtGatt.ScanManager( 5650): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager( 5650): allow scan with filters
D/BtGatt.ScanManager( 5650): client filter size is = 1available filters are = 13
,D/BtGatt.ScanManager( 5650): set filter index= 5 for clientIf= 7
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(11750): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453205195736.11750","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11750): start: {"pi":"E0:DB:10:14:E2:C0","pn":"1453205195736.11750","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11750): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"1453205195736.11750","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/BtGatt.GattService( 5650): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 5650): callback done for clientIf - 7 status - 0
,D/WifiP2pService( 3523): InactiveState{ what=139292 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=139292 }
,D/BtGatt.ScanManager( 5650): configureRegularScanParams() - queue=1
,D/WifiP2pService( 3523): P2pEnabledState add service
,D/BtGatt.ScanManager( 5650): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,I/BtGatt.ScanManager( 5650): :scan window =2000 Scan interval = 5000
,D/WifiP2pService( 3523): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setState: RUNNING_BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453205195736.11750
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startBlePeerDiscovery: Already running
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(11750): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): onIsAdvertiserStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper(11750): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/io.jxcore.node.ConnectionHelper(11750): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11750): Local service added successfully
,I/jxcore-log(11750): ok 49 Should be able to call startBroadcasting without error
I/jxcore-log(11750): 
,D/WifiP2pService( 3523): InactiveState{ what=139265 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=139265 }
,D/WifiService( 3523): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3523): callSECApi what=74
D/WifiStateMachine( 3523): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3523): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3834): USE_NETWORK : USE_NETWORK OFF
,I/wpa_supplicant( 3834): p2p0: P2P: Reject scan trigger since one is already pending
,I/io.jxcore.node.ConnectionHelper(11750): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11750): shutdown
D/BluetoothSocket(11750): close() in, this: android.bluetooth.BluetoothSocket@15b665dd, channel: 6, state: LISTENING
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: STARTED
,D/BluetoothSocket(11750): close() this: android.bluetooth.BluetoothSocket@15b665dd, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3fe39108, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@37a0e552mSocket: android.net.LocalSocket@24ccd023 impl:android.net.LocalSocketImpl@30b17920 fd:FileDescriptor[118]
,D/BluetoothSocket(11750): Closing mSocket: android.net.LocalSocket@24ccd023 impl:android.net.LocalSocketImpl@30b17920 fd:FileDescriptor[118]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11750): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): release: 1 listener(s) left
,D/WifiP2pService( 3523): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper(11750): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): stop: Stopping peer discovery...
,D/BtGatt.AdvertiseManager( 5650): message : 1
,D/BtGatt.AdvertiseManager( 5650): stop advertise for client 6
,D/BtGatt.AdvertiseManager( 5650):  dualWaveClientIf = 0client.clientIf6
,D/BtGatt.AdvertiseManager( 5650): logClientsSet() - status: -1
,D/BtGatt.GattService( 5650): onAdvertiseInstanceDisabled() - clientIf=6, status=0
,D/BtGatt.GattService( 5650): Client app is not null!
,D/BtGatt.GattService( 5650): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): onIsAdvertiserStartedChanged: false
,W/bt-smp  ( 5650): Key(LSB ~ MSB) = 30 7e 01 64 39 c4 92 6c 13 df 24 1d 72 e8 19 7f 
,W/bt-smp  ( 5650): Plain text(LSB ~ MSB) = 93 b5 45 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5650): Encrypted text(LSB ~ MSB) = d0 8e f0 1a e6 a0 69 bf 03 9e 6d 63 b4 4c 93 98 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/BtGatt.GattService( 5650): stopScan() - queue size =1
,D/BtGatt.ScanManager( 5650): filter size is 1
,D/BtGatt.ScanManager( 5650): delete FilterIndex - 5
,D/BtGatt.GattService( 5650): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
,D/BtGatt.ScanManager( 5650): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager( 5650): stop scan
,D/BtGatt.ScanManager( 5650): configureRegularScanParams() - queue=0
,D/BtGatt.GattService( 5650): unregisterClient() - clientIf=7
D/WifiP2pService( 3523): InactiveState{ what=139268 }
I/wpa_supplicant( 3834): P2P-FIND-STOPPED 
,D/BtGatt.ScanManager( 5650): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 5650): configureRegularScanParams() - queue emtpy, scan stopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11750): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: NOT_INITIALIZED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): P2P device discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): stopWifiPeerDiscovery: Stopped
D/WifiP2pService( 3523): InactiveState{ what=147493 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(11750): release: No more listeners, de-initializing...
D/WifiP2pService( 3523): P2pEnabledState{ what=147493 }
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): release: No more listeners, de-initializing...
D/WifiP2pService( 3523): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper(11750): onDiscoveryManagerStateChanged: NOT_STARTED
D/WifiP2pService( 3523): InactiveState{ what=139298 }
D/WifiP2pService( 3523): P2pEnabledState{ what=139298 }
D/WifiP2pService( 3523): P2pEnabledState clear service
,I/jxcore-log(11750): ok 50 Should be able to call stopBroadcasting without error
I/jxcore-log(11750): 
,D/WifiP2pService( 3523): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11750): Local services cleared successfully
,D/WifiP2pService( 3523): InactiveState{ what=139268 }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): P2P device discovery stopped successfully
D/WifiP2pService( 3523): InactiveState{ what=139307 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=139307 }
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453205196029.11750
D/WifiP2pService( 3523): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): bind: Binding a new listener
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11750): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): initialize: My bluetooth address is E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(11750): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453205196029.11750","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter(11750): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(11750): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
D/BluetoothSocket(11750): bindListen(), new LocalSocket 
D/BluetoothSocket(11750): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(11750): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@35c4049e
D/BluetoothSocket(11750): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): start: OK
I/io.jxcore.node.ConnectionHelper(11750): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper(11750): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11750): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453205196029.11750
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(11750): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(11750): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(11750): createAdvertiseData: From: 1453205196029.11750 b6a44ad1-d319-4b3a-815d-8b805a47fb51 E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(11750): E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(11750): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -32, -37, 16, 20, -30, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner(11750): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 5650): registerClient() - UUID=92bce39c-2491-4cc1-88fb-0ec97c51cb96
,D/BtGatt.GattService( 5650): onClientRegistered() - UUID=92bce39c-2491-4cc1-88fb-0ec97c51cb96, clientIf=6
,D/BluetoothLeAdvertiser(11750): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 5650): message : 0
,D/BtGatt.AdvertiseManager( 5650): number of adv instance running0
,D/BtGatt.AdvertiseManager( 5650): size of list is =0
,D/BtGatt.AdvertiseManager( 5650): starting advertising
D/BtGatt.AdvertiseManager( 5650): isDualWavefalse
,D/BtGatt.GattService( 5650): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 5650): starting multi advertising
,D/BtGatt.GattService( 5650): onAdvertiseDataSet() - clientIf=6, status=0
D/BtGatt.AdvertiseManager( 5650): logClientsSet() - status: 0
D/BtGatt.AdvertiseManager( 5650): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService( 5650): registerClient() - UUID=d31b2331-6385-41c0-8750-3be947a0a6eb
,D/BtGatt.GattService( 5650): onClientRegistered() - UUID=d31b2331-6385-41c0-8750-3be947a0a6eb, clientIf=7
,D/BluetoothLeScanner(11750): onClientRegistered() - status=0 clientIf=7
,D/BtGatt.GattService( 5650): start scan with filters
,D/BtGatt.ScanManager( 5650): handling starting scan
,D/BtGatt.GattService( 5650): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,D/BtGatt.ScanManager( 5650): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager( 5650): allow scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startBlePeerDiscovery: OK
,D/BtGatt.ScanManager( 5650): client filter size is = 1available filters are = 13
,D/BtGatt.ScanManager( 5650): set filter index= 6 for clientIf= 7
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(11750): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453205196029.11750","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11750): start: {"pi":"E0:DB:10:14:E2:C0","pn":"1453205196029.11750","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11750): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"1453205196029.11750","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/BtGatt.GattService( 5650): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 5650): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager( 5650): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager( 5650): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,I/BtGatt.ScanManager( 5650): :scan window =2000 Scan interval = 5000
,D/WifiP2pService( 3523): InactiveState{ what=139292 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=139292 }
D/WifiP2pService( 3523): P2pEnabledState add service
D/WifiP2pService( 3523): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper(11750): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453205196029.11750
D/WifiP2pService( 3523): InactiveState{ what=139265 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=139265 }
D/WifiService( 3523): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/WifiStateMachine( 3523): callSECApi what=74
D/WifiStateMachine( 3523): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3523): callSECApiBoolean - ID [13]
I/wpa_supplicant( 3834): USE_NETWORK : USE_NETWORK OFF
,I/wpa_supplicant( 3834): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(11750): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11750): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper(11750): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: STARTED
D/WifiP2pService( 3523): discovery change broadcast true
,I/jxcore-log(11750): ok 51 Should be able to call startBroadcasting without error
I/jxcore-log(11750): 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/WifiP2pService( 3523): InactiveState{ what=139268 }
I/wpa_supplicant( 3834): P2P-FIND-STOPPED 
I/io.jxcore.node.ConnectionHelper(11750): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11750): shutdown
D/BluetoothSocket(11750): close() in, this: android.bluetooth.BluetoothSocket@300a209b, channel: 6, state: LISTENING
D/BluetoothSocket(11750): close() this: android.bluetooth.BluetoothSocket@300a209b, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@35c4049e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1d214c38mSocket: android.net.LocalSocket@37b6b411 impl:android.net.LocalSocketImpl@39ce0976 fd:FileDescriptor[118]
D/BluetoothSocket(11750): Closing mSocket: android.net.LocalSocket@37b6b411 impl:android.net.LocalSocketImpl@39ce0976 fd:FileDescriptor[118]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper(11750): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11750): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): onServerStopped
,D/BtGatt.AdvertiseManager( 5650): message : 1
,D/BtGatt.AdvertiseManager( 5650): stop advertise for client 6
D/BtGatt.AdvertiseManager( 5650):  dualWaveClientIf = 0client.clientIf6
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): P2P device discovery stopped successfully
D/WifiP2pService( 3523): InactiveState{ what=147493 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=147493 }
D/BtGatt.AdvertiseManager( 5650): logClientsSet() - status: -1
D/WifiP2pService( 3523): discovery change broadcast false
,D/BtGatt.GattService( 5650): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 5650): Client app is not null!
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: RESTARTING
,D/BtGatt.GattService( 5650): unregisterClient() - clientIf=6
D/WifiP2pService( 3523): InactiveState{ what=139268 }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 5650): stopScan() - queue size =1
,D/BtGatt.ScanManager( 5650): filter size is 1
D/BtGatt.ScanManager( 5650): delete FilterIndex - 6
D/BtGatt.GattService( 5650): unregisterClient() - clientIf=7
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11750): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onIsWifiPeerDiscoveryStartedChanged: false
D/WifiP2pService( 3523): InactiveState{ what=139298 }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(11750): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): release: No more listeners, de-initializing...
D/WifiP2pService( 3523): P2pEnabledState{ what=139298 }
W/bt-smp  ( 5650): Key(LSB ~ MSB) = 30 7e 01 64 39 c4 92 6c 13 df 24 1d 72 e8 19 7f 
D/WifiP2pService( 3523): P2pEnabledState clear service
W/bt-smp  ( 5650): Plain text(LSB ~ MSB) = 4c e6 48 00 00 00 00 00 00 00 00 00 00 00 00 00 
,W/bt-smp  ( 5650): Encrypted text(LSB ~ MSB) = 8e 7f c2 b5 a8 e7 f8 eb 2f 82 1e a8 bd 82 54 3d 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper(11750): onDiscoveryManagerStateChanged: NOT_STARTED
,D/WifiP2pService( 3523): remove client information from framework
,D/BtGatt.GattService( 5650): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 5650): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager( 5650): stop scan
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11750): Local services cleared successfully
D/BtGatt.ScanManager( 5650): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 5650): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 5650): configureRegularScanParams() - queue emtpy, scan stopped
,D/WifiP2pService( 3523): InactiveState{ what=139268 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): P2P device discovery stopped successfully
I/jxcore-log(11750): ok 52 Should be able to call stopBroadcasting without error
I/jxcore-log(11750): 
D/WifiP2pService( 3523): InactiveState{ what=139307 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=139307 }
D/WifiP2pService( 3523): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11750): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setDiscoveryMode: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453205196278.11750
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): initialize: My bluetooth address is E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(11750): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453205196278.11750","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter(11750): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(11750): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
D/BluetoothSocket(11750): bindListen(), new LocalSocket 
D/BluetoothSocket(11750): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(11750): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@23baf3e4
D/BluetoothSocket(11750): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): start: OK
I/io.jxcore.node.ConnectionHelper(11750): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper(11750): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11750): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453205196278.11750
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(11750): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(11750): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(11750): createAdvertiseData: From: 1453205196278.11750 b6a44ad1-d319-4b3a-815d-8b805a47fb51 E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(11750): E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(11750): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -32, -37, 16, 20, -30, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner(11750): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 5650): registerClient() - UUID=3da03775-3cd3-44fc-a2be-a21ffdcbb163
,D/BtGatt.GattService( 5650): onClientRegistered() - UUID=3da03775-3cd3-44fc-a2be-a21ffdcbb163, clientIf=6
,D/BluetoothLeAdvertiser(11750): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 5650): message : 0
,D/BtGatt.AdvertiseManager( 5650): number of adv instance running0
D/BtGatt.AdvertiseManager( 5650): size of list is =0
,D/BtGatt.AdvertiseManager( 5650): starting advertising
D/BtGatt.AdvertiseManager( 5650): isDualWavefalse
,D/BtGatt.GattService( 5650): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 5650): starting multi advertising
,D/BtGatt.GattService( 5650): onAdvertiseDataSet() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 5650): logClientsSet() - status: 0
,D/BtGatt.AdvertiseManager( 5650): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService( 5650): registerClient() - UUID=c144d374-c4eb-4a33-9d69-3d9568496809
,D/BtGatt.GattService( 5650): onClientRegistered() - UUID=c144d374-c4eb-4a33-9d69-3d9568496809, clientIf=7
,D/BluetoothLeScanner(11750): onClientRegistered() - status=0 clientIf=7
,D/BtGatt.GattService( 5650): start scan with filters
,D/BtGatt.ScanManager( 5650): handling starting scan
,D/BtGatt.GattService( 5650): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,D/BtGatt.ScanManager( 5650): callback done for clientIf - 7 status - 0
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startBlePeerDiscovery: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(11750): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453205196278.11750","ra":"E0:DB:10:14:E2:C0"}
,D/BtGatt.ScanManager( 5650): allow scan with filters
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11750): start: {"pi":"E0:DB:10:14:E2:C0","pn":"1453205196278.11750","ra":"E0:DB:10:14:E2:C0"}
,D/BtGatt.ScanManager( 5650): client filter size is = 1available filters are = 13
,D/BtGatt.ScanManager( 5650): set filter index= 7 for clientIf= 7
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11750): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"1453205196278.11750","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/BtGatt.GattService( 5650): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 5650): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager( 5650): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager( 5650): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,I/BtGatt.ScanManager( 5650): :scan window =2000 Scan interval = 5000
,D/WifiP2pService( 3523): InactiveState{ what=139292 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=139292 }
,D/WifiP2pService( 3523): P2pEnabledState add service
,D/WifiP2pService( 3523): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setState: RUNNING_BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453205196278.11750
,I/io.jxcore.node.ConnectionHelper(11750): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(11750): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11750): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper(11750): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,D/WifiP2pService( 3523): InactiveState{ what=139265 }
D/WifiP2pService( 3523): P2pEnabledState{ what=139265 }
,D/WifiService( 3523): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/WifiStateMachine( 3523): callSECApi what=74
D/WifiStateMachine( 3523): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3523): callSECApiBoolean - ID [13]
I/wpa_supplicant( 3834): USE_NETWORK : USE_NETWORK OFF
,I/wpa_supplicant( 3834): p2p0: P2P: Reject scan trigger since one is already pending
I/jxcore-log(11750): ok 53 Should be able to call startBroadcasting without error
I/jxcore-log(11750): 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: STARTED
D/WifiP2pService( 3523): discovery change broadcast true
,I/io.jxcore.node.ConnectionHelper(11750): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11750): shutdown
D/WifiP2pService( 3523): InactiveState{ what=139268 }
D/BluetoothSocket(11750): close() in, this: android.bluetooth.BluetoothSocket@1432d449, channel: 6, state: LISTENING
D/BluetoothSocket(11750): close() this: android.bluetooth.BluetoothSocket@1432d449, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@23baf3e4, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@fc8d14emSocket: android.net.LocalSocket@189b126f impl:android.net.LocalSocketImpl@2a7edb7c fd:FileDescriptor[118]
D/BluetoothSocket(11750): Closing mSocket: android.net.LocalSocket@189b126f impl:android.net.LocalSocketImpl@2a7edb7c fd:FileDescriptor[118]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11750): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): onServerStopped
I/io.jxcore.node.ConnectionHelper(11750): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): stop: Stopping peer discovery...
I/wpa_supplicant( 3834): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): P2P device discovery stopped successfully
D/BtGatt.AdvertiseManager( 5650): message : 1
,D/BtGatt.AdvertiseManager( 5650): stop advertise for client 6
D/WifiP2pService( 3523): InactiveState{ what=147493 }
D/BtGatt.AdvertiseManager( 5650):  dualWaveClientIf = 0client.clientIf6
D/WifiP2pService( 3523): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3523): discovery change broadcast false
D/BtGatt.AdvertiseManager( 5650): logClientsSet() - status: -1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: RESTARTING
,D/BtGatt.GattService( 5650): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 5650): Client app is not null!
D/WifiP2pService( 3523): InactiveState{ what=139268 }
,D/BtGatt.GattService( 5650): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 5650): stopScan() - queue size =1
,D/BtGatt.ScanManager( 5650): filter size is 1
,D/BtGatt.GattService( 5650): unregisterClient() - clientIf=7
D/BtGatt.ScanManager( 5650): delete FilterIndex - 7
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): setIsStarted: true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11750): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): stop: Stopping P2P device discovery...
,D/WifiP2pService( 3523): InactiveState{ what=139298 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: NOT_INITIALIZED
D/WifiP2pService( 3523): P2pEnabledState{ what=139298 }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): stopWifiPeerDiscovery: Stopped
W/bt-smp  ( 5650): Key(LSB ~ MSB) = 30 7e 01 64 39 c4 92 6c 13 df 24 1d 72 e8 19 7f 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(11750): release: No more listeners, de-initializing...
D/WifiP2pService( 3523): P2pEnabledState clear service
,W/bt-smp  ( 5650): Plain text(LSB ~ MSB) = 54 63 51 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5650): Encrypted text(LSB ~ MSB) = 87 b1 0d cc dd 34 ac a7 c4 a2 5d 95 52 7f b6 11 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): release: No more listeners, de-initializing...
,D/BtGatt.GattService( 5650): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setState: NOT_STARTED,
D/BtGatt.ScanManager( 5650): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager( 5650): stop scan
D/BtGatt.ScanManager( 5650): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 5650): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
,D/BtGatt.ScanManager( 5650): configureRegularScanParams() - queue emtpy, scan stopped
I/io.jxcore.node.ConnectionHelper(11750): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log(11750): ok 54 Should be able to call stopBroadcasting without error,
I/jxcore-log(11750): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setDiscoveryMode: Mode set to BLE,
D/WifiP2pService( 3523): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setDiscoveryMode: Mode set to BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11750): Local services cleared successfully
,D/WifiP2pService( 3523): InactiveState{ what=139268 }
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453205196515.11750
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): initialize: My bluetooth address is E0:DB:10:14:E2:C0
D/WifiP2pService( 3523): InactiveState{ what=139307 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): P2P device discovery stopped successfully
D/WifiP2pService( 3523): P2pEnabledState clear service request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11750): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(11750): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453205196515.11750","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter(11750): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(11750): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
D/BluetoothSocket(11750): bindListen(), new LocalSocket 
D/BluetoothSocket(11750): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(11750): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2e64b45a
D/BluetoothSocket(11750): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): start: OK
I/io.jxcore.node.ConnectionHelper(11750): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper(11750): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11750): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453205196515.11750
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(11750): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(11750): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(11750): createAdvertiseData: From: 1453205196515.11750 b6a44ad1-d319-4b3a-815d-8b805a47fb51 E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(11750): E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(11750): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -32, -37, 16, 20, -30, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner(11750): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 5650): registerClient() - UUID=544d4c74-984d-4a38-998e-7372ec1f6065
,D/BtGatt.GattService( 5650): onClientRegistered() - UUID=544d4c74-984d-4a38-998e-7372ec1f6065, clientIf=6
,D/BluetoothLeAdvertiser(11750): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 5650): message : 0
,D/BtGatt.AdvertiseManager( 5650): number of adv instance running0
,D/BtGatt.AdvertiseManager( 5650): size of list is =0
,D/BtGatt.AdvertiseManager( 5650): starting advertising
D/BtGatt.AdvertiseManager( 5650): isDualWavefalse
,D/BtGatt.GattService( 5650): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 5650): starting multi advertising
,D/BtGatt.GattService( 5650): onAdvertiseDataSet() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 5650): logClientsSet() - status: 0
,D/BtGatt.AdvertiseManager( 5650): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService( 5650): registerClient() - UUID=3ede0894-197b-4b1d-9129-cd10409d815e
,D/BtGatt.GattService( 5650): onClientRegistered() - UUID=3ede0894-197b-4b1d-9129-cd10409d815e, clientIf=7
,D/BluetoothLeScanner(11750): onClientRegistered() - status=0 clientIf=7
,D/BtGatt.GattService( 5650): start scan with filters
,D/BtGatt.ScanManager( 5650): handling starting scan
,D/BtGatt.GattService( 5650): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,D/BtGatt.ScanManager( 5650): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager( 5650): allow scan with filters
,D/BtGatt.ScanManager( 5650): client filter size is = 1available filters are = 13
,D/BtGatt.ScanManager( 5650): set filter index= 8 for clientIf= 7
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startBlePeerDiscovery: OK
,D/BtGatt.GattService( 5650): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 5650): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager( 5650): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager( 5650): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,I/BtGatt.ScanManager( 5650): :scan window =2000 Scan interval = 5000
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(11750): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453205196515.11750","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11750): start: {"pi":"E0:DB:10:14:E2:C0","pn":"1453205196515.11750","ra":"E0:DB:10:14:E2:C0"},
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11750): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"1453205196515.11750","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 3523): InactiveState{ what=139292 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=139292 }
,D/WifiP2pService( 3523): P2pEnabledState add service
,D/WifiP2pService( 3523): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setState: RUNNING_BLE_AND_WIFI
D/WifiP2pService( 3523): InactiveState{ what=139265 }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453205196515.11750
D/WifiP2pService( 3523): P2pEnabledState{ what=139265 }
I/WifiStateMachine( 3523): callSECApi what=74
D/WifiService( 3523): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 3523): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3523): callSECApiBoolean - ID [13]
I/wpa_supplicant( 3834): USE_NETWORK : USE_NETWORK OFF
,I/io.jxcore.node.ConnectionHelper(11750): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: OK
D/WifiP2pService( 3523): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(11750): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): onIsAdvertiserStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11750): Local service added successfully
I/io.jxcore.node.ConnectionHelper(11750): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/jxcore-log(11750): ok 55 Should be able to call startBroadcasting without error
I/jxcore-log(11750): 
,D/WifiP2pService( 3523): InactiveState{ what=139268 }
I/wpa_supplicant( 3834): P2P-FIND-STOPPED 
,I/io.jxcore.node.ConnectionHelper(11750): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11750): shutdown
D/BluetoothSocket(11750): close() in, this: android.bluetooth.BluetoothSocket@38fce067, channel: 6, state: LISTENING
D/BluetoothSocket(11750): close() this: android.bluetooth.BluetoothSocket@38fce067, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2e64b45a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@6b51e14mSocket: android.net.LocalSocket@21c016bd impl:android.net.LocalSocketImpl@38e574b2 fd:FileDescriptor[118]
D/BluetoothSocket(11750): Closing mSocket: android.net.LocalSocket@21c016bd impl:android.net.LocalSocketImpl@38e574b2 fd:FileDescriptor[118]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11750): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper(11750): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): P2P device discovery stopped successfully
,D/WifiP2pService( 3523): InactiveState{ what=147493 }
D/BtGatt.AdvertiseManager( 5650): message : 1
D/WifiP2pService( 3523): P2pEnabledState{ what=147493 }
D/WifiP2pService( 3523): discovery change broadcast false
,D/BtGatt.AdvertiseManager( 5650): stop advertise for client 6
D/BtGatt.AdvertiseManager( 5650):  dualWaveClientIf = 0client.clientIf6
,D/BtGatt.AdvertiseManager( 5650): logClientsSet() - status: -1
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: RESTARTING
,D/WifiP2pService( 3523): InactiveState{ what=139268 }
D/BtGatt.GattService( 5650): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 5650): Client app is not null!
,D/BtGatt.GattService( 5650): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 5650): stopScan() - queue size =1
,D/BtGatt.GattService( 5650): unregisterClient() - clientIf=7
D/BtGatt.ScanManager( 5650): filter size is 1
D/BtGatt.ScanManager( 5650): delete FilterIndex - 8
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11750): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): stop: Stopping P2P device discovery...
D/WifiP2pService( 3523): InactiveState{ what=139298 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): stopWifiPeerDiscovery: Stopped
D/WifiP2pService( 3523): P2pEnabledState{ what=139298 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(11750): release: No more listeners, de-initializing...
,D/WifiP2pService( 3523): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setState: NOT_STARTED
W/bt-smp  ( 5650): Key(LSB ~ MSB) = 30 7e 01 64 39 c4 92 6c 13 df 24 1d 72 e8 19 7f 
W/bt-smp  ( 5650): Plain text(LSB ~ MSB) = 16 e5 66 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5650): Encrypted text(LSB ~ MSB) = b7 6b b9 fc 13 62 44 ed 1b 97 18 35 14 ef 08 6e 
,I/io.jxcore.node.ConnectionHelper(11750): onDiscoveryManagerStateChanged: NOT_STARTED
D/WifiP2pService( 3523): remove client information from framework
,D/WifiP2pService( 3523): InactiveState{ what=139268 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11750): Local services cleared successfully
D/BtGatt.GattService( 5650): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 5650): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager( 5650): stop scan
D/BtGatt.ScanManager( 5650): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 5650): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 5650): configureRegularScanParams() - queue emtpy, scan stopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): P2P device discovery stopped successfully
D/WifiP2pService( 3523): InactiveState{ what=139307 }
D/WifiP2pService( 3523): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3523): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11750): Service requests cleared successfully
,I/jxcore-log(11750): ok 56 Should be able to call stopBroadcasting without error
I/jxcore-log(11750): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setDiscoveryMode: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453205196764.11750
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): initialize: My bluetooth address is E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(11750): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453205196764.11750","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter(11750): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(11750): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
D/BluetoothSocket(11750): bindListen(), new LocalSocket 
D/BluetoothSocket(11750): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(11750): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2ed00780
D/BluetoothSocket(11750): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): start: OK
I/io.jxcore.node.ConnectionHelper(11750): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper(11750): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11750): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453205196764.11750
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(11750): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(11750): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(11750): createAdvertiseData: From: 1453205196764.11750 b6a44ad1-d319-4b3a-815d-8b805a47fb51 E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(11750): E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(11750): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -32, -37, 16, 20, -30, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner(11750): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 5650): registerClient() - UUID=c5be054b-6bc5-493b-9d25-75c36474dd59
,D/BtGatt.GattService( 5650): onClientRegistered() - UUID=c5be054b-6bc5-493b-9d25-75c36474dd59, clientIf=6
,D/BluetoothLeAdvertiser(11750): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 5650): message : 0
,D/BtGatt.AdvertiseManager( 5650): number of adv instance running0
,D/BtGatt.AdvertiseManager( 5650): size of list is =0
,D/BtGatt.AdvertiseManager( 5650): starting advertising
,D/BtGatt.AdvertiseManager( 5650): isDualWavefalse
,D/BtGatt.GattService( 5650): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 5650): starting multi advertising
,D/BtGatt.GattService( 5650): onAdvertiseDataSet() - clientIf=6, status=0
D/BtGatt.AdvertiseManager( 5650): logClientsSet() - status: 0
D/BtGatt.AdvertiseManager( 5650): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService( 5650): registerClient() - UUID=b4fe08c3-7bde-494f-8d1e-5055ecd4b5ee
,D/BtGatt.GattService( 5650): onClientRegistered() - UUID=b4fe08c3-7bde-494f-8d1e-5055ecd4b5ee, clientIf=7
,D/BluetoothLeScanner(11750): onClientRegistered() - status=0 clientIf=7
,D/BtGatt.GattService( 5650): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startBlePeerDiscovery: OK
D/BtGatt.ScanManager( 5650): handling starting scan
,D/BtGatt.GattService( 5650): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
D/BtGatt.ScanManager( 5650): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager( 5650): allow scan with filters
D/BtGatt.ScanManager( 5650): client filter size is = 1available filters are = 13
D/BtGatt.ScanManager( 5650): set filter index= 9 for clientIf= 7
,D/BtGatt.GattService( 5650): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 5650): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager( 5650): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 5650): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/BtGatt.ScanManager( 5650): :scan window =2000 Scan interval = 5000
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(11750): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453205196764.11750","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11750): start: {"pi":"E0:DB:10:14:E2:C0","pn":"1453205196764.11750","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11750): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"1453205196764.11750","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 3523): InactiveState{ what=139292 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=139292 }
,D/WifiP2pService( 3523): P2pEnabledState add service
,D/WifiP2pService( 3523): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper(11750): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453205196764.11750
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startWifiPeerDiscovery: Wi-Fi Direct OK
D/WifiP2pService( 3523): InactiveState{ what=139265 }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: OK
D/WifiP2pService( 3523): P2pEnabledState{ what=139265 }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(11750): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): onIsAdvertiserStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): restart: Restarting...
D/WifiService( 3523): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11750): Local service added successfully
I/io.jxcore.node.ConnectionHelper(11750): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/WifiStateMachine( 3523): callSECApi what=74
D/WifiStateMachine( 3523): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3523): callSECApiBoolean - ID [13]
I/wpa_supplicant( 3834): USE_NETWORK : USE_NETWORK OFF
,I/jxcore-log(11750): ok 57 Should be able to call startBroadcasting without error
I/jxcore-log(11750): 
,I/io.jxcore.node.ConnectionHelper(11750): stop,
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11750): shutdown
D/BluetoothSocket(11750): close() in, this: android.bluetooth.BluetoothSocket@2ed86075, channel: 6, state: LISTENING
,D/BluetoothSocket(11750): close() this: android.bluetooth.BluetoothSocket@2ed86075, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2ed00780, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2f02e80amSocket: android.net.LocalSocket@28ac087b impl:android.net.LocalSocketImpl@5f74698 fd:FileDescriptor[118]
D/BluetoothSocket(11750): Closing mSocket: android.net.LocalSocket@28ac087b impl:android.net.LocalSocketImpl@5f74698 fd:FileDescriptor[118]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11750): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): onServerStopped
I/wpa_supplicant( 3834): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: STARTED
D/WifiP2pService( 3523): discovery change broadcast true
,D/WifiP2pService( 3523): InactiveState{ what=139268 }
,I/wpa_supplicant( 3834): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper(11750): onConnectionManagerStateChanged: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): P2P device discovery stopped successfully
D/WifiP2pService( 3523): InactiveState{ what=147493 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=147493 }
D/WifiP2pService( 3523): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: RESTARTING
,D/BtGatt.AdvertiseManager( 5650): message : 1
D/BtGatt.AdvertiseManager( 5650): stop advertise for client 6
D/BtGatt.AdvertiseManager( 5650):  dualWaveClientIf = 0client.clientIf6
,D/WifiP2pService( 3523): InactiveState{ what=139268 }
,D/BtGatt.AdvertiseManager( 5650): logClientsSet() - status: -1
,D/BtGatt.GattService( 5650): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 5650): Client app is not null!
,D/BtGatt.GattService( 5650): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 5650): stopScan() - queue size =1
,D/BtGatt.ScanManager( 5650): filter size is 1
D/BtGatt.ScanManager( 5650): delete FilterIndex - 9
,D/BtGatt.GattService( 5650): unregisterClient() - clientIf=7
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11750): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: NOT_INITIALIZED
D/WifiP2pService( 3523): InactiveState{ what=139298 }
,W/bt-smp  ( 5650): Key(LSB ~ MSB) = 30 7e 01 64 39 c4 92 6c 13 df 24 1d 72 e8 19 7f 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): stopWifiPeerDiscovery: Stopped
W/bt-smp  ( 5650): Plain text(LSB ~ MSB) = 46 17 7b 00 00 00 00 00 00 00 00 00 00 00 00 00 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(11750): release: No more listeners, de-initializing...
W/bt-smp  ( 5650): Encrypted text(LSB ~ MSB) = 13 b4 ca f8 d9 93 97 83 da 6b 62 8f de c1 7f c2 
,D/WifiP2pService( 3523): P2pEnabledState{ what=139298 }
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): release: No more listeners, de-initializing...
D/WifiP2pService( 3523): P2pEnabledState clear service
,D/BtGatt.GattService( 5650): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 5650): callback done for clientIf - 7 status - 0
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setState: NOT_STARTED
D/BtGatt.ScanManager( 5650): stop scan
D/BtGatt.ScanManager( 5650): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 5650): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 5650): configureRegularScanParams() - queue emtpy, scan stopped
,I/io.jxcore.node.ConnectionHelper(11750): onDiscoveryManagerStateChanged: NOT_STARTED
,D/WifiP2pService( 3523): remove client information from framework
,I/jxcore-log(11750): ok 58 Should be able to call stopBroadcasting without error
I/jxcore-log(11750): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11750): Local services cleared successfully
D/WifiP2pService( 3523): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): P2P device discovery stopped successfully
D/WifiP2pService( 3523): InactiveState{ what=139307 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3523): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453205196984.11750
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): bind: Binding a new listener
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11750): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): initialize: My bluetooth address is E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(11750): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453205196984.11750","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter(11750): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(11750): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
D/BluetoothSocket(11750): bindListen(), new LocalSocket 
D/BluetoothSocket(11750): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(11750): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@22ef7ad6
D/BluetoothSocket(11750): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): setState: RUNNING
I/io.jxcore.node.ConnectionHelper(11750): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): start: OK
I/io.jxcore.node.ConnectionHelper(11750): start: Using peer discovery mode: BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11750): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453205196984.11750
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(11750): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(11750): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(11750): createAdvertiseData: From: 1453205196984.11750 b6a44ad1-d319-4b3a-815d-8b805a47fb51 E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(11750): E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(11750): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -32, -37, 16, 20, -30, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner(11750): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 5650): registerClient() - UUID=dd1accc5-5738-492b-ab7c-3a39a379590f
,D/BtGatt.GattService( 5650): onClientRegistered() - UUID=dd1accc5-5738-492b-ab7c-3a39a379590f, clientIf=6
,D/BluetoothLeAdvertiser(11750): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 5650): message : 0
,D/BtGatt.AdvertiseManager( 5650): number of adv instance running0
D/BtGatt.AdvertiseManager( 5650): size of list is =0
,D/BtGatt.AdvertiseManager( 5650): starting advertising
D/BtGatt.AdvertiseManager( 5650): isDualWavefalse
,D/BtGatt.GattService( 5650): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 5650): starting multi advertising
,D/BtGatt.GattService( 5650): onAdvertiseDataSet() - clientIf=6, status=0
D/BtGatt.AdvertiseManager( 5650): logClientsSet() - status: 0
D/BtGatt.AdvertiseManager( 5650): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService( 5650): registerClient() - UUID=f0c200ef-dba6-41b8-853d-2fb9ae496d0c
,D/BtGatt.GattService( 5650): onClientRegistered() - UUID=f0c200ef-dba6-41b8-853d-2fb9ae496d0c, clientIf=7
,D/BluetoothLeScanner(11750): onClientRegistered() - status=0 clientIf=7
D/BtGatt.GattService( 5650): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startBlePeerDiscovery: OK
,D/BtGatt.ScanManager( 5650): handling starting scan
,D/BtGatt.GattService( 5650): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
D/BtGatt.ScanManager( 5650): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager( 5650): allow scan with filters
D/BtGatt.ScanManager( 5650): client filter size is = 1available filters are = 13
D/BtGatt.ScanManager( 5650): set filter index= 10 for clientIf= 7
,D/BtGatt.GattService( 5650): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15,
D/BtGatt.ScanManager( 5650): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager( 5650): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager( 5650): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/BtGatt.ScanManager( 5650): :scan window =2000 Scan interval = 5000
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(11750): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453205196984.11750","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11750): start: {"pi":"E0:DB:10:14:E2:C0","pn":"1453205196984.11750","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11750): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"1453205196984.11750","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 3523): InactiveState{ what=139292 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=139292 }
,D/WifiP2pService( 3523): P2pEnabledState add service
,D/WifiP2pService( 3523): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): start: Starting P2P device discovery...
,D/WifiP2pService( 3523): InactiveState{ what=139265 }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setState: RUNNING_BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453205196984.11750
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startBlePeerDiscovery: Already running
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(11750): onStartSuccess
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11750): Local service added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper(11750): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/io.jxcore.node.ConnectionHelper(11750): start: OK
,D/WifiP2pService( 3523): P2pEnabledState{ what=139265 }
,D/WifiService( 3523): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3523): callSECApi what=74
,D/WifiStateMachine( 3523): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3523): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3834): USE_NETWORK : USE_NETWORK OFF
,I/wpa_supplicant( 3834): p2p0: P2P: Reject scan trigger since one is already pending
,I/jxcore-log(11750): ok 59 Should be able to call startBroadcasting without error
I/jxcore-log(11750): 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: STARTED
,D/WifiP2pService( 3523): discovery change broadcast true
,I/io.jxcore.node.ConnectionHelper(11750): stop
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11750): shutdown
,D/BluetoothSocket(11750): close() in, this: android.bluetooth.BluetoothSocket@2ddd0bf3, channel: 6, state: LISTENING
,D/BluetoothSocket(11750): close() this: android.bluetooth.BluetoothSocket@2ddd0bf3, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@22ef7ad6, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@11b450b0mSocket: android.net.LocalSocket@127c2b29 impl:android.net.LocalSocketImpl@3ebb0eae fd:FileDescriptor[118]
,D/BluetoothSocket(11750): Closing mSocket: android.net.LocalSocket@127c2b29 impl:android.net.LocalSocketImpl@3ebb0eae fd:FileDescriptor[118]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11750): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): release: 1 listener(s) left
,D/WifiP2pService( 3523): InactiveState{ what=139268 }
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper(11750): onConnectionManagerStateChanged: NOT_STARTED
I/wpa_supplicant( 3834): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): stop: Stopping peer discovery...
,D/BtGatt.AdvertiseManager( 5650): message : 1
,D/BtGatt.AdvertiseManager( 5650): stop advertise for client 6
,D/BtGatt.AdvertiseManager( 5650):  dualWaveClientIf = 0client.clientIf6
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): P2P device discovery stopped successfully
,D/WifiP2pService( 3523): InactiveState{ what=147493 }
,D/BtGatt.AdvertiseManager( 5650): logClientsSet() - status: -1
,D/BtGatt.GattService( 5650): onAdvertiseInstanceDisabled() - clientIf=6, status=0
,D/BtGatt.GattService( 5650): Client app is not null!
,D/BtGatt.GattService( 5650): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): onIsAdvertiserStartedChanged: false
,W/bt-smp  ( 5650): Key(LSB ~ MSB) = 30 7e 01 64 39 c4 92 6c 13 df 24 1d 72 e8 19 7f 
,W/bt-smp  ( 5650): Plain text(LSB ~ MSB) = cd a1 4e 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5650): Encrypted text(LSB ~ MSB) = c6 51 74 1a 52 40 2a d8 0b 0a 1c 62 6b 27 67 a2 
,D/BtGatt.GattService( 5650): stopScan() - queue size =1
,D/BtGatt.GattService( 5650): unregisterClient() - clientIf=7
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): onIsScannerStartedChanged: false
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): setIsStarted: true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11750): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): stop: Stopping P2P device discovery...
,D/WifiP2pService( 3523): P2pEnabledState{ what=147493 }
,D/BtGatt.ScanManager( 5650): filter size is 1
,D/BtGatt.ScanManager( 5650): delete FilterIndex - 10
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(11750): release: No more listeners, de-initializing...
,D/BtGatt.GattService( 5650): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 5650): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager( 5650): stop scan
D/WifiP2pService( 3523): discovery change broadcast false
D/BtGatt.ScanManager( 5650): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 5650): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 5650): configureRegularScanParams() - queue emtpy, scan stopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): release: No more listeners, de-initializing...
,D/WifiP2pService( 3523): InactiveState{ what=139298 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=139298 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setState: NOT_STARTED
D/WifiP2pService( 3523): P2pEnabledState clear service
I/io.jxcore.node.ConnectionHelper(11750): onDiscoveryManagerStateChanged: NOT_STARTED
,D/WifiP2pService( 3523): remove client information from framework
I/jxcore-log(11750): ok 60 Should be able to call stopBroadcasting without error
I/jxcore-log(11750): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11750): Local services cleared successfully
D/WifiP2pService( 3523): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): P2P device discovery stopped successfully
D/WifiP2pService( 3523): InactiveState{ what=139307 }
D/WifiP2pService( 3523): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3523): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11750): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453205197282.11750
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): initialize: My bluetooth address is E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(11750): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453205197282.11750","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter(11750): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(11750): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
D/BluetoothSocket(11750): bindListen(), new LocalSocket 
D/BluetoothSocket(11750): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(11750): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3b85c7dc
D/BluetoothSocket(11750): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): start: OK
I/io.jxcore.node.ConnectionHelper(11750): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper(11750): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11750): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453205197282.11750
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(11750): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(11750): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(11750): createAdvertiseData: From: 1453205197282.11750 b6a44ad1-d319-4b3a-815d-8b805a47fb51 E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(11750): E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(11750): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -32, -37, 16, 20, -30, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner(11750): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 5650): registerClient() - UUID=acf4d058-d4f2-47d5-b980-06a656ee52de
,D/BtGatt.GattService( 5650): onClientRegistered() - UUID=acf4d058-d4f2-47d5-b980-06a656ee52de, clientIf=6
,D/BluetoothLeAdvertiser(11750): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 5650): message : 0
,D/BtGatt.AdvertiseManager( 5650): number of adv instance running0
D/BtGatt.AdvertiseManager( 5650): size of list is =0
,D/BtGatt.AdvertiseManager( 5650): starting advertising
D/BtGatt.AdvertiseManager( 5650): isDualWavefalse
,D/BtGatt.GattService( 5650): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 5650): starting multi advertising
,D/BtGatt.GattService( 5650): onAdvertiseDataSet() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 5650): logClientsSet() - status: 0
D/BtGatt.AdvertiseManager( 5650): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService( 5650): registerClient() - UUID=db43eb4c-3a9f-41af-b2d8-ebe554360740
,D/BtGatt.GattService( 5650): onClientRegistered() - UUID=db43eb4c-3a9f-41af-b2d8-ebe554360740, clientIf=7
,D/BluetoothLeScanner(11750): onClientRegistered() - status=0 clientIf=7
D/BtGatt.GattService( 5650): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startBlePeerDiscovery: OK
D/BtGatt.ScanManager( 5650): handling starting scan
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(11750): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453205197282.11750","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11750): start: {"pi":"E0:DB:10:14:E2:C0","pn":"1453205197282.11750","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11750): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"1453205197282.11750","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/BtGatt.GattService( 5650): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
D/BtGatt.ScanManager( 5650): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager( 5650): allow scan with filters
D/BtGatt.ScanManager( 5650): client filter size is = 1available filters are = 13
D/BtGatt.ScanManager( 5650): set filter index= 11 for clientIf= 7
,D/WifiP2pService( 3523): InactiveState{ what=139292 }
D/BtGatt.GattService( 5650): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 5650): callback done for clientIf - 7 status - 0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): start: Starting P2P device discovery...
D/BtGatt.ScanManager( 5650): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 5650): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/BtGatt.ScanManager( 5650): :scan window =2000 Scan interval = 5000
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453205197282.11750
D/WifiP2pService( 3523): P2pEnabledState{ what=139292 }
,I/io.jxcore.node.ConnectionHelper(11750): start: OK
,D/WifiP2pService( 3523): P2pEnabledState add service
D/WifiP2pService( 3523): add a new client
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(11750): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): onIsAdvertiserStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): restart: Restarting...
D/WifiP2pService( 3523): InactiveState{ what=139265 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper(11750): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11750): Local service added successfully
D/WifiP2pService( 3523): P2pEnabledState{ what=139265 }
,D/WifiService( 3523): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/WifiStateMachine( 3523): callSECApi what=74
D/WifiStateMachine( 3523): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3523): callSECApiBoolean - ID [13]
I/wpa_supplicant( 3834): USE_NETWORK : USE_NETWORK OFF
,I/jxcore-log(11750): ok 61 Should be able to call startBroadcasting without error
I/jxcore-log(11750): 
,I/wpa_supplicant( 3834): p2p0: P2P: Reject scan trigger since one is already pending
,I/io.jxcore.node.ConnectionHelper(11750): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): P2P device discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11750): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: STARTED
D/BluetoothSocket(11750): close() in, this: android.bluetooth.BluetoothSocket@21d1661, channel: 6, state: LISTENING
D/BluetoothSocket(11750): close() this: android.bluetooth.BluetoothSocket@21d1661, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3b85c7dc, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@333a4586mSocket: android.net.LocalSocket@1ca29e47 impl:android.net.LocalSocketImpl@2f613674 fd:FileDescriptor[118]
D/BluetoothSocket(11750): Closing mSocket: android.net.LocalSocket@1ca29e47 impl:android.net.LocalSocketImpl@2f613674 fd:FileDescriptor[118]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11750): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): onServerStopped
,D/WifiP2pService( 3523): discovery change broadcast true
I/io.jxcore.node.ConnectionHelper(11750): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): stop: Stopping peer discovery...
,D/BtGatt.AdvertiseManager( 5650): message : 1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/BtGatt.AdvertiseManager( 5650): stop advertise for client 6
D/BtGatt.AdvertiseManager( 5650):  dualWaveClientIf = 0client.clientIf6
,D/WifiP2pService( 3523): InactiveState{ what=139268 }
,I/wpa_supplicant( 3834): P2P-FIND-STOPPED 
D/BtGatt.AdvertiseManager( 5650): logClientsSet() - status: -1
,D/BtGatt.GattService( 5650): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 5650): Client app is not null!
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): P2P device discovery stopped successfully
,D/BtGatt.GattService( 5650): unregisterClient() - clientIf=6
D/WifiP2pService( 3523): InactiveState{ what=147493 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3523): discovery change broadcast false
W/bt-smp  ( 5650): Key(LSB ~ MSB) = 30 7e 01 64 39 c4 92 6c 13 df 24 1d 72 e8 19 7f 
W/bt-smp  ( 5650): Plain text(LSB ~ MSB) = 81 70 44 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5650): Encrypted text(LSB ~ MSB) = d3 21 ad 81 b0 77 6f a9 b7 ec 56 f1 2d b6 a8 d1 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 5650): stopScan() - queue size =1
,D/BtGatt.ScanManager( 5650): filter size is 1
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: RESTARTING
,D/BtGatt.ScanManager( 5650): delete FilterIndex - 11
,D/BtGatt.GattService( 5650): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 5650): callback done for clientIf - 7 status - 0
,D/BtGatt.GattService( 5650): unregisterClient() - clientIf=7
D/BtGatt.ScanManager( 5650): stop scan
,D/BtGatt.ScanManager( 5650): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 5650): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 5650): configureRegularScanParams() - queue emtpy, scan stopped
,D/WifiP2pService( 3523): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11750): stop: Stopping services
,D/WifiP2pService( 3523): InactiveState{ what=139298 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=139298 }
D/WifiP2pService( 3523): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(11750): release: No more listeners, de-initializing...
,D/WifiP2pService( 3523): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11750): Local services cleared successfully
D/WifiP2pService( 3523): InactiveState{ what=139268 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper(11750): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): P2P device discovery stopped successfully
D/WifiP2pService( 3523): InactiveState{ what=139307 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=139307 }
D/WifiP2pService( 3523): P2pEnabledState clear service request
,I/jxcore-log(11750): ok 62 Should be able to call stopBroadcasting without error
I/jxcore-log(11750): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11750): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setDiscoveryMode: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453205197492.11750
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): initialize: My bluetooth address is E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(11750): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453205197492.11750","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter(11750): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(11750): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
D/BluetoothSocket(11750): bindListen(), new LocalSocket 
D/BluetoothSocket(11750): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(11750): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1ae53412
D/BluetoothSocket(11750): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): start: OK
I/io.jxcore.node.ConnectionHelper(11750): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper(11750): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11750): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453205197492.11750
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(11750): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(11750): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(11750): createAdvertiseData: From: 1453205197492.11750 b6a44ad1-d319-4b3a-815d-8b805a47fb51 E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(11750): E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(11750): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -32, -37, 16, 20, -30, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner(11750): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 5650): registerClient() - UUID=7c471443-250f-446f-970c-bb3fc1e68486
,D/BtGatt.GattService( 5650): onClientRegistered() - UUID=7c471443-250f-446f-970c-bb3fc1e68486, clientIf=6
,D/BluetoothLeAdvertiser(11750): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 5650): message : 0
,D/BtGatt.AdvertiseManager( 5650): number of adv instance running0
,D/BtGatt.AdvertiseManager( 5650): size of list is =0
,D/BtGatt.AdvertiseManager( 5650): starting advertising
D/BtGatt.AdvertiseManager( 5650): isDualWavefalse
,D/BtGatt.GattService( 5650): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 5650): starting multi advertising
,D/BtGatt.GattService( 5650): onAdvertiseDataSet() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 5650): logClientsSet() - status: 0
D/BtGatt.AdvertiseManager( 5650): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService( 5650): registerClient() - UUID=7711d66a-4b40-4768-bd7b-5fcba50f2b36
,D/BtGatt.GattService( 5650): onClientRegistered() - UUID=7711d66a-4b40-4768-bd7b-5fcba50f2b36, clientIf=7
,D/BluetoothLeScanner(11750): onClientRegistered() - status=0 clientIf=7
,D/BtGatt.GattService( 5650): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startBlePeerDiscovery: OK
D/BtGatt.ScanManager( 5650): handling starting scan
,D/BtGatt.GattService( 5650): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
D/BtGatt.ScanManager( 5650): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager( 5650): allow scan with filters
D/BtGatt.ScanManager( 5650): client filter size is = 1available filters are = 13
D/BtGatt.ScanManager( 5650): set filter index= 12 for clientIf= 7
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(11750): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453205197492.11750","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11750): start: {"pi":"E0:DB:10:14:E2:C0","pn":"1453205197492.11750","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11750): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"1453205197492.11750","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/BtGatt.GattService( 5650): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 5650): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager( 5650): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager( 5650): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/BtGatt.ScanManager( 5650): :scan window =2000 Scan interval = 5000
D/WifiP2pService( 3523): InactiveState{ what=139292 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=139292 }
,D/WifiP2pService( 3523): P2pEnabledState add service
,D/WifiP2pService( 3523): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453205197492.11750
,I/io.jxcore.node.ConnectionHelper(11750): start: OK
,D/WifiP2pService( 3523): InactiveState{ what=139265 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=139265 }
,I/jxcore-log(11750): ok 63 Should be able to call startBroadcasting without error
I/jxcore-log(11750): 
D/WifiService( 3523): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3523): callSECApi what=74
D/WifiStateMachine( 3523): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
I/io.jxcore.node.ConnectionHelper(11750): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11750): shutdown
D/BluetoothSocket(11750): close() in, this: android.bluetooth.BluetoothSocket@323f0f3f, channel: 6, state: LISTENING
D/BluetoothSocket(11750): close() this: android.bluetooth.BluetoothSocket@323f0f3f, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1ae53412, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2538e00cmSocket: android.net.LocalSocket@2c33d55 impl:android.net.LocalSocketImpl@2e8f336a fd:FileDescriptor[118]
D/BluetoothSocket(11750): Closing mSocket: android.net.LocalSocket@2c33d55 impl:android.net.LocalSocketImpl@2e8f336a fd:FileDescriptor[118]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): setState: NOT_STARTED
D/WifiNative-HAL( 3523): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3834): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11750): Exiting thread
I/wpa_supplicant( 3834): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): onServerStopped
,D/WifiP2pService( 3523): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(11750): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11750): Local service added successfully
I/io.jxcore.node.ConnectionHelper(11750): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper(11750): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): stop: Stopping peer discovery...
,D/BtGatt.AdvertiseManager( 5650): message : 1
,D/WifiP2pService( 3523): InactiveState{ what=139268 }
D/BtGatt.AdvertiseManager( 5650): stop advertise for client 6
D/BtGatt.AdvertiseManager( 5650):  dualWaveClientIf = 0client.clientIf6
I/wpa_supplicant( 3834): P2P-FIND-STOPPED 
,D/BtGatt.AdvertiseManager( 5650): logClientsSet() - status: -1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): P2P device discovery stopped successfully
,D/BtGatt.GattService( 5650): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 5650): Client app is not null!
D/WifiP2pService( 3523): InactiveState{ what=147493 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3523): discovery change broadcast false
D/BtGatt.GattService( 5650): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): onIsAdvertiserStartedChanged: false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: RESTARTING
,D/BtGatt.GattService( 5650): stopScan() - queue size =1
W/bt-smp  ( 5650): Key(LSB ~ MSB) = 30 7e 01 64 39 c4 92 6c 13 df 24 1d 72 e8 19 7f 
W/bt-smp  ( 5650): Plain text(LSB ~ MSB) = 88 dd 61 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5650): Encrypted text(LSB ~ MSB) = 66 4d 90 c4 82 2e c0 69 43 8b 8f d9 b4 ad 3f 3c 
,D/BtGatt.ScanManager( 5650): filter size is 1
D/BtGatt.ScanManager( 5650): delete FilterIndex - 12
,D/BtGatt.GattService( 5650): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
D/WifiP2pService( 3523): InactiveState{ what=139268 }
D/BtGatt.ScanManager( 5650): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager( 5650): stop scan
D/BtGatt.ScanManager( 5650): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 5650): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
,D/BtGatt.ScanManager( 5650): configureRegularScanParams() - queue emtpy, scan stopped
,D/BtGatt.GattService( 5650): unregisterClient() - clientIf=7
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): onIsScannerStartedChanged: false
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11750): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(11750): release: No more listeners, de-initializing...
D/WifiP2pService( 3523): InactiveState{ what=139298 }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setState: NOT_STARTED
D/WifiP2pService( 3523): P2pEnabledState{ what=139298 }
,I/io.jxcore.node.ConnectionHelper(11750): onDiscoveryManagerStateChanged: NOT_STARTED
D/WifiP2pService( 3523): P2pEnabledState clear service
,I/jxcore-log(11750): ok 64 Should be able to call stopBroadcasting without error
I/jxcore-log(11750): 
,D/WifiP2pService( 3523): remove client information from framework
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11750): Local services cleared successfully
,D/WifiP2pService( 3523): InactiveState{ what=139268 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): P2P device discovery stopped successfully
,D/WifiP2pService( 3523): InactiveState{ what=139307 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3523): P2pEnabledState clear service request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11750): Service requests cleared successfully
,I/jxcore-log(11750): # setup
I/jxcore-log(11750): 
,I/jxcore-log(11750): # ThaliEmitter calls startBroadcasting twice with error
I/jxcore-log(11750): 
,I/wpa_supplicant( 3834): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3523): InactiveState{ what=147477 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3523): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3523): InactiveState{ what=139283 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3523): DefaultState{ what=139283 }
,D/WifiDisplayController( 3523): Received list of peers.
,D/WifiDisplayController( 3523):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,I/jxcore-log(11750): # teardown
I/jxcore-log(11750): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setDiscoveryMode: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453205201136.11750
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): initialize: My bluetooth address is E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(11750): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453205201136.11750","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter(11750): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(11750): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
D/BluetoothSocket(11750): bindListen(), new LocalSocket 
D/BluetoothSocket(11750): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(11750): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2e99f0f8
D/BluetoothSocket(11750): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): start: OK
I/io.jxcore.node.ConnectionHelper(11750): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper(11750): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11750): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453205201136.11750
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(11750): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(11750): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(11750): createAdvertiseData: From: 1453205201136.11750 b6a44ad1-d319-4b3a-815d-8b805a47fb51 E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(11750): E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(11750): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -32, -37, 16, 20, -30, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner(11750): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 5650): registerClient() - UUID=c427812e-9952-4f22-bd66-b392c5e368e8
,D/BtGatt.GattService( 5650): onClientRegistered() - UUID=c427812e-9952-4f22-bd66-b392c5e368e8, clientIf=6
,D/BluetoothLeAdvertiser(11750): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 5650): message : 0
,D/BtGatt.AdvertiseManager( 5650): number of adv instance running0
D/BtGatt.AdvertiseManager( 5650): size of list is =0
,D/BtGatt.AdvertiseManager( 5650): starting advertising
,D/BtGatt.AdvertiseManager( 5650): isDualWavefalse
,D/BtGatt.GattService( 5650): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 5650): starting multi advertising
,D/BtGatt.GattService( 5650): onAdvertiseDataSet() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 5650): logClientsSet() - status: 0
D/BtGatt.AdvertiseManager( 5650): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService( 5650): registerClient() - UUID=33cb773c-c81b-4a93-8d75-e43881156c56
,D/BtGatt.GattService( 5650): onClientRegistered() - UUID=33cb773c-c81b-4a93-8d75-e43881156c56, clientIf=7
,D/BluetoothLeScanner(11750): onClientRegistered() - status=0 clientIf=7
,D/BtGatt.GattService( 5650): start scan with filters
,D/BtGatt.ScanManager( 5650): handling starting scan
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startBlePeerDiscovery: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(11750): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453205201136.11750","ra":"E0:DB:10:14:E2:C0"}
,D/BtGatt.GattService( 5650): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,D/BtGatt.ScanManager( 5650): callback done for clientIf - 7 status - 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11750): start: {"pi":"E0:DB:10:14:E2:C0","pn":"1453205201136.11750","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11750): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"1453205201136.11750","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/BtGatt.ScanManager( 5650): allow scan with filters
,D/BtGatt.ScanManager( 5650): client filter size is = 1available filters are = 13
,D/BtGatt.ScanManager( 5650): set filter index= 13 for clientIf= 7
,D/BtGatt.GattService( 5650): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 5650): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager( 5650): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager( 5650): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,I/BtGatt.ScanManager( 5650): :scan window =2000 Scan interval = 5000
,D/WifiP2pService( 3523): InactiveState{ what=139292 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=139292 }
,D/WifiP2pService( 3523): P2pEnabledState add service
,D/WifiP2pService( 3523): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): start: Starting P2P device discovery...
,D/WifiP2pService( 3523): InactiveState{ what=139265 }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setState: RUNNING_BLE_AND_WIFI
D/WifiP2pService( 3523): P2pEnabledState{ what=139265 }
,D/WifiService( 3523): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3523): callSECApi what=74
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453205201136.11750
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startBlePeerDiscovery: Already running
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startBlePeerDiscovery: OK
I/io.jxcore.node.ConnectionHelper(11750): start: OK
,D/WifiStateMachine( 3523): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3523): callSECApiBoolean - ID [13]
I/wpa_supplicant( 3834): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(11750): onStartSuccess
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11750): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper(11750): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: STARTED
I/jxcore-log(11750): ok 65 Should be able to call startBroadcasting without error
I/jxcore-log(11750): 
,D/WifiP2pService( 3523): discovery change broadcast true
,D/WifiP2pService( 3523): InactiveState{ what=139268 }
I/wpa_supplicant( 3834): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): P2P device discovery stopped successfully
I/jxcore-log(11750): ok 66 Cannot call startBroadcasting twice
I/jxcore-log(11750): 
D/WifiP2pService( 3523): InactiveState{ what=147493 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=147493 }
I/io.jxcore.node.ConnectionHelper(11750): stop
D/WifiP2pService( 3523): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11750): shutdown
D/BluetoothSocket(11750): close() in, this: android.bluetooth.BluetoothSocket@2816c20d, channel: 6, state: LISTENING
D/BluetoothSocket(11750): close() this: android.bluetooth.BluetoothSocket@2816c20d, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2e99f0f8, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@23dec5c2mSocket: android.net.LocalSocket@1c277fd3 impl:android.net.LocalSocketImpl@35f5e710 fd:FileDescriptor[118]
D/BluetoothSocket(11750): Closing mSocket: android.net.LocalSocket@1c277fd3 impl:android.net.LocalSocketImpl@35f5e710 fd:FileDescriptor[118]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11750): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): stop: Stopping peer discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper(11750): onConnectionManagerStateChanged: NOT_STARTED
D/BtGatt.AdvertiseManager( 5650): message : 1
,D/BtGatt.AdvertiseManager( 5650): stop advertise for client 6
D/BtGatt.AdvertiseManager( 5650):  dualWaveClientIf = 0client.clientIf6
D/WifiP2pService( 3523): InactiveState{ what=139268 }
,D/BtGatt.AdvertiseManager( 5650): logClientsSet() - status: -1
,D/BtGatt.GattService( 5650): onAdvertiseInstanceDisabled() - clientIf=6, status=0
,D/BtGatt.GattService( 5650): Client app is not null!
,D/BtGatt.GattService( 5650): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 5650): stopScan() - queue size =1
,D/BtGatt.GattService( 5650): unregisterClient() - clientIf=7
D/BtGatt.ScanManager( 5650): filter size is 1
,D/BtGatt.ScanManager( 5650): delete FilterIndex - 13
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onIsBlePeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11750): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): stopWifiPeerDiscovery: Stopped
D/WifiP2pService( 3523): InactiveState{ what=139298 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(11750): release: No more listeners, de-initializing...
D/WifiP2pService( 3523): P2pEnabledState{ what=139298 }
D/WifiP2pService( 3523): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): release: No more listeners, de-initializing...
,W/bt-smp  ( 5650): Key(LSB ~ MSB) = 30 7e 01 64 39 c4 92 6c 13 df 24 1d 72 e8 19 7f 
W/bt-smp  ( 5650): Plain text(LSB ~ MSB) = 9d 3c 53 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5650): Encrypted text(LSB ~ MSB) = a6 63 00 8b 89 b9 47 26 a7 cf 0b 2c 3b 53 f1 59 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper(11750): onDiscoveryManagerStateChanged: NOT_STARTED
,D/WifiP2pService( 3523): remove client information from framework,
,I/jxcore-log(11750): ok 67 Should be able to call stopBroadcasting without error
I/jxcore-log(11750): 
D/BtGatt.GattService( 5650): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 5650): callback done for clientIf - 7 status - 0
,D/WifiP2pService( 3523): InactiveState{ what=139268 }
D/BtGatt.ScanManager( 5650): stop scan
D/BtGatt.ScanManager( 5650): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 5650): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
,D/BtGatt.ScanManager( 5650): configureRegularScanParams() - queue emtpy, scan stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11750): Local services cleared successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): P2P device discovery stopped successfully
D/WifiP2pService( 3523): InactiveState{ what=139307 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=139307 }
D/WifiP2pService( 3523): P2pEnabledState clear service request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11750): Service requests cleared successfully
,I/jxcore-log(11750): # setup
I/jxcore-log(11750): 
,I/PowerManagerService( 3523): [PWL] Off : 180s ago
,I/PowerManagerService( 3523): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService( 3523): [PWL]     mWakeLockSummary : 0x1,
,I/PowerManagerService( 3523): [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=5650, ws=null) (elapsedTime=435),
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 250, CUR = 43
,I/jxcore-log(11750): # ThaliEmitter throws on connection to bad peer
I/jxcore-log(11750): 
,I/jxcore-log(11750): # teardown
I/jxcore-log(11750): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setDiscoveryMode: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453205201966.11750
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): initialize: My bluetooth address is E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(11750): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453205201966.11750","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter(11750): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(11750): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
,D/BluetoothSocket(11750): bindListen(), new LocalSocket 
D/BluetoothSocket(11750): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(11750): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3ad77c0e
D/BluetoothSocket(11750): channel: 6
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): start: OK
I/io.jxcore.node.ConnectionHelper(11750): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper(11750): start: Using peer discovery mode: BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453205201966.11750
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(11750): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11750): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(11750): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(11750): createAdvertiseData: From: 1453205201966.11750 b6a44ad1-d319-4b3a-815d-8b805a47fb51 E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(11750): E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(11750): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -32, -37, 16, 20, -30, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner(11750): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 5650): registerClient() - UUID=b9d92263-8b2f-4e4a-b568-cf00ced3f14d
,D/BtGatt.GattService( 5650): onClientRegistered() - UUID=b9d92263-8b2f-4e4a-b568-cf00ced3f14d, clientIf=6
,D/BluetoothLeAdvertiser(11750): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 5650): message : 0
,D/BtGatt.AdvertiseManager( 5650): number of adv instance running0
,D/BtGatt.AdvertiseManager( 5650): size of list is =0
,D/BtGatt.AdvertiseManager( 5650): starting advertising
,D/BtGatt.AdvertiseManager( 5650): isDualWavefalse
,D/BtGatt.GattService( 5650): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 5650): starting multi advertising
,D/BtGatt.GattService( 5650): onAdvertiseDataSet() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 5650): logClientsSet() - status: 0
,D/BtGatt.AdvertiseManager( 5650): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService( 5650): registerClient() - UUID=8b6c26c5-d510-492d-91e3-e1576b674dbf
,D/BtGatt.GattService( 5650): onClientRegistered() - UUID=8b6c26c5-d510-492d-91e3-e1576b674dbf, clientIf=7
,D/BluetoothLeScanner(11750): onClientRegistered() - status=0 clientIf=7
,D/BtGatt.GattService( 5650): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startBlePeerDiscovery: OK
,D/BtGatt.ScanManager( 5650): handling starting scan
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(11750): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453205201966.11750","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11750): start: {"pi":"E0:DB:10:14:E2:C0","pn":"1453205201966.11750","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11750): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"1453205201966.11750","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/BtGatt.GattService( 5650): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
D/BtGatt.ScanManager( 5650): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager( 5650): allow scan with filters
D/BtGatt.ScanManager( 5650): client filter size is = 1available filters are = 13
D/BtGatt.ScanManager( 5650): set filter index= 14 for clientIf= 7
,D/BtGatt.GattService( 5650): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 5650): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager( 5650): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 5650): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/BtGatt.ScanManager( 5650): :scan window =2000 Scan interval = 5000
,D/WifiP2pService( 3523): InactiveState{ what=139292 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper(11750): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453205201966.11750
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startBlePeerDiscovery: OK
,D/WifiP2pService( 3523): P2pEnabledState{ what=139292 }
I/jxcore-log(11750): ok 68 Should be able to call startBroadcasting without error
I/jxcore-log(11750): 
,D/WifiP2pService( 3523): P2pEnabledState add service
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: OK
D/WifiP2pService( 3523): add a new client
I/io.jxcore.node.ConnectionHelper(11750): connect: Trying to connect to peer with ID foobar
W/io.jxcore.node.ConnectionHelper(11750): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(11750): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): onIsAdvertiserStartedChanged: true
E/io.jxcore.node.ConnectionHelper(11750): connect: Invalid Bluetooth address: foobar
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper(11750): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11750): Local service added successfully
,D/WifiP2pService( 3523): InactiveState{ what=139265 }
D/WifiP2pService( 3523): P2pEnabledState{ what=139265 }
,I/WifiStateMachine( 3523): callSECApi what=74
D/WifiService( 3523): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 3523): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3523): callSECApiBoolean - ID [13]
I/wpa_supplicant( 3834): USE_NETWORK : USE_NETWORK OFF
I/jxcore-log(11750): ok 69 Should not connect to a bad peer
I/jxcore-log(11750): 
,I/io.jxcore.node.ConnectionHelper(11750): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11750): shutdown
I/wpa_supplicant( 3834): p2p0: P2P: Reject scan trigger since one is already pending
,D/BluetoothSocket(11750): close() in, this: android.bluetooth.BluetoothSocket@cb5164b, channel: 6, state: LISTENING
D/BluetoothSocket(11750): close() this: android.bluetooth.BluetoothSocket@cb5164b, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3ad77c0e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1ee78828mSocket: android.net.LocalSocket@2b015941 impl:android.net.LocalSocketImpl@20afee6 fd:FileDescriptor[118]
D/BluetoothSocket(11750): Closing mSocket: android.net.LocalSocket@2b015941 impl:android.net.LocalSocketImpl@20afee6 fd:FileDescriptor[118]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11750): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): release: 1 listener(s) left
D/WifiP2pService( 3523): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): stop: Stopping peer discovery...
D/BtGatt.AdvertiseManager( 5650): message : 1
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: STARTED
,I/io.jxcore.node.ConnectionHelper(11750): onConnectionManagerStateChanged: NOT_STARTED
D/BtGatt.AdvertiseManager( 5650): stop advertise for client 6
D/BtGatt.AdvertiseManager( 5650):  dualWaveClientIf = 0client.clientIf6
D/WifiP2pService( 3523): InactiveState{ what=139268 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/BtGatt.AdvertiseManager( 5650): logClientsSet() - status: -1
I/wpa_supplicant( 3834): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): P2P device discovery stopped successfully
,D/WifiP2pService( 3523): InactiveState{ what=147493 }
D/WifiP2pService( 3523): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3523): discovery change broadcast false
D/BtGatt.GattService( 5650): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 5650): Client app is not null!
,D/BtGatt.GattService( 5650): unregisterClient() - clientIf=6
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: RESTARTING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): onIsAdvertiserStartedChanged: false
D/WifiP2pService( 3523): InactiveState{ what=139268 }
,D/BtGatt.GattService( 5650): stopScan() - queue size =1
D/BtGatt.ScanManager( 5650): filter size is 1
D/BtGatt.ScanManager( 5650): delete FilterIndex - 14
D/BtGatt.GattService( 5650): unregisterClient() - clientIf=7
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11750): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): stop: Stopping P2P device discovery...
W/bt-smp  ( 5650): Key(LSB ~ MSB) = 30 7e 01 64 39 c4 92 6c 13 df 24 1d 72 e8 19 7f 
W/bt-smp  ( 5650): Plain text(LSB ~ MSB) = 68 0c 6f 00 00 00 00 00 00 00 00 00 00 00 00 00 
D/WifiP2pService( 3523): InactiveState{ what=139298 }
,W/bt-smp  ( 5650): Encrypted text(LSB ~ MSB) = 99 1c c2 43 d5 66 27 d0 87 3b c6 cc 48 3d f5 22 
D/WifiP2pService( 3523): P2pEnabledState{ what=139298 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(11750): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setState: NOT_STARTED
D/WifiP2pService( 3523): P2pEnabledState clear service
,I/io.jxcore.node.ConnectionHelper(11750): onDiscoveryManagerStateChanged: NOT_STARTED
D/BtGatt.GattService( 5650): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 5650): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager( 5650): stop scan
D/BtGatt.ScanManager( 5650): configureRegularScanParams() - queue=0
,D/BtGatt.ScanManager( 5650): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 5650): configureRegularScanParams() - queue emtpy, scan stopped
,I/jxcore-log(11750): ok 70 Should be able to call stopBroadcasting without error
I/jxcore-log(11750): 
D/WifiP2pService( 3523): remove client information from framework
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11750): Local services cleared successfully
D/WifiP2pService( 3523): InactiveState{ what=139268 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): P2P device discovery stopped successfully
D/WifiP2pService( 3523): InactiveState{ what=139307 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=139307 }
D/WifiP2pService( 3523): P2pEnabledState clear service request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11750): Service requests cleared successfully
,I/jxcore-log(11750): # setup
I/jxcore-log(11750): 
,I/jxcore-log(11750): # ThaliEmitter throws on disconnect to bad peer
I/jxcore-log(11750): 
,I/jxcore-log(11750): # teardown
I/jxcore-log(11750): 
,I/wpa_supplicant( 3834): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-1 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1
,D/WifiP2pService( 3523): InactiveState{ what=147477 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3523): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3523): InactiveState{ what=139283 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3523): DefaultState{ what=139283 }
,D/WifiDisplayController( 3523): Received list of peers.
,D/WifiDisplayController( 3523):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3523):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setDiscoveryMode: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453205202610.11750
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): initialize: My bluetooth address is E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(11750): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453205202610.11750","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter(11750): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(11750): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
,D/BluetoothSocket(11750): bindListen(), new LocalSocket 
,D/BluetoothSocket(11750): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(11750): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2140fed4
D/BluetoothSocket(11750): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper(11750): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): start: OK
I/io.jxcore.node.ConnectionHelper(11750): start: Using peer discovery mode: BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11750): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453205202610.11750
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(11750): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(11750): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(11750): createAdvertiseData: From: 1453205202610.11750 b6a44ad1-d319-4b3a-815d-8b805a47fb51 E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory(11750): E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(11750): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -32, -37, 16, 20, -30, -64]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner(11750): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 5650): registerClient() - UUID=a9aa2f77-ef03-4ea6-9770-c674e5bf0ddc
,D/BtGatt.GattService( 5650): onClientRegistered() - UUID=a9aa2f77-ef03-4ea6-9770-c674e5bf0ddc, clientIf=6
,D/BluetoothLeAdvertiser(11750): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 5650): message : 0
,D/BtGatt.AdvertiseManager( 5650): number of adv instance running0
D/BtGatt.AdvertiseManager( 5650): size of list is =0
,D/BtGatt.AdvertiseManager( 5650): starting advertising
,D/BtGatt.AdvertiseManager( 5650): isDualWavefalse
,D/BtGatt.GattService( 5650): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 5650): starting multi advertising
,D/BtGatt.GattService( 5650): onAdvertiseDataSet() - clientIf=6, status=0
D/BtGatt.AdvertiseManager( 5650): logClientsSet() - status: 0
D/BtGatt.AdvertiseManager( 5650): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService( 5650): registerClient() - UUID=6e89191c-ad4f-421a-9493-d84bba1aab72
,D/BtGatt.GattService( 5650): onClientRegistered() - UUID=6e89191c-ad4f-421a-9493-d84bba1aab72, clientIf=7
,D/BluetoothLeScanner(11750): onClientRegistered() - status=0 clientIf=7
,D/BtGatt.GattService( 5650): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startBlePeerDiscovery: OK
,D/BtGatt.ScanManager( 5650): handling starting scan
,D/BtGatt.GattService( 5650): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,D/BtGatt.ScanManager( 5650): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager( 5650): allow scan with filters
,D/BtGatt.ScanManager( 5650): client filter size is = 1available filters are = 13
,D/BtGatt.ScanManager( 5650): set filter index= 15 for clientIf= 7
,D/BtGatt.GattService( 5650): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 5650): callback done for clientIf - 7 status - 0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(11750): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"1453205202610.11750","ra":"E0:DB:10:14:E2:C0"}
,D/BtGatt.ScanManager( 5650): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager( 5650): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11750): start: {"pi":"E0:DB:10:14:E2:C0","pn":"1453205202610.11750","ra":"E0:DB:10:14:E2:C0"}
,I/BtGatt.ScanManager( 5650): :scan window =2000 Scan interval = 5000
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11750): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"1453205202610.11750","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 3523): InactiveState{ what=139292 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=139292 }
,D/WifiP2pService( 3523): P2pEnabledState add service
,D/WifiP2pService( 3523): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): start: Starting P2P device discovery...
,D/WifiP2pService( 3523): InactiveState{ what=139265 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=139265 }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: OK
,D/WifiService( 3523): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setState: RUNNING_BLE_AND_WIFI
,I/WifiStateMachine( 3523): callSECApi what=74
D/WifiStateMachine( 3523): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: Peer ID: E0:DB:10:14:E2:C0, peer name: 1453205202610.11750
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startBlePeerDiscovery: Already running
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser(11750): onStartSuccess
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11750): Local service added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper(11750): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/io.jxcore.node.ConnectionHelper(11750): start: OK
D/WifiNative-HAL( 3523): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3834): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: STARTED
,I/jxcore-log(11750): ok 71 Should be able to call startBroadcasting without error
I/jxcore-log(11750): 
,D/WifiP2pService( 3523): discovery change broadcast true
,D/io.jxcore.node.ConnectionHelper(11750): disconnectOutgoingConnection: Trying to close connection to peer with ID foobar
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/WifiP2pService( 3523): InactiveState{ what=139268 }
,E/io.jxcore.node.ConnectionHelper(11750): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID foobar
,D/io.jxcore.node.ConnectionHelper(11750): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,W/io.jxcore.node.ConnectionHelper(11750): disconnectOutgoingConnection: Failed to disconnect (peer ID: foobar), either no such connection or failed to close the connection
,I/wpa_supplicant( 3834): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): P2P device discovery stopped successfully
,D/WifiP2pService( 3523): InactiveState{ what=147493 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3523): discovery change broadcast false
,I/jxcore-log(11750): ok 72 Disconnect should fail to a non-existant peer 
I/jxcore-log(11750): 
,I/io.jxcore.node.ConnectionHelper(11750): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11750): shutdown
D/BluetoothSocket(11750): close() in, this: android.bluetooth.BluetoothSocket@2126ef79, channel: 6, state: LISTENING
D/BluetoothSocket(11750): close() this: android.bluetooth.BluetoothSocket@2126ef79, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2140fed4, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2b2104bemSocket: android.net.LocalSocket@1575191f impl:android.net.LocalSocketImpl@1d7d546c fd:FileDescriptor[118]
D/BluetoothSocket(11750): Closing mSocket: android.net.LocalSocket@1575191f impl:android.net.LocalSocketImpl@1d7d546c fd:FileDescriptor[118]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11750): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11750): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11750): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper(11750): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: RESTARTING
,D/BtGatt.AdvertiseManager( 5650): message : 1
D/WifiP2pService( 3523): InactiveState{ what=139268 }
D/BtGatt.AdvertiseManager( 5650): stop advertise for client 6
D/BtGatt.AdvertiseManager( 5650):  dualWaveClientIf = 0client.clientIf6
,D/BtGatt.AdvertiseManager( 5650): logClientsSet() - status: -1
,D/BtGatt.GattService( 5650): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 5650): Client app is not null!
,D/BtGatt.GattService( 5650): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 5650): stopScan() - queue size =1
,D/BtGatt.ScanManager( 5650): filter size is 1
D/BtGatt.ScanManager( 5650): delete FilterIndex - 15
D/BtGatt.GattService( 5650): unregisterClient() - clientIf=7
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer(11750): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11750): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): stop: Stopping P2P device discovery...
D/WifiP2pService( 3523): InactiveState{ what=139298 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): setState: NOT_INITIALIZED
D/WifiP2pService( 3523): P2pEnabledState{ what=139298 }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): onIsWifiPeerDiscoveryStartedChanged: false
D/WifiP2pService( 3523): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(11750): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11750): release: No more listeners, de-initializing...
W/bt-smp  ( 5650): Key(LSB ~ MSB) = 30 7e 01 64 39 c4 92 6c 13 df 24 1d 72 e8 19 7f 
W/bt-smp  ( 5650): Plain text(LSB ~ MSB) = 4f 84 43 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5650): Encrypted text(LSB ~ MSB) = 9a fe c1 73 2b c5 3a 43 7b 83 d7 de aa fb 6b 40 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11750): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper(11750): onDiscoveryManagerStateChanged: NOT_STARTED
D/WifiP2pService( 3523): remove client information from framework
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11750): Local services cleared successfully
,D/WifiP2pService( 3523): InactiveState{ what=139268 }
I/jxcore-log(11750): ok 73 Should be able to call stopBroadcasting without error
I/jxcore-log(11750): 
,D/BtGatt.GattService( 5650): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 5650): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager( 5650): stop scan
,D/BtGatt.ScanManager( 5650): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 5650): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 5650): configureRegularScanParams() - queue emtpy, scan stopped,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11750): P2P device discovery stopped successfully
D/WifiP2pService( 3523): InactiveState{ what=139307 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=139307 }
D/WifiP2pService( 3523): P2pEnabledState clear service request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11750): Service requests cleared successfully
,I/jxcore-log(11750): # setup
I/jxcore-log(11750): 
,I/jxcore-log(11750): # #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available
I/jxcore-log(11750): 
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:40, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:41
D/BatteryService( 3523): stay LED for fully charged
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5650): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5650): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11750): # teardown
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 74 should be equal
I/jxcore-log(11750): 
,I/jxcore-log(11750): # setup
I/jxcore-log(11750): 
,I/jxcore-log(11750): # #startUpdateAdvertisingAndListening should use different USN after every invocation
I/jxcore-log(11750): 
,I/jxcore-log(11750): # teardown
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 75 should not be equal
I/jxcore-log(11750): 
,I/jxcore-log(11750): # setup
I/jxcore-log(11750): 
,I/jxcore-log(11750): # verify that Thali-specific messages are filtered correctly
I/jxcore-log(11750): 
,I/wpa_supplicant( 3834): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-1 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1
,D/WifiP2pService( 3523): InactiveState{ what=147477 },
,D/WifiP2pService( 3523): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3523): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3523): InactiveState{ what=139283 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3523): DefaultState{ what=139283 }
,D/WifiDisplayController( 3523): Received list of peers.
,D/WifiDisplayController( 3523):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3523):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,I/jxcore-log(11750): # teardown
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 76 irrelevant messages should be ignored
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 77 relevant messages should not be ignored
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 78 messages from this device should be ignored
I/jxcore-log(11750): 
,I/jxcore-log(11750): # setup
I/jxcore-log(11750): 
,I/jxcore-log(11750): # #start should fail if called twice in a row
I/jxcore-log(11750): 
,I/jxcore-log(11750): # teardown
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 79 specific error should be received
I/jxcore-log(11750): 
,I/jxcore-log(11750): # setup
I/jxcore-log(11750): 
,I/jxcore-log(11750): # #startUpdateAdvertisingAndListening should start hosting given router object
I/jxcore-log(11750): 
,I/jxcore-log(11750): # teardown
I/jxcore-log(11750): 
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 10589
,I/jxcore-log(11750): ok 80 server should respond with code 200
I/jxcore-log(11750): 
,I/jxcore-log(11750): # setup
I/jxcore-log(11750): 
,I/jxcore-log(11750): # #stop can be called multiple times in a row
I/jxcore-log(11750): 
,I/jxcore-log(11750): # teardown
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 81 should be in stopped state
I/jxcore-log(11750): 
,I/jxcore-log(11750): ok 82 should still be in stopped state
I/jxcore-log(11750): 
,I/jxcore-log(11750): Tests Complete
I/jxcore-log(11750): 
,I/chromium(11750): [INFO:CONSOLE(63)] "logCallback ------ Final results ---- ", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log(11750): Total: 0	Passed: 0	Failed: 0
I/jxcore-log(11750): 
,I/jxcore-log(11750): Toggling radios to false
I/jxcore-log(11750): 
,I/chromium(11750): [INFO:CONSOLE(63)] "logCallback Total: 0, Passed: 0, Failed: 0", source: file:///android_asset/www/js/thali_main.js (63)
,D/BluetoothAdapter(11750): disable()
,D/SettingsProvider( 3523): name = bluetooth_on
,I/WifiManager(11750): packageName : com.test.thalitest
,D/SecContentProvider( 3523): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3523): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3523): mCursor = null
,D/WifiService( 3523): setWifiEnabled: false pid=11750, uid=10589
,E/WifiService( 3523): Invoking mWifiStateMachine.setWifiEnabled
D/SettingsProvider( 3523): name = wifi_on
,D/BluetoothAdapterState( 5650): CURRENT_STATE=ON, MSG = USER_TURN_OFF
,D/BluetoothAdapterProperties( 5650): Setting state to 13
I/BluetoothAdapterState( 5650): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService( 5650): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 5650): updateAdapterState state is 13
,I/BluetoothPbapService( 5650): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,D/BluetoothAdapterService( 5650): Autoconnection is available 
D/BluetoothAdapterService( 5650): updateAdapterState prevState = 12newState = 13
D/BluetoothAdapterService( 5650): terminating service from this receiver
,D/BluetoothSocket( 5650): close() in, this: android.bluetooth.BluetoothSocket@278cacc9, channel: 19, state: LISTENING
D/BluetoothSocket( 5650): close() this: android.bluetooth.BluetoothSocket@278cacc9, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@265866b8, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2000ffcemSocket: android.net.LocalSocket@15b1deef impl:android.net.LocalSocketImpl@a82edfc fd:FileDescriptor[72]
D/BluetoothSocket( 5650): Closing mSocket: android.net.LocalSocket@15b1deef impl:android.net.LocalSocketImpl@a82edfc fd:FileDescriptor[72]
,D/BluetoothAdapterProperties( 5650): onBluetoothDisable()
,W/InputMethodManagerService( 3523): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 3523): [BT Setting State] State =13
,D/SecContentProvider( 3523): uri = 3 selection = isDiscoverableEnabled
,I/jxcore-log(11750): Radios toggled
I/jxcore-log(11750): 
I/BluetoothAdapterState( 5650): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,E/WifiStateMachine( 3523): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 3834): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3834): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3834): Skip scan - bUseNetwork false
,I/jxcore-log(11750): ****TEST TOOK:  ms ****
I/jxcore-log(11750): 
E/WifiStateMachine( 3523): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3523): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3523): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3523): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/jxcore-log(11750): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(11750): 
,D/BluetoothTile( 3692):  onBluetoothStateChange:
E/WifiStateMachine( 3523): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
D/BluetoothTile( 3692):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 3692): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 3692):  handleUpdatestate:false name:null
I/SamsungIME( 4500): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
E/WifiStateMachine( 3523): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3523): do suspend true
D/BluetoothTile( 3692):  handleUpdatestate:false name:null
D/STATUSBAR-QSTileView( 3692): onStateChanged: Bluetooth
D/StatusBarManagerService( 3523): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
V/BluetoothEventManager( 8752): Received android.bluetooth.adapter.action.STATE_CHANGED
,D/StatusBarManagerService( 3523): setIconVisibility slot=bluetooth visible=false
,D/PhoneStatusBar( 3692): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 )
,D/WifiP2pService( 3523): InactiveState{ what=143375 }
D/WifiP2pService( 3523): P2pEnabledState{ what=143375 }
,D/CommandListener( 2845): Clearing all IP addresses on wlan0
,V/NativeCrypto( 4626): Read error: ssl=0x9c419e00: I/O error during system call, Connection timed out
,D/BluetoothAdapterProperties( 5650): Scan Mode:20
,D/BluetoothAdapterState( 5650): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
E/bt-btif ( 5650): btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,V/NativeCrypto( 4626): SSL shutdown failed: ssl=0x9c419e00: I/O error during system call, Broken pipe
E/bt-btif ( 5650): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,E/bt-btif ( 5650): cmd socket is not created
,E/BtOppRfcommListener( 5650): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/bt-btm  ( 5650): btm_ble_start_auto_conn start : 0, 0
W/bt-btif ( 5650): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
W/bt-l2cap( 5650): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 5650): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 5650): L2CAP - PSM: 0x001b not found for deregistration
E/WifiStateMachine( 3523): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService( 3523): updateNetworkInfo()
D/ConnectivityService( 3523): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3523): updateNetworkInfo()
D/ConnectivityService( 3523): NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 3
D/btif_config_util( 5650): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,E/WifiConfigStore( 3523): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/WifiTrafficPoller( 3523): evaluateTrafficStatsPolling
,D/ConnectivityService( 3523): reportBadNetwork(NetworkAgentInfo [WIFI () - 503]) by 10014
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): ValidatedState{ when=-5ms what=532488 arg1=10014 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): DefaultState{ when=-6ms what=532488 arg1=10014 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,I/System.out( 3523): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 3523): Tagging socket 334 with tag ffffffff00000000{4294967295,0} uid 10014, pid: 3523, getuid(): 1000
,I/System.out( 3523): (HTTPLog)-Static: isSBSettingEnabled false
,W/ContextImpl( 8752): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,E/WifiStateMachine( 3523): scanCount==0 - aborting
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3692): applyOpen
,D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,I/jxcore-log(11750): Toggling radios to false
I/jxcore-log(11750): 
,D/ConnectivityService( 3523): notifyType LOST for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3523): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/EntConnectivity( 3523): Not allowed due to - mEnabled false
D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 0 for uid 1000
D/BluetoothAdapter(11750): disable()
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): Validated
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): ValidatedState{ when=-5ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 3523): [1,453,205,205,791 ms] noteScanEnd no scan source
,D/TelephonyNetworkFactory( 3977): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiP2pService( 3523): InactiveState{ what=131204 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=131204 }
,E/WifiStateMachine( 3523): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3523): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 3523): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3523): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 3523): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3523): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent( 3523): NetworkAgent: NetworkAgent channel lost
,D/ConnectivityManager.CallbackHandler( 3692): CM callback handler got msg 524292
,D/WifiP2pService( 3523): sending p2p connection changed broadcast: FAILED
,D/ConnectivityManager.CallbackHandler( 4760): CM callback handler got msg 524292
,D/BluetoothPbap( 8752): Proxy object disconnected
D/PbapServerProfile( 8752): Bluetooth service disconnected
D/WifiScanningService( 3523): SCAN_AVAILABLE : 1
D/WifiScanningService( 3523): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,D/RttService( 3523): SCAN_AVAILABLE : 1
,D/RttService( 3523): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker( 3523): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 3523): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=false
D/ConnectivityService( 3523): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/WifiDisplayController( 3523): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,E/BluetoothManagerService( 3523): Bluetooth is already disabled. DO NOT disable again.
,I/WifiManager(11750): packageName : com.test.thalitest
D/SecContentProvider( 3523): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3523): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3523): mCursor = null
D/WifiService( 3523): setWifiEnabled: false pid=11750, uid=10589
E/WifiService( 3523): Invoking mWifiStateMachine.setWifiEnabled
D/SettingsProvider( 3523): name = wifi_on
E/WifiController( 3523): illegal state found both WifiController and WifiStateMachine
I/jxcore-log(11750): Radios toggled
I/jxcore-log(11750): 
D/WifiDisplayController( 3523): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter( 3523): onP2pDisconnected
D/IpRemoteDisplayController( 3523): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 3523): WfdBridgeServer is already null
D/WifiP2pService( 3523): sending p2p connection changed broadcast: DISCONNECTED
D/DockEventReceiver( 8752): finishStartingService: stopping service
D/EntConnectivity( 3523): Not allowed due to - mEnabled false
D/WifiP2pService( 3523): P2pDisablingState
D/WifiP2pService( 3523): P2pDisablingState{ what=147458 }
D/WifiP2pService( 3523): p2p socket connection lost
D/ConnectivityService( 3523): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
E/ConnectivityService( 3523): updateNetworkInfo()
D/ConnectivityService( 3523): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3523): updateNetworkInfo()
D/WifiP2pService( 3523): P2pDisabledState
D/WifiP2pService( 3523): P2pDisabledState{ what=139283 }
D/WifiP2pService( 3523): DefaultState{ what=139283 }
E/WifiStateMachine( 3523): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - enter - invokeEnterMethods
E/WifiStateMachine( 3523): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine( 3523): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
E/WifiStateMachine( 3523): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3523): do suspend true
D/WifiDisplayController( 3523): Received list of peers.
D/WifiDisplayController( 3523): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController( 3523): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/Tethering( 3523): MasterInitialState.processMessage what=3
D/SmartBondingService( 3523): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/WifiDisplayController( 3523): disconnect
D/WifiDisplayController( 3523): updateConnection
D/SmartBondingService( 3523): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/WifiDisplayController( 3523): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/WifiDisplayAdapter( 3523): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,V/NetworkStats( 3523): updateIfacesLocked()
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
V/NetworkStats( 3523): performPollLocked(flags=0x1)
,D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): 0
D/WifiP2pService( 3523): P2pDisabledState{ what=143375 }
D/WifiP2pService( 3523): DefaultState{ what=143375 }
,D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3692): updateDataNetType()
D/StatusBar.NetworkController( 3692): NoService, mRoamingIconId = 0
D/NetworkStatsFactory( 3523): UpdateStatsForKnox
E/StatusBar.NetworkController( 3692): updateLTEICONDataNetType:0
D/SmartBondingService( 3523): getNetworkEnabled : wifi : true mobile : false
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
V/NetworkStats( 3523): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 3692): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 3692): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3692): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,V/NetworkStats( 3523): performPollLocked() took 14ms
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/WifiDisplayController( 3523): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter( 3523): onP2pDisconnected
D/IpRemoteDisplayController( 3523): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 3523): WfdBridgeServer is already null
,D/CommandListener( 2845): Clearing all IP addresses on wlan0
,D/BluetoothSocket( 5650): close() in, this: android.bluetooth.BluetoothSocket@2b2a4c85, channel: 5, state: LISTENING
,D/BluetoothSocket( 5650): close() this: android.bluetooth.BluetoothSocket@2b2a4c85, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2d3ffc91, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@38314adamSocket: android.net.LocalSocket@30677b0b impl:android.net.LocalSocketImpl@190eede8 fd:FileDescriptor[74]
D/BluetoothSocket( 5650): Closing mSocket: android.net.LocalSocket@30677b0b impl:android.net.LocalSocketImpl@190eede8 fd:FileDescriptor[74]
I/BtOppRfcommListener( 5650): stopping Accept Thread
D/BluetoothSocket( 5650): close() in, this: android.bluetooth.BluetoothSocket@21482c01, channel: 12, state: LISTENING
D/BluetoothSocket( 5650): close() this: android.bluetooth.BluetoothSocket@21482c01, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@34d554d0, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@32e93aa6mSocket: android.net.LocalSocket@3f90bce7 impl:android.net.LocalSocketImpl@2bd90094 fd:FileDescriptor[77]
,D/BluetoothSocket( 5650): Closing mSocket: android.net.LocalSocket@3f90bce7 impl:android.net.LocalSocketImpl@2bd90094 fd:FileDescriptor[77]
I/BtOppRfcommListener( 5650): BluetoothSocket listen thread finished
,E/WifiStateMachine( 3523): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/AllShareCastTile( 3692): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,D/WifiDisplayAdapter( 3523): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/AllShareCastTile( 3692): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3523): stopping supplicant
,I/wpa_supplicant( 3834): p2p0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine( 3523): setWifiState: disabling
,I/WifiTrafficPoller( 3523): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
,D/SmartBondingService( 3523): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,D/SLocation( 3523): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,D/SecContentProvider2( 3523): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3523): mCursor = null
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/SmartBondingService( 3523): getNetworkEnabled : wifi : false mobile : false
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/STATUSBAR-WifiQuickSettingButton( 3692): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 3692): Wifi onReceive(0)
,D/HotspotTile( 3692): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-QSTileView( 3692): onStateChanged: Wi-Fi
D/HotspotTile( 3692): onReceive : 0, 0
,D/BluetoothNotiBroadcastReceiver( 8752): onReceive
,E/WifiStateMachine( 3523): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3523): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/AuthorizationBluetoothService( 4626): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/Hs20UtilService( 4112): Starting #14
,I/Hs20UtilService( 4112): Message received 5007
,D/NearbySettings( 8752): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8752): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8752): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8752): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 8752): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8752): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8752): MountReceiver.mPrefHandler - 7002
,W/bt-l2cap( 5650): btif_mce_execute_service enable:0
,W/bt-l2cap( 5650): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 5650): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 5650): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 5650): L2CAP - PSM: 0x0017 not found for deregistration
D/bt_userial( 5650): RX termination
W/bt-l2cap( 5650): L2CAP - PSM: 0x001b not found for deregistration
W/bt_userial( 5650): select_read return size <=0:-1, exiting userial_read_thread
W/bt-l2cap( 5650): L2CAP - PSM: 0x0019 not found for deregistration
D/bt_userial( 5650): Leaving userial_read_thread()
,W/bt-l2cap( 5650): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 5650): L2CAP - PSM: 0x001b not found for deregistration
W/bt-btif ( 5650): ag scb idx 1 not allocated
W/bt-btif ( 5650): ag scb idx 2 not allocated
E/bt-btif ( 5650): BTA AG is already disabled, ignoring ...
D/bt_userial( 5650): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg( 5650): hw_epilog_process
I/bt_userial_vendor( 5650): device fd = 65 close
,I/GKI_LINUX( 5650): gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX( 5650): GKI_exit_task 0 done
I/GKI_LINUX( 5650): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 5650): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BtConfig.SecureMode( 5650): isSecureModeOn:false
D/BluetoothAdapterService( 5650): mProfilesStarted : true supportedProfileServices.length : 12
W/BluetoothAdapterService( 5650): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 5650): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 5650): Not skipping com.android.bluetooth.gatt.GattService
,I/SignOutReceiver(11363): NETWORK_STATE_CHANGED_ACTION
,W/BluetoothAdapterService( 5650): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,D/BtSettings.ProfileConfig( 5650): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/BtGatt.DebugUtils( 5650): handleDebugAction() action=null
,D/FileWriteThread_Telephony( 3977): FileWriteThread : threadType = 3
W/BluetoothAdapterService( 5650): Not skipping com.android.bluetooth.hfp.HeadsetService
,D/BtGatt.GattService( 5650): Received stop request...Stopping profile...
D/BtGatt.GattService( 5650): stop()
D/BtGatt.AdvertiseManager( 5650): advertise clients cleared
,D/FileWriteThread_Telephony( 3977): FileWriteThread : threadType = 3
,D/NearbySettings( 8752): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/FileWriteThread_Telephony( 3977): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3977): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3977): FileWriteThread : threadType = 3
W/BluetoothAdapterService( 5650): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 5650): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,D/FileWriteThread_Telephony( 3977): FileWriteThread : threadType = 3
D/BluetoothAdapterService( 5650): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bec4f09
,V/NearbySettings( 8752): DMSUtil.isNetworkConnected - flag-null, state-null
D/HeadsetService( 5650): Received stop request...Stopping profile...
,W/BluetoothAdapterService( 5650): Not skipping com.android.bluetooth.a2dp.A2dpService
,D/BluetoothAdapterService( 5650): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bec4f09
I/NearbySettings( 8752): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/FileWriteThread_Telephony( 3977): FileWriteThread : threadType = 3
W/BluetoothAdapterService( 5650): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5650): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,D/AudioService( 3523): onServiceDisconnected: Bluetooth profile: 1
D/FileWriteThread_Telephony( 3977): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3977): FileWriteThread : threadType = 3
,W/BluetoothAdapterService( 5650): Not skipping com.android.bluetooth.hid.HidService
D/FileWriteThread_Telephony( 3977): FileWriteThread : threadType = 3
I/NearbySettings( 8752): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 8752): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8752): MountReceiver.onReceive - Set preference state off
D/FileWriteThread_Telephony( 3977): FileWriteThread : threadType = 3
,W/BluetoothAdapterService( 5650): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 5650): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
D/FileWriteThread_Telephony( 3977): FileWriteThread : threadType = 3
V/NearbySettings( 8752): MountReceiver.mPrefHandler - 7002
W/BluetoothAdapterService( 5650): Not skipping com.android.bluetooth.hdp.HealthService
,D/HeadsetProfile( 8752): Bluetooth service disconnected
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
I/wpa_supplicant( 3834): Blacklist: Clear (all) 
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12855): MountEmulatedStorage()
I/libpersona(12855): KNOX_SDCARD checking this for 10079
E/Zygote  (12855): v2
I/libpersona(12855): KNOX_SDCARD not a persona
,I/SELinux (12855): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3523): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=12855 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/BluetoothAdapterService( 5650): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 5650): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,I/SELinux (12855): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,W/BluetoothAdapterService( 5650): Not skipping com.android.bluetooth.pan.PanService
,E/SELinux (12855): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/BluetoothAdapterService( 5650): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 5650): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 5650): Not skipping com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 5650): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 5650): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 5650): Not skipping com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 5650): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 5650): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService( 5650): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 5650): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 5650): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,I/wpa_supplicant( 3834): p2p0: CTRL-EVENT-TERMINATING 
W/BluetoothAdapterService( 5650): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 5650): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 5650): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 5650): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 5650): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 5650): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService( 5650): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
D/BluetoothAdapterState( 5650): Stopping profile services that were post enabled
E/BluetoothAdapterService(1005342473)( 5650): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
E/BluetoothAdapterService(1005342473)( 5650): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5650): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 5650): Profile still running: com.android.bluetooth.hid.HidService
,D/A2dpService( 5650): Received stop request...Stopping profile...
V/Avrcp   ( 5650): doQuit
D/A2dpStateMachine( 5650): Exit Disconnected: -1
,I/wpa_supplicant( 3834): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3834): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 3834): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3834): wlan0: State: DISCONNECTED -> DISCONNECTED
D/Avrcp   ( 5650): Unregistering previous receiver
,D/BluetoothAdapterService( 5650): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bec4f09
,D/BluetoothA2dp( 5025): Proxy object disconnected
D/TimaKeyStoreProvider(12855): TimaSignature is unavailable
,D/BluetoothA2dp( 3523): Proxy object disconnected
D/ActivityThread(12855): Added TimaKeyStore provider
D/BluetoothA2dp( 8752): Proxy object disconnected
,D/A2dpProfile( 8752): Bluetooth service disconnected
D/AudioService( 3523): onServiceDisconnected: Bluetooth profile: 2
,D/AndroidRuntime(12830): 
D/AndroidRuntime(12830): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,W/BluetoothHeadsetServiceJni( 5650): Cleaning up Bluetooth Handsfree Interface...
,W/BluetoothHeadsetServiceJni( 5650): Cleaning up Bluetooth Handsfree callback object
D/HidService( 5650): Received stop request...Stopping profile...
D/HidService( 5650): Stopping Bluetooth HidService
W/BluetoothHidServiceJni( 5650): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 5650): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 5650): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 5650): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bec4f09
,D/BluetoothInputDevice( 8752): Proxy object disconnected
D/HidProfile( 8752): Bluetooth service disconnected
D/AndroidRuntime(12830): CheckJNI is OFF
,D/AndroidRuntime(12830): readGMSProperty: start
D/AndroidRuntime(12830): readGMSProperty: already setted!!
D/HealthService( 5650): Received stop request...Stopping profile...
D/BluetoothAdapterService( 5650): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bec4f09
,D/AndroidRuntime(12830): readGMSProperty: end
D/AndroidRuntime(12830): addProductProperty: start
,D/PanService( 5650): Received stop request...Stopping profile...
D/BluetoothAdapterService( 5650): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bec4f09
,D/ResourcesManager(12855): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
D/BluetoothPan( 3523): BluetoothPAN Proxy object disconnected
D/BluetoothPan( 8752): BluetoothPAN Proxy object disconnected
D/PanProfile( 8752): Bluetooth service disconnected
,D/BluetoothMapService( 5650): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 5650): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bec4f09
,D/BluetoothMap( 8752): Proxy object disconnected
D/MapProfile( 8752): Bluetooth service disconnected
,D/SapService( 5650): Received stop request...Stopping profile...
D/SapService( 5650): Stopping Bluetooth SapService
D/BluetoothAdapterService( 5650): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bec4f09
,E/BluetoothAdapterService(1005342473)( 5650): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5650): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 5650): Profile still running: com.android.bluetooth.hid.HidService
D/Bluetoothsap( 8752): BluetoothSAP Proxy object disconnected
D/BluetoothA2dp( 5650): Proxy object disconnected
D/SapProfile( 8752): Bluetooth service disconnected
D/BluetoothAdapterService( 5650): Bluetooth A2dp source service disconnected
I/GKI_LINUX( 5650): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 5650): GKI_exit_task 2 done
I/GKI_LINUX( 5650): GKI_shutdown(): task [A2DP-MEDIA] terminated
V/Avrcp   ( 5650): cleanup
,E/BluetoothAdapterService(1005342473)( 5650): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5650): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 5650): Profile still running: com.android.bluetooth.map.BluetoothMapService
E/BluetoothAdapterService(1005342473)( 5650): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5650): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 5650): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni( 5650): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 5650): Cleaning up Bluetooth Health object
,E/BluetoothAdapterService(1005342473)( 5650): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5650): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 5650): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 5650): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 5650): Cleaning up Bluetooth PAN callback object
,D/FileShare-Server(12855): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
E/BluetoothAdapterService(1005342473)( 5650): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5650): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 5650): Profile still running: com.broadcom.bt.service.sap.SapService
E/BluetoothAdapterService(1005342473)( 5650): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,W/BluetoothSAPServiceJni( 5650): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 5650): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
D/BluetoothAdapterState( 5650): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 5650): Setting state to 10
I/BluetoothAdapterState( 5650): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 5650): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 5650): updateAdapterState state is 10
D/BluetoothAdapterService( 5650): Autoconnection is available 
D/BluetoothAdapterService( 5650): updateAdapterState prevState = 13newState = 10
I/BluetoothAdapterState( 5650): Entering OffState
,D/BluetoothMap( 8752): onBluetoothStateChange: up=false
,I/ActivityManager( 3523): Killing 11472:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
,D/Bluetoothsap( 8752): onBluetoothStateChange: up=false
D/Bluetoothsap( 8752): Unbinding service...
,I/Hs20UtilService( 4112): Starting #15
D/BluetoothA2dp( 3523): onBluetoothStateChange: up=false
,I/Hs20UtilService( 4112): Message received 5007
,D/NearbySettings( 8752): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8752): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8752): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/BluetoothA2dp( 5650): onBluetoothStateChange: up=false
I/NearbySettings( 8752): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 8752): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8752): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8752): MountReceiver.mPrefHandler - 7002
D/BluetoothA2dp( 8752): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 5025): onBluetoothStateChange: up=false
,I/SignOutReceiver(11363): NETWORK_STATE_CHANGED_ACTION
,D/BluetoothInputDevice( 8752): onBluetoothStateChange: up=false
,D/BluetoothPbap( 8752): onBluetoothStateChange: up=false
,I/Hs20UtilService( 4112): Starting #16
,I/Hs20UtilService( 4112): Message received 5011
,I/wpa_supplicant( 3834): Blacklist: Clear (all) 
,D/KeyguardWallpaperUpdator(12119): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12119): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12119): stopCheckCategoryVersion
,D/BluetoothManagerService( 3523): Broadcasting onBluetoothServiceDown() to 11 receivers.
,I/SignOutReceiver(11363): WIFI_STATE_CHANGED_ACTION
D/BluetoothManagerService( 3523): Broadcasting onBluetoothServiceUp() to 0 receivers.
,W/InputMethodManagerService( 3523): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 3523): [BT Setting State] State =10
I/InputMethodManagerService( 3523): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,D/BluetoothAdapter( 3692): 8964651: getState() :  mService = null. Returning STATE_OFF
D/BluetoothTile( 3692):  onBluetoothPairedDevicesChanged:
D/BluetoothAdapter( 3692): 8964651: getState() :  mService = null. Returning STATE_OFF
D/BluetoothTile( 3692): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothAdapter( 3692): 8964651: getState() :  mService = null. Returning STATE_OFF
D/STATUSBAR-QSTileView( 3692): onStateChanged: Bluetooth
,D/BluetoothAdapter( 3692): 8964651: getState() :  mService = null. Returning STATE_OFF
,I/SamsungIME( 4500): STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
D/BluetoothAdapter( 3692): 8964651: getState() :  mService = null. Returning STATE_OFF
D/StatusBarManagerService( 3523): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
D/StatusBarManagerService( 3523): setIconVisibility slot=bluetooth visible=false
V/BluetoothEventManager( 8752): Received android.bluetooth.adapter.action.STATE_CHANGED
D/PhoneStatusBar( 3692): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 )
D/BluetoothAdapter( 4626): 391585438: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 4626): 391585438: getState() :  mService = null. Returning STATE_OFF
,E/AffinityControl(12830): AffinityControl: registerfunction enter
,I/GKI_LINUX( 5650): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 5650): GKI_exit_task 1 done
I/GKI_LINUX( 5650): GKI_shutdown(): task [BTIF] terminated
,I/BluetoothServiceJni( 5650): cleanupNative: return from cleanup
,I/art     ( 5650): System.exit called, status: 0
I/AndroidRuntime( 5650): VM exiting with result code 0, cleanup skipped.
,D/AndroidRuntime(12830): Calling main entry com.android.commands.pm.Pm
,D/PackageManager( 3523): START PACKAGE DELETE: observer{630012121}
D/PackageManager( 3523): pkg{<packageName>}
D/PackageManager( 3523): user{0}
D/PackageManager( 3523): caller{2000}
D/PackageManager( 3523): flags{3}
D/PersonaManagerService( 3523): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService( 3523): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3523): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3523): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3523): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 3523): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 3523): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 3523): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 3523): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3523): getApplicationUninstallationEnabled :  enabled true
W/ContextImpl( 8752): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/PackageManager( 3523): !@killApplicatoin: 10589, uninstall pkg
I/ActivityManager( 3523): Force stopping com.test.thalitest appid=10589 user=-1: uninstall pkg
I/ActivityManager( 3523): Killing 11750:com.test.thalitest/u0a589 (adj 0): stop com.test.thalitest
,I/ActivityManager( 3523):   Force finishing activity ActivityRecord{2f3513e2 u0 com.test.thalitest/.MainActivity t26}
,W/ActivityManager( 3523): mDVFSHelper.acquire()
,W/PackageSettings( 3523): Skipping PackageSetting{64ace28 com.example.hello/10563} due to missing metadata
,D/WifiService( 3523): Client connection lost with reason: 4
,I/WindowState( 3523): WIN DEATH: Window{2192e278 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger( 2849): id=14 Removed NainActivit (5/8)
I/SurfaceFlinger( 2849): id=14 Removed NainActivit (-2/8)
,I/SurfaceFlinger( 2849): id=14 Removed NainActivit (-2/8)
,D/PointerIcon( 3523): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 3523): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3523): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3523): setHoveringSpenCustomIcon IconType is same.1
,I/ActivityManager( 3523): Process com.android.bluetooth (pid 5650)(adj 0) has died(244,1199)
,I/ActivityManager( 3523): Force stopping com.test.thalitest appid=10589 user=0: pkg removed
,I/ActivityManager( 3523):   Force finishing activity ActivityRecord{2f3513e2 u0 com.test.thalitest/.MainActivity t26 f}
W/ActivityManager( 3523): Duplicate finish request for ActivityRecord{2f3513e2 u0 com.test.thalitest/.MainActivity t26 f}
,D/ConnectivityService( 3523): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 6239): [com.wssyncmldm.ui.XUIInstallConfirmActivity(456/onResume)] 
,I/DBG_DM  ( 6239): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 10
,I/art     ( 8810): Explicit concurrent mark sweep GC freed 31653(1743KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.151ms total 48.716ms
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/art     ( 4055): Explicit concurrent mark sweep GC freed 33225(2037KB) AllocSpace objects, 1(39KB) LOS objects, 21% free, 28MB/36MB, paused 1.341ms total 46.832ms
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,D/DockEventReceiver( 8752): finishStartingService: stopping service
,I/art     ( 4760): Explicit concurrent mark sweep GC freed 28160(1592KB) AllocSpace objects, 3(48KB) LOS objects, 20% free, 31MB/39MB, paused 1.480ms total 79.405ms
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/DBG_DM  ( 6239): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,E/SamsungIME( 4500): mOCRHelper is null
,I/DBG_DM  ( 6239): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6239): [com.wssyncmldm.ui.XUIInstallConfirmActivity(466/onResume)] Postpone Count : 10
,W/GeofencerStateMachine( 4626): Ignoring removeGeofence because network location is disabled.
,I/DBG_DM  ( 6239): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,D/LWLocationManager(11450): getDeviceLocationId :  id = -100
,D/LocationWidgetApplication(11450): getLastUiLocationId() : mLastUiLocationId = -100
,I/DBG_DM  ( 6239): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/InputReader( 3523): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/talkback/talkback.apk
,I/NetworkMonitor(11906): type=WIFI subType= reason=null isConnected=false
,W/ResourceType( 5364): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5364): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/EnterpriseDeviceManagerService( 3523): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3523): Admin package name: com.google.android.gms
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager(11450): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,I/wpa_supplicant( 3834): wlan0: CTRL-EVENT-TERMINATING 
,E/WifiStateMachine( 3523): Supplicant connection lost
,I/DBG_DM  ( 6239): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/Tethering( 3523): InitialState.processMessage what=4
,D/SecContentProvider2( 3523): uri = 14 selection = getSealedState
D/SecContentProvider2( 3523): mCursor = null
,E/Tethering( 3523): No numeric data
,I/art     ( 3523): Explicit concurrent mark sweep GC freed 67507(4MB) AllocSpace objects, 49(832KB) LOS objects, 24% free, 49MB/65MB, paused 2.946ms total 210.056ms
I/art     ( 3523): WaitForGcToComplete blocked for 209.037ms for cause Explicit
D/ResourcesManager( 3523): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(11450): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/BluetoothNotiBroadcastReceiver( 8752): onReceive
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ApplicationPolicy( 3523): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
E/WifiStateMachine( 3523): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
V/ApplicationPolicy( 3523): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/WifiNative-HAL( 3523): callSECApiBoolean - ID [21]
,E/WifiStateMachine( 3523): setWifiState: disabled
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12889): MountEmulatedStorage()
I/libpersona(12889): KNOX_SDCARD checking this for 1002
E/Zygote  (12889): v2
I/libpersona(12889): KNOX_SDCARD not a persona
I/SELinux (12889): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3523): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=12889 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
I/SELinux (12889): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12889): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 6239): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 10
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/SecContentProvider2( 3523): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 3523): mCursor = null
I/DBG_DM  ( 6239): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,I/DBG_DM  ( 6239): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
D/Tethering( 3523): sendTetherStateChangedBroadcast 0, 0, 0
,I/DBG_DM  ( 6239): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 6239): [llIIlIIlIllIllIlllII(376/llIIllllIIlllIIIIlll)] 
,I/DBG_DM  ( 6239): [IIlIIIlllllIIlIIIlII(339/llllIlIIIllllIIlIlll)] No need to check encryption status
,I/DBG_DM  ( 6239): [llIIlIIlIllIllIlllII(405/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=false enabledDesc:null
D/STATUSBAR-WifiQuickSettingButton( 3692): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 3692): Wifi onReceive(1)
,D/STATUSBAR-QSTileView( 3692): onStateChanged: Wi-Fi
D/HotspotTile( 3692): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/HotspotTile( 3692): onReceive : 1, 0
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
V/NetworkStats( 3523): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 3523): UpdateStatsForKnox
,D/HotspotTile( 3692): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 3692): updateTetherState():false, false
,V/NetworkStats( 3523): performPollLocked() took 6ms
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
,D/TimaKeyStoreProvider(12889): TimaSignature is unavailable
,D/ActivityThread(12889): Added TimaKeyStore provider
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(11450): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ActivityManager( 3523): post active user change for 0
,D/KnoxTimeoutHandler( 3523): postActiveUserChange for user 0
,I/DBG_DM  ( 6239): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/Settings( 4626): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
,I/SurfaceFlinger( 2849): id=16 createSurf (1440x2560),2 flag=404, YUIInstallC
,D/StatusBarManagerService( 3523): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3523): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/RegisteredServicesCache( 3965): empty dynamic service
,D/PointerIcon( 3523): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3523): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3523): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3523): setHoveringSpenCustomIcon IconType is same.1
,I/DBG_DM  ( 6239): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,D/ResourcesManager(12889): creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
,I/DBG_DM  ( 6239): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,D/ResourcesManager(11450): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager(12889): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,W/ResourcesManager(12889): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,V/ActivityThread( 6239): updateVisibility : ActivityRecord{3b0e6dfe token=android.os.BinderProxy@c224083 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(11450): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,D/ResourcesManager(11450): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(11450): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,I/BluetoothA2dpSinkServiceJni(12889): register_com_android_bluetooth_a2dp_sink
,D/BtSettings.ProfileConfig(12889): Adding GattService
D/BtSettings.ProfileConfig(12889): Adding HeadsetService
D/BtSettings.ProfileConfig(12889): Adding A2dpService
D/BtSettings.ProfileConfig(12889): Adding HidService
,D/BtSettings.ProfileConfig(12889): Adding HealthService
D/BtSettings.ProfileConfig(12889): Adding PanService
D/BtSettings.ProfileConfig(12889): Adding BluetoothMapService
D/BtSettings.ProfileConfig(12889): Adding SapService
D/BtSettings.ProfileConfig(12889): Adding HeadsetClientService
D/BtSettings.ProfileConfig(12889): Adding A2dpSinkService
D/BtSettings.ProfileConfig(12889): Adding SapClientService
D/BtSettings.ProfileConfig(12889): Adding HidDevService
,I/BtSettings.ProfileConfig(12889): *********Initializing Bluetooth Profile Settings*******
,D/SettingsProvider( 3523): name = bt_svcst_com.android.bluetooth.gatt.GattService
D/SettingsProvider( 3523): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3523): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3523): selectionArgs: false
D/SettingsProvider( 3523): selectionArgs: 1002
D/SecContentProvider( 3523): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3523): ret = -1
I/art     ( 3523): Explicit concurrent mark sweep GC freed 12324(632KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 49MB/65MB, paused 2.363ms total 210.397ms
,D/SettingsProvider( 3523): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/SettingsProvider( 3523): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3523): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3523): selectionArgs: false
D/SettingsProvider( 3523): selectionArgs: 1002
D/SecContentProvider( 3523): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3523): ret = -1
,D/SettingsProvider( 3523): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
D/SettingsProvider( 3523): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3523): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3523): selectionArgs: false
D/SettingsProvider( 3523): selectionArgs: 1002
D/SecContentProvider( 3523): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3523): ret = -1
,D/SettingsProvider( 3523): name = bt_svcst_com.android.bluetooth.hid.HidService
D/SettingsProvider( 3523): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3523): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3523): selectionArgs: false
D/SettingsProvider( 3523): selectionArgs: 1002
D/ResourcesManager(11450): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
D/SecContentProvider( 3523): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3523): ret = -1
,D/InputMethodManagerService( 3523): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/SettingsProvider( 3523): name = bt_svcst_com.android.bluetooth.hdp.HealthService
D/SettingsProvider( 3523): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3523): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3523): selectionArgs: false
D/SettingsProvider( 3523): selectionArgs: 1002
D/SecContentProvider( 3523): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3523): ret = -1
,D/SettingsProvider( 3523): name = bt_svcst_com.android.bluetooth.pan.PanService
D/SettingsProvider( 3523): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3523): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3523): selectionArgs: false
D/SettingsProvider( 3523): selectionArgs: 1002
D/SecContentProvider( 3523): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3523): ret = -1
,D/SettingsProvider( 3523): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
D/SettingsProvider( 3523): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3523): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3523): selectionArgs: false
D/SettingsProvider( 3523): selectionArgs: 1002
D/SecContentProvider( 3523): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3523): ret = -1
,D/ResourcesManager(11450): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/SettingsProvider( 3523): name = bt_svcst_com.broadcom.bt.service.sap.SapService
D/SettingsProvider( 3523): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3523): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3523): selectionArgs: false
D/SettingsProvider( 3523): selectionArgs: 1002
,D/SecContentProvider( 3523): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3523): ret = -1
D/SettingsProvider( 3523): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
D/SettingsProvider( 3523): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3523): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3523): selectionArgs: false
D/SettingsProvider( 3523): selectionArgs: 1002
,D/SecContentProvider( 3523): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3523): ret = -1
,D/SettingsProvider( 3523): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
D/SettingsProvider( 3523): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3523): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3523): selectionArgs: false
D/SettingsProvider( 3523): selectionArgs: 1002
D/SecContentProvider( 3523): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3523): ret = -1
,D/SettingsProvider( 3523): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
D/SettingsProvider( 3523): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3523): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3523): selectionArgs: false
W/InputMethodManagerService( 3523): Got RemoteException sending setActive(false) notification to pid 11750 uid 10589
D/SettingsProvider( 3523): selectionArgs: 1002
D/SecContentProvider( 3523): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 3523): ret = -1
D/SettingsProvider( 3523): name = bt_svcst_com.android.bluetooth.hid.HidDevService
D/SettingsProvider( 3523): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3523): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3523): selectionArgs: false
D/SettingsProvider( 3523): selectionArgs: 1002
,D/SecContentProvider( 3523): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3523): ret = -1
,D/ResourcesManager(11450): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(11450): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 3523): Killing 11488:com.android.calendar/u0a164 (adj 13): bgCount ##31
,I/Timeline( 6239): Timeline: Activity_idle id: android.os.BinderProxy@c224083 time:279318
,D/ResourcesManager(11450): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/AuthorizationBluetoothService( 4626): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/ActivityManager( 3523): mDVFSHelper.release()
,I/Timeline( 3523): Timeline: Activity_windows_visible id: ActivityRecord{f589b01 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t24} time:279330
,W/ResourceType( 3523): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/ResourcesManager(11450): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(11450): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,E/Zygote  (12908): MountEmulatedStorage()
E/Zygote  (12908): v2
I/libpersona(12908): KNOX_SDCARD checking this for 10063
I/libpersona(12908): KNOX_SDCARD not a persona
,D/ResourcesManager(11450): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,I/SELinux (12908): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,W/ResourcesManager(11450): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(11450): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11450): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11450): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,I/ActivityManager( 3523): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=12908 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/WifiStateMachine( 3523): skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,E/WifiStateMachine( 3523): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3523): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,I/SELinux (12908): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/PackageManager( 3523): delete codoeFile: 
E/SELinux (12908): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(11450): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
I/AASAUninstall( 3523):  com.test.thalitest not target!
,D/PackageManager( 3523): result of delete: 1{630012121}
,D/AndroidRuntime(12830): Shutting down VM
,D/ResourcesManager(11450): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(11450): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/TimaKeyStoreProvider(12908): TimaSignature is unavailable
,D/ActivityThread(12908): Added TimaKeyStore provider
,D/ResourcesManager(12908): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,D/ResourcesManager(11450): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/VRSetupWizardStub/PackageIntentReceiver(12908): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(12908): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(12908): packagename:com.test.thalitest
,D/ResourcesManager(11450): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/KLMS-2.4.521: (11993): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Jan 19 13:06:46 GMT+01:00 2016
,I/KLMS-2.4.521: (11993): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 3523): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3523): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,I/KLMS-2.4.521: (11993): KLMSIntentService(): onCreate()
,D/ResourcesManager(11450): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,I/KLMS-2.4.521: (11993): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (11993): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
I/KLMS-2.4.521: (11993): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,D/ResourcesManager(11450): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,I/KLMS-2.4.521: (11993): KLMSIntentService(): PACKAGE_REMOVED
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,I/KLMS-2.4.521: (11993): KLMSIntentService(): listeningToPackageRemoved().START
,E/Zygote  (12924): MountEmulatedStorage()
E/Zygote  (12924): v2
I/libpersona(12924): KNOX_SDCARD checking this for 10106
I/libpersona(12924): KNOX_SDCARD not a persona
,I/SELinux (12924): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(11450): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
I/KLMS-2.4.521: (11993): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
I/SELinux (12924): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3523): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=12924 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,E/SELinux (12924): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Books/Books.apk
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager(11450): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/TimaKeyStoreProvider(12924): TimaSignature is unavailable
,D/ActivityThread(12924): Added TimaKeyStore provider
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/RCPManager(12088):  in createShortcut() for packageName: com.test.thalitest userId0
,D/RCPManagerService( 3523):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3523): queryAllProviders():  providerCallBack is not register for 0
,D/ResourcesManager(11450): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(11450): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
E/Zygote  (12939): MountEmulatedStorage()
I/libpersona(12939): KNOX_SDCARD checking this for 10050
E/Zygote  (12939): v2
I/libpersona(12939): KNOX_SDCARD not a persona
I/SELinux (12939): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,I/SELinux (12939): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
E/SELinux (12939): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=12939 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(11450): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,W/ResourcesManager( 3523): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3523): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3523): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3523): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Videos/Videos.apk
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/ResourcesManager(11450): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(12939): TimaSignature is unavailable
D/ResourcesManager(11450): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ActivityThread(12939): Added TimaKeyStore provider
I/libpersona(12954): KNOX_SDCARD checking this for 10101
E/Zygote  (12954): MountEmulatedStorage()
I/libpersona(12954): KNOX_SDCARD not a persona
E/Zygote  (12954): v2
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,I/SELinux (12954): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3523): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=12954 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
I/SELinux (12954): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/ResourcesManager( 3523): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
E/SELinux (12954): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/RCPManagerService( 3523): PackageReceiver onReceive()
D/ResourcesManager(11450): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
,D/ResourcesManager(12924): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
I/HarmonyEASService( 3523): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 3523): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/BackupManagerService( 3523): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 3523): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3523): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3523): uID is 10589
V/EnterpriseBillingPolicy( 3523): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3523): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 3523): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3523): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3523): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3523): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 3523): getBillingProfileForVpnEngine - end - null
,I/KLMS-2.4.521: (11993): KLMSIntentService(): listeningToPackageRemoved().END
,D/elm:14491(12924): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14491(12924): ELMEngine.ELMEngine( context ).
D/elm:14491(12924): MDMBridge.setEnterpriseBridge()
D/ResourcesManager(11450): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TimaKeyStoreProvider(12954): TimaSignature is unavailable
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
D/ActivityThread(12954): Added TimaKeyStore provider
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/ResourcesManager(11450): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(12939): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,E/Zygote  (12970): MountEmulatedStorage()
E/Zygote  (12970): v2
I/libpersona(12970): KNOX_SDCARD checking this for 10183
I/libpersona(12970): KNOX_SDCARD not a persona
,I/SELinux (12970): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12970): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12970): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=12970 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
,W/ResourcesManager(12939): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12939): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12939): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12939): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(12939): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager(12939): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/ResourcesManager(11450): creating new AssetManager and set to /system/app/FBInstagram_stub/FBInstagram_stub.apk
W/ResourcesManager(12939): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12939): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/SmartBondingService( 3523): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3523): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
W/SLocation( 3523): No Active Data Connection
,D/UsbSettingsManager( 3523): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 3523): onPackageRemoved : com.test.thalitest
,D/GpsLocationProvider( 3523): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/elm:14491(12924): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/SLocation( 3523): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
D/SmartBondingService( 3523): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,D/KnoxTimeoutHandler( 3523): handleActiveUserChange for user 0
,D/SmartBondingService( 3523): getNetworkEnabled : wifi : false mobile : false
,D/ResourcesManager(11450): creating new AssetManager and set to /system/app/FBMessenger_stub/FBMessenger_stub.apk
,D/SmartBondingService( 3523): getNetworkEnabled : wifi : false mobile : false
,I/KLMS-2.4.521: (11993): KLMSIntentService(): onDestroy()
,D/elm:14491(12924): ElmAgentService : onCreate()
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(12970): TimaSignature is unavailable
,D/elm:14491(12924): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/ActivityThread(12970): Added TimaKeyStore provider
,D/elm:14491(12924): MainReceiver.listeningToPackageRemoved()
,D/elm:14491(12924): MDMBridge.getInstance()
D/elm:14491(12924): MDMBridge.getAllLicenseInfoFromSDK()
,D/ResourcesManager(11450): creating new AssetManager and set to /system/app/FBPagesManager_stub/FBPagesManager_stub.apk
,D/ResourcesManager(12954): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/elm:14491(12924): MDMBridge.getAllLicenseInfoFromSDK()
,E/Zygote  (12987): MountEmulatedStorage()
I/libpersona(12987): KNOX_SDCARD checking this for 10019
E/Zygote  (12987): v2
I/libpersona(12987): KNOX_SDCARD not a persona
I/SELinux (12987): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12987): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/ResourcesManager(11450): creating new AssetManager and set to /system/app/Maps/Maps.apk
E/SELinux (12987): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=12987 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,D/ResourcesManager(11450): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/ActivityManager( 3523): Killing 10765:com.android.defcontainer/u0a5 (adj 13): bgCount ##31
,D/TaskPersister( 3523): removeObsoleteFile: deleting file=26_task.xml
,D/TaskPersister( 3523): removeObsoleteFile: deleting file=24_task.xml
,I/ApplicationPolicy( 3523): updateDataUsageMap
,I/ApplicationPolicy( 3523): updateDataUsageMap  idList is null 
,D/StatusBar( 3692): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 3692): isKioskContainerExistOnDevice
,D/PersonaManager( 3692): isKioskContainerExistOnDevice
D/TimaKeyStoreProvider(12987): TimaSignature is unavailable
,I/PhoneStatusBar( 3692): Icon Only
D/ActivityThread(12987): Added TimaKeyStore provider
,I/StatusBar( 3692): Icon Only
D/PanelView( 3692): There is/are notification(s) 
,D/ResourcesManager(11450): creating new AssetManager and set to /system/app/PENUP/PENUP.apk
D/PanelView( 3692): There is/are notification(s) 
,D/PersonaManager( 3692): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3692): Icon Only
I/StatusBar( 3692): Icon Only
,D/PanelView( 3692): There is/are notification(s) 
,E/SQLiteLog(12939): (28) failed to open "/data/data/com.sec.android.gallery3d/databases/picasa.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(12939): Failed to open database '/data/data/com.sec.android.gallery3d/databases/picasa.db'.
E/SQLiteDatabase(12939): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12939): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12939): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12939): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12939): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12939): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12939): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12939): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12939): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12939): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12939): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12939): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12939): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12939): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12939): 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider$SyncContext.<init>(PicasaContentProvider.java:911)
E/SQLiteDatabase(12939): 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider.attachInfo(PicasaContentProvider.java:103)
E/SQLiteDatabase(12939): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/SQLiteDatabase(12939): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/SQLiteDatabase(12939): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/SQLiteDatabase(12939): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12939): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12939): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12939): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12939): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12939): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12939): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12939): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12939): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/ResourcesManager(11450): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/elm:14491(12924): ElmAgentService : onDestroy().
,I/ActivityManager( 3523): Killing 11618:com.android.vending/u0a31 (adj 13): bgCount ##31
,D/ResourcesManager(12970): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,D/ResourcesManager(11450): creating new AssetManager and set to /system/app/SecCalculator2/SecCalculator2.apk
,D/DocsApplication(12954): Installing DEX configuration.
D/ResourcesManager(12987): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
D/DexInstaller(12954): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,E/SharedPreferencesImpl(12939): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
I/PackageInfoHelper(12954): Provided clientMode=RELEASE, packageInfo=PackageInfo{36701536 com.google.android.apps.docs}
,D/ResourcesManager(11450): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/TAG     (12954): onCreate()
D/PackageManager( 3523): findPreferredActivity: No PreferredActivities set
,D/CrossAppStateProvider(12954): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,D/ResourcesManager(11450): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/NearbySource(12939): Nearby Source Create!
D/NearbyContext(12939): Nearby Context Create!
,E/SQLiteLog(12970): (28) failed to open "/data/data/com.samsung.android.provider.shootingmodeprovider/databases/shootingmodemanager.db" with flag (131138) and mode_t (0) due to error (30)
,D/com.sec.android.service.health.upgrade.UninstallReceiver(12987): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver(12987): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver(12987): onReceive() : package name is not s health. Return !!!
,E/SQLiteDatabase(12970): Failed to open database '/data/data/com.samsung.android.provider.shootingmodeprovider/databases/shootingmodemanager.db'.
E/SQLiteDatabase(12970): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12970): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12970): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12970): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12970): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12970): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12970): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12970): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12970): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12970): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12970): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12970): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12970): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12970): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12970): 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.initializeSQLiteStatements(ShootingModeProvider.java:269)
E/SQLiteDatabase(12970): 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.onCreate(ShootingModeProvider.java:232)
E/SQLiteDatabase(12970): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/SQLiteDatabase(12970): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/SQLiteDatabase(12970): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/SQLiteDatabase(12970): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/SQLiteDatabase(12970): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/SQLiteDatabase(12970): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12970): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12970): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12970): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12970): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12970): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12970): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12970): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12970): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime(12970): Shutting down VM
,E/AndroidRuntime(12970): FATAL EXCEPTION: main
E/AndroidRuntime(12970): Process: com.samsung.android.provider.shootingmodeprovider, PID: 12970
E/AndroidRuntime(12970): java.lang.RuntimeException: Unable to get provider com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12970): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5564)
E/AndroidRuntime(12970): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/AndroidRuntime(12970): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/AndroidRuntime(12970): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/AndroidRuntime(12970): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/AndroidRuntime(12970): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(12970): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(12970): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(12970): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(12970): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(12970): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(12970): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(12970): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12970): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12970): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(12970): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(12970): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12970): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12970): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12970): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(12970): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(12970): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(12970): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(12970): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12970): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(12970): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(12970): 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.initializeSQLiteStatements(ShootingModeProvider.java:269)
E/AndroidRuntime(12970): 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.onCreate(ShootingModeProvider.java:232)
E/AndroidRuntime(12970): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/AndroidRuntime(12970): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/AndroidRuntime(12970): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/AndroidRuntime(12970): 	... 11 more
,D/LocationWidgetApplication(11450): getLastUiLocationId() : mLastUiLocationId = -100
D/PanelView( 3692): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
V/ApplicationPolicy( 3523): isApplicationStateBlocked userId 0 pkgname com.samsung.android.provider.shootingmodeprovider
D/ResourcesManager(11450): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
D/UsbHostManager( 3523): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
D/UsbHostManager( 3523): displayNotification : [02h,02h,01h]
D/UsbHostManager( 3523): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
D/UsbHostManager( 3523): displayNotification : [0ah,00h,00h]
D/UsbHostManager( 3523): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3523): displayNotification : [02h,0dh,00h]
E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
D/UsbHostManager( 3523): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3523): displayNotification : [0ah,00h,01h]
W/ContextImpl(12939): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource(12939): Samsung link source created
D/UsbHostManager( 3523): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
I/PCWCLIENTTRACE_PushUtil(11879): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11879): sales region : global
I/PCWCLIENTTRACE_PushUtil(11879): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11879): [onReceive] - android.intent.action.PACKAGE_REMOVED
D/UsbHostManager( 3523): displayNotification : [09h,00h,00h]
D/UsbHostManager( 3523): usbDeviceRemoved : /dev/bus/usb/001/003
E/UsbHostManager( 3523): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
D/UsbSettingsManager( 3523): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
D/ResourcesManager(11450): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
I/ActivityManager( 3523): Killing 12279:com.sec.android.provider.badge/u0a82 (adj 13): bgCount ##31
E/DropBoxManagerService( 3523): Can't write: system_app_crash
E/DropBoxManagerService( 3523): java.io.FileNotFoundException: /data/system/dropbox/drop199.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3523): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3523): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3523): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3523): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3523): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3523): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3523): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3523): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3523): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3523): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3523): 	... 5 more
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (13012): MountEmulatedStorage()
E/Zygote  (13012): v2
I/libpersona(13012): KNOX_SDCARD checking this for 10035
I/libpersona(13012): KNOX_SDCARD not a persona
I/SELinux (13012): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3523): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=13012 uid=10035 gids={50035, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
D/UsbHostManager( 3523): usbDeviceRemoved : /dev/bus/usb/001/001
E/UsbHostManager( 3523): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
I/SELinux (13012): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (13012): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/EventHub( 3523): Removing device '/dev/input/event10' due to inotify event
,I/art     ( 2884): Explicit concurrent mark sweep GC freed 8727(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.732ms total 48.049ms
,E/SQLiteLog(12939): (28) failed to open "/data/data/com.sec.android.gallery3d/databases/local.db" with flag (131138) and mode_t (0) due to error (30)
,I/art     ( 2884): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 875us total 28.133ms
,E/SQLiteDatabase(12939): Failed to open database '/data/data/com.sec.android.gallery3d/databases/local.db'.
E/SQLiteDatabase(12939): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12939): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12939): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12939): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12939): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12939): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12939): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12939): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12939): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12939): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12939): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12939): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12939): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12939): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(12939): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteDatabase(12939): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteDatabase(12939): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteDatabase(12939): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:202)
E/SQLiteDatabase(12939): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:194)
E/SQLiteDatabase(12939): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(12939): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(12939): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12939): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12939): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12939): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12939): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12939): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12939): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12939): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12939): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/SQLiteOpenHelper(12939): Couldn't open local.db for writing (will try read-only):
E/SQLiteOpenHelper(12939): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(12939): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(12939): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(12939): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(12939): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(12939): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(12939): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(12939): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(12939): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(12939): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(12939): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(12939): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(12939): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(12939): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(12939): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteOpenHelper(12939): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteOpenHelper(12939): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteOpenHelper(12939): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:202)
E/SQLiteOpenHelper(12939): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:194)
E/SQLiteOpenHelper(12939): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(12939): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(12939): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(12939): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(12939): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(12939): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(12939): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(12939): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(12939): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(12939): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(12939): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/TimaKeyStoreProvider(13012): TimaSignature is unavailable
,W/SQLiteOpenHelper(12939): Opened local.db in read-only mode
,D/ActivityThread(13012): Added TimaKeyStore provider
,D/WifiDisplayAdapter( 3523): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/art     ( 2884): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.228ms total 27.231ms
,D/ResourcesManager(11450): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,I/EventHub( 3523): Removing device '/dev/input/event7' due to inotify event
,E/Zygote  (13029): MountEmulatedStorage()
E/Zygote  (13029): v2
I/libpersona(13029): KNOX_SDCARD checking this for 10190
I/libpersona(13029): KNOX_SDCARD not a persona
,I/SELinux (13029): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (13029): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3523): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=13029 uid=10190 gids={50190, 9997} abi=armeabi-v7a
,E/SELinux (13029): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Killing 11940:com.sec.android.cloudagent/u0a2 (adj 13): bgCount ##31
,I/EventHub( 3523): Removing device '/dev/input/event8' due to inotify event
,D/TimaKeyStoreProvider(13029): TimaSignature is unavailable
,D/ActivityThread(13029): Added TimaKeyStore provider
,I/EventHub( 3523): Removing device '/dev/input/event9' due to inotify event
,I/Process (12970): Sending signal. PID: 12970 SIG: 9
,D/ContactProvider(12939): getAllContactInfoList Start
,D/ResourcesManager(13012): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,I/EventHub( 3523): Removing device '/dev/input/event11' due to inotify event
,D/WifiDisplayAdapter( 3523): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ResourcesManager(13029): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
,D/MtpClient(12939): onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/MtpClient(12939): ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
,I/EventHub( 3523): Removing device '/dev/input/event12' due to inotify event
,E/SharedPreferencesImpl(12939): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
,I/TapandpayWidget:TanpandpayAppWidgetProvider(13029): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(13029): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,I/TapandpayWidget:Utils(13029): Clear T&P info.
D/TapandpayWidget:TanpandpayAppWidgetProvider(13029): Widget is not attached.
,I/EventHub( 3523): Removing device '/dev/input/event13' due to inotify event
,E/Zygote  (13047): MountEmulatedStorage()
E/Zygote  (13047): v2
I/libpersona(13047): KNOX_SDCARD checking this for 10052
I/libpersona(13047): KNOX_SDCARD not a persona
,I/SELinux (13047): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3523): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=13047 uid=10052 gids={50052, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,I/SELinux (13047): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (13047): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Process com.samsung.android.provider.shootingmodeprovider (pid 12970)(adj 9) has died(213,1190)
,I/FeatureConfig(13012): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,I/EventHub( 3523): Removing device '/dev/input/event14' due to inotify event
,I/ActivityManager( 3523): Killing 11958:com.sec.android.diagmonagent/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(13047): TimaSignature is unavailable
,D/ActivityThread(13047): Added TimaKeyStore provider
,D/ResourcesManager(13012): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager(13012): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager(13012): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(13012): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(13012): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13012): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(13012): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager(13012): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,W/ResourcesManager(13012): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13012): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(13012): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 4760): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 4760): Clearing selected account for com.test.thalitest
,D/ResourcesManager(13012): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager(13012): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager(13012): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(13012): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager(13012): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(13012): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(13012): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13012): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager(13012): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager(13047): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager(13012): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(13047): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager(13047): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(13012): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(13012): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(13012): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13012): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,W/ResourcesManager(13047): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager(13047): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13047): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager(13047): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0

```
